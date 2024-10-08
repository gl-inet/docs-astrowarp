# Setting Up AstroWarp with GL.iNet Routers: Remote Networking

This document outlines the steps to create a remote network that connects resources from two offices, enabling mutual access.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/scenario_remote_networking_topology.jpg){class="glboxshadow"}

## **Preparation**

Before starting the configuration, please complete the [**preparations**](preparation_work.md).

</br>

## **Creating the Network**

**Step 1:** Set a Network Name: Choose a name for your network, such as "mynet."

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/astrowarp_give_name_for_network.png){class="glboxshadow"}

**Step 2:** Select the Site to Site Scenario.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/select_s2s_scenario.png){class="glboxshadow"}

**Step 3:** Choose Routers and Associated Server Locations

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/astrowarp_select_routers.png){class="glboxshadow"}

**Step 4:** If you choose a non-free service, you will enter the payment step. Complete the payment according to the guide, and the following topology will appear.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/astrowarp_s2s_inited_topology.png){class="glboxshadow"}

**Step 5:** Click on the connection line between the two routers to ensure that bidirectional access permissions are enabled.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/astrowarp_set_resource_and_permission_remote_networking.png){class="glboxshadow"}

**Step 6:** Click the plus sign next to Office1 and Office 2, select the devices you wish to access mutually, and confirm.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/astrowarp_select_resource.png){class="glboxshadow"}

Once access is granted, a virtual IP will be automatically assigned. You can view this by clicking on the corresponding router in the topology diagram.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/astrowarp_check_virtual_ip.png){class="glboxshadow"}

*Note: Access between devices will occur via the virtual IP. You can perform a simple test using the ping command.*

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_networking/ping_result.png){class="glboxshadow"}

## **FAQ** 

**Q:** What should I do if I cannot ping after following the setup steps?

**A:** First, ensure you are using the virtual IP for access and that the username and password are correct. If the issue persists, please check the firewall settings on the device being accessed.

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
