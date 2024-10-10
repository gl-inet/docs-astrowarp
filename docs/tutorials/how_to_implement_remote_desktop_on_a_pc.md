# How to Implement Remote Desktop on a PC

With AstroWarp, you can establish secure remote desktop connections to your PCs without the need for public IP addresses.

## Enable Remote Desktop

Please fellow the guide here to enable remote desktop on your PC: [Enable Remote Desktop on Windows](https://support.microsoft.com/en-us/windows/how-to-use-remote-desktop-5fe128d5-8fb1-7a23-3b8a-41e636865e8c){target="_blank"}.

## Find the Username

Fellow the guide below to find the username for remote connection:

1. Press the Windows key + I to open the Settings app.
2. Click on "Accounts".
3. In the left sidebar, click on "Your info".
4. Under your profile picture and name, you will see the username associated with the Windows account.
    
    ![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/windows_username.png){class="glboxshadow gl-50-desktop"}

## Configure the PC as accessible resource in the Network

The PC that needs to be remotely accessed is connected under the **MT3000-Host**. Click **MT3000-Host**, then click the **+** sign to add the PC as an accessible resource.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/add_resource.png){class="glboxshadow"}

In the diagram, GLinet-SDWAN is shown as a computer already added as an accessible resource. Its virtual IP is `10.0.3.1`.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/2.png){class="glboxshadow"}

## Connect to Remote Desktop

1. On another computer, open the "Remote Desktop Connection" program.

2. Enter the computer name or IP address you recorded earlier and click "Connect".

    ![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/remote_desktop_connection.png){class="glboxshadow"}

3. Enter the credentials. The username can find at [previous step](#find-the-username), click OK, then you will be able to access the remote desktop.
    
    ![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/enter_credentials.png){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.