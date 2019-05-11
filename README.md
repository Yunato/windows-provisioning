# windows-provisioning
Provisioning files for Windows

# Usage (Windows 10)
## First step

Install with PowerShell.exe

```
> Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

Confirm

```
> choco -v
```

## Second step

Install git

```
> choco install git -y
```

## Third step

Clone this repository

```
> git clone https://github.com/Yunato/windows-provisioning.git
```

## Forth step

Install applications

```
> cd ./windows-provisioning
> choco install .\package.config -y
```

# Upgrade

```
> choco upgrade all -y
```

# LICENSE
MIT
