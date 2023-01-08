# Shortcut Updater 

Update your shortcut using GitHub.

<img width="150" alt="0378ACF9-8014-4C25-8F72-80CD7E539E6B" src="https://user-images.githubusercontent.com/82555878/210124744-680186bc-e300-458f-9820-084acc4b0d09.png">

# Features:
- Check for update every ? days.
- Skip update check if there's no internet connection.
- Check for update manually.
- Downgrade shortcut.
- Disable updates.

# How to use:
1. Implement Shortcut Updater to your shortcut. (Scroll down to find the bit where your shortcut should be added.)

|            | Explanation                                                   | Example            |
|------------|---------------------------------------------------------------|--------------------|
| Name       | Enter your shortcut name. This is used for searching updates. | TrollStore Checker |
| Version    | Enter the version of your shortcut release                    | 1.0                |
| Github     | This is where you enter your GitHub username.                 | Dr-Sauce           |
| Repository | Enter the repository name for your shortcut.                  | TrollStoreChecker  |

2. Upload your shortcut to GitHub releases.

|               | Explanation                                                                                                   | Example                                                                                                                                                                                                                                                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Release title | Release title should only include the shortcut name and version.                                              | TrollStore Checker 1.0                                                                                                                                                                                                                                                                                                    |
| Tag           | Tag should only include the version number. It should not include any text or special letters.                | 1.0                                                                                                                                                                                                                                                                                                                       |
| Body          | Release body should include the shortcut iCloud link. Other text such as explanation, update log are allowed. | **TrollStore Checker 2.2** https://www.icloud.com/shortcuts/c475c0f149fb4ea8b659d7b7ca6ecf48 <br /><br /> **TrollStore Checker 2.2 (한국어)** https://www.icloud.com/shortcuts/0c6d8d6399934ac793d16f767760a25e <br /><br /> # Changelog: <br /> - Added iOS/ iPadOS info when showing software version. <br /> - Added software build behind software version. |

# How does it work?
- Shortcut Updater compares the latest version with the shortcut the user is using. If there's a new version, Shortcut Updater will get the iCloud link from the latest release on GitHub.

# Note:
- Shortcut Updater uses iCloud Drive by default to store log files. (Users have to enable iCloud Drive. If it's not enabled, a popup will appear.)
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:

[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

~~[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))~~
