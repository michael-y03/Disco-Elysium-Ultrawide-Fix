# Disco Elysium – 32:9 / Super Ultrawide Fix

This mod makes Disco Elysium use 32:9 resolutions (5120×1440, 3840×1080) instead of capping at 21:9.

- ✅ Removes the forced black bars
- ✅ Widens the global UI canvas to match your monitor

![Dialogue on 32:9](screenshots/image1.png)
![Martinaise exterior 32:9](screenshots/image2.png)
![Whirling interior 32:9](screenshots/image3.png)

---

## Which download do I need? (Mono vs IL2CPP)

Disco Elysium exists in **two runtime builds**. You must pick the matching download.

**IL2CPP build**: your game folder contains `GameAssembly.dll`  
➡️ Use the **IL2CPP** files.

**Mono build**: your game folder contains `Disco Elysium_Data/Managed/Assembly-CSharp.dll`  
➡️ Use the **MONO** files.

---

## Install (easy way – includes BepInEx)

1. Download **one** of these:
   - **`DiscoElysium-32x9-v1.1.0-IL2CPP-easy.zip`**
   - **`DiscoElysium-32x9-v1.1.0-MONO-easy.zip`**
2. Extract it directly into your **Disco Elysium** game folder (same level as the game EXE).
   - After extracting you should have:
     - `Disco Elysium/BepInEx/...`
     - plus the loader files included with the easy install package
3. Launch the game.

---

## Install (plugin-only)

Already have the correct BepInEx installed for your game build?

1. Download **one** of these:
   - **`DiscoElysium-32x9-v1.1.0-IL2CPP-plugin-only.zip`**
   - **`DiscoElysium-32x9-v1.1.0-MONO-plugin-only.zip`**
2. Extract it directly into: `/Disco Elysium`
3. Launch the game.

---

## Notes / Compatibility

- **Build support:** **Mono + IL2CPP** (separate downloads).
- **Wrong build installed?** If you install the wrong one, the plugin won’t load. Check Mono vs IL2CPP above.
- **Test coverage:** Intro, Whirling-in-Rags (interior), Martinaise exterior, dialogue.
- **Resolutions:** Verified at 5120×1440 and 3840×1080.
- **Bundled loader:** The “easy install” packages include an **unmodified** BepInEx build for convenience.

---

## Known issues

- Some UI layouts may still be off in specific scenes.
- Intro “Begin” button isn’t clickable at this aspect — press **Enter** to continue.
- Only 32:9 verified (no guarantee for 48:9 / multi-monitor).

---

## Troubleshooting

- Check `BepInEx/LogOutput.txt` for `[DiscoElysium32x9] Plugin loaded.`
- Confirm you installed the correct build (Mono vs IL2CPP).
- If asking for help, include the first ~50 lines of `LogOutput.txt`.

---

## Nexus Mods

- https://www.nexusmods.com/discoelysium/mods/53

---

## License / Credits

- BepInEx: © BepInEx Team, distributed under **LGPL-2.1** (only in the “easy install” packages)
