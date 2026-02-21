# Ultra Card (Local Pro build)

Community build of [Ultra Card](https://github.com/WJDDesigns/Ultra-Card) with **cloud and external licensing removed** and **all Pro features unlocked locally**.

## What this build does

- **No external servers** – No authentication, backups, or sync with ultracard.io. No billing or subscription checks.
- **Pro modules unlocked** – Video Background, Animated Clock, Animated Weather, Animated Forecast work without a Pro subscription.
- **Unlimited 3rd party cards** – Use as many custom/community cards (Bubble, Mushroom, ApexCharts, etc.) as you want in one dashboard.
- **Same editor and builder** – Layout, Settings, Pro (local settings only), and About tabs; export/import card config to file still works locally.

## What is disabled

- Cloud backup/restore, version history, one-click restore from cloud  
- Multi-device sync, WordPress dashboard, billing portal  
- Preset catalog from ultracard.io (local presets/favorites unchanged)  
- Sign-in / register links to ultracard.io  

## Requirements

- Home Assistant 2023.4.0 or newer  
- Install via HACS (add this repo as a custom Frontend repository) or manually copy `ultra-card.js` to `config/www` and add as a JavaScript Module resource.

## Installation (HACS)

1. HACS → Frontend → ⋮ → **Custom repositories**
2. Add: `https://github.com/silasmariusz/Ultra-Card`
3. Install **Ultra Card**
4. Add resource: URL `/local/ultra-card.js`, type **JavaScript Module**
5. Restart or clear frontend cache if needed

## Credits

Based on [Ultra Card](https://github.com/WJDDesigns/Ultra-Card) by WJD Designs. This fork is not affiliated with Ultra Card Pro or ultracard.io.
