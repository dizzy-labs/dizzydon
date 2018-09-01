# Dizzydon
(Requires [Stylus](https://add0n.com/stylus.html)) A customizable userstyle for Mastodon
# Features
* Custom css for mastodon
* Supports vanilla, glitch-soc, and sleeping town front ends
* Default theme based on pico-8 palette
* Customizable colors and toggles for shadows and transparency

# How to Install
(First, install [Stylus](https://add0n.com/stylus.html) for your browser if you haven't aleady.)

The easiest way is to [install dizzydon](https://raw.githubusercontent.com/dizzy-labs/dizzydon/master/dizzydon_source.user.css) by opening the .user.css file in stylus and clicking <b>Install Style</b> in the top left.

Alternatively, download <b>dizzydon.json</b> from the [current release](https://github.com/dizzy-labs/dizzydon/releases/tag/v2.0.0) -> Open the management page for stylus (click the stylus icon in your browser and click <b>"manage"</b>) -> click <b>"Import Styles"</b> in the bottom of the left column -> open <b>dizzydon.json</b>

After installing you can open the config menu by clicking the gear icon either on the management page or after clicking the icon in your browser.

# Updating
Open the management page for stylus and click the refresh icon for the style
Alternatively, follow the install instructions again for the new version and it will overwrite the old version.

# Troubleshooting and FAQ
* # What's Pico-8stodon?
* * This is the older version of Dizzydon. It's recommended that you use Dizzydon instead, as this is no longer actively maintained and lacks all of Dizzydon's customization without any benefits of it's own. It's available on userstyles.org so you can download it easily from there if you like the default colors and transparency effects.
[Install with Stylus from userstyles.org](https://userstyles.org/styles/163455/pico-8stodon) 
* # Hey, this doesn't change anything on my instance?
* * Be sure to add your mastodon instance to the "Applies to" section on the styles settings page to use it on an instance that's not alread set up. Open the management page for Stylus, then click this style in the list, then add your instances domain to the list of websites it applies to at the bottom or middle of the edit page.

* # The shadows are flickering
* * Drop shadows use hardware-acceleration, so this is probably related to your graphics hardware.
* * If using Dizzydon, turn off the drop-shadows in the settings menu.
* * If using pico-8stodon, install the no-filter version. Open the management page for stylus -> click the "Write new style" button -> click the import button under Mozilla Format -> copy and paste the code from pico-8stodon_no-filter.css -> name it and save. Then just use that version as you would the other.
