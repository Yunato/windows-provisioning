# windows-provisioning
Provisioning files for Windows 10.

# Setup
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
> cd ~
> git clone https://github.com/Yunato/windows-provisioning.git
```

# Usage

## Install applications

```
> choco install ~\windows-provisioning\package.config -y
```

## Upgrade

```
> choco upgrade all -y
```

# LICENSE
MIT
