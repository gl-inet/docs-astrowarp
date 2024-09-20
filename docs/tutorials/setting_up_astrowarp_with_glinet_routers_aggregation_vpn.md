# Setting Up AstroWarp with GL.iNet Routers: Aggregation VPN

This document will guide you in creating an Aggregated VPN link for internet access. By using an Aggregated VPN, users can enjoy a better online experience in certain scenarios.

 ![](../images/scenario_bandwidth_bonding.png)

## **Preparation**
Before starting the configuration, please complete the [**preparations**](preparation_work.md).

</br>

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
