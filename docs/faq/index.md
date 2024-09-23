# FAQ



### **Remote access failed**

* Check the [node access and resource access settings](../quick_start/index.md/#access-permission-settings) of the network topology map to confirm that the device is allowed to be accessed.

* Check the firewall settings of the accessed device to ensure that the device is allowed to be accessed by the router.

* Try to restart ([stop and then start](../quick_start/index.md/#stop-or-start-network)) the astrowarp network.

* Try to [switch the server node](../quick_start/index.md/#switch-cloud-node-location).

  ---

### **Unable to access the resource domain name**

* The resource domain name is only valid in the intranet. Confirm the access scope first.

* The resource domain name is resolved locally by the router. Please make sure that DNS encryption is not enabled on the device side and the DNS server is not pointed to an encrypted address such as 1.1.1.1.

  ---

### **The device is not in the resource list**

* Make sure that the device and the router are in the same network. It may take up to 2 minutes to discover the device when the device is connected to the network for the first time.

* If there are multiple layers of NAT between the accessed device and the router, it needs to be added manually. This feature will be supported in version 0.6.0.

  ---

### **The original IP address of the device is inaccessible**

* To avoid IP changes and subnet conflicts on the device, only accessible IPs assigned by astrowarp are supported for access.

---

### **Unable to access the Internet**

* If the exit node is in use, please confirm whether the exit node can access the Internet normally.

* Try to restart ([stop and then start](../quick_start/index.md/#stop-or-start-network)) the astrowarp network.

* Try to [disable the astrowarp](../quick_start/index.md/#disable-astrowarp-services) service on the router.

  ---



  Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.

