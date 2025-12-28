# Shortcut Updater 

Update shortcuts using GitHub.

<img width="100" height="100" alt="${f}" src="https://github.com/user-attachments/assets/6fd6e5d3-cde9-4030-a298-ead82ac2db6d" />

# Features:
- Check for updates.
- Upgrade· downgrade.

# How to use:
1. [Create a GitHub Account](https://github.com/signup) or [Login to Your Account](https://github.com/login). And create a repository for your Shortcut.

2. Get the latest version of **Shortcut Updater** from [Releases](https://github.com/Dr-Sauce/ShortcutUpdater/releases/latest). Open it in the Shortcuts app. Merge your shortcut with **Shortcut Updater** (You can use [Join Shortcuts](https://routinehub.co/shortcut/10038/) to merge shortcuts)

3. Open the merged shortcut and add the following info to the top dictionary.

|               | Description                                                                                      | Example            |
|---------------|--------------------------------------------------------------------------------------------------|--------------------|
| Name          | Enter the name of your shortcut.                                                                 | TrollStore Checker |
| Version       | Enter the version of your shortcut.                                                              | 1.1                |
| Github        | Enter your GitHub username.                                                                      | Dr-Sauce           |
| Repository    | Enter your shortcut repository name on GitHub.                                                   | TrollStoreChecker  |
| icon          | Shortcut icon that appears in menus. (Icon needs to be encoded with base64. You can do it with [this](https://www.icloud.com/shortcuts/609ab31889194189be9bb60c5f62263b) shortcut.)                     |                    |

4. Open `Share` sheet and click `Copy iCloud link`.

5. Open the GitHub repository you made for your shortcut. Go to releases and create a release.

|               | Description                                                                                                   | Example                                                                                                                                                                                                                                                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Release title | Enter a nice title for your shortcut release.                                              | TrollStore Checker 1.1                                                                                                                                                                                                                                                                                                     |
| Tag (version)           | Enter the version number here. The tag should match the version number in the top dictionary in your shortcut.| 1.1                                                                                                                                                                                                                                                                                                                       |
| Body          | Release body should include the shortcut iCloud link.| **TrollStore Checker 1.1** <br /> https://www.icloud.com/shortcuts/31e7a02165c6494b8eb557c1939e3020 <br />  <br /> # Changelog: <br /> - Updated TrollStore install methods. <br /> - Added support for iOS 15.6 beta. <br /> - Added support for iOS 15.5 RC, 15.6 RC 1/2. |

# History:
- **1.x:** Brought the idea of updating shortcuts with GitHub to life with some hacky ways.
- **2.x:** Implemented GitHub API properly, making `Shortcut Updater` stable.
- **3.x:** Added VCF menus, which allowed images and subtitles to be shown in menus.

# Note:
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:
[Detect System Language JS](https://www.reddit.com/r/shortcuts/comments/c0bkad/comment/er4zrxb/) ([MMP0](https://www.reddit.com/user/MMP0))
