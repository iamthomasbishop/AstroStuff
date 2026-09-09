---
cssclasses:
  - wide
---
[Repository](https://github.com/iamthomasbishop/AstroStuff/tree/main)

---

## Planning Criteria

- Targets to consider: see 'Targets' section below
- Primary focus: DSOs — nebulae (reflection/bright/planetary), and galaxies (globular clusters if nothing else is available)
- Secondary focus: solar system (moon and planets)
- Horizon: must be above horizon (see horizon data above), ideally for ≥ 2 hours during imaging window. Note: be somewhat conservative, as horizon values may be inexact.
- Object size: minimum ~1.5 arcmin (roughly the size of the Ring Nebula), maximum ~40 arcmin or around the size of Triangulum
- Ideally well away from the moon when it’s in play but not a deal-breaker if imaging in narrowband
- Alt and az constraints: see (location-specific) horizon data above
- Gear: see "Gear" section above

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
| Guide system       | ZWO OAG (small)                                                                     | No guiding                                                  | No guiding                                                                  |
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

---

## Locations


|                              | Primary - Home                                                                                                         | Alt. 1 - Marquette                                                                                                               |
| :--------------------------- | :--------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| Location                     | Appleton, WI                                                                                                           | Marquette, MI                                                                                                                    |
| Approx. coordinates          | 44.227° N, 88.379° W                                                                                                   | 46.548° N, 87.388° W                                                                                                             |
| Horizon (azimuth + altitude) | See [Custom Horizon - Home.md](https://github.com/iamthomasbishop/AstroStuff/blob/main/Custom%20Horizon%20-%20Home.md) | See [Custom Horizon - Marquette.md](https://github.com/iamthomasbishop/AstroStuff/blob/main/Custom%20Horizon%20-%20Marquette.md) |

---

## On processing
Acquisition happens on the associated controller, either via Dropbox or the internal file storage system (i.e. StellaVita) and later transferred to an external hard-drive.  Processing is typically done with Siril, Autostakkert, Pixelmator Pro, others.