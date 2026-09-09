# Dal

**Systems & Network Infrastructure Engineer**  
Specializing in Low-Latency Protocols, User-Space Networking, and Distributed Proxy Architectures.

---

### 🔬 Core Engineering Domains

- **Transport & Proxy Protocols:** In-depth implementation and tuning of VLESS, Reality (TLS 1.3 Camouflage), WireGuard, Cloudflare WARP, and multiplexed tunnels.
- **Network Stack & Kernel Interfaces:** Virtual network device management (`TUN/TAP`), User-space network stacks (`gVisor netstack`), Packet routing, and NAT configuration.
- **Low-Latency Systems Design:** Engineering application-layer protocols over persistent full-duplex WebSockets (sub-5ms execution latency) with strict access-control tiers.
- **Client-to-Core Integration:** Orchestrating background network processes (`sing-box core`), IPC via local loopback sockets, and cross-platform native hooks (`Android VpnService`).
- **Linux Systems & Reliability:** Kernel parameter optimization (`sysctl`), TCP Congestion Control tuning, MTU path discovery, resource containment (cgroups/OOM mitigation), and CI/CD cross-compilation.

---

### 🛠 Technical Specifications

| Layer / Domain | Technologies & Standards |
| :--- | :--- |
| **Networking & Protocols** | VLESS, Reality, sing-box, Xray-core, WireGuard (RFC 8439), gVisor `netstack`, WebSocket, TCP/UDP tuning, MTU path debugging, `iperf3` |
| **Systems & Linux** | Ubuntu, Linux Kernel (`sysctl`, routing tables, `iptables`/`nftables`, NAT), `systemd`, Process lifecycle management, Memory profiling |
| **Languages & Runtimes** | Python (Asyncio, Socket programming), Go / Dart (Flutter native channels), Shell / Bash |
| **Cross-Platform & Client** | Android `VpnService`, Desktop Tray/Daemon integration, Native build toolchains, Local IPC (`gRPC`, Unix Domain Sockets / Loopback) |
| **Automation & CI/CD** | GitHub Actions (multi-platform native cross-compilation), Docker, Agentic tool execution protocols |

---

### ⚡ Featured Implementations

#### [REX — Remote EXecution Protocol](https://github.com/dalroot/rex)
> Ultra-fast, zero-overhead agent-to-server infrastructure control protocol.
- Engineered as an application-layer protocol running over persistent WebSockets, eliminating the latency and memory overhead of pseudo-terminal (PTY/TTY) emulation.
- Achieves sub-5ms deterministic command execution latency with an integrated 3-tier cryptographic privilege validation model.

#### [Hawal (هه‌واڵ)](https://github.com/dalroot/hawal)
> Zero-dependency tunnel management panel & high-throughput multiplexing core.
- Architected for resilient, censorship-resistant networking with native connection pooling and multiplexing.
- Implemented with zero external dependencies to ensure minimal attack surface and deterministic runtime performance on minimal VPS footprints.

#### [Roozaneh Client & Core Platform](https://github.com/dalroot/roozaneh-app)
> Cross-platform, high-throughput network tunnel client.
- Orchestrates headless `sing-box` cores through local loopback interfaces with automated lifecycle monitoring and error recovery.
- Implements direct Android `VpnService` integration for transparent Layer 3 full-system TUN routing without root privileges.
- Resolves upstream race conditions across local gRPC IPC channels and network state transitions.

#### [Antigravity Cleaner](https://github.com/tawroot/antigravity-cleaner)
> Multi-platform environment recovery & state sanitation utility for developer runtimes (115+ GitHub Stars).
- Cross-platform automation (PowerShell/Bash) for cleaning orphaned state, managing browser/IDE session databases, and automated environment resets.

#### [Agentic SEO Architecture](https://github.com/dalroot/agentic-seo)
> Modular multi-agent automation ecosystem for large-scale technical workflows.
- Contains 16 operational sub-skills, 10 deterministic agent personas, 89 execution scripts, and 160+ structured tool-calling specifications.
