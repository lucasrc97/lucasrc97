# Lucas Rodrigues

**Software Developer · .NET · React · Rust**

I build web APIs, desktop apps and Windows tools. I enjoy work that sits close to the system: Bluetooth protocols, Win32 and audio APIs, and the apps people use on top of them.

🇧🇷 Portuguese (native) · 🇺🇸 English

## Tech stack

**Languages**
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AutoHotkey](https://img.shields.io/badge/AutoHotkey-334455?style=flat-square&logo=autohotkey&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Backend**
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

**Desktop & systems**
![egui](https://img.shields.io/badge/egui-000000?style=flat-square&logo=rust&logoColor=white)
![Win32 API](https://img.shields.io/badge/Win32_API-0078D4?style=flat-square)
![Bluetooth](https://img.shields.io/badge/Bluetooth_RFCOMM-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![Windows Core Audio](https://img.shields.io/badge/Windows_Core_Audio-0078D4?style=flat-square)

**Testing & DevOps**
![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Azure Pipelines](https://img.shields.io/badge/Azure_Pipelines-0078D7?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=vscodium&logoColor=white)

## Featured projects

### [ugreenapp-windows](https://github.com/lucasrc97/ugreenapp-windows) · Rust

Desktop app and command line to control UGREEN HiTune Max5c earbuds from a PC instead of the phone app: noise cancelling, equalizer, voice prompts and more. My fork brings an existing Linux CLI to Windows and adds the GUI.

- Windows Bluetooth RFCOMM transport with paired-device discovery and an SDP fallback, using `windows-sys`
- Desktop GUI in egui with light and dark themes, saved settings and a debug console
- Cargo workspace split into core, CLI and GUI crates, with 80 unit and golden tests, including tests replayed from real device captures
- Tested on real hardware, shipped as portable Windows executables on the Releases page

### [DevTask-Manager](https://github.com/lucasrc97/DevTask-Manager) · C# · JavaScript

Full-stack task manager with authentication.

- REST API in ASP.NET Core 8 with JWT authentication and Swagger docs
- Entity Framework Core with SQLite and migrations
- React 18 + Vite frontend with protected routes and an Axios client that attaches the token and handles expired sessions
- Integration tests with xUnit and `WebApplicationFactory`
- Azure DevOps pipeline that builds, tests and publishes artifacts on every push and pull request

### [autohotkey-scripts](https://github.com/lucasrc97/autohotkey-scripts) · AutoHotkey v2

Windows productivity tools.

- **Audio**: a volume mixer with per-app volume and mute, microphone mute and global hotkeys, built directly on the Windows Core Audio COM API, with light and dark themes
