## Inter Server
### Unable to change VPS password
```
1. Reinstall OS and change the VPS password
   a. Provide the login password and New VPS root password
2. Try different password and format
```
### Setup VPS Domain in DNS Manager
```
1. Get the domain and point to VPS IP address
2. Add the DNS entry sample: mydomain.com 1.1.1.1 (vps ip)
```
### Setup Domain to read VPS
```
1. find the VPS Nameservers
    sample: a. cdns1.interserver.net, cdns2.interserver.net, cdns1.interserver.net
2. Then add these to your Domain name DNS
    a. you will wait 24hrs for this to take effect
```
### Setup Free business email (Zoho Email)
```
1. Register for Free business email in Zoho
2. Create a Free email
3. Register your domain
4. Choose TXT record for registration
5. In your VPS find the DNS Manager and add the TXT record from Zoho after registration
```
