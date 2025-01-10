# FAQ

### **Why can't I find my router in the AstroWarp device list?**

* Ensure that your router's firmware is updated to version 4.7.0.

* When logging into the cloud service, make sure to use the "SELF" option.

---

### **Why is there an issue refreshing service websites after setting the Travel node to use the internet exit?**

* After setting the exit node, the network may briefly disconnect, preventing devices from accessing service websites and the internet. Please wait for up to one minute for the connection to restore.

---

### **What should I do if I cannot access Remote Desktop after following the setup steps?**

* First, ensure you are using the virtual IP to access Remote Desktop and that the username and password are correct. If the issue persists, check the firewall settings to ensure that permissions for the Remote Desktop application are properly configured.
  
---

### **What should I do if I cannot ping after following the setup steps?**

* Make sure you are using the virtual IP for access and that the username and password are correct. If the issue persists, check the firewall settings on the device you are trying to access.


---

### **Why is there no significant increase in speed with connection aggregation?**

* Check if your speed has already reached the physical limit. For Spitz AX (GL-X3000) and Puli AX (GL-XE3000) devices, the aggregated physical limit is around 300 Mbps.

* The speed aggregation feature may not work effectively in scenarios with significant differences in link quality, such as bandwidth and latency. We do not recommend using Ethernet and cellular networks for aggregated connections.

---

### **Remote access failed**

* Check the [node access and resource access settings](../quick_start/index.md/#access-permission-settings) of the network topology map to confirm that the device is allowed to be accessed.

* Check he firewall settings of the accessed device to ensure that the device is allowed to be accessed by the router.

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

<!-- --- -->

<!-- Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}. -->
