# Valkyrie10

> **Windows 10, but it's yours.**

Valkyrie10 is a customized version of Windows 10 that removes unnecessary components, background services, and telemetry. It offers a faster and more private Windows experience.

Engineered for performance, optimized for gaming, and designed for users who want full control over Windows.
[![Discord](https://img.shields.io/badge/DISCORD-JOIN%20COMMUNITY-5865F2?logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/pEpzsstsR)
<img width="1360" height="768" alt="Windows 10 x64-2026-08-03-20-46-20" src="https://github.com/user-attachments/assets/9399615e-460c-466f-8cec-b8c8f1cbf497" />
<img width="1360" height="768" alt="Windows 10 x64-2026-08-03-20-46-37" src="https://github.com/user-attachments/assets/e459f37f-2340-46ef-a9d6-0fea3e38b57e" />
<img width="1360" height="768" alt="Windows 10 x64-2026-08-03-20-47-00" src="https://github.com/user-attachments/assets/ea82c565-4cde-418e-86ad-824b4c7fbc91" />
<img width="1360" height="768" alt="Windows 10 x64-2026-08-03-20-50-41" src="https://github.com/user-attachments/assets/4ee507db-488d-48a2-ab8c-019ae020fe4f" />


## Features

- Microsoft Edge removed
- Aggressive system debloating
- Most Windows telemetry removed or disabled
- Reduced background services and scheduled tasks
- Lower RAM and CPU usage
- Faster boot and improved responsiveness
- Xbox services retained for gaming

## To install a browser
   
*To install a browser either load a USB with .EXE file or use winget

*To install winget use 
```(Invoke-WebRequest https://raw.githubusercontent.com/asheroto/winget-installer/master/winget-install.ps1 -UseBasicParsing | iex)```

*For brave with winget use 
```(winget install --id Brave.Brave -e)```

# What is disabled?

- Windows Defender

*You are responsible for securing your own system.*

- Windows Update
- Microsoft Edge
- Unnecessary services and telemetry  

# Current Status

> ⚠️ **Alpha Release**

Valkyrie10 is currently in **Alpha**.

It is under active development and should be considered experimental. Bugs, missing components, and unexpected behavior is expected.

Do **not** install this on a machine you depend on for work, school, or important data unless you test it and experience good results.

# Known Issues

### Some language packs are unavailable

 A small number of language packs were accidentally removed during development.

 Most common languages are unaffected, but some optional language packs may not install.

 *Will be fixed in Valkyrie v1.1*
# FAQ

### Does Windows Update work?

❌ No.

Windows Update has been intentionally disabled.

### Does Microsoft Defender work?

❌ No.

Defender has been intentionally disabled.

### Can removed components be restored?

Generally no.

This build is designed to remain lightweight and fast rather than support restoring removed Windows features.


# Disclaimer

⚠️ **Use Valkyrie10 entirely at your own risk.**

This project is an experimental modification of Microsoft Windows.

The developers are **not responsible** for:

- Data loss
- System instability
- Software incompatibilities
- Hardware issues
- Corrupted installations
- Any other damage resulting from the use of this build

Always test Valkyrie10 in a virtual machine or on non-critical hardware before daily use.

By installing this operating system, you accept full responsibility for any consequences.

# Reporting Issues

Found a bug?

Please include:

- Hardware specifications
- Screenshots (if applicable)
- Error message
- Logs and Event Viewer (if applicable) 

# Credits:
⭐ Mazen-linux (Vixit)
⭐ Moaaz (MRCX)
⭐ Kaii (For the name Valkyrie)
⭐ Danii (Procrastinating the entire project)

# License

The files in this repository are licensed under the **MIT License**. 

This license applies **only** to the contents of this repository (documentation, scripts, configuration, etc.) and **does not apply to Microsoft Windows**, which remains proprietary software owned by Microsoft.
