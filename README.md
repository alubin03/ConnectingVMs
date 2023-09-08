
## Configuring NAT network to connect 2 VMs

I am setting up my lab enviornment to use for malware analysis, penetration testing, and secure software testing. But first I need to connect them by using NAT networking.🌐

⚠️ I want to clarify that the following documentation is not intended to serve as a comprehensive, step-by-step guide for the lab that I have created. It is rather a record of my personal notes and observations on the lab⚠️

### Tools Used🔨

- VirtualBox Installer
- Kali Linux OVA file
- Windows ISO file

### Program Walk-Thru🚶🏽‍♀️
<p align="center">
In this lab i set up my virtual enviornment using Virtual Box.(My Favorite). You can use other virtual Machines like VMware and Microsoft Hyper-V Manager aswell.
First thing i did was download Kali Linux OVA file and Windows ISO file.

<p align="center">
The network on the vm is originally NAT I changed it to "NAT network" this allows BOTH machines to reach each other.

<p align="center">
<img src="https://github.com/alubin03/ConnectingVMs/assets/141780397/8d112d89-7734-40c1-a3f0-6eea13102595"/>
</p>

<p align="center">
"if config" to get the ip address

<p align="center">
<img src="https://github.com/alubin03/ConnectingVMs/assets/141780397/65e61121-c560-4f87-9077-8ee5d263d5f1"/>
</p>

<p align="center">
Then ping the ip address (nick name is "manta")
  
<p align="center">
<img src="https://github.com/alubin03/ConnectingVMs/assets/141780397/c5de7cd5-1592-4cb0-ab46-58b791cdf770"/>
</p>
<p align="center">
Completed!
  
### Completion thoughts:
I successfully configured a NAT network for connecting two virtual machines in my lab environment. This setup will be used for malware analysis, penetration testing, and secure software testing purposes. As with any technical project, I faced a few obstacles along the way. Initially, I ran into issues with a missing product key when attempting to use Windows 8 as my operating system. Additionally, setting up a Windows 10 ISO file took longer than expected. Nevertheless, I persevered and eventually managed to establish a NAT network so that both virtual machines could connect to it. This environment is now fully functional and available for use in future projects.

