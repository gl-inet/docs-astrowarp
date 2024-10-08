# How to Implement Remote Desktop on a Computer

### Ensure Version Support:

* Make sure your computer is running Windows Professional, Enterprise, or Education edition, as the Home edition does not support Remote Desktop functionality.

### Enable Remote Desktop:

* 	Right-click on “This PC” and select “Properties.”
* 	Click on “Remote settings.”
* 	Under the Remote tab, check “Allow remote connections to this computer” and make sure “Only allow connections from computers running Remote Desktop with Network Level Authentication” is unchecked.
![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/2-1.png){class="glboxshadow"}

### Record the Username:

* In the “System” window, note down your username for remote connection.
![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/3-1.png){class="glboxshadow"}

### Configure Firewall:

* Ensure that Windows Firewall allows RDP traffic. You can check and allow “Remote Desktop” in the firewall settings under the Control Panel.
![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/4.png){class="glboxshadow"}

### Configure the Network:

* Add the computer to be accessed remotely as an accessible resource. In the diagram, GLinet-SDWAN is shown as a computer already added as an accessible resource.
  ![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/1.png){class="glboxshadow"}

  ![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/2.png){class="glboxshadow"}

### Connect to Remote Desktop:

* On another computer, open the “Remote Desktop Connection” program.

* Enter the computer name or IP address you recorded earlier and click “Connect.”

* Enter your username and password (usually the account name and password you use to log into the computer), and you will be able to access the remote desktop.
  ![](https://static.gl-inet.com/docs/astrowarp/tutorials/rdp/3.png){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.