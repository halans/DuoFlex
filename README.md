# DuoFlex

**A waist-level finder camera for iPhone Duo.**

<img src="assets/icon.png" alt="DuoFlex app icon: a twin-lens reflex camera" width="128" height="128">

DuoFlex turns iPhone Duo into a twin-lens reflex. Half-fold the phone with the camera half standing up and facing your subject, hold it at your waist, and look straight down into the bottom half to frame your shot. The upright half shows your settings, laid out like a rangefinder's status screen. The flat half is the ground glass and the shutter release.

This repository holds the DuoFlex landing page. DuoFlex is coming soon to the App Store.

## How it works

1. **Half-fold it.** Hold iPhone Duo in portrait and fold it to about 90°, with the camera half standing up.
2. **Hold it at your waist.** The bottom half lies flat and becomes the viewfinder, like the hood of a twin-lens reflex.
3. **Look down and shoot.** Frame on the ground glass, swipe to set exposure or focus, and press the shutter — or use the volume buttons.

## Features

- **Three frame formats:** WIDE fills the whole viewfinder half and crops the photo to exactly what you see; 3:2 and 6×6 square give you classic film frames.
- **Swipe to adjust:** swipe up or down on the viewfinder for exposure compensation in ⅓-stop steps (−3 to +3 EV). In manual focus, swipe sideways to focus, with yellow focus peaking on sharp edges.
- **Level and tilt:** a circular bubble level and a horizon line that turn yellow, with a gentle tap, when you're level.
- **Film simulations:** Classic Chrome, Portra 400, Ektar 100, Velvia 50, CineStill 800T, Tri-X 400, and Acros 100, rendered live with grain.
- **LUTs:** four built in, plus import for your own 3D `.cube` files, with adjustable strength.
- **Camera controls:** live aperture and shutter readouts, ISO from 50 to 3200, white balance presets, and 0.5×, 1×, and 2× lenses.
- **Grid, mirror, and self-timer:** thirds, 4×4, or center grids; a mirrored image like a classic reflex finder; and a 2 s or 10 s timer.
- **Files with their story:** HEIF or JPEG, with the camera's EXIF data, the look you used, and — if you allow it — where you took the photo.

## Privacy

- No account, and no analytics.
- Photos are saved to your library on your device. DuoFlex only asks to add photos, never to read them.
- Location is optional and only used to tag photos with where you took them.

## Requirements

iOS 27.2 or later. DuoFlex is designed for iPhone Duo, using the fold of the inner display in portrait. On other iPhones, it stacks the settings above the viewfinder instead.

## About this site

The landing page is a single static file, `index.html`, with its images in `assets/`. It has no build step and makes no requests to other sites.

- **Preview:** open `index.html` in a browser.
- **Publish:** serve the repository root with GitHub Pages, or any static host.

| Path | Contents |
| --- | --- |
| `index.html` | The page, with its styles and illustrations inline. |
| `assets/icon.png` | App icon, 512 px. |
| `assets/apple-touch-icon.png` | Home Screen icon for the site, 180 px. |
| `assets/favicon.png` | Browser tab icon, 64 px. |

iPhone is a trademark of Apple Inc.
