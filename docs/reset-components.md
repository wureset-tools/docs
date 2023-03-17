# Reset Components

If you are experiencing persistent issues with Windows Update, it may be necessary to reset the Windows Update Components to their default settings. This tool is specifically designed to address issues related to these components.

> ### Contents
>
> [Reset Windows Update Components](#reset-windows-update-components) <br />
> [The Windows Update service could not be stopped](#the-windows-update-service-could-not-be-stopped)

## Reset Windows Update Components

Before proceeding, it is important to create a backup of the registry in case anything goes wrong during the process.

To reset Windows Update Components to their default values, select the "Reset Windows Update Components" option. This will stop Windows Update services and clean the components, restoring them to their initial settings.

The tool will start resetting the components automatically, and the process should be completed in a few minutes.

Once completed, it is recommended to install the latest Windows Update Agent from the following link: [https://support.microsoft.com/en-us/kb/949104](https://support.microsoft.com/en-us/kb/949104).

Finally, restart your PC to ensure that the changes have been saved.

## The Windows Update service could not be stopped

If the Windows Update Service won't stop, try running this tool in Safe Mode.

<div align="center">
	<img src="https://docs.wureset.online/assets/images/failed.png" alt="failed command">
</div>
<br />

To access Safe Mode, you can get into the Windows recovery environment by holding down the Shift key while clicking Restart. This will take you to the Advanced Startup Options menu, where you can select Safe Mode.

If you're still experiencing the error, it's possible that your Windows installation is in poor condition and requires repair or reinstallation.
