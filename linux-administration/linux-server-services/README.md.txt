# Linux Server Services (Enterprise Lab)

## 🎯 Purpose
Set up and manage core infrastructure services in a Linux environment, including DHCP, DNS, web server and database.

---

## 🏢 Scenario
A simulated internal company network where a Linux server provides:

- IP address management (DHCP)
- Name resolution (DNS)
- Web services (Nginx)
- Database services (MySQL)

The environment is built in a virtualized lab using Ubuntu Server.

---

## 🧱 Environment
- Ubuntu Server 24.04 LTS
- Hyper-V (internal virtual network)
- Multiple virtual machines

---

## ⚙️ Services Implemented

### 🔹 DHCP (isc-dhcp-server)
- Configured subnet and IP range
- Client successfully received IP address

### 🔹 DNS (Bind9)
- Configured custom zone
- Tested using dig and ping

### 🔹 Web Server (Nginx)
- Installed and configured Nginx
- Created custom web page

### 🔹 Database (MySQL)
- Created database and tables
- Inserted and verified data

---

## 🔍 Troubleshooting
- Fixed DHCP syntax errors
- Validated configs before restart
- Used systemctl status for services

---

## 🌐 Result
All services were successfully deployed:
- DHCP working
- DNS resolving domain
- Web server accessible
- Database storing data

---

## 📸 Screenshots

### DHCP
![DHCP](screenshots/dhcp-ip.png)

### DNS
![DNS DIG](screenshots/dns-dig.png)
![DNS PING](screenshots/dns-ping.png)

### Web Server
![Nginx](screenshots/nginx-web.png)

### Database
![MySQL](screenshots/mysql-data.png)

### Service Status
![Service](screenshots/service-status.png)