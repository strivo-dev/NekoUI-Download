# NekoUI Extension Policy
This document outlines the policy regarding **external extensions** in the NekoUI project, particularly background assets for both NekoUI: Java Edition and NekoUI: Bedrock Edition.

---

## Overview
NekoUI supports **external custom backgrounds** (static or animated) via a flexible resource pack system.  
These background extensions are **not part of the core mod**, and may be created, modified, and shared independently.

---

## Community Rules
- **NSFW backgrounds** or any sexually explicit, violent, or otherwise inappropriate content are **strictly prohibited** in any official NekoUI community (Discord, forums, etc.).
- You may use such content **for personal use only**, or **share it privately or outside the official community**.

---

## NekoUI: Bedrock Edition
### 1. Default Background
- By default, the Bedrock Edition using minecraft default paranoma backgrounds.
- No third-party, franchise-based, or copyrighted backgrounds are included.

### 2. External Background Support
- External backgrounds must follow the structure defined in [this guide](https://discord.com/channels/1214492329046581278/1396857398857302217/1396857398857302217).
- Frame count is limited to **100 frames** with filenames like `hans_common_100.png`.

### 3. Modification Restrictions
It is **strictly prohibited** to modify the following core files:
- All files inside `.hans_common_files`, except:  
  - `hans_animated_background.json`  
  - `hans_loading_background.json`
- All files in `hans_common_files_experimental`

If you have your own modifications with your own code, you are encouraged to use the `modifications`: `{}` section inside your extension, and place them under:
- The `ui/` folder
- Or other folders explicitly marked as modifiable

There are **no restrictions** on modifying:
- UI textures
- Fonts
- Any non-core aesthetic elements

---

## NekoUI: Java Edition
### 1. Default Background
- The mod includes only a **solid black static background** by default.
- No third-party or copyrighted material.

### 2. External Background Support
- Custom backgrounds must follow this folder structure:  
  `assets/nekoui/background/<name>/`
- Animated backgrounds should contain sequential frame files (e.g., `frame0.png`, `frame1.png`, etc.).
- There is **no frame limit**, but system performance may vary depending on the number and resolution of frames.

---

## Permissions
You are **allowed to**:
- Create and share your own background packs.
- Modify or remix unofficial backgrounds.
- Publicly distribute your background packs (e.g., on GitHub, Modrinth, CurseForge).

You are **not allowed to**:
- Redistribute the NekoUI mod or compiled code with your background.
- Claim your extension as “official” or endorsed by the NekoUI team.
- Use commercial assets in your backgrounds unless you fully own or are licensed to use them.

---

## Disclaimer
- The Author (`nokarin`) is **not responsible** for any third-party extensions, user-submitted backgrounds, or IP violations.
- Users are fully responsible for complying with applicable copyright and intellectual property laws.

---

By using or creating extensions for NekoUI, you agree to this policy.  
For submissions, showcases, or questions, please contact the Author or join the official NekoUI Discord server.