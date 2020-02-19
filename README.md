# windows-test
 
open powershell as administrator
 
```js
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

```shell
choco install git.install
choco install docker-desktop
choco install yarn
choco install nodejs
choco install vscode -y
```

find ssh key under your home .ssh
