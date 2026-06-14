# Open-Arista-WM
A simple personal-use Arista AP wireless management
<br>Join Discord, let's develop together
<br>https://discord.gg/nz3s7aHa
<br>Arista AP models:<br>
Device versions 12+ (mabye)
## Set Your Server IP/IPDNS
```
[config]$ help server discovery
Command:
Name              : server discovery
Description       : Set server discovery settings
Arguments (* suffix = Mandatory):
method*           : (id|ipdns) Server Discovery Method
pri               : (0-655254) for id based discovery; (IP addr|DNS string) of primary server for ipdns based discovery
sec               : NA for id based discovery; (IP addr|DNS string) of secondary server for ipdns based discovery
```

```
#eg1:
server discovery method ipdns pri 192.168.1.100 sec 192.168.1.101
#eg2:
server discovery method ipdns pri primary.server.local sec backup.server.local
#eg3:
server discovery method id pri 12345
```

<br>
Features implemented:<br>
1. SSID &emsp;✅<br>
2. Link aggregation &emsp;✅<br>
3. AP version push &emsp;❌<br>
4. MESH &emsp;❌<br>
5. WIPS &emsp;❌<br>
6. AP reporting data storage and display &emsp;❌<br>
7. Web control &emsp;❌
<br>
<img width="815" height="594" alt="iShot Pro 2026-04-23 00 13 27" src="https://github.com/user-attachments/assets/65963ec8-ef26-461c-ac97-498d798033e4" />
<img width="612" height="770" alt="iShot Pro 2026-04-23 00 17 01" src="https://github.com/user-attachments/assets/38646df9-6aa5-4c0b-af7f-5c1aca3bd658" />
