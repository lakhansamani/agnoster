# Fish Agnoster theme

Fancy, colorful theme with support for Powerline fonts.

## Installation

You should use [Fisherman](https://github.com/fisherman/fisherman)

    fisher install hauleth/agnoster

Yeah, really. That's it. Be happy with your fancy new theme.

## Themes

To choose theme run `agnoster <theme name>`.

Available themes:

- `default` ![default theme](screenshots/default.png)
- `powerline` ![powerline theme](screenshots/powerline.png)

### Custom theme

You can create your own theme by setting these variables

```
# Segment endings
# AGNOSTER_SEGMENT_SEPARATOR[1] is separator of segment
# AGNOSTER_SEGMENT_SEPARATOR[2] is separator of subsegment
set -g AGNOSTER_SEGMENT_SEPARATOR '' '|'

# Icons
set -g AGNOSTER_ICON_ERROR \u2717 # unicode ballot X (✗)
set -g AGNOSTER_ICON_ROOT \u26a1 # unicode high voltage sign (⚡)
set -g AGNOSTER_ICON_BGJOBS \u2699 # unicode gear (⚙)
set -g AGNOSTER_ICON_GIT_BRANCH \u2387 # unicode alternative key symbol (⎇)
set -g AGNOSTER_ICON_GIT_REF \u27a6 # unicode heavy black curved upwards and rightwards arrow (➦)
```

## Licence

Check [LICENSE](LICENSE)
