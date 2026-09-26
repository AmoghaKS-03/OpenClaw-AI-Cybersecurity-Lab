# Environment Setup

## Lab Environment

The OpenClaw AI Cybersecurity Lab was deployed on Kali Linux, providing a stable environment for running AI models, managing integrations, and testing cybersecurity tools.

---

## Hardware Requirements

| Component | Specification                                  |
| --------- | ---------------------------------------------- |
| CPU       | Multi-Core Processor                           |
| RAM       | Minimum 8 GB (16 GB Recommended)               |
| Storage   | 20 GB+ Free Space                              |
| GPU       | Optional (Recommended for faster AI inference) |

---

## Software Components

| Software   | Purpose                                   |
| ---------- | ----------------------------------------- |
| Kali Linux | Operating System                          |
| OpenClaw   | AI Agent Framework                        |
| Ollama     | Local LLM Runtime                         |
| Telegram   | User Communication Interface              |
| Git        | Repository Management and Version Control |

---

## Network Requirements

* Stable internet connection
* Access to Telegram services
* Access to download required models and dependencies

---

## Environment Verification

Verify the Kali Linux installation:

```bash
cat /etc/os-release
```

Verify Git installation:

```bash
git --version
```

Verify internet connectivity:

```bash
ping -c 4 google.com
```

Successful execution of these commands confirms that the environment is ready for OpenClaw installation and configuration.
