# PDQ DEPLOY: Package and deploy WinRAR
### Documentation and download
Download link:

* [WinRAR](https://www.win-rar.com/download.html?&L=0)

Silent switches:
```powershell
/S
```

```powershell
ni "HKLM:\SOFTWARE\Microsoft\Active Setup\Installed Components\runWinRAR" | New-ItemProperty -Name "StubPath" -Value ('REG ADD "HKCU\Software\Microsoft\Windows\CurrentVersion\RunOnce" /v runWinRAR /t REG_SZ /d "{0}\WinRAR\WinRAR.exe"' -f $env:ProgramFiles)
```