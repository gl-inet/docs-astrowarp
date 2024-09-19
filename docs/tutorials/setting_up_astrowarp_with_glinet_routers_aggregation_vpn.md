# Setting Up AstroWarp with GL.iNet Routers: Aggregation VPN

This document will guide you in creating an Aggregated VPN link for internet access. By using an Aggregated VPN, users can enjoy a better online experience in certain scenarios.

## Preparation

1. Router Compatibility: Confirm that your router model falls under the following list: 

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

4. Testing Configuration: For testing purposes, you may configure the router to use both repeater and tethering modes (this step can be skipped if the environment does not allow it).

## **Creating the Network**

**Step 1:** Set a Network Name: Choose a name for your network, such as "mynet."

![](../images/astrowarp_give_name_for_network.png)

**Step 2:** Select the Connection Aggregation Scenario.

![](../images/select_aggregation_scenario.png)

**Step 3:** Choose the Location and Traffic Plan.

![](../images/astrowarp_choose_location_and_traffic_plan.png)

**Step 4:** Select Routers for Aggregated VPN.

![](../images/astrowarp_select_aggregated_routers.png)

**Step 5:**After completing the payment, the following topology connection will be generated.

![](../images/astrowarp_aggregated_inited_topology.png)

You can check if our public IP address matches the public IP address of the aggregation node via [ipaddress.my](https://www.ipaddress.my/).

![](../images/astrowarp_check_ip_address.png)

**Step 6:** Once confirmed the IP address, you can test different application scenarios. For example, you can try disconnecting the router's tethering network connection during a video conference to observe if the call is interrupted due to network issues.

## **FAQ** 

**Q:** Why is there no significant increase in speed with connection aggregation?

**A:** First, check if your speed has already reached the physical limit. For Spitz AX (GL-X3000)/Puli AX (GL-XE3000) devices, the aggregated physical limit is around 500 Mbps. The speed aggregation feature does not apply to scenarios with significant differences in link quality, such as bandwidth and latency. We do not recommend using Ethernet and cellular networks for aggregated connections.

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
