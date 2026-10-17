# Cheat Sheets Collection 📚

<!-- aio-desktop-badge:start -->
[![AIO Desktop](https://img.shields.io/badge/Try-AIO_Desktop-7c3aed?style=for-the-badge&logo=googlechrome&logoColor=white)](https://fbaio.org/#/desktop)
<!-- aio-desktop-badge:end -->

A comprehensive collection of cheat sheets for cybersecurity, certifications, programming, and various tools.

## Features

- 🗂️ Organized by categories
- 🔍 Search functionality
- 📱 Mobile-responsive design
- 📥 Direct PDF download
- 🖼️ In-browser PDF viewer

## Categories

- **Cloud & AWS** - Cloud platform certifications and guides
- **CompTIA Certifications** - A+, Network+, Security+, CySA+
- **Security Certifications** - CEH, CISSP
- **Hacking Tools** - Nmap, SQLmap, CrackMapExec, NetExec, Google Dorks
- **Operating Systems** - Linux, Unix, Windows, PowerShell
- **Networking** - Common Ports, IPv4 Subnets, OSI Model
- **Programming** - SQL, Python, XPath
- **Tools & Utilities** - SSH, Tcpdump, Tmux, Vi, Wireshark, Splunk
- **Career** - Cybersecurity job guides

## Setup

### View the Cheat Sheets

Simply open `index.html` in your web browser.

### Update PDF Structure

When you add new PDFs to the `pdf/` folder, run the update script to automatically regenerate the data structure:

```bash
# Using npm
npm run update-pdfs

# Or directly with Node.js
node script/update-pdf-structure.js
```

This script will:

- Scan all subdirectories in the `pdf/` folder
- Automatically detect categories based on folder names
- Update `src/data.js` with the current structure
- Sort PDFs by category and name

## Adding New PDFs

1. Create a category folder in `pdf/` (if it doesn't exist)
2. Add your PDF file to the appropriate category folder
3. Run the update script: `npm run update-pdfs`
4. The PDF will automatically appear in the viewer

## Project Structure

```
cheat-sheets/
├── index.html          # Main HTML file
├── pdf/                # PDF files organized by category
│   ├── Career/
│   ├── Cloud & AWS/
│   ├── CompTIA Certifications/
│   ├── Hacking Tools/
│   ├── Networking/
│   ├── Operating Systems/
│   ├── Programming/
│   ├── Security Certifications/
│   └── Tools & Utilities/
├── script/
│   └── update-pdf-structure.js   # Auto-update script
├── src/
│   ├── data.js         # PDF structure data (auto-generated)
│   ├── main.js         # Main JavaScript logic
│   └── style.css       # Styles
└── README.md
```

## Resources

- [How to use WireShark](https://www.stationx.net/how-to-use-wireshark-to-capture-network-traffic/)
- [Wireshark Cheat Sheet](https://drive.google.com/drive/folders/132ptAPFrhVZAV5dMMK6Jk9HSA4UJl7Du?sh_kit=2b6ce0a25f1787b4012e55fd345e0cc36f7974832f1caa670f49aa49728e80f4)

## License

MIT

<!-- aio-desktop:start -->
### 🖥️ AIO Desktop

**EN:** Find this tool and many more free tools & games in **[AIO Desktop](https://fbaio.org/#/desktop)**, a Windows/macOS-style web desktop by Social AIO. [▶ Open AIO Desktop](https://fbaio.org/#/desktop)
**VI:** Xem công cụ này cùng nhiều công cụ, trò chơi miễn phí khác trong **[AIO Desktop](https://fbaio.org/#/desktop)**, màn kiểu Windows/macOS của Social AIO. [▶ Mở AIO Desktop](https://fbaio.org/#/desktop)
<!-- aio-desktop:end -->
