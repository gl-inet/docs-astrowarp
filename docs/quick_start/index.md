# Quick start

## Preparation

### Check model and version

Router Compatibility: Confirm that your router model falls under the following list:

| Supported Models              | Version         | Firmware Download                                                                     |
|-------------------------------|-----------------|---------------------------------------------------------------------------------------|
| Spitz AX (GL-X3000)           | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/x3000/?type=stable){target="_blank"}  |
| Puli AX (GL-XE3000)           | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/xe3000/?type=stable){target="_blank"} |
| Beryl AX (GL-MT3000)          | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/mt3000/stable){target="_blank"}       |
| Flint 2 (GL-MT6000)           | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/mt6000/stable){target="_blank"}       |
| Brume 2 (GL-MT2500/GL-MT2500A)| 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/mt2500/stable){target="_blank"}       |
| Flint (GL-AX1800)             | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/ax1800/stable){target="_blank"}       |
| Slate AX (GL-AXT1800)         | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/axt1800/stable){target="_blank"}      |
| Slate 7 (GL-BE3600)           | 4.7.0 or higher | [Stable Firmware](https://dl.gl-inet.com/router/be3600/stable){target="_blank"}       |
| Flint 3 (GL-BE9300)           | coming soon     |                                                                                       |


### Router Connection and Initial Setup

If you are a new user, please complete the GL router connection and initial setup following the [tutorial](https://docs.gl-inet.com/router/en/4/faq/first_time_setup/){target="_blank"} below before starting the configuration.

### Enable Cloud Services

Please follow the steps below to enable Cloud Services before using AstroWarp:

**Step 1:** Access the router's management interface ([http://192.168.8.1](http://192.168.8.1){target="_blank"}). In the left panel, navigate to CLOUD SERVICES → AstroWarp. Click on "Get Started." A "Cloud Services" window will appear in the top-right corner. Click the "Enable" button to activate Cloud Services.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/1.png){class="glboxshadow"}

**Step 2**: Log in to your glinet account.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/2.png){class="glboxshadow"}

If you don’t have an account yet, you’ll need to create one by clicking the "Sign up" button and completing the login process.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/3.png){class="glboxshadow"}

**Step 3**: Click the "Get Started" button to open AstroWarp.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/4.png){class="glboxshadow"}

Note: Every router in the network must be signed in to the glinet account.

### Connect device to the router

If you are configuring for the first time, we recommend that you connect the device to the LAN port or WIFI of the router, which is applicable to all scenarios.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/router_1.jpg){class="glboxshadow"}

In many cases, our device is already in the existing network. At this time, we just need to add the router to the existing network. (Notice: Only applies to the case where the device is only used as the accessed end or the router is used as the exit node)

![](https://static.gl-inet.com/docs/astrowarp/quick_start/router_2.jpg){class="glboxshadow"}

### Log in to your account

Use your glinet account to log in to AstroWarp.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/7.png){class="glboxshadow"}

## Creating the Network

**Step 1**: Set a Network Name: Choose a name for your network, such as "mynet".

![](https://static.gl-inet.com/docs/astrowarp/quick_start/8.png){class="glboxshadow"}

**Step 2**: Select your server location, router, and plan type.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/9.png){class="glboxshadow"}

**Step 3**: Click the "Other Plan" button to select the plan that suits you.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/10.jpg){class="glboxshadow"}

**Step 4**: If you choose a paid plan, proceed to the payment page to complete the transaction.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/11.png){class="glboxshadow"}

**Step 5**: After completing the steps, the following topology diagram will appear, confirming the successful setup of the basic network.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/12.png){class="glboxshadow"}

## Router node management

### Add router nodes

You can add more router nodes to the basic network to enrich your application.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/Add_router_nodes.gif)

### Node renaming

To make the network clearer, we can set our favorite names for the nodes.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_rename_node.gif)

### Delete router nodes

