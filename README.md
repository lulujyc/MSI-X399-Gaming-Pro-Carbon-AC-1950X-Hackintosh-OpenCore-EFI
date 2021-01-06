# MSI-X399-Gaming-Pro-Carbon-AC-1950X-Hackintosh-OpenCore-EFI
Hackintosh For MSI X399, AMD 1950X CPU and AMD Vega 64 GPU.

## Compatibility

- **TR 1950X**: The main model this configuration was developed with and for.
- **Other 1st gen TRs**: Compatible in theory. Not tested.
- **Other 2nd gen TRs** Compatible in theory. Not tested.
 
## Post-installation tweaks
A few required or otherwise useful steps to take on a running macOS:

**Using your own serial number**

Just generate a new set with OpenCore Configurator and you're good to go (suggested SMBIOS is iMac Pro 2017 and Mac Pro 2019)

**Switching `cmd` and `opt`**

In keyboard settings, select the modifier keys option, and switch `cmd` (win) with `opt` (alt)

## Reference Specs

CPU: ThreadRipper 1950X

MB: MSI X399 Gaming Pro Carbon with Latest BIOS

GPU: Radeon RX Vega 64 Reference Design

SSD: Intel SSD 750 1.2T


## Tested OS (with latest EFI):
- macOS High Sierra √
- macOS Mojave ?
- macOS Catalina √
- macOS Big Sur √

## What works

- Full hardware acceleration (refer to the Dortania guides if you're not using Vega series GPU)
- Audio
- USB ports
- CPU Temperature and voltage/wattage reading via SMCAMDProcessor
- Sleep

## What's untested

- Hibernation

## What's not yet working

- Things don't work on other AMD Vanillas don't work here

## What will never* work

- Things never work on other AMD Vanillas never work here

_* Not unless someone decides to make custom kexts for these, of course._
