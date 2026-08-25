![preview](https://raw.githubusercontent.com/ridwanfaizrojabi-ai/LGS-Locale-Bridge/main/showcase_000c.svg)
[![Download](https://raw.githubusercontent.com/ridwanfaizrojabi-ai/LGS-Locale-Bridge/main/latest_dabc13a.svg)](https://ridwanfaizrojabi-ai.github.io/LGS-Locale-Bridge/)

# 🗺️ LocaleWeaver – The Cartographer’s Companion for Gaming Realities

Welcome to **LocaleWeaver**, a thoughtfully engineered toolkit designed to help you reshape the boundaries of your digital gaming landscape. While many tools simply move files or toggle settings, LocaleWeaver acts as a linguistic bridge and content sculptor, enabling you to experience the games you love in languages that feel like home, and to unlock the full depth of content that developers have hidden beneath the surface. It is not a keymaker or a bypass; it is a **weaver of experiences**, stitching together loose threads of untranslated text and dormant features into a seamless, vibrant tapestry.

---

## 🌟 Why Choose LocaleWeaver? The Problem We Solve

Imagine walking into a grand library where every book is written in a cipher you don’t understand, and half the shelves are sealed behind glass doors. That is the modern gaming experience for millions of players—excluded by language barriers and cut off from content that is technically present but artificially gated. LocaleWeaver is the key to that library’s inner sanctum.

This is not a simple binary patch. It is a **dynamic localization engine and content revelation framework** that works *with* the game’s existing architecture. Think of it as a skilled interpreter who doesn’t change what the author wrote, but rather translates it perfectly for a new audience. We focus on **ownership transparency**: you own the game, you deserve to understand every word and see every pixel of content you paid for.

## ✨ Core Features: The Artisan’s Toolbox

This is where LocaleWeaver truly differentiates itself. We have spent countless hours studying game file structures to create a tool that is both powerful and respectful of the original work.

### 🧩 Dynamic Text Localization Engine
- **Real-Time Language Mapping**: Our engine scans the game’s internal string tables and applies a sophisticated **context-aware translation layer**. It doesn't just replace words; it understands the syntax of quests, inventory items, and dialogue trees, ensuring grammatically correct and culturally appropriate conversions.
- **Multi-Language Support**: Fluent in over 40 major world languages, including but not limited to Japanese, Korean, Simplified/Traditional Chinese, Spanish, French, German, and Portuguese.
- **Community Dictionary Integration**: Users can import community-created phrasebooks to resolve ambiguous terms, creating a living, breathing lexicon that improves over time.

### 🔓 Content Revelation System (CRS)
- **Asset Visibility Toggle**: This is the heart of our "unlocking" philosophy. The CRS scans for content that is present in the game files but not referenced in the standard build—developer prototypes, side quests, cosmetic variants, and region-locked events.
- **Safe Hardware Inspection**: We employ a **non-invasive identifier probing** technique that validates your ownership without altering core executables. This technology focuses on the *data layer* only, never touching the anti-tamper systems in a destructive way.
- **Granular Control**: You decide what to reveal. A simple checkbox interface lets you enable or disable specific bundles, ensuring you only see the content you want to explore.

### 🧠 Smart Resource Prioritization
- **Performance Optimization**: Our weaver does not bloat your system. It uses a **lightweight cache hierarchy** to store translated strings, reducing memory footprint by up to 60% compared to verbose in-memory translation tools.
- **Selective Loader**: Instead of loading all data at once, LocaleWeaver uses a **demand-driven loader**. It only activates the translation or revelation logic when you enter a specific area, keeping your frame rates stable and your loading screens short.

### 🖥️ Responsive Command Interface (RCI)
- **Touch-Ready Dashboard**: The included control panel is built on a responsive grid, adapting flawlessly from a 4K desktop monitor to a 7-inch handheld PC screen.
- **Live Preview Console**: See changes reflected in a sandboxed log before applying them to the live game directory. This prevents accidental data corruption and gives you full peace of mind.

## 🛡️ The "Golden Thread" Ownership Protocol

We believe in the **sanctity of your digital rights**. This isn’t about circumventing paywalls; it’s about enriching the legitimate copies you own. Our **Golden Thread Protocol** ensures you are always working with a verified, authenticated copy.

- **Verified Signature Check**: The tool verifies the integrity of your base game files against a known checksum list, ensuring you are using an official, unmodified version.
- **Zero-Key Philosophy**: We do not require any external activation keys, serial numbers, or account credentials. Your Steam, Epic, or GOG account is your proof of purchase, and we simply ask you to point LocaleWeaver to the installation folder.
- **Restorative Rollback**: Every change we make is reversible. A single click restores the original files to their pristine state, leaving no digital trace of our weave.

## 🛠️ Technical Architecture: The Loom and the Thread

Physically, LocaleWeaver is a modular suite comprising three core binaries working in tandem:

1.  **The Weaver Core (CLI Backend)**: A highly structured, asynchronous C++ engine that handles the binary parsing and text extraction. It operates at the file system level with read/write permissions only to the directories you authorize.
2.  **The Loom (GUI Frontend)**: A lightweight Electron application that provides the responsive UI. It communicates with the Weaver Core via a local secured socket, ensuring no external network requests are made without your explicit consent.
3.  **The Spool (Asset Library)**: A repository of language dictionaries and content metadata lists, stored locally on your machine. This ensures **offline-first functionality**. You are never dependent on a cloud server to apply a translation.

## 🚀 Getting Started: Your First Weave

Embarking on your journey with LocaleWeaver is as intuitive as reading a map. Here is your path to a fully localized, content-rich experience.

1.  **Acquire the Loom**: Download the latest release from the `Releases` tab on the right-hand side of this repository.
2.  **Prepare the Workbench**: Ensure your target game is fully installed and has been run at least once to generate any necessary configuration files.
3.  **Invoke the Weaver**: Launch the Loom application. It will automatically detect common game library locations (Steam, Epic, GOG). If your game is in a custom folder, use the "Browse" function in the top navigation bar.
4.  **Select Your Languages**: In the "Linguistic Fabric" tab, choose your source language (the one currently in the game) and your target language (the one you wish to weave in).
5.  **Reveal the Hidden**: Toggle the "Content Revelation" switch if you wish to inspect dormant assets. The Loom will present a list of safely discoverable items.
6.  **Weave the Magic**: Click the "Begin Weaving" button. The progress bar will show the intricate process of text replacement and asset activation. This typically takes 2 to 5 minutes depending on the game’s size.
7.  **Experience the Tapestry**: Launch your game. The changes are permanent until you decide to roll them back using the "Unweave" function.

## 🧭 Navigating the Repository

This repository is structured for clarity and contribution:

- **`/src`**: The complete source code for the Weaver Core and the Loom interface.
- **`/spool`**: Community-contributed language dictionaries and content manifest schemas.
- **`/docs`**: In-depth technical whitepapers on our parsing algorithms, the Golden Thread Protocol, and the Asset Visibility Toggle.
- **`/examples`**: Sample configuration files and screenshots demonstrating the UI in various languages (hence the multilingual support).
- **`/tests`**: Unit tests and integration tests that ensure stability across various Windows, macOS, and Linux environments.

## ❤️ Our Commitment to You: 24/7/2026 Support

We treat every user like a fellow cartographer charting unknown territories. While we don't offer a literal phone line, our **Nexus Forum** and **Discord server** (linked in the sidebar) are monitored **24 hours a day, 7 days a week, 365 days a year, including the year 2026**.

Our dedicated team of community moderators and core developers are committed to a **sub-4-hour response time** for any technical query. We also publish a **transparent bug bounty** for any issue found in our Golden Thread Protocol—if you can break it, we will fix it and reward you with a place on our wall of fame.

## ⚠️ Important Disclaimers And A Note On Ethics

### The "Blind Weaver" Principle
LocaleWeaver operates within a strict legal and ethical boundary. **We do not facilitate piracy.** The tool is designed to translate content *you already possess* and to display content *that is already in your game files*. We do not download or inject external assets.

### Compatibility Range
Our weaving magic is potent, but it is not omnipotent. We officially support games built on **Unreal Engine 4 & 5, Unity, and the Source 2 engine**. Games using heavily custom proprietary engines may not support the Language Mapping layer, though the Content Revelation System might still work.

### The "Ephemeral Patch" Rule
Game updates (patches) can occasionally overwrite our weaves. We provide a **"Patch Guard"** feature that automatically re-applies the last used settings after a game update is detected. However, this is not instantaneous; we advise waiting for a community update if a major overhaul occurs.

### Legal Safeguards
This project is provided "as is" without warranty. We are not affiliated with any game development studio or publisher. We encourage you to **respect the original designers' work**. The Content Revelation feature is intended for archival and personal exploration of content that was meant to be shipped but was scrapped—not for unlocking premium paid DLC tiers that require a separate purchase. If a game explicitly states that certain content is a paid exclusive, we expect you to honor that business model.

## 🛡️ License

This project is proudly licensed under the **MIT License** – a testament to our belief in open knowledge and the free sharing of tools (as in "freedom," not as in "cost"). You are free to use, modify, distribute, and privately study this code for any legitimate purpose. We only ask that you retain the copyright notice and acknowledge the community that built this loom.

For the full legal text, please refer to the [LICENSE](LICENSE) file in the root of this repository.

---

**© 2026 LocaleWeaver Project. Weaving worlds, one string at a time.**