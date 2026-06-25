**For a Raspberry Pi acting as a Wi-Fi server/access point in a rural village setting, the typical real-world range is:**

### Wi-Fi Range (Most Relevant for Your Use Case)
- **Indoor / with walls**: 20–50 meters (65–160 feet) depending on walls, interference, and frequency band.
- **Outdoor / line-of-sight (best case)**: **100–300+ meters** (up to ~1,000 feet) with clear conditions and good placement.

**Key factors affecting range**:
- **2.4 GHz band**: Longer range, better penetration through trees/vegetation, but slower speeds and more interference.
- **5 GHz band**: Faster speeds, shorter range, poorer penetration.
- **Placement**: Elevate the Pi (2–3+ meters high), use clear line-of-sight, and avoid metal enclosures or thick vegetation.
- **Hardware**: Built-in Pi Wi-Fi (especially Pi 4/5) has a PCB antenna with limited power. External USB Wi-Fi adapters with high-gain antennas or dedicated access points significantly improve range.

In practice, a single Raspberry Pi Wi-Fi hotspot is great for a small cluster of homes or a central meeting point in a village, but **not** for covering an entire spread-out rural village on its own.

### User Capacity ("How Many People?")
- **Light usage** (browsing, messaging, offline content): **10–25 concurrent users** is realistic on a Pi 5 (8GB).
- **Heavier usage** (video streaming, many file downloads): Drops to 5–15 users comfortably.
- For offline LLMs, file sharing, or education content (Kiwix/IIAB), it handles small groups well.

### Other "Range" Interpretations
- **Performance range** (workload): Excellent for lightweight-to-moderate services (offline LLMs, file server, mesh gateway, monitoring). Struggles with heavy concurrent video transcoding or large databases.
- **Meshtastic integration** (recommended for your project): LoRa-based nodes give **kilometers** of range (often 5–20+ km line-of-sight per hop with good antennas/solar nodes), which complements the Pi’s short-range Wi-Fi perfectly for village-scale coverage.

### Recommendations for Your Michigan + Djibouti Projects
1. Use the **Raspberry Pi as the central server/gateway** (offline content, LLM, management dashboard).
2. Feed it with **Starlink** for backhaul.
3. Extend local coverage with:
   - Good Wi-Fi mesh routers or access points.
   - **Meshtastic** nodes for long-range, low-bandwidth text/GPS/sensor mesh.
   - Briar on phones for offline messaging.

This hybrid approach gives you strong local Wi-Fi where needed + kilometers of resilient off-grid communication.

Would you like help choosing specific hardware (e.g., high-gain Wi-Fi adapters, outdoor enclosures, or Meshtastic + Pi setups) or tips for maximizing range in wooded/rural areas?
