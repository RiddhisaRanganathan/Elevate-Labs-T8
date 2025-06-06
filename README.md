# Elevate-Labs-T8

### 1. Change in Internet Speed
- Internet speed was tested before and after using ProtonVPN.
- While connected to the VPN, there was a slight reduction in speed, due to encryption overhead and routing through remote servers.
- Disconnecting the VPN led to improved speeds, confirming VPN impact on performance.

### 2. VPN Encryption and Privacy Features
- **ProtonVPN** uses modern secure protocols like **WireGuard** and **OpenVPN**.
- Encryption standards include **AES-256** and **ChaCha20** to protect data in transit.
- Verified using **Wireshark**: packets sent to `duckduckgo.com` on port `443` were encrypted (TLS protocol), confirming secure tunneling.
- ProtonVPN also offers:
  - **No-logs policy**
  - **DNS leak protection**
  - **Secure Core routing** for extra privacy

### 3. VPN Benefits and Limitations

#### Benefits
- Masks **real IP address** and **location**
- **Encrypts all internet traffic**, even on public Wi-Fi
- Bypasses **geo-restrictions** and censorship
- Protects privacy from **ISPs and third parties**

#### Limitations
- May **slow down internet speed**
- **Free plans** have limited servers and features
- **Does not block malware** or phishing sites
- Requires **trust in VPN provider** (if no-logs policy is weak)
