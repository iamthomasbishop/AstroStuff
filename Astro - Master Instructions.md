---
cssclasses:
  - style--font-size--xsmall
  - full-width
---

## Planning Criteria

- Current targets: [Astro Targets.md](https://github.com/iamthomasbishop/AstroStuff/blob/main/Astro%20Targets.md) (include but don't necessarily limit to these)
- Gear: see 'Gear' section
- Types of objects
	- Primary (Config. A): DSOs (in order of priority) → nebulae, galaxies, globular clusters if not much else is available
	- Planetary (Config. B for imaging, Config. C for visual): solar system
	- Note: prioritize preferences noted in initiating prompt
- Horizon and alt-az constraints:
	- Important: Estimate somewhat conservatively because horizon values may be inexact
	- Objects ideally should be above horizon for ≥ 2 hours during imaging window
	- See 'Locations' for horizon data
	- Preference for E-SSW window when location is 'Home'
- Object size: minimum 1 arcmin (roughly the size of the Ring Nebula), maximum ~40 arcmin or around the size of Triangulum
- Moon proximity: avoid the moon when it’s in play unless you have any strong contenders for narrowband imaging
- Avoid the need for rotation, especially after ~11pm
---

## Gear

### Current Kit Configurations
I currently have 3 kit configurations: a primary for imaging DSOs (config A), a primary for visual observing (config C), and a secondary for planetary imaging (config B).

| **Component**      | **A - Primary Imaging (DSO)**                                                       | **B - Secondary Imaging (planetary)**                       | **C - Primary Visual**                                                      |
| :----------------- | :---------------------------------------------------------------------------------- | :---------------------------------------------------------- | :-------------------------------------------------------------------------- |
| OTA                | Celestron NexStar 8SE                                                               | Celestron NexStar 8SE                                       | Celestron 90 SLT                                                            |
| Mount              | MLAstro SAL-33                                                                      | MLAstro SAL-33                                              | Stock 8SE single fork arm on Celestron 93665 EQ wedge                       |
| Pier extension     | MLAstro P-200                                                                       | MLAstro P-200                                               | --                                                                          |
| Tripod             | ZWO TC-40                                                                           | Stock NexStar 8SE tripod                                    | Stock 8SE tripod                                                            |
| Main camera        | ZWO ASI294MC Pro                                                                    | ZWO ASI678MC                                                | --                                                                          |
| Guide system       | ZWO OAG Small                                                                       | No guiding                                                  | No guiding                                                                  |
| Guide camera       | ZWO ASI120MM Mini                                                                   | --                                                          | --                                                                          |
| Filter wheel       | ZWO EFW mini                                                                        | --                                                          | --                                                                          |
| Rotator            | BlueFireball manual rotator (M42)                                                   | --                                                          | --                                                                          |
| Magnification      | Celestron 0.63x reducer                                                             | Sometimes Svbony SV216 2x Barlow or Celestron 0.63x reducer | Sometimes Svbony SV216 2x Barlow or Celestron 0.63x reducer (default: none) |
| Finder             | Stock 8SE red-dot                                                                   | Stock 8SE red-dot                                           | Stock 90 SLT red-dot                                                        |
| Eyepieces          | --                                                                                  | --                                                          | 32mm, 25mm, 20mm, 15mm, 6mm (mostly Svbony)                                 |
| Diagonal           | --                                                                                  | --                                                          | Celestron 1.25" star diagonal                                               |
| Visual back        | --                                                                                  | --                                                          | Stock 8SE/90 SLT visual back                                                |
| Dew shield         | Astromania flexible dew shield                                                      | Astromania flexible dew shield                              | Astromania flexible dew shield                                              |
| OTA dew heater     | Celestron dew heater ring (secondary mirror)                                        | Celestron dew heater ring (secondary mirror)                | --                                                                          |
| Camera dew control | ZWO anti-dew heater (for ASI294MC-Pro camera)                                       | SVBONY SV172 dew heater strap (for ASI678MC camera)<br>     | --                                                                          |
| Filters            | Optolong UV/IR cut, Svbony SV240 multi-narrowband, Svbony SV220 3nm dual-narrowband | Svbony UV/IR cut                                            | Celestron UHC, Svbony CPL                                                   |
| Controller         | Mele Quieter 4c                                                                     | Mele Quieter 4c                                             | Touptek StellaVita                                                          |
| Software           | NINA, PHD2 (guiding), ASCOM device hub                                              | SharpCap                                                    | Touptek StellaVita app                                                      |
| Power control      | Svbony SV241 Pro hub                                                                | Svbony SV241 Pro hub                                        | Svbony SV241 (non-pro) hub                                                  |
| Power sources      | Fixed outlet, Jackery power generator as backup                                     | Fixed outlet, Jackery power generator as backup             | Fixed outlet, Jackery power generator as backup                             |
| Power adapters     | 12V 10A and 12V 8A power adapters                                                   | 12V 10A and 12V 8A power adapters                           | 12V 5A batter pack/power adapter                                            |
| Other gear         | Assortment of back-spacing accessories, adapters, other attachments                 |                                                             |                                                                             |
| Calibration frames | LED light panel for flats                                                           | LED light panel for flats                                   | --                                                                          |

### A note on focal length
- My C8 has a "native" focal length of 2032 mm (focal ratio of f/10)
- With my 0.63x reducer, the native focal length is ~1280 mm (focal ratio of f/6.3)
- My "effective" focal length (for imaging) is ~1291 mm (as of 2026-09-22) (focal ratio of f/6.35)


---

## Locations


|                              | Primary - Home                                                                                                         | Alternate 1 (Marquette)                                                                                                          |
| :--------------------------- | :--------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| Location                     | Appleton, WI                                                                                                           | Marquette, MI                                                                                                                    |
| Coordinates                  | 44.22699° N, 88.38495° W                                                                                               | 46.54722° N, 87.38488° W                                                                                                         |
| Horizon (azimuth + altitude) | See [Custom Horizon - Home.md](https://github.com/iamthomasbishop/AstroStuff/blob/main/Custom%20Horizon%20-%20Home.md) | See [Custom Horizon - Marquette.md](https://github.com/iamthomasbishop/AstroStuff/blob/main/Custom%20Horizon%20-%20Marquette.md) |

---

## On processing
Acquisition happens on the associated controller, either via Dropbox or the internal file storage system (i.e. StellaVita) and later transferred to an external hard-drive.  Processing is typically done with Siril, Autostakkert, Pixelmator Pro, others.