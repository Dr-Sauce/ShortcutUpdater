# Shortcut Updater 

Update shortcuts uploaded to GitHub. 

<img width="150" alt="0378ACF9-8014-4C25-8F72-80CD7E539E6B" src="https://user-images.githubusercontent.com/82555878/210124744-680186bc-e300-458f-9820-084acc4b0d09.png">

# Features:
- Check for update.
- Upgrade/ Downgrade.

# How to use:
1. Implement Shortcut Updater to your shortcut.

Add the following info to the dictionary at the start of the shortcut.

|               | Description                                                                                      | Example            |
|---------------|--------------------------------------------------------------------------------------------------|--------------------|
| Name          | Enter the name of your shortcut.| TrollStore Checker |
| Version       | Enter the version of your shortcut release.                                                      | 2.2                |
| Github        | This is where you enter your GitHub username.                                                    | Dr-Sauce           |
| Repository    | Enter the repository name for your shortcut.                                                     | TrollStoreChecker  |

2. Upload your shortcut to GitHub releases.

|               | Description                                                                                                   | Example                                                                                                                                                                                                                                                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Release title | Enter a nice title for your shortcut release.                                              | TrollStore Checker 2.2                                                                                                                                                                                                                                                                                                     |
| Tag (version)           | Enter the version info here. Tag should be the same as the version info you typed in the shortcut.| 2.2                                                                                                                                                                                                                                                                                                                       |
| Body          | Release body should include the shortcut iCloud link.| **TrollStore Checker 2.2** https://www.icloud.com/shortcuts/c475c0f149fb4ea8b659d7b7ca6ecf48 <br /><br /> # Changelog: <br /> - Added iOS/ iPadOS info when showing software version. <br /> - Added software build behind software version. |

# Note:
- ~~Shortcut Updater uses iCloud Drive by default to store log files. (Users have to enable iCloud Drive. If it's not enabled, a popup will appear.)~~
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:

[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

~~[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))~~

[Detect System Language JS](https://www.reddit.com/r/shortcuts/comments/c0bkad/comment/er4zrxb/) ([MMP0](https://www.reddit.com/user/MMP0))
