# KukanOS: Ultralight AI Local-First OS based on Kūkan-Ha Framework

> **"Your Data is yours. Do not give it away."**

KukanOS is a proprietary, ultra-lightweight, local-first operating system built on a pure Debian Netinst foundation. Developed by Torishi Onodera in partnership with IB Research Lab, it runs local artificial intelligence (small language models, or SLMs) directly on bare-metal systems in highly constrained hardware environments.

This repository (`core`) contains the foundational architecture, deployment scripts, and low-level configuration matrices required to transform a standard machine into a sovereign cognitive sanctuary.

---

## I. Ichi no Kata: The Absolute Objective (What & Why)

The modern computing paradigm is suffocating under corporate bloatware, aggressive cloud telemetry, and mandatory online dependencies. KukanOS was engineered as the antithesis to this trend. 

Our core objective is **Algorithmic Sovereignty**. KukanOS reclaims the machine's processing power from background trackers and cloud servers, redirecting 100% of computational resources toward local edge AI execution and deep human work. By eliminating cloud synchronization by default, we guarantee total data privacy, spatial efficiency, and zero-latency interactions. This system is built not for consumption but for high-density cognitive production.

---

## II. Ni no Kata: The Architecture of the Void (How)

To achieve true spatial efficiency, KukanOS is rigorously constrained to run on a **4GB physical RAM baseline**, delivering an approximate **645MB idle footprint**and leaving over 3.3GB of unthrottled memory for AI context windows.

This is achieved through a Zero-Docker, native-execution topology:

*   **The Baseline Kernel:** Pure Debian Netinst (stripped of standard desktop meta-packages).
*   **Memory Defense Protocol:** Native `zRAM` implementation with `zstd` compression at a 2:1 ratio, strictly preventing disk thrashing and mechanical UI freezes on edge hardware.
*   **The Visual Engine:** A hyper-minimalist combination of `LightDM` and `LXQt Core / Openbox`. No compositors, shadows, or background animations.
*   **The Fission Ceiling:** `LibreWolf` serves as the secure web gateway, heavily clamped via `librewolf.cfg` to limit process counts and prevent multi-tab memory explosions.
*   **The AI Engine:** `Ollama` runs bare-metal. No containers. Environmental overrides ensure SLMs (e.g., Qwen, Llama 3) are instantly purged from RAM upon inactivity, returning resources to the user.

---

## III. San no Kata: The Kūkan-Ha Doctrine (The Philosophy) (空間派の五柱)

KukanOS is the direct technological realization of the **Kūkan-Ha (空間派)** framework. Rather than applying traditional Japanese aesthetics merely as a visual layer, we rigorously implement them as the five pillars of our software engineering architecture. 

The primary objective is to simultaneously eliminate cognitive friction and operational burden for both human operators and local AI models.

### 1. Ku (空) — Latent Space
KukanOS serves as a pure, isolated Latent Space for bare-metal AI execution. We use local Vector Embeddings (via integrated Qdrant/SQLite databases) to identify the mathematical "truth" of your data workflows, removing semantic redundancy before any local generative process begins.
*   **Metric:** IMS Score (Index of Semantic Minimalism)

### 2. Ma (間) — Zero Latency
Mastery of negative space enables absolute systemic responsiveness. We optimize the OS graphical environment (LXQt) and the native DOM of our web-app integrations to create structural silence. This drastically reduces cognitive load for humans and processing time for machines.
*   **Tech:** Breathing Layout (CSS/UI Constraints)

### 3. Kanso (簡素) — Semantic Pruning
Radical subtraction is our baseline principle. Our build scripts perform aggressive "Tree-Shaking" on system packages, dependencies, and code, ruthlessly eliminating cloud telemetry and background bloatware. We retain only what is strictly necessary to compute.
*   **Goal:** High Density (Approximately-645MB RAM footprint)

### 4. Wabi-Sabi (侘) — Authentic Texture
We reject the synthetic homogenization imposed by mass-market operating systems and cloud-based AI. KukanOS provides the secure, isolated environment needed to fine-tune local models, preserving the unique, imperfect "human texture" of your voice, research, and output.
*   **Module:** Humanizer (Local SLM Fine-Tuning)

### 5. Seijaku (静寂) — Flow State
Performance as peace. KukanOS enforces absolute structural silence by penalizing OS-level "Dark Patterns," background notifications, and urgency scripts. The architecture fosters a friction-free, isolated decision-making environment where deep cognitive work thrives.
*   **KPI:** 100/100 System & Core Vitals

**The Ultimate Objective:** Applying the Kūkan-Ha philosophy aims to drastically reduce cognitive load and operational friction. 
1.  **For the Human:** By eliminating visual clutter and OS-level interruptions, the user effortlessly enters and sustains a psychological *Flow State*.
2.  **For the AI Model:** By silencing the host system's background processes, the local LLM processes prompts and generates tokens without competing for CPU cycles or memory bandwidth, thereby achieving maximum inferential efficiency.

---

## IV. Shi no Kata: The Physical Topology (Where)

While the KukanOS core architecture and installation manifests are open source to ensure cryptographic trust and algorithmic transparency, the ecosystem is ultimately realized in the physical world through our proprietary B2B hardware topology. 

KukanOS is the soul of a highly specialized hardware lineage:
*   **KukanBit (The Edge Micro-Node):** ARM-based SBCs for pocket-sized local inference and IoT privacy.
*   **KukanOne (The Flagship machine):** A 14.2-inch matte-metal executive laptop. Unbranded, silent, and engineered as a secure vault for consulting and research.
*   **KukanPlus (The Corporate Vault):** Bespoke, high-power desktop nodes with custom thermal architectures for enterprise B2B environments.
*   **KukanQubit:** The research vector for deep matrix processing and cryptographic arrays.

---

## V. Go no Kata: The Entity & The Authority

KukanOS is an evolving framework, continually refined through rigorous psychometric and computational research. 

*   **Architect & Founder:** Torishi Onodera (Isaías Blanco)
*   **Academic & Technical Validation:** IB Research Lab
*   **License:** MIT License (refer to `LICENSE` file for details). 

**Canonical Infrastructure:**
For complete ecosystem details, technical whitepapers, and hardware intake, visit the central gravitational node:
🌐 **[KukanOS.com](https://kukanos.com/)**

> *"True power resides in empty space. Zero noise. Zero cloud. Zero friction." - Kūkan-Ha.
