<!---
  samplefwlink: https://go.microsoft.com/fwlink/?linkid=860459
--->

# Windows 10 IoT Core samples

This repo contains the samples that demonstrate the usage patterns for the Microsoft Windows 10 IoT Core operating system. These code samples were created with templates available in Visual Studio, and are designed to run on devices that run Windows 10 IoT Core.

> **Note:** If you are unfamiliar with Git and GitHub, you can download the entire collection as a 
> [ZIP file](../../archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info, see [Get Started](https://go.microsoft.com/fwlink/?linkid=860461). 

## Windows 10 IoT Core development

These samples require Visual Studio 2017 to build and Windows 10 IoT Core to execute.  The setup and installation steps are different based on what hardware device you have.

   [Get a free copy of Visual Studio 2017 Community Edition](http://go.microsoft.com/fwlink/p/?LinkID=280676)

Additionally, to stay on top of the latest updates to Windows and the development tools, become a Windows Insider by joining the Windows Insider Program.

   [Become a Windows Insider](https://insider.windows.com/)

## Using the samples

The easiest way to use these samples without using Git is to download the zip file containing the current version (using the following link or by clicking the "Download ZIP" button on the repo page). You can then unzip the entire archive and use the samples in Visual Studio 2017.

   [Download the samples ZIP](../../archive/master.zip)

   **Notes:** 
   * Before you unzip the archive, right-click it, select **Properties**, and then select **Unblock**.
   * Be sure to unzip the entire archive, and not just individual samples. The samples all depend on the SharedContent folder in the archive.   
   * In Visual Studio 2017, the platform target defaults to ARM, so be sure to change that to x64 or x86 if you want to test on a non-ARM device. 
   
The samples use Linked files in Visual Studio to reduce duplication of common files, including sample template files and image assets. These common files are stored in the SharedContent folder at the root of the repository, and are referred to in the project files using links.

**Reminder:** If you unzip individual samples, they will not build due to references to other portions of the ZIP file that were not unzipped. You must unzip the entire archive if you intend to build the samples.

For more info about the programming models, platforms, languages, and APIs demonstrated in these samples, please refer to the guidance, tutorials, and reference topics provided in the Windows 10 documentation available in the [Windows Developer Center](http://go.microsoft.com/fwlink/p/?LinkID=532421). These samples are provided as-is in order to indicate or demonstrate the functionality of the programming models and feature APIs for Windows.

## Contributions

These samples are direct from the feature teams and we welcome your input on issues and suggestions for new samples. If you would like to see new coverage or have feedback, please consider contributing. You can edit the existing content, add new content, or simply create new issues. We’ll take a look at your suggestions and will work together to incorporate them into the docs.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## See also

For additional Windows samples, see [Windows on GitHub](http://microsoft.github.io/windows/). 

## Samples by category

### Devices, sensors and samples that involve wiring

<table>
 <tr>
  <td><a href="Samples/AppServiceBlinky">AppServiceBlinky</a></td>
  <td><a href="Samples/DigitalSign">DigitalSign</a></td>
  <td><a href="Samples/HelloBlinky">HelloBlinky</a></td>
 </tr>
 </tr>
 <tr>
  <td><a href="Samples/HelloBlinkyBackground">HelloBlinkyBackground</a></td>
  <td><a href="Samples/NFCForIoT">NFCForIoT</a></td>
  <td><a href="Samples/PotentiometerSensor">PotentiometerSensor</a></td>
 </tr>
 <tr>
  <td><a href="Samples/PushButton">PushButton</a></td>
  <td><a href="Samples/RGBLED">RGBLED</a></td>
  <td><a href="Samples/Accelerometer">Accelerometer</a></td>
 </tr>
 <tr>
  <td><a href="Samples/SPIDisplay">SPIDisplay</a></td>
  <td><a href="Samples/TempForceSensor">TempForceSensor</a></td>
  <td><a href="Samples/VideoCaptureSample">VideoCaptureSample</a></td>
 </tr>
  <tr>
  <td><a href="Samples/I2CCompass">I2CCompass</a></td>
  <td><a href="Samples/ContainerWebSocket">ContainerWebSocket</a></td>
  <td><a href="Samples/GpioOneWire">GpioOneWire</a></td>
 </tr>
</table>

### Samples that demonstrate Universal Windows Application Features 

<table>
 <tr>
  <td><a href="Samples/AppServiceSharedNotepad">AppServiceSharedNotepad</a></td>
  <td><a href="Samples/CompanionApp">CompanionApp</a></td>
  <td><a href="Samples/ExternalProcessLauncher">ExternalProcessLauncher</a></td>
 </tr>
 <tr>
  <td><a href="Samples/ForegroundAppWithBackgroundApp">ForegroundAppWithBackgroundApp</a></td>
  <td><a href="Samples/HelloBlinkyBackground">HelloBlinkyBackground</a></td>
  <td><a href="Samples/HelloWorld">HelloWorld</a></td>
 </tr>
 <tr>
  <td><a href="Samples/IotBrowser">IotBrowser</a></td>
  <td><a href="Samples/IoTCoreDefaultApp">IoTCoreDefaultApp</a></td>
  <td><a href="Samples/IoTCoreMediaPlayer">IoTCoreMediaPlayer</a></td>
 </tr>
<tr>
  <td><a href="Samples/IotOnboarding">IotOnboarding</a></td>
  <td></td>
  <td></td>
 </tr>
</table>

### Samples that utilize Microsoft Azure features

<table>
 <tr>
  <td><a href="Samples/IoTConnector">IoTConnector</a></td>
  <td><a href="Samples/SpeechTranslator">SpeechTranslator</a></td>
  <td><a href="Samples/WeatherStation">WeatherStation</a></td>
 </tr>
</table>

### Samples that involve device drivers, services, or realtime processing

<table>
 <tr>
  <td><a href="Samples/IoTCoreService">IoTCoreService</a></td>
  <td><a href="Samples/NTServiceRpc">NTServiceRpc</a></td>
  <td><a href="Samples/SerialUART">SerialUART</a></td>
 </tr>
 <tr>
  <td><a href="Samples/ShiftRegister">ShiftRegister</a></td>
  <td><a href="Samples/MemoryStatus">MemoryStatus</a></td>
  <td></td>
 </tr>
</table>
