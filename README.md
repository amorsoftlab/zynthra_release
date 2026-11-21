# Zyntra Releases

Official compiled release binaries for **Zyntra Vault** (Android APK and Windows Installer).

Download the latest installers from the [Releases](https://github.com/amorsoftlab/zynthra_release/releases) page or directly below.

---

## 📱 Latest Release: v1.0.2

- **File**: [`zyntra-v1.0.2-release.apk`](zyntra-v1.0.2-release.apk)
- **Target**: Android (ARM64, ARMv7, x86_64)
- **Min SDK**: Android 5.0 (API 21)
- **Signing**: Official Zyntra Release Keystore Signed

### 🚀 What's New in v1.0.2:
- **Card Image Scanner (OCR)**:
  - Take a photo with camera or pick from gallery to instantly extract and auto-fill card numbers, expiry dates, and cardholder names.
  - Interactive realistic card preview with metallic chip, contactless badge, and network gradient.
- **Real-Time Card Network Detection**:
  - Automatically identifies RuPay, Visa, Mastercard, American Express, and Discover as you type digits.
  - Comprehensive RuPay NPCI BIN coverage (60, 65, 81, 82, 508, 353, 356) for major Indian banks (SBI, Federal, HDFC, Canara, KGB, etc.).
  - Dynamic `CardNetworkBadge` and auto-selected network chips.
  - Auto-spacing 4-digit card number formatter (`XXXX XXXX XXXX XXXX`).
- **Indian Banks Catalog & IFSC Finder**:
  - Searchable Indian bank picker modal covering Public, Private, Regional Rural, and Small Finance banks.
  - Multi-criteria IFSC search by District, Branch, and Bank code with quick search chips.
- **Direct Cards Vault Access**:
  - Added "Cards" category option to the Vault Category Picker App Drawer.
- **Bank Account Form Cleanup**:
  - Streamlined to core essential fields (Bank Name, Holder Name, Account Number, IFSC with Finder, Account Type, and Notes).

---

## 📦 Previous Releases:

- **v1.0.1**: [`zyntra-v1.0.1-release.apk`](zyntra-v1.0.1-release.apk) — Redesigned Vault Category picker, full-width To-Do cards, Master PIN & Biometric cloud synchronization.
