# Watchpost

[Русский](README.ru.md)

Watchpost brings cameras, video recorders, and the rest of your site infrastructure together in one application. Whether you manage one site or dozens for your clients, the information and tools you need are always within reach.

## Built for each platform

Watchpost is designed for macOS, iPhone and iPad, Windows, Android, and Linux. Each app is built with its platform in mind, using a native interface and platform capabilities so it feels at home on the device you use. Linux is planned; availability and features vary by platform.

## Different manufacturers, one app

Work with equipment from different manufacturers in one place. Watchpost supports Hikvision, Xiongmai, Dahua, ONVIF, and OpenIPC, and the list of compatible equipment continues to grow with each release. Available features depend on the device, protocol, and platform; consult the release notes for current support.

For equipment from each supported manufacturer, Watchpost offers functionality comparable to the manufacturer's own applications.

## Your sites, organized

The device registry is more than a camera list: it brings cameras, recorders, routers, switches, wireless bridges, and UPS units together by site, along with the details you need to reach them.

- Discover cameras, recorders, and other active equipment on the local network.
- Import lists of devices in batches from Excel or CSV.
- Monitor device availability.
- Share site information with clients or colleagues through Watchpost Inbox or another convenient method.

## Remote access with Watchpost Hub

Watchpost Hub is designed to connect sites to the app without exposing device ports or requiring a public IP address at the site. Sites connect outward to the Hub, and Watchpost selects an available route so you can open a camera remotely much as you would on the local network.

There are two options: a Hub on your own VPS, installed from the app, or a ready-to-use Hub operated by Watchpost. With Inbox, you can send a site package to a colleague or client, who can accept it in the app. Hub capabilities and the availability of the hosted service continue to evolve.

**Watchpost is in alpha.** Features may change, and you may encounter errors. We welcome feedback as the app develops.

This repository distributes Watchpost releases and contains no application source code. Visit [watchpost.app](https://watchpost.app/) to learn more about the project.

## Download and install

Open [Releases](https://github.com/dimnik70/watchpost-release/releases) and choose a release for your platform. Alpha releases may be marked as pre-releases; open the release notes to find their downloads. The release notes provide the available files, installation instructions, and any release-specific requirements.

| Platform | Minimum system version | Installation |
| --- | --- | --- |
| macOS | macOS 14 | Download the macOS build and follow the release instructions. |
| Windows | Windows 10, version 2004 (build 19041) | Download the Windows build and follow the release instructions. |
| Android | Android 8 | Download the Android build and follow the release instructions for installing it. |
| iPhone and iPad | iOS 17 or iPadOS 17 | Follow the distribution and installation instructions in the release notes. |
| Linux | To be announced | Planned; release details will be published when available. |

Availability and features may differ between platforms. See the [download page](https://watchpost.app/download/) and [documentation](https://docs.watchpost.app/) for more information.

## Verify a download

Download files from the official release page or the Watchpost website. If a release provides checksums or signature verification instructions, use those published with that release to verify the file before installing it.

## Feedback and support

- Report bugs and suggest improvements in [GitHub Issues](https://github.com/dimnik70/watchpost-release/issues).
- Ask questions and share ideas in [GitHub Discussions](https://github.com/dimnik70/watchpost-release/discussions).

When reporting a problem, include your platform, OS version, Watchpost version, and steps to reproduce it. Please remove passwords and other private information from reports and logs.

## License and terms

Watchpost is proprietary software owned by Dmitrii Nikolaev. This repository does not contain the application source code. All rights are reserved.

You may install and use Watchpost for personal and commercial purposes under the terms of your license. You may charge clients for installing, configuring, and supporting Watchpost. Organizations may keep an unmodified official installer in internal storage and deploy it to their own devices. Installers may also provide an unmodified official installer to a client for installation.

Without permission from the copyright holder, you may not redistribute Watchpost, publish its builds on public mirrors or third-party platforms, include it in another product, or distribute it under another brand. Sharing a link to an official release is welcome.

You may not modify Watchpost, reverse engineer, decompile, or disassemble it, attempt to obtain its source code, or bypass licensing or other protections, except where such restrictions are prohibited by applicable law or overridden by the licenses of included third-party components.

Good-faith security research is welcome within these limits. Please report vulnerabilities privately through [GitHub Security Advisories](https://github.com/dimnik70/watchpost-release/security/advisories), rather than in public issues, and allow time for investigation and a fix before disclosure. Private vulnerability reporting must be enabled for this repository before this channel is available.

Third-party components may be subject to their own licenses. Full license terms and pricing will be added here.
