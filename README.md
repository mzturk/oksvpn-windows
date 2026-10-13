# OKSVPN for Windows

**Fast & secure VPN · Hızlı ve güvenli VPN** — by [oktasoft](https://oktasoft.com/oksvpn)

➡️ **Download / İndir:** [Releases](https://github.com/mzturk/oksvpn-windows/releases/latest) → `OKSVPN-Setup-x.y.z.exe`
(Windows 10 / 11, 64-bit)

This repository only hosts the installer downloads. The source code is private.
Bu depo yalnızca kurulum dosyalarını barındırır; kaynak kod özeldir.

## Install / Kurulum
1. Download `OKSVPN-Setup-x.y.z.exe` from the latest release. / Son sürümden indirin.
2. Optionally verify the SHA-256 checksum (`.sha256` file next to it). / İsterseniz SHA-256 özetini doğrulayın:
   `Get-FileHash .\OKSVPN-Setup-x.y.z.exe -Algorithm SHA256`
3. Windows may show **"Windows protected your PC / unknown publisher"** because early builds are not code-signed yet →
   **More info → Run anyway.** / Windows "bilinmeyen yayıncı" uyarısı gösterebilir (ilk sürümler henüz imzalı değil) →
   **Ek bilgi → Yine de çalıştır.**
4. Setup installs the OKSVPN app, its background service and the official OpenVPN 2.6 components (core + Wintun driver).
   / Kurulum; OKSVPN uygulamasını, arka plan hizmetini ve resmi OpenVPN 2.6 bileşenlerini (çekirdek + Wintun) kurar.

## Support / Destek
- E-mail: destek@oktasoft.com
- Privacy: https://oktasoft.com/oksvpn/privacy · Gizlilik: https://oktasoft.com/oksvpn/gizlilik
- Terms: https://oktasoft.com/oksvpn/terms · Şartlar: https://oktasoft.com/oksvpn/kullanim

## Third-party / Üçüncü taraf
OpenVPN (GPLv2, separate program — source: https://github.com/OpenVPN/openvpn), Wintun, OpenSSL, .NET runtime.
See `third_party_notices.txt` in the installation folder.

© 2026 Mehmet Öztürk (oktasoft) · Muratpaşa / Antalya, Türkiye
