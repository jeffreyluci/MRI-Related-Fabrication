# MRI Earbud Cups
CAD drawings, 3D printer files, and other resources for building cups that improve the applicability of some MRI-safe earbuds.

BACKGROUND
---
There are organizations that manufacture and sell MRI-safe earbuds for audio delivery to subjects undergojng research MRI scans. [Sensimetrics](https://www.sens.com/) is one such corporation that makes [earbuds](https://www.sens.com/products/earphones-for-fmri-research/) compatible with the unique demands and requirements of many research MRI projects. Earbuds like these use disposable fitted tips in order to maintain sanitary conditions and optimum comfort. Unfortunately, it is sometimes difficult to properly stabilize the head for brain imaging with standard pads without applying unneeded force on the earbuds and causing discomfort. These ear covers are designed to help alleviate that problem. The list of materials needed to fabricate your own set is included in the Fabrication section below.

DESIGN
---
Using off-the-shelf replacement hearing protection pads that mount to a custom designed, 3D printed “cup,” these units provide protection for the ear without forcing the earbuds deeper than desired. They simultaneously allow for more thorough head stabilization using padding without taking up excessive space in the head coil.

DISCLAIMER
---
It is important to note that the items provided in this repository are intended to be used solely for research purposes, and under expert supervision. No clinical exam should be undertaken using the designs, technology, workflow, scheme, or products derived from these in this repository. The author makes no claims as to the applicability or appropriateness of these things for any purpose or intention, and use of any of them are at the user’s own risk. There is no warranty, implied or expressed, for anything provided in this repository. The author accepts no liability and disclaims all responsibility for any consequences, damage, injury, and any other unintended or undesirable results of use.

It should be noted that although this design makes use of earpads and foam sheets that are designed to be used for OSHA-compliant hearing protection, they are not designed for, independently tested, or approved for hearing protection in THIS use case. As a result, NO degree of Sound Pressure Level (SPL) attenuation should be attributed to or expected from them when not used as originally intended by the manufacturer, and this use has NEVER been intended by the manufacturer.

DESCRIPTION
---
Standard replacement earmuff-type pads were selected for their low cost, wide availability, and ease & tolerance of frequent disinfection procedures. The base of the pad was used as a template for a shallow “cup” that receives the pad. The cup’s mounting surface provides vent holes that allow the pad’s own vents to efficiently vent air when compressed. The cup also accepts a think sheet of foam that is provided with the ear pads as a kit. Those sheets may be used at the discretion of the researcher and as appropriate. The padding may provide additional support and cushioning for the buds, but in some cases, it might be necessary to reclaim the space occupied by the sheets in order to optimize comfort.

![Sensimetrics earpiece rotation](https://user-images.githubusercontent.com/88209977/175659291-369d330f-c6dd-4837-ba26-13338add1deb.gif)

**Figure 1:** CAD drawing of earpiece cup.

![pad-and-cup-photo](https://user-images.githubusercontent.com/88209977/175659547-5c8f7f0e-4f65-4bb1-94fb-0721956c6f89.png)

**Figure 2:** Photo of both sides of the earpad and cup.

![full-assembly](https://user-images.githubusercontent.com/88209977/175659759-7a416f17-b744-468b-89f1-199c01a1b503.png)

**Figure 3:** Photo of Bottom of assembly showing cable access channel

FABRICATION. 
---
A Honeywell Howard Leight model 1030220 replacement earmuff pad kit was purchased from [Grainger, item# 6TUK9.](https://www.grainger.com/product/6TUK9?RIID=60078970355) A scan of the mating surface of one earpad was scanned, and imported into Autodesk Inventor 2022 Professional, and scaled to size. The base was traced, and the cup surface was built up from that model. The 3D model was exported to an STL file (included in this repository) and printed on a [formlabs Form3 resin 3D printer](https://formlabs.com/3d-printers/form-3/) using [standard draft white resin](https://formlabs.com/materials/standard/#color-kit) at 100um resolution. Two copies were printed simultaneously. The job took approximately 6.5 hours to complete. The parts were rinsed in isopropyl alcohol, and cured in a UV oven at 100°F (~38°C) for approximately 12 hours. After some finish sanding with 180 grit sandpaper, a channel was cut in the bottom of the cup to accomodate the earbud cable. (A 3D model of the cup with the channel incorporated was produced, but printing quality was adversely impacted, and removed as a consequence.) The foam sheets were installed using a pencil eraser to coax the foam into the corners of the cups. Using [3M Double-Sided Tape](https://www.3m.com/3M/en_US/p/d/cbgnhw011091/), the pads and cups were attached on the "top" of the cup only to allow for the pad to be lifted up and install the earbud cable as depicted in Figure 4 below. For most industrial applications, a stronger tape is usually employed. A good choice is [3M's VHB modelLSE-060WF](https://www.3m.com/3M/en_US/p/d/b5005036159/LSE-060WF). I elected not use VHB here to allow for ease of replacement. But, this is a personal choice, and either would be acceptable. The regular tape does not ha ve the bonding strength of VHB, but that is advantageous during replacement.


![installing-s14](https://user-images.githubusercontent.com/88209977/175664754-9d7387fa-b5f3-4bee-86d1-b1930cf99a01.png)

**Figure 4:** Photo showing the lift of the pad necessary to place the earbud in the cup. Note that the pad is only taped to the cup on the mating surface still in contact in this figure.

The completed assembly is comfortable, takes away minimal valuable space in the head coil, and effectively prevents the earbuds from being forced deeper int he ear than necessary or desirable.

![s14-installed](https://user-images.githubusercontent.com/88209977/175665172-3b697b32-b6f8-407d-8ea1-be2618a0f1b5.png)

**Figure 5:** Complete assembly of the cup & pad with a Sensimetrics S14 earbud installed.

LICENCE and TERMS of USE
---
All information contained in this repository is copyrighted by Jeffrey Luci, 2021. Jeffrey Luci grants non-exclusive, revocable license to use the information contained in this repository to all persons for non-commercial use, provided that works using information in this respository (including those that build upon, modify, or improve the design) in publication or presentation must reference this repository formally, in accordance with the accepted practices, procedures, and styles of the relevant publishing entity. ALL commercial use must be separately and individually licensed from Jeffrey Luci.

Jeffrey Luci reserves the right to modify, update, amend, append, expand, and revoke this and all subsequent licenses at any time and for any reason. Your use of any information held in this repository constitutes acceptance of these terms and the disclaimers that follow below.