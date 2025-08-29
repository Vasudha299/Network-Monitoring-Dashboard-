
# Network-Monitoring-Dashboard-



A lightweight and extensible real-time network monitoring dashboard built with Python (Flask) and Plotly.js. This project monitors device availability, tracks latency trends, and visualizes network health in an interactive web interface. It is designed for telecom, enterprise networks, and academic purposes.
Features

✅ Real-time Device Monitoring – Pings configured devices and checks availability.

✅ Latency Tracking – Collects and plots latency values in interactive graphs.

✅ Multiple Graphs in One Dashboard – Compare network performance across devices in a single view.

✅ Device Configuration – Devices listed in devices.json can be updated easily.

✅ Alerts (Optional) – Extendable to send email/Telegram alerts on device downtime.

✅ Simple Web UI – Dashboard built with Flask + HTML + Plotly.js.


network-fault-detector

I backend

   a) monitor.py       # Handles pinging & latency tracking

   b)server.py         # Flask server & API endpoint.

   c)devices.json      # List of devices to monitor

│
II templates

  a)── status.html    # Frontend dashboard with graphs


III requirements.txt   # Python dependencies

IV README.md           # Documentation


## Acknowledgements



I would like to express my sincere gratitude to my mentors , for their constant guidance, encouragement, and valuable feedback throughout the development of this project. Their insights helped me refine my ideas and build this project into a practical and functional system.

A special thanks to my peers, family, and friends who supported me with motivation and suggestions during this journey.

Finally, I would like to acknowledge the open-source community and the developers of Python, Flask, and Plotly, whose tools and libraries made this project possible.
## Appendix

Any additional information goes here


## Demo





# Hi, I'm Vasudha ! 👋
I am passionate about solving practical problems using AI-driven solutions and aspire to contribute to projects that enhance network reliability, data-driven decision-making, and automation in technology systems.


## Installation

Install my-project with npm


```bash
  git clone https://github.com/your-username/network-fault-detector.git
cd network-fault-detector
```
Install Dependencies
```bash
pip install -r requirements.txt
``` 
Configure Devices

Edit backend/devices.json to add devices you want to monitor:
```bash
[
  { "name": "Google DNS", "ip": "8.8.8.8" },
  { "name": "Cloudflare DNS", "ip": "1.1.1.1" }
]
```
Run the Server
```bash
python backend/server.py
```
👩‍💻 Tech Stack

Backend – Python, Flask

Frontend – HTML, CSS, Plotly.js

Data – JSON-based device configuration






    
## 🔗 Links
[![Dashboard](https://img.shields.io/badge/Open-Dashboard-orange)](http://127.0.0.1:5000/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vasudha29/)


