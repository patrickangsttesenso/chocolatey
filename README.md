# Chocolatey

## Install Chocolatey

Run PowerShell as admin and paste:
```ps1
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

7-Zip
```ps1
choco install 7zip
```

Git
```ps1
choco install git
```

VS Code
```ps1
choco install vscode
```

Google Drive
```ps1
choco install googledrive
```