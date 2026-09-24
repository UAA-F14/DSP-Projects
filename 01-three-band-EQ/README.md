# Three Band EQ 

A didactic board for triggering SCRs/thyristors — a phase-control firing circuit built for a power electronics course.

## Directory structure
```
├── design
│   ├── KicadDesign
│   │   ├── Design.kicad_pcb
│   │   ├── Design.kicad_pro
│   │   ├── Design.kicad_sch
│   └── Schematic.pdf
├── doc
│   ├── AC
│   ├── ConfigAC.tex
│   ├── Examen1.pdf
│   ├── Examen1.tex
│   └── Tarjeta didáctica de control para tiristores.pdf
├── README.md
├── src
│   └── render.png
├── sim
│   └── EQ.asc
```

- `SCRController.kicad_sch` / `.kicad_pcb` / `.kicad_pro` — KiCad design
- `SCRController.step` — 3D model
- `Tarjeta didáctica de control para tiristores.pdf` — design writeup
- `simulation.asc.txt` — LTspice simulation


![3D render](src/render.png)

**Photos of the built board — coming soon**

## Files

## Credit
Built as coursework with [DasReyxr](https://github.com/DasReyxr)  and [Kevin Lara](https://github.com/Gyonyu) 


## Template
```
mkdir code design doc scripts sim src
```

```
tree >> README.md
```

