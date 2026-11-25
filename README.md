# EthernetWizard Pager Theme

A wizard-themed interface for the Hak5 WiFi Pineapple Pager, with custom pixel art, menus, and animations. Check your Pager firmware before choosing a download.

- **Firmware 2.0.0 — theme v2:** [Download EthernetWizard_v2.zip](https://github.com/EthernetWizard/EthernetWizard-Pager-Theme/releases/download/v2/EthernetWizard_v2.zip) · [v2 release notes](https://github.com/EthernetWizard/EthernetWizard-Pager-Theme/releases/tag/v2). The ZIP contains `ethernet_wizard/`.
- **Firmware 1.0.0 — original theme v1:** [Download EthernetWizard_v1.zip](https://github.com/EthernetWizard/EthernetWizard-Pager-Theme/releases/download/v1/EthernetWizard_v1.zip) · [v1 release notes](https://github.com/EthernetWizard/EthernetWizard-Pager-Theme/releases/tag/v1). The ZIP contains `EthernetWizard/`.

The v2 release requires firmware 2.0.0. The v1 release specifies 1.0.0; compatibility with other 1.0.x versions is unconfirmed.

## Install or upgrade

1. Download and unzip the asset for your firmware.
2. If moving from v1 to v2, switch to the built-in `wargames` theme first. Back up the old `EthernetWizard` folder before removing it from the Pager's themes directory.
3. Copy the extracted folder—not the ZIP or a folder containing it—into `/root/themes/` on the Pager. See [Hak5's file transfer guide](https://docs.hak5.org/wifi-pineapple-pager/connecting-to-the-wifi-pineapple-pager/ssh-and-the-wifi-pineapple-pager). Check that `theme.json` is directly inside the copied folder: `/root/themes/ethernet_wizard/theme.json` for v2 or `/root/themes/EthernetWizard/theme.json` for v1.
4. On the Pager, go to **Settings → General → Theme** and select the installed theme.

## Screenshots

[Original v1 screenshots and walkthrough](#v1-original)

### Dashboard

![v2 Dashboard](screenshots/v2/01_dashboard.png)

### Pager Portal

![v2 Pager Portal](screenshots/v2/02_pager_portal.png)

### Alerts

![v2 Alerts](screenshots/v2/03_alerts.png)

### Payloads

![v2 Payloads](screenshots/v2/04_payloads.png)

### Recon

![v2 Recon](screenshots/v2/05_recon.png)

### Recon list

![v2 Recon list](screenshots/v2/06_recon_list.png)

### Recon payloads

![v2 Recon payloads](screenshots/v2/07_recon_payloads.png)

### Launch payload

![v2 Launch payload screen](screenshots/v2/08_launch_payload.png)

### PineAP

![v2 PineAP](screenshots/v2/09_pineap.png)

### Settings

![v2 Settings](screenshots/v2/10_settings.png)

### Power menu

![v2 Power menu](screenshots/v2/11_power_menu.png)

### Quick settings

![v2 Quick settings](screenshots/v2/12_quick_settings.png)

### Keyboard

![v2 Keyboard](screenshots/v2/13_keyboard.png)

### Lock screen

![v2 Lock screen](screenshots/v2/14_lock_screen.png)

### EthernetWizard Lab QR code

![v2 EthernetWizard Lab QR code](screenshots/v2/15_lab_qr.png)

## What's new in v2

- New main menu rail with sharper icons, the name of the icon you're on shown beside it, and a glowing green rune marking your spot
- New Pager Portal scenes: a PC with a portal pouring out of the screen, the wizard brewing potions for Payloads, and browsing on a crystal screen PC for Themes
- All the original v1 art remastered, crisper and tuned for the Pager screen
- Mana Flask on/off switch that fills with glowing green mana when it's on
- Arcane eye launch animation that opens and closes while your payload launches
- Green gem cursor, green potion payload marker, crystal ball folder icon and redrawn small icons
- Orb loading spinner with mist swirling inside
- Rune stone keyboards
- Candlelit Recon list, green glow on selected alerts, and solid lock screens you can actually see
- EthernetWizard Lab QR code under Settings → Help (page 2)
- All the new firmware 2.0.0 screens styled to match

## v1 original

Original artwork and walkthrough, kept for reference. The video is for v1.

[Watch the original v1 installation walkthrough (YouTube, 5:56)](https://youtu.be/jQi02L46kvA?t=356)
<img width="898" height="643" alt="1Dashboard" src="https://github.com/user-attachments/assets/c2686cc9-c325-46e9-94af-b4d3da6896a4" />
<img width="898" height="627" alt="2Alerts" src="https://github.com/user-attachments/assets/f611a996-2aac-486c-8fd5-f2f8dae946b7" />
<img width="901" height="627" alt="3Payloads" src="https://github.com/user-attachments/assets/544568f6-c9e8-4ec2-a2c9-20cb9aec37ef" />
<img width="905" height="634" alt="4Recon_1" src="https://github.com/user-attachments/assets/09455c75-31f8-4103-ad39-a0bdc3a34d28" />
<img width="904" height="626" alt="5Recon_2" src="https://github.com/user-attachments/assets/acaf1125-56ed-4b2e-9790-e9e0103387e1" />
<img width="904" height="635" alt="6ReconPayload" src="https://github.com/user-attachments/assets/326243a5-7166-4726-80e8-1f92fd788cb9" />
<img width="902" height="633" alt="7Launchpayload" src="https://github.com/user-attachments/assets/4c054ec4-6edf-46dc-9ea5-964bb56d3baa" />
<img width="897" height="634" alt="8Pineap" src="https://github.com/user-attachments/assets/9a31db5b-a6ec-4fa3-84d4-9ca83aff083c" />
<img width="902" height="634" alt="9Settings" src="https://github.com/user-attachments/assets/b1be139a-5c5b-4eaa-a200-95a51e9e4a38" />
<img width="930" height="637" alt="Powerbutton" src="https://github.com/user-attachments/assets/cd4a2aef-d927-4411-a155-a1256dce3ffa" />
