# chonky-charger

> A simple, slow, but working charger for the Canon NB-11L camera battery

This project was made for the NB-11L battery from a camera a friend gave me. It came without a charger, so I made my own! It's really simple: you take a Seeed XIAO nRF and use the built-in LiPo charger, since the battery chemistry is compatible. The NB-11L is a single cell 3.7V battery, which is exactly what the XIAO can charge. I also reused the XIAO PCB from my old project [Scroll Dial](https://github.com/maker-lukas/scroll-dial), which didn't quite work out, but the PCB worked just well enough for this project with the battery pins exposed. The charger is pretty slow, but it does charge.

## BOM

| Part | Qty | Specification | Price | Link |
|------|-----|---------------|-------|------|
| Case | 1 | 3D printed (top + bottom) | N/A | N/A |
| Elastic band | 1 | Holds the battery in place | N/A | N/A |
| Screws | 2 | M2x5 flat head | N/A | N/A |
| MCU | 1 | Seeed XIAO nRF52840 | N/A | N/A |
| PCB | 1 | XIAO PCB from [Scroll Dial](https://github.com/maker-lukas/scroll-dial) | N/A | N/A |
| Female jumper cables | 2 | To connect the battery to the XIAO | N/A | N/A |
| Male pin headers | 4 pins | Battery contacts + PCB contacts | N/A | N/A |

See [BOM.csv](BOM.csv) for the full bill of materials.

## Images

| | | |
|---|---|---|
| ![Assembled charger](images/assembled.jpg) | ![Charging](images/charging.jpg) | ![Case](images/case.jpg) |
| Assembled charger | Charging in action | 3D printed case |

