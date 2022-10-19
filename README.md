# Cockpit Keyboard ZMK Configuration
## To build Firmware in GitHub Actions

### Setup

- Fork this repo.
- Enable GitHub Actions on your fork.

### Build firmware

- Push a commit to trigger the build.
- [Download](https://github.com/ozkan/Cockpit-ZMK-config/actions) the artifact. 

## Flash firmware
- Press RESET twice within 500ms.   
  The blue led will start slowly dimming and a Mass Storage should appear in your file explorer.
- Now you can copy the ZMK UF2 firmware file on it. After copying the UF2 (cockpit-nice_nano_v2-zmk.uf2 ) file to the Mass Storage, the nice!nano will automatically reboot and load the new firmware. 

---
[Cockpit Keyboard](https://github.com/ozkan/Cockpit-Keyboard)
