# Forged

Welcome to Forged. This is a simple, no-nonsense playbook for Windows 11 designed for gamers, power users, and anyone who wants a cleaner, faster, and more private OS without the bloat. It's built for the [AME Wizard](https://ameliorated.io/) and makes deep-level changes to create a stable and optimized system from a stock Windows installation.

## Core

*   **Privacy-Focused:** Strips out invasive telemetry and data collection services.
*   **Performance-Tuned:** Optimizes system services, registry settings, and power plans for lower latency and a smoother experience, especially in games.
*   **Thoroughly Debloated:** Removes non-essential apps and features like Edge, OneDrive, and Teams.

## How to Use

1.  Download the latest release of Forged from the **Releases** page on GitHub.
2.  Get a compatible **Windows 11 ISO**. See the `playbook.conf` file for supported build numbers.
3.  Download the latest **AME Wizard** from the official site.
4.  Launch the AME Wizard, select your Windows 11 ISO, and then load the Forged `.apbx` file.
5.  Follow the on-screen prompts, and you're good to go!

## ⚠️ A Word of Warning ⚠️

This playbook makes significant changes to your Windows system. It is intended for advanced users who understand the implications of removing core components.

I am not responsible for any data loss or issues that may arise. **Always back up your important files before proceeding. Use at your own risk.**

Known issues that i am literally too burnt out to fix, i've worked on this for too many hours in the past week:
 
 * Microsoft edge blank icon in the taskbar, its just a shitty shortcut that i forgot to remove, cant cause issues.
 * The start menu is bloated, my approach failed to fix this, things such as `LinkedIn` and `Install Whatsapp` are simply there as icons and they are not functinoal, they can be removed by simply right-clicking them and removing them from the start menu.
 * I forgot to include icons for the browser options, gradient is good enough so whatever.

Future plans, in **not** a very near future:

* I'll be looking to implement [DirectStart](https://github.com/Lixkote/DirectStart) for the start menu.
* Get away from explorerpatcher, for now, its there so you can have some customization at installation.
* Full ISO injection compatibility with the next AME-Wizard beta update.
* Blacksmith tool which will handle alot of the tasks the playbook does so its simpler for the user to revert tweaks and gain more compatibility back in Forged.
* Someone to help me going forward because this is tiring as fuck, the playbooks available around the internet are 99.9% made by a team of users instead of one person.
