# Configure a Virtual Machine
<p align="center">
<img src="https://i.imgur.com/NSZx7p5.jpg" alt="osTicket logo"/>
</p>
A step by step tutorial on how to create a virtual machine in Azure.
<a href="https://youtu.be/Qjkd9SI4NFo"> 
Creating Virtual Machine In Azure




<h1>CREATING VIRTUAL MACHINE</h1>
<b>Creating Virtual Machines</b>

First visit https://azure.microsoft.com/en-us/free/virtual-machines/


Sign Up for a free 30 day subscription and create a username and password (tenant). You may access your portal at anytime by -visiting portal.azure.com; and logging in with your credentials.

In the search bar type in "resource groups" and click "create resource group"

Type in the desired name of your resource group, and under "Resource Details" choose any region you'd like, then Click "Review + Create". Once validation has passed; click "Create" at the bottom of screen to create resource group.

Now that you have a resource group; go to the search bar and type in "Virtual Machines". Once on the page; click "Create" and click on the first option "Azure Virtual Machine"

Once your page loads, You'll see "Azure Subscription 1" and "(New) Resource group". Click the box refering to the resource group, and click on the resource group you've just created. This is where your virtual machine will be stored.

Name your Virtual Machine, select the same region that you chose for your resource group, Under "image"; select your desired operating system, Under "size" select the desired size of the virtual cpu you want, create a username and password under "Administrator account", check box under "licensing", lastly click "Review + Create". If done correctly; validation should pass, and click "create". Exercise some patience, for it will take a while to create.

All set!! You have now created a VIRTUAL MACHINE!!!

<h2>REMOTE ACCESS</h2>

Now that you have created the VM (virtual machine) click in the search bar and search "Virtual Machines" (or click you can click virtual machines under the "Azure Services" tab) there you will see the name of the machine you created.

Click the name of your vm and that will take you to an overview page displaying all the info about your vm. You will see a public ip address and a private ip address. You will need the public ip; copy or write it down!!!

If you are a windows user; click the start menu and type in "remote desktop". In the screen; paste or type in the public ip address and enter the username and password you've created making the vm. If you get warning message saying that it isn't safe, disregard that and click yes, its totally safe. If done correctly, your virtual machine will open on your screen and start loading. Type in username and password when prompted, and welcome to your Virtual Machine!

For Mac users, download "RD Cient" from the Apple store (its free).

Open the app and click on the + sign. Select "Add PC". Enter ip adress under "PC NAME" and under "USER ACCOUNT" type in your vms username and password that you created and click save. This will create your virtual PC within the app with the IP adress as the name.

Click on the PC and if done correctly; your vm should load on your Mac.

To delete your vm, go back to your azure portal and go to resoure group. Delete the resource group and the NetworkWatcherRG folders created and your done. 

This tutorial outlines the implementation of a Vitual Machine.

<H3> VIDEO EXAMPLE</H3>

<a href="https://youtu.be/Qjkd9SI4NFo"> Creating Virtual Machine In Azure</a>
