# Determine the IP Address Configuration of a Device 🖥️💻

🔎<b>Objectives</b>

Determine the MAC, IPv4/IPv6, Default Gateway, DHCP Server, DNS Server addresses.
<h1></h1>

<b>Step 1:</b> Open Command Prompt and run the [ipconfig](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig) command 

<p align="center">
<img src="Screenshot (66).jpg"/>
</p>


- <b>What is the IPv4 address?</b> 192.168.1.190
- <b>What is the Subnet Mask?</b> 255.255.255.0
- <b>What is the Default Gateway?</b> 192.168.1.254

<b>Step 2:</b> Open Command Prompt and run the [ipconfig/all](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig) command
<img src="Screenshot (67).jpg"/>

- <b>What is the Mac address?</b> F8-DA-0C-46-C5-B1
- <b>What is the DHCP Server address?</b> 192.168.1.254
- <b>What is the DNS Server address?</b> 192.168.1.254

<b>Step 3:</b> Verify that the TCP/IP protocol is functioning by pinging the loopback address.
<img src="Screenshot (68).png">
