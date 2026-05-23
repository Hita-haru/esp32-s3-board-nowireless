---
title: "ESP32-S3-board-nowireless"
author: "ひらさわ"
description: "This is ESP32-S3 devboard"
created_at: "2026-05-20"
---

# 5/20: Created project and designed schematic
I Created project and Kicad files.
I’ve drawn up a schematic as well. At first, I was thinking of using WROOM, but since the versions with Technical Conformity Mark are expensive, I’ve decided to just use the chip on its own.

![schematic](./screenshots/schematic1.png)
**Total time spent: 4 hours**

# 5/22: Set up git and added crystal oscillator and so on
I set up GitHub.
I also added a crystal oscillator and modified the USB connector.
Unfortunately, there wasn’t much documentation available, so I ended up spending quite a bit of time searching for information.

![Github](./screenshots/github.png)
![Schematic](./screenshots/schematic2.png)
**Total time spent: 5 hours**

# 5/23: Added flash memory and PSRAM to the schematic
I added flash memory and PSRAM to the circuit diagram.
As usual, there was no detailed documentation, so I added them while referring to the Blueprint's guide.
Other than that, I just added a connector for attaching a camera.
It took me forever to find the documentation, so it was a real hassle.

![Schematic](./screenshots/schematic3.png)
**Total time spent: 4 hours**