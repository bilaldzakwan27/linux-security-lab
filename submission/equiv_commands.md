# Command Equivalents Between Debian-based and RedHat-based Linux

## 1. Install Package
- Debian / Kali:
  sudo apt install nmap
- RedHat / CentOS:
  sudo dnf install nmap

## 2. Start SSH Service
- Debian / Kali:
  sudo systemctl start ssh
- RedHat / CentOS:
  sudo systemctl start sshd

## 3. Check Service Status
- Debian / Kali:
  systemctl status ssh
- RedHat / CentOS:
  systemctl status sshd

## 4. Add Firewall Rule
- Debian / Kali:
  sudo ufw allow 22/tcp
- RedHat / CentOS:
  sudo firewall-cmd --add-service=ssh --permanent
  sudo firewall-cmd --reload

## 5. View System Information
- Debian / Kali:
  uname -a
- RedHat / CentOS:
  uname -a
