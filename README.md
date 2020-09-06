# Terminator Lighthaus
A [Lighthaus](https://github.com/lighthaus-theme/lighthaus) theme for [Terminator](https://github.com/gnome-terminator/terminator).

### Table of Contents
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Version](#version)
- [Bugs/Issues](#bugs/issues)
- [License](#license)

### Screenshots

<p align="center"><img src="https://raw.githubusercontent.com/lighthaus-theme/terminator/master/terminator-01.png"><p>

<p align="center"><img src="https://raw.githubusercontent.com/lighthaus-theme/terminator/master/terminator-02.png"><p>

<p align="center"><img src="https://raw.githubusercontent.com/lighthaus-theme/terminator/master/terminator-03.png"><p>

Font used in the screenshots: [Source Code Pro for Powerline](https://github.com/powerline/fonts/tree/master/SourceCodePro)

### Installation
To use the Lighthaus theme for Terminator, copy the content from Lighthaus [`config`](https://github.com/lighthaus-theme/terminator/blob/master/src/config) to your `~/.config/terminator/config`.

- Add the `[global_config]` to your `~/.config/terminator/config`
    -   ```
        [global_config]
        title_hide_sizetext = True
        title_transmit_fg_color = "#FFFF00"
        title_transmit_bg_color = "#18191E"
        title_receive_fg_color = "#ED722E"
        title_receive_bg_color = "#21252D"
        title_inactive_fg_color = "#FFFADE"
        title_inactive_bg_color = "#21252D"
        ```

- Add the `lighthaus` profile to your  `profiles` in 2`~/.config/terminator/config`
    -   ```
        [profiles]
            [[lighthaus]]
                background_color = "#18191E"
                cursor_color = "#FFFF00"
                cursor_color_fg = False
                foreground_color = "#FFEE79"
                scrollbar_position = hidden
                palette = #18191E:#FC2929:#44B273:#E25600:#1D918B:#D16BB7:#00BFA4:#CCCCCC:#21252D:#FC5050:#50C16E:#ED722E:#47A8A1:#D68EB2:#5AD1AA:#FFFADE"

        ```

_For more information refer to the [project man page](https://linux.die.net/man/5/terminator_config)._

### Version
```
v 1.0.0
```

_Lighthaus and all it's projects use [Semantic Versioning](https://semver.org/)._ <br/>
_All changes are recorded in [CHANGELOG](https://github.com/lighthaus-theme/terminator/blob/master/CHANGELOG.md)_

### Bugs/Issues
Please report any bugs or issues [here](https://github.com/lighthaus-theme/terminator/issues).

### License 

_Copyright © 2020-Present Lighthaus Theme_<br>
_Copyright © 2020-Present Adhiraj Sirohi_<br>
_Copyright © 2020-Present Vasundhara Sharma_

<p align="left"><a href="https://github.com/lighthaus-theme/terminator/blob/master/LICENSE"><img src="https://img.shields.io/static/v1.svg??style=flat&logo=appveyore&label=License&message=MIT&colorA=1C918A&colorB=50C16E"/></a></p>

<p align="center"><img src="https://raw.githubusercontent.com/lighthaus-theme/lighthaus/9e5cf66db03fc3e183e6cfbf7c4c04263a4f23df/ImageResources/lighthaus-border.svg"><p>

