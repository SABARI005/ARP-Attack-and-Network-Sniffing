# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/1808charitha/ARP-Attack-and-Network-Sniffing/assets/132996838/601f689e-2073-4ea1-b7c0-dda2611844ce)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/1808charitha/ARP-Attack-and-Network-Sniffing/assets/132996838/891aae37-5a0c-42dc-bde0-39a0bd125c1a)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/1808charitha/ARP-Attack-and-Network-Sniffing/assets/132996838/430c1bf2-cd8c-41c7-b06b-51c391dae702)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/1808charitha/ARP-Attack-and-Network-Sniffing/assets/132996838/fe5cb0d1-aec3-4b29-a6a2-bce5f60011f0)




Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/1808charitha/ARP-Attack-and-Network-Sniffing/assets/132996838/b51acbd8-7aa5-4d59-bfd5-52c67b3cb6e1)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
