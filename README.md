# A userstyle for Mastodon
* Custom css for mastodon.
* Supports vanilla, glitch-soc, and sleeping town front ends.
* Based on pico-8 pallette.
* Requires [Stylus](https://add0n.com/stylus.html)

# Dizzydon
Dizzydon is a usercss conversion of the older pico-8stodon.css
That just means it's got customizable colors and toggles for shadows and transparency.
To use it: Open the management page for stylus -> check "as Usercss" next to the "Write new style" button -> click the "Write new style" button -> select ALL of the code already in the editor -> copy and paste the code from dizzydon.css over it -> save. Click the gear in the stylus menu to change settings.

# Pico-8stodon
This is the older version of Dizzydon. It's hosted on userstyles.org so you can download it easily from there if you like the default colors and transparency effects.
[Install with Stylus from userstyles.org](https://userstyles.org/styles/163455/pico-8stodon) 

# Troubleshooting
* # Hey, this doesn't change anything on my instance?
* * Be sure to add your mastodon instance to the "Applies to" section on the styles settings page to use it on an instance that's not alread set up. Open the management page for Stylus, then click this style in the list, then add your instances domain to the list of websites it applies to at the bottom or middle of the edit page.

* # The shadows are flickering
* * Drop shadows use hardware-acceleration, so this is probably related to your graphics hardware.
* * If using Dizzydon, turn off the drop-shadows in the settings menu.
* * If using pico-8stodon, install the no-filter version. Open the management page for stylus -> click the "Write new style" button -> click the import button under Mozilla Format -> copy and paste the code from pico-8stodon_no-filter.css -> name it and save. Then just use that version as you would the other.
