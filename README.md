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
![4 1](https://github.com/Gopikakarthik/ARP-Attack-and-Network-Sniffing/assets/121235427/f25f7b55-5ea4-4069-9991-a1616bd42675)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![4 2](https://github.com/Gopikakarthik/ARP-Attack-and-Network-Sniffing/assets/121235427/68f7baf9-82e2-486a-abce-4cc9bc3290dd)



 dsniff:
 
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![4 3](https://github.com/Gopikakarthik/ARP-Attack-and-Network-Sniffing/assets/121235427/465926f5-4f00-41cc-a962-fc0271bd41a6)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![4 5](https://github.com/Gopikakarthik/ARP-Attack-and-Network-Sniffing/assets/121235427/0da4e1aa-f732-4ee2-ab5a-02b1aca2c11b)




Invoke the wireshark and examine the various menus  and controls of the tool:
![4 6](https://github.com/Gopikakarthik/ARP-Attack-and-Network-Sniffing/assets/121235427/79241b95-88e9-42c0-b08c-4b551558fe30)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
