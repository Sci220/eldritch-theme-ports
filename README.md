# Eldritch Theme Ports

[Eldritch](https://github.com/eldritch-theme/eldritch) Lovecraftian horror color palette ported to various desktop theming engines.

![Eldritch](https://img.shields.io/badge/Eldritch-212337?style=for-the-badge&logo=data:image/svg+xml;base64,&logoColor=37f499)
![Kvantum](https://img.shields.io/badge/Kvantum-Qt_Theme-04d1f9?style=for-the-badge)
![Rewaita](https://img.shields.io/badge/Rewaita-GTK4_Theme-37f499?style=for-the-badge)

## Included Themes

### Eldritch-Pax (Kvantum)

Qt theme combining the Eldritch palette with **Pax-Kvantum**'s translucency and blur effects. Built on the excellent Pax-Kvantum theme by l4k1.

### Eldritch (Rewaita)

GTK4/libadwaita theme for the [Rewaita](https://github.com/swordpuffin/rewaita) theme manager.

### Features

- **Eldritch color palette** - deep oceanic backgrounds with vibrant cosmic accents
- **Window translucency** with blur effects (from Pax-Kvantum)
- **Popup blurring** for menus and dropdowns
- **Animated states** for smooth UI transitions
- **Transient scrollbars** for a clean look

### Color Palette

| Role | Color | Hex | Name |
|------|-------|-----|------|
| Background | ![#212337](https://placehold.co/16x16/212337/212337) | `#212337` | Sunken Depths Grey |
| Surface | ![#323449](https://placehold.co/16x16/323449/323449) | `#323449` | Shallow Depths Grey |
| Text | ![#ebfafa](https://placehold.co/16x16/ebfafa/ebfafa) | `#ebfafa` | Lighthouse White |
| Primary Accent | ![#37f499](https://placehold.co/16x16/37f499/37f499) | `#37f499` | Great Old One Green |
| Secondary Accent | ![#04d1f9](https://placehold.co/16x16/04d1f9/04d1f9) | `#04d1f9` | Watery Tomb Blue |
| Selection | ![#7081d0](https://placehold.co/16x16/7081d0/7081d0) | `#7081d0` | The Old One Purple |
| Tertiary | ![#a48cf2](https://placehold.co/16x16/a48cf2/a48cf2) | `#a48cf2` | Lovecraft Purple |
| Warning | ![#f7c67f](https://placehold.co/16x16/f7c67f/f7c67f) | `#f7c67f` | Dreaming Orange |
| Error | ![#f16c75](https://placehold.co/16x16/f16c75/f16c75) | `#f16c75` | R'lyeh' Red |

## Installation

### Kvantum (Eldritch-Pax)

1. Clone or download this repository
2. Copy the theme to your Kvantum directory:

```bash
mkdir -p ~/.config/Kvantum/Eldritch-Pax
cp Eldritch-Pax.kvconfig Eldritch-Pax.svg ~/.config/Kvantum/Eldritch-Pax/
```

3. Open **Kvantum Manager**, select **Eldritch-Pax**, and click **Use this theme**

**Requires:** [Kvantum](https://github.com/tsujan/Kvantum) and a compositor with blur support (Niri, Hyprland, KWin, etc.)

### Rewaita (GTK4/libadwaita)

1. Copy the CSS file to Rewaita's dark themes directory:

```bash
cp "rewaita/Eldritch 🐙.css" ~/.var/app/io.github.swordpuffin.rewaita/data/dark/
```

2. Restart Rewaita and select **Eldritch 🐙** from the dark theme list

**Requires:** [Rewaita](https://github.com/swordpuffin/rewaita) (Flatpak)

## Credits

- **[Eldritch Theme](https://github.com/eldritch-theme/eldritch)** - Color palette by the Eldritch community
- **[Pax-Kvantum](https://github.com/nicman23/Kvantum-Themes)** - Base Kvantum theme structure by l4k1
- **[Kvantum](https://github.com/tsujan/Kvantum)** - Qt theme engine by tsujan
- **[Rewaita](https://github.com/swordpuffin/rewaita)** - GTK4/libadwaita theme manager

## License

This theme is released under the [MIT License](LICENSE).
