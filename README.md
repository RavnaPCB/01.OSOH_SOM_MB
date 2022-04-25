## ReadME

    STM32MP157 SOM [DBSTM32MP1]               - [Work In Progress]
    
    STM32MP157 Motherboard [MB10080_STM32MP1] - [Work In Progress]
    
## Introduction

I started this project a few months ago, in order to learn PCB Design, and deepen my electronics knowledge, with the intention to eventually publicly release the development files, so other people could learn from them and my mistakes, and maybe at some point, after all the issues are sorted out - use as a reference.

## Future Plans

> Develop a series of robust [OpenHardware] Systems On Module [SOM], Motherboards and Single Board Computers [SBC] capable of operating in the industrial temperature range, accompanied by detailed circuit explanations, spreadsheets, simulations and repair manuals.

## Software Requirements [OpenSource]

[KiCAD](https://www.kicad.org/) - A Cross Platform and Open Source Electronics Design Automation Suite

[LibreOFFICE](https://www.libreoffice.org)  - Office Suite

[FreeCAD](https://www.freecadweb.org/)  - 3D Parametric Modeler

[FEMM](https://www.femm.info/wiki/Download) - Finite Element Method Magnetics

[CommonLIB](https://github.com/IvanIlievOSOH/00.CommonLIB) - Custom KiCAD Library

## Knows Issues, Flaws and Quirks [Detailed Descriptions in the 'Issues' Tab]

> The components I picked are not the best ones currently in production, nor the most suitable ones, but when i started this project a few months ago, I had the intention to have the PCBs manufactured and assembled, so I had to work with what was available on Mouser and Digikey.

> There are some things that don't make much sense at first glance (unused pads, holes in the solder mask, unnecessary components and copper pours etc). Most are there intentionaly because i wanted to do some measurements and experiments with the PCBs in order to prove some rules and concepts to myself.

> There are also a few, but very obvious and probably critical "SI" and "PI" issues (Dual Stripline traces running parallel to eachother longer than they should, one of the eMMC Flash power rails routed as a relatively narrow trace on an outside layer etc.)

> Potential "Thombstoning" problems during reflow soldering.

> In hindsight, most of the issues and mistakes could have easily been avoided at an earlier stage of the design, if more research was done, but I decided to upload it now, as a [Work In Progress], so i can hopefully get some constructive criticism and suggestoins before I start redesigning the board.

    All your feedback, cirticism, help and suggestions will be greatly appreciated.

![](https://github.com/IvanIlievOSOH/00.GitHUB_Config/blob/main/Showcase.png)
