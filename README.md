
---



---

## 🧠 Brain

### Raspberry Pi
*Runs Home Assistant OS*

- ✅ Has a ready-made interface (dashboard)
- ✅ Connects to your Wi-Fi
- ✅ The "brain" that controls everything

📡 **Communication:** Wi-Fi / Zigbee

---

## 🔌 Devices

### Smart Switches
*Installed behind walls*

| Device | Purpose |
|--------|---------|
| **Shelly 1PM** | Controls AC (with power monitor) |
| **Shelly 1PM** | Controls Refrigerator |
| **SONOFF ZBMINI** | Controls Lights |

---

## 📱 Control Methods

### How You Control It

| Method | Location |
|--------|----------|
| ✅ Touch Screen | Wall panel |
| ✅ Phone App | Anywhere |
| ✅ Computer Browser | Anywhere |

---

## 🔄 System Architecture

### Level 1: Brain
- **Raspberry Pi** — Home Assistant OS
- Dashboard interface
- Wi-Fi connected

⬇️ *Wi-Fi / Zigbee*

### Level 2: Devices
- **Shelly 1PM** → AC Unit
- **Shelly 1PM** → Refrigerator  
- **SONOFF ZBMINI** → Lights

⬇️ *User Control*

### Level 3: Interfaces
- **Touch Screen** — Wall panel
- **Phone App** — Anywhere
- **Computer Browser** — Anywhere

---

## 📊 System Overview

```
Raspberry Pi (Brain)
       │
       │ Wi-Fi / Zigbee
       ▼
  Smart Switches
       │
       ├── Shelly 1PM → AC Unit
       ├── Shelly 1PM → Refrigerator
       └── SONOFF ZBMINI → Lights
       │
       ▼
  User Control
       │
       ├── Touch Screen (wall panel)
       ├── Phone App (anywhere)
       └── Computer Browser (anywhere)
```

---

## 📋 Component Summary

| Component | Quantity | Purpose |
|-----------|----------|---------|
| Raspberry Pi | 1 | Home Assistant OS (brain) |
| Shelly 1PM | 2 | AC + Refrigerator control |
| SONOFF ZBMINI | 1 | Lights control |
| Touch Screen | 1 | Wall panel interface |
| Phone App | 1 | Remote control |
| Computer Browser | 1 | Web interface |

---

## ✅ Quick Overview

| Layer | Component | Communication |
|-------|-----------|---------------|
| **Brain** | Raspberry Pi | Wi-Fi |
| **Devices** | Shelly 1PM, SONOFF ZBMINI | Wi-Fi / Zigbee |
| **Control** | Touch Screen, Phone, Browser | Wi-Fi / Internet |

---

