# webdev-setup
Web development setup, environment and configurations.

### Presetup

[winfiles](https://github.com/webdev4422/winfiles)

[.dotfiles](https://github.com/webdev4422/.dotfiles)

## WSL
### Install WSL
wsl --install

https://docs.microsoft.com/en-us/windows/wsl/install

### Build tools
sudo apt install -y build-essential git curl nginx

### nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

### Node.js
curl -fsSL https://deb.nodesource.com/setup_lts.x | bash -
apt-get install -y nodejs

## Windows
### Uninstall apps
winget uninstall  "Microsoft People"

### Install apps
winget install Lexikos.AutoHotkey;
winget install hluk.CopyQ;
winget install Microsoft.WindowsTerminal.Preview; 
winget install Microsoft.VisualStudioCode;
winget install Google.Chrome;
winget install Telegram.TelegramDesktop;
winget install Kingsoft.WPSOffice;

### VScode
Install Remote Development Extension Pack https://code.visualstudio.com/docs/remote/wsl

Vue Language Features (Volar)
