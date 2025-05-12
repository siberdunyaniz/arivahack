# ArivaOSINTHack

🌐 **ArivaOSINTHack** is a powerful Python-based Open-Source Intelligence (OSINT) and cybersecurity tool designed for educational purposes. It enables users to gather publicly available information using various search methods, including email, name, phone number, IP address, and social media profiles. With a neon-styled interface, Telegram integration, and proxy support, it offers a robust platform for security researchers and ethical hackers.

⚠️ **Disclaimer**: This tool is for educational purposes only. Unauthorized or illegal use is strictly prohibited. The developers are not responsible for misuse.

## 📋 Features
- **Multi-Platform Search**: Query data by email, name, phone, IP, social media (Telegram, Instagram, Facebook), and more.
- **Neon-Styled Interface**: Visually appealing CLI with colorful, animated output using `pystyle` and `colorama`.
- **Telegram Integration**: Receive search results and notifications via Telegram bots.
- **Proxy Support**: Route requests through proxies for anonymity.
- **Fake Data Generation**: Create realistic fake identities and credit card details for testing (using `faker`).
- **Port Scanning & DDoS Testing**: Advanced network analysis tools (use responsibly).
- **Database Search**: Query large datasets for OSINT purposes.
- **Expiration Check**: Tool stops working after May 20, 2025, for controlled distribution.

## 📦 Installation

### Option 1: Pydroid 3 (Android)
1. **Download the Script**:
   - Copy the `arivaosinthack.py` file from this repository.
   - Open Pydroid 3, create a new file, paste the code, and save it as `arivaosinthack.py` in `/storage/emulated/0/`.

2. **Install Dependencies**:
   - Open Pydroid 3’s terminal (via the menu).
   - Run the following command to install required modules:
     ```bash
     pip install pystyle requests beautifulsoup4 python-whois psutil telebot telethon faker fake-useragent colorama
     ```
   - If errors occur, ensure you have an active internet connection and try `pip install --no-cache-dir` for each module.

3. **Run the Tool**:
   - In Pydroid 3, open the script and press the "Run" button, or use the terminal:
     ```bash
     python /storage/emulated/0/arivaosinthack.py
     ```

### Option 2: General Python Environment (Windows/Linux/macOS)
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/siberdunyaniz/arivahack.git
   cd arivahack
   ```

2. **Set Up a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   If `requirements.txt` is not available, install manually:
   ```bash
   pip install pystyle requests beautifulsoup4 python-whois psutil telebot telethon faker fake-useragent colorama
   ```

4. **Run the Tool**:
   ```bash
   python arivaosinthack.py
   ```

## 🚀 Usage
1. Launch the tool using the appropriate command above.
2. Select an option from the menu (e.g., `[1] E-posta ile arama`, `[9] Telegram ile arama`).
3. Follow the prompts to input search parameters (e.g., email, phone number).
4. Results are displayed in the terminal and optionally sent via Telegram (if configured).

**Example**:
```bash
python arivaosinthack.py
# Select: [12] IP ile arama
# Enter IP: 8.8.8.8
# Output: Geolocation, ISP, and related data
```

## 🔧 Configuration
- **Telegram Bot**:
  - Create a bot via `@BotFather` on Telegram and obtain the API token.
  - Edit `arivaosinthack.py` to include your bot token and chat ID.
- **Proxy Setup**:
  - Configure proxies in the script by modifying the proxy list or using a proxy API.
- **Expiration**: The tool is programmed to stop working after May 20, 2025. Contact the developer for updates.

## 🛡️ Ethical Use
- Use this tool only for legal and authorized purposes, such as security research or penetration testing with explicit permission.
- Do not use for illegal activities, unauthorized data collection, or harming systems/networks.
- Respect privacy and comply with local laws.

## 📞 Support
- **Telegram**: Join our community at [t.me/ArivaTools](https://t.me/ArivaTools) or contact [t.me/AtahanArslan](https://t.me/AtahanArslan).
- **Instagram**: Follow us at [@tanrln](https://instagram.com/tanrln) and [@siberdunyaniz](https://instagram.com/siberdunyaniz).
- **Issues**: Report bugs or suggest features via GitHub Issues.

## 🤝 Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make changes and commit (`git commit -m "Add your feature"`).
4. Push to your fork (`git push origin feature/your-feature`).
5. Open a Pull Request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

🌟 **Star this repository if you find it useful!** 🌟