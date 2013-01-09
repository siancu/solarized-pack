# solarized-pack

An [emacs-live](https://github.com/overtone/emacs-live) pack containing the Solarized color theme.

The Solarized theme is taken from [https://github.com/bbatsov/solarized-emacs](https://github.com/bbatsov/solarized-emacs).

## Installing and loading the pack

There are two ways in which the pack can be installed.

### Forked emacs-live

If you already have your own fork of emacs-live, then just add the [solarized-pack]() as a submodule in the packs/dev folder of your emacs-live and then run the `update-live-packs` script so that solarized-pack is added to the live packs.

Afterwards, create a `~/.emacs-live.el` file and use the function `live-add-packs` to load the solarized-pack:

    (live-add-packs '(live/solarized-pack))

### Official emacs-live

If you prefer to use emacs-live from the official repository, then first clone solarized-pack into a folder (for example `~/.live-packs/solarized-pack`).

Then create a `~/.emacs-live.el` file and use the function `live-add-packs` to load the solarized-pack:

    (live-add-packs '(~/.live-packs/solarized-pack))
