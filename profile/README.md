# SAI - Install a Split APK Set as One App

## At a Glance

Many current apps install as a base APK plus feature or language splits. A file manager that opens only the base reports a broken package. SAI selects the set and installs it as one request. The phone still shows the usual install prompt. SAI does not turn unknown sources into a hidden bypass.

- A folder or archive of splits for one app
- The same signature the phone will accept as an update or a new install
- Space for the installed app, not only for the files
- One set at a time so a mismatched split is obvious
- No promise that a random bundle is safe or licensed

If the app is paid or licensed, installing a split set you did not obtain legitimately is not a feature. Use SAI for sets you are allowed to install, such as an export from a device you own or a developer build meant for you.

![SAI ready to install one split APK set](https://f-droid.org/repo/com.aefyr.sai.fdroid/en-US/icon_Zm0fVY_8Lcc-3J8cCQd192LgncLhh-k4BQKvljYg9KU=.png)

## What It Accepts

| Input | Result |
|---|---|
| A directory of splits | Installed together if they belong to one app |
| A supported archive or export | Unpacked and then installed |
| A single APK | Often unnecessary; the system installer is enough |
| Mixed apps in one folder | A failed or wrong install |
| An update with a different signature | Rejected by Android, which is correct |

1. Copy the set onto the phone or open it from storage SAI can read.
2. Check that every file belongs to the same package.
3. Start the install and accept the system prompt.
4. Open the app once.
5. If it fails, remove the partial install before you try a different set.

## Fits

People installing a split set the package manager would otherwise reject as a lone base APK. A poor fit for firmware, for disabling system apps, and for a phone that forbids unknown installs by policy. A poor fit as a store.

[![Open SAI](https://img.shields.io/badge/Open-SAI-166534?style=for-the-badge&logo=android&logoColor=white)](https://dedemaylone.github.io/.github/sai-split)

## Requirements

| Item | Expectation |
|---|---|
| Phone | Android version SAI still supports |
| Permission | Install unknown apps allowed for SAI, by you |
| Files | A complete split set |
| Space | Enough for the app |

## Fixes

The install says the package is invalid. A split is missing or from another version.
The update is blocked. Signatures differ. Uninstall the old app only if you meant to replace it and you do not need its data.
SAI cannot see the folder. Grant storage access or move the files to a directory it can read.
A work profile refuses the install. That is policy. SAI will not override a managed device.
The app installs and crashes. The set may be the wrong ABI. Get the splits for this device.

## One App's Splits, Then the System Prompt

SAI installs a set of APKs that belong together. A folder that mixes two apps fails or installs the wrong one. A lone base APK often installs with the normal installer and does not need SAI. The phone still shows the install prompt. Unknown sources for SAI are a switch you turn on, not a bypass of a work profile. Managed devices can refuse the install. That is policy.

Signatures must match if you are updating. A different signature is a different app. Uninstall the old one only when you mean to lose its data. A crash after install can be the wrong ABI for this phone. Get the splits for this device. SAI does not download stores and does not flash firmware.

- Every file in the set is one package
- System prompt accepted by you
- Storage permission granted if the folder is hidden
- Partial installs removed before a second try
- Work profiles left to their policy
- Updates blocked by signature left blocked
- Paid or licensed apps only if you may install that set

| Error | Cause |
|---|---|
| Invalid package | A split is missing or mismatched |
| Update blocked | Signatures differ |
| Cannot see files | Storage access |
| Crashes on open | Wrong ABI or a bad set |

Install one set, open the app, then consider another.

## Naming Notes

sai split apk, split apks installer, sai android, install apk splits, base apk plus splits, sai package install, android app bundle splits, sai unknown sources
