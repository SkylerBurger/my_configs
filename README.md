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
- **`pip3`**: 
  - `sudo apt install python-pip3`
  - `sudo apt update`
- **`fusuma`**: 
  - Follow instruction in the [GitHub repo](https://github.com/iberianpig/fusuma)
  - Add to startup applications
  - Add `config.yml` to `~/.config/fusuma`
- **Workspace Matrix**:
  - Use Ubuntu Software to install 
  - Set up a horizontal arrangement of workspaces (3 col by 1 row)
  - Change Ubuntu keyboard shortcuts so CTRL + ALT + (LEFT or RIGHT) moves up or down a workspace rather than left or right.
- **`pipenv`**:
  - `pip3 install --user pipenv` 
  - [Documentation](https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv)
- **`tilda`**:
  - `apt install tilda`
  - Add to startup applications
  - Add `config_0` to `~/.config/tilda`
  - [GitHub repo](https://github.com/lanoxx/tilda)
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