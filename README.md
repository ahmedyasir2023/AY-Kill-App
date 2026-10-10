# AY Kill App

**Developed by Eng. Ahmed Yasir**

AY Kill App is a simple and powerful KernelSU Next module that automatically force-stops user applications immediately after you leave them. It also includes a manual “Close All Apps” action, an app exclusion list, and a modern WebUI.

## What It Does

- **Automatic Force Stop on Exit:** When you open any app and then leave it, AY Kill App waits briefly and force-stops that app using `am force-stop`.
- **Fast Exit Detection:** Uses a lightweight background monitor to detect the current foreground app and detect when you switch away from it.
- **Exclusion List:** Add any apps you want to protect from automatic force-stop. Apps not added to this list will be closed automatically after exit.
- **System App Protection:** Essential system packages such as SystemUI, Phone, Settings, GMS, Play Store, Bluetooth, and permission-related services are protected automatically.
- **Close All Apps Button:** Force-stops all eligible user applications directly from the KernelSU Action button or from the WebUI.
- **Toast Notifications:** Shows a notification after an app or multiple apps are force-stopped.
- **Modern WebUI:** Manage automatic killing, adjust the exit delay, enable/disable Toast notifications, manage the exclusion list, and use the manual kill-all button.
- **Banner Support:** Includes a yellow-and-black banner displayed in the module WebUI.

## Key Features

- Automatic force-stop after leaving an app.
- Manual **Close All Apps** action.
- Configurable exclusion list.
- Fast exit monitoring with a short delay.
- Toast notifications.
- WebUI control panel.
- KernelSU Action button support.
- Designed for KernelSU Next.

## Compatibility

Designed for KernelSU Next on compatible Android devices. Actual behavior may vary depending on your Android version, device manufacturer, ROM, and kernel.

## Important Notes

Force-stopping applications can interrupt background downloads, syncing, music playback, notifications, and other background tasks. Use the exclusion list to protect apps that need to keep running.

Do not add essential system apps to the exclusion list unless you understand what you are doing. The module already protects critical system services by default.

## Version

**v3.0.0**

## Developer

**Eng. Ahmed Yasir**
