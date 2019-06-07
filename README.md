# What is this?
Custom themes to spice your Spotify client up using [spicetify-cli](https://github.com/khanhas/spicetify-cli)

# What's on the menu?
Check available [Themes](https://github.com/DoubleJarvis/SpicetifyThemes/wiki/Themes)

# How to use?
Install spicetify using instructions on its github page.
Locate your Themes folder:
```
Windows: %userprofile%\.spicetify\Themes\
Linux: $XDG_CONFIG_HOME/.config/spicetify/Themes/ or ~/.config/spicetify/Themes
MacOS: ~/spicetify_data/Themes
```
Clone this repo into your Themes folder:
```sh
git clone https://github.com/DoubleJarvis/SpicetifyThemes ~/.config/spicetify/Themes
```
Alternatively clone the repo into whatever directory, and copy desired theme folders into your Themes directory.
You should end up with structure like:
```
.config/spicetify/Themes/SomeTheme/user.css
.config/spicetify/Themes/SomeTheme/color.ini
.config/spicetify/Themes/AnotherCoolTheme/user.css
.config/spicetify/Themes/AnotherCoolTheme/color.ini
```
Locate your `config.ini`:
```
Windows: %userprofile%\.spicetify\config.ini
Linux: $XDG_CONFIG_HOME/.config/spicetify/config.ini or ~/.config/spicetify/config.ini
MacOS: ~/spicetify_data/config.ini
```
Set desired theme in your `config.ini`:
```ini
[Setting]
...
current_theme = TychoAwake
...
```
Apply the theme:
```sh
spicetify apply
```
Refer to spicetify-cli [wiki pages](https://github.com/khanhas/spicetify-cli/wiki/Basic-Usage) if you need additional usage information.