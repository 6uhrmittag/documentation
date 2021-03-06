# Tools to install

# via patchmypc

see https://patchmypc.com/home-updater-download

- Foxit Reader
- ImageGlass
- Notepad++
- Dropbox
- Git version
- GitHub Desktop
- Google Chrome
- Microsoft Visual C++ 2010 x64 Redistributable
- Microsoft Visual C++ 2010 x86 Redistributable
- Microsoft Visual C++ 2012 Redistributable (x64)
- Microsoft Visual C++ 2012 Redistributable (x86)
- Mozilla Firefox
- TeraCopy version
- TreeSize Free
- VLC media player
- WinRAR
- Wireshark

# manual setup

- Vagrant
- Virtualbox (Check Version - must work with Vagrant)
- [KiTTY](http://kitty.9bis.net/)
- Pycharms via jetbrains-toolbox
- https://www.binisoft.org/wfc
- https://github.com/jimradford/superputty
- https://portal.office.com/account
- https://sourceforge.net/projects/vcxsrv/
- https://www.samsung.com/semiconductor/minisite/ssd/product/consumer/magician/
- Terminal/Powershell AddOn [/setup/windows/terminal/](/setup/windows/terminal/)
- https://mpv.io/installation/

# Via WindowsStore

- Windows Terminal: https://aka.ms/terminal
    - https://github.com/microsoft/terminal

# manual setup optional

- ScreenToGif: https://www.screentogif.com/
- Hosts File Editor: https://hostsfileeditor.com/

# manual config

## Putty

- https://github.com/jacktrocinski/pretty-putty
    - **Note:** Will change mouse-shortcut `right-click to paste/insert` to wheel-click! change after import back to right-click(Win default)

# via scoop (optional)

- https://github.com/lukesampson/scoop
- https://rasa.github.io/scoop-directory/by-stars

All Commands in Powershell

````powershell
iwr -useb get.scoop.sh | iex
scoop bucket add extras # add more Tools
scoop bucket add nirsoft # add nirsoft systemtools
scoop bucket add Sysinternals 'https://github.com/Ash258/Scoop-Sysinternals.git' # add sysinternal tools
scoop bucket add Ash258 'https://github.com/Ash258/Scoop-Ash258.git' # add more 3rd party tools
scoop install sudo # to use --global
scoop install aria2 # better download performance
````

## Usage

````powershell
scoop list
scoop install <app>
sudo scoop install --global <app>
scoop update
scoop update <app>
scoop uninstall <app>
````

