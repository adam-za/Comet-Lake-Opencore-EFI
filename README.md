# Comet-Lake-Opencore-EFI
Opencore EFI folder for macOS Big Sur on comet lake devices.
![Example Screenshot](Screenshots/Screenshot%202026-06-22%20at%2008.59.07.png)

## Specs of machine tested on:
- Intel Core I5 10210U
- Intel UHD 620 for 10th gen Intel.
- Kioxia NVME SSD (256GB).
- 8GB DDR4 2666Mhz RAM.
- Intel Wi-Fi card with Realtek RTL8111 ethernet card.
- PS/2 Keyboard with Synaptics RMI trackpad.

## Caution
Please be advised that this is only to be used as a template for educational purposes!
This EFI will most likely not work on your machine without some modifications, read below for details.

## Setup
1. Please use the 'GenSMBIOS' tool to add the needed SMBIOS info in the platforminfo section.
1. Adjust framebuffer patch to match your iGPU (current spoof for UHD 620)
1. Copy folder over to your EFI partition and attempt boot.
