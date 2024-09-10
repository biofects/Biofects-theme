# 🚀 Biofects Theme
**Biofects Theme** is a modern, futuristic HUD display for Home Assistant, designed to be both visually striking and easy to use. **[WIP]**

<p align="center">
  <img src="images/biofects-mainpage.jpg" alt="Biofects Theme Main" width="400"/>
  <img src="images/biofects-sample.jpg" alt="Biofects Theme Sample Page" width="400"/>
</p>

---

## 🔍 About this Theme
I created the **Biofects Theme** to give my family a clean, easy-on-the-eyes interface with a simple layout that everyone can navigate. It's not just visually appealing but also designed to seamlessly integrate with additional plugins for a rich user experience.

- My Home Assistant runs in Docker on a server. I don't use the supervised version, nor do I send any data to Home Assistant servers. This is my personal choice, despite it requiring more manual management.
  
  <strong style="color:red;">I don’t know how it works with HAOS.</strong>

- I prioritize securing my network by blocking **phone home** calls from IoT devices, ensuring data privacy.
- My Home Assistant setup includes an array of devices, with plans to expand further. Here’s a snapshot of what I manage:

    - 💡 Hue
    - 🏠 Tuya
    - 📊 Grafana for monitoring
    - 🎞️ Emby for media
    - 🚪 Door locks
    - 🔒 Cameras
    - 💻 Local AI (on server)
    - 🚦 Pi Hole for ad-blocking
    - 🖥️ Full network & server monitoring, including GPU & storage
    - 🌀 Fans
    - And much more to come!

---

## 💸 Donations Welcome!
If you find this theme useful, please consider donating. Your support is greatly appreciated!

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TWRQVYJWC77E6)

---

## 🔧 Plugins I Use to Achieve My Layout
These are the essential plugins that helped me craft the Biofects Theme experience:

- [Sidebar Card](https://github.com/DBuit/sidebar-card) – For an easy-to-navigate sidebar.
- [Wall Panel](https://github.com/j-a-n/lovelace-wallpanel) – A powerful screen saver.
- [Card Mod](https://github.com/thomasloven/lovelace-card-mod) – Add custom styling to cards.
- [Restriction Card](https://github.com/iantrich/restriction-card) – Lock access to things like thermostats. 🔒
- [Unifi Gateway](https://github.com/custom-components/sensor.unifigateway)
- [Unifi Counter Sensors](https://github.com/clyra/unifics)
- [Simple Sticky Note](https://github.com/biofects/simple_sticky_note) – For quick notes.
- [Clock Weather Card](https://github.com/pkissling/clock-weather-card)

---

## 🚀 Installation Instructions

### HACS (Recommended)

#### Step-by-Step Guide

1. Ensure [HACS](https://hacs.xyz/) is installed in your Home Assistant.
2. Open the HACS panel, click the three dots in the top-right corner, and select **"Custom Repositories."**
3. Add the following URL as a **Custom Repository**:  
   [https://github.com/biofects/biofects-theme](https://github.com/biofects/Biofects-theme)  
   and select **"Theme"** as the category.
4. Click **"Add,"** then navigate to the **"Theme"** tab, click **"+ Explore & Download Repositories"** and search for "Biofects."
5. Install the theme and restart Home Assistant.
6. Go to **User Profile** in Home Assistant and select the Biofects theme.

---

## 🛠️ How I Created My Layout

To get the layout I wanted with Biofects Theme, I combined various plugins and customization:

1. Updated each dashboard to support **Wall Panel** and **Sidebar Card**.
2. YAML for content and views should be placed above the dashboard views.
3. Example box for clock-weather card configuration:  
   [Clock-Weather_card-configuration.yaml](./examples/Clock-Weather_card-configuration.yaml)
4. Full Lovelace dashboard configuration:  
   [lovelace-dashboard.yaml](./examples/lovelace-dashboard.yaml)

---

## 🐛 Support & Issues
If you encounter bugs or have feature requests, feel free to [open an issue](https://github.com/biofects/biofects-theme/issues) on the GitHub repository.

---

## 📜 License
This project is licensed under the MIT License.

