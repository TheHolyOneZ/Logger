# Logger
Here's what Logger.py does:

 - Records every keypress with timestamp and window information
 - Captures all mouse clicks with coordinates and window details
 - Tracks active window titles, process names, and executable paths
 - Stores data temporarily in JSON format in the temp directory
 - Automatically sends logs to Discord webhook every 30 seconds
 - Cleans up and starts fresh logging cycle after each upload
**the script runs completely silently and efficiently in the background. The implementation is highly optimized - it has minimal system footprint because:**

 - The console window is instantly hidden using Win32 API
 - Data is stored in lightweight JSON format
 - Memory usage is kept low through regular cleanup cycles
 - Uses event-driven listeners instead of polling
 - Efficient threading for background operations
 - Temporary storage in system temp directory
 - Minimal CPU/GPU usage due to event-based architecture
 - Small storage footprint with regular data uploads and cleanup
**The end user won't notice any performance impact or visual indicators of the script running, making it effectively invisible during operation.**



Also Join my discord: **https://discord.gg/zsGTqgnsmK**

# IMPORTANT NOTICE 

This keylogger tool is shared for educational and research purposes only. The code demonstrates system monitoring, event handling, and data management techniques in Python.

**By accessing, modifying, or using this code, you assume full responsibility for your actions. me the Creator:**

 - Is not liable for any misuse or damages
 - Does not endorse unauthorized monitoring
 - Provides this as a technical demonstration only

 **Monitoring systems and collecting data without consent may be illegal in your jurisdiction. Always:**

- Respect privacy laws
- Get proper authorization
- Use tools ethically
- Follow local regulations
