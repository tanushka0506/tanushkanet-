# tanushkanet-
# Packet Sniffer Project using Scapy

## 📜 Description
This repository contains a packet sniffer program developed in Python using the Scapy library. The tool captures and displays packet summaries from a specified network interface.

## 📂 Project Structure
- `packet_sniffer.py`: Python script to capture and display network packets.
- `requirements.txt`: List of dependencies.
- `README.md`: Project documentation.

## 🛠️ Installation
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/packet-sniffer.git
   cd packet-sniffer
   ```
2. **Create a virtual environment (optional):**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage
Run the script to start sniffing packets on the `eth0` interface:
```bash
python packet_sniffer.py
```

## 📝 Example Output
```
Ether / IP / TCP 172.28.0.1:37048 > 172.28.0.12:8080 PA / Raw
HTTP Request Host: example.com
```

## 🛡️ Security Notice
- Ensure you have proper authorization before sniffing network traffic.
- This tool is for educational and research purposes only.

## 🧑‍💻 Author
- **Tanushka Bhatnagar** - PDEU College

## ⚠️ License
This project is licensed under the MIT License.

---

## ✅ How to Upload to GitHub
### **1. Create a Private Repository**
- Go to [GitHub](https://github.com/) and create a new repository (`packet-sniffer`), mark it **private**.

### **2. Push Project to GitHub**
```bash
git init
git remote add origin https://github.com/yourusername/packet-sniffer.git
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

### **3. Get Repository Link**
- Copy the URL from GitHub: `https://github.com/yourusername/packet-sniffer`

### **4. Share Securely**
- Invite collaborators from **Settings > Collaborators** (Read-only permissions for others).

Happy Coding! 😊
