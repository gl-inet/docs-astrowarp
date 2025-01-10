# Security Notice

AstroWarp provides high-standard security protection through powerful encryption technologies, flexible network isolation mechanisms, and distributed architecture design. Whether it's point-to-point connections or transmissions via cloud nodes, AstroWarp prioritizes safeguarding user security and privacy to ensure network safety and stability.


To achieve this, AstroWarp offers a range of security features, including:

1. **Two-Factor Authentication (2FA)**: Enhances the security of user identity verification.
2. **Data Isolation Between Networks**: Ensures network isolation between different users and devices.
3. **End-to-End Encryption**: Secures data transmission using WireGuard and V2Ray VMess protocols.
### **Security Features**
1. **Two-Factor Authentication (2FA)** <br>AstroWarp supports 2FA and is compatible with common authentication tools like Google Authenticator. Users can secure their accounts with dynamic verification codes to prevent unauthorized access.
   


2. **Network Isolation**<br>AstroWarp offers network isolation between users, allowing them to define access permissions for specific devices. This feature effectively blocks unauthorized access and protects users' network resources.

3. **Encrypted Communication Based on WireGuard**
   <br>AstroWarp’s communication encryption adopts the WireGuard protocol, providing robust security for various application scenarios and needs.<br>
    **WireGuard** <br>WireGuard is a foundational element of AstroWarp’s communication infrastructure, offering a fast, modern, end-to-end encrypted VPN connection. WireGuard leverages state-of-the-art cryptography to secure connections between devices. Its design has undergone extensive cryptographic review and auditing, with only minor issues identified and resolved.

    Key design principles include:
   <br>
      * **Advanced Encryption Technology**: Utilizes industry-leading cryptographic algorithms such as the Noise protocol framework, Curve25519, ChaCha20, Poly1305, and BLAKE2 to ensure communication security.<br>
      * **Minimized Attack Surface**: Through minimalistic design, WireGuard reduces potential vulnerabilities. Its codebase is significantly smaller than traditional VPN solutions (e.g., IPsec and OpenVPN), making it easier to audit and verify.
  
  
4. **Data Privacy Protection**
AstroWarp prioritizes user data privacy and, by design, does not inspect user traffic, only processing essential metadata.
      * **End-to-End Encryption**: User data is encrypted during transmission using WireGuard. Even when AstroWarp's cloud servers act as intermediaries, they cannot decrypt the communication content.
      * **Metadata Handling**: For cloud node-exclusive IP functionality, AstroWarp only collects necessary metadata (e.g., connection information) for network service support and never inspects user internet traffic content.
  
    Even in extreme scenarios (e.g., cloud node failure), AstroWarp maintains high service availability and user independence by enabling device-to-device (P2P) connections.


5. **Globally Distributed Node Architecture**
   
    AstroWarp provides globally distributed cloud nodes and disaster recovery servers, supporting automatic switching under the following conditions:<br>
   1. **Single Point of Failure**: If a cloud node in one region goes down, AstroWarp automatically switches to disaster recovery nodes in other regions.<br>
   2. **Unstable Networks**: When P2P connections are unstable, cloud nodes serve as relays to ensure continuous communication.

AstroWarp’s cloud nodes currently cover North America, Europe, and Asia. A non-shared state design between regions further enhances fault tolerance and network resilience.