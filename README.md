# Onasport Firmware Releases Development

Welcome to the Onasport Firmware Releases repository for DEVELOPMENT. This repository contains the firmware update files for Onasport devices for purposes outside of customers: for development, quality assurance and beta testers environments. This repository is the source for the onasport verify app to fetch latest firmware versions for users.

To update a new firmware file:
* Upload the compiled .sfb files into the repository.
* Compute a md5sum identifier from https://emn178.github.io/online-tools/md5_checksum.html.
* Update appropriately the fw_info.json file. A description can be added to provide more context to that specific firmware version files.