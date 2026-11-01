# Licensing

This tree combines several works. Each keeps the licensing it had when it was brought in; nothing here
relicenses anyone else's work. Check the folder or file in question.

| Component | Where | License |
|---|---|---|
| WarcraftXL modules and their native ports (loot beam, visuals, quest tracker, unit outline, M3/DDS, physics, grass, and others) | `Engine/Source/ModernAssets/Wxl*`, and the files elsewhere (mostly under `WoW/Source/**/Linux`) whose header says "Copyright (C) 2026 WarcraftXL" or "GPL-3.0-or-later" (about 90 files) | **GPL-3.0-or-later**. Full text: `Engine/Source/ModernAssets/WxlLootBeam/LICENSE` and `Engine/Source/ModernAssets/WxlVisuals/LICENSE`. Imported files keep their headers. |
| wowdecomp reconstruction of the 3.3.5a client (`Engine/`, `WoW/`) by Saty, with the forks by STRHercules and RosemyneH | most of `Engine/Source` and `WoW/Source` | The upstream projects publish **no license file or license statement**. No license has been added or implied here; it is credited and used as published. |
| Third-party libraries | `ThirdParty/` (bzip2, expat, FreeType, zlib, PCRE, Dear ImGui, NVAPI, xvidcore, ...) and `Engine/Source/SoundEngine/fmodex` | Their own licenses, in each folder (`LICENSE`, `COPYING`, ...). |
| Linux platform layer and ports added in this repository | `Engine/Source/Os/Linux`, `WoW/**/Linux`, `tools/`, `tests/` | Files derived from a WarcraftXL module carry that module's GPL-3.0-or-later header. Other new code has no separate license declared yet. |
| Installer, launcher and release packaging | the `fta-linux-client` repository | GPL-3.0-or-later (`LICENSE` there). |

Game data (MPQ archives, DBC files, textures, models) is **not** part of this repository and belongs to Blizzard
Entertainment; you need your own copy of a client.

If you distribute binaries built from this tree, the combined work includes both GPL-3.0-or-later code and
code with no declared license, so check the position with the upstream authors before doing so.
