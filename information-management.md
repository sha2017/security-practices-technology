# Backups: 

## Grade 1 Security practice requirements: 
* Stored Offsite 
* Management Channels to and from backup components using TLS.

## Grade 2 Security practice requirements: 
* All of Grade 1’s security practices 
* Application Data must be encrypted separately to backup data  to lower risk of application bugs that can affect recovery of user information. 
* Data Encrypted with Per Server key and Master Key (TLS). 

## Grade 3-A Security practice requirements: 
* All of Grade 2’s security practices 
* Master key must be stored on Hardware HSM with a securely randomly generated password.

## Grade 3-B Security practice requirements: 
* All of Grade 2’s security practices 
* Master key must be in shards with a 66% voting required for retrieval of master key in emergency situations. 

## Grade 4 Security practice requirements: 
* All of Grade 3’s security practices 

## Grade 5 Security practice requirements: 
* All of Grade 4’s security practices 
