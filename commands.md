# Commands used in Linux Lab

## System Information

```bash
whoami
hostname
lsb_release -a
ip a
```

## Update System

```bash
sudo apt update
sudo apt upgrade -y
```

## User Management

```bash
sudo adduser jsmith
sudo adduser mjones
who
groups jsmith
```

## Group Management

```bash
sudo groupadd it
sudo groupadd hr
sudo usermod -aG it jsmith
sudo usermod -aG hr mjones
```

## Files & Directories

```bash
pwd
ls
ls -l
mkdir Projects
cd Projects
cp file1.txt backup.txt
mv oldfile.txt newfile.txt
rm filename.txt
rm -r directoryname
```

## Permissions

```bash
chmod 755 filename
sudo chown username:group filename
```

## Monitoring

```bash
df -h
free -h
top
```

## Networking & SSH

```bash
ping google.com
sudo systemctl status ssh
sudo systemctl enable ssh
```

## System Control

```bash
sudo reboot
sudo shutdown now
exit
```

## Server Details

* Hostname: `ubuntu-server01`
* OS: `Ubuntu Server 26.04 LTS ARM64`
* Platform: `VirtualBox 7.2.8`
* User: `galid23`

