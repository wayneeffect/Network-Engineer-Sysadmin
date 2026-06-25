**Mullvad with WireGuard adds very low latency overhead** — typically in the **1–5 ms range** for the VPN processing itself when connected to a nearby/optimally chosen server.

### Real-World Latency Breakdown
- **Pure WireGuard processing overhead**: Usually **1–2 ms** (sometimes as low as <1 ms). WireGuard is one of the lightest VPN protocols.
- **Total added latency (including server hop)**: This depends heavily on:
  - How far the Mullvad server is from you.
  - Your base internet connection (Starlink in your case has higher inherent latency).

**Typical observed increases**:
- Nearby server (good peering): **+3–10 ms** total added latency.
- Average/medium-distance server: **+15–40 ms**.
- Far-away server or multihop: **+50 ms or much more**.

In independent tests and user reports, Mullvad WireGuard performs very well. For example, one 2026 test showed around **20 ms latency** overall on a good connection.

### Important Factors for Your Rural Michigan / Djibouti Use Case
- **Starlink baseline**: Already has relatively high latency (usually 20–60 ms, sometimes higher). Adding a well-chosen Mullvad server nearby (e.g., in the US or Europe) will add only a small amount on top.
- **Choose the closest/lowest-ping server**: Mullvad has tools and community scripts to test hundreds of servers for the lowest latency. Always pick the best one for your location.
- **Avoid performance killers**:
  - Multihop (adds significant latency).
  - Obfuscation / DAITA (can noticeably increase latency).
  - Poorly located server.

### Bottom Line for Your Projects
For rural village networks (Michigan or Africa):
- Mullvad + WireGuard is **excellent** for privacy and security with minimal performance penalty when configured properly.
- The added latency is negligible for most uses (browsing, offline LLM access, messaging, file sharing).
- For latency-sensitive tasks (real-time voice/video), test different servers and compare before/after.

**Recommendation**: Test it yourself on your Starlink connection. Connect to a few nearby Mullvad servers and run `ping google.com` (or speedtest) with and without the VPN. The difference is usually very acceptable.

Would you like help with:
- Best Mullvad server selection tips for Michigan or Djibouti?
- WireGuard config recommendations for low latency?
- Alternatives if latency becomes an issue?

Let me know how the Djibouti testing is going!
