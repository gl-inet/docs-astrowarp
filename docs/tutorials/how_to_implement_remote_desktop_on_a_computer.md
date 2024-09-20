# How to Implement Remote Desktop on a Computer

### Ensure Version Support:
* Make sure your computer is running Windows Professional, Enterprise, or Education edition, as the Home edition does not support Remote Desktop functionality.

### Enable Remote Desktop:
* 	Right-click on “This PC” and select “Properties.”
* 	Click on “Remote settings.”
* 	Under the Remote tab, check “Allow remote connections to this computer” and make sure “Only allow connections from computers running Remote Desktop with Network Level Authentication” is unchecked.
![](../images/rdp/2-1.png)

### Record the Username:
* In the “System” window, note down your username for remote connection.
![](../images/rdp/3-1.png)

### Configure Firewall:
* Ensure that Windows Firewall allows RDP traffic. You can check and allow “Remote Desktop” in the firewall settings under the Control Panel.
![](../images/rdp/4.png)

### Configure the Network:
* Add the computer to be accessed remotely as an accessible resource. In the diagram, GLinet-SDWAN is shown as a computer already added as an accessible resource.
  ![](../images/rdp/1.png)
  ![](../images/rdp/2.png)

### Connect to Remote Desktop:
* On another computer, open the “Remote Desktop Connection” program.

* Enter the computer name or IP address you recorded earlier and click “Connect.”

* Enter your username and password (usually the account name and password you use to log into the computer), and you will be able to access the remote desktop.
  ![](../images/rdp/3.png)

  ---

  

  Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.