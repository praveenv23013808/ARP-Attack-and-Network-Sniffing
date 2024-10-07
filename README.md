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
![image](https://github.com/user-attachments/assets/e5a55c4f-d8fe-4ab8-ad26-3623c2cd28bb)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/b5bce369-bc72-4d3c-8578-0d01c4bc6571)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![image](https://github.com/user-attachments/assets/c8475a3f-e618-4a24-9d32-64fc9d58b644)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/6b2fb5f6-d28f-4e1f-b2b9-daf417a9a9db)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/bc0f36e7-9fc2-4784-9b74-e38ca6cd85e5)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
