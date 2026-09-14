# Home Assistant Clock Dashboard

Fullscreen clock dashboard with a daily Bing Wallpaper background.

## Requirements

- Home Assistant 2026.x or newer.
- HACS.
- `custom:button-card`.
- Bing Wallpaper integration installed and configured.
- A weather entity named `weather.forecast_home`.

## HACS Dependencies

- Button Card:  
  https://github.com/custom-cards/button-card

- Bing Wallpaper:  
  https://github.com/ndesgranges/bing-wallpaper

## Installation

1. Install the dependencies through HACS.
2. Copy `packages/clock.yaml` to `/config/packages/`.
3. Add this to `configuration.yaml`:

   ```yaml
   homeassistant:
     packages: !include_dir_named packages
