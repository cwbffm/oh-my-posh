
- Baixar o powershell: https://learn.microsoft.com/pt-br/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4#winget 
- NerdFont: https://www.nerdfonts.com/font-downloads
- Oh My Posh: https://ohmyposh.dev/
- Instalar PSReadline: Install-Module PSReadLine -AllowPrerelease -Force
- Instalar icones: Import-Module -Name Terminal-Icons 
- Criar arquivo de config: .$PROFILE ou code $PROFILE 


Meu arquivo de config completo:

oh-my-posh init pwsh --config 'C:/Users/MUDE-AQUI-SEU-NOME/AppData/Local/Programs/oh-my-posh/themes/atomic.omp.json' | Invoke-Expression
Import-Module -Name Terminal-Icons
