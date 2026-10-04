# Orbit Client 2.0

Orbit Client is an all-in-one, highly customizable Fabric client for **Minecraft 1.21.11**. It combines PvP HUD tools, survival information, visual controls, performance settings and quality-of-life features inside a clean Orbit-themed interface.

## Controls

- **Right Shift** — open the Orbit module menu
- **Right Ctrl** — open the drag-and-drop HUD editor
- **C (hold)** — zoom
- Screenshot-folder key — configurable in Minecraft Controls

## Highlights

- 80+ built-in modules/settings pages
- Orbit space-themed dashboard with categories, module cards and per-module settings
- Drag-and-drop HUD editor with snapping and center guides
- Per-HUD background, opacity, text color, accent color and shadow controls
- Advanced custom crosshair
- Fixed Low Shield, Low Fire and Zoom
- Uniform Fullbright using the 1.21.11 lightmap path
- AppleSkin-style held-food nutrition/saturation preview
- Hunger + saturation HUD
- Inventory counters for common PvP/survival items
- Client-side visual controls for FOV, dynamic FOV, view bobbing, damage tilt, portal distortion, glint, chat appearance and GUI scale
- Performance controls for FPS, background FPS, particles, weather, render distance and entity distance
- No cheat modules: no aim assist, reach modification, velocity modification, autoclicker, ESP or x-ray

## Modules

### PvP
Keystrokes, CPS Counter, Armor HUD, Potion Effects, Durability HUD, Totem Counter, Item Counter, Attack Indicator, Attack Cooldown, Mace Cooldown, Crosshair Customizer, Hit Color, Hit Sound, Low Fire, Low Shield, Auto Sprint, Combo Counter, Hit Distance.

### HUD / Info
FPS Counter, Ping Display, Coordinates, Direction, Speedometer, Session Time, Memory Usage, Clock, Biome Display, Player Counter, Server Address, Hunger & Saturation, Health Display, Armor Condition, Experience, Day Counter, Dimension, Chunk Position, Target Info, Held Item Info, Food Preview, Golden Apple Counter, Pearl Counter, Arrow Counter, Crystal Counter, XP Bottle Counter, Obsidian Counter, Potion Counter, Shield Counter, Stopwatch, Date, Ping Graph, Custom HUD Editor.

### Visual
Fullbright, Zoom, Weather Changer, No Vignette, No Pumpkin Overlay, No Portal Overlay, Block Outline, Custom Sky, FOV Changer, View Bobbing, Damage Tilt, Dynamic FOV, Distortion Control, Enchant Glint, Entity Shadows, Chat Appearance, GUI Scale.

### Performance
Particles, Dynamic FPS, Weather Optimization, FPS Limiter, View Distance Cap, Entity Distance.

### Utility
Orbit Settings, Auto Respawn, Screenshot Manager, Chat Timestamps, Chat Notifications, Toggle Sneak, Toggle Sprint.

## Building

Requires **Java 21**. The repository includes a GitHub Actions workflow that builds with Gradle 9.2.0.

```bash
gradle build
```

The built JAR is placed in `build/libs/`.

## Project identity

Orbit Client uses its own name, theme, logo, code and UI assets. It is not affiliated with any other Minecraft client.
