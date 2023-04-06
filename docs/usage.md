# Usage

The Reset Windows Update Tool utilizes command-line functions to implement its processes. It is important to note that certain recovery functions may not be available on all versions of Windows, and the tool will detect such limitations to avoid potential errors.

To apply the necessary corrections, simply type in the number corresponding to the desired function and press "Enter".

> ### Contents
>
> [Run as administrator](#run-as-administrator) <br />
> [Command line](#command-line)

## Run as administrator

**User Account Control** (UAC) is a mandatory access control enforcement facility introduced with Microsoft's Windows Vista and Windows Server 2008 operating systems, with a more relaxed version also present in Windows 7, Windows Server 2008 R2, Windows 8, Windows Server 2012 and Windows 10. It aims to improve the security of Microsoft Windows by limiting application software to standard user privileges until an administrator authorizes an increase or elevation. In this way, only applications trusted by the user may receive administrative privileges, and malware should be kept from compromising the operating system. In other words, a user account may have administrator privileges assigned to it, but applications that the user runs do not inherit those privileges unless they are approved beforehand or the user explicitly authorizes it.

### How to run a program as an administrator

To run a program as an administrator, follow these steps:

1. Right-click the icon that you use to run the program, and then click **Run as administrator**.
2. When you are prompted for an administrator password or for a confirmation, type the administrator password, or click **Continue**.

For some program icons, the **Run as administrator** option is not available on the shortcut menu. For these program icons, follow these steps:

1. Right-click the icon that you use to run the program, and then click **Properties**. On the **Shortcut** tab, the **Target** box contains the location and the name of the program file.
2. Open the folder that contains the program file.
3. Right-click the program file, and then click **Run as administrator**. ![User Account Control permission](https://sawinternal.blob.core.windows.net/gds-images/support/kbgraphics/public/en-us/securityshield.jpg) If you are prompted for an administrator password or for a confirmation, type the password, or click **Continue**.

If you must run a program as an administrator, you may want to set up the program so that you automatically run it as an administrator. To do this, follow these steps:

1. Right-click the icon that you use to run the program, and then click **Properties**.
2. On the **Compatibility** tab, click to select the **Run this program as an administrator** check box, and then click **OK**.

The **Compatibility** tab is not available for some program icons. For these program icons, follow these steps:

1. Right-click the icon that you use to run the program, and then click **Properties**. On the **Shortcut** tab, the **Target** box contains the location and the name of the program file.
2. Open the folder that contains the program file.
3. Right-click the program file, and then click **Properties**.
4. On the **Compatibility** tab, click to select the **Run this program as an administrator** check box, and then click **OK**.

<div align="center">
	<img src="https://docs.wureset.com/assets/images/runas.gif" alt="contextual menu run as an admin">
</div>
<br />

For more information, see [references](https://support.microsoft.com/en-us/kb/922708)

## Command line

The Reset Windows Update Tool can be utilized through the command line using the following format:

```
$ WURESET [/reset][/search][/clean:{temp|regs|sock}][/sfc][/dism:{scan|check|repair|clean}]
```

Here, the various options that can be used with the tool are listed within brackets. These options include resetting the tool, searching for updates, cleaning temporary files or registry values, running System File Checker (SFC), and running DISM to scan, check, repair, or clean the system image.

**Parameter List**

<table border="0" cellpadding="4">
	<tr>
		<th>
			Parameter
		</th>
		<th>
			Description
		</th>
		<th>
			Abbreviation
		</th>
		<th>
			Example
		</th>
	</tr>
	<tr>
		<td>
			reset
		</td>
		<td>
			Reset the Windows Update Components.
		</td>
		<td>
		</td>
		<td>
			/reset <br />
			-reset
		</td>
	</tr>
	<tr>
		<td>
			search
		</td>
		<td>
			Search updates.
		</td>
		<td>
		</td>
		<td>
			/search <br />
			-search
		</td>
	</tr>
	<tr>
		<td>
			clean
		</td>
		<td>
			Clean options.
		</td>
		<td>
		</td>
		<td>
			/clean:temp <br />
			/clean:regs:temp <br />
			-clean:temp <br />
			-clean:sock
		</td>
	</tr>
	<tr>
		<td>
			sfc
		</td>
		<td>
			Scans all protected system files.
		</td>
		<td>
		</td>
		<td>
			/sfc <br />
			-sfc
		</td>
	</tr>
	<tr>
		<td>
			dism
		</td>
		<td>
			Dism options.
		</td>
		<td>
		</td>
		<td>
			/dism:scan:repair:clean <br />
			-dism:check:repair
		</td>
	</tr>
	<tr>
		<td>
			help
		</td>
		<td>
			Displays a help message.
		</td>
		<td>
			<b>h</b> or <b>?</b>
		</td>
		<td>
			/help <br />
			/h <br />
			/? <br />
			-help <br />
			-h <br />
			-?
		</td>
	</tr>
	<tr>
		<td>
			version
		</td>
		<td>
			Displays a version message.
		</td>
		<td>
			<b>v</b>
		</td>
		<td>
			/version <br />
			/v <br />
			-version <br />
			-v
		</td>
	</tr>
</table>

**Sample usage:**

<div>
	<img src="https://docs.wureset.com/assets/images/commands.gif" alt="example of command line">
</div>
<br />

For check version

<div>
	<img src="https://docs.wureset.com/assets/images/version.gif" alt="get version with command line">
</div>
<br />
