# 🟦 AlertTicker-Card - Show Alerts Right on Your Dashboard

[![Download](https://img.shields.io/badge/Download-AlertTicker--Card-blue?style=for-the-badge&logo=github)](https://github.com/ehgus6653/AlertTicker-Card)

## 📘 Overview

AlertTicker-Card is a custom Lovelace card for Home Assistant. It shows alerts and notifications based on entity states.

Use it to keep important messages in view on your dashboard. It can show items like device issues, sensor alerts, or state changes in a clean ticker style.

## 🖥️ What You Need

- A Windows PC to set up the files
- A Home Assistant setup
- A browser such as Chrome, Edge, or Firefox
- Access to your Home Assistant dashboard
- Basic file access to place the card file where Home Assistant can use it

## ⚙️ Main Uses

- Show alert messages on a Lovelace dashboard
- Display notifications from entity states
- Create a ticker area for status updates
- Keep attention on active warnings
- Support a custom dashboard layout

## 📥 Download and Set Up

Visit this page to download and use the files:

[https://github.com/ehgus6653/AlertTicker-Card](https://github.com/ehgus6653/AlertTicker-Card)

1. Open the link in your browser on Windows.
2. Look for the project files and any release or source download options.
3. Download the card files to a folder on your PC.
4. If the download comes as a ZIP file, right-click it and choose Extract All.
5. Copy the card file into the folder Home Assistant uses for custom cards.
6. Add the card to your dashboard after the file is in place.

## 🧩 Install in Home Assistant

### 1. Get the card file

Download the project from the link above and save it on your computer.

### 2. Place the file in the right folder

Move the card file to your Home Assistant `www` folder or the folder you use for custom Lovelace resources.

A common path looks like this:

- `config/www/`

If you use a subfolder, keep the file name easy to find.

### 3. Add the resource

Open Home Assistant and go to your dashboard settings.

Add the card as a Lovelace resource if your setup needs it.

Use the file path you copied into your Home Assistant files, such as:

- `/local/AlertTicker-Card.js`

If the file name is different, use that name in the path.

### 4. Refresh the browser

After you add the file, refresh the page.

If the card does not show at once, clear the browser cache and try again.

## 🏠 Add the Card to Your Dashboard

Add the card from the dashboard editor.

A basic setup may look like this:

- Select your dashboard
- Open the edit menu
- Choose to add a card
- Select the custom card option
- Pick `AlertTicker-Card`
- Save your changes

If you use YAML mode, add the card where your Lovelace cards are defined.

## 🛠️ Example Setup

This card is meant to show alerts tied to entities. A simple setup may include:

- A sensor for device status
- A binary sensor for alerts
- An entity that changes state when a problem appears
- A ticker message for the dashboard

Example uses:

- Door left open alert
- Temperature high warning
- Network device offline notice
- Battery low message
- Maintenance reminder

## 🔔 Features

- Custom Lovelace card for alerts
- Ticker-style message display
- Entity-based notification view
- Works with Home Assistant dashboards
- Clean display for important state changes
- Easy to place on a card view
- Useful for home status and warning panels

## 🧪 Common Setup Tips

- Use a short entity name so alerts are easy to read
- Keep messages simple
- Test with one alert first
- Make sure the file path is correct
- Refresh the dashboard after each change
- Check Home Assistant logs if the card does not load

## 🔍 If the Card Does Not Show

Try these steps:

- Confirm the file is in `www` or your custom card folder
- Check that the resource path starts with `/local/`
- Refresh the browser page
- Clear browser cache
- Check that Home Assistant can reach the file
- Make sure the card name matches the file name

## 📁 File Layout Example

A simple Windows file layout may look like this:

- `Downloads`
- `AlertTicker-Card`
- `config`
- `www`
- `AlertTicker-Card.js`

This keeps the file easy to find when you move it into Home Assistant.

## 🧭 Who This Is For

- Home Assistant users who want alert text on a dashboard
- People who use Lovelace cards
- Users who want a simple ticker view for state changes
- Anyone who wants important messages in one place
- Home automation users who want a clear alert panel

## 🧾 Topics Covered by This Project

- alert
- custom card
- dashboard
- HACS
- Home Assistant
- home automation
- JavaScript
- Lit Element
- Lovelace card
- notification
- ticker

## 🖱️ Quick Use Guide

1. Download the project from the link above.
2. Extract the files if they come in a ZIP.
3. Copy the card file into the Home Assistant `www` folder.
4. Add the resource path to Lovelace.
5. Add the card to your dashboard.
6. Save and refresh the page.

## 🧰 Windows Folder Help

If you are new to Windows file handling:

- Right-click a ZIP file to extract it
- Use File Explorer to move files
- Keep the card file in a folder you can find again
- Check the full file name before copying it
- Use copy and paste if drag and drop feels hard

## 🏷️ Naming Tips

Use clear names for your entities and alerts.

Good names include:

- Front Door
- Garage Sensor
- Water Leak
- Server Room Temp
- Battery Alert

Clear names make the ticker easier to read on the dashboard.

## 🔗 Project Link

Primary download and source page:

[https://github.com/ehgus6653/AlertTicker-Card](https://github.com/ehgus6653/AlertTicker-Card)

## 📌 Basic Use Pattern

- An entity changes state
- Home Assistant detects the change
- The card shows the alert text
- You see the update on the dashboard
- The alert stays easy to notice

## 🧩 Why Use a Ticker Card

A ticker card keeps active alerts in view without taking much space. It works well on a dashboard where you want fast status checks.

It can help you track:

- Safety alerts
- Device faults
- Network issues
- Climate changes
- Reminder messages