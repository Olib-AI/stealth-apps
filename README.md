# StealthApp Registry

Official app registry for [StealthOS](https://stealthos.app).

## What is this?

This repository hosts verified apps for the StealthApp Store built into StealthOS. Apps listed here are reviewed, signed, and available for installation directly from the store.

## Available Apps

| App | Description |
|-----|-------------|
| Torrent | BitTorrent client with SHA-1 verification and malware scanning. **Disclaimer:** BitTorrent is a peer-to-peer file transfer protocol designed for legitimate content distribution. This app must not be used for any illegal purposes, including the downloading or sharing of copyrighted material without authorization. Users are solely responsible for ensuring compliance with applicable laws. |

## For Developers

Want to build an app for StealthOS? See the developer documentation included with the StealthOS source.

## Security

Every app in this registry is:

- Cryptographically signed
- Hash verified before installation
- Scanned for malicious code
- Sandboxed at runtime with permission controls
- Network isolated through privacy routing

Apps cannot access data from other apps or bypass the network configuration set by the user.

## License

All apps in this repository are distributed under their respective licenses. The registry infrastructure is maintained by [Olib AI](https://www.olib.ai).
