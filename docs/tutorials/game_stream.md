# How to Stream Games Using Remote Desktop

Game streaming allows you to play high-performance games on any device remotely, whether you’re on a weaker PC, a laptop, or even a mobile device. This guide will help you set up remote desktop streaming for games using Windows Remote Desktop.

### **Ensure Your Host PCIs Ready for Remote Desktop**

* Check Windows Version:
Ensure you are using Windows 10/11 Professional, Enterprise, or Education editions. Windows Home does not support Remote Desktop by default.
* Enable Remote Desktop:
	1. Right-click on “This PC” or “My Computer” and select Properties.
	1. Click Remote Settings on the left.
	1. Under the Remote Desktop section, select “Allow remote connections to this computer.”
	1. Uncheck the box that says “Allow connections only from computers running Remote Desktop with Network Level Authentication” for easier connections.

### **Set Up Your Firewall**

* Allow Remote Desktop in Firewall:
	1. Go to Control Panel > System and Security > Windows Firewall.
	1. Click Allow an app or feature through Windows Firewall.
	1. Ensure “Remote Desktop” is checked in both private and public networks.

### **Prepare Your Network**

* Network Requirements:
	1. Make sure your **Host PC** is connected via **AstroWarp** for better connection stability.
	2. Distrebute your **Host PC** and make sure your **Client PC** can access it.
	1. Ensure the network is fast enough for gaming (recommended: 20Mbps or higher for streaming).

![](https://static.gl-inet.com/docs/astrowarp/tutorials/game/openRs.png){class="glboxshadow"}

### **Install and Configure a Game Streaming Client**

Although Windows Remote Desktop is effective for work tasks, you might prefer a dedicated game streaming app for better performance. Here are two great options:

* Steam Remote Play:
	1. Open Steam on your main computer.
	1. Enable Remote Play in Steam settings.
	1. Log into Steam from a secondary device (laptop, mobile, etc.) and start streaming games from your main PC.
![](https://static.gl-inet.com/docs/astrowarp/tutorials/game/2.png){class="glboxshadow"}

* NVIDIA GeForce Experience (for NVIDIA GPU users):
	1. Install NVIDIA GeForce Experience on your **Gaming Host PC**.
	1. Enable GameStream in the settings.
	1. Download the Moonlight app on your remote device and input accessable address(IP) to stream games from your **Client PC**.
![](https://static.gl-inet.com/docs/astrowarp/tutorials/game/3.png){class="glboxshadow"}

### **Connect and Start Streaming**

* Open Remote Desktop on the Remote Device:
	1. On another device (Windows, macOS, or mobile), open the Remote Desktop Connection app.
	1. Enter the IP address which distrebute by **AstroWarp**. 
	1. Input your credentials (username and password).
![](https://static.gl-inet.com/docs/astrowarp/tutorials/game/1.png){class="glboxshadow"}
* Adjust Streaming Quality:
	1. For smooth gameplay, lower the streaming quality if the connection is unstable. Most streaming apps (e.g., Steam, Moonlight) let you adjust resolution and frame rates.
![](https://moonlight-stream.org/images/steam_framed.webp){class="glboxshadow"}

### **Conclusion**

Remote desktop game streaming allows you to access your powerful gaming PC from anywhere, turning any device into a gaming platform. By following this guide and using apps like Steam Remote Play or Moonlight, you can enjoy a seamless gaming experience, even on weaker devices.

Happy gaming!

Feel free to modify this tutorial based on your preferred tools or additional steps. Would you like me to help with specific images for this guide?

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.