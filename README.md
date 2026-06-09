Hardend an SSH server on CentOS Stream 9 Linux VM

## What I did
- Generated ed25519 SSH key pair
- Set 700 permissions on ~/.ssh directory
- Set 600 permissions on private key and authorized_keys
- Disabled root login in sshd_config
- Disabled password authentication
- Enabled public key authentication only
- Restarted sshd service and verified with systemctl

- - Verified SSH connection from Windows PowerShell using key-based authentication
- Confirmed root login blocked and password authentication disabled

## Skills practiced 
Linux * SSh * chmod * sshd_config * systemctl * Security Hardening
