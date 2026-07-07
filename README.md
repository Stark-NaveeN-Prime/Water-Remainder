# Water-Remainder
Markdown
# 💧 Desktop Water Reminder with Custom Animated Character

A native-looking Windows toast notification application that pops up at customizable intervals to remind you to stay hydrated! Features a custom animated character/video layout alongside clean interactive options.

---

## 🚀 Features

* **Native Windows Toast Style:** Frameless, modern borderless layout that snaps perfectly into the bottom-right corner of your primary monitor.
* **Always on Top:** Stays layered above your active apps and video games so you never miss a reminder.
* **Animated GIF Support:** Seamlessly loops your favorite character or video animation inside the UI window.
* **Custom Snooze & Timers:** Postpone alerts by 1 minute with the **Snooze** action, or pick custom delay periods (**5m, 10m, 15m, 30m, 45m, 1h**).
* **Built-in Social Credits:** Features clickable developer links that open up your custom profiles natively.

---

## 🛠️ Required Module Installation

This application uses **Python 3** and relies on the `Pillow` library to handle custom images and animated sequences smoothly.

Before running the application, make sure you have dependencies set up by executing:

```bash
pip install pillow
📦 Project Setup & Execution
Clone or Download this repository to your local device.

Ensure your custom character GIF file is saved in your path directory, or replace the self.character_path variable inside the script with your absolute system directory address:

Python
self.character_path = r"C:\Users\TonyStarkNaveen\Downloads\Walking_drinking_water_left_right_202607071140.gif"
Run the application from your command line terminal:

Bash
python water_reminder.py
💡 Configuration
Default Interval: The reminder is configured to check and launch immediately upon startup, and then default back onto a 5-minute schedule.

Interval Adjustments: To update baseline timer configurations, you can easily change the values of self.next_reminder_delay = 300 (calculated in seconds) inside the script source code.

🧑‍💻 Credits & Attribution
Prompt & Design Concept by: Stark Naveen Prime

Developer Instagram: 📸 @Starknaveenprime
