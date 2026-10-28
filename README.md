# RSE File Format Templates
This repository contains [010 Editor](https://www.sweetscape.com/010editor/) templates for RSE game file formats. This is a decent way of documenting the file formats and allowing interactive exploration of the data.

As part of a reorganisation of the RainbowRedux project with [AlexKimov](https://github.com/AlexKimov), many of the templates from the [original repository](https://github.com/AlexKimov/RSE-file-formats) have been migrated to this repository. This repository is to be considered the most up to date for the purposes of RainbowRedux.

Notes on migration:
 - Files have been renamed to match the RainbowRedux naming convention, R6 = Rainbow Six, RS = Rogue Spear, GR = Ghost Recon
 - Some formats have not been migrated yet. Please look in the original repository if there is a missing format.


## 2026.10 update
 - New templates: `RainbowSix/SOB(r6).bt` (from the original repository), `RogueSpear/SHT(rs).bt`, `GhostRecon/CHR(gr).bt`, `GhostRecon/BMF(gr).bt`, `GhostRecon/POB(gr).bt`.
 - The other templates gained field names and corrections; each one's History block lists what changed.
 - The layouts were checked against all of the PC releases' files of each type; the few files that don't fit are noted in the template.
 - Fields that are still unknown keep "Unknown" names.
