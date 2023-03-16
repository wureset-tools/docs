# Home

<div align="center">
	<a href="https://wureset.com/">
		<img src="assets/images/logo.png" alt="Logo" height="300" width="300">
	</a>
</div>
<br />

This tool has been specifically developed to provide support for system repair options. It is designed to reset the Windows Update Components, delete temporary files, detect and repair any corruptions with the Windows System image, scan all protected system files and replace any corrupted files, change invalid values in the Windows Registry, reset Winsock settings, and more.

The Reset Windows Update Components tool can be operated via command-line and requires basic system requirements such as a compatible operating system and elevated privileges.

This document serves as a guide to describe the correct process sequences for utilizing the Reset Windows Update Tool.

> ### Contents
>
> [Requirements](#requirements) <br />
> [Glossary](#glossary) <br />
> [Reference](#reference) <br />
> [License](#license)

## Requirements

This tool is fully compatible with Windows 10 or any higher version of the operating system.

Upon running the Reset Windows Update Tool, the tool will automatically detect the version or build of the operating system, which in turn determines the name and family of the system.

In the event that the operating system is not compatible with the tool, an error message will be displayed and the tool will be closed.

## Glossary

<dl>
<dt>DISM</dt>
<dd>Deployment Image Servicing and Management is a command-line tool that can be used to service a Windows image.</dd>
<dt>Fix It</dt>
<dd>diagnostic program to detect problems of Windows.</dd>
<dt>Registry</dt>
<dd>is a database that stores settings for the operating system.</dd>
<dt>Restore point</dt>
<dd>is a representation of a stored state of your computer's system files.</dd>
<dt>SFC</dt>
<dd>System File Checker is a utility that allows users to scan for corruptions.</dd>
<dt>Winsock</dt>
<dd>Windows Sockets API is a technical specification that defines how Windows network software should access network.</dd>
</dl>

## Reference

How do I reset Windows Update components?: [https://support.microsoft.com/en-us/kb/971058](https://support.microsoft.com/en-us/kb/971058).

Use the System File Checker tool to repair missing or corrupted system files: [https://support.microsoft.com/en-us/kb/929833](https://support.microsoft.com/en-us/kb/929833).

Fix Windows Update errors by using the DISM or System Update Readiness tool: [https://support.microsoft.com/en-us/kb/947821](https://support.microsoft.com/en-us/kb/947821).

## License

Reset Windows Update Tool is licensed under the MS-PL License - see the [Microsoft Public License](https://opensource.org/licenses/MS-PL) for details.
