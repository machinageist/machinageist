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
- **Currently:** studying enterprise Linux administration toward the RHCSA, and documenting
  my cluster's network + DNS.
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

## Certifications — stated plainly

I'd rather publish the honest version of this than the impressive one. **None of these are
earned yet.** When one is, it will say *passed*, with the credential ID.

- **RHCSA (EX200)** — my active exam. Enterprise Linux administration on a RHEL-family
  system: SELinux contexts and AVC denials, LVM, rootless containers under systemd,
  boot-level recovery, `firewalld`. Studying now; **no exam date booked yet**, and I'll name
  a date here once one is scheduled.
- **CCNA (200-301)** — next, after RHCSA. Real study already logged against it; it isn't my
  active exam right now.
- **CompTIA Security+ (SY0-701)** — last in the sequence, planned rather than in progress.

The order is deliberate: RHCSA is the one that matches the Linux and infrastructure work I
actually do, so it comes first. Longer term I'm working toward infrastructure and platform
engineering — but the near-term rung is systems administration and infrastructure support,
and that's the work I'm building evidence for.

---

## Currently learning / not yet claiming

Deepening Linux systems administration on a RHEL-family scratch VM — SELinux, LVM,
containers, and boot-level recovery are study, not yet portfolio evidence, and I'll label
them that way until there's real command output behind them. Also building toward measured
backup/restore and evidence-gated HA testing on the cluster.

Not claiming: production SRE/DevOps, HA operations, or offensive-security work.

---

## Open to

Remote Linux / infrastructure support engineering and systems administration — plus technical
collaboration and a good conversation with people building serious things.

Based in Portland, OR.

📬 [machinageist@proton.me](mailto:machinageist@proton.me)
