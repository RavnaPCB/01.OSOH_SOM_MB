## ReadME

    STM32MP157 SOM [DBSTM32MP1]               - [Work In Progress]
    
    STM32MP157 Motherboard [MB10080_STM32MP1] - [Work In Progress]
    
## Introduction

I started this project a few months ago, in order to learn PCB Design, and deepen my knowledge in electronics, with the intention to eventually publicly release the development files, so other people could learn from them and my mistakes, and maybe at some point, after all the issues are sorted out - use it as a reference.

A detailed explanation of how each circuit works and why things are connected and routed the way they are will be included at some point in the future.

## Future Plans

Development of different, robust [Open Hardware] SOM Modules, Motherboards and SBCs capable of operating in the industrial temperature range.

## Software Requirements [OpenSource]

[KiCAD](https://www.kicad.org/) - A Cross Platform and Open Source Electronics Design Automation Suite

[LibreOFFICE](https://www.libreoffice.org)  - Office Suite

[FreeCAD](https://www.freecadweb.org/)  - 3D Parametric Modeler

[FEMM](https://www.femm.info/wiki/Download) - Finite Element Method Magnetics

[CommonLIB](https://github.com/IvanIlievOSOH/00.CommonLIB) - Custom KiCAD Library

## Knows Issues, Flaws and Quirks 

> The components i picked are not the best ones currently "in production" nor the most suitable ones, but when i started this project a few months ago, i had the intention to have the PCBs manufactured and assembled, so i had to work with what was available on Mouser and Digikey.

> There are some things that don't make much sense at first glance (unused pads, holes in the solder mask, unnecessary components etc). This was done because i wanted to do some measurements and experiments with the PCBs so i can prove some rules and concepts to me.

> There are also a few but very obvious and probably critical "SI" and "PI" issues (Dual Stripline traces running parallel to eachother longer than they should, one of the eMMC Flash power rails routed as a relatively narrow trace on an outside layer etc.)

> Potential "Thombstoning" problems during reflow soldering.

> In hindsight, most of the issues and mistakes could have been avoided (at least the most noticeable ones) if i did more research and prepared better before i started routing the PCB. 

    All your feedback, cirticism and recommendations will be greatly appreciated.

![](https://github.com/IvanIlievOSOH/00.GitHUB_Config/blob/main/Showcase.png)
