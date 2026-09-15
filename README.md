# Hi, I'm Jeff — infrastructure technician: Linux, networking & virtualization

I'm an infrastructure-focused technical support candidate building a public portfolio
around self-hosted Linux services, Proxmox virtualization, network troubleshooting, and
security-operations fundamentals. I like systems with a clear reason to exist, and I like
understanding them deeply enough to *operate* them: make the hidden state visible, then
ship the smallest useful slice that survives real use.

I run a real **three-node Proxmox cluster** at home and self-host my site on it: a Rust/Axum
service behind Caddy and a Cloudflare Tunnel, publicly reachable with no open inbound ports.
The lab is where I deploy, break, observe, and harden real services.

- **Portfolio & write-ups:** https://machinageist.dev
- **Currently:** building out Linux systems-administration labs and documenting my
  cluster's network + DNS.
- **Hands-on with:** Linux (Arch daily driver, Debian servers), Proxmox VE, systemd, Caddy,
  Cloudflare Tunnel, DNS, TCP/IP diagnostics, Rust.

---

## Selected work

**[Geistos](https://github.com/machinageist/geistos)** — an in-progress local-first Arch workstation layer around Hyprland and Quickshell. It provides a keyboard-first bar and cards, theme/wallpaper state, lifecycle controls, and a PostgreSQL bootstrap boundary for the separate Geist application suite. The project is intentionally described as ongoing: packaging, clean-machine installation, and broader application integration are not finished.

**[mg-server](https://github.com/machinageist/mg-server)** — the Rust/Axum service that runs
machinageist.dev. Custom security-header and rate-limit middleware, compile-time templates,
self-hosted on a Proxmox Debian VM behind Caddy and a Cloudflare Tunnel.

**[homelab-infrastructure](https://github.com/machinageist/homelab-infrastructure)** — network
map, node/VM inventory, and troubleshooting notes for my three-node cluster.

---

## How I work

- Evidence-driven: small slices, tested assumptions, visible artifacts, honest limits.
- Security-aware by default: trust boundaries, least privilege, secrets hygiene, safe failure.
- I trace systems end to end — I'd rather understand the request path than guess at it.
- **I'd rather be precise than loud.** I label work as learning, in progress, or done, and I
  keep a note of what I can't yet claim.

---

## The homelab

Where curriculum becomes operational: Proxmox, Linux VMs, an Arch + Hyprland desktop, internal
DNS on a dedicated Pi, tunnels, reverse proxies, and enough moving parts to keep me honest. A
cluster with VM mobility — not a high-availability cluster, and I'm explicit about the
difference. It's a place to deploy, break, observe, and harden real services.

---

**Current study/build direction:** Linux systems administration, routing and switching, defensive security fundamentals, Rust tooling, and the Geistos workstation. I am building these through small homelab exercises, public technical notes, and software that I can run and inspect rather than treating a reading list as operational experience.

**What I am not claiming:** production SRE/DevOps, high-availability operations, or offensive-security expertise. Geistos and the broader Rust/software work are active projects, not finished products.

---

## Currently learning / not yet claiming

Deepening Linux systems administration and security-operations fundamentals through
hands-on homelab work, building toward measured backup/restore and HA testing on the
cluster. Not claiming: production SRE/DevOps, HA operations, or offensive-security work.

---

## Open to

Remote Linux / infrastructure support, systems administration, and NOC / data-center
roles — plus technical collaboration and a good conversation with people building serious
things.

📬 [machinageist@proton.me](mailto:machinageist@proton.me)
