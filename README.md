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
![Screenshot 2025-04-17 093615](https://github.com/user-attachments/assets/e6e6eb33-d64c-4c5f-8a2f-0073c3057353)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-04-17 093115](https://github.com/user-attachments/assets/208f35fb-13f8-4e8c-af7c-f007d8515033)




 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2025-04-17 093126](https://github.com/user-attachments/assets/a0f3370d-7ebc-442a-be4c-3e918a03c507)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-04-17 093138](https://github.com/user-attachments/assets/a6729b80-ae63-4e4c-a7c9-2923e95b16af)


Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-04-17 093236](https://github.com/user-attachments/assets/a9355ea3-d506-4375-922a-c41189cf303a)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
