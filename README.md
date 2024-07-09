# Personal Guide to Install Home Lab Server (Casa OS)

## Ubuntu Server Based Tutorial

**To create a Casa OS home lab, the first step is to install the desired OS (the author has tried the OS in the [following list](#list-of-os-that-have-been-tried) )**

Once the server is installed, the next step is to install Casa OS using the following command:

```
curl -fsSL https://get.casaos.io | sudo bash
```

Wait for the installation to finish

Then, if the Casa OS installation is complete, you can access Casa OS through the server's IP address on port 80 (ip_server:80)

**The issue I faced was with the firewall. You can enable port 80 on the Ubuntu Server firewall using the following command:**

```
sudo ufw allow 80
```

## List of OS that have been tried

- Ubuntu Server 22.04.4 LTS ✔️
- Fedora 40 ❌ ([udevil dependency problem](https://github.com/IceWhaleTech/CasaOS/issues/1149))
- Debian 🟡
- Proxmox 🟡
- SUSE 🟡
- CentOS 🟡
- Windows Server 🟡

## Another Tutorials
- [Ngrok Tunneling](/tunneling-ngrok.md)
