<div align="center">
  <img src="https://media.discordapp.net/attachments/952368183543746570/1415145477841883136/image.png?ex=68c2246e&is=68c0d2ee&hm=9528852b083a11c1a5905407aa71782eb46e657cef73fab6c6f4d6d6fafda3e0&=&format=webp&quality=lossless">
</div>

---

<p align="center">
This project started because I kept reinstalling Windows to fix FPS drops, and I got tired of setting up everything from scratch. So, I made this friendly tool that installs all the software I use every day—games, productivity apps, utilities—automatically. It saves time, avoids mistakes, and gets your system ready to go in minutes, whether you’re a gamer, a multitasker, or just want a clean setup.
</p>

---

<h3>🪼 Installation</h3>
<p>Run this command in Console Prompt (CMD): </p>

```batch
powershell Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; Invoke-WebRequest -Uri "https://github.com/noxx212/Essentials/releases/download/1.1.1/essentials.bat" -OutFile "$env:TEMP\essentials.bat"; Start-Process -FilePath "$env:TEMP\essentials.bat"
```

---

<h3>🪶 Features</h3>

<h4>Presets: </h4>

- Competitive Preset (Installs 7zip, Visual Redists, DirectX, Discord, Spotify and your Game Launchers)
  
- Multitasking Preset (Installs all of them above and vlc and spicetify if you wish to. I will be adding more things in future.)
  
- Custom Installation Mode (Lets you install all of them above and also, Free Download Maneger, Veracrypt, Keepass, VSCode)

<br>

> [!TIP]
> Using the custom installation mode is Highly Recommended to install only the software you need.


---

<p>Thank you for considering using my script. Follow me on <a href=https://x.com/noxxzeraa>X/Twitter</a></p>
