
# Azuro: Self-Adaptive AI for Edge Devices

**Azuro** is a self-adaptive, energy-efficient AI framework built in Python & PyTorch.  
It automatically freezes inactive weights after warm-up, reducing CPU usage by up to **40%**, and works fully offline — ideal for IoT, drones, sensors, and industrial edge devices.

---

## 🔹 Demo EXE

- Windows executable: `Azuro_demo.exe` (~130 MB)  
- Trial mode: 7 days OR 50 runs  
- Full version: HWID-locked license

### 📥 How to get the demo

1. Download the demo `.exe` from the [GitHub Release / cloud link]().  
2. Run the `.exe`. On first launch, it shows your **Hardware ID**.  
3. If no license is present, the demo runs in trial mode:
   - 7 days or 50 executions
4. To unlock full version:
   - Email your **Hardware ID** to `kretski1@gmail.com`
   - Receive `azuro.lic` → save next to `.exe`  
   - Next run automatically unlocks full functionality

---

https://youtu.be/tr2CduSidyM



- Live comparison: **GravOptAdaptiveE vs Adam**
- Metrics: mean `h`, freeze ratio (%), CPU %
- Reports saved: `azuro_demo_report.png` + `azuro_demo_report.html`

---

## 🔹 How it works

1. **Optimizer:** `GravOptAdaptiveE`  
   - Adaptive freeze/unfreeze of parameters  
   - Warm-up, median-based threshold, monitoring CPU usage  
2. **Tasks:** Tiny CNN / RNN demo  
3. **Visualization:** Live plot of loss, CPU%, adaptive h, freeze ratio  
4. **Report:** Generates **HTML + PNG** reports automatically

---

## 🔹 Installation (for source use)


Support

You can support the development with a voluntary donation (e.g. 10€):

https://buymeacoffee.com/azuro
