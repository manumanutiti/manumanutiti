### Hi, I'm Manuel 👋

Platform / DevSecOps engineer based in Marbella, Spain. I work on Kubernetes, AWS and Terraform, and I care about security being part of the platform rather than something bolted on afterwards. 

In my spare time I build infrastructure and security tools in Go and Python, mostly to understand how things work one layer down.

#### What I'm building

- **[MicroHosted](https://github.com/manumanutiti/MicroHosted)**: Docker and Docker Compose, but every container is a Firecracker microVM. Written in Go: `mh build`, `mh run`, `mh up`, with each workload getting its own kernel inside Jailer (chroot + cgroups v2 + seccomp) and isolated networks enforced with nftables.
- **[sknock](https://github.com/manumanutiti/sknock)**: Single Packet Authorization daemon and client in Go. One encrypted UDP packet (X25519 + AES-256-GCM, TOTP inside) opens access, and the server never answers, so to nmap or masscan the port looks closed. An auditable alternative to fwknop.
- **[anchor](https://github.com/manumanutiti/anchor)**: a CLI plus a self-hosted vault for small teams. Secrets are resolved at runtime, kept in memory and never written to disk. Per-secret key derivation (HKDF-SHA256), versioning and group-based RBAC. Python (FastAPI), MongoDB.
- **[sec-linux](https://github.com/manumanutiti/sec-linux)**: Ansible roles for Linux hardening.

#### Tools I use

Kubernetes · AWS · Terraform · Helm · ArgoCD · GitHub Actions · GitLab CI · Prometheus · Grafana · Go · Python · Bash

#### Contact

[LinkedIn](https://linkedin.com/in/maguher)
