# My MacroPad Project

This is custom 3×3 macropad PCB built with KiCad. It runs with Seeed Studio XIAO RP2040 microcontroller, uses Cherry MX switches and t has RGB lights with SK6812 MINI-E LEDs.

## About This Project

I have done PCB design before, but I wanted to do something more hard like adding MCU, RGB LEDs, and a matrix connection. 
I learned key matrix wiring with diodes, level-shifting logic with the 74AHCT125 processor, PCB routing around an MCU and KiCad in general. 
Also I learned a lot from MarkDown syntax.
I will use this for switching apps, custom scripts in some apps like VsCode for pushing new code to github etc...
The routing was pretty easy, just time consuming but I really enjoed making traces.

## 📁 Project Structure

- **[KiCAD_project/](KiCAD_project/)** 
  - `KiCAD_project.kicad_pcb` 
  - `KiCAD_project.kicad_sch` 
  - `KiCAD_project.kicad_pro` 
  - **[output/](KiCAD_project/output/)** 
  - **[OPL_Kicad_Library-master/](KiCAD_project/OPL_Kicad_Library-master/)**
  - **[kicad-libraries-master/](KiCAD_project/kicad-libraries-master/)** 
  - **[kicad_care_package/](KiCAD_project/kicad_care_package/)** 
  - **[KiCAD_project-backups/](KiCAD_project/KiCAD_project-backups/)** 

- **[CAD/](CAD/)** 
  - `3d_PCB.step` 
  - `housing.stl` 
  - `pcb_only.stl` 
  - `With-PCB_for-render.stl` 
  - `Seeed Studio XIAO RP2040.stl` 
  - **[blender/](CAD/blender/)** 

- **[KiCAD_project/My macroPad-bom.csv](KiCAD_project/My%20macroPad-bom.csv)** - BOM

## Design images

### Schematic
![Schematic](schematic.png)

### PCB Layout
![PCB Layout](pcb_kicad.png)

### 3D Renderings

#### Rendered PCB
![Rendered PCB](rendered_pcb.png)

#### PCB without rendering
![Non-rendered PCB](not_rendered_pcb.png)

#### Rendered Housing for PCB
![Rendered CAD](CAD/blender/rendered_CAD.png)

#### Housing for PCB (screenshot from fusion360)
![Rendered CAD](CAD/blender/not_rendered_CAD.png)

Project Link: https://stasis.hackclub.com/dashboard/projects/cmosrdxum001301mxc1tzjn15

## Bill of Materials

| Component | Purpose | Qty | Total | Distributor |
| :--- | :--- | :---: | :---: | :--- |
| PCB | Board to solder all components on | 1 | ~$1.40 | JLCPCB |
| Cherry MX Switches | Key switches | 10 | ~$3.00 | AliExpress |
| Capacitor 0.47 µF 0603 | Prevents LED flicker on voltage spikes | 10 | ~$0.50 | Farnell |
| Diode 1N4148 | Key matrix diodes for preventing ghosting | 10 | ~$2.15 | Farnell |
| SN74AHCT125N | Voltage level-shifter for RGB LED | 1 | ~$0.90 | Farnell |
| SK6812 MINI-E | RGB LED | 1 | ~$2.40 | AliExpress |
| Seeed Studio XIAO RP2040 | Main microcontroller | 1 | ~$4.80 | Farnell |

