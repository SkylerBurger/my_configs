# My Configs

These are my common config files that I often will need when setting up a new Ubuntu environment. Some common project resources may end up here as well.

## Contents
- `.bashrc`: Configuration file for BASH terminal
- `.gitconfig`: Configuration file for `git`
- `.gitignore`: Common Git Ignore for Python projects
- `.profile`: Configuration file for BASH terminal
- `config_0`: Configuration file for `tilda` terminal
- `config.yml`: Configuration file for `fusuma` multi-touch gestures
- `django-html.json`: My user-created snippets for VS Code's Django extension

## Applications to Install:
- **General Updates**:
  - `sudo apt update`
  - `sudo apt upgrade`
  - `sudo apt autoremove`
- **General Settings**:
  - Dock > Auto-hide the Dock <-- Toggle ON
  - Dock > Icon size <-- Set to 30px
- **General Applications**:
  - Chrome
  - Slack
  - Spotify
- **`pip3`**: 
  - `sudo apt install python3-pip`
  - `sudo apt update`
- **`pipenv`**:
  - `pip3 install --user pipenv` 
  - [Documentation](https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv)
- **`git`**:
  - `sudo apt install git`
  - Add `.gitconfig` to `~/`
- **GNOME Tweaks**:
  - Use Ubuntu Software to install
  - Extensions > Desktop Icons > Settings Gear <-- Turn OFF personal folder AND trash icon toggles
  - Appearance > Applications <-- Yaru-Dark
  - Top Bar > Activities Overview Hot Corner <-- Toggle ON
  - Top Bar > Battery Percentage <-- Toggle ON
  - Windows > Center New Windows <-- Toggle ON
- **`tilda`**:
  - `sudo apt install tilda`
  - Start `tilda` once before proceeding
  - Replace `config_0` at `~/.config/tilda` with the copy from this repo
  - Add to startup applications
  - [GitHub repo](https://github.com/lanoxx/tilda)
- **`fusuma`**: 
  - Follow instruction in the [GitHub repo](https://github.com/iberianpig/fusuma)
  - Create`fusuma` directory in `~/.config`
  - Add `config.yml` to `~/.config/fusuma`
  - Add to startup applications
- **Workspace Matrix**:
  - Use Ubuntu Software to install 
  - Set up a horizontal arrangement of workspaces (3 col by 1 row)
  - Change Ubuntu keyboard shortcuts so CTRL + ALT + (LEFT or RIGHT) moves up or down a workspace rather than left or right.
- **VS Code**:
  - Extensions:
    - autoDocstring - Docstrings for Python
    - Material Theme
    - Material Icon Theme
    - Edit csv
    - Live Share
    - Python
    - TODO Highlight
    - Docker
    - Django
  - Place `django-html.json` into `./config/Code/User/snippets`
- **Font Packs**:
  - [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
