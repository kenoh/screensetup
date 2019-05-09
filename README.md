# screensetup
Application for setting up screen in Linux

## Requirements
Python 3.6+

TODO

## Configuration
Configuration file is `~/.screensetup`. Its JSON schema is at the top of the script.

Example:
```yaml
default-setup:
  dpi: 96
  displays:
    LVDS1:
      mode: 1920x1080
setups:
  laptop:
  desktop:
    displays:
      LVDS1:
        mode: 1920x1080
      HDMI1:
        mode: 1920x1080
        right-of: LVDS1
```

## Usage
Run with `--help` to see options. Should be straigtforward.
