Linux System Administration Lab - Commands Reference

System Information

Display Current User

whoami

Display Hostname

hostname

Display Ubuntu Version

lsb_release -a

Display IP Address

ip a

⸻

System Updates

Update Package Lists

sudo apt update

Upgrade Installed Packages

sudo apt upgrade -y

⸻

User Management

Create a User

sudo adduser jsmith

Delete a User

sudo deluser jsmith

View Current User

whoami

⸻

Group Management

Create a Group

sudo groupadd it

Add User to Group

sudo usermod -aG it jsmith

View User Groups

groups jsmith

⸻

File and Directory Management

Create a Directory

mkdir company

Create Multiple Directories

mkdir hr it finance

List Files

ls

List Detailed Information

ls -la

Change Directory

cd directory_name

Display Current Directory

pwd

⸻

File Permissions

Change Ownership

sudo chown jsmith file.txt

Change Permissions

chmod 755 file.txt

View Permissions

ls -l

⸻

System Monitoring

View Disk Usage

df -h

View Memory Usage

free -h

View Running Processes

top

View CPU Information

lscpu

⸻

Networking

View Network Interfaces

ip a

Test Network Connectivity

ping google.com

Display Routing Table

ip route

⸻

SSH

Verify SSH Service Status

systemctl status ssh

Start SSH Service

sudo systemctl start ssh

Enable SSH at Boot

sudo systemctl enable ssh

⸻

Shutdown and Reboot

Reboot Server

sudo reboot

Shut Down Server

sudo shutdown now
