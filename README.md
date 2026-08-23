<p align="center">
  <img
    src="https://tinyshield.proxyman.com/assets/images/tiny_shield_icon_v1.png"
    width="96"
    alt="Tiny Shield app icon"
  />
</p>

<h1 align="center">Tiny Shield</h1>

<p align="center">
  <strong>See every connection. Control what gets online.</strong>
</p>

<p align="center">
  A native network monitor and firewall for macOS.
</p>

<p align="center">
  <a href="https://api-tinyshield.proxyman.com/api/releases/download/tinyshield.dmg">Download</a>
  ·
  <a href="https://tinyshield.proxyman.com">Website</a>
  ·
  <a href="https://tinyshield.proxyman.com/docs/">Documentation</a>
  ·
  <a href="https://github.com/ProxymanApp/Tiny-Shield/issues/new">Report an issue</a>
</p>

<p align="center">
  <img
    src="https://img.shields.io/badge/macOS-15%2B-111827?style=flat-square&logo=apple&logoColor=white"
    alt="Requires macOS 15 or later"
  />
  <img
    src="https://img.shields.io/badge/Apple_silicon-supported-7FE055?style=flat-square"
    alt="Supports Apple silicon"
  />
  <img
    src="https://img.shields.io/badge/Intel-supported-7FE055?style=flat-square"
    alt="Supports Intel Macs"
  />
</p>

<p align="center">
  <a href="https://tinyshield.proxyman.com/assets/videos/tinyshield-homepage-hero.mp4">
    <img
      src="https://tinyshield.proxyman.com/assets/images/tinyshield-homepage-hero-poster.jpg"
      width="920"
      alt="Tiny Shield monitoring network connections from Mac apps"
    />
  </a>
</p>

<p align="center">
  <sub>Click the preview to watch Tiny Shield in action.</sub>
</p>

> [!NOTE]
> This repository is the public issue tracker for Tiny Shield. Tiny Shield is
> closed source. The app source code and private packages are not published
> here.

## About Tiny Shield

Tiny Shield shows which apps and macOS services use your network. It helps you
understand each connection and decide what should be allowed or blocked.

- See apps, domains, IP addresses, ports, and destination countries.
- Block one app or only one destination.
- Approve a new app before it connects.
- View remote connections on a world map.
- Keep monitored connection data on your Mac.
- Use a native app built on Apple's Network Extension framework.

## Features

### 1. Monitor every connection

- See which app or macOS service opened a connection.
- Check whether traffic is active, allowed, or blocked.
- Search by app, domain, or IP address.
- Keep the connection history on your Mac.

<p align="center">
  <img
    src="https://tinyshield.proxyman.com/assets/images/tinyshield_demo.webp"
    width="820"
    alt="Tiny Shield network connection list"
  />
</p>

