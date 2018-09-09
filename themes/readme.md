# Themes
Themes are stripped down versions of dizzydon that only alter the colors and nothing else. They are meant to be used in addition to Dizzydon to allow custom color settings to be saved and shared.

Dizzydon themes are installed and used just like the base Dizzydon.
Open the raw <theme>.user.css file in your browser and install it with stylus. Then enable it on any site you use Dizzydon on so it overrides the colors.

# Can I make a theme?
Yes! Unfortunately the process is a little non-trivial. First, You'll need to download a theme to use as a template (I suggest [dizzydon-default.](https://raw.githubusercontent.com/dizzy-labs/dizzydon/master/themes/dizzydon-default.user.css) Then just copy and paste your color settings over defaults set in that (the last part of the lines that look like this '@var color primaryFontColor "Primary font color" #fff1e8' is the default color for that setting). Finally, give it a new name by changing the name after '@name' at the top and save it. If you want your new theme added to this folder, feel free to submit a pull request.
