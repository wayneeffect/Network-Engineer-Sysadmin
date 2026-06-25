**Yes — this is a smart, practical project that directly strengthens your network engineering and sysadmin profile.** Living in rural Michigan (Newberry area, 11 miles out) with spotty traditional internet (now improved by Starlink) gives you real-world experience that's highly transferable to the rural Africa setups you're considering. It also ties beautifully into offline LLMs for phones and software engineering.

### Why This Strengthens Your Repertoire
Setting up resilient, hybrid networks in your own challenging rural environment proves you can do it "almost anywhere," as you said. Recruiters and hiring managers value **demonstrable, real-world deployments** like this, especially when they involve:

- **Hybrid backhaul** (Starlink as the internet gateway + local mesh for resilience)
- **Offline-first / delay-tolerant networking**
- **Wireless mesh and peer-to-peer technologies**
- **Low-resource, high-reliability design** (power, coverage, intermittent connectivity)
- **Integration with modern tools** like offline LLMs

This project showcases **practical NetDevOps/sysadmin skills** in constrained environments — exactly what stands out for infrastructure, rural connectivity, disaster-resilient, or international development roles.

### Serval Mesh vs. Briar in Your Context
- **Serval Mesh (Batphone)**: Interesting concept for voice/SMS/file sharing over Wi-Fi mesh, but as of 2026 it is largely **experimental and inactive**. The Android app is old, requires sideloading, and major development has slowed. It may still work for testing but isn't the most reliable choice for production use.
- **Briar**: Much stronger current option. It's actively maintained (latest release in 2026), open-source, end-to-end encrypted, and designed for offline scenarios. It syncs via Bluetooth, Wi-Fi, or memory cards (and Tor when online). Great for secure messaging in areas with poor connectivity. Many people use it successfully for rural/off-grid or emergency comms.

**Recommendation for your area**: Start with **Briar** for local offline messaging. Combine it with Starlink as the occasional backhaul. For longer-range or more robust mesh, look at modern alternatives like **Meshtastic** (LoRa-based, excellent range with cheap hardware) alongside Briar.

### Offline LLMs Integration (Phones + Software Engineering)
This is a fantastic extension. In 2026, running offline LLMs on Android phones is very feasible:
- Apps like **MLC Chat**, **PocketPal AI**, or **MNN Chat** let you run quantized models (e.g., Llama 3.2 1B/3B, Gemma 2B/3B, Phi-3 Mini).
- These work great for coding assistance, chat, reasoning, or even local knowledge bases — perfect for rural software engineering or community use where internet is unreliable.
- You could host a small local server (e.g., on a Raspberry Pi or old hardware) that serves models to phones over the mesh/Wi-Fi when Starlink is slow or down.

**Your setup could become**: Starlink → local router/mesh → phones running Briar + offline LLMs. This creates a resilient "village-scale" lab right in Newberry.

### Practical Next Steps for Your Michigan Setup
1. **Test Briar** with neighbors/family for local offline messaging.
2. **Improve your local Wi-Fi coverage** with a good mesh system (e.g., wired backhaul where possible) fed by Starlink.
3. **Add mesh hardware**: Cheap Wi-Fi routers in bridge/mesh mode, or LoRa devices for longer range.
4. **Document everything**: Diagrams, configs, performance notes, photos, and lessons learned. Put it on GitHub. This becomes strong portfolio evidence.
5. **Expand to Africa pilot**: The rural Michigan experience (distance, weather, power considerations, Starlink integration) is directly analogous and gives you credibility.

This kind of hands-on, innovative project — especially combined with your decade of engineering experience, GitHub, automation skills, and AI prototyping ability — makes you very competitive for **NetDevOps**, **Infrastructure**, **Rural Connectivity**, or **Resilient Networks** roles.

Would you like:
- Specific technical recommendations for hardware/software setup in your Newberry location?
- Resume bullets or project description help?
- Suggestions for modern mesh alternatives to Serval?
- Guidance on running offline LLMs locally?

Happy to dive deeper!
