#Manjaro Install

## Key Points
* Wants an EFI partition for booting
* I had to format the drive completely to get this working properly - after nearly a day of trying

## Setting Up Family Shield DNS 
### Helpful Resources
* https://wiki.manjaro.org/index.php?title=Networking#Manually_Setting_DNS_Servers
* https://forum.manjaro.org/t/setting-a-dns-or-nameserver/46186/2

### Steps 
* Edit /etc/resolvconf.conf
* Set DNS to 
  
    208.67.222.123
    208.67.220.123
