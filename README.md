# A.G.A.P. Seizure Monitoring System

**Kapitolyo High School STEM Research Project**

A wearable seizure detection device powered by ESP32-C3 that continuously monitors biosignals (sEMG, Accelerometer, Gyroscope, Pulse Oximeter) and updates live telemetry to GitHub Pages.

## Live Dashboard
Access the live monitoring web dashboard here:  
`https://krystalcasipit-rgb.github.io/agap-monitor/`

## Sensor Specifications & Thresholds
- **sEMG Sensor**: Muscle spasms (> 2.01 V / 2500 raw threshold)
- **MPU6050 Accelerometer/Gyroscope**: Tremors (> 2.50 G / > 300 deg/s)
- **MAX30102 Heart Rate Sensor**: Tachycardia (> 120 BPM)
