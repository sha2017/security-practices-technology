# Applications
* Administrator Access is on a need to know basis 

## Grade 1 Security practice requirements: 
* Transport Encryption is a minimum requirement for applications.
* At least TLS 1.1 encryption used between application’s components
* At least SHA1 Encryption of passwords.
* Regular Updates of application software. 
* Strong randomly generated Admin passwords of at least 8 characters.

## Grade 2 Security practice requirements: 
* All of Grade 1’s security practices 
* Application level encryption of user data.  
* At least TLS 1.1 encryption used between application’s components
* At least SHA512 Encryption of passwords.
* Strong randomly generated Admin passwords of at least 12 characters.

## Grade 3 Security practice requirements: 
* All of Grade 2’s security practices 
* TLSA records should be present in DNS with correct fingerprints. 
* At least TLS 1.2, TLS 1.3 encryption used between application’s components.
* At least Bcrypt Encryption of passwords.
* Strong randomly generated Admin passwords of at least 22 characters.

## Grade 4 Security practice requirements: 
* All of Grade 3’s security practices 
* SAML based federated authentication must be used to ensure central storage of password hashes. 
* Following ciphers must be used preferred in the following order:
  - ECDH+AESGCM
  - ECDH+AES256
  - ECDH+AES128
  - DH+3DES
  - !ADH
  - !AECDH
  - !MD5

