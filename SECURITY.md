# Security Policy

## Official Distribution Channels

KVitals is distributed through the following **official channels**:

### 1. **KDE Store** (Recommended)
- **URL**: https://www.pling.com/p/2347917/
- **Installation**: Via KDE Plasma widget installer (Right-click panel → Add Widgets → Download New Plasma Widgets)
- **Verification**: Installed directly from the official KDE Plasma store

### 2. **GitHub Releases**
- **URL**: https://github.com/yassine20011/kvitals/releases
- **Installation**: `curl` or `wget` scripts from official releases
- **Verification**: Source code available for review at https://github.com/yassine20011/kvitals

### 3. **Git Clone** (Source)
- **Repository**: https://github.com/yassine20011/kvitals.git
- **Installation**: `bash install.sh` from cloned repository
- **Verification**: Full source code transparency; review commits and tags

## Community-Maintained Packages

### **AUR**
- **Package**: `plasma6-applets-kvitals-git`
- **Status**: Community-maintained package, not officially maintained by the KVitals project.
- **Verification**: Check the AUR package maintainer; review PKGBUILD for any modifications

## What to Avoid

⚠️ **Avoid installing KVitals from**:
- Unofficial forks or repackaged versions not listed above
- Third-party websites or app stores not listed above
- Modified or patched versions from unknown sources

If you encounter a suspicious KVitals package or fork, please report it to me via GitHub.

## Reporting Security Vulnerabilities

If you discover a security vulnerability in KVitals, **do not** open a public GitHub issue. Instead:

### Recommended: GitHub Security Advisory
1. Go to https://github.com/yassine20011/kvitals/security/advisories
2. Click **Report a vulnerability**
3. Provide details about the vulnerability

This allows for responsible disclosure and coordinated patching before public disclosure.

### Alternative: Direct Contact
For sensitive issues, use the email fallback below rather than a public GitHub comment or issue.

### What to Include
- Clear description of the vulnerability
- Steps to reproduce (if applicable)
- Potential impact or severity
- Suggested fix (if you have one)

**Please allow reasonable time for investigation and coordinated disclosure before public disclosure.**

## Code Verification

KVitals is written in **QML** (Qt Markup Language) and distributed as open source without bundled compiled binaries. To verify authenticity:

1. Clone the official repository:
```bash
   git clone https://github.com/yassine20011/kvitals.git
```

2. Review the source code:
   - All widget logic is in `contents/ui/` (human-readable QML)
   - Configuration is in `contents/config/`
   - No obfuscated or minified code

3. Install from your reviewed source:
```bash
   bash install.sh
```

## Questions or Concerns?

For security-related questions or concerns, please use the GitHub Security Advisory flow first. If you need a direct fallback, contact me by email at [Yassine.amjad001@gmail.com](mailto:Yassine.amjad001@gmail.com).