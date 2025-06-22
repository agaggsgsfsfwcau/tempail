# 🔥 Temp Mail - VWH Email API Client

![Temp Mail Screenshot](https://i.imgur.com/HVdowdX.png) 

**A privacy-focused disposable email client** that lets you receive emails without exposing your real address. Perfect for signups, verifications, and anonymous communication.

[![GitHub Stars](https://img.shields.io/github/stars/agaggsgsfsfwcau/tempail?style=social)](https://github.com/agaggsgsfsfwcau/tempail)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

---

## 🌟 Key Features

### 🔒 Email Management
| Feature | Description |
|---------|-------------|
| ⚡ Instant Generation | Create random emails (e.g. `x8j3k@vwh.sh`) with one click |
| ✏️ Custom Aliases | Use your own prefix (e.g. `yourname@vwh.sh`) |
| 🌐 Multi-Domain | Supports `@vwh.sh` domain |
| 📋 Smart Copy | One-click copy with visual confirmation |

### 📬 Inbox Power
| Feature | Description |
|---------|-------------|
| 🔄 Auto-Refresh | Checks for new emails every 15 seconds |
| 👀 Message Previews | See sender, subject and timestamps |
| 🖥️ HTML Rendering | Safe sandboxed message display |
| 📝 Plain Text Mode | Clean text-only viewing option |

### ✉️ Message Tools
| Feature | Description |
|---------|-------------|
| 📂 Download | Save messages as `.txt` files |
| 🗑️ Secure Delete | Permanently remove messages |
| 📱 Responsive | Works on all device sizes |

---

## 🛠 Tech Stack

**Frontend**  
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Security**  
![CSP](https://img.shields.io/badge/-CSP-FF6B6B)
![Sandbox](https://img.shields.io/badge/-Sandboxed-4ECDC4)

**API**  
`https://email.vwh.sh/api`

---

## 🚀 Getting Started

### Quick Usage
1. **Generate** - Click the button or type a custom name
2. **Use** - Copy your temp email for signups
3. **Monitor** - Inbox auto-updates every 15s
4. **Manage** - View, download or delete messages

### Local Development
```bash
# Clone the repository
git clone https://github.com/agaggsgsfsfwcau/tempail.git

# Open in browser (no build required)
open index.html
```

---

## 🌐 API Documentation

### Endpoints
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/email/{address}` | GET | Fetch inbox |
| `/inbox/{id}` | GET | Load full message |
| `/delete/{id}` | DELETE | Remove message |
---

## 📜 License  
Distributed under the MIT License. See `LICENSE` for more information.

---

## ✉️ Contact
For questions or support, please contact:
- Email: astaab1@protonmail.com
- GitHub Issues: [https://github.com/agaggsgsfsfwcau/tempail/issues](https://github.com/agaggsgsfsfwcau/tempail/issues)
