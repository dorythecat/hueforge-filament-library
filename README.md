# Dory's Curated Filaments

This repository serves as a HueForge community library built of the filaments I've been able to test by myself and whose color and TD I take great effor in verifying. Mostly Spanish brands due to obvious bias.

## Registering in HueForge

1. In HueForge, open **Filaments → Manage Community Sources**
2. Click **+ Add Source**
3. Paste the raw manifest URL:
   ```
   https://raw.githubusercontent.com/dorythecat/hueforge-filament-library/main/manifest.json
   ```
4. Click **OK** — HueForge will fetch and verify the manifest

## About the UUIDs

UUIDs for each filament follow the structure:

```
{BRANDNAM-d0ry-DDMM-YYYY-FILAMENTNAME}
```

Where `BRANDNAM` is the brandname, truncated or elongated to 8 characterts, `DD` and `MM` are the two-digit day and month of the upload of the filament, respectively, `YYYY` is the year of upload, and `FILAMENTNAME` is the name of the filament, including the material, truncated or elongated to 12 characters.

This follows the HueForge library's UUID conventions while still being human-readable (somewhat), you'll thank me later.

## Current brands

We currently have the following brands in the library:

- Smartfil, by Smart Materials (`smartfil`)
- León 3D (`leon3des`)
- Sakata 3D (`sakata3d`)
