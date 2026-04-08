# Multi-Threaded Network Port Scanner

A lightweight, high-performance network port scanning utility with a graphical user interface (GUI). Built entirely with Python's standard libraries, this tool allows users to scan remote hosts or local IPs to identify open ports and their associated services.

## Features
* **Multi-Threaded Performance:** Utilizes up to 500 concurrent worker threads to scan thousands of ports in seconds without freezing the UI.
* **Service Resolution:** Automatically maps common open ports to standard services (e.g., Port 80 -> HTTP, Port 22 -> SSH).
* **Real-Time GUI:** Built with Tkinter, featuring a dynamic progress bar, elapsed time tracker, and live status updates.
* **Export Functionality:** Save scan results directly to a formatted `.txt` file for auditing and record-keeping.
* **Zero Dependencies:** Relies strictly on Python's built-in libraries—no external `pip` installations required.

## Tech Stack
* **Language:** Python 3
* **GUI Framework:** Tkinter / ttk
* **Networking & Concurrency:** `socket`, `threading`, `queue`

## How to Run

1. Ensure you have Python 3 installed on your system.
2. Clone this repository or download the source code.
3. Open your terminal or command prompt and navigate to the project folder.
4. Run the script:
   ```bash
   python main.py