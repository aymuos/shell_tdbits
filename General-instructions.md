## Connect to windows files from WSL2 Linux distro 
` cd /mnt/d `     for D drive  or `cd /mnt/c`  for C drive 

Alternatively , to access linux files run the following 
` \\wsl.localhost\Ubuntu` 

## Install Chocolaety 

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`

with Powershell as admin 

Install nvm-windows : https://github.com/coreybutler/nvm-windows
istall nvm in WSL : 

