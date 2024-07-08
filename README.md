# Personal Guide to Install Home Lab Server (Casa OS)

## Ubuntu Server Based Tutorial
**To create a Casa OS home lab, the first step is to install the desired OS (the author has tried the OS in the [following list](##List-of-OS-that-have-been-tried) )**

Once the server is installed, the next step is to install Casa OS with the following command:

```
curl -fsSL https://get.casaos.io | sudo bash
```

Wait for the installation to complete

Then, if the Casa OS installation is complete, you can access Casa OS via the server IP on port 80 (ip_server:80)

**The problem I encountered is dealing with the firewall. You can enable port 80 on the Ubuntu Server firewall with the following command:**

```
sudo ufw allow 80
```

**English Translation:**

**List of tried operating systems:**

- Ubuntu Server 22.04.4 LTS v
- Fedora Server x
- Debian x

**To set up a Casa OS home lab, the first step is to install the desired operating system (the author has already tried the operating systems in the following list)**

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

- Ubuntu Server 22.04.4 LTS v
- Fedora Server x
- Debian x
