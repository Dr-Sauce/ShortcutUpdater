# Shortcut Updater 

Update your shortcut using GitHub.

<img width="150" alt="0378ACF9-8014-4C25-8F72-80CD7E539E6B" src="https://user-images.githubusercontent.com/82555878/210124744-680186bc-e300-458f-9820-084acc4b0d09.png">

# Features:
- Check for update every ? days.
- Skip update check if there's no internet.
- Check for update manually.
- Downgrade shortcut.
- Disable updates.

# How to use:
1. Implement Shortcut Updater to your shortcut. (Make sure to edit the dictionary on the top.)
2. Upload your shortcut to GitHub releases. (Release title should be 'Shortcut Name 1.0'. And tag should be 1.0. Paste the shortcut iCloud link in the description.)
3. Done.

# How does it work?
- Shortcut Updater checks the latest version tag of the shortcut and compares it to the shortcut version saved on the users device. 

If there's a new version, Shortcut Updater will get the iCloud link from the latest release description on GitHub.

# Note:
- Shortcut Updater uses iCloud Drive by default to store log files. (Users have to enable iCloud Drive. If it's not enabled, a popup will appear.)
- This shortcut uses GitHub API. The API limit is 60 times per hour, per IP.

# Source:

[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))
