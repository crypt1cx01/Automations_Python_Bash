# Automations_Python_Bash
Automations Python &amp; Bash Script For Easy Task

---

## 🛠️ System Monitor & Information Script (whoami)

This is a lightweight and powerful Bash script designed to gather and display vital system statistics, resource usage, and network profiles in a clean, color-coded Terminal interface.

### 📄 Script File
* You can view and access the source code directly here: **[whoami.sh](https://github.com/crypt1cx01/Automations_Python_Bash/blob/main/Bash/whoami/whoami.sh)**

### 📸 Screenshot
<br>

![whoami](https://github.com/crypt1cx01/Automations_Python_Bash/blob/main/Bash/whoami/whoami_script.PNG)

<br>
<hr>

### ✨ Key Features

* **Smart Welcome:** Detects the current user and displays a red warning emoji if executed with `root` privileges.
* **System Info:** Pulls the exact OS name, current Shell type, system Uptime, and formatted local Date/Time.
* **Resources Profile:** Calculates RAM consumption percentage and monitors Disk usage (with an auto-warning trigger if Disk space exceeds 90%).
* **Network Profile:** Extracts your Local IP, Loopback IP, and fetches your live Public IP (displays "Offline" if no internet connection is detected).
* **Port Monitoring:** Tracks and displays the total number of open network ports currently listening for connections.

<br>

### 🚀 How to Run

Give execution permissions to the script and run it using the following commands:

```bash
chmod +x whoami.sh
./whoami.sh
```

