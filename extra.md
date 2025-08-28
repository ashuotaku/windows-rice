## Paste this in powershell with elevated privileges.
`Set-ItemProperty 'HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem' -Name 'LongPathsEnabled' -Value 1`

## Extra (Optional)
> It is highly recommended that you enable the "Turn off all unnecessary animations (when possible)" option in "Control Panel > Ease of Access > Ease of Access Centre / Make the computer easier to see" for the best performance with komorebi.