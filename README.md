# Micropic Energy Meter


## ⚡ Overview

Micropic Energy Meter is a custom Home Assistant integration that helps you monitor and manage energy consumption and production in real-time. Designed to provide seamless integration with your existing Home Assistant setup, this integration is perfect for users who want to track energy data and send updates via MQTT.

With **Micropic Energy Meter**, you can:
- Monitor **power production** and **energy consumption** with customizable sensors.
- Send energy data in real-time to MQTT brokers.
- Configure update intervals and topics directly from the Home Assistant UI.
- Enjoy a visually appealing icon and logo for easy identification.

---

## 🚀 Features

- **Real-time Energy Monitoring:** View and track energy data from sensors in real-time.
- **Flexible MQTT Integration:** Send data to MQTT brokers with a customizable topic.
- **User-Friendly Configuration:** Configure sensors, topics, and update intervals directly from the Home Assistant interface.
- **Multilingual Support:** Available in English and Spanish (more languages coming soon).
- **Custom Branding:** Includes an intuitive icon and logo for better integration visibility.

---

## 📦 Installation

### **Manual Installation**
1. Download the integration from [this repository](https://github.com/ProyectosMicroPIC/micropic_energy_meter).
2. Place the `micropic_energy_meter` folder in the `custom_components` directory of your Home Assistant installation:
      /config/custom_components/micropic_energy_meter/
3. Restart Home Assistant.

### **HACS Installation**
1. Add this repository to HACS as a custom repository.
2. Search for **Micropic Energy Meter** in HACS.
3. Install and restart Home Assistant.

---

## 🔧 Configuration

1. Go to **Settings > Devices & Services** in Home Assistant.
2. Click **Add Integration** and search for `Micropic Energy Meter`.
3. Enter the required details:
- **Power Sensor:** Entity ID for the power production sensor.
- **Consumption Sensor:** Entity ID for the consumption sensor.
- **MQTT Topic:** Topic to which the energy data will be published.
- **Update Interval:** Frequency (in seconds) for updates.

4. Save and start monitoring your energy data!

---

## 📚 Documentation

- **Integration Details:** [Link to the integration documentation](https://github.com/tu-usuario/micropic_energy_meter/wiki)
- **Home Assistant Documentation:** [Home Assistant Custom Integrations](https://developers.home-assistant.io/docs/integration_index/)
- **MQTT Documentation:** [MQTT Protocol Basics](https://mqtt.org/)

