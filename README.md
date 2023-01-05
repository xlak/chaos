# Chaos Exploit
This is a bypass method for certain web filters and monitoring software on school-managed Chromebooks.

To use it, go to [xlak.github.io/chaos](https://xlak.github.io/chaos)

## Point-Blank Entrypoint
This entrypoint is an implementation of [the Point-Blank exploit discovered by bypassi](https://blog.bypassi.com/_/point-blank/). It will work on managed Chromebooks and on non-Chrome OS devices.

## Inspect Entrypoint
This entrypoint was discovered by me. It will ONLY work on Chrome OS devices that are logged into a managed account.
It is also more complicated and tedious than the other entrypoint, and you should only use it if the other entrypoint doesn't work.

# Not working?
If you're using another type of device (Windows, Mac), there are (easier) working bypass methods that you can find elsewhere.

Using a Chromebook? [Try This Instead](https://github.com/xlak/alphabetic)

# Supported Web Filters

Filter | Supported
--- | ---
Hapara Highlights | ✔️
Hapara Filter | ✔️
Securly | 🧪
GoGuardian | 🧪
Blocksi | 🧪
Lightspeed | 🧪
LanSchool | 🧪

✖ = Not supported (yet)

🧪 = Untested / Not reliable

✔️ = Tested and fully working

# How does it work?
The exploit works by confusing the Kami, EquatIO, or Assessment Assistant extensions on Chrome OS.
It may still work if you don't have these extensions installed, they just need to be enabled in the organization.
