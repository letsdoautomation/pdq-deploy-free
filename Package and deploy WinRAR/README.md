# PDQ DEPLOY FREE: Package and deploy WinRAR
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

### My enviroment setup
<b>PDQ setup:</b> <br />

[PDQ Deploy Free: Install and Setup](https://youtu.be/jB6SOhKFoHg) <br />

<b>My windows server setup:</b> <br />

[Windows Server 2022: Install File Server role and prepare a share for software deployment with GPO](https://youtu.be/jEWSdC2qwyA) <br />
[Windows Server 2022: Install DHCP server](https://youtu.be/8n0MD9stQis) <br />
[Windows Server 2022: Install Active Directory Domain Services (AD DS)](https://youtu.be/1cYewbW3Tl0) <br />