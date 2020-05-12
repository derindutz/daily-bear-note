# daily-bear-note
Automatically creates a note in [Bear](https://bear.app/) titled with today's date.

![Daily Bear Note Screenshot](/daily-bear-note-screenshot.png)

If you're logged into your computer, the note is created at 4AM. Otherwise, the note is created whenever you log in.


## Installation
1. Download `daily-bear-note.scpt` and put it somewhere on your computer. Mine is at `/Users/derindutz/Dropbox/Developer/scripts/daily-bear-note.scpt`

2. Download `local.DailyBearNote.plist` and open it in your favorite editor

3. Replace ABSOLUTE_PATH_TO_SCRIPT with the path to `daily-bear-note.scpt`. As above, mine is `/Users/derindutz/Dropbox/Developer/scripts/daily-bear-note.scpt`

4. Save `local.DailyBearNote.plist` and put it in `~Library/LaunchAgents`

5. Log out and back in and everything should be good to go! You can test it by running `launchctl start local.DailyBearNote` from your terminal
