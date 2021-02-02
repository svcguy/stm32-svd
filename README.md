# stm32-svd
### An up to date collection of STM32 SVD files

This repo uses GitHub Workflows to download SVD files from ST.  The job runs once a day, which is probably overkill for SVD files, downloads the .zips, unzips them, copies them to a clean folder structure and pushes them to this repo.

SVD files are used by debuggers to identify the registers on a microcontroller in a nice human-readable format.

It currently supports the following STM32 families:
- F0
- F1
- F2
- F3
- F4
- F7
- G0
- G4
- H7
- L0
- L1
- L4
- L4+
- MP1
- WB
- WL

The ReleaseNotes folder contains the release notes (including the version) for each family of SVD files

Hope this helps!
