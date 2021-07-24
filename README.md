# ToggleRealtekAudio
Create a windows shortcut by right clicking, selecting new and then shortcut
# Set this as the target
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -command "Get-PnpDevice -FriendlyName \"Realtek(R) Audio\" | Disable-PnpDevice -confirm:$false; Get-PnpDevice -FriendlyName \"Realtek(R) Audio\" | Enable-PnpDevice -confirm:$false"
# Admin
Once created, right click, go to advanced and select run as admin
