<p style="text-align:center" ><img src="../img/reachview/settings/settings.png" style="width: 800px;" /></p>

## ReachView updates

### App version  
Every time you power up Reach in a Wi-Fi network, it checks for new ReachView update and notify you accordingly.

!!! note ""
    The update check is only done one time during the boot process. If you want to force new version check, please proceed to ReachView Updater. It is available on port 5000, for example, `http://reach.local:5000`. The Updater automatically scans Emlid update servers when you open it. [Learn more about ReachView updater.](../common/reachview/updater.md)

## System utilities

### Night mode 
Night mode allows you to turn off the LEDs until the next reboot of the device. 

### Bottom connector settings
Enables automatic boot and shutdown using the bottom connector on Reach. Perfect for integrating the receiver with cars or tractors.

### System report
The tool is used to facilitate issues reports. There are two kinds of system reports:

* Simple system report (in plain text format)
* Full system report (in a zip archive)

The former is for the forum and makes it easy to share settings, network state, and app version. The latter is for harder cases and contains system logs and technical details of your device.

!!! note "Getting system report"
	<p style="text-align:center"><img src="../img/reachview/settings/system-report.gif" style="width: 800px;" /></p>

### Sound notifications

Enables sound notifications on Reach and allows to adjust the volume. Reach will warn you once it gets or loses the fix solution status.

### Reset settings to default  
Click *Reset setting to default* button to return all settings to factory configuration. Only logs and wireless settings are preserved. If you would like to perform a complete factory reset and wipe all your data you can [reflash firmware image](../common/reachview/firmware-reflashing.md).

## General settings

### Reach and hotspot name

Reach name can be changed in order to distinguish between multiple devices. A very common pattern is to name devices according to their base or rover function. A device name is a base for hotspot name and local network name. The default name is **reach**, changing it will also affect local name `http://reach.local` and hotspot name `reach:xx:xx`.

### Logging settings
Specify how ReachView will handle full memory behavior here, it can either stop logging or override old logs in favour of new ones. In most cases “rolling logs” is recommended.

### Log split period
A new log file will be created every N hours while preserving the previous log as well. This setting allows you to control the size of the files that you work with.
