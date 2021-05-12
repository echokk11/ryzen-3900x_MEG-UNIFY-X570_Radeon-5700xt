- Update 2021.05
- Support `Big Sur 11.3.1`
- OpenCore Version `0.6.9`

![IMG_7215](./img/IMG_7215.jpg)

# ryzen-3900x_MEG-UNIFY-X570_Radeon-5700xt
- CPU: AMD R9 Ryzen 3900X
- Motherboard: (MSI)MEGX570 UNIFY
- GPU: ASUS ROG STRIX Radeon RX5700XT O8G GAMING
- Wireless Card: PCI-E BCM94360CD
- Other:
  - RAM: Kingston Fury DDR4 3200 16Gx4
  - SSD: SAMSUNG 970 EVO Plus 500GB(M.2/Nvme)
  - Monitor: BenQ PD2700U & Dell P2415Q

Based on [barrrrt/AMD-3900x_MEG-MSI-Unify-X570_AMD-X5700XT](https://github.com/barrrrt/AMD-3900x_MEG-MSI-Unify-X570_AMD-X5700XT)



> I use PCI-E Wireless Card, so I should disabled the internel WIFI Intel AX200
>
> Find `USBPorts.kext`, open Contents/Info.plist, and remove which key is  `PRT4 ` and the node dict



**Attention**: Don't forget regenerate your Seria Number. Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

