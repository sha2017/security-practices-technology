# Physical Servers 
## Grade 1 Security practice requirements: 
* Key Sizes:  4096 minimum bits (SSH).
* Encryption: Full Disk Encryption of Physical Underlaying infrastructure.
* Chassis intrusion detection must be enabled if applicable. 
* DRAC, ILO and management interfaces must be updated on a regular basis. 

## Grade 2 Security practice requirements: 
* All of Grade 1’s security practices 
* SSHFP Record Stored in DNS with correct fingerprint.
* DRAC, ILO and management interfaces on dedicated secure Management Network. 
* Firewall active and dropping all unknown traffic. (whitelist firewall) 

## Grade 3 Security practice requirements:
* All of Grade 2’s security practices 
* All processes listening on TCP or UDP that are not required shutdown and disabled. 
* Fail to ban enabled and blocking IP’s on 3 failed login attempts. 

# Virtual Servers
## Grade 1 Security practice requirements: 
* Key Sizes:  4096 minimum bits (SSH).
* Encryption: Full Disk Encryption of Physical Underlaying infrastructure.

## Grade 2 Security practice requirements: 
* All of Grade 1’s security practices 
* SSHFP Record Stored in DNS with correct fingerprint.
* DRAC, ILO and management interfaces on dedicated secure Management Network. 
* Firewall active and dropping all unknown traffic. (whitelist firewall) 

## Grade 3 Security practice requirements: 
* All of Grade 2’s security practices 
* All processes listening on TCP or UDP that are not required shutdown and disabled. 
* Fail to ban enabled and blocking IP’s on 3 failed login attempts. 

## Grade 4 Security practice requirements:
* All of Grade 3’s security practices 
* Encryption of Virtual Server's disk drives. 
## Grade 5 Security practice requirements:
* All of Grade 4’s security practices 
