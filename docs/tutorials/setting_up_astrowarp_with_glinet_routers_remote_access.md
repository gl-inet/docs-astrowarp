# Setting Up AstroWarp with GL.iNet Routers: Remote Access

This document outlines the steps to create a remote access scenario, allowing you to access your office computer from home.

![](../images/scenario_remote_access_topology.png)

## Preparation
1. Router Compatibility: Confirm that your router model falls under the following list: 
    Note: Models can be different, such as combining Beryl AX (GL-MT3000) and Flint 2 (GL-MT6000).

  **1.1 Supported Firmware Versions**

  Minimum Required Firmware Version: 4.7.0 or higher

  **1.2 Supported Models**

  Spitz AX (GL-X3000)

  Puli AX (GL-XE3000)

  Beryl AX (GL-MT3000)

  Flint 2 (GL-MT6000)

 Brume 2 (GL-MT2500/GL-MT2500A)

 Flint (GL-AX1800) Coming soon

 Slate AX (GL-AXT1800) Coming soon

2. Firmware Version: Ensure the firmware version is 4.7.0 or higher.

3. Login to GL.iNet Account: Follow the instructions below to log in to your GL.iNet account and bind your device.

  **Step 1:** Access your router’s management interface and click on the cloud icon at the top of the page to enable it.

  ![](../images/router_top_cloud_icon.png)

  **Step 2:** Login or Register Your GL Account

![](../images/router_login_cloud.png)

  *Note: Every router in the network must be signed in to the GL.iNet account.*

4. Connect the devices you need to access to the router or the upstream network of the router.



## **Creating the Network**

**Step 1:** Set a Network Name: Choose a name for your network, such as "mynet."

![](../images/astrowarp_give_name_for_network.png)

**Step 2:** Select the Site to Site Scenario.

![](../images/select_s2s_scenario.png)

**Step 3:** Choose Routers and Associated Server Locations

![](../images/astrowarp_select_routers.png)

**Step 4:** If you choose a non-free service, you will enter the payment step. Complete the payment according to the guide, and the following topology will appear.

![](../images/astrowarp_s2s_inited_topology.png)

**Step 5:** To enhance security, we want to ensure that only the home computer can access the office computer without allowing reverse access. Click on the connection line between the two routers and disable the Office->Home access permission in the options on the right sidebar.

![](../images/astrowarp_set_resource_and_permission.png)

**Step 6:** Click the plus sign next to Office, select your office computer, and confirm. This indicates that your office computer is allowed to be accessed from the Home side.

![](../images/astrowarp_select_resource.png)

Once access is granted, a virtual IP will be automatically assigned. You can view this by clicking on the corresponding router in the topology diagram.

![](../images/astrowarp_check_virtual_ip.png)

**Step 7:** Using this virtual IP address, you can perform a series of remote operations on your office computer from the home computer, such as using [Windows Remote Desktop Connection](https://support.microsoft.com/en-us/windows/how-to-use-remote-desktop-5fe128d5-8fb1-7a23-3b8a-41e636865e8c#ID0EDD=Windows_10).



## **FAQ** 

**Q: What should I do if I cannot access Remote Desktop after following the setup steps?**
**A:** First, ensure you are using the virtual IP for access and that the username and password are correct. If the issue persists, check the firewall settings regarding permissions for the [Remote Desktop application](https://answers.microsoft.com/en-us/windows/forum/all/windows-firewall-blocks-remote-desktop/e9231961-f579-463d-80be-93e980728a77).

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
