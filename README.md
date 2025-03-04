# CyberSecurity

# Computer Forensics 
The technical field of computer forensics finds and saves evidence from a computer device using investigative methods. Computer forensics is frequently utilized to find evidence that might be presented in court. Areas outside of investigations are also included in computer forensics. 

## Malware Forensics 
Analyzing the malicious software from its origin. 

## Challenges in Computer Forensics
**Encryption**: Encrypted files and communications are difficult to access without the nessesary decrytion keys, posing clallenges for forensics investigations.

**Cloud Computing**: The decentralized nature of cloud storage makes it harder to acquire and preserve evidence, as data can spread acress multiple servers in different jurisdiction.

**Evolving Technology**: As technology advances, forensic methods must continually evolve to hadle new types of devices, operating systems, and cyber threats.


## Keyboard
Ctrl + shift + T will open a new terminal on Kali Linux.
Alt + shift + S to rename the tab of the terminal.
ping <IPAddress> to ping the IP address.
sudo nano /etc/hosts to save the ipaddress for later for you to just put the username and ping the username with the indication of IP address.
nmap -p- silverplatter.thml -T5 -v  to check the available open ports.
nmap -p 22,80,8080 -A silverplatter.thml -v -T5 to check all the open ports, ip address, and the resources which you are searching on.

``` bash
PORT     STATE    SERVICE    VERSION
22/tcp   open     ssh        OpenSSH 8.9p1 Ubuntu 3ubuntu0.4 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   256 1b:1c:87:8a:fe:34:16:c9:f7:82:37:2b:10:8f:8b:f1 (ECDSA)
|_  256 26:6d:17:ed:83:9e:4f:2d:f6:cd:53:17:c8:80:3d:09 (ED25519)

80/tcp   open     http       nginx 1.18.0 (Ubuntu)
|_http-title: Hack Smarter Security
| http-methods: 
|_  Supported Methods: GET HEAD
|_http-server-header: nginx/1.18.0 (Ubuntu)

8080/tcp filtered http-proxy
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel
NSE: Script Post-scanning.
Initiating NSE at 05:53
Completed NSE at 05:53, 0.00s elapsed
Initiating NSE at 05:53
Completed NSE at 05:53, 0.00s elapsed
Initiating NSE at 05:53
Completed NSE at 05:53, 0.00s elapsed
Read data files from: /usr/bin/../share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 21.93 seconds
```
