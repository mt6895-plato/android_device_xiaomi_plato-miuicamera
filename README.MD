# MiuiCamera Leica Mod for Xiaomi 12T (plato)
> Originally adapted from an awesome project: [NaufalSaputraa/PlatoCamera](https://github.com/NaufalSaputraa/PlatoCamera) - Big thanks to them <3

1. Get started by cloning this repo to: `device/xiaomi/plato-miuicamera`
2. Clone [Vendor repo](https://gitlab.com/archcloudy/android_vendor_xiaomi_plato-miuicamera) to: `vendor/xiaomi/plato-miuicamera`
3. Inherit it from `device.mk` in your device tree:
```
# Camera
$(call inherit-product-if-exists, vendor/xiaomi/plato-miuicamera/device.mk)
```

## Credits
- [NaufalSaputraa/PlatoCamera](https://github.com/NaufalSaputraa/PlatoCamera) - PlatoCamera Project | ANGLE/Mediatek Libs fixes, Adapt to Xiaomi 12T compatibility
- [@HolyBearHome](https://github.com/a406010503) | [@itzdfplayer](https://t.me/itzdfplayer_stash2) | @Sevtinge - MiuiCamera Leica Mod v5.0 + Other Mods