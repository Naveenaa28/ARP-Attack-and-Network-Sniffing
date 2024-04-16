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
From kali linux issue the command : sudo arpspoof -i eth0 -t
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/131433133/4441e68f-8b9e-4a5d-a369-5aa673e06f2f)
From Kali linux issue the command : sudo arpspoof -i etho -t 
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/131433133/11280e19-939f-4e60-bdaa-112cf83881b7)
dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/131433133/90142c2e-f0d4-46fb-9ac7-d9eb6502c090)
In Kali issue the following commands: sudo dsnifff
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/131433133/526a9746-561e-47af-8da8-f3aea123be11)
Invoke the wireshark and examine the various menus and controls of the tool:
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/131433133/5ab3363c-812f-4496-ab53-6df2f07a3aee)
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
