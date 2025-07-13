## fm3chanic Themes for Alacritty

This repository contains all color themes for the Alacritty terminal emulator I've created so far.<br> 
Alacritty is a highly configurable fast cross-plattform terminal emulator using gpu acceleration.

Themes which have been created during my project of color theming Vtubers are in the directory "vtuber_project". The folder "other" contains all color themes which where created outside of the project.

**[HTML Reference Sheets & Galery Non-Project Themes](https://github.com/fm3chanic/color_schemes)**<br>
**[Vtuber Project | Information & Galery](https://github.com/fm3chanic/vtuber_project)**

> [!IMPORTANT]
> Please note that all color themes have been originally created for Notepad++, which has the tendency to show colors lighter as they are in other applications. Therefore it might occur that the color theme is a bit on the darker side.

### Installation:

**Installation under Linux**

1. Copy the theme file to `~/.config/alacritty`.

2. Add the following line to your `alacritty.toml`:

```
general.import = [
"~/.config/alacritty/themefilename.toml"
]
````
3. Replace "themefilename" with the correct file name.

**Installation under Windows**

1. Copy the theme file to `%APPDATA%\alacritty`. (`%APPDATA%` leads to `C:\Users\YourUserName\AppData\Roaming`)

2. Add the following line to your `alacritty.toml`:

```
general.import = [
"C:/Users/YourUserName/AppData/Roaming/alacritty/themefilename.toml"
]
``` 
3. Replace "themefilename" and "YourUserName" with the correct file name and your Windows user name.

> [!Note]
> If you are using another directory for your `alacritty.toml` configuration file, it might make sense to copy the theme there.
> In that case also adjust your path in the configuration file accordingly.

For further information about the configuration of Alacritty check the **[documentation](https://alacritty.org/config-alacritty.html)**.

### Contribution:

If you want to help maintaining the themes, please use colors from the according color scheme. You can find the scheme files in the repo linked above.