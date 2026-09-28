# Changelog

All notable changes to ProbeShield are documented here.

Format: `[Version] — Release Date`

---

## [1.2.0] — 2026-09-28

**Alerts**
- After a scan, optionally turn on daily background monitoring to be notified when a new device joins, your router's identity changes, or a device becomes riskier
- Notification permission is now requested only when monitoring is turned on
- Dashboard shows monitoring status and the last background check

**Router check**
- New "Check your router" card and screen with an immediate check
- Results start with a ranked verdict and a plain-language fix for each issue
- Never reports the router as secure when the default-password test could not run

**Sharing**
- Share a network health card (score, status, device counts) as an image; it omits the network name, IPs and MACs

**Guidance**
- More accurate CVE fix guidance, with a note about vendor backports and a tappable NVD advisory link
- The first-run disclaimer now mentions the weekly public CVE download from NIST's National Vulnerability Database

**Fixes**
- Fixed the release build and corrected ProGuard keep rules
- Optional in-app rating request after a clean second scan

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
