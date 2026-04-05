# nexus

A browser-native operating system, transaction protocol, self-modifying AI runtime, and cognitive research methodology. Each ships as a single HTML file with zero dependencies.

---

🔧 **[Kernel](/kernel)** — Iframe process isolation, capability-gated IPC, cryptographic boot handshake. A microkernel that runs in a browser tab.

💰 **[Wallet](/wallet)** — UTXO model, ECDSA-P256 signing, escrow primitives, dual transport with failover. Runs standalone or as a kernel block.

🧬 **[Phase 5](/phase5)** — Self-modifying quine with AI evolution engine, generational lineage, and self-healing persistence. **Experimental.**

🧠 **[Council](/council)** — Multi-instance adversarial cognitive architecture. Three AI instances, three different cognitive configurations, findings no single instance can reach. Usable today with any LLM.

---

## What connects these

Every artifact is a self-contained file that governs the behavior of whatever opens it — by defining constraints at a boundary and letting correct behavior emerge rather than specifying it directly. The kernel constrains how applications communicate. The wallet constrains how value transfers. The quine constrains how it evolves. The Council constrains how AI instances process a problem.

Read the **[case study](CASE_STUDY.md)** for how a solo developer with no CS background built all of this using AI as a co-developer over two years.

## Getting started

Each artifact is a single HTML file. Open it in a browser. That's it.

| Artifact | File | What happens when you open it |
|----------|------|-------------------------------|
| Kernel | `kernel/nexus-os.html` | A desktop environment boots. Blocks can register and communicate through the kernel. |
| Wallet | `wallet/wallet-v4.html` | A UTXO wallet initializes. Create keypairs, construct transactions, sign and verify. |
| Phase 5 | `phase5/nexus-phase5.html` | A full AI chat environment with self-modification, evolution, and quine export. |
| Council | `council/QUICKSTART.md` | Open 3 browser tabs with any LLM. Paste the prompts. Send your question. |

## Status

This is the first public release. The code works. The documentation is minimal. There are no tests. These are working prototypes and research artifacts, not production software. Contributions, questions, and adversarial review are welcome.

## License

Code (`/kernel`, `/wallet`, `/phase5`): [MPL-2.0](licenses/MPL-2.0.txt)
Methodology (`/council`): [CC BY-SA 4.0](licenses/CC-BY-SA-4.0.txt)

See [LICENSE.md](LICENSE.md) for details.
