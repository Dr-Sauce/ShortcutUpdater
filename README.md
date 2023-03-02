# Shortcut Updater 

Shortcut Updater compares the shortcut version on user's device and the latest version from GitHub. 

If there's a new version it shows a option to update.

<img width="150" alt="0378ACF9-8014-4C25-8F72-80CD7E539E6B" src="https://user-images.githubusercontent.com/82555878/210124744-680186bc-e300-458f-9820-084acc4b0d09.png">

# Features:
- Check for update every ? days.
- Skip update check if there's no internet connection.
- Check for update manually.
- Downgrade shortcut.
- Disable updates.

# How to use:
1. Implement Shortcut Updater to your shortcut. (Scroll down to find the bit where your shortcut should be added.)

Add the following info to the dictionary on the top of your shortcut.

|               | Description                                                                                      | Example            |
|---------------|--------------------------------------------------------------------------------------------------|--------------------|
| Name          | Enter your shortcut name. This is used for searching updates. So you have to enter it correctly. | TrollStore Checker |
| Version       | Enter the version of your shortcut release.                                                      | 2.2                |
| Github        | This is where you enter your GitHub username.                                                    | Dr-Sauce           |
| Repository    | Enter the repository name for your shortcut.                                                     | TrollStoreChecker  |
| File Location | This is where shortcut log files will be stored. (iCloud Drive → Shortcuts → 'Folder Name')      | SAUCE COMPANY      |

2. Upload your shortcut to GitHub releases.

|               | Description                                                                                                   | Example                                                                                                                                                                                                                                                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Release title | Release title should only include the shortcut name and version.                                              | TrollStore Checker 2.2                                                                                                                                                                                                                                                                                                     |
| Tag           | Tag should only include the version number. It should not include any text or special letters other than dots.| 2.2                                                                                                                                                                                                                                                                                                                       |
| Body          | Release body should include the shortcut iCloud link. Other text such as update logs are allowed.             | **TrollStore Checker 2.2** https://www.icloud.com/shortcuts/c475c0f149fb4ea8b659d7b7ca6ecf48 <br /><br /> # Changelog: <br /> - Added iOS/ iPadOS info when showing software version. <br /> - Added software build behind software version. |

# Note:
- Shortcut Updater uses iCloud Drive by default to store log files. (Users have to enable iCloud Drive. If it's not enabled, a popup will appear.)
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:

[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

~~[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))~~
