# bolita-dexcom
Diabetes monitor and voice assistant for the Xiaozhi Bolita V2
# Bolita Dexcom Monitor 🩺
A custom package for the Xiaozhi "Bolita" to display real-time Dexcom glucose levels.

## How to use:
1. Add this to your `Ball_v2.yaml`:
   ```yaml
   packages:
     dexcom: github://rilucca/bolita-dexcom/dexcom_package.yaml@main
   
   substitutions:
     dexcom_glucose_sensor: sensor.your_glucose_entity
     dexcom_trend_sensor: sensor.your_trend_entity
