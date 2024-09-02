# Chocowi36

> A 36-key, low profile, wireless, split keyboard. Derived from [davidphilipbarr/Choc-Spaced-Corne](https://github.com/davidphilipbarr/Choc-Spaced-Corne), with the original design based on [Foostan's Corne](https://github.com/foostan/crkbd).

![Chocowi36 PCB Top - JLCPCB render](img/pcb_fab_top.png)
![Chocowi36 PCB Bottom - JLCPCB render](img/pcb_fab_bot.png)
![Chocowi36 PCB - KiCad render](img/pcb_kicad.png)

## Changes

-   The PCB shape, dimensions and mounting holes' position are modified to personal preferences.
-   Battery onboard connector is replaced with through hole pads for better flexibility. Power switch is connected to the positive terminal of the battery instead of ground.
-   The outermost thumb key has been changed to a 1u key, and the splayed angle of the thumb cluster has been increased to 15 degrees.
-   Allow the nice!nano to be mounted with the USB port facing down for both halves for better MCB protection.
-   Support both hotswap and soldered switches. Only Choc v1 switches are supported.

## Notes

There are two versions of the PCB, one with [straight traces](./pcb/gerber/straight/straight.zip) and one with [curved traces](./pcb/gerber/rounded/rounded.zip). There are no major differences between the two, mostly just aesthetics.

## Disclaimer

This is a **personal project** and not affiliated with the original authors. The gerber file has been checked against JLCPCB's DFM checker and no critical error was found. All files are provided as-is, **without any warranty or support**. Use at your own risk.
