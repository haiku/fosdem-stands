# What's New

Since the last FOSDEM in 2021, Haiku has had a major release: Beta 3 in 2021. Our third beta release, the first being in 2018, Beta 3 builds upon the improvements delivered in Beta 2 and brings a stack of improvements to Haiku.

Notably, 251 tickets mainly consisting of bug reports were closed during this release cycle.

![Haiku stand](/stands/haiku/stand.jpg)

## Highlights from Beta 3

- The installation process is now much smoother.
- Package management received performance and stability improvement, and can now resume interrupted downloads.
- We switched to Python 3.7 as the default Python version.
- The user interface received improvements on dark color theme, scaling, and localization.
- The font overlay and fallback system was fixed.
- WebPositive automatically uses dark mode according to the current system color scheme.
- The WebKit version used by WebPositive was updated.
- A BeControlLook allows apps to match the BeOS R5 interface closely.
- The POSIX compatibility received many fixes and additions, including `mlock`/`munlock`, `posix_fallocate` and `ppoll` calls.
- Some optimizations were done in frequently used API calls.
- Czech translation is now available, making Haiku available in 28 languages.
- We improved several drivers, and added support for SD/MMC on PCI (SDHCI).

## Other news

- For the first time since 2014, [we have a long term contract for a full-time developer](https://www.haiku-os.org/news/2021-08-25_hiring_waddlesplash/). Waddlesplash
  is working on various areas of the operating system, ranging from the USB stack to an X11 compatibility layer to run more Linux/BSD applications.
- For the first time ever, [the Haiku desktop is booting on non-x86 hardware thanks to the efforts
  from X512 of porting Haiku to RISC-V](https://www.haiku-os.org/blog/kallisti5/2021-11-07_booting_our_risc-v_images/). There are ongoing efforts for the ARM port as well.
