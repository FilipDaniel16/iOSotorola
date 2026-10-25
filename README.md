iOSotorola

An experimental open-source research project exploring the possibility of running iOS 16.5 on the Motorola Moto G60.

⚠️ Development status: Early planning. No working iOS port or tested boot image is available yet.

🎯 Project Goals

- Investigate adapting the HackiOS project for the Motorola Moto G60.
- Research custom EFI/UEFI bootloader development.
- Investigate compatibility with the device's hardware.
- Explore display, touchscreen, graphics, and audio support.
- Develop reproducible build and testing procedures.
- Publish verified releases when working software becomes available.

📱 Target Device

Property| Details
Device| Motorola Moto G60
Codename| "hanoip"
Target OS| iOS 16.5
Project type| Experimental OS porting research
Status| Planning and source-code investigation

🔧 Upstream Research

We will investigate these existing projects:

- "HackiOS XNU Kernel" (https://github.com/oosexgang/hackios-xnu-kernel)
- "HackiOS Userland" (https://github.com/oosexgang/hackios-xnu-userland)

Upstream code will be reused only in accordance with its applicable license.

📦 Planned Boot Image

Proposed filename:

"iosotorola-hanoip-boot.img"

This image has not been built or tested yet.

The eventual image must be built from actual source code and tested before being described as bootable.

🔊 Planned Hardware Research

- EFI/UEFI boot support
- CPU and memory initialization
- Display output
- Touchscreen input
- Graphics acceleration
- Speaker and microphone support
- Wi-Fi and Bluetooth
- Power management

These are research goals, not confirmed capabilities.

🛡️ Safety

- Do not flash untested images.
- Maintain a recovery plan before experimenting with the device.
- Verify release checksums and build provenance.
- Do not upload proprietary Apple firmware or extracted iOS system files.
- Document limitations and actual test results honestly.

⚠️ Disclaimer

iOSotorola is an independent experimental project. It is not affiliated with Apple or Motorola.

Compatibility with the Motorola Moto G60 has not been established. Changing a device profile alone cannot make iOS compatible with different hardware.

🤝 Contributions

Contributions to hardware research, documentation, build tooling, and compatibility testing are welcome.

The immediate priority is understanding the existing HackiOS implementation and identifying what would be required for the Moto G60.
