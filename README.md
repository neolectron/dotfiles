# Dotfiles
Collection of simple configurations files 

# Philosophy
We're not here to fap our brain on some complicated setup.

The main argument is the simplicity of it, yet it's still elegant.

# Technologies
Theses dotfiles are meant with [sway](https://swaywm.org/) desktop environment,
therefore [wayland](https://wayland.freedesktop.org/) is mandatory.

To use it, you can either pick the conf for specific sofware, or all-in with my sway config.

I use [chezmoi](chezmoi.io) to manage my dotfiles, and I advise you to do the same.

# Known issues
- The top bar (waybar) is missing a pretty font with icons.
- XDG variables aren't set in /etc/profile, so some non-XDG-standard softwares might not pick your prefered default.
- The screenshot button doesn't start the screenshot command, because I want it to work like on windows, where it "freeze" your screen below the selection.

# State of the project
As you can see, I'm still figuring out some stuff to make things work as smooth as possible with wayland. This config is subject to change from day to day, but only to improve itself, without adding extra complexity.
I aim for full transparency, that's why, altough unrelated, you will find [a list of known wayland limitations](#wayland-limitations) down below.

# Screenshots
![image](https://user-images.githubusercontent.com/5268400/188838375-3f1b57a3-2abf-4aba-a1cd-599d41b7db6f.png)
![image](https://user-images.githubusercontent.com/5268400/188839157-bb1909bc-5223-4a50-9720-f0f5c56d8dbb.png)

# Wayland limitations
- Discord screen-sharing doesn't really work well with wayland if you use the default repository, but some fixed versions exists out there (until they update their electron version to be > 19).
- OBS doesn't support custom-browser docks yet, probably v29 will fix it (yet everything else works perfectly).
