# Setting Up AstroWarp with GL.iNet Routers: Game Streaming

Game streaming allows you to play high-performance games on any device remotely, whether on a weaker PC, laptop, or mobile device. You can set up remote desktop streaming for games using [Windows Remote Desktop](https://support.microsoft.com/en-us/windows/how-to-use-remote-desktop-5fe128d5-8fb1-7a23-3b8a-41e636865e8c){target="_blank"}, or a dedicated game streaming app.

## Using Windows Remote Desktop

**Step1:** Select a plan to create the network.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/10.jpg){class="glboxshadow"}

**Step2:** Set a name for your network, such as "Game_Streaming".

![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/2.png){class="glboxshadow"}

**Step3:** Integrate the router hosting your gaming server into the network. The Free Plan allows you to do this at no additional cost.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/3.png){class="glboxshadow"}

**Step4:** Once the network is created, make your gaming host accessible as a resource and add it to the current AstroWarp network.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/4.png){class="glboxshadow"}

![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/5.png){class="glboxshadow"}

**Step5:** Add the devices you'll use to play games remotely, such as phones, tablets, or other devices, into the network as clients.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/6.png){class="glboxshadow"}

## Using Game Streaming App

While Windows Remote Desktop is effective for work-related tasks, using a dedicated game streaming app can offer significantly better performance for gaming. Two recommended options are **Sunshine** and **GeForce Experience**.

### Host Gaming PC Requirements

**For Sunshine**

* **GPU:** Any modern GPU from AMD, NVIDIA, or Intel.
* **Operating System:**
    * Windows 10 or 11 (**Windows 7 and 8 are not supported**).
    * macOS 12 and newer (**experimental**).
    * Linux: Debian 11, Ubuntu 22.04, Fedora 38, or newer.

**For GeForce Experience**

* **Operating System:** Windows 10 or 11 (**Windows 7 and 8 may be supported**).
* **GPU:** NVIDIA GeForce GTX/RTX 600+ series GPU or NVIDIA Quadro GPU (Kepler series or later).
* **Software:** NVIDIA GeForce Experience (GFE) 2.1.1 or higher, or NVIDIA Quadro Experience.
* **Display:** A 720p or higher display (or headless display dongle) connected to the NVIDIA GPU.
* **Network Speed:** 5 Mbps or higher upload speed (only required for streaming outside your house).

### Sunshine

Detailed instructions for installing and configuring Sunshine can be found on the [Sunshine documentation](https://github.com/moonlight-stream/moonlight-docs/wiki/Setup-Guide){target="_blank"}.

1. Download and Install Sunshine.
	1. Go to the [Setup Page](https://docs.lizardbyte.dev/projects/sunshine/latest/md_docs_2getting__started.html){target="_blank"} to download the latest version.
	2. Install it on your gaming PC. You may need to reboot your PC after installation to complete the setup and enable controller emulation.

2. Launch Sunshine.
	1. Launch Sunshine. A configuration page will open in your web browser, and you may see a "this page is not secure" warning, which can be ignored.
	2. If needed, you can manually access it via the tray menu option "Open Sunshine" or by visiting [https://localhost:47990](https://localhost:47990/){target="_blank"}.

3. Create an Account.
	
    Upon first launching Sunshine, you'll be prompted to create an account. This is essential for securing access since others can connect to your PC if they access this interface.
   
	![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/12.png){class="glboxshadow"}

4. Connect with Moonlight.
	1. Open Moonlight on your client device and ensure it is connected to the same network as your gaming PC.
	2. Your gaming PC should automatically appear in the PC list. If it doesn’t, you can manually add it using its IP address.

5. Pair Devices.
	1. Select your gaming PC from the list to start pairing. Sunshine will send a notification to your host PC.
	2. Follow the prompt to enter the PIN displayed in Moonlight on the pairing dialog and submit it.

6. Test Streaming.
    
    Try streaming a game or application from your gaming PC to verify that everything is working properly.
	    
    ![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/8.png){class="glboxshadow"}

7. Access Pre-loaded Applications.

    Sunshine comes pre-loaded with Steam and the Remote Desktop. You can manually add other games and apps by following [Sunshine's guide](https://docs.lizardbyte.dev/projects/sunshine/latest/md_docs_2app__examples.html){target="_blank"} to adding apps. 

8. Further Assistance.
    
    For more information or troubleshooting, refer to the [Sunshine documentation](https://docs.lizardbyte.dev/projects/sunshine/latest/index.html){target="_blank"}.

### GeForce Experience

1. Install GeForce Experience.

    Install the GeForce Experience software from NVIDIA on your gaming PC. Your PC may need a reboot after installation to finish setup.

2. Enable GameStream.

    Open GeForce/Quadro Experience and click on the Settings (gear) icon. Navigate to the SHIELDsection and ensure the GameStream toggle is switched on (green). If the SHIELD tab is missing, refer to the [troubleshooting guide](https://github.com/moonlight-stream/moonlight-docs/wiki/Troubleshooting){target="_blank"}.
    
    ![](https://static.gl-inet.com/docs/astrowarp/tutorials/game_stream/10.png){class="glboxshadow"}

3. Launch Moonlight.

    Start the Moonlight app on your client device and ensure it is connected to the same network as your gaming PC. In most cases, your PC will appear automatically in the PC list after a few seconds. Click on your PC's entry to initiate pairing. 

4. Pair Devices.

    On your PC, enter the PIN displayed in Moonlight and confirm the pairing request.

5. Test Streaming.

    Stream a game or application to verify that everything is functioning correctly.

6. Manually Add Games (if necessary).

    If a game doesn't appear in Moonlight, you can manually add it in GeForce Experience. Alternatively, you can stream your desktop and launch any program directly.

___

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.