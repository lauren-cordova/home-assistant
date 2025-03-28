# 🏡 Home Assistant Setup Guide

 This repo has notes and useful links I've accumulated over time. Sharing for anyone wanting to get into [Home Assistant](https://www.home-assistant.io/)! Feel free to open an issue or submit a pull request with feedback or feature suggestions.

---

## 🚀 **How to Get Started!**

Follow this guide to set up your Home Assistant (HA) instance on a Raspberry Pi. You'll need to purchase some hardware and install a few key programs to get up and running.

---

## 🛒 **1. Purchase Hardware**

### 🔹 **1a. Raspberry Pi**
- [Raspberry Pi 5 (8GB)](https://www.amazon.com/dp/B0CK2FCG1K?ref=ppx_yo2ov_dt_b_fed_asin_title) – I chose the newest model for better performance.  
- The Raspberry Pi 4 also works well if you want to save some money.  
- **⚠️ If you get the Pi 5, it's recommended to have active cooling!**  

---

### 🔹 **1b. Power Cord**
- [Power Cord](https://www.amazon.com/dp/B0CQ2DL2RW?ref=ppx_yo2ov_dt_b_fed_asin_title) – Many options will work, but this is the one I use.  

---

### 🔹 **1c. Micro SD Card**
- Any Micro SD card will work.  
- Make sure to have an adapter to plug it into your computer if needed.  

---

### 🔹 **1d. Case**
- [Case with Cooling (for RP5)](https://www.amazon.com/dp/B0CTBJ42P9?ref=ppx_yo2ov_dt_b_fed_asin_title) – A case is optional but recommended for protection.  
- **⚠️ The fans on this one are loud, but it's really cute!**

---

## 🛠️ **2. Set Up Programs**

### 🔹 **2a. Install HA OS**
- Follow the official [HA OS installation instructions](https://www.home-assistant.io/installation/raspberrypi).  
- After installing, complete the [onboarding steps](https://www.home-assistant.io/getting-started/onboarding).  

---

### 🔹 **2b. Install HACS**  
HACS allows you to install custom apps and extensions for Home Assistant:  
1. Install the app → [Get HACS](https://www.hacs.xyz/docs/use/download/download/)  
2. Add HACS integration → [Set up HACS](https://www.hacs.xyz/docs/use/configuration/basic/#setting-up-the-hacs-integration)  

---

## 🎨 **3. Add Cool Stuff**  

### 🔹 **3a. Add-Ons**  
Use HACS to search and install these helpful add-ons:  
✅ Bubble Card  
✅ browser_mod  
✅ card-mod  
✅ simpleicons  

---

### 🔹 **3b. Devices & Integrations**  
- Go to `Settings > Devices & Services`  
- Add the discovered devices!  
- You can also search for integrations and connect them.  

---

## 🌐 **🔧 ADVANCED: Set Up Remote Access**  
- **Recommend fixing the HA IP address** before doing this!
- Shoutout to [Cloudflare] (https://www.cloudflare.com/) for offering this free and secure solution!
- Follow this detailed video for remote access setup:  
👉 [Remote Access Setup Guide](https://www.youtube.com/watch?v=JGAKzzOmvxg)  

---

## 🎯 **✅ Completed!**  
You’re now ready to automate your home with Home Assistant! 🎉  

---

### 🏆 **Need Help?**  
- Check out the official [Home Assistant documentation](https://www.home-assistant.io/docs/)  
- Visit the [Home Assistant Community](https://community.home-assistant.io/) for support  

---

> *Happy automating!* 😎
