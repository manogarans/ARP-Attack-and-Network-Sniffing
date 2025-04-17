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
![Screenshot 2025-04-17 093115](https://github.com/user-attachments/assets/6a3d7b61-1f6f-406b-b249-2cbf281a094b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-04-17 093126](https://github.com/user-attachments/assets/4ffb55df-b283-4f95-8929-74ad808e0bfd)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2025-04-17 093138](https://github.com/user-attachments/assets/98a11841-e660-499b-8b6e-232b153bb7c8)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![Screenshot 2025-04-17 093236](https://github.com/user-attachments/assets/03756b27-43c4-4ba8-ae0c-e902064d5be1)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
