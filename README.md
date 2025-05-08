# Real-Time Log File Monitor with Python, Tkinter, and Pygtail

This project is a **real-time log file monitoring tool** built using **Python**, **Tkinter**, and **Pygtail**. It allows you to monitor system log files on **Windows** and display new entries as they appear, which is useful for debugging, system monitoring, or simply keeping an eye on logs.

## Features

- **Real-Time Log Monitoring**: Continuously checks the log file for new entries and updates the display instantly.
- **User-Friendly Interface**: A clean and interactive interface created with **Tkinter** for easy viewing of log content.
- **Log File Handling with Pygtail**: Efficiently manages rotating log files, making it ideal for production environments where logs are frequently updated.
- **File Existence Check**: Checks if the log file exists before reading it, preventing unnecessary errors.
- **Graceful Shutdown**: Ensures that the monitoring thread stops correctly when the application is closed.

## Why This Project?

System logs are an essential part of debugging and monitoring, and this tool makes it easier to:
- Track log updates in **real-time** without having to manually open the file each time.
- Debug applications by providing live visibility into logs.
- Interact with logs through a user-friendly interface rather than searching through static text files.

## Technologies Used

- **Python**: The backend logic for monitoring log files.
- **Tkinter**: A simple GUI to display the log updates.
- **Pygtail**: A library for efficiently handling log rotation and continuous reading.
- **Threading**: To run the log monitoring in the background without freezing the UI.

### Prerequisites
- Python 3.x
- Tkinter (usually bundled with Python, but can be installed separately if needed)
- Pygtail (`pip install pygtail`)

