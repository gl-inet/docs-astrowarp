# Setting Up AstroWarp with GL.iNet Routers: Remote Access

This document outlines the steps to create a remote access scenario, allowing you to access your office computer from home.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/scenario_remote_access_topology.jpg){class="glboxshadow"}

## **Preparation**

Before starting the configuration, please complete the [**preparations**](preparation_work.md).

</br>

## **Creating the Network**

**Step 1:** Set a Network Name: Choose a name for your network, such as "mynet."

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/astrowarp_give_name_for_network.png){class="glboxshadow"}

**Step 2:** Select the Site to Site Scenario.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/select_s2s_scenario.png){class="glboxshadow"}

**Step 3:** Choose Routers and Associated Server Locations

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/astrowarp_select_routers.png){class="glboxshadow"}

**Step 4:** If you choose a non-free service, you will enter the payment step. Complete the payment according to the guide, and the following topology will appear.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/astrowarp_s2s_inited_topology.png){class="glboxshadow"}

**Step 5:** To enhance security, we want to ensure that only the home computer can access the office computer without allowing reverse access. Click on the connection line between the two routers and disable the Office->Home access permission in the options on the right sidebar.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/astrowarp_set_resource_and_permission.png){class="glboxshadow"}

**Step 6:** Click the plus sign next to Office, select your office computer, and confirm. This indicates that your office computer is allowed to be accessed from the Home side.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/astrowarp_select_resource.png){class="glboxshadow"}

Once access is granted, a virtual IP will be automatically assigned. You can view this by clicking on the corresponding router in the topology diagram.

![](https://static.gl-inet.com/docs/astrowarp/tutorials/remote_access/astrowarp_check_virtual_ip.png){class="glboxshadow"}

**Step 7:** Using this virtual IP address, you can perform a series of remote operations on your office computer from the home computer, such as using [Windows Remote Desktop Connection](https://support.microsoft.com/en-us/windows/how-to-use-remote-desktop-5fe128d5-8fb1-7a23-3b8a-41e636865e8c#ID0EDD=Windows_10){target="_blank"}.

## **FAQ** 

**Q:** What should I do if I cannot access Remote Desktop after following the setup steps?

**A:** First, ensure you are using the virtual IP for access and that the username and password are correct. If the issue persists, check the firewall settings regarding permissions for the [Remote Desktop application](https://answers.microsoft.com/en-us/windows/forum/all/windows-firewall-blocks-remote-desktop/e9231961-f579-463d-80be-93e980728a77){target="_blank"}.

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
