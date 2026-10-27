# Networkwalks Week 1: Lab Setup

## Project Overview
This project documents my Week 1 Networkwalks internship task. I set up a Kali Linux virtual machine using Oracle VirtualBox.

## Tools Used
- Oracle VirtualBox
- Kali Linux
- Windows
## Host Laptop Specifications

- Manufacturer: HP
- Model: HP EliteBook 840 G3
- Processor: Intel(R) Core(TM) i5-6300U CPU @ 2.40GHz
- CPU cores: 2
- Logical processors: 4
- Installed RAM: 8 GB
## Network Configuration
- Network type: NAT Network
- Network CIDR: `10.0.0.0/24`
- Kali Linux IP address: `10.0.0.2/24`
- Default gateway: `10.0.0.1`
- DNS servers: `1.1.1.1` and `8.8.8.8`

## Testing and Verification
- Internet connectivity: Successful
- Shared Downloads folder: Working
- Shared clipboard: Working
- Virtual machine snapshot: Created
- Drag-and-drop: Configured as bidirectional, but file transfers did not work.

## Challenges Encountered
I experienced a problem with VirtualBox drag-and-drop. Even after updating the guest packages and enabling bidirectional mode, file transfers failed with the message "Can't drop data to guest." I used the shared Downloads folder to access files between Windows and Kali Linux.

## Lessons Learned
I learned how to configure a virtual machine, set a static IP address, test internet connectivity, share a folder, configure clipboard sharing, and create a snapshot.

## Screenshots

- [Kali IP Address](kali-ip-address.png)
- [Internet Connectivity Test](internet-connectivity.png)
- [Shared Downloads Folder](shared-downloads-folder.png)
- [VirtualBox Network Settings](virtualbox-network-settings.png)
- [Networkwalks Week 1 Snapshot](networkwalks-week1-snapshot.png)

## Conclusion
The main lab setup is working, including networking, internet access, the shared folder, clipboard
