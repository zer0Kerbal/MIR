---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- 
hdr-changelog.md v1.0.0.0
MIR (Мир)
created: 13 May 2022
updated: 15 Apr 2023
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | MIR (Мир)                                                         |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-4.0+ARR                                                  |
| author     | BobCat, DECQ, Dragon01, Sampa and zer0Kerbal                      |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209731-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/MIR)                    |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/MIR)                  |
| spacedock  | (https://spacedock.info/mod/3115)                                 |
| ckan       | MIR                                                               |

* 📌 Pinned
  * Dependency
    * [BobCat Industries (BOB)](https://www.curseforge.com/kerbal/ksp-mods/BobCatInd)

## Version 4.0.99.3-prerelease `<Спасибо evanisrael>` edition

* Released
  * 16 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [sampa](https://github.com/Toa-Sampa) and [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 4.0.99.3

* Add
  * Мир (MIR) Assembly guide (pages)
  * Snacks compatibility (rough guess at amounts)
* Localize
  * ![Russian (Русский)](https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/RU.png) Russian (Русский)
  * Спасибо [evanisrael](https://github/evanisrael)
* Corrected part name (added to ghostparts)
  * [mir-core] was [мir-core] - notice the Cyrillic `м` snuck in
* Kerbalnauts did precarious day long (6 hour) spacewalk to repair all three types of solar panels. Snacks! for everyone!
* scolded several hiding textures and put their name tags back on

#### Assets 4.0.99.3

* KSP reporting missing textures
  * scolded the hiding textures and put their name tags back on
  * [TKS-m001_NRM] was hiding as [TKS-m001]
  * [TKS-m003_NRM] was hiding as [TKS-m003]
* updates #62 - [BUG][LOG] missing NRM textures

#### Parts 4.0.99.3

* Corrected part name
  * [mir-core] was [мir-core] - notice that the Cyrillic `м` snuck in
  * added [мir-core] to ghostparts
* Solar Panels not generating ElectricCharge when open
  * Kerbalnauts did precarious day long (6 hour) spacewalk to repair all three types of solar panels. Snacks! for everyone!
  * [mir-solar-top.cfg]
    * attachment nodes
  * [mir-kvant-solar.cfg]
    * attachment nodes
  * [mir-solar.cfg]
    * attachment nodes
* closes #69 - [BUG] Solar Panels not generating ElectricCharge
* closes #70 - [BUG] mir-core not showing when searching 'mir' in editor

#### Compatibility 4.0.99.3

* ADD
  * NEW: Snacks compatibility
  * resource amounts are rough guess at amounts - kindly submit changes via GitHub
  * [Snacks.cfg] v1.0.0.0
    * 500 snacks
      * Mir-core
    * 150 snacks
      * mir-kvant-1v
      * mir-tks-kristall-1
      * mir-tks-kvant-2v
      * mir-tks-spektr
      * mir-tks-tug
      * mir-tks-zarya

#### Localization 4.0.99.3

* Add
  * Russian (Русский)
    * [ru.cfg] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
  Translation guides
    * [readme-ru.md] v1.0.1.0
    * [quickstart-ru.md] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
* Update
  * [ru.cfg] v1.0.1.0
  * add header, give credit
* closes #20 - Russian (Русский) <ru.cfg>
* updates #12 - Localization - Master

#### Documentation 4.0.99.3

* Update
  * [404.md] v1.0.3.0
  * [Assembly.md] v1.0.3.0
  * [Attributions.md] v1.0.3.0
  * [LegalMumboJumbo.md] v1.0.3.0
  * [Localizations.md] v1.0.3.0
  * [ManualInstallation.md] v1.0.3.0
  * [Marketing.md] v1.0.3.0
  * [Notices.md] v1.0.3.0
  * [readme.md] v4.0.99.3
  * [Why.md] v1.0.3.0
* Мир (MIR) Assembly guides
  * renamed [Assembly-Mir-en-us.html] --> [Assembly-Mir-en.html]
  * added [Assembly-Mir-ru.html]

### Status 4.0.99.3

* Issues
  * closes #65 - Мир (MIR) 4.0.99.3-prerelease `<Спасибо evanisrael>` edition
  * closes #66 - 4.0.99.3 Additional Tasks

---

## Version 4.0.99.2-prerelease `<Gracias Fitiales>` edition

* Released
  * 06 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [sampa](https://github.com/Toa-Sampa) and [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 4.0.99.2

* Adjust attachment nodes
* Add localization: Spanish (Español) - Gracias [Fitiales](https://github.com/Fitiales)
* [BUG] Solar panels are animated, but not generating EC
* update documentation

### Changes 4.0.99.2

#### Parts 4.0.99.2

* Adjust attachment nodes
  * [mir-core] v4.0.99.2
    * ModuleInventoryPart - added 3/180 (cramped)
  * [mir-dockingmodule-1] v4.0.99.2
  * [mir-tks-kristall-1] v4.0.99.2
  * [mir-tks-kvant-2v] v4.0.99.2
  * [mir-tks-priroda] v4.0.99.2
  * [mir-tks-spektr] v4.0.99.2
  * [mir-tks-tug] v4.0.99.2
  * [mir-tks-zarya] v4.0.99.2
  * thank you to [Sampa](https://github.com/Toa-Sampa)
* mir-tks-tug
  * change [vesselType] from Ship to Probe
  * add [CrewCapacity] = 0
* [BUG] Solar panels not generating
  * [mir-kvant-solar.cfg] v4.0.99.2
  * [mir-solar.cfg] v4.0.99.2
  * [mir-solar-top.cfg] v4.0.99.2
  * updates #58 - Mir Solar Panels not drawing any power

#### Localization 4.0.99.2

* Add
  * Spanish (Español)
    * [es-es.cfg] v1.0.0.0
    * Gracias [Fitiales](https://github.com/Fitiales)
* Update
  * [es-es.cfg] v1.0.1.0
  * add header, give credit
* closes #16 - Spanish (Español) <es-es.cfg>
* updates #12 - Localization - Master

#### Documentation 4.0.99.2

* Update
  * [readme.md] v4.0.99.2
  * [Attributions.md] v1.0.8.0
  * [LegalMumboJumbo.md] v1.3.0.0
  * [Localizations.md] v1.0.8.0
  * [ManualInstallation.md] v1.0.9.0
  * [PartsCatalog.md] v1.0.5.0

* Issues
  * closes #51 - Мир (MIR) 4.0.99.2-prerelease `<Gracias Fitiales>` edition
  * closes #52 - 4.0.99.2 Additional Tasks
  * closes #48 - Update RealismOverhaul patch

---

## Version 4.0.99.1-prerelease `<Спасибо Сампа>` edition

* Released
  * 13 May 2023
  * for Kerbal Space Program 1.12.5
  * by [sampa](https://github.com/Toa-Sampa) and [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 4.0.99.1

* BUG
  * Drogue and Probe not docking
    * Have sat the three parts with [ModuleDockingNode] down and had *'the talk'* with them.
    * (drogue) was set to True/True - now True/True
    * (probe) was set to False/True - now True/False
    * Спасибо, Сампа! (Spasibo, Sampa!) to [Sampa](https://github.com/Toa-Sampa)

### Changes 4.0.99.1

* Issues
  * closes #45 - Мир (MIR) 4.0.99.1-prerelease `<Thank you BobCat, DECQ, and Dragon01>` edition
  * closes #46 - 4.0.99.1 Additional Tasks
  * closes #53 - Probe and Drogue Docking ports fail to dock

---

## Version 4.0.99.0-adoption `<Thank you BobCat, DECQ, and Dragon01>` edition

* Released
  * 20 Apr 2023
  * for Kerbal Space Program 1.12.5
  * by [sampa](https://github.com/Toa-Sampa) and [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 4.0.99.0

* Dependency
  * [BobCat Industries (BOB)](https://www.curseforge.com/kerbal/ksp-mods/BobCatInd)
* fully localized
* ghostparts 2.0
* MIR core mass reduced. (0.4968823529%)

### Changes 4.0.99.0

* Issues
  * closes #1 - Мир (MIR) 4.0.99.0-adoption `<Thank you BobCat, DECQ, and Dragon01>`
  * closes #2 - 4.0.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 4.0.99.0 Create Documentation
  * closes #4 - 4.0.99.0 Create Social Media Presence
  * closes #43 - Мир (MIR) 4.0.99.0-adoption `<Thank you BobCat, DECQ, and Dragon01>`
  * closes #5 - Create GitHub Pages
  * closes #6 - Create HeroLogo.png
  * closes #8 - Create Localization directory and contents
  * closes #9 - Part Asset Updates
  * closes #10 - Create MIR.cfg
  * closes #11 - Update License
  * closes #13 - English <us-en.cfg>
  * closes #30 - Part Localization
  * updates #12 - Localization - Master
  * updates #48 - Update RealismOverhaul patch

---

## Version 4.0.98.2-beta `<Beta 0>` edition

* 30 Sep 2022
* For Kerbal Space Program 1.12.3

### Summary 4.0.98.2-beta

* stock RCSFX working
* [WIP] docking port: (TKS drogue and probe) now gendered

* Known Issues
  * solar panels
    * not sun tracking
    * not generating EC
    * but they look good and the animations are awesome!
  * several parts use [ModuleEngines] instead of [ModuleEnginesFX]
  * reported shadow bugs on some of the components

### Changes

* Add
  * [DRAG_CUBES] to parts
* Update
  * <mir-rcs-block-1.cfg> v1.2.2.1
    * stock RCSFX working
  * <mir-tks-dock-probe.cfg> v1.2.0.1
    * docking port: male/gendered
  * <mir-tks-dock-drogue.cfg> v1.2.0.1
    * docking port: female/gendered
* Known Issues
  * EC not flowing
    * <mir-solar.cfg> v1.0.0.1
    * <mir-kvant-solar.cfg> v1.0.0.1
      * comment out [power curve] (test)

### Localization 4.0.98.2

* simplify localization ID's
  * from: #MIR-mir-*
  * to: #MIR-*
* updates #12 - Localization - Master
* updates #30 - Part Localization
* updates #13 - English <us-en.cfg>

### Status 4.0.98.2

* Issues
  * closes #35 - MIR (MIR) 4.0.98.0-alpha `<Alpha 0>`
  * closes #36 - MIR (MIR) 4.0.98.1-alpha `<Alpha 1>`
  * closes #40 - MIR (MIR) 4.0.98.2-beta `<Beta 0>`

---

## Version 4.0.98.1-alpha `<Alpha 1>` edition

* 18 Sep 2022
* For Kerbal Space Program 1.12.3

### Changes 4.0.98.1

### Rename 4.0.98.1

* Internal Part names should not change going forward
* <docs/PartsCatalog.md> v1.1.4.0 now shows all parts
* All parts have received initial
  * update pass
  * localization pass
  * asset pass
* <MIR.version>
  * removed [KSP_VERSION_MAX]
  * added SubAssemblies
* Files
  * <TKS_Zarya.cfg> --> <mir-tks-zarya.cfg> v1.2.0.0
  * <TKS_Kristall.cfg> --> <mir-tks-kristall.cfg> v1.2.0.0
  * <TKS_Kvant2.cfg> --> <mir-tks-kvant-2v.cfg> v1.2.0.0
  * <TKS_Priroda.cfg> --> <mir-tks-priroda.cfg> v1.2.0.0
  * <TKS_Spektr.cfg> --> <mir-tks-spektr.cfg> v1.2.0.0
  * <TKS_tug.cfg --> <mir-tks-tug.cfg> v1.2.0.0
  * <MirCap.cfg> --> <mir-tks-dock-cap.cfg> v1.2.0.0
  * <MirDrogue.cfg> --> <mir-tks-dock-drogue.cfg> v1.2.0.0
  * <MirProbe.cfg> --> <mir-tks-dock-probe.cfg> v1.2.0.0
* Parts
  * TKS_Zarya --> mir-tks-zarya
  * TKS_Kristall -->  mir-tks-kristall
  * TKS_Kvant2V --> mir-tks-kvant-2v
  * TKS_Priroda --> mir-tks-priroda
  * MIR_Spektr1 --> mir-tks-spektr
  * TKS_tug1 --> mir-tks-tug
  * Mir_DockingPortProbe1 --> mir-tks-dock-probe
  * Mir_DockingPortCoverCap1 --> mir-tks-dock-cap
  * Mir_DockingPortDrogue1 --> mir-tks-dock-drogue
* Models
  * <model.mu> --> <mir-core.mu>
  * <MIR_core.mu> --> <mir-core.mu>
  * <model.mu> --> <mir-rcs-block-1.mu>
  * <NewModel.mu> --> <mir-solar.mu.mu>
  * <MIR_solartop.mu> --> <mir-solar-top.mu>
  * <Kvant_core.mu> --> <mir-kvant.mu>
  * <Kvant_solar.mu> --> <mir-kvant-solar.mu>
* Textures
  * <model000.dds> --> <MIR-DP00.dds>
  * <model001.png> --> <MIR-DP01.png>
* IVA
  * Filename
    * <Internal.cfg> --> <MIR-TKS-internal.cfg>
  * actually deactivate Spaces/MIR-core-internal/PropConfig.cfg
  Name
    * MIR_TKS_internal --> MIR-TKS-internal
    * update pointers in six parts

### Split Out 4.0.98.1

* Update
  * <ECLSS.cfg>.cfg> v1.1.0.0

---

## Version 4.0.98.0-alpha `<Alpha 0>` edition

* 12 Sep 2022
* For Kerbal Space Program 1.12.3

### Changes 4.0.98.0

* Rename
  * File name
    * part.cfg --> mir-port-apas-1.cfg
    * part.cfg --> mir-dockingmodule-1.cfg
    * part.cfg --> mir-rcs-block-1.cfg
    * MIRCore.cfg --> mir-core.cfg
    * MIRSolarTop.cfg --> mir-solar-top.cfg
    * MIRSolar.cfg --> mir-solar.cfg
    * Kvant1.cfg --> mir-kvant-1v.cfg
    * KvantSolar --> mir-kvant-solar.cfg
  * Part Name
    * APASport1 --> mir-port-apas-1
    * Mir_RCS_ThrusterBlock1 --> mir-rcs-block-1
    * MIR_core --> mir-core
    * Kvant-1V --> mir-kvant-1v
    * Kvant_1_Solar_Panel1 --> mir-kvant-solar
  * Model name
    * model.mu --> mir-core
    * MIR_core.mu --> mir-core
    * model.mu --> mir-rcs-block-1
    * NewModel.mu --> mir-solar.mu
    * MIR_solartop.mu --> mir-solar-top.mu
    * Kvant_core --> mir-kvant.mu
    * Kvant_solar --> mir-kvant-solar.mu
  * Texture name
  * model000.dds --> apas-000
  * model001.dds --> apas-001
  * model000.dds --> mirrcs-0
  * model001.png --> mirrcs-1

### IVA 4.0.98.0

* Internal.cfg --> MIR-Core-Internal.cfg

### Split out 4.0.98.0

* Add
  * <ECLSS.cfg>
  * <KerbalAttachmentSystem.cfg>

---

## Version 4.0.0.0-release `<Archival>` edition

* 2014
* For Kerbal Space Program 1.0.5

* Last released by DECQ and Dragon01
* From BobCat Industries Soviet Pack

### Status 0.4.0.0

* Issues
  * closes #7 - Archival Releases
  * closes #31 - 4.0.0.0-release

---

## Version 1.5A

* Add-on MIR separated by ENERGIA folder.
* MIR has a different size and weight compared with the original work of Bobcat, also when  two versions they will not interfere with each other.

---

If we are able to recover release notes we will add them here (or below)

---
