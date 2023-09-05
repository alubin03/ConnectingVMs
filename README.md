
## Configuring NAT network to connect 2 VMs

I am setting up my lab enviornment to use for malware analysis, penetration testing, and secure software testing. But first i need to connect them by using NAT networking.🌐

### Tools Used:

- VirtualBox Installer
- Kali Linux OVA file
- Windows ISO file

### What I Did
<p align="center">
In this lab i set up my virtual enviornment using Virtual Box.(My Favorite). You can use other virtual Machines like VMware and Microsoft Hyper-V Manager aswell.
  
![image](https://github.com/alubin03/internship-projects/assets/141780397/484878d0-15c7-4300-b045-2696ecb79d4b)
<p align="center">
Then I Downloaded Kali Linux OVA file

![image](https://github.com/alubin03/internship-projects/assets/141780397/e092f873-35e5-42a5-ab00-375b4e4c1629)
<p align="center">
Then I had to change the network to NAT network so the vms can reach each other

![image](https://github.com/alubin03/ConnectingVMs/assets/141780397/8d112d89-7734-40c1-a3f0-6eea13102595)
<p align="center">
"if config" to get the ip address

![image](https://github.com/alubin03/ConnectingVMs/assets/141780397/65e61121-c560-4f87-9077-8ee5d263d5f1)
<p align="center">
Then ping the ip address (nick name is "manta")

![image](https://github.com/alubin03/ConnectingVMs/assets/141780397/c5de7cd5-1592-4cb0-ab46-58b791cdf770)

<p align="center">
Completed!
  
### Completion thoughts:
I successfully configured a NAT network for connecting two virtual machines in my lab environment. This setup will be used for malware analysis, penetration testing, and secure software testing purposes. As with any technical project, I faced a few obstacles along the way. Initially, I ran into issues with a missing product key when attempting to use Windows 8 as my operating system. Additionally, setting up a Windows 10 ISO file took longer than expected. Nevertheless, I persevered and eventually managed to establish a NAT network so that both virtual machines could connect to it. This environment is now fully functional and available for use in future projects.

