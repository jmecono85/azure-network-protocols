<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Network Protocols (ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1 Create a Windows 10 Virtual Machine (VM)
- Step 2 Create a Linux (Ubuntu) VM 
- Step 3 Use Remote Desktop to connect to your Windows 10 Virtual Machine
- Step 4 Within your Windows 10 Virtual Machine, Install Wireshark 
- Step 5 Within Wireshark, filter for ICMP traffic only
- Step 6 Retrieve the private IP address of the Ubuntu VM (linux-vm) and attempt to ping it from within the Windows 10 VM
  Observe ping requests and replies within WireShark.
- Step 7 (Configuring a Firewall [Network Security Group]) Linux-Virtual Machine and disable (inbound) ICMP Traffic
  and Observe ping has Timed Out after disabling (inbound) ICMP Traffic


<h2>Step 1</h2>

<p>
  
![image](https://github.com/user-attachments/assets/595cdca7-c65f-4a45-82c3-cb2ba45f9309)
![image](https://github.com/user-attachments/assets/1def5486-89da-49f0-8f42-02d8b3ea02ae)


</p>


<h2>Step 2</h2>

<p>
  
![image](https://github.com/user-attachments/assets/7f00a886-64f1-4319-be3f-64c0a6f33d47)
![image](https://github.com/user-attachments/assets/b22338d5-dede-4315-83ae-b416d1c840c0)


</p>



<h2>Step 3</h2>

<p>
  
![image](https://github.com/user-attachments/assets/fa7d34b6-64b5-475a-8287-cc59dff59e70)

</p>


<h2>Step 4</h2>

<p>
  
![image](https://github.com/user-attachments/assets/8474181c-453f-40b4-93fd-719b0c09a44e)

</p>



<h2>Step 5</h2>

<p>
  
![image](https://github.com/user-attachments/assets/9cfedc4f-98cd-4280-a730-306c4fc54fc7)


</p>



<h2>Step 6</h2>

<p>

![image](https://github.com/user-attachments/assets/2c258a82-3037-467f-800d-a1eeba5a48e5)


</p>


<h2>Step 7</h2>

<p>
  
![image](https://github.com/user-attachments/assets/b0b77daa-b77b-4c5e-ba3a-1ebf37719a58)
![image](https://github.com/user-attachments/assets/4ac16db9-3801-4c1a-b5d8-a389a32c7e9e)
![image](https://github.com/user-attachments/assets/e932cfc6-a33d-45de-8a76-25071fb26428)


</p>



