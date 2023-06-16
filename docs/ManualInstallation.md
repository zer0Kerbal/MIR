---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.3.0
MIR (Мир)
created: 01 Oct 2019
updated: 16 Jun 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->
## [MIR (Мир)][mod]

[Home](./index.md)

Мир (MIR) Space Station for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `MIR` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/BobCat/SovietPack/MIR`
* Extract the package's `BobCat/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/BobCat` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/BobCat/SovietPack/MIR`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/BobCat/SovietPack/MIR`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/BobCat/SovietPack/MIR`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [BobCat]
      + [Agencies]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [SovietPack]
        + [MIR]
          + [Assets]
            ...
          + [Compatibility]
            ...
          + [Config]
            ...
          + [Localization]
            ...
          + [Parts]
            ...
          + [Props]
            ...
          + [Spaces]
            ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-ND-4.0+ARR.txt
      * changelog.md
      * ManualInstallation.htm
      * MIR.version
      * readme.htm
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [BobCat Industries (BOB)](https://www.curseforge.com/kerbal/ksp-mods/BobCatInd)

THIS FILE: CC BY-ND 4.0 by zer0Kerbal
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/Mir "MIR (Мир)"
