<div align="center">

# Hi, I'm Damodar · Technerd07 👋

I'm Damodar, an infrastructure enthusiast interested in operating systems, networking, cloud computing, and how complex systems work. I enjoy building hands-on labs, tracing failures across system components, and documenting what I learn.

<br />

[![GitHub](https://img.shields.io/badge/GitHub-Technerd07-7aa2f7?style=flat-square&logo=github&logoColor=white&labelColor=1a1b27)](https://github.com/Technerd07)

</div>

---

### About Me

- ☸️ **Kubernetes, built by hand:** I bootstrap clusters manually (etcd, PKI, control plane, kubelets, pod networking) with plain shell scripts, so I understand every moving part.
- 💥 **Chaos engineering & recovery:** I reproduce real cluster failures and write step-by-step break-glass recovery guides.
- 🐳 **Containers:** Daily hands-on with Docker and Podman for packaging, running, and debugging workloads.
- 🧰 **Shell-first automation:** Repeatable tools written in Bash, with systemd integration where it fits.
- 🧅 **Privacy & security:** Self-hosted services over Tor, encrypted file transfer, and private search.
- 📚 **How I work:** Practical documentation, careful testing, learning by building.

---

### Focus Areas

```bash
$ cat focus_areas.json
{
  "kubernetes":           ["Manual cluster bootstrap", "etcd", "PKI & certificates", "CNI / pod networking", "kubectl"],
  "containers":           ["Docker", "Podman", "Images & registries", "Container networking"],
  "reliability":          ["Chaos engineering", "Fault injection", "Break-glass recovery", "Root-cause debugging"],
  "privacy_and_security": ["Tor onion services", "Encrypted transfer", "Self-hosted IRC / Matrix / mail", "Private search"],
  "automation":           ["Bash", "Linux", "systemd timers", "Git workflows", "Java"]
}
```

---

### Featured Projects

#### ☸️ Kubernetes & Reliability

| Project | What it is |
| :-- | :-- |
| [**kubernetes-manual-cluster**](https://github.com/Technerd07/kubernetes-manual-cluster) | Numbered shell scripts that build a Kubernetes cluster by hand: jump box and SSH setup, certificate and key generation, etcd, control plane, worker nodes, kubectl config, and pod networking. |
| [**k8s-problems-reproduced**](https://github.com/Technerd07/k8s-problems-reproduced) | Chaos engineering and disaster-recovery lab for bare-metal Kubernetes. Reproducible fault injection (etcd corruption, API server outages, CNI/iptables drops, DNS and endpoint failures) with recovery workflows. |

#### 🧰 Tooling

| Project | What it is |
| :-- | :-- |
| [**git-sync**](https://github.com/Technerd07/git-sync) | Bash utility for local Git setup and remote repository synchronization, with optional systemd user timer integration. |

#### 🔐 Privacy & Security

| Project | What it is |
| :-- | :-- |
| [**safe_relay**](https://github.com/Technerd07/safe_relay) | Java project exploring encrypted file transfer over Tor. |
| [**shadowseek**](https://github.com/Technerd07/shadowseek) | A private search engine project. |
| [**IRC_server_over_tor**](https://github.com/Technerd07/IRC_server_over_tor) | Self-hosted IRC server exposed as a Tor onion service. |
| [**matrix_synase_over_tor**](https://github.com/Technerd07/matrix_synase_over_tor) | Matrix Synapse homeserver reachable over Tor. |
| [**mailserver_over_tor**](https://github.com/Technerd07/mailserver_over_tor) | Self-hosted mail server running behind Tor. |

---

### Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,kubernetes,docker,java,git,github,nginx,prometheus,grafana&theme=dark" alt="Skills" />
</div>

<br />

<div align="center">

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![etcd](https://img.shields.io/badge/etcd-419EDA?style=flat-square&logo=etcd&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111827)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Tor](https://img.shields.io/badge/Tor-7D4698?style=flat-square&logo=torproject&logoColor=white)
![Matrix](https://img.shields.io/badge/Matrix-000000?style=flat-square&logo=matrix&logoColor=white)
![I2P](https://img.shields.io/badge/I2P-Privacy%20Network-4B6B3C?style=flat-square)
![IRC](https://img.shields.io/badge/IRC-Self--Hosted-5B4B8A?style=flat-square)
![Mail Servers](https://img.shields.io/badge/Mail%20Servers-Self--Hosted-52616B?style=flat-square)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat-square&logo=virtualbox&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-FFFFFF?style=flat-square&logo=systemd&logoColor=black)

</div>

I also have hands-on experience setting up private-hosted services, including I2P networks, IRC networks, and mail servers. I prioritize privacy and anonymity, using secure tunnels to help protect service traffic and access.

---

### How I Learn

I start with a working system, change one part at a time, and observe how the behavior changes. When something fails, I trace the issue across the relevant layers—Linux, networking, Kubernetes components, and workloads—then document the evidence and recovery steps. This helps me understand not just which command fixes an issue, but why the system behaved that way.

<div align="center">

<sub>Build it. Break it. Document it.</sub>

</div>

---

### More About My Interests

I’m also interested in exploring Linux internals, operating-system behavior, container runtimes, and cloud computing. I enjoy breaking down complex systems into their components, tracing how networking and control-plane services interact, and learning how to diagnose and recover from failures. These are areas I’m continuing to explore through hands-on labs and documentation.
