# 🐧 Linux Learning Labs

Hands-on system administration, terminal command notes, and lab practice at **Per Scholas**.

---

## 📍 Lab 01: Remote Access (SSH) & Linux Documentation

**Environment:** Amazon Linux 2 (AWS EC2 Instance)

### 1. Hands-On Execution
- Connected to an Amazon Linux AMI instance using **SSH**.
- Executed `man man` to explore system documentation and manual page structures.

### 2. Key Commands & Shortcuts Learned
* `man <command>` — Opens the system manual for a specific command.
* `/keyword` — Searches for specific text forward within a manual page.
* `q` — Exits the manual page viewer back to the shell prompt.

### 3. Lab Proof

<p>
  <b>SSH Terminal Access:</b><br>
 <img width="796" height="508" alt="lab1-ssh png" src="https://github.com/user-attachments/assets/0eb83208-fb01-4775-8c09-cac430b258d1" />


<p>
  <b>Manual Page Exploration (man man):</b><br>
<img width="795" height="1072" alt="lab1-man-page png" src="https://github.com/user-attachments/assets/07896565-b527-46f0-a036-96fd20438b1f" />

---

## 📍 Lab 02: Essential System Information & Terminal Productivity

**Environment:** Amazon Linux 2 (AWS EC2 Instance)

### 1. Hands-On Execution
- Inspected active user sessions, server hostname, system uptime, and user group memberships using core Linux diagnostic tools.
- Tested time zone modifications using the `TZ` environment variable alongside Julian (`-j`) and Sunday-start (`-s`) calendar displays.
- Managed command execution history using interactive history search, Tab completion, and event designators (`!!`).

### 2. Key Commands & Productivity Shortcuts Learned
* `whoami` — Displays the currently logged-in username.
* `hostname -s` — Shows the short host name of the system.
* `uptime -p` — Displays how long the server has been running in a pretty, human-readable format.
* `who -H -a` — Prints all details about currently logged-in users with column headers.
* `id <username>` — Displays User ID (UID), Group ID (GID), and all secondary group memberships for a user.
* `TZ=<Region>/<City> date` — Temporarily sets the time zone variable to view the date/time in specific regions (e.g., `TZ=America/New_York date`).
* `cal -j` — Displays the calendar showing Julian days (day count from 1 to 365/366).
* `cal -s` — Displays the calendar with Sunday set as the first day of the week.
* `history` — Outputs the indexed list of previously executed terminal commands.
* `Ctrl + R` — Opens the reverse history search prompt to instantly find and auto-fill previously used commands.
* `Tab` — Auto-completes commands and directory paths to speed up typing and avoid typos.
* `!!` — Re-runs the exact last command executed in the shell.

### 3. Lab Proof

<p>
  <b>System Diagnostics, User Inspection & Timezone/Calendar Commands:</b><br>
  <!-- Drag and drop your terminal output screenshot directly below this line -->
</p><img width="818" height="1067" alt="Screenshot 2026-09-07 000809" src="https://github.com/user-attachments/assets/3acde06c-a278-4fb0-abbb-e5073f273905" />




<p>
  <b>History Search and Event Designators (!!):</b><br>
  <!-- Drag and drop your history/repeat command screenshot directly below this line -->
</p>

<img width="988" height="290" alt="Screenshot 2026-09-07 000957" src="https://github.com/user-attachments/assets/931e68ad-530a-4e0c-93cc-45a8d3374a91" />
