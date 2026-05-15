# Hi — I’m Alex

**Go Infrastructure Engineer**  
**Network control planes · Web3 infrastructure · OS-adjacent reliability**

Building Go infrastructure tools for observable and recoverable systems; currently exploring AI-assisted workflows for Web3 operations and backend reliability.

I build Go systems close to the operating system: processes, signals, timeouts, routing tables, NAT, firewalls, tunnels, health checks, watchdogs, and deterministic recovery.

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
- macOS `pf` firewall rules
- Dynamic firewall anchors
- LAN-to-WAN leak prevention
- Kill-switch architecture
- Tunnel-bound routing
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

I am building and documenting small infrastructure systems in Go:

- control-plane daemons
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

## Selected Project Direction

My strongest current work is a Go-based network control-plane project for macOS.

The system coordinates external tunnel processes, discovers runtime network interfaces, applies firewall/NAT state, performs health checks, and enforces strict traffic safety rules.

The important part is not the tunnel itself.

The important part is the control plane:

- process supervision
- dynamic interface discovery
- firewall state orchestration
- routing safety
- deterministic recovery
- operational diagnostics

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

