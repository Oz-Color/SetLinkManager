# Set Link Manager

**Check, configure and monitor Set Link Nano units from your Mac.** By [Oz Color](https://shop.oz-color.fr/).

Set Link Nano units are Wi-Fi HaLow radios that carry camera and video links on set. Set Link Manager reads and writes their settings over Ethernet, prepares a whole set in one go, and keeps an eye on the links while you shoot.

**[Download the latest version](../../releases/latest)** · macOS 15 or later · Apple silicon and Intel · Free

## What it does

- **Units:** every unit wired to the Mac shows up by itself, with its settings. Units linked over HaLow show too, with their signal and the settings last read while they were wired. Give each unit a name and a ring colour to match the one in your hand.
- **Presets:** save a set of settings (network name, frequencies, bandwidth, power, encryption…) and write it to any wired unit.
- **Change set:** write one preset, or a factory reset, to a whole set of units, one after another. Every write is read back and checked field by field: the app says "Verified" only when it is.
- **Signal:** each HaLow link's strength over time, with its best, average and worst, and how often it dropped.
- **Ping:** watch the cameras, iPads and routers on set answer on the network.
- **Menu bar:** keep monitoring with the window closed, with an alert when a unit loses its link or a device goes offline.
- **Warnings:** settings that would stop units from linking are pointed out before they cost you time on set.

The unit's role (AP or client) stays on its hardware switch, and pairing on its button: the app shows them and never changes them.

## Install

1. Download the `.dmg` from **[Releases](../../releases/latest)**.
2. Open it and double-click **Set Link Manager**. It's signed and notarised by Apple, so it opens normally.
3. The app offers to **move itself to Applications**: click **Move to Applications**.
4. When macOS asks whether Set Link Manager may **find devices on your local network**, click **Allow**: that's how it talks to the units.
5. Allow **notifications** if you want link-loss and ping alerts.

`Licence.txt` in the download sets out the terms of use.

## Connect a unit

1. Power the unit.
2. Connect its Ethernet port to the Mac, directly or through a switch. A USB or Thunderbolt Ethernet adapter works.
3. Open **Units**: the unit appears under **Wired to this Mac** within a few seconds. If it doesn't, click **Scan** (⌘R).

Wire several units through a switch to set them all up at once. Units come back faster after a replug when the Ethernet adapter has a static IP: the app shows how (Help → *Set a static IP*).

## Updates

Installed copies check for updates once a day and ask before installing. To check now: **Set Link Manager → Check for Updates…**.

## Help and support

- **Help → Set Link Manager Help** (⌘?) opens the full manual. Hover over a setting for a short explanation.
- **Help → Contact Support…** sends your question to Oz Color with the app's diagnostics (passwords are never included), or write to [support@oz-color.fr](mailto:support@oz-color.fr).

---

This repository holds only the signed app and its update feed (`appcast.xml`, read by the app). © 2026 Oz Color. All rights reserved.
