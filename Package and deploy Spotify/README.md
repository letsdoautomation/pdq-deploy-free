# PDQ DEPLOY FREE: Package and deploy Spotify
### Documentation and download
Download link:

* [Spotify](https://www.spotify.com/de-en/download/windows/)
* [Spotify Offline Installer](https://download.scdn.co/SpotifyFullSetup.exe)

Silent switches:
```powershell
/Silent
```

Generate package guid:
```powershell
[guid]::NewGuid().guid
```

WiX build MSI package command:
```powershell
wix build .\Spotify.wxs
```

# Related videos

<b>WiX Toolset 4 CLI</b>

[Windows Tools: Download and install .NET 7 SDK and WiXtoolset 4 CLI tool](https://youtu.be/ukrIlmadTjw) <br />
[Group Policy: Packaging EXE into MSI for Group Policy software deployment using WiX toolset CLI](https://youtu.be/pZ42XS2Ucsg) 

<b>Windows registry</b>

[Windows Registry: Run and RunOnce](https://youtu.be/zgFzCq5uEPw) <br />
[Windows Registry: Active Setup](https://youtu.be/HrVJ7wdvfmo) <br />

<b>My windows server setup</b>

[Windows Server 2022: Install File Server role and prepare a share for software deployment with GPO](https://youtu.be/jEWSdC2qwyA) <br />
[Windows Server 2022: Install DHCP server](https://youtu.be/8n0MD9stQis) <br />
[Windows Server 2022: Install Active Directory Domain Services (AD DS)](https://youtu.be/1cYewbW3Tl0) <br />