# Security Notice

## AstroWarp: Delivering High-Standard Security Through Cutting-Edge Technology

AstroWarp provides users with high-standard security protection through robust encryption technology, flexible network isolation mechanisms, and distributed architecture design. Whether through point-to-point connections or cloud node transmissions, AstroWarp's core philosophy prioritizes the protection of user safety and privacy, ensuring network security and stability.

To achieve this, AstroWarp offers a suite of security features, including:

1. **Two-Step Verification**: Enhances the security of user authentication.
2. **Data Isolation Between Networks**: Ensures network separation between different users and devices.
3. **End-to-End Encryption**: Safeguards data transmission with WireGuard-based encryption protocols.

### Key Security Features

1. **Two-Step Verification**

    AstroWarp supports two-step verification, compatible with commonly used tools like Google Authenticator. Users can add an extra layer of protection to their accounts using dynamic verification codes, preventing unauthorized access.
   
2. **Network Isolation**

    AstroWarp offers network isolation between users, allowing them to define access permissions for specific devices. This feature effectively blocks unauthorized access and ensures the security of network resources.

3. **Encrypted Communication Based on WireGuard**

    AstroWarp’s communication encryption adopts the WireGuard protocol, providing robust security for various application scenarios and needs.

    **WireGuard**: 
    
    WireGuard is a foundational element of AstroWarp’s communication infrastructure, offering a fast, modern, end-to-end encrypted VPN connection. WireGuard leverages state-of-the-art cryptography to secure connections between devices. Its design has undergone extensive cryptographic review and auditing, with only minor issues identified and resolved.
    
    Key design principles include:

    * **Advanced Encryption Technology**: Utilizes industry-leading cryptographic algorithms such as the Noise protocol framework, Curve25519, ChaCha20, Poly1305, and BLAKE2 to ensure communication security.

    * **Minimized Attack Surface**: Through minimalistic design, WireGuard reduces potential vulnerabilities. Its codebase is significantly smaller than traditional VPN solutions (e.g., IPsec and OpenVPN), making it easier to audit and verify.

4. **Data Privacy Protection**

    AstroWarp prioritizes the protection of user data privacy through system-level design, ensuring no traffic inspection and minimal metadata handling.

    Key aspects include:

     * **End-to-End Encryption** : User data is encrypted using WireGuard, meaning even AstroWarp’s cloud node servers involved in data relay cannot decrypt communication content.
     * **Metadata Processing** : When users utilize proprietary IP features through cloud nodes, AstroWarp only collects essential metadata, such as connection information, necessary for network service support. User internet traffic remains uninspected.
  
    Even in extreme scenarios (e.g., cloud node failures), AstroWarp maintains device-to-device connectivity through point-to-point (P2P) methods, ensuring high availability and user independence.

5. **Globally Distributed Node Architecture**

    AstroWarp provides globally distributed cloud nodes and disaster recovery servers, enabling automatic switching under the following conditions:

    * **Single Point of Failure**: If a cloud node server in a specific region goes down, AstroWarp automatically switches to backup nodes in other regions.
    * **Network Instability**: When P2P connections are unstable, cloud nodes act as relays to maintain continuous communication.
   
Currently, AstroWarp's cloud nodes span North America, Europe, and Asia. These regions operate with a non-shared state design, further enhancing fault tolerance and network resilience.

___

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.