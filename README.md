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
### ARP spoofing: 
A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
#### OUTPUT:
![alt text](<Screenshot 2024-04-24 082027.png>)

### From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
#### OUTPUT:
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_12_04_2024_10_42sudo.png)

### dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
#### OUTPUT:
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_24_04_2024_10_42ds.png)


### In Kali issue the following commands:
sudo dsnifff
#### OUTPUT:
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_24_04_2024_10_42dsniff.png)


### Invoke the wireshark and examine the various menus  and controls of the tool:
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_12_04_2024_10_42invo.png)
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
