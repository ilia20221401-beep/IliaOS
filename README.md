🐧 IliaOS

IliaOS is a Debian-based Linux distribution created as an open-source learning and experimentation project.

The goal of IliaOS is to provide a lightweight, customizable, and educational Linux environment while exploring Linux system administration, package management, networking, and operating-system development.

«🚧 Status: Early Development

IliaOS is currently a learning project and is not intended to replace established Linux distributions.»

---

🎯 Goals

- 🐧 Learn how Linux distributions are built
- ⚙️ Customize the Debian base system
- 🖥️ Create a clean and practical desktop environment
- 🌐 Explore Linux networking and system administration
- 📦 Experiment with packages and system configuration
- 🔧 Build and test everything inside virtual machines
- 🌍 Learn and contribute to open-source development

---

🛠️ Current Technology

- Base: Debian
- Build System: live-build
- Architecture: amd64
- Desktop Environment: XFCE
- Virtualization: VirtualBox
- License: MIT

---

📁 Project Structure

IliaOS/
├── config/
│   ├── package-lists/
│   └── includes.chroot/
├── scripts/
│   └── build.sh
├── docs/
│   └── roadmap.md
├── .gitignore
├── LICENSE
└── README.md

---

🚀 Building IliaOS

1. Install the required tools

sudo apt update
sudo apt install live-build debootstrap squashfs-tools xorriso

2. Clone the repository

git clone https://github.com/ilia20221401-beep/IliaOS.git
cd IliaOS

3. Build the ISO

chmod +x scripts/build.sh
./scripts/build.sh

The generated ISO can then be tested safely in a virtual machine such as VirtualBox.

---

🧪 Testing

IliaOS is currently tested in virtual machines.

Recommended:

- VirtualBox
- At least 2 GB RAM
- 20 GB virtual disk
- Internet connection during the build process

---

🗺️ Roadmap

IliaOS 0.1

- [x] Create project repository
- [ ] Configure Debian base
- [ ] Add initial package list
- [ ] Configure XFCE
- [ ] Build first ISO
- [ ] Test boot process
- [ ] Test networking
- [ ] Document installation

Future

- [ ] Custom IliaOS branding
- [ ] Custom welcome screen
- [ ] Better default configuration
- [ ] Automated ISO builds
- [ ] More hardware testing
- [ ] Community contributions
- [ ] First stable release

---

🤝 Contributing

IliaOS is an open-source learning project.

If you want to contribute, you can:

- Report bugs
- Test the ISO
- Improve documentation
- Suggest features
- Submit code improvements

Before making major changes, please open an issue to discuss the idea.

---

⚠️ Disclaimer

IliaOS is experimental software.

Always test development builds inside a virtual machine or on non-critical hardware.

Do not use development builds on systems containing important data.

---

📜 License

IliaOS is released under the MIT License.

See ""LICENSE"" (LICENSE) for details.

---

👨‍💻 Developer

Ilia

Linux enthusiast and creator of IliaOS.

---

⭐ If you find the project interesting, consider giving it a star and following its development.
