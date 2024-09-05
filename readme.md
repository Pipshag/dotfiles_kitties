# Kitties UI-dots

Dotfiles for making your life better looking. Or at least your desktop.

This is a vertical [waybar](https://github.com/Alexays/Waybar/) setup with matching styles [hyprland](https://hyprland.org), [kitty](https://sw.kovidgoyal.net/kitty/), [wofi](https://hg.sr.ht/~scoopta/wofi), [cava](https://github.com/karlstav/cava). Includes:

- some custom scripts
  -- power on/off/sleep etc
  -- bluetooth connectivity w/ icons
- wofi,
- kitty and
- cava theme

**Requires Font Awesome 6 Pro**.
Well, really, just test with the free and find your own icons. I'm using the pro version.

This [firefox theme](https://addons.mozilla.org/en-US/firefox/addon/catppuccin-macchiato-green/) is a pretty good match.

For nvim the catppuccin macchiato color scheme is a good match.

### Screenshots

[![waybar](/screenshots/screenshot_waybar.resized.png?raw=true)](/screenshots/screenshot_waybar.png)
[![kitty](/screenshots/screenshot_kitty.resized.png?raw=true)](/screenshots/screenshot_kitty.png)
[![wofi](/screenshots/screenshot_wofi.resized.png?raw=true)](/screenshots/screenshot_wofi.png)
[![cava](/screenshots/screenshot_cava.resized.png?raw=true)](/screenshots/screenshot_cava.png)
[![nvim](/screenshots/screenshot_nvim.resized.png?raw=true)](/screenshots/screenshot_nvim.png)

## waybar

What is waybar?

> Highly customizable Wayland bar for Sway and Wlroots based compositors.
> Available in Arch community or AUR, openSUSE, and Alpine Linux

### Top

- Clock
- Tray

### Middle

- Workspaces (hyprland style)

#### Right

- Bluetooth icons for connected devices
  -- See waybar/custom_modules/bluetooth_devices.sh for more info
- Temperature
- Sound volume / panel
- Power menu
  -- Requires wofi

## hyprland

What is hyprland?

> Tiling compositor with the looks
> Hyprland provides the latest Wayland features, dynamic tiling, all the eyecandy, powerful plugins and much more

I've really only included colors and some looks. Integrate it as you see fit.

## kitty

What is kitty?

> kitty is a free and open-source GPU-accelerated terminal emulator for Linux, macOS, and some BSD distributions. focused on performance and features.

My term and config that includes font (Hack) and colors. Included is a ssh.conf that copies selected files and folders when used with **kitten ssh some-hostname-to-connect-to**

Screenshoot depicts kitty w/ [zunder-zsh](https://github.com/warbacon/zunder-zsh).

## wofi

What is wofi?

> Wofi is a launcher/menu program for wlroots based wayland compositors such as sway.

Styling and scripts (invoked through hotkey, set up your own).

## cava

What is cava?

> Cava is a bar spectrum audio visualizer for terminal or desktop (SDL).

Just some nice colors for cava.
