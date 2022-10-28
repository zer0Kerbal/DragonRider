---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- 
hdr-changelog.md v1.0.0.0
Dragon Rider (DRAGR)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | Dragon Rider (DRAGR)                                              |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-3.0                                                      |
| author     | CardBoardBoxProcessor, MacLuky and zer0Kerbal                     |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/210281-*/) |
| github     | (https://github.com/zer0Kerbal/DragonRider)                       |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/DragonRider)          |
| spacedock  | (https://spacedock.info/mod/3140)                                 |
| ckan       | DragonRider                                                       |

## Version 0.9.99.1-prerelease `<Thank you CardBoardBoxProcessor and MacLuky>` edition

* Released
  * 27 Oct 2022
  * for Kerbal Space Program 1.12.3
  * by zer0Kerbal

## Summary 0.9.99.1

* Update, moderization, localization, and linting pass
* New Cover/Hero logo image

### Documentation 0.9.99.1

* Create
  * docs/
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
      * done
    * [Notices.md] v1.0.1.0
    * [Disclaimer.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
      * done
    * [Why.md] v1.1.0.0
  * closes #33 - Create GitHub Pages
  * closes #34 - Create HeroLogo.png
* Update
  * <DragonRider.version>
  * Remove [KSP_VERSION_MAX]
* Add
  * Hero.png
  * @thumbs/
    * add thumbnails
* closes #7 - Create HeroLogo.png
* closes #43 - Create Thumbs

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
    * model.mu --> Dragon*.mu
  * textures to unique names
    * model000.dds --> dragr-00.dds
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* updates #36 - Part Asset Updates

### ImgBot

* #1 - [ImgBot] Optimize images - contributed by imgbot[bot]

### Localization 0.9.99.1

* Localize parts
* Update Localization/
  * <en-us.cfg> v1.1.0.0
  * [readme.md] v2.1.2.0
  * [quickstart.md] v1.0.1.1
* updates #8 - Localization - Master
* closes #9 - English <us-en.cfg>
* closes #37 - Create <DragonRider.cfg>
* closes #35 - Create Localization directory and contents

### Parts 0.9.99.1

* Update pass
* header
* update
  * file name from <Dragon*.cfg> --> <dragr-*.cfg>
  * part name from Dragon* --> dragr-*
  * linting
  * localization

### Compatibility 0.9.99.1

* Update
  * <TacLifeSupport.cfg> v1.0.1.0
  * <CommunityTechTree.cfg> v1.0.1.0
  * <Kerbalism.cfg> v1.0.1.0
  * <Lazor.cfg> v1.0.1.0
  * <Mechjeb.cfg> v1.0.1.0

### Update License

* Updated License: CC BY-ND 3.0 US
  * was: CC BY-NC-ND 3.0 US
* closes #38 - Update License

### Status 0.9.99.1

* Issues
  * closes #29 - Dragon Rider (DRAGR) 0.9.99.1-prerelease `<Thank you CardBoardBoxProcessor and MacLuky>` edition
  * closes #30 - 0.9.99.1 Create Legal Mumbo Jumbo
  * closes #31 - 0.9.99.1 Create Documentation
  * closes #32 - 0.9.99.1 Create Social Media Presence

---

## Version 0.9.99.0-adoption `<Adoption by zer0Kerbal>` edition

* 31 Dec 2021
* for Kerbal Space Program 1.12.2

* closes #25 - 0.9.9.9 adoption
* closes #3 - Release 0.9.9.9-adoption
* closes #4 - Adoption - social media
* closes #5 - Adoption Legal MumboJumbo
* closes #6 - Adoption - Documentation
* closes #7 - Adoption - GitHub
* closes #9 - Localization - English <en-us.cfg>

---

## Version 0.2.0.0-release `<Archival>` edition

* fixes for KSP 1.8.1
* fixes for KSP 1.2.2
* added mission flags
* updated buoyancy profile
* updated COL profile
* techtree integration
* editor search and category integration
* generic docking node fits normal and jr clampotron
* emergency fuelcell if power drops below 10%
* integrated heatshield and insulated capsule
* science container and crew report
* integrated transmitter

---

## Version 0.1.0.0-release `<Archival>` edition

fix link

---

## Version R4

* Band-aided Solar and Landing leg animation problem. only real fix is a DEV fix.
* removed Dragon Brain as it is pointless now.
* Changed some engine power and the like.
* added Reaction Wheels to Capsule.

---

## Version R3

* Fixed RCS Translation instability
* made compatible with 0.20 finally.
* added mechJeb2 support to brain and Capsule (AFAIK not tested)
* Added Docking Cam Support (AFAIK not tested)

---
