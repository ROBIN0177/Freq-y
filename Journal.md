# RF Signal Scanner — Build Journal

*Third project so far. Not super comfortable with advanced calculations yet, but here we are.*

---

## DEVLOG 1 - Component Selection & Datasheet Review

Opened KiCad and laid out all the major components: TPS4056, USB-C, nRF24L01+, CC1101, and supporting passives. Read through every datasheet and took notes for this project's requirements.
<img width="596" height="602" alt="image" src="https://github.com/user-attachments/assets/b7574e47-2c54-4e9c-9320-df2f514dcf29" />
(changed some chips due to availability)
**Time: 2.3 hrs**

---

## DEVLOG 2 — Schematic

Schematic work was straightforward. Main challenge was real estate, I was missing space,  bumped the page size and got too much dead space, kept it tight and had to cram things in. Settled with smaller size.
<img width="1036" height="695" alt="image" src="https://github.com/user-attachments/assets/f25ad918-c2ee-4ad9-9525-8ab6565439c5" />

**Time: 4.1 hrs**

---

## DEVLOG 3 —  Case Design

Decided to nail the case dimensions before locking the PCB size. Sourced the display on Amazon, settled on 6 mm side bezels for clean proportions, thick enough to look intentional, thin enough to stay stable. Added walls, cutouts, etc.
<img width="1918" height="1030" alt="image" src="https://github.com/user-attachments/assets/9bd20872-e457-4a31-83ae-087b7f25b12f" />

**Time: 1.2 hrs**

---

## DEVLOG 4 — PCB Layout & Routing

With the Case fixed, routed the board. Grouped RF components tight to keep traces short. Trace widths aren't textbook RF-grade, but the target range is ~3 m radius so the margin holds. Layout iterations took a while finding the right component placement was a PAIN.
<img width="725" height="514" alt="image" src="https://github.com/user-attachments/assets/b0183b4c-13c5-4fc2-a077-f76fe2f61a03" />

**Time: 8.7 hrs**

---

## DEVLOG 5 — Renders

Exported the STL into Blender for final shots. Lighting setup got weird, a red shadow artifact kept showing up no matter what. Couldn't track it down, but the renders still came out clean. Project looks sigma.
<img width="522" height="249" alt="image" src="https://github.com/user-attachments/assets/a6cb29af-264b-4334-b476-6ca1ffffd949" />

**Time: 2.0 hrs**

---

### TOTAL TIME: 18.3 HOURS

(plz approve, lolol)
