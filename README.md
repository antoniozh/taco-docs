# TaCo – TastyIgniter Companion

TaCo (TastyIgniter Companion) is a mobile app designed for restaurant owners using TastyIgniter. It streamlines order management with real-time updates, push notifications, receipt printing, and more, all within a clean, intuitive interface.

## Features

- **Order Management** – View, track, and update orders with real-time status changes  
- **Push Notifications** – Instant alerts for new orders and updates  
- **EPSON Printing** – Print receipts effortlessly with supported EPSON printers  
- **ESC/POS Printing** Print receipts using a raw TCP connection and ESC/POS data (experimental feature)
- **Sunmi Printing** Print receipts using a handheld Sunmi printer (Tested devices: Sunmi V2 Pro, Sunmi V2s)
- **Localization Support** – Available in multiple languages  
- **Delivery Navigation** – Jump directly to customer addresses from the app  
- **Tablet UI** – Optimized layout for tablets  
- **Branding Options** – Customize with your logo, splash screen, and store listing  (contact me for more info)
- **Easy Setup** – Plug-and-play installation with no complex configuration needed

## Prerequisites

- Android device running Android 7.0 or higher
- iOS device running iOS 15.0 or higher  
- A running TastyIgniter server (with API access)

## Installation

1. Install directly from Google Play:  
   [TaCo on Google Play](https://play.google.com/store/apps/details?id=de.dineabyte.taco)

   Install directly from Apple App Store:
   [TaCo on App Store](https://apps.apple.com/de/app/taco-tastyigniter-companion/id6742470816?l=en-GB)  

## Configuration

1. Launch **TaCo**
2. Enter your TastyIgniter instance URL and credentials.  
3. [Configure your printers](docs/printers.md).  [Supported printers](supported_printers.md)
4. Set up [Webhooks for push notifications](docs/webhooks.md)

## Usage

1. Navigate to the the **Orders** drawer to see incoming orders.  
2. Select an order to view details, update its status, or print a receipt.  
3. Use the **Navigate** button to open your preferred map app for deliveries.

## Report Bugs

If you encounter any bugs or issues, please check the [common issues page](docs/common_issues.md) and if you still have issues, [open an issue](https://github.com/antoniozh/taco-docs/issues) on GitHub with details about your device, operating system, and steps to reproduce the problem. Your feedback helps improve the app!

## Status of notification server

[Click here to check the status of the notification/license server.](https://monitor.dineabyte.de/status/taco)

> **Note:** If the license server is temporarily unavailable, your device license will remain valid for up to three days. This grace period ensures uninterrupted access to notifications and app features even during server outages.
