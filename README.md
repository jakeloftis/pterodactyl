### Pterodactyl Install
## Part 1
```
apt update && apt upgrade -y
```

```
bash <(curl -s https://pterodactyl-installer.se)
```

```
Option 2
```
## Part 2
```
Database name (panel): leave blank
```

```
Database username (pterodactyl): leave blank
```

```
Password: generate a secure password
```

```
Select timezone: America/Chicago
Other timezones available at: https://www.php.net/manual/en/timezones.america.php
```

```
Provde the email address that will be used to configure Let's Encrypt and Pterodactyl: enter your email
```

```
Email address for the initial admin accout: enter your email
```

```
Username for the initial admin account: admin
```

```
First Name: your first name
```

```
Last name: your last name
```

```
Password for the initial account: generate a secure password
```
## Part 3
```
Set the FQDN of this panel (panel.example.com): enter your domain address for the panel
DNS Record Type: A
Name: panel
Content: VPS IP address
Proxy status: DNS only (off)
```

```
Do you want to automatically configure UFW (firewall)?: y
```

```
Do you want to automatically configure HTTPS using Let's Encrypt?: y
```

```
I agree that this HTTPS request is performed: y
```

```
Initial configuration completed. Continue with installation?: y
```

```
Enable sending anonymous telemetry data?: no
```

```
You must agree in order to register with the ACME server. Do you agree?: Y
```
## Part 4
```
Installation of panel completed. Do you want to proceed to wings installation?: y
```

```
Do you want to automatically cdonfigure UFW (firewall)?: y

```

```
Do you want to automatically configure a user for database hosts?: y
```

```
Do you want to configure MySQL to be accessed externally?: y
```

```
Enter the panel address (blank for any address): enter your domain address for the panel
```

```
Would you like to allow incoming traffic to port 3306?: y
```

```
Database host username (pterodactyluser): leave blank
```

```
Database host password: generate a secure password
```

```
Do you want to automatically configure HTTPS using Let's Encrypt?: y
```

```
Set the FQDN to use for Let's Encrypt (node.example.com): enter your domain address for the node
DNS Record Type: A
Name: node
Content: VPS IP address
Proxy status: DNS only (off)
```

```
I agree that this HTTPS request is performed: y
```

```
Enter the email address for Let's Encrypt: enter your email address
```

```
Proceed with installation?: y
```
