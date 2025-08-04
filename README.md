# Shortcut Updater 

Update shortcuts using GitHub.

Designed to work on iOS 15. (But also works on other versions)

<img width="100" alt="0378ACF9-8014-4C25-8F72-80CD7E539E6B" src="https://user-images.githubusercontent.com/82555878/210124744-680186bc-e300-458f-9820-084acc4b0d09.png">

# Features:
- Check for updates.
- Upgrade· downgrade.

# How to use:
1. [Create a GitHub account](https://github.com/signup) or [login to your account](https://github.com/login).

And create a repository for your Shortcut.

2. Get the latest version of **Shortcut Updater** from [releases](https://github.com/Dr-Sauce/ShortcutUpdater/releases/latest). Open it in the Shortcuts app. Now merge **Shortcut Updater** to your shortcut. 

Use [Join Shortcuts](https://routinehub.co/shortcut/10038/) to merge shortcuts.

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

# Note:
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:
[Detect System Language JS](https://www.reddit.com/r/shortcuts/comments/c0bkad/comment/er4zrxb/) ([MMP0](https://www.reddit.com/user/MMP0))
