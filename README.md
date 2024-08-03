# wear-os-2-stuff
I have a Moto 360 3rd Gen. I like how it looks and am fine with the functionality, but it won't be updated to Wear OS 3, which means app support is bad and Google Assistant doesn't work.

## Wear OS 2.0 details
Android 9.0, API 28. Google currently requires all Google Play Wear OS apps to target API 30.

## Moto 360 3rd Gen details
- Released 2020
- APQ8009W CPU.
  - It is a quad-core Cortex-A7 but two of the cores are disabled. The two remaining cores have a max clock speed of 1.1GHz.
  - The two other cores are still part of the CPU (they show up in /sys/devices/system/cpu), but are disabled in the kernel (I think). I might try to build a kernel which re-enables them
- 390x390 round screen
- 1GB RAM
- 8GB storage

## What this repo will contain
Watch faces, maybe custom apps I will make, guides for getting stuff like Google Assistant to work
