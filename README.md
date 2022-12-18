# Shortcut Updater

Shortcut Updater was created because I wasn't satisfied with the shortcut updaters that use third party APIs. (Third party APIs require shortcuts to be uploaded to their own site. Since I upload shortcuts on GitHub, I didn't want to upload to two different places.)

This shortcut updater gets the latest version from GitHub releases. To make this possible the shortcut loads the repository's latest release page. This makes the shortcut much heavier than other shortcut updaters which just works with a few actions. But to make it work like magic, I chose to do it like this.

This shortcut is designed to work with my own shortcuts, so it may be hard to implement this updater to your shortcuts.

# Q&A:

**○ Why doesn't Shortcut Updater use GitHub API (instead of loading the whole release page)?**

GitHub API is faster but has limits. (I don't want people complaining about they're getting an error.)

**○ How does Shortcut Updater manage the heavy code?**

Shortcut Updater only runs the update action when 7 days have passed. (You can change the day settings.)

# Source:
[Silent Updater](https://www.reddit.com/r/shortcuts/comments/k094tf/shortcut_updater_tutorial/) ([u/robric18](https://www.reddit.com/user/robric18))

[Remove Duplicates](https://www.reddit.com/r/shortcuts/comments/fv1l2u/comment/fmfzzn3/) ([u/RogerDowning](https://www.reddit.com/user/RogerDowning))
