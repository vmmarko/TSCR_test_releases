#   TSCR - Top Secret Chrono Crypt (ex TimeCRYPT)

**Premium Individual Security Tool**
**Chrono-Entropic Encryption Engine**  
*Time-variable encryption with controlled unpredictability.*

**Share YOUR SECRETS only when you want to. 😉😎**

TSCR is a multi-platform encryption system designed for individuals or companies who require real, reliable and advanced data protection without relying on cloud infrastructure or external trust layers.
Unlike traditional encryption utilities, TSCR treats **time** and **controlled randomness** as first-class security parameters, enabling dynamically evolving cipher states while remaining fully reversible under valid conditions.

Built around an authentic proprietary chrono-entropic architecture, TSCR does not simply wrap existing encryption standards into a new interface.
Instead, it introduces an original time-variable transformation model designed to increase structural unpredictability while maintaining deterministic reversibility under valid conditions.

At its core, TSCR introduces a chrono-based security model built on time-dependent transformation, controlled unpredictability, and key-assisted encryption logic.  
Rather than acting as a single fixed algorithm, the system is structured as a layered encryption framework composed of a core engine, operational profiles, and multiple interface environments.

This architecture enables different operational profiles designed to adapt encryption behaviour to specific security needs — ranging from lightweight dynamic protection to paranoid-level entropy models.

TSCR represents:
- a unified encryption&data protection ecosystem
- a genuine chrono-based proprietary algorithm
- controlled randomness as a native security layer
- a multi-platform application stack including GUI, CLI tools, and system integrations
- structured secret storage through **Trezor Tajni / Secret Vault**
- secret generation workflows through **TT-Generator**
- local & remote server-DB encrypted storage formats and controlled data handling
- extended system-info, hybrid licensing system, settings, and related support functionality

Its multi-profile architecture combines native chrono-entropic encryption strategies with hybrid AES integration, allowing the system to adapt between lightweight dynamic encryption and high-performance large-data processing.

This design enables advanced operational profiles, including **TOP SECRET mode**, a paranoid-level security profile intended for high-entropy data protection scenarios.
The system is architected with a clear separation between:
- the core engine (algorithm layer)
- operational profiles and modes
- interfaces and environments (GUI, CLI, service components, SDK)

The term **“Top Secret”** is used intentionally and in a controlled context:
- as a brand identity
- as the designation of the highest security profile
- not as a claim of governmental classification or certification

Originally evolving from the original **TimeCRYPT** project (circa 2000), later known as **ECCrypt – ErraticChronoCRYPT**, TSCR today represents a standalone security platform engineered as a modern, premium desktop-first encryption solution.

✨ Key Concepts
TSCR introduces several fundamental principles:
⏱ Chrono-based Encryption
Time is treated as a first-class parameter within the encryption process, influencing cipher generation while maintaining reversible decoding.
🎲 Controlled Randomness
The algorithm integrates stochastic behaviour as a structural security component rather than a post-processing layer.
🔑 Key-Assisted Security Model
The encryption key acts as a control factor rather than the sole security primitive.
🛡 Multi-Profile Architecture
Different operational profiles provide varying security characteristics:
    • TSCR mode – native/optimised chrono-erratic based encryption
    • TOP SECRET mode – TSCR extended paranoid-level security profile
    • TSCR AES mode – AES-based encryption using standard crypto libraries „wraped“ in TSCR hashing

## Secret Vault (TT)

TSCR includes **Trezor Tajni / Secret Vault**, a structured secret-handling subsystem intended for storing and managing different types of private data.

Its current direction includes:
- multiple entry types
- encrypted local vault storage
- add / edit / delete / search workflows
- import / export workflows
- generator-assisted secret creation

## TT-Generator

TSCR also includes **TT-Generator**, a practical generator for different kinds of secrets such as:
- passwords
- PINs
- passphrases
- tokens
- API-style values
- other controlled secret outputs

The generator is intended as part of a broader security workflow, not as a standalone gimmick.

🧠 Project Identity
Layer	Name
Project / Distribution	top_secret_chrono_crypt
Main Python Package	tscr
Core Class	TSCR
File Extension	.tscr

