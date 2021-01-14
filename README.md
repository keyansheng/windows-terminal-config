# Install (PowerShell)

```powershell
# Windows Terminal
Set-Location $ENV:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

# Windows Terminal Preview
Set-Location $ENV:LOCALAPPDATA\Packages\Microsoft.WindowsTerminalPreview_8wekyb3d8bbwe\LocalState

# Windows Terminal (Unpackaged)
Set-Location "$ENV:LOCALAPPDATA\Microsoft\Windows Terminal"

Remove-Item * -Recurse -Force
git clone https://github.com/keyansheng/windows-terminal-settings .
```

# Update (PowerShell)

```powershell
# Windows Terminal
Set-Location $ENV:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

# Windows Terminal Preview
Set-Location $ENV:LOCALAPPDATA\Packages\Microsoft.WindowsTerminalPreview_8wekyb3d8bbwe\LocalState

# Windows Terminal (Unpackaged)
Set-Location "$ENV:LOCALAPPDATA\Microsoft\Windows Terminal"

git pull
```
