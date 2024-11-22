# update-windows11-powershell
update windows11 powershell


Install-Module -Name PSWindowsUpdate -Force

Get-Command -Module PSWindowsUpdate

Get-WindowsUpdate -AcceptAll -Download -Install -MicrosoftUpdate
