## Intro

In this tutorial, we will walk you through the following steps:

* Install the ReachView app
* Connect to Reach RS/RS+
* Perform firmware update
* Set up base and rover connection

To do that, you’ll need Reach RS/RS+ itself, a Wi-Fi network with Internet access and a smartphone or PC.


## Video guide

The video below covers the process of the first update.

<center>

???+ note "Reach RS/RS+ has the ReachView app sticker on top"
    <div style="text-align: center;"><iframe title="Emlid manuals" width="560" height="315" src="https://www.youtube.com/embed/fIY__hNjcNI" allowfullscreen></iframe></div>

</center>

If your Reach RS/RS+ came with the QR code sticker on top, it supports the mobile ReachView app. Get it from the App Store or Google Play before updating.

<center>

|Download links||
|:-------------:|:----------:|
|[Google Play](https://play.google.com/store/apps/details?id=com.reachview)|[App Store](https://itunes.apple.com/us/app/reachview/id1295196887?mt=8)|

</center>

If there was no sticker, the unit might have an older firmware version. Please watch this video instead.

??? note "Reach RS/RS+ has no sticker on top"
    <div style="text-align: center;"><iframe title="Emlid manuals" width="560" height="315" src="https://www.youtube.com/embed/HCOqtSUumow" allowfullscreen></iframe></div>

!!! note ""
    If you encounter any issues performing these steps, we will be happy to help at our [**community forum**](http://community.emlid.com/)


## Text guide

### Powering up

Hold the power button for 3 seconds to turn Reach RS/RS+ on. After about 30 seconds the blue LED will stop blinking. Reach RS/RS+ is now broadcasting Wi-Fi.

<div style="text-align: center;"><img src="../img/quickstart/first-setup/running-hotspot.png" style="width: 350px;"></div>

### Connecting to Reach RS/RS+

* Open a list of Wi-Fi networks on your smartphone/PC

* Connect to a network named **reach:xx:xx**

* Type network password: **emlidreach**


### Setting up Wi-Fi

??? note "Using Reach with iOS/Android device"

    1. Get the ReachView app from [Google Play](https://play.google.com/store/apps/details?id=com.reachview) or [App Store](https://itunes.apple.com/us/app/reachview/id1295196887?mt=8)
    2. Open the app and choose Reach from the list
    4. Tap the *plus* button and enter your Wi-Fi network name, security type, and password
    5. Tap *Save* button
    6. Tap on the added network and then *Connect*

??? note "Using Reach with a web browser from any device"

    1. Launch a web browser (we recommend using Chrome or Mozilla)
    2. Go to 192.168.42.1
    3. Tap the *plus* button and enter your Wi-Fi network name, security type, and password
    4. Tap *Save* button
    5. Tap on the added network and then *Connect*

Reach RS/RS+ will stop broadcasting Wi-Fi and connect to your network. 

The blue LED will blink rapidly while scanning for networks. Once Reach connects to Wi-Fi, the LED will start blinking slowly. 

<div style="text-align: center;"><img src="../img/quickstart/first-setup/running-client.gif" style="width: 350px;"></div>

!!! note ""
    If your device did not connect to a Wi-Fi network, it will switch back to a hotspot mode.
    In that case, repeat the steps and double check your network name and password. 


### Accessing Reach RS/RS+ device in a network

!!! danger ""
    Make sure that your smartphone/PC has connected to the same Wi-Fi network as Reach.

??? note "Using Reach with iOS/Android device"

    1. Open ReachView app
    2. Refresh the list of devices
    3. Tap **reach**


??? note "Using Reach with PC"

    After connecting the Reach device to an existing Wi-Fi network, you will need to identify its IP.

    For this you can use:

    * "**Fing**" app for [iOS](https://goo.gl/Ho0qB) or [Android](https://goo.gl/7Wuwu)

    * ["**Nmap**"](https://nmap.org/) on Linux/OS X

    * ["**Zenmap**"](https://nmap.org/zenmap/) on Windows

    <div style="text-align: center;"><img src="../img/quickstart/first-setup/fing.png" style="width: 500px;"></div>

    * Reach will show up as "**Murata Manufacturing**" or "**AMPAK Technology**" device in these apps

    * Put Reach IP in the address bar and go

    Read more on resolving IP addresses in the [ReachView section](../common/reachview/index.md#resolving-ip).


### Updating ReachView

After connecting to Reach RS/RS+, you will see ReachView Updater again. Wait until it checks for the latest updates.

* If there is an update, press *Update ReachView* button and wait. This process will take a few minutes

* When it’s done tap *Reboot and go to the app* button to reboot Reach RS/RS+

* Wait for the blue LED to start blinking slowly, showing that Reach RS has joined your Wi-Fi network again

* Press *Reboot and go to the app* button and wait while device reboots

If you use ReachView app, swipe right to get back to the list of devices, refresh the list and tap **reach**. As for the web browser, just refresh the page with ReachView. You’ll see the filling EMLID logo indicating the loading process of ReachView.

Your Reach RS/RS+ is ready for work. Do the same with all other units.

[Now you can set up Base and Rover connection by following instruction from our guide.](base-rover-setup.md)
