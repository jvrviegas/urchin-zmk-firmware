# Urchin keymap

Tags: `zmk`, `keymap`, `urchin`, `totem`, `home-row-mods`

- Active layout and behaviors: `config/urchin.keymap`
- Hardware has 34 positions: 30 alpha-grid keys followed by four thumbs; physical coordinates are documented in `config/urchin.json`.
- The keymap is a direct adaptation of `../zmk-config-totem/config/totem.keymap`.
- The Totem's outer bottom-row Shift keys and outer GUI/Alt thumb keys do not physically exist on Urchin and are omitted.
- Bottom-row combo positions and bilateral hold-trigger lists are translated to Urchin's 34-position matrix.
- Totem mouse bindings are intentionally replaced with `&none`; pointing support is disabled.
- Firmware API compatibility is pinned by `config/west.yml` to ZMK `v0.3.0`.
