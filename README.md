# Le-Potato-Instructions
Libre Computer AML-S905X-CC (Le Potato) Instructions

## Useful links
Product home page
libre.computer/products/aml-s905x-cc/#

Help forum
hub.libre.computer/t/libre-computer-start-here-guide/2422

Libre Computer Start Here Guide
https://hub.libre.computer/t/libre-computer-start-here-guide/2422

Flash 

Download OS image
https://hub.libre.computer/t/debian-12-bookworm-and-11-bullseye-for-libre-computer-boards/230
https://distro.libre.computer/ci/debian/12/debian-12-base-arm64%2Baml-s905x-cc.img.xz

Extract img file
unxz --verbose debian-12-base-arm64+aml-s905x-cc.img.xz

Flash .img file into USB pendrive or SSD (Takes 15 min or more)
dd if=debian-12-base-arm64%2Baml-s905x-cc.img of=/dev/DEVICE bs=1M status=progress





