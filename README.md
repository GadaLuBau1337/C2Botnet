<h1 align="center">SonicBotnet</h1>

<br>

 **SonicBotnet** is a basic open source [denial of service](https://en.wikipedia.org/wiki/Denial-of-service_attack) [botnet](https://en.wikipedia.org/wiki/Botnet) system written in Python 3, consists of a connect and control server and a bot malware script.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br>

# Installation
1. Install Git and Python 3 on your server.
2. Clone the SonicBotnet Github repository to your server via Git: `$ git clone https://github.com/GadaLuBau1337/C2Botnet`.
3. Change the host address and C&C port in the configuration section in [bot.py](src/Payload/bot.py) to your server address and C&C port.
4. Install the requirements.txt
5. Start the C2 server by executing the command: `$ python main.py`.
6. Add accounts in [logins.txt](/src/logins.txt) using the format: `username:password:yyyy-mm-dd`.
7. Configure the port on the [config.json](/src/config.json) `{
"cnc_host": "0.0.0.0",
  "reg_host": "0.0.0.0",
  "cnc_port": 5511,
  "reg_port": 5512
}`.

8. Connect to the server through [PuTTY](https://www.putty.org/) on a raw socket connection.

<br>

📍 *Compiling the malware and installing it on vulnerable devices won't be told as it's highly illegal to get remote access to devices without permission. Use of this project for illegal activities is at own risk! I'm not responsible for any of your taken actions!*

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br>

<br>

# Ideas
1. `Method:  OVH | Bypass OVH` 
2. `Method:  POST | POST Flood` 
3. `Method:  STRESS | Send HTTP Packet With High Byte`
4. `Method:  OSTRESS | STRESS Without Proxy`
5. `Method:  BYPASS | Bypass Normal AntiDDoS` 
6. `Method:  DGB | DDoS Guard Bypass` 
7. `Method:  AVB | Arvan Cloud Bypass`
8. **Send attacks with API's** 
9. **Optimize malicious code**

<br>

# Owner Code
📌**Credits:** https://github.com/GadaLuBau1337

<br>

---

**👑Author:**

- **GadaLuBau1337**
- **WhatsApp : +6283114593730**

<div>
    
  [![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/none)
  [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/none/)
  [![Tiktok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@gada_lu_bau)
</div>
