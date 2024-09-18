# Setting Up AstroWarp with GL.iNet Routers: Remote Access

This document outlines how to use your home network as an internet exit while traveling. By accessing the internet through your home network, you can ensure security and privacy while bypassing some traditional VPN limitations. For example, many services like Netflix restrict the use of VPNs in various situations. However, if you access the internet through your home network, you will not encounter these restrictions.

![](../images/scenario_keep_ip_home_topology.png)

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

**Step 5:** Configure the Home node as the exit node, and set the Travel node to use this exit.

![](../images/astrowarp_set_exit_node.png)

Once set, a small area icon will appear on the side of the connection near Home.

![](../images/astrowarp_force_exit_node_icon.png)

**Step 6:** Open a browser on the Travel side and check if our public IP address matches that of the home network via [ipaddress.my](https://www.ipaddress.my/).

![](../images/astrowarp_check_ip_address.png)



## **FAQ** 

**Q:** After setting the Travel node to use the internet exit, why is there an issue refreshing service websites?

**A:** After setting the exit node, the network may briefly disconnect, causing devices to be unable to access service websites and the internet. Please wait a moment (no more than 1 minute) for the connection to restore.



