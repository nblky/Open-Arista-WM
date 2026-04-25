# OpenVWM
Open Virtual Wireless Manager
<br>README.md Translated by DeepSeek
## Name Origin:
H3C's wireless controller is called AC, and their virtualized wireless controller is called VAC. Hence, the project is named OpenVWM.  

## Project Origin:
I have an addiction to picking up "e-waste." One day in August 2024, I ordered a discontinued surveillance product on Taobao, and it ended up sitting there for over a year. Since I was unemployed and bored at home after quitting my job, I started tinkering with that camera. With the help of buyer reviews in the product link and AI, I successfully "resurrected" the device's service. After that project ended, I remembered the Arista AP that had been lying in the corner of my home for over six months (because Arista's AP doesn't have a fat/thin integration mode like Aruba's; it can only be managed by its own CVP/CV-CUE). So I thought I'd give it a try with AI to see if I could build my own wireless control platform. 


## Project Statement:
!!! This project is strictly for learning/research purposes on the communication principles between various APs and wireless controllers !!!
!!! This project shall not be used for commercial purposes !!!
!!! This project does not provide paid customizations for commercial use !!!
!!! If you violate these terms and use the project improperly, you bear all consequences; this project (and its author) assumes no responsibility !!!

1. The entire code is written by AI, implementing only some key functions, with corresponding scripts.
2. Need a UI expert for front-end adaptation (the AI is already overwhelmed).

## Overall Project Plan:
Adapt wireless controllers from some manufacturers on the market (possibly only Arista for now).
<br>
## Project Progress / Adaptation Status:
&emsp;Initial adaptation for Arista APs is complete; a UI expert is urgently needed.<br>
&emsp;Looking for any official AP upgrade packages from manufacturers.<br>
&emsp;

Arista AP models:<br>
Device versions 12, 13, 16<br>
&emsp;WiFi 6E and below products &emsp;✅<br>
&emsp;WiFi 7 &emsp;❌<br>

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
