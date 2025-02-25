# wofi-emoji 🥞

Simple emoji selector for Wayland using [wofi](https://cloudninja.pw/docs/wofi.html) that relies on [wtype](https://github.com/atx/wtype) and [wl-clipboard](https://github.com/bugaevc/wl-clipboard).

![Screenshot of wofi-emoji in action](https://i.imgur.com/8XiUoh6.png)

## Fork

This fork exists purely because I needed the wofi prompt to use a normal window instead of the default one, check out my [rice](https://github.com/katieumbra/Dotfiles) to see its usage.

## Usage

Download [wofi-emoji](https://github.com/KatieUmbra/wofi-emoji/raw/master/wofi-emoji), ensure it's executable and somewhere in your `$PATH`.
Alternatively download it inside `~/.config/wofi/wofi-emoji/` and point to the executable instead

- With sway

    Add a shortcut key in your [sway](https://swaywm.org/) config:

    ```
    # ~/.config/sway/config

    bindsym Mod4+e exec path/to/wofi-emoji
    ```

- With niri


    Add a shortcut key in your [niri](https://github.com/YaLTeR/niri) config:

    ```
    # ~/.config/niri/config.kdl

    Mod+Period { spawn "path/to/wofi-emoji"; }
    ```

## Credits

* Original author: [dln](https://github.com/dln)
* Current maintainer: [Zeioth](https://github.com/Zeioth)
* Fork maintainer: [Katherine](https://github.com/katieumbra)

## 🌟 Support the project
Star this repository (and the original one) and vote the [AUR package](https://aur.archlinux.org/packages/wofi-emoji) to increase the visibility of the project.

## Roadmap
This project is community driven. If you have a proposal, send a PR and I will review it.
