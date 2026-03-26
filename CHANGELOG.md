# Changelog

All notable changes to ProbeShield are documented here.

Format: `[Version] — Release Date`

---

## [1.0.0] — 2025

### 🎉 Initial Release

**Device Discovery**
- ARP scan to detect all connected devices
- mDNS resolution for device hostnames
- Ping sweep for reachability confirmation
- MAC OUI manufacturer lookup

**Port Scanner**
- TCP scan of top 100 most common ports
- Service banner grabbing
- Per-port open/closed/filtered status

**Risk Scoring**
- Four-tier risk classification: Critical / High / Medium / Safe
- Risk badges on device list
- Detailed risk breakdown per device

**UI**
- Dark navy theme with electric cyan accents
- Device list with risk badges
- Device detail screen with full port breakdown
- Live port feed during active scan
- Scan history (stored locally via Room database)

**Security**
- App lock with PIN support
- Biometric authentication (fingerprint)
- Disclaimer screen on first launch
- All data stored locally — nothing transmitted externally

**Onboarding**
- 3-slide onboarding for new users
- Settings screen
- Feedback screen

---

*Older versions will be listed here as they are released.*
