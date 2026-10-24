<p align="center"><img src="assets/logo.png" width="80" alt="CoffeeNote"></p>

# CoffeeNote

Keep the best recipe for every coffee.

**[简体中文](README.md)** · **[Download Android APK](https://github.com/xuewei1005/CoffeeNote/releases/latest)** · **[Changelog](CHANGELOG.md)**

CoffeeNote is an Android coffee journal for home brewers. Keep your coffee beans, flavor notes, resting status, brewing recipes and gear together, so your next cup starts with a recipe you already know.

No account is required. Coffee records, photos, gear and preferences are stored on your device. Coffee-bag text recognition runs on the device.

> This repository distributes APK releases, documentation and example screenshots only. **The application source code is not published and no open-source license is granted.**

## Download and install

- Current version: **2.8.0**.
- Requires **Android 8.0 or later**.
- Download [`CoffeeNote-2.8.0-release.apk`](https://github.com/xuewei1005/CoffeeNote/releases/download/v2.8.0/CoffeeNote-2.8.0-release.apk), approximately 51 MiB.
- One universal APK includes `arm64-v8a`, `armeabi-v7a`, `x86` and `x86_64`; no separate architecture selection is needed.

Open [Releases](https://github.com/xuewei1005/CoffeeNote/releases), download the release APK and follow the installation prompts on your Android device. You can install an update over the previous version. Export a backup before uninstalling or clearing application data.

SHA-256:

```text
65A4B9CDC67732B83C24F191AD4ECFE648821308D982DC5B9198C289EF51FD3A
```

## Features

| Feature | What it does |
| --- | --- |
| Coffee shelf | Store the brand, coffee name, origin, processing method, roast level, roast/opened dates and tasting notes. Search and filter open, resting or finished coffees. |
| Coffee-bag recognition | Take a photo or select an image to recognize text and fill fields. Chinese, Japanese, Korean and English/Latin-script models are bundled with the APK; choose a language or use automatic mode. |
| Field matching | An offline dictionary covers 16 brands and their aliases. Product names, origins, roast levels and flavors are handled separately; packaging disclaimers are filtered out and uncertain fields are left for review. |
| Brewing recipes | Switch between three single-select tabs: espresso, pour-over and iced pour-over. Each method keeps its own recipe, and only methods with real saved values appear on a card. Espresso defaults to 25 seconds. |
| Resting suggestions | Suggested resting days depend on roast level, brew method and certain processing methods. The default uses the middle of the suggested range and can be changed manually. |
| Coffee gear | Organize grinders, brewers and espresso machines, and link them to coffee recipes. |
| Card management | Long-press to reorder cards or delete a coffee. Deletion requires confirmation and the order is saved between sessions. |
| Themes and languages | Light, dark or system theme. The interface supports Simplified Chinese, Japanese, Korean and English, following the system language by default. |
| Local backup | Export a JSON backup with photos, coffee records, gear and preferences. Confirm before merging an import, or remove bag photos separately. |
| Demo shelf | Explore sample records before adding your own. Exit the read-only demo at any time without replacing personal data. |

## Promotional video

[Download / watch the CoffeeNote 2.8.0 vertical promotional video (1080×1920)](https://github.com/xuewei1005/CoffeeNote/releases/download/v2.8.0/CoffeeNote-2.8.0-promo-vertical-1080x1920.mp4)

The video and APK are attached to the [v2.8.0 Release](https://github.com/xuewei1005/CoffeeNote/releases/tag/v2.8.0).

## Screenshots

These screenshots show the actual app interface rendered at a mobile viewport size with fictional example records. Brand/product combinations illustrate features, not verified retail specifications or endorsements. They contain no personal coffee records, home photos or recognition history. They are not evidence of real-device camera/OCR accuracy testing.

<table>
<tr>
<td align="center"><b>Coffee shelf</b><br><img src="screenshots/01-shelf-light-zh.png" width="240" alt="Coffee shelf in light mode"></td>
<td align="center"><b>Brewing recipe</b><br><img src="screenshots/02-bean-detail-zh.png" width="240" alt="Espresso recipe and coffee status"></td>
<td align="center"><b>Coffee profile</b><br><img src="screenshots/03-coffee-profile-zh.png" width="240" alt="Photo entry, coffee fields and flavor tags"></td>
</tr>
<tr>
<td align="center"><b>Reorder and delete</b><br><img src="screenshots/04-sort-delete-zh.png" width="240" alt="Long-press card management"></td>
<td align="center"><b>Coffee gear</b><br><img src="screenshots/05-coffee-gear-zh.png" width="240" alt="Grinders, brewers and espresso machines"></td>
<td align="center"><b>Theme and language</b><br><img src="screenshots/06-settings-dark-zh.png" width="240" alt="Dark theme and language options"></td>
</tr>
<tr>
<td align="center"><b>Backup and data</b><br><img src="screenshots/07-backup-privacy-zh.png" width="240" alt="Local backup and data management"></td>
<td align="center"><b>English settings</b><br><img src="screenshots/08-settings-dark-en.png" width="240" alt="Settings in English"></td>
<td align="center"><b>English shelf</b><br><img src="screenshots/09-shelf-dark-en.png" width="240" alt="Dark shelf with English example records"></td>
</tr>
</table>

## Getting started

1. Tap **+** to add coffee, or explore the demo shelf first.
2. Tap **Photo** and choose the camera or gallery. Review automatically filled fields. Glare, folds, blur or missing text may require another photo or manual entry.
3. Choose one brew method, keep the defaults or enter your recipe, then save.
4. Long-press a card in **All** with no search query to drag it. Tap **×** and confirm to delete. Filtered/search results also support long-press deletion.
5. Tap the cup logo at the top left to change appearance, languages, defaults or export a backup.

OCR language and interface language are independent. The brand dictionary matches readable text rather than guessing a brand from a product name. Manually entered values are preserved. Resting-day suggestions are a starting point for taste; adjust them for your beans and preferences.

## Data

There is no account or cloud-sync service. JSON backups include device records and photos; transfer and import the backup yourself when changing devices. An import keeps existing records with matching IDs and restores preferences from the backup. Opening the author's GitHub link launches an external browser.

## Author and feedback

**曹好远 (Cao Haoyuan)** · GitHub: [@xuewei1005](https://github.com/xuewei1005)

Please report issues or suggestions through [Issues](https://github.com/xuewei1005/CoffeeNote/issues), including the app version, phone model and reproduction steps. Remove personal information from attached images first.
