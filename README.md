# 🔥 Task 4: Setup and Use a Firewall (Cyber Security Internship)

## ✅ Objective
Configure basic firewall rules on Linux using UFW to allow/block traffic and understand network filtering.

## 🛠 Tools Used
- OS: Ubuntu 22.04
- UFW (Uncomplicated Firewall)
- Terminal (Bash)

## 🧾 Steps Performed

1. **Checked if UFW is installed and enabled it**  
   `sudo ufw enable`

2. **Listed current firewall rules**  
   `sudo ufw status numbered`

3. **Blocked Telnet port 23**  
   `sudo ufw deny 23`

4. **Allowed SSH on port 22**  
   `sudo ufw allow 22`

5. **Tested blocking using telnet**  
   Attempted to connect: `telnet 127.0.0.1 23`

6. **Removed the block rule after test**  
   `sudo ufw delete deny 23`

## 📷 Screenshots
All screenshots are available in the `/screenshots` folder.

## 📘 What I Learned
- How to use UFW to manage firewall rules.
- How firewalls control incoming/outgoing traffic using port numbers.
- Importance of blocking insecure ports (like Telnet).

