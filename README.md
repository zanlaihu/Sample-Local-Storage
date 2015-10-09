Local Storage
===================
<a href="https://platform.telerik.com/#appbuilder/clone/https%3A%2F%2Fgithub.com%2FIcenium%2Fsample-localstorage" target="_blank"><img src="http://docs.telerik.com/platform/samples/images/try-in-appbuilder.png" alt="Try in AppBuilder" title="Try in AppBuilder" /></a>  <a href="https://github.com/Icenium/sample-localstorage" target="_blank"><img style="padding-left:20px" src="http://docs.telerik.com/platform/samples/images/get-github.png" alt="Get from GitHub" title="Get from GitHub"></a>

<a id="top"></a>
* [Overview](#overview)
* [Showcased APIs](#showcased-apis)
* [Screenshots](#screenshots)
* [Test the Sample](#test-the-sample)
* [Limitations](#limitations)

This sample shows you how to use the Local Storage API to access the local storage of a device and create, search for or delete items.

> *Supported mobile platforms:* iOS, Android, Windows Phone
>
> *Developed with:* Apache Cordova 3.7.0

[Back to Top](#top)

# Showcased APIs

This sample shows how to use the following methods of the [Local Storage API][Local Storage API].

* **getItem():** Returns the value associated with the key.
* **setItem():** Saves the specified key-value pair.
* **removeItem():** Removes the item associated with the key argument.
* **clear():** Removes all items saved in localStorage.

[Back to Top](#top)

# Screenshots

Platform | Home
---|---
All | ![](https://raw.githubusercontent.com/Icenium/sample-localstorage/master/screenshots/home.png)

[Back to Top](#top)

# Test the Sample

Apart from exploring the sample code base in GitHub, you can also clone and run the sample in your preferred AppBuilder client.

## In-Browser

With the AppBuilder in-browser client, you can develop hybrid and NativeScript cross-platform mobile apps from your browser. You can use the in-browser client at [https://platform.telerik.com](https://platform.telerik.com).

### Clone the sample

1. Click **Try in AppBuilder** above.
1. Provide your login credentials, if prompted.

### Run the sample

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Deploy on device via QR code.][QR code]

[Back to Top](#top)

## Windows

With the AppBuilder Windows client, you can develop hybrid and NativeScript cross-platform mobile apps from your Windows desktop. You can download and install the Windows client from [http://www.telerik.com/appbuilder/windows-client](http://www.telerik.com/appbuilder/windows-client).

### Clone the sample

1. Verify that the AppBuilder Windows client is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. In the dashboard, click **Samples** and select **Hybrid**.
1. From the **Workspace** drop-down menu, select the workspace in which you want to develop your application.
1. Select **Core APIs**.
1. Select **Localstorage**.
1. (Optional) Rename the project.
1. Click **Clone**.

### Run the sample

With the AppBuilder Windows client, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## Visual Studio

With the AppBuilder extension for Visual Studio, you can develop hybrid and NativeScript cross-platform mobile apps from Microsoft Visual Studio. You can download and install the extension from [http://www.telerik.com/appbuilder/visual-studio-extension](http://www.telerik.com/appbuilder/visual-studio-extension).

### Clone the sample

1. Verify that the AppBuilder extension for Visual Studio is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. Select **AppBuilder** &#8594; **Get Sample**.
1. Select **Hybrid**.
1. Select **Core APIs**.
1. Select **Localstorage**.
1. (Optional) Rename the project.
1. Click **Get**.

The extension for Visual Studio copies the sample files locally. The extension creates a new solution and project and loads them.

### Run the sample

With the AppBuilder extension for Visual Studio, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## CLI

With the AppBuilder command-line interface, you can develop hybrid and NativeScript cross-platform mobile apps from the command line. You can learn how to add the AppBuilder commands to your command line from [http://www.telerik.com/appbuilder/command-line-interface](http://www.telerik.com/appbuilder/command-line-interface).

### Clone the sample

1. Verify that a command prompt is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. To list the available samples, run the following command.

	```bash
	appbuilder sample
	```
1. Run the clone command for the sample as listed by `appbuilder sample`.
	
	```bash
	appbuilder sample clone localstorage
	```

The AppBuilder command-line interface shows the following message: `Successfully initialized project in the folder!`

### Run the sample

With the AppBuilder command-line interface, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

# Limitations

* Using `localStorage` for large data loads and complex objects might exhaust the memory of the device.
* The device simulator preserves the local storage. To start with clear local storage, you need to implement a cleanup programmatically or manually delete the contents of the `Telerik.BlackDragon.Client.Modules.WebBrowser-*` folder located in `%LOCALAPPDATA%\Telerik\BlackDragon\Cache` before running the device simulator.

[Back to Top](#top)

[device simulator]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-apps-in-simulator/launch-simulator
[companion]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/run-companion/using-appbuilder-companion-app
[QR code]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/deploy-remote
[USB deploy]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/running-on-connected-devices/deploy-connected
[emulators]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-in-emulators/native-emulators
[Local Storage API]: http://cordova.apache.org/docs/en/4.0.0/cordova/storage/storage.html#link-1