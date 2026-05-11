# Standard options

## Video settings

| Option | Setting | Vanilla | Renice³ |
|---|---|---:|---:|
| `graphicsPreset` | Uses a custom graphics preset because Renice³ combines performance-focused options with a few visual exceptions instead of using a fully vanilla preset. | `"fancy"` | `"custom"` |
| `renderDistance` | Sets how many chunks are rendered around the player. Renice³ uses 10 chunks as a balanced visibility range for normal gameplay. | `16` | `10` |
| `simulationDistance` | Sets how many chunks around the player continue running game logic, such as entities, block updates and redstone. | `12` | `10` |
| `biomeBlendRadius` | Controls how smoothly biome colors blend between nearby blocks. Lower values reduce blending work and make biome transitions sharper. | `2` | `1` |
| `entityDistanceScaling` | Controls how far entities are rendered compared with the default entity render range. | `1.0` | `0.75` |
| `entityShadows` | Toggles shadows below entities. Disabling this removes a small visual effect from mobs, players and other rendered entities. | `true` | `false` |
| `cutoutLeaves` | Keeps leaves in cutout mode, making leaf blocks visually clearer while avoiding heavier transparency behavior. | `true` | `true` |
| `textureFiltering` | Controls texture filtering. Renice³ keeps it disabled, preserving a sharper pixel-art look and avoiding extra filtering. | `1` | `0` |
| `mipmapLevels` | Controls how distant textures are downscaled. Renice³ keeps mipmaps enabled, but lowers the level from the vanilla value. | `4` | `2` |
| `particles` | Controls particle density. Renice³ uses the decreased particle setting to reduce visual clutter and particle rendering load. | `0` | `1` |
| `weatherRadius` | Limits the radius where weather effects are visually processed around the player. | `10` | `5` |
| `prioritizeChunkUpdates` | Controls how chunk updates are prioritized by the chunk builder. Renice³ uses the lower configured priority value. | `1` | `0` |

## Interface and game settings

| Option | Setting | Vanilla | Renice³ |
|---|---|---:|---:|
| `guiScale` | Sets the user interface scale. Renice³ uses a fixed scale of 3 instead of automatic scaling. | `0` | `3` |
| `operatorItemsTab` | Enables the operator items tab in Creative mode when the player has the required permissions. | `false` | `true` |
| `tutorialStep` | Controls the vanilla tutorial hint state. Renice³ sets it to none so tutorial hint popups do not appear. | `movement` | `none` |

## Hidden options

| Option | Setting | Vanilla | Renice³ |
|---|---|---:|---:|
| `joinedFirstServer` | Marks the first-server flow as already completed, preventing the related first-time hint from appearing again. | `false` | `true` |
| `onboardAccessibility` | Controls whether the accessibility onboarding screen is shown during the initial setup flow. | `[no data]` | `false` |
| `skipMultiplayerWarning` | Skips the vanilla multiplayer warning screen before entering multiplayer. | `false` | `true` |
| `telemetryOptInExtra` | Controls the optional extra telemetry opt-in state. Renice³ keeps this disabled. | `false` | `false` |

## Resource packs

| Option | Setting | Vanilla | Renice³ |
|---|---|---:|---:|
| `resourcePacks` | Stores the enabled resource packs. Renice³ enables vanilla resources plus Continuity resources for connected-texture-related visuals and the glass pane culling fix. | `[]` | `["vanilla", "continuity:default", "continuity:glass_pane_culling_fix"]` |
| `incompatibleResourcePacks` | Stores resource packs that the game treats as incompatible but still allows or tracks in the options file. | `[]` | `[]` |
