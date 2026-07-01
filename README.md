# Open-Arista-WM
A simple personal-use Arista AP wireless management
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

<img width="818" height="432" alt="image" src="https://github.com/user-attachments/assets/e6f6fd91-25fc-4ef7-a7d1-5b8e45fd5eeb" />


## Features implemented:
1. SSID &emsp;✅<br>
2. Link aggregation &emsp;✅<br>
3. AP version push &emsp;❌<br>
4. MESH &emsp;❌<br>
5. WIPS &emsp;❌<br>
6. AP reporting data storage and display &emsp;❌<br>
7. Web control &emsp;❌
<br>
<img width="815" height="594" alt="iShot Pro 2026-04-23 00 13 27" src="https://github.com/user-attachments/assets/65963ec8-ef26-461c-ac97-498d798033e4" />

arista ap-c360 version 16
<br><img width="612" height="770" alt="iShot Pro 2026-04-23 00 17 01" src="https://github.com/user-attachments/assets/38646df9-6aa5-4c0b-af7f-5c1aca3bd658" />
<br>
arista ap-c260 version 18
<br><img width="867" height="732" alt="SecureCRT 2026-06-15 04 14 21" src="https://github.com/user-attachments/assets/af482cc3-fe59-4cfc-a338-1c823e25d6d0" />
