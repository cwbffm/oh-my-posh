# Instalação PowerShell

- Baixe e instale powershell: ```winget install --id Microsoft.Powershell --source winget```


## Instalação OH MY POSH

- Oh My Posh: https://ohmyposh.dev/


```
Instalar Oh-My-Posh

winget install JanDeDobbeleer.OhMyPosh -s winget
$env:Path += ";C:\Users\user\AppData\Local\Programs\oh-my-posh\bin"
Get-Command oh-my-posh).Source 
```

```
Instalar as Fonts

oh-my-posh font install
```

```

Instalar PSReadLine e Icons

Install-Module PSReadLine -AllowPrerelease -Force
Install-Module -Name Terminal-Icons
```


# Criar arquivo de config: 

notepad $PROFILE

Meu arquivo de config completo:
```
Import-Module -Name Terminal-Icon
oh-my-posh init pwsh --config 'C:\Users\SEU USER AQUI\AppData\Local\Programs\oh-my-posh\themes\quick-term.omp.json' | Invoke-Expression
```
