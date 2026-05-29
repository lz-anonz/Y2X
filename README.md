# Y2eXploit (Y2X)

<div align="center">

## A streamlined autoloader framework for Y2JB-based payload execution workflows

Built by **LZ**

</div>

---

## Overview

**Y2eXploit (Y2X)** is a lightweight autoloader framework designed to simplify and organize payload execution within the Y2JB ecosystem.

It provides a structured workflow for chaining and managing exploit-stage payloads including **P2JB + Lapse integration support**, improving reliability, timing control, and execution flow for advanced users working in PS5 userland research environments.

This project is a community-oriented utility built to enhance usability around existing exploit frameworks, not to replace or recreate them.

---

## Features

- Clean autoloader execution structure for Y2JB environments  
- Payload sequencing and timing control system  
- Support for **Lapse-based userland initialization flows**  
- Integration-ready structure for **P2JB chain execution stages**  
- Multi-file payload management (.js / .elf / .bin)  
- Lightweight and modular loader design  
- Built for experimentation, testing, and research workflows  

---

## How It Works

Y2X follows a simple staged execution model:

1. Y2JB environment initializes userland entry point  
2. Y2X loads a defined payload sequence (`autoload.txt`)  
3. Lapse-based payload stage prepares runtime conditions  
4. P2JB chain stage executes where compatible  
5. Additional payloads are dispatched in order:
   - Kernel-stage payloads  
   - ELF loaders  
   - Post-exploit utilities or tools  

---

## Screenshots

![Main UI](screenshots/main.png)

---

## Installation

### Download from Releases

Place files into your Y2JB-compatible environment and ensure correct payload order is configured in `autoload.txt`.

---

## Project Purpose

This project was created to improve structure and usability around payload execution workflows in the Y2JB ecosystem.

It is not intended to replace existing exploit research projects, but to act as a **utility layer that improves workflow clarity, timing control, and payload management**.

---

## Credits & Acknowledgements

This project builds on the foundational work and research contributions from many developers in the PS5 security and homebrew community.

### Core Contributions

- **Gezine**  
  Creator of the Y2JB framework and foundational Lapse ecosystem work

- **itsPLK**  
  Contributions to autoloader concepts and payload workflow structuring

- **abc / psfree contributors**  
  Research and development work related to Lapse and exploit chain improvements

- **TheFlow**  
  Low-level vulnerability research that enabled modern exploit development

- **EchoStretch / john-tornblom**  
  ELF loading tools, debugging utilities, and runtime execution research

- **PS5 Homebrew & Jailbreak Community**  
  Testing, validation, documentation, and continuous ecosystem support

---

## Disclaimer

This software is provided strictly for **educational and research purposes only**.

The developer does not promote or encourage piracy, system abuse, or unauthorized modification of commercial devices.

Users are fully responsible for compliance with applicable laws and regulations in their region.

No liability is assumed for damage, data loss, bans, or system instability.

---

## Contributing

Contributions, improvements, and suggestions are welcome.

To contribute:

1. Fork the repository  
2. Create a feature branch  
3. Commit your changes  
4. Submit a pull request  
