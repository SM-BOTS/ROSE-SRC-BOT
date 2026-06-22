<p align="center">
  <img src="https://graph.org/file/71c6a6f6fcd1536ff1177.jpg" alt="Rose Src Bot Logo" width="150" height="150" style="border-radius: 50%;">
</p>

<h1 align="center">🌹 𝐑𝐎𝐒𝐄-𝐒𝐑𝐂-𝐁𝐎𝐓 🌹</h1>

<p align="center">
  <a href="https://github.com/SM-BOTS/ROSE-SRC-BOT/stargazers"><img src="https://img.shields.io/github/stars/SM-BOTS/ROSE-SRC-BOT?style=for-the-badge&color=ff3366&logo=github" alt="Stars"></a>
  <a href="https://github.com/SM-BOTS/ROSE-SRC-BOT/network/members"><img src="https://img.shields.io/github/forks/SM-BOTS/ROSE-SRC-BOT?style=for-the-badge&color=00c853&logo=github" alt="Forks"></a>
  <a href="https://python.org"><img src="https://img.shields.io/badge/Made%20With-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Made With Python"></a>
</p>

<p align="center">
  <b>An Advanced, Powerful and Highly Modular Telegram Group Management Bot built with Python.</b>
</p>

---

### 🌟 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

*   🛡️ **Advance Security Tools:** Protects your group from spammers and malicious entities automatically.
*   🤖 **Anti-Service & Anti-Flood:** Clean up service messages (joins/leaves) and control flood attacks instantly.
*   🚫 **Powerful Filters & Notes:** Create custom responses and save data commands effortlessly.
*   🔐 **Captcha Verification:** Filter out automated user accounts and VoIP bot attacks upon entry.
*   📢 **Multi-Force Subscribe:** Ensure members join your required backup or main channels before interacting.
*   🗄️ **Database Support:** Smooth management powered by MongoDB for long-term data persistence.

---

### 🚀 𝐃𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭 𝐌𝐞𝐭𝐡𝐨𝐝𝐬

#### 💜 Deploy on Heroku

Easily host your bot on Heroku by clicking the button below:

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/SM-BOTS/ROSE-SRC-BOT)

#### 💻 VPS / Local Hosting

Follow these commands to deploy on your Linux VPS:

```bash
# Update and install dependencies
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install python3-pip -y

# Clone the repository
git clone [https://github.com/SM-BOTS/ROSE-SRC-BOT](https://github.com/SM-BOTS/ROSE-SRC-BOT)
cd ROSE-SRC-BOT

# Install requirements
pip3 install -r requirements.txt

# Configure your environment variables in config.py or .env
# Run the bot
python3 -m tg_bot
