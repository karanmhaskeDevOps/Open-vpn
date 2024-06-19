

---

# VPN Project

## Overview
This project was created to deepen my understanding of networking and VPNs. I aimed to do something unique and built a VPN to clarify networking concepts and the functionality of VPNs.

## Technical Details
- **Region**: North Virginia
- **VPN Machine**: AccessMyVPN AMI (Amazon Machine Image)
- **Important Note**: Do not connect as the root user during setup. Connect as 'openvpnas' to ensure proper access and security.
- **Data Flow**: 
  - **User Location**: India
  - **ISP**: Connects to the Internet Service Provider
  - **Encryption**: Data is encrypted by the VPN client
  - **Routing**: Encrypted data is routed to the remote server owned by ABC Company
  - **Decryption**: Data is decrypted at a server in the US
  - **Final Destination**: Data is routed to its final destination after decryption

## Motivation
I built this project to gain hands-on experience with networking and VPN technologies. It was a unique opportunity to move beyond theoretical knowledge and implement a practical solution.

## Setup Instructions
1. **Launch VPN Server**: Use the AccessMyVPN AMI in the North Virginia region to set up your VPN server.
2. **Configure VPN Client**: 
   - Install a VPN client on your device.
   - Ensure the VPN client is configured to connect to the VPN server you set up.
3. **Connection Note**: 
   - Do not connect as the root user.
   - Always connect as 'openvpnas' for security and proper access.
4. **Testing**: 
   - Connect from a client machine in India.
   - Verify the encrypted data is routed through the ISP to the VPN server.
   - Ensure data is decrypted at the US server and reaches its intended destination.

## Learning Outcomes
This project provided insights into:
- Setting up and configuring a VPN using a cloud-based AMI.
- The importance of encryption and secure data transmission.
- Practical aspects of networking, including data routing and server management.

## Conclusion
Building this VPN project helped me understand the intricacies of VPNs, encryption, and networking. It provided a solid foundation in networking concepts and practical skills that are essential for any networking professional.

![Screenshot 2024-06-19 123801 - Copy](https://github.com/karanmhaskeDevOps/Open-vpn/assets/161995584/2261c602-da60-4ebd-b53f-2771447075fe)

![Screenshot 2024-06-19 183837](https://github.com/karanmhaskeDevOps/Open-vpn/assets/161995584/82c18727-e85a-460d-b47b-0748689c6c5f)

![Screenshot 2024-06-19 181150](https://github.com/karanmhaskeDevOps/Open-vpn/assets/161995584/21c6d3ba-740c-4c8b-920f-073cb12ae46e)


