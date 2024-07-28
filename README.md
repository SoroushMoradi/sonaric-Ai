# sonaric-Ai

from Dante Github.




#Sonaric AI Node

Reward: Confirmed

Minimal Systems Requirements:
✅ 4 GB RAM  
✅ 2 CPU cores  
✅ 20 GB free disk space  
✅ 64-bit operating system  

Installation (Choose One):  
▫️ Via VPS-Linux (Recommended):   
1. Run Our Script  
```
wget https://raw.githubusercontent.com/dante4rt/Ramanode-Guides/main/Sonaric/sonaric.sh && chmod +x sonaric.sh && ./sonaric.sh   
```
2. Check If your Node Sucessfully Installed  
```
sonaric node-info  
```
3. Run GUI  
➖ Open your local terminal  
➖ Change "user@your-vps-ip" with yours (eg: root@121.243.762)  
```
ssh -L 127.0.0.1:44003:127.0.0.1:44003 -L 127.0.0.1:44004:127.0.0.1:44004 -L 127.0.0.1:44005:127.0.0.1:44005 -L 127.0.0.1:44006:127.0.0.1:44006 user@your-vps-ip
```
4. Backup  
➖ Via GUI:  
- visit http://localhost:44004  
- click ⚙️ icon, then export json file, save it to the safe place.  
➖ Via VPS:  
```
sonaric identity-export -o mysonaric.identity  
```
save mysonaric.identity file to the safe place.  

5. Leaderboard
Track your position here (https://tracker.sonaric.xyz/), if your node exist then you're GMI 😊
