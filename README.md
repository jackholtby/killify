# killify

### What it does
Instructions on how to setup a shortcut to restart Spotify when an ad comes on in Spotify desktop client (on Linux currently)
Basically I thought a script was needed, but not really... just two commands.

## Setup - KDE
(I'm using Plasma 5.14.5 on Debian 10).
1. Open settings.
2. Go to Shortcuts > Custom Shortcuts
3. Right click on the left pane in under the Configure Input Actions settings heading.
4. Select New > Global Shortcut > Command/URL
5. Name it "Killify" or whatever you'd like.
6. With Killify selected, select the Trigger tab in the right pane and add your preferred shortcut. Mine is Ctrl+Shift+P.
7. In the Action tab, enter "pkill spotify && spotify" into the Command/URL textbox.
8. Ya done.
