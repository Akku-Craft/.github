# Contributing to Akku-Craft

> [!TIP]
> Do you prefer the web version? Visit [https://akku-craft.usbverkehrtherum.de/contributing](https://akku-craft.usbverkehrtherum.de/contributing).

Thanks for your interest in contributing. Akku-Craft is a small project, and outside help genuinely makes a difference — whether you're into embedded systems, web development, PCB design, or CAD.

> [!NOTE]
> This is a brief overview. For detailed contribution guidelines, check the `CONTRIBUTING.md` in the relevant repository.

---

### Before anything else: read the wiki

Please do this before diving into any repository. The wiki explains the architecture, design decisions, and conventions that keep everything consistent. Skipping it tends to create more back-and-forth later.

[Akku-Craft Wiki](https://akku-craft.usbverkehrtherum.de/wiki)

---

### How to get in touch

The easiest way is via **Discord**. Message either:

* **jumpstone4477** (preferred)
* **akku_craft**

If Discord doesn't work for you, send an email to us via the Contact page. 

Either way, please mention which area you'd like to work on when you reach out. It helps us point you in the right direction straight away.

---

### Areas of contribution

#### Firmware
**Repository:** [Akku-Craft/ArduinoBms](https://github.com/Akku-Craft/ArduinoBms)

The brain of the system. We work primarily in **C++**, with some C where it makes sense.
* Arduino / PlatformIO environment
* Real-time BMS logic (SoC, SoH, protection circuits)
* I²C / CAN communication

*A good fit if you're comfortable with embedded C++ and want to work close to the hardware.*

#### Website
**Repository:** [Akku-Craft/website](https://github.com/Akku-Craft/website)

Probably the most accessible entry point, especially if you're new to the project and don't have a hardware background.
* Next.js + TypeScript
* UI improvements, content, and documentation pages

#### Schematics
**Repository:** [Akku-Craft/schematics](https://github.com/Akku-Craft/schematics)

Right now, the focus here is on cleanup and optimization rather than new features. If you have experience with PCB design and enjoy making things tidy and correct, this is where you'd fit in.
* KiCad (or compatible tooling)
* Improving layout, annotations, and overall readability

#### 3D Models
**Repository:** [Akku-Craft/3d-models](https://github.com/Akku-Craft/3d-models)

Enclosure design built around FDM printing. If you're into CAD and care about parts that actually assemble cleanly, we'd be happy to have you.
* PETG / ASA / ABS preferred for functional builds
* Thermal management and assembly ergonomics are the main concerns

---

### One last thing

Akku-Craft is intentionally scoped. We're not trying to do everything — we're trying to do a few things well. If you're unsure whether something fits, just ask before building it.

We look forward to hearing from you.

— *The Akku-Craft Team*
