# NekoUI Changelog

## Summary of Changes

### Stable Releases
- **1.0.3 (20/12/2025)** – Added new `/rpc` command, Credits screen, multi-language support, migrating to Discord Game SDK, and more.
- **1.0.2 (15/07/2025)** – Enhanced dimension-aware Discord RPC, added performance detector, and static/animated background toggle.
- **1.0.1 (21/06/2025)** – Polished Clean Mode visuals and fixed versioning issues in updater system.
- **1.0.0-release+mc1.21.1 (20/06/2025)** – Introduced Clean Mode, robust animated background system, and dynamic Discord presence.

### Beta Releases
- **1.0-beta2+mc1.21.1 (05/06/2025)** – Introduced animated background support and refreshed UI design.
- **1.0-beta+mc1.21 (29/05/2025)** – Added updater, Discord RPC, mod loader support, and static background integration.

### Alpha Releases
- **v1.0-beta (31/07/2024)** – First release with Blue Archive backgrounds and basic config system.

---

## Stable Release Versions

### NekoUI 1.0.3 (20/12/2025)
#### Rich Presence (RPC)
- [ EXPERIMENTAL FEATURES ] Added new `/rpc` command.
- [ EXPERIMENTAL FEATURES ] Migrated from standard Discord RPC to Discord Game SDK for better performance and support.

#### Background
- Improve background rendering & caching.
- Fixed issue where the background did not render correctly on the title screen (Forge only).
- Background is now visible on the **Select World**, **Select Server**, and **Options** screens.

#### UI & Layout
- Refined overall UI layout system for better responsiveness.
- Improving title screen & agreement screen layout.
- Improving UI animation for better performance.

#### Updater
- Updated NekoUI Updater Launcher with performance and reliability improvements.

#### Languages
- Added support for new languages:
  - Arabic
  - Brazilian Portuguese
  - Mexican Spanish
  - Italian
  - German
  - Georgian

### Window
- Minecraft window now will show "NekoUI - [EVENT]"

---

### NekoUI 1.0.2 (15/07/2025)
#### Mixin
- Added `UIInterceptorMixin` to prevent external mods from injecting incompatible background changes into NekoUI.
- Added `TitleScreenMixin` to support rendering animated/static NekoUI backgrounds on the main menu.

#### Background
- `BackgroundBuilder` now respects `lowQualityMode` and displays static-only backgrounds across all screens.
- Background auto-performance detection now logs when low-spec hardware is detected.
- Fixed background rendering while in-game or when switching window focus.

#### Rich Presence (RPC)
- Displays current dimension (e.g., Overworld, Nether, The End) in Discord Rich Presence.
- Added fallback naming for unknown or custom dimensions.
- Refactored internal game state logic for more reliable dimension tracking.

#### Utility
- Added basic performance issue detector.

#### Config
- Background preview now uses static images only.
- Added toggle between static and animated background modes.
- Adjustable background frame rate (FPS) in config.

---

### NekoUI 1.0.1 (21/06/2025)
#### UI
- Fixed gradient not rendering on the left side when toggling Clean Mode.
- Improved fade-out animation for Minecraft version text in Clean Mode.
- Fixed UI buttons reappearing after window resize or fullscreen toggle in Clean Mode.
- Smoother transition in and out of Clean Mode.
- Added logic to hide widgets instantly during Clean Mode activation.

#### Rich Presence (RPC)
- Updated fallback and inactive small image to use the Minecraft icon.

#### Updater
- Improved version checking for Modrinth’s new metadata format.
- Refactored version comparator to support complex version identifiers.
- Added suffix ordering (`alpha < beta < release < stable`) for proper version sorting.
- Improved support for semantic and metadata-based versioning (e.g., `+mc1.21.1`).
- Ensured backward compatibility with older version formats.

---

### NekoUI 1.0.0-release+mc1.21.1 (20/06/2025)
#### UI
- Added sliding + fading animation for widgets when toggling Clean Mode.
- New button on title screen to toggle Clean Mode (minimal UI state).
- Fixed issue with widgets reappearing after window resize/fullscreen toggle in Clean Mode.

#### Rich Presence (RPC)
- Presence dynamically updates based on player's state (menus, SP/MP).
- Dimension icon now correctly reflects the current dimension.
- Reduced redundant presence updates using cooldown and state comparison.
- Start timestamp remains consistent during session unless context changes (e.g., new world/server).

#### Background
- Added automatic image format conversion for in-game use.
- Fixed incorrect color tinting (red shift) in converted images.
- Preserved alpha transparency correctly during image processing.
- Improved rendering consistency and color accuracy.
- Added fallback system for invalid or missing backgrounds (defaults to `default`).
- Frames now sorted using numeric values from filenames (`frame-1.jpg`, `1.png`, etc.).
- Ignored files without numeric indexes (e.g., `frame.png`).
- Prevented background loading if no valid frames are found.
- Improved reliability and fallback when animated backgrounds fail to load.

#### Implementation
- Integrated Mod Menu for Fabric and Quilt.

#### Deprecated
- Removed deprecated Forge code.
- Replaced deprecated API usage in URL utilities.

#### Config
- Optimized performance of background selection screen for low-end devices.
- Only selected background animates during preview.
- Unselected backgrounds now show static thumbnails.
- Reduced lag when browsing many animated backgrounds.
- Improved UI clarity by highlighting only the selected background.

#### Updater Window
- Fixed overflow caused by `Show Details` button.
- Resolved loss of rounded corners after calling `pack()`.
- Fixed resizing issues when toggling log area visibility.
- Fixed component misalignment when log area is shown.
- Replaced `setSize()` with `pack()` for dynamic resizing.
- Restored custom rounded window shape after resizing.
- Updated layout and shape dynamically based on detail panel toggle.
- "Enable Auto-Update" and "Show Details" buttons now aligned horizontally.
- Added minimum window size to prevent unexpected shrinking.

#### Other
- Native window title (taskbar & top bar) now shows `NekoUI [Minecraft Version]`.

---

## Beta Releases

### NekoUI 1.0-beta2+mc1.21.1 (05/06/2025)
#### UI
- Refreshed title screen UI.
- New custom design for Config Screen.

#### Config
- Fixed Config Screen rendering issues on NeoForge.

#### Background
- Added support for animated backgrounds.
- Custom animated backgrounds now supported.
- Improved rendering performance for backgrounds.
- Animated backgrounds require a Resource Pack.  
  → [Download here](https://github.com/strivo-dev/NekoUI-Resources/releases/tag/1.0)

#### Language
- Added Indonesian translation.

#### Deprecated
- Updated deprecated code references.

---

### NekoUI 1.0-beta+mc1.21 (29/05/2025)

#### UI
- Custom title screen.
- Animated widgets.

#### Mod Features
- Added update reminder and built-in updater.
- Added Discord Rich Presence.
- Supported Fabric and NeoForge loaders.
- Supported Minecraft 1.21.
- Fixed config not saving properly.
- Resolved mod conflict issues.

#### Background
- Only static backgrounds available in this version.

#### Other
- General code quality improvements.

---

## Alpha Versions

### NekoUI v1.0-beta (31/07/2024)
#### Background
- Added Blue Archive backgrounds (Yuuka, Noa, Miyu, Kotama).

#### Config
- Background switching through mods config.
- Initial mods config implementation.