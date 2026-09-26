# OpenClaw Installation

## Purpose

OpenClaw serves as the core AI agent framework responsible for receiving user requests, managing workflows, and coordinating communication between Telegram, Ollama, and integrated security tools.

---

## Installation Steps

### Step 1: Update Kali Linux

Update the system packages to ensure all dependencies are up to date.

```bash
sudo apt update && sudo apt upgrade -y
```

### Step 2: Install Git

Git is required to clone the OpenClaw repository.

```bash
sudo apt install git -y
```

### Step 3: Clone the OpenClaw Repository

Download the OpenClaw source code from GitHub.

```bash
git clone <repository-url>
```

### Step 4: Navigate to the Project Directory

```bash
cd OpenClaw
```

### Step 5: Configure OpenClaw

Update the configuration files with the required Telegram and Ollama settings.

### Step 6: Start OpenClaw

Launch the OpenClaw service.

```bash
docker compose up -d
```

---

## Verification

Verify that OpenClaw containers are running successfully.

```bash
docker ps
```

Expected result:

* OpenClaw containers are running.
* No errors are displayed.
* Services are accessible for integration with Ollama and Telegram.

---

## Outcome

OpenClaw is successfully installed and ready to communicate with Ollama, Telegram, and integrated cybersecurity tools.
