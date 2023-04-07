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

# Release note:

Shortcut Updater used to load the whole page of GitHub releases in the background to fetch info. The code was too heavy so I made it only run once a week/month. 

But soon I figured out log files were messing up and GitHub API limit(60 times per hour, per IP) wasn't that bad to use. So starting with 1.2.1 I switched the fetching method to GitHub API. And with 1.6 I completely removed auto update check and brought it back with a better method starting with 1.8.

I personally recommend people to use the latest version. But if you want to use older versions check the chart below.

| Version                  | Includes..                                                                                                                                                                                                                                                        | Recommended version |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| Shortcut Updater 1.0~1.5 | Auto update check. (Checks for update every ? days. Stores log files for this)<br><br>Enable/ disable update. (1.1~)<br>Downgrade feature (1.2~)<br>Manually check for update (1.2~)<br>GitHub API (1.2.1~)<br>Update log (1.4~)<br>Add multiple languages (1.5~) | 1.5                 |
| Shortcut Updater 1.6~1.7 | ‘Auto update check’ removed (To improve stability)<br><br>‘Enable/ disable update’ removed. (Not possible since it doesn’t store logs on device)<br>Upgraded outdated code. (Improved release title, tag fetching process… and more)                              | 1.7                 |
| Shortcut Updater 1.8~    | Advanced auto update check. (Now checks for update everytime user launches shortcut)<br><br>‘Manually check for update’ removed. (No longer needed)                                                                                                               | Latest version                   |

# Note:
- ~~Shortcut Updater uses iCloud Drive by default to store log files. (Users have to enable iCloud Drive. If it's not enabled, a popup will appear.)~~
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:

[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

~~[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))~~

[Detect System Language JS](https://www.reddit.com/r/shortcuts/comments/c0bkad/comment/er4zrxb/) ([MMP0](https://www.reddit.com/user/MMP0))
