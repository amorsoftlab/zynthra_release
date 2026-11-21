# Changelog

All notable changes to the **Zyntra** project will be documented in this file.

## [1.0.2] - 2026-11-21

### Added
- **Card Image Scanner (OCR)**:
  - Take a photo with camera or choose from gallery to auto-fill card details.
  - On-device Google ML Kit text recognition with fallback and sample OCR testing.
  - Interactive realistic card preview (network gradient, metallic chip, contactless icon, eye reveal).
- **Real-Time Card Network Identification**:
  - Automatically identifies RuPay, Visa, Mastercard, American Express, and Discover directly from card digits.
  - Comprehensive RuPay NPCI BIN coverage (60, 65, 81, 82, 508, 353, 356) for major Indian banks (SBI, Federal, HDFC, Canara, Kerala Gramin Bank, etc.).
  - Dynamic `CardNetworkBadge` and auto-selected network chips.
  - Auto-spacing 4-digit card number formatter (`ZyntraCardNumberFormatter`).
- **Indian Banks Catalog & IFSC Finder**:
  - Searchable Indian bank picker modal covering Public, Private, Regional Rural, and Small Finance banks.
  - Multi-criteria IFSC search by District, Branch, and Bank code with quick search chips.
- **Direct Cards Vault Access**:
  - Added "Cards" category option to the Vault Category Picker App Drawer.

### Changed
- **Bank Account Form Cleanup**:
  - Removed unnecessary clutter (NetBanking URL, Customer ID, NetBanking Password, App PIN, and Custom Fields builder).
  - Streamlined to core fields: Bank Name, Holder Name, Account Number, IFSC with Finder, Account Type, and Notes.

### Fixed
- Resolved all RenderFlex overflows across viewports down to 320px width.
- Maintained 100% test pass rate across 59 unit and widget tests.

---

## [1.0.1] - 2026-11-21

### Added
- Vault Category Picker Modal redesigned with 3-column app drawer grid.
- Full-width To-Do reminder cards with complete/incomplete status toggling.
- Master PIN & Biometric cloud synchronization.

---

## [1.0.0] - 2026-11-15

### Added
- Initial public release of Zyntra Vault.
- AES-256-GCM encrypted local vault with multi-UID isolation.
- Offline auto-lock, clipboard auto-clearing, and background OS notifications.
