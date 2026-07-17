# Hi, I'm Jeff — infrastructure, Linux & networking

I like systems with a clear reason to exist, and I like understanding them deeply enough
to *operate* them: make the hidden state visible, then ship the smallest useful slice that
survives real use. I'm moving into infrastructure and network operations — NOC, Linux
systems, and data-center / cloud support — and I build the evidence for it in public.

I run a real **three-node Proxmox cluster** at home and self-host my site on it: a Rust/Axum
service behind Caddy and a Cloudflare Tunnel, publicly reachable with no open inbound ports.
The lab is where I deploy, break, observe, and harden real services.

- **Portfolio & write-ups:** https://machinageist.dev
- **Currently:** studying CompTIA Network+ (N10-009); documenting my cluster's network + DNS.
- **Hands-on with:** Linux (Arch daily driver, Debian servers), Proxmox VE, systemd, Caddy,
  Cloudflare Tunnel, DNS, TCP/IP diagnostics, Rust.

---

## Selected work

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

## Currently learning / not yet claiming

Security+ next, then Linux+ and Server+. Building toward measured backup/restore and HA testing
on the cluster. Not claiming: production SRE/DevOps, HA operations, or offensive-security work.

---

## Open to

Infrastructure, Linux, NOC, and cloud-support roles — plus technical collaboration and a good
conversation with people building serious things.

📬 [machinageist@proton.me](mailto:machinageist@proton.me)
