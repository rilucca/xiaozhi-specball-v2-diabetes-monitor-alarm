# bolita-dexcom
Diabetes monitor and voice assistant for the Xiaozhi Bolita V2
# Bolita Dexcom Monitor 🩺
A custom package for the Xiaozhi "Bolita" to display real-time Dexcom glucose levels.

# 🍄 Bolita Mario Dexcom (Beta 1)

### 📸 Bolita en Acción
<img src="BolitaHight.jpg" width="220"> <img src="BolitaMarioListen.jpg" width="220">

### 📝 Quick Setup (3 Steps)

1. **Assets:** Place the `assets_round/` folder in your local ESPHome directory.
2. **Secrets:** Open your `secrets.yaml` and fill in your credentials exactly like this:

```yaml
# secrets.yaml
wifi_ssid: "YOUR_WIFI_NAME"
wifi_password: "YOUR_WIFI_PASSWORD"
dexcom_username: "YOUR_DEXCOM_USER"  # Example: locolucca

