# Changelog

All notable changes to the **RW Mod Protector Tool** for Android are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/), and this project adheres to [Semantic Versioning](https://semver.org/).

---

## [1.2.51] - 2026-03-01

- Improved Disengagement Boost Mode file filtering
- Fixed issue where enabling Experimental Option would incorrectly allow file injection

[➡️ Download APK](https://github.com/EldenThrone588/Rusted-Warfare-Mod-Asset-Protector-Tool___Android/releases)

---

## [1.2.4] - 2026-02-01

"Added Debug Stats Info in Settings that shows last RAM usage",
"Added new Category 'Asset Protection Modes' for Options in Misc Subpage",
"Added Default, Image-Music Only and Image Only Asset Protection Mode in Misc Subpage",
"Fixed Proper Refresh when selecting colors in Appearances Settings",
"Downgraded SDK from 35 to 33 to avoid Restriction and Threading Handling by Android 15",
"Updated Tutorial Video inApp"

---

## [1.2.32] - 2026-01-24

"Updated Credits Attribution included in protected mod",
"Moved Experimental and Performance Setting into Misc Settings Subpage to reduce settings content cluttering",
"New Category 'Miscellaneous' to access Misc Setting Subpage",
"New Custom Attribution File Injection in Misc Settings Subpage",
"New Category 'Attribution' for Author Name",
"Author Name is now included in HELLO.txt Attribution if switch is on"
Note: Custom Attribute File injection limit is 10 files and 10MB size. Also HELLO.txt was already included in 1.2 major update by default, this version just gave more customization. The Custom Attribute File Injection injects another file in the root directory of a zip file similarly to HELLO.txt in root.

---

## [1.2.3] - 2026-01-18

"Adjusted Theme Customization(for status text colors)",
"Added Export to Backup Zip Button to Terminal after Process is done",
"Adjusted the logging a little bit",
"Added Deltarune Theme Color Set Template Button",
"Renamed Encryptor into Mod Protector",
"Replaced Input Password Dialog into Confirm Dialog to make this tool make sense"

---

## [1.2.21] - 2026-01-11

"Better Main Menu GUI",
"Adjusted Background Logging",
"Improved Mod Compilation Engine",
"Added New Category 'Performance' with Disengagement Boost Mode",
"Added New Category 'Appearances' and customization"

---

## [1.2.1] - 2025-12-30

"Fixed Storage Permissions having two in Android 11+ Settings",
"Fixed ANR Logging being aggressive that catches small freezes",
"Updated Storage Permissions Descriptions"
Note: The Storage Permission being two options in settings doesnt make sense for android 11+ when you already have a All File Access while having another storage permission option to choose, which is fixed, so different permissions now across android versions.

---

## [1.2.0] - 2025-12-30
### ⚡ Major Update

"Updated Gradle Compilation from 7.5 to 8.7",
"Updated Android Gradle Plugin from 7.4.2 to 8.6",
"Updated SDK Compilation from 33 to 35",
"Updated Chaquopy version from 14.0.2 to 16.1.0",
"Updated Minimum Android version from 5.1 to 7.0",
"Improved Mod Compilation Handling",
"Fixed CopyToAppStorage and CopyAndSelect not working",
"Added Benchmark, Delete All Logs and Delete Cache button in settings",
"Improved loading texts",
"Encryptor changed to Protector",
"Reduced Number of Warning dialogs"

---

## [1.1.0] - 2025-12-09
### Initial Update

"Fixed instance duplication when button tapped many times",
"Added save crash log option on exit in settings on general category",
"Added custom output dir setup in new output category in settings",
"Added Loading screen",
"Added Persistent Pastebin Version Update Button and Dialog",
"Better App logging with crash logs status",
"Added Document Api + dialog requests for permission",
"New Folder Mirage Experimental Option",
"Added Video tutorial InApp for new users"

---