If the router node is no longer needed, we can delete it.
![](https://static.gl-inet.com/docs/astrowarp/quick_start/Delete_router_nodes.gif)

### Disable AstroWarp services

If you need to disable the AstroWarp service on your router, you can turn off the virtual network connection in your router's details settings.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/Disable_astrowarp_services.gif)

## Access permission settings

Node access and resource access constitute the permission control mechanism of AstroWarp, and the device is only allowed to access if both permissions are set correctly.

### Node access permissions

#### Add permissions

Draw a line on the topology map to establish a network connection between two nodes.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_node_permission.gif)

By clicking on the connection, we can set the access permissions between nodes through the permission switch on the right.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_node_permission_setting.gif)

**Notice:** when you try to connect a router to a cloud node, it means that the current router uses the cloud node as the aggregate VPN exit. Currently, only EXCLUSIVE server support the aggregate VPN function.

#### Remove permissions

You can also select and delete connections that are no longer needed.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/delete-line.gif)

### Resource access permissions

You can add or delete resources through the details interface of the node.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_node_add_resource.gif)

Or you can quickly add resources through the + sign on the right of the node.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/sign_on_the.gif)

Note: You can view the IP address and MAC address in the router's management interface to verify the resources.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/13.png)

#### Accessible address (Virtual IP)

Once a resource is added, a virtual IP will be automatically assigned for access, virtual IP can effectively avoid subnet conflicts and IP changes between routers.

The virtual IP is not actually assigned to your device, but is done through NAT rules like the one below.

```
iptables -t nat -I POSTROUTING -d 10.0.2.3/32 -j DNAT --to-destination 192.168.99.171
```

The upper limit of virtual IP allocation is 254. If this number is exceeded, you need to delete some unused or infrequently used resources.

#### Domain Name

You can set a domain name for **local** access for any resource. The domain name suffix is always atwp.net. The fixed suffix is for easier certificate issuance.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_resource_set_domain.gif)

This domain name is resolved locally by the router, so please do not set DNS encryption on your access end or point the DNS service to other addresses.

## Exit Node Settings

Router nodes can be used as Internet exits.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_set_exit_node.gif)

Exit nodes are not used for any router nodes by default, so we need to set whether other routers use this exit.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_use_exit_node.gif)

## Switch Cloud Node Location

In a few cases, the recommended server may be subject to some restrictions. If necessary, you can switch to a different server location.

![](https://static.gl-inet.com/docs/astrowarp/quick_start/astrowarp_node_exchange.gif)

## Delete network

![](https://static.gl-inet.com/docs/astrowarp/quick_start/delete_network.gif)

Note: Only free network can be deleted.

## Use the AstroWarp Client

### Preparation

Before start, You should create your network as described in the [Quick Start](../quick_start/index.md) and download the appropriate client application [here](https://www.astrowarp.net/download).

### Add share link in network

**Step 1:** Add share link in Astrowarp network

![](https://static.gl-inet.com/docs/astrowarp/quick_start/15.png){class="glboxshadow"}

**Step 2:** Set up share link

![](https://static.gl-inet.com/docs/astrowarp/tutorials/use_app/astrowarp-client-setting.png){class="glboxshadow"}

![](https://static.gl-inet.com/docs/astrowarp/tutorials/use_app/astrowarp-qr-code.png){class="glboxshadow"}

**Link Lifetime:**  The validity period of the shared link

**Add Once:**  Whether to allow the shared link to be used by multiple clients

**Use Internet Exit:**  Whether to allow the client to use the Internet exit

**Accessible Router**:  List of routers to be accessed

### Join network in client

Join the Astrowarp network using the shared link in the client

* Windows

![](https://static.gl-inet.com/docs/astrowarp/tutorials/use_app/astrowarp-app-windows-add-link.png){class="glboxshadow"}

* Mobile phone

![](https://static.gl-inet.com/docs/astrowarp/quick_start/17.png){class="glboxshadow"}

If you want to quickly apply the modified configuration on the client, exit and reopen the client to automatically re-pull the latest configuration.

---

Related Articles:

- [Scenario Usage Guide](../tutorials/index.md)
- [FAQ](../faq/index.md){target="_blank"}
___

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.

