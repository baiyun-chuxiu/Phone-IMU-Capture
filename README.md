# 📱 Phone IMU Web Streamer (Pure Client-Side)

Real-time smartphone (iPhone / Android) built-in IMU motion telemetry acquisition, live waveform visualization, 3×3 rotation matrix calculation, and dataset export directly in mobile browsers.

**100% Pure Client-Side — 0 Backend, 0 Installation, 0 Shell Scripts.**

---

## 🌟 Features

- **Standard W3C Sensor API**: Native `DeviceMotionEvent` & `DeviceOrientationEvent`.
- **Full Sensor Telemetry**:
  - Linear Acceleration (X, Y, Z in G)
  - Gyroscope Rotation Rate (Pitch, Roll, Yaw in rad/s)
  - Attitude Angles (Roll, Pitch, Yaw in rad)
  - Calculated 3×3 Spatial Rotation Matrix
- **Real-Time Visualization**: Dynamic high-refresh canvas waveforms.
- **1-Click Recording & Export**: Output in `acc.txt`, `rotation_rate.txt`, `rotation_matrix.txt`, `imu_data.csv`, `imu_data.json`.
- **Zero-Setup Mobile Experience**: Simply open the web page on iPhone (Safari/Chrome) or Android, tap **Authorize**, and start streaming!

---

## 🚀 How to Deploy on GitHub

### 1. Create a new GitHub Repository
Create an empty repository on GitHub (e.g. `Phone-IMU`).

### 2. Push this folder to GitHub
```bash
cd Phone-IMU-WebDeploy
git init
git add .
git commit -m "feat: Initial release of Pure Phone IMU Web Streamer"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to repository **Settings** -> **Pages** -> Select **Deploy from a branch** -> `main` -> `/ (root)` -> **Save**.
- Open the resulting link on your smartphone!

---

## 📱 How to Use on iPhone / Android

1. Open the deployed URL in Safari (iOS) or Chrome (Android).
2. Tap **🛡️ Authorize & Start** on the floating banner.
3. On iOS, tap **Allow** when Safari prompts `"Allow website to access motion and orientation"`.
4. The motion data and live waveforms start streaming immediately!
