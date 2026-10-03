# OpenCode_OffsecX

A custom **OpenCode configuration for cybersecurity and offensive-security workflows**.

`OpenCode_OffsecX` is similar in concept to [Hermes-EchoNet](https://github.com/giriaryan694-a11y/Hermes-EchoNet), but built for **OpenCode**.

The configuration is designed to give OpenCode a more security-focused workflow for activities such as:

* Authorized penetration testing
* CTFs and training labs
* Web and API security research
* Vulnerability analysis
* Security experimentation
* Cybersecurity learning

> **Recommended model:** `MiMo-V2.6-Flash Free`
>
> This is currently one of my favorite models available through OpenCode. OpenCode currently lists it as a free model for a limited time, so availability can change.

---

## ✨ Why OpenCode_OffsecX?

OpenCode provides a terminal-based AI coding agent with configurable agents, prompts, tools, permissions, and model preferences.

Compared with my [Hermes-EchoNet](https://github.com/giriaryan694-a11y/Hermes-EchoNet) configuration, this project is specifically intended for OpenCode and its agent system.

The goal is simple:

> **Turn OpenCode into a more security-oriented AI workspace without manually rebuilding the configuration every time.**

---

# 🛠️ Installation

## 1. Install OpenCode

### Recommended: npm

Make sure Node.js and npm are installed, then run:

```bash
npm install -g @opencode/cli
```

### Alternative: curl

```bash
curl -fsSL https://opencode.ai/v2/install | bash
```

OpenCode also provides other installation methods and standalone binaries. See the official OpenCode documentation for the latest options.

---

# 📥 2. Download OpenCode_OffsecX

Go to the directory where you want to use OpenCode.

For example:

```bash
mkdir my-security-lab
cd my-security-lab
```

Download the configuration:

```bash
wget https://raw.githubusercontent.com/giriaryan694-a11y/OpenCode_OffsecX/main/opencode.json
```

Your working directory should now contain:

```text
my-security-lab/
└── opencode.json
```

The important part is that `opencode.json` is available in the directory where you launch OpenCode.

---

# 🚀 3. Start OpenCode

Run:

```bash
opencode
```

OpenCode will start in your terminal.

---

# 🤖 4. Open the Agent Selector

Inside the OpenCode interface, run:

```text
/agents
```

This opens the available agent list.

<img width="765" height="261" alt="Screenshot 2026-10-03 134534" src="https://github.com/user-attachments/assets/28d1ca84-3433-4cda-ab44-4d2ee4229725" />

You should see the configured agents, including:

```text
OpenCode_OffsecX
```

Select it using your keyboard/cursor.

<img width="782" height="483" alt="Screenshot 2026-10-03 134546" src="https://github.com/user-attachments/assets/2b175ac7-2479-496e-8be3-f6e31d30ae55" />

OpenCode also supports switching between primary-capable agents with `Tab`.

---

# 🎯 5. Start Using OpenCode_OffsecX

Once `OpenCode_OffsecX` is selected, you are ready to use the configured agent.

For example, you can give it a security-related task inside an **authorized lab, CTF, or system you have permission to test**.

<img width="1302" height="521" alt="Screenshot 2026-10-03 134623" src="https://github.com/user-attachments/assets/407c5f93-66b7-4205-953e-9b96d2f16001" />

The exact response and available capabilities can depend on the model, OpenCode version, configuration, and enabled permissions.

---

# 🧠 Recommended Model

My personal recommendation for this configuration is:

```text
MiMo-V2.6-Flash Free
```

OpenCode currently provides several free models through its ecosystem, and the available list can change over time.

I particularly like **MiMo-V2.6-Flash Free** for this workflow because it is the model I have found most useful for my OpenCode security experiments.

Free model availability is not permanent, because apparently even computers have subscription drama.

---

# 📁 Repository Structure

```text
OpenCode_OffsecX/
├── opencode.json
├── README.md
└── LICENSE
```

The `images/` directory contains screenshots used by this README.

---

# ❓ Common Questions

## Is OpenCode_OffsecX safe to use for pentesting, CTFs, or labs?

The configuration is intended for:

* CTFs
* Local security labs
* Training environments
* Authorized penetration testing
* Cybersecurity research
* Ethical hacking practice

For professional penetration tests, make sure the AI service and associated data handling are permitted by the organization or client.

Things worth checking include:

* AI-generated content policies
* Logging and privacy requirements
* Whether external AI services are allowed
* Internal compliance requirements
* Rules surrounding sensitive source code, credentials, and customer data

The configuration does not grant permission to attack systems. Authorization still matters, tragically, because computers have not yet replaced lawyers.

---

## Does this configuration make OpenCode an autonomous hacking tool?

No.

`OpenCode_OffsecX` is a configuration that changes the agent's behavior, system instructions, available capabilities, and/or model configuration according to the contents of `opencode.json`.

Its actual capabilities depend on:

* OpenCode
* The configured agent
* Enabled permissions
* Available tools
* The selected model
* The environment where OpenCode is running

---

## Can I use another model?

Yes.

OpenCode supports multiple providers and models. You can use another supported model by changing the relevant model configuration or selecting another model through OpenCode.

Free models may change or disappear over time, so do not build a workflow that depends on one temporary free offering surviving forever.

---

## Do I need to use this exact directory structure?

No.

The important part for the quick-start method in this repository is downloading the `opencode.json` configuration into the directory where you intend to run OpenCode.

---

# ⚠️ Important Notes

* `OpenCode_OffsecX` is intended for:

  * Ethical hacking
  * Security labs
  * Pentest learning
  * Authorized research
  * CTF workflows
* Always follow applicable laws, rules, and platform terms.
* Only test systems you own or are explicitly authorized to assess.
* Do not place API keys, passwords, session tokens, private keys, or other secrets into this repository.
* Review the configuration before using it in environments containing sensitive information.
* Model availability, configuration syntax, and OpenCode behavior may change as OpenCode evolves.
* This project is not affiliated with OpenCode, Anomaly, or the developers/providers of the models mentioned here.

---

# 🔗 Related Projects

### Hermes-EchoNet

A similar security-oriented configuration for the Hermes agent:

https://github.com/giriaryan694-a11y/Hermes-EchoNet

### OpenCode

OpenCode is an open-source AI coding agent that runs in the terminal and supports configurable agents, models, tools, and permissions.

---

# 📜 License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for details.

---

## ⭐ Credits

Created and maintained by **giriaryan694-a11y**.

Built for experimenting with AI-assisted cybersecurity workflows, security research, and offensive-security learning.
