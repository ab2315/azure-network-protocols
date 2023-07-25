# azure-network-protocols
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create a virtual machine in azure
- Download wire shark
- Command ping 
- NSlookup 

<h2>Actions and Observations</h2>

<p>

![image](https://github.com/ab2315/azure-network-protocols/assets/139497276/8b30e4b6-dbe6-4e12-9fe2-de7df6995a22)

<p>
First step is to create 2 Virtual Machines on azure in order to do that you must have a subscription and a resource group after that is completed you can go in to azure search virtual machines and create one
</p>
<br />

<p>

![image](https://github.com/ab2315/azure-network-protocols/assets/139497276/b7a857f7-62ee-4bec-bb60-7a01550604e5)

</p>
<p>
</p>
Second step you want to go into VM on your remote desktop open up wire shark after you have downloaded it and command line ping on powershell to see the traffic coming into the VM  
<br />

<p>

![image](https://github.com/ab2315/azure-network-protocols/assets/139497276/9d5f4213-ec4d-4865-ace0-c4b8398afb65)

</p>
<p>
Last step you want input command nslookup (any website) on windows power shell with wire shark open in order to see the traffic come in from the website of your choice as well as recieving a public IP address for that website 
</p>
<br />
