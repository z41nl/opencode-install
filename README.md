# opencode-install

ps1

irm get.scoop.sh | iex

scoop --version


Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

scoop bucket add extras; scoop install extras/opencode-desktop

opencode --version

#oh my opencode 

powershell -c "irm bun.sh/install.ps1|iex"

bunx oh-my-opencode install

