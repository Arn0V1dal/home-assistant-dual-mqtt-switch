# 💡 Dual MQTT Switch – Room Lights

This Home Assistant automation blueprint allows you to control two groups of lights using a dual-button MQTT switch. Each button can toggle one or more lights, and long-press increases brightness progressively.

Perfect for bedside lamps, living rooms, or any scenario where you'd like intuitive tactile control over multiple lights.

---

## ✨ Features

- 🔘 **Single Left Press** – Toggle left lights (user-defined brightness)
- 🔘 **Single Right Press** – Toggle right lights (user-defined brightness)
- 🔘 **Simultaneous Press** – Toggle both left and right lights
- 📈 **Hold Left** – Gradually increase brightness on left lights
- 📈 **Hold Right** – Gradually increase brightness on right lights

---

## ⚙️ Inputs

- **MQTT Switch** – Device with dual-button support (e.g., Zigbee, Wi-Fi switch with MQTT integration)
- **Left Light** – One or more lights to control with the left button
- **Right Light** – One or more lights to control with the right button
- **Left Brightness** – Brightness level to set when turning on left lights
- **Right Brightness** – Brightness level to set when turning on right lights

---

## 🚀 How to use

1. Copy the blueprint YAML file into your Home Assistant configuration directory:
   ```bash
   config/blueprints/automation/your_user/dual_mqtt_switch_room_lights.yaml
   ```

2. In Home Assistant:
   - Go to *Settings* → *Automations & Scenes* → *Blueprints*
   - Click *Import Blueprint*
   - Load your file and create a new automation using the blueprint

---

## 📝 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🙌 Credits

Developed by Arnaud with help from ChatGPT.
