# Firmware Settings and Menus

Among many challanges around initializing hardware, security, and booting into
operating systems, firmware also needs to provide an interface for the user to
change settings, set up a trust anchor, or simply enjoy colorful graphics.
This talk summarizes approaches from (U)EFI [dating back to 2003](
https://www.intel.com/content/dam/www/public/us/en/documents/reference-guides/efi-human-interface-infrastructure-specification-v09.pdf),
looking at modern OEM UIs in comparison to open implementations such as the menu
in [webboot](https://github.com/u-root/webboot), those from [System76](
https://github.com/system76/firmware-setup), EDK2, and [Dasharo](
https://github.com/Dasharo/edk2/tree/dasharo/MdeModulePkg/Library/UefiBootManagerLib),
and showcasing prototyping environments for further development, finishing with
a short discussion of reusable and portable abstractions for designing APIs.
