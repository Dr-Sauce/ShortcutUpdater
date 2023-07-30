# Shortcut Updater 

Update shortcuts using GitHub. 

<img width="150" alt="0378ACF9-8014-4C25-8F72-80CD7E539E6B" src="https://user-images.githubusercontent.com/82555878/210124744-680186bc-e300-458f-9820-084acc4b0d09.png">

# Features:
- Check for update
- Upgrade/ downgrade

# How to use:
1. [Create a GitHub account](https://github.com/signup) or [login to your account](https://github.com/login).

And create a repository for your Shortcut.

2. Get the latest version of **Shortcut Updater** from [releases](https://github.com/Dr-Sauce/ShortcutUpdater/releases/latest). Open it in the Shortcuts app. Now merge **Shortcut Updater** to your shortcut. 

(Use [Join Shortcuts](https://routinehub.co/shortcut/10038/) to merge shortcuts)

3. Add the following info to the dictionary at the top of the shortcut.

|               | Description                                                                                      | Example            |
|---------------|--------------------------------------------------------------------------------------------------|--------------------|
| Name          | Enter the name of your shortcut.| TrollStore Checker |
| Version       | Enter the version of your shortcut release.                                                      | 1.1                |
| Github        | Enter your GitHub username.                                                    | Dr-Sauce           |
| Repository    | Enter the repository name for your shortcut.                                                     | TrollStoreChecker  |

4. Generate iCloud link for your shortcut.

5. Open the GitHub repository page you made for your shortcut. Go to releases and create a release.

Make sure to include iCloud link in body text.

|               | Description                                                                                                   | Example                                                                                                                                                                                                                                                                                                                   |
|---------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Release title | Enter a nice title for your shortcut release.                                              | TrollStore Checker 1.1                                                                                                                                                                                                                                                                                                     |
| Tag (version)           | Enter the version info here. Tag should be the same as the version info you typed in the shortcut.| 1.1                                                                                                                                                                                                                                                                                                                       |
| Body          | Release body should include the shortcut iCloud link.| **TrollStore Checker 1.1** <br /> https://www.icloud.com/shortcuts/31e7a02165c6494b8eb557c1939e3020 <br />  <br /> # Changelog: <br /> - Updated TrollStore install methods. <br /> - Added support for iOS 15.6 beta. <br /> - Added support for iOS 15.5 RC, 15.6 RC 1/2. |

# More information:

Shortcut Updater used to load the whole page of GitHub releases in the background to fetch info. The code was too heavy so I made it only run once a week/month. 

But soon I figured out log files were messy and GitHub API limit(60 times per hour, per IP) wasn't that bad to use. So I removed the old update method and adapted a upgraded version of auto update check starting with 2.0.

I personally recommend to use the latest version. (The main reason why I am keeping old versions which has spaghetti code in it, is to allow users to try out the downgrading feature) But if you want to use older versions check the chart below. You'll find some useful info.

| Version                  | Includes..                                                                                                                                                                                                                                                        | Recommended version |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| Shortcut Updater 1.0~1.5 | Auto update check. (Checks for update every ? days. Stores log file for this)<br><br>Enable/ disable update. (1.1~)<br>Downgrade feature (1.2~)<br>Manually check for update (1.2~)<br>GitHub API (1.2.1~)<br>Update log (1.4~)<br>Add multiple languages (1.5~) | 1.5                 |
| Shortcut Updater 1.6~1.7 | ‘Auto update check’ removed (To improve stability)<br><br>‘Enable/ disable update’ removed. (Not possible since this version no longer store logs on device)<br>Upgraded outdated code. (Improved release title, tag fetching process… and more)                              | 1.7                 |
| Shortcut Updater 2.0~    | Advanced auto update check. (Now checks for update everytime user launches shortcut. No longer stores logs)<br><br>‘Manually check for update’ removed. (No longer needed)                                                                                                               | Latest version                   |

# Note:
- ~~Shortcut Updater uses iCloud Drive by default to store log files. (Users have to enable iCloud Drive. If it's not enabled, a popup will appear.)~~
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:

[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

~~[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))~~

[Detect System Language JS](https://www.reddit.com/r/shortcuts/comments/c0bkad/comment/er4zrxb/) ([MMP0](https://www.reddit.com/user/MMP0))
