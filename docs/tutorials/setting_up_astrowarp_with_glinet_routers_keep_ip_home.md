# Setting Up AstroWarp with GL.iNet Routers: Keep Your Home IP

This document outlines how to use your home network as an internet exit while traveling. By accessing the internet through your home network, you can ensure security and privacy while bypassing some traditional VPN limitations. For example, many services like Netflix restrict the use of VPNs in various situations. However, if you access the internet through your home network, you will not encounter these restrictions.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/scenario_keep_ip_home_topology.jpg){class="glboxshadow"}

## **Preparation**
Before starting the configuration, please complete the [**preparations**](preparation_work.md).

</br>

## **Creating the Network**

**Step 1:** Set a Network Name: Choose a name for your network, such as "mynet."

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/astrowarp_give_name_for_network.png){class="glboxshadow"}

**Step 2:** Select the Site to Site Scenario.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/select_s2s_scenario.png){class="glboxshadow"}

**Step 3:** Choose Routers and Associated Server Locations

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/astrowarp_select_routers.png){class="glboxshadow"}

**Step 4:** If you choose a non-free service, you will enter the payment step. Complete the payment according to the guide, and the following topology will appear.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/astrowarp_s2s_inited_topology.png){class="glboxshadow"}

**Step 5:** Configure the Home node as the exit node, and set the Travel node to use this exit.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/astrowarp_set_exit_node.png){class="glboxshadow"}

Once set, a small area icon will appear on the side of the connection near Home.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/astrowarp_force_exit_node_icon.png){class="glboxshadow"}

**Step 6:** Open a browser on the Travel side and check if our public IP address matches that of the home network via [ipaddress.my](https://www.ipaddress.my/){target="_blank"}.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/keep_ip_home/astrowarp_check_ip_address.png){class="glboxshadow"}

## **FAQ** 

**Q:** After setting the Travel node to use the internet exit, why is there an issue refreshing service websites?

**A:** After setting the exit node, the network may briefly disconnect, causing devices to be unable to access service websites and the internet. Please wait a moment (no more than 1 minute) for the connection to restore.

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