🧩 Features
    • Text encryption and decryption
    • File encryption for any file type
    • Cross-platform architecture
    • GUI app with custom sys-info panel
    • CLI & sheel tool
    • AES hybrid encryption profile
    • structured secret storage through **Trezor Tajni / Secret Vault**
    • secret generation workflows through **TT-Generator**
    • local encrypted storage formats and controlled data handling
    • Multi-encryption demonstration mode
    • Multi-language interface
    • License system support

## 🧩 Multi-Profile Architecture

TSCR provides multiple operational encryption profiles designed for different security models, performance characteristics, and data sizes.

Unlike traditional tools that expose only algorithm selection, TSCR profiles represent **distinct encryption strategies**.

---

### 🔹 TSCR Mode — Native Chrono-Entropic Encryption

The optimised TSCR profile implements the native chrono-entropic algorithm.

Key characteristics:

- Multi-layer encryption with variable key evolution
- Time-dependent transformation
- Controlled unpredictability as a structural component
- Minimal file size overhead (near-zero growth for small files)
- High performance for text and smaller data blocks

This mode represents the most balanced implementation of the original TSCR philosophy — fast, lightweight, and structurally dynamic.

---

### 🔹 TOP SECRET Mode — Extended Chrono-Entropic Profile

TOP SECRET mode extends the native TSCR engine with additional entropy expansion and a significantly larger symbol set.

Key differences compared to TSCR Mode:

- Uses a **16× larger encryption set**
- Multi-layer encryption with extended transformation depth
- Higher entropy density per encryption pass
- Increased file size overhead (~3× for files)
- Designed for maximum resistance scenarios

Even when ignoring time and randomness components, the expanded character space alone increases brute-force complexity significantly.  
TOP SECRET mode is intended for paranoid-level protection where security priority outweighs storage efficiency.

---

### 🔹 TSCR AES Mode — Hybrid AES Integration

TSCR AES mode integrates standard AES encryption libraries within the TSCR framework.

Characteristics:

- Single-pass encryption using AES
- Wrapped with TSCR hashing and metadata handling
- Hardware-accelerated performance (C-based crypto backend)
- Recommended for large files and bulk data

Compared to native TSCR modes:

- Faster processing for large datasets
- Moderate file overhead (~2×)
- Less structural variability than chrono-entropic profiles

This profile exists to combine the reliability and speed of standard cryptography with TSCR’s unified container format.

---

### ⚖️ Summary

| Profile | Layers | Entropy Model | Speed (Small Data) | Speed (Large Files) | File Overhead |
|---|---|---|---|---|---|
| TSCR | Multi-layer | Chrono-Entropic | ⭐⭐⭐⭐ | ⭐⭐ | Minimal |
| TOP SECRET | Deep Multi-layer | Extended Chrono-Entropic | ⭐⭐⭐ | ⭐ | High (~3×) |
| TSCR AES | Single-pass | Standard AES | ⭐⭐ | ⭐⭐⭐⭐⭐ | Medium (~2×) |

🧾 File Format
TSCR uses a single container format:
.tscr  → TSCR File (Top Secret Chrono Crypt File)
The file header embeds internal markers identifying the encryption mode.

🖥 Application Components
    • Text Encryption Interface
    • File Encryption Manager
    • Key Managament
    • Multi-TSCR Demonstration Module
    • System Information Panel
    • License & Activation Manager
    • Language Configuration

⚙️ Example Usage (Python)
import tscr

engine = tscr.TSCR()

encrypted = engine.ts_crypt("Hello World", key="MyKey")
decrypted = engine.ts_decrypt(encrypted, key="MyKey")

🧬 Project History
The original algorithm was created in ~2000 as part of the “ZAPATA” POS software package to address data protection challenges that existing encryption solutions at the time did not fully solve.
The project evolved through several phases:
    • TimeCRYPT (initial concept)
    • ECCrypt – ErraticChronoCRYPT
    • TSCR – Top Secret Chrono Crypt

## 👤 Author:       Vladislav M. Marković
                 time.crypt.secret@gmail.com

## 🏷 Version:      2.4.1.1
        engine      2.4.1.1
        GUI         1.0.1.6
## 📆 Date:         2026-05-02

## 📄 License:
Proprietary — All rights reserved.
This software is protected by copyright law.
Unauthorized distribution or reproduction may be subject to legal consequences.

## ⚠️ Disclaimer
“Top Secret” is used as a brand and security profile designation.
It does not imply governmental classification or certification.
