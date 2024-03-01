![image](https://github.com/Chillsoda/creating-a-virtual-machine/assets/161760771/a5767a6c-1b75-4aaf-ab70-e5c617b65165)



<h1> Creating a virtual machine on Microsoft Azure</h1> 

This tutorial outlines how to create a virtual machine on Azure from start to finish. Creating the virtual machine allows us to be able to use it to observe internet traffic, set up ticketing systems, or configure a VPN, among many other things. 

<h2> Requirements and prerequisites</h2> 

1.) An active subscription to Microsoft Azure 

2.) A stable internet connection 

<h2> Operating systems used </h2> 

1.) Windows 10 VM

2.) Linux Ubuntu VM  

<h1> Set up instructions</h1> 

1.) Have an active subscription to Microsoft Azure. Signing up will give you $200 worth of free credits to your account. Head to https://portal.azure.com to get started. 

![Screen Shot 2024-03-01 at 3 34 50 AM](https://github.com/Chillsoda/creating-a-virtual-machine/assets/161760771/b8d4847b-2f10-4fe7-b6b0-e57eaf5db2a2) 

2.) Once you arrive at the home screen, head to resource groups and create a new one. This will serve to organize our resources under one banner. Give it a name then click review and create it. 

3.) Back at the home screen, click on virtual machines and click to create a new one. Organize it under our newly created resource group, give it a name, and select Windows 10 as its operating system (image in Azure). Also, select which region you would like it to be in. 

![Screen Shot 2024-03-01 at 3 45 56 AM](https://github.com/Chillsoda/creating-a-virtual-machine/assets/161760771/491a5f94-21e8-4fd5-b15e-b6d266d29a73) 

4.) For its size, go for two vcpu's. Create your username and password and check the box for licensing. Click review and create and wait for it to be deployed.

5.) Our screen should now look like this under our resource group. Notice how multiple resources were created, not just the virtual machine. 

![Screen Shot 2024-03-01 at 4 02 25 AM](https://github.com/Chillsoda/creating-a-virtual-machine/assets/161760771/7e46cc70-df6a-425d-80e1-702d426c6f55) 

6.) Repeat the process to create another virtual machine, this time select Ubuntu as the operating system (image) instead of Windows. 

7.) Click next on the bottom until you get to the networking section. Notice how the virtual network it selected is the one we created alongside the previous virtual machine. 

![Screen Shot 2024-03-01 at 4 17 58 AM](https://github.com/Chillsoda/creating-a-virtual-machine/assets/161760771/846a3050-9304-4373-ab35-545b27fa9ea9) 

8.) 








