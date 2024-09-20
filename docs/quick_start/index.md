# Quick start

## **Create a basic network**

For first-time users, we recommend setting up your AstroWarp account based on your specific needs. Here are some network setup options to choose from, depending on your scenario:

[**Setting Up AstroWarp with GL.iNet Routers: Remote Access**](../tutorials/setting_up_astrowarp_with_glinet_routers_remote_access.md)

​		If you need to access your devices remotely, follow this guide.

[**Setting Up AstroWarp with GL.iNet Routers: Keep IP home**](../tutorials/setting_up_astrowarp_with_glinet_routers_keep_ip_home.md)

​		This option is for users who want to maintain their home IP address while away.

[**Setting Up AstroWarp with GL.iNet Routers: Remote networking**](../tutorials/setting_up_astrowarp_with_glinet_routers_remote_networking.md)

​		Ideal for users who need to set up a network between different locations.

[**Setting Up AstroWarp with GL.iNet Routers: Aggregation VPN**](../tutorials/setting_up_astrowarp_with_glinet_routers_aggregation_vpn.md)

​		For those looking to combine multiple connections to increase speed and reliability.

<br>

After completing the creation of the basic network, we can continue reading to complete more complex operations.



## **Router node management**

### Add router nodes

You can add more router nodes to the basic network to enrich your application.

![](../images/astrowarp_add_router_node.gif)



### Node renaming

To make the network clearer, we can set our favorite names for the nodes.

![](../images/astrowarp_rename_node.gif)

### Delete router nodes

If the router node is no longer needed, we can delete it.

![](../images/astrowarp_delete_node.gif)





## **Access permission settings**

### Node access permissions

Draw a line on the topology map to establish a network connection between two nodes.

![](../images/astrowarp_node_permission.gif)

By clicking on the connection, we can set the access permissions between nodes through the permission switch on the right.

![](../images/astrowarp_node_permission_setting.gif)

**Notice:** when you try to connect a router to a cloud node, it means that the current router uses the cloud node as the aggregate VPN exit. Currently, only EXCLUSIVE server support the aggregate VPN function.

### Resource access permissions

You can add or delete resources through the details interface of the node.

![](../images/astrowarp_node_add_resource.gif)

Or you can quickly add resources through the + sign on the right of the node.

![](../images/astrowarp_node_add_resource_shortcut.gif)



#### Virtual IP

Once a resource is added, a virtual IP will be automatically assigned for access, virtual IP can effectively avoid subnet conflicts and IP changes between routers.

The virtual IP is not actually assigned to your device, but is done through NAT rules like the one below.

```
iptables -t nat -I POSTROUTING -d 10.0.2.3/32 -j DNAT --to-destination 192.168.99.171
```

The upper limit of virtual IP allocation is 254. If this number is exceeded, you need to delete some unused or infrequently used resources.



#### Domain Name

You can set a domain name for **local** access for any resource. The domain name suffix is always atwp.net. The fixed suffix is for easier certificate issuance.

![](../images/astrowarp_resource_set_domain.gif)

This domain name is resolved locally by the router, so please do not set DNS encryption on your access end or point the DNS service to other addresses.



## **Exit Node Settings**

Router nodes can be used as Internet exits.

![](../images/astrowarp_set_exit_node.gif)

Exit nodes are not used for any router nodes by default, so we need to set whether other routers use this exit.

![](../images/astrowarp_use_exit_node.gif)



## **Cloud Node Management**

### Switch Cloud Node Location

In a few cases, the recommended server may be subject to some restrictions. If necessary, you can switch to a different server location.

![](../images/astrowarp_node_exchange.gif)

