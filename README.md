# Portable ZeroNet Script

## About

A simple tool in Bash that helps you make your ZeroNet Bundle Portable.

## Features

- Device Mounting: Automatically mounts the device that ZeroNet Bundle is on.
- LUKS Encryption Support: Supports LUKS encrypted devices.
- Tor Connectivity Check: Checks if your Tor is connected to prevent mistakes and IP leaks.

## How to Use

**Before you start:**
- Make sure you have a Bash-compatible system.
- You'll need permission to run some commands with "sudo".

**Run the Script:**
```bash
./portable_zeronet.sh /path/to/your/device /path/to/zeronet-bundle
```

Replace `/path/to/your/device` with your device and `/path/to/zeronet-bundle` with where you keep ZeroNet. It's good if ZeroNet is on a USB stick.

## License

This script follows the rules of the MIT License. See [LICENSE](LICENSE) for more.
