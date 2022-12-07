# Linux Laptop Setup

## Update

```Bash
sudo apt update && sudo apt upgrade
reboot
```

## Remove Software

### Remove Firefox

```Bash
sudo snap remove firefox
```

### Remove Thunderbird

```Bash
sudo apt purge --yes --auto-remove thunderbird*
```

### Remove Rythmbox

```Bash
sudo apt purge --yes --auto-remove rhythmbox*
```

### Remove Libre Office

```Bash
sudo apt purge --yes --auto-remove libreoffice*
```

### Remove Shotwell

```Bash
sudo apt purge --yes --auto-remove shotwell
```

### Remove Cheese

```Bash
sudo apt purge --yes --auto-remove cheese
```

### Remove Totem

```Bash
sudo apt purge --yes --auto-remove totem
```

### Remove GEDIT

```Bash
sudo apt purge --yes --auto-remove gedit
```

### Remove Remina

```Bash
sudo apt purge --yes --auto-remove remmina 
sudo apt purge --yes --auto-remove remmina-plugin-rdp 
sudo apt purge --yes --auto-remove remmina-plugin-secret 
sudo apt purge --yes --auto-remove remmina-plugin-spice
```

### Remove Games

```Bash
sudo apt purge --yes --auto-remove aisleriot 
sudo apt purge --yes --auto-remove gnome-sudoku 
sudo apt purge --yes --auto-remove mahjongg 
sudo apt purge --yes --auto-remove ace-of-penguins 
sudo apt purge --yes --auto-remove gbrainy
sudo apt purge --yes --auto-remove gnome-mahjongg
sudo apt purge --yes --auto-remove gnome-mines
```

### Final Cleanup

```Bash
sudo apt autoremove
sudo apt update && sudo apt upgrade
reboot
```

## Software Installation

### Software Installation Preparation

```Bash
# Start in Home
cd ~
```

```Bash
# Deb packages will be stored here
mkdir ~/Deb
```

### Install Git

```Bash
sudo apt install git
```

### Install Curl

```Bash
sudo apt install curl
```

### Install Micro (Text Editor)

```Bash
sudo snap install --classic micro
```

### Install DotNet 6 SDK

```Bash
sudo apt install dotnet6
```

### Install PowerShell

```Bash
sudo snap install powershell --classic
```

### Install Microsoft Edge

[Download Microsoft Edge](https://www.microsoft.com/en-us/edge?form=MA13FJ#evergreen)

```Bash
mv ~/Downloads/microsoft-edge-stable_105.0.1343.53-1_amd64.deb ~/Deb
```

```Bash
sudo apt install libatomic1
```

```Bash
sudo dpkg -i microsoft-edge-stable_105.0.1343.53-1_amd64.deb
```

### Install Visual Studio Code

```Bash
sudo snap install --classic code
```

### Install Visual Studio Code Extensions

```Bash
code --install-extension mandeepsran.gruvbox-black
```

```Bash
code --install-extension formulahendry.code-runner
```

```Bash
code --install-extension heaths.vscode-guid
```

```Bash
code --install-extension pdconsec.vscode-print
```

```Bash
code --install-extension editorconfig.editorconfig
```

```Bash
code --install-extension janisdd.vscode-edit-csv
```

```Bash
code --install-extension mechatroner.rainbow-csv
```

```Bash
code --install-extension khaeransori.json2csv      
```

```Bash
code --install-extension richie5um2.vscode-sort-json
```

```Bash
code --install-extension euskadi31.json-pretty-printer
```

```Bash
code --install-extension sidneys1.gitconfig
```

```Bash
code --install-extension eamodio.gitlens
```

```Bash
code --install-extension dotjoshjohnson.xml
```

```Bash
code --install-extension redhat.java
```

```Bash
code --install-extension dbaumer.vscode-eslint
```

```Bash
code --install-extension rvest.vs-code-prettier-eslint
```

```Bash
code --install-extension ms-vscode.powershell
```

```Bash
code --install-extension ms-dotnettools.csharp
```

```Bash
code --install-extension donjayamanne.python-environment-manager
```

```Bash
code --install-extension kevinrose.vsc-python-indent
```

```Bash
code --install-extension ms-python.python
```

```Bash
code --install-extension ms-python.vscode-pylance
```

```Bash
code --install-extension njpwerner.autodocstring
```

```Bash
code --install-extension wholroyd.jinja
```

```Bash
code --install-extension njpwerner.autodocstring
```

```Bash
code --install-extension ms-toolsai.jupyter
```

```Bash
code --install-extension ms-toolsai.jupyter-keymap
```

```Bash
code --install-extension ms-toolsai.jupyter-renderers
```

```Bash
code --install-extension davidanson.vscode-markdownlint
```

```Bash
code --install-extension yzhang.markdown-all-in-one
```

```Bash
code --install-extension yzane.markdown-pdf
```

```Bash
code --install-extension phoihos.csv-to-md-table
```

```Bash
code --install-extension shd101wyy.markdown-preview-enhanced
```

```Bash
code --install-extension bierner.markdown-preview-github-styles
```

```Bash
code --install-extension josa.markdown-table-formatter
```

```Bash
code --install-extension esbenp.prettier-vscode
```

```Bash
code --install-extension stkb.rewrap
```

```Bash
code --install-extension tyriar.sort-lines
```

```Bash
code --install-extension janjoerke.align-by-regex
```

```Bash
code --install-extension streetsidesoftware.code-spell-checker  
```

### Install Latex

```Bash
sudo apt install texlive-full
```

### Install Anaconda

```Bash
mkdir ~/Conda
```

```Bash
cd ~/Conda
```

[Download Anaconda](https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh)

```Bash
bash anaconda.sh
```

```Bash
conda config --set auto_activate_base false
```

### Install Nerd Fonts

```Bash
git clone https://github.com/ryanoasis/nerd-fonts.git
```

```Bash
./install.sh Meslo
```

### Appearance Settings

```Bash
Settings -> Appearance
```

```Bash
Style Dark
```

```Bash
Show Personal Folder -> False
```

```Bash
Auto-Hid the Dock -> True
```

```Bash
Panel Mode -> False
```

```Bash
Show On -> All Displays
```

```Bash
Position on Screen -> Bottom
```

```Bash
Configure Dock Behavior -> Show Volumes and Devices -> False
```

### Accessibility Settings

```Bash
Large Text -> True
```

### Font Size Settings (Tweak Tool)

```Bash



### Install Tweak Tool

```Bash
sudo apt install gnome-tweaks
```

