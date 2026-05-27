# Hi — I’m Alex

**Go Infrastructure Engineer**  
**Network control planes · Web3 infrastructure · OS-adjacent reliability**

Building Go infrastructure tools for observable, recoverable systems; currently exploring AI-assisted workflows for Web3 operations and backend reliability.

I build Go systems close to the operating system: processes, signals, timeouts, routing tables, NAT, firewalls, TUN interfaces, health checks, watchdogs, and deterministic recovery.

My focus is backend infrastructure that can be inspected, restarted, verified, and recovered.

---

## Core Engineering Area

**Go infrastructure engineering**

- Process lifecycle supervision
- `context.Context` cancellation
- POSIX signal handling
- Timeout-bounded command execution
- External process orchestration with `os/exec`
- Runtime state verification
- Health-check loops
- Watchdog / recovery logic
- Config-driven daemon behavior
- Failure-aware logging

**Network systems**

- TCP/IP
- Routing tables
- NAT
- DNS / DHCP
- SOCKS5 testing
- TUN / utun interfaces
- Host firewall policy and dynamic rule orchestration
- Dynamic firewall anchors
- Fail-closed LAN traffic protection
- Transport-bound routing policy
- Secure-path recovery
- Network-dependent service recovery

**Web3 infrastructure**

- Ethereum execution-layer fundamentals
- Geth development-node operation
- IPC console workflow
- HTTP JSON-RPC inspection
- Account and transaction testing
- Gas / fee mechanics
- Mempool concepts
- Solidity ABI/bin compilation
- Node diagnostics from an operator perspective

---

## Current Focus

I am building and documenting infrastructure systems in Go:

- local-network control-plane daemons
- network automation tools
- process supervisors
- reliability tooling
- Web3 node-operation labs
- reproducible debugging environments

I care about what happens after a system starts:

- how it fails
- how it reports failure
- how it prevents unsafe states
- how it recovers
- how an operator can verify the result

---

## Main Project

[`xrouter`](https://github.com/revolver-sys/xrouter) is my current main infrastructure project.

`xrouter` is a Go-based LAN gateway control plane for secure transport backends, `pf`/NAT orchestration, and fail-closed traffic protection.

The current implementation provides a working macOS gateway daemon that coordinates a TUN-based transport process, discovers runtime `utun` interfaces, applies dynamic `pf` policy, performs health checks, and triggers deterministic recovery when the configured secure path becomes unavailable.

The important part is not a single transport implementation.

The important part is the control plane:

- process supervision
- dynamic interface discovery
- firewall / NAT state orchestration
- transport-bound routing policy
- fail-closed LAN traffic protection
- deterministic recovery
- operational diagnostics

`xrouter` is the first working stage of a broader local-network routing platform, with active development direction toward pluggable transport backends, Docker-based backend isolation, live status tracking, event streams, and multi-node deployment models.

---

## Additional Project Directions

**LAN / local network tooling**

- local gateway automation
- network recovery workflows
- status and health inspection
- host-level routing diagnostics
- controlled failure handling

**Web3 / RPC reliability**

- node-operation labs
- JSON-RPC inspection
- execution-layer experiments
- failure-pattern analysis
- operational debugging from an infrastructure perspective

---

## Tools I Work With

`Go` · `Shell/Zsh` · `YAML` · `Git` · `SSH` · `Docker basics` · `Geth` · `JSON-RPC` · `IPC` · `solc` · `pfctl` · `ifconfig` · `netstat` · `scutil` · `curl`

---

## What I’m Looking For

I’m interested in infrastructure-heavy backend roles involving:

- Go backend systems
- Web3 / RPC infrastructure
- blockchain node platforms
- network automation
- service reliability
- process supervision
- routing / failover tooling
- observability and operational diagnostics

---

If you are building systems where failure matters — we should talk.
