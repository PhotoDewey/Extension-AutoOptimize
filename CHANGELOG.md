# AutoOptimize - Changelog

## v1.5 - 2026-11-11
- Added an Invert button that turns photos scanned as a negative (for example slides) back into positives. Click it again to remove the inversion; Reset also removes it.

## v1.4 - 2026-07-27

- Added Auto Tone: a gentle, always-safe S-curve that lifts shadow detail and softens highlight roll-off without ever introducing new clipping. Applied via luminance-preserving colour scaling so hue and saturation are not distorted.
- Added hover tooltips to all Auto Optimize buttons explaining what each one does.
- Fixed Reset sometimes requiring two clicks before the histogram reflected the fully reset image.
- Fixed Auto Levels producing a visible comb/sawtooth pattern in the histogram on lower-contrast photos. The stretch now uses Floyd-Steinberg error diffusion instead of a direct lookup, which smooths the result substantially (it cannot be fully eliminated on very low-contrast source photos - the same effect is visible in other photo editors after a strong Levels stretch).

## v1.3 - 2026-06-12

## v1.2 - 2026-06-11

## v1.1 - 2026-06-11

## v1.0 - 2026-06-06