[Read the network monitoring documentation](https://tinyshield.proxyman.com/docs/features/monitor-network)

### 2. Read domains instead of guessing from IP addresses

- See readable hostnames under the app that contacted them.
- Find the service behind a connection faster.
- See domains used by Chrome and Firefox, including DNS over HTTPS traffic.

<p align="center">
  <img
    src="https://tinyshield.proxyman.com/assets/images/tinyshield_show_hostname.jpeg"
    width="520"
    alt="Tiny Shield showing domains contacted by Spotify"
  />
</p>

### 3. Block apps and destinations

- Block all network access from one app.
- Block one domain, wildcard domain, or IP address.
- Keep the rest of the app online when you use a narrow rule.
- Review every rule in one Block List.

<p align="center">
  <a href="https://tinyshield.proxyman.com/assets/videos/tinyshield_demo_blockList.mp4">
    <img
      src="https://tinyshield.proxyman.com/assets/images/tinyshield_demo_blockList.jpeg"
      width="760"
      alt="Blocking an app with Tiny Shield"
    />
  </a>
</p>

<p align="center">
  <sub>Click the preview to watch the Block List demo.</sub>
</p>

[Read the blocking documentation](https://tinyshield.proxyman.com/docs/features/block-apps-and-domains)

### 4. Choose how connections are handled

- **Allow All** lets normal traffic continue while the Block List stays active.
- **Block All** stops connections unless an Allow List rule permits them.
- Switch modes from the main Tiny Shield window.
- Use the right level of control for normal work, testing, or lockdown.

<p align="center">
  <a href="https://tinyshield.proxyman.com/assets/videos/tinyshield-connection-modes-demo.mp4">
    <img
      src="https://tinyshield.proxyman.com/assets/images/tinyshield-connection-modes-poster.jpg"
      width="760"
      alt="Tiny Shield connection modes"
    />
  </a>
</p>

<p align="center">
  <sub>Click the preview to watch the connection modes demo.</sub>
</p>

[Allow All documentation](https://tinyshield.proxyman.com/docs/features/allow-all-mode)
·
[Block All documentation](https://tinyshield.proxyman.com/docs/features/block-all-mode)

### 5. Require Approval

- Pause a connection from a new app before it continues.
- Review the app, signature, domains, IP addresses, countries, and ports.
- Allow or block the app once.
- Let Tiny Shield remember your choice for the next connection.

<p align="center">
  <a href="https://tinyshield.proxyman.com/assets/videos/tinyshield-require-approval.mp4">
    <img
      src="https://tinyshield.proxyman.com/assets/images/tinyshield-require-approval-poster.jpg"
      width="620"
      alt="Tiny Shield asking for approval before an app connects"
    />
  </a>
</p>

<p align="center">
  <sub>Click the preview to watch the Require Approval demo.</sub>
</p>

[Read the Require Approval documentation](https://tinyshield.proxyman.com/docs/features/require-approval)

### 6. See destinations on the GeoIP map

- See the approximate country or region behind a remote connection.
- View destinations for one app, domain, or IP address.
- Spot connections to places you do not expect.
- Match map locations with the connection list.

<p align="center">
  <a href="https://tinyshield.proxyman.com/assets/videos/tinyshield-geoip.mp4">
    <img
      src="https://tinyshield.proxyman.com/assets/images/tinyshield-geoip-poster.jpg"
      width="820"
      alt="Tiny Shield GeoIP map showing network destinations"
    />
  </a>
</p>

<p align="center">
  <sub>Click the preview to watch the GeoIP map demo.</sub>
</p>

[Read the GeoIP map documentation](https://tinyshield.proxyman.com/docs/features/geoip-map)

### 7. Native Network Extension

- Uses Apple's supported Network Extension framework.
- Monitors incoming and outgoing TCP and UDP connections.
- Applies Allow List, Block List, and mode decisions as traffic starts.
- Runs efficiently in the background.
- Keeps network processing and monitored data on your Mac.

<p align="center">
  <img
    src="https://tinyshield.proxyman.com/assets/images/tiny_shield_network_extension.jpeg"
    width="760"
    alt="Tiny Shield enabled in macOS Network Extensions"
  />
</p>

[Read the Network Extension documentation](https://tinyshield.proxyman.com/docs/features/network-extension)

## Supported Macs

- macOS 15 or later.
- Apple silicon Macs.
- Intel Macs.

Tiny Shield is a macOS app. Windows and Linux are not supported.

## Download

<p align="center">
  <a href="https://api-tinyshield.proxyman.com/api/releases/download/tinyshield.dmg">
    <img
      src="https://img.shields.io/badge/Download_Tiny_Shield-for_macOS-7FE055?style=for-the-badge&logo=apple&logoColor=black"
      alt="Download Tiny Shield for macOS"
    />
  </a>
</p>

More links:

- [Tiny Shield website](https://tinyshield.proxyman.com)
- [Pricing](https://tinyshield.proxyman.com/pricing)
- [Documentation](https://tinyshield.proxyman.com/docs/)
- [Release notes](https://github.com/ProxymanApp/Tiny-Shield/releases)

## Support and feedback

- **Public bug report or feature request:**
  [Open a GitHub issue](https://github.com/ProxymanApp/Tiny-Shield/issues/new)
- **Private or license question:**
  [tinyshield@proxyman.com](mailto:tinyshield@proxyman.com)
- **Help and troubleshooting:**
  [Tiny Shield Support](https://tinyshield.proxyman.com/docs/support)

When reporting a problem, include your macOS version, Tiny Shield version, Mac
model, selected connection mode, and clear steps to reproduce it.

Do not post a license key, private hostname, IP address, or other sensitive
network data in a public issue.

---

<p align="center">
  Built by <a href="https://proxyman.com">Proxyman</a>.
</p>
