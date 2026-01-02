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

The themes are based on the mapped template in directory **/tools**.<br>
The python script (_\[...\]\_load_colors.py_) reads the colors from a html file from [color_schemes](https://github.com/fm3chanic/color_schemes) and uses replace to fill in the colors.<br>

If you want to work on colors it makes the most sense to change the colors in repository [color_schemes](https://github.com/fm3chanic/color_schemes) so the changes can be applied to all applications using the theme.<br>
If you want to work on the mapping of the colors it might make sense to change the base template, so changes can be applied to all themes of this application.<br>

Neverless, **I also welcome contribution not following this standard**. The standard was made to keep it maintainable for one person, not to block community ideas.<br>