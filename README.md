
# Freq-y
## Your Frequency Scanning Companion

I made this project because there isn't a cheap frequency scanner you can rely on. If you've built RF projects before, you know the pain of tracking down a signal leak, figuring out where it's coming from, what frequency it's on, and which device is causing it.

I ran into this myself: my home WiFi was getting choked by an unknown source. Turned out to be my own custom radio bleeding into the band. This scanner also lets you test how much shielding a material actually provides—whether it's a wall, a case, or a Faraday cage. Pinpoint the exact device causing interference easily. (Unlike me. Took 3 days to figure out..)

---

## Pictures

<img width="534" height="807" alt="image" src="https://github.com/user-attachments/assets/13d776fc-909e-48b5-b5d1-63939beea2ec" />
<img width="920" height="347" alt="image" src="https://github.com/user-attachments/assets/4e65b55f-bd80-4810-b277-7c6d4dc15992" />
<img width="651" height="357" alt="image" src="https://github.com/user-attachments/assets/4ab2ca17-c8d9-4f11-a4bb-46dc5f9d709d" />
(Mind the hole, it's for a rocker switch I couldn't get a STL of.)

<img width="576" height="780" alt="image" src="https://github.com/user-attachments/assets/8f7ba3e4-a7f1-468b-9ff9-a523ee3f16a5" />
<img width="749" height="843" alt="image" src="https://github.com/user-attachments/assets/5c224a7a-d414-4ab0-85f6-43f12bcb1e2a" />
<img width="1005" height="702" alt="image" src="https://github.com/user-attachments/assets/f81061be-d317-4d6e-ab74-329f72813cb4" />

---

## BOM

Full BOM with DigiKey part numbers: see `/BOM/`

---

## File Structure

```
Freq-y/
├── CAD/
│   ├── enclosure_top.stl
│   └── enclosure_bottom.stl
├── PCB/
│   ├── Freq-y_Schem
|   ├── Freq-y_PCB
│   └── Freq-y_Pro
├── GERBER/
│   ├── Freq-y-B_Cu.gbr
│   ├── Freq-y-F_Cu.gbr
│   ├── Freq-y-B_Mask.gbr
│   ├── Freq-y-F_Mask.gbr
│   ├── Freq-y-B_Silkscreen.gbr
│   ├── Freq-y-F_Silkscreen.gbr
│   ├── Freq-y-Edge_Cuts.gbr
│   ├── Freq-y-B_Paste.gbr
│   ├── Freq-y-F_Paste.gbr
│   ├── Freq-y-NPTH.drl
│   ├── Freq-y-PTH.drl
│   └── Freq-y.zip
├── BOM/
│   ├── BOM_DigiKey.csv
│   └── BOM_AUX.csv
├── README.md
├── Journal.md
└── LICENSE
```

---

## Special Thanks

**Hack Club** — I couldn't have made this without it.


## NOTE

RF impedance was calculated to the nearest allowed mm. Any more would have severed and or created problems for other components!!
Range is limited due to it not having exact RF impedance!!
