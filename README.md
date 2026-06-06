# ps1 - admin


> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser


> irm get.scoop.sh | iex

or

> iex "& {$(irm get.scoop.sh)} -RunAsAdmin"


new ps window

> scoop --version

> scoop install git

> scoop bucket add extras; scoop install extras/opencode-desktop

or

> scoop install opencode-desktop

#omo

https://nodejs.org/en/download

> powershell -c "irm bun.sh/install.ps1|iex"

> bunx oh-my-opencode install

> bunx oh-my-openagent install
