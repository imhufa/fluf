# ALL HAIL LORD FLUFF! JACK-OF-ALL-FLUFFY, MASTER OF ALL!

![Markdownlint](https://github.com/imhufa/fluf/workflows/Markdownlint/badge.svg)

## lordfluffy is life:

- `lordfluffy must be hailed.`
- `he is the answer.`
- `he is the truth.`
- `he speaks the coding-language of gods.`

## build a temple for our Lordfluffy:

### clone repo

```console
git clone https://github.com/imhufa/fluf.git
```

### to build his holy temple on bill gate's operating system:

1. install .NET [elevated powershell]:
> [!WARNING]
> if you dont know how to run powershell. dude.dudette, just stop. go back to your videogame.

```console
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Bypass -Force
Invoke-WebRequest -Uri "https://dot.net/v1/dotnet-install.ps1" -OutFile dotnet-install.ps1 -UseBasicParsing 2>&1 | Out-Null
Unblock-File dotnet-install.ps1
.\dotnet-install.ps1 -Runtime windowsdesktop && .\dotnet-install.ps1 -Runtime aspnetcore
Write-Host "ALL HAIL LORDFLUF!"
```

2. compile and build
```console
$holytemple = "$(echo "${pwd}")/fluf"

cd $holytemple
dotnet publish
dotnet run
```
