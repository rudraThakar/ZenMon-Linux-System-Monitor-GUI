# ZenMon: Linux System Monitor GUI

A **cross-distro Bash-based system monitoring tool** with a graphical interface powered by **Zenity**.  
ZenMon provides real-time insights about your system such as CPU, RAM, battery, disk, network usage, hardware info, and more : all accessible via a simple GUI.

---

## ✨ Features

- **System Overview**: Hostname, OS, kernel, architecture, uptime, and more  
- **CPU Monitoring**: Live usage, temperature, core count, power mode  
- **RAM Usage**: Total, used, available memory  
- **Disk Usage**: Storage details and space utilization  
- **Network Stats**: Bandwidth monitoring via `ifstat` or `vnstat`  
- **Process Viewer**: Top running processes in real-time  
- **Battery Status** (for laptops)  
- **Wi-Fi Connected Devices**: Detected via `arp-scan`  
- **Hardware Details**: Gathered using `lshw`  
- **Zenity GUI Menu**: Interactive and beginner-friendly  
- **Cross-Distro Installer**: Automatically detects and installs dependencies for Debian, Ubuntu, Arch/Manjaro, and Fedora  

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/rudraThakar/ZenMon-Linux-System-Monitor-GUI.git
cd ZenMon-Linux-System-Monitor-GUI
```

Make the script executable:
```bash
chmod +x system_monitor.sh
```

Run the script:
```bash
./system_monitor.sh
```
