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

![e4 1](https://github.com/Gayathriraj18/ARP-Attack-and-Network-Sniffing/assets/94154854/5981e989-1f6a-4c43-adaf-70b4bccba80f)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

![e4 2](https://github.com/Gayathriraj18/ARP-Attack-and-Network-Sniffing/assets/94154854/cec0ca5d-c4c2-4394-85df-374ef9c1e3f4)



 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

![e4 3](https://github.com/Gayathriraj18/ARP-Attack-and-Network-Sniffing/assets/94154854/dacb260d-4de8-44b4-9ede-a71e94d4485a)




In Kali issue the following commands:
sudo dsnifff

![e4 4](https://github.com/Gayathriraj18/ARP-Attack-and-Network-Sniffing/assets/94154854/3fdb3215-c2dc-4b7d-b37f-de6ae54b585e)



Invoke the wireshark and examine the various menus  and controls of the tool:

![e4 5](https://github.com/Gayathriraj18/ARP-Attack-and-Network-Sniffing/assets/94154854/bb967f15-537b-431e-9c5c-e5eb03fc1dd2)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
