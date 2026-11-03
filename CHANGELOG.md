# 更新记录 / Changelog

## 1.0.4

- 修复了部分材质包不兼容问题。
- Fixed compatibility issues with some resource packs.

## 1.0.3

- 修复测试版切换彩色潜影盒时的闪退，修正颜色编号读取所使用的内部对象类型。
- Fixes a development-build crash when selecting colored shulker boxes by correcting the internal object type used to read their color value.
- 潜影盒预览面板随盒子颜色变化，覆盖未染色和全部 16 种染色；彩色边框搭配同色系深色底板，物品图标保持原色，快捷栏、背包、容器与鼠标悬停预览保持一致。
- Shulker preview panels follow the box color, including undyed and all 16 dyed variants. Colored borders and dark matching backgrounds preserve original item colors across hotbar, inventory, container, and mouse-hover previews.
- LL 的 MoreInfo 设置中新增独立 Debug 分组，提供日志开关与实际保存目录。默认关闭，开启后将玩家名称、XUID、设备及模组诊断写入本机日志，便于复现问题。
- Adds a Debug category to MoreInfo's LL settings, with a logging switch and the actual log location. Off by default; when enabled, player name, XUID, device details, and mod diagnostics are recorded locally to help reproduce issues.
- 补充背包主区域、背包内快捷栏和容器的原版槽位鼠标悬停预览，移开后隐藏，不受快捷栏显示时长限制；OTG 鼠标悬停预览已由玩家实测通过。
- Adds native slot-hover shulker previews in the main inventory, its bottom hotbar, and containers, hiding on mouse exit and ignoring the hotbar duration. OTG mouse-hover previews have passed player testing.

## 1.0.2

- 新增 Minecraft 1.26.60.4 支持，并修复新版经典界面下快捷栏装备与状态信息不显示的问题。
- Adds Minecraft 1.26.60.4 support and fixes missing equipment/status information in its updated classic UI.
- 新增潜影盒 27 格内容预览，支持快捷栏、背包及其他容器，可调整大小与位置，并分别控制两类预览的显示。
- Adds 27-slot shulker box previews in the hotbar, inventory, and containers, with scale/position controls and separate visibility switches.
- 预览启用时替换对应的原版文字说明；修复名称与数量闪烁，支持 `§` 彩色名称，空盒子正常显示空格子。
- Enabled previews replace corresponding vanilla descriptions. Fixes title/count flicker, supports `§` colored names, and renders empty boxes as empty slots.
- 新增可选“点击外部关闭预览”（默认关闭），在背包和容器中保留物品选中状态，下一次点击正常执行原版操作。
- Adds optional “Tap outside to close preview” (off by default), preserving the selected item in inventory/container screens so the next tap works normally.
- 新增“物品栏预览显示时长”（秒，默认 `0` 持续显示），仅对快捷栏选中预览计时；背包、容器及鼠标悬浮预览不受影响。
- Adds “Hotbar preview duration” in seconds, defaulting to `0` for persistent display. Inventory, container, and mouse-hover previews are unaffected.

## 1.0.1

- 新增 Minecraft 1.26.52.3 适配，单人世界与服务器中的显示、副手交互及连续操作均已通过真机测试。
- Adds Minecraft 1.26.52.3 compatibility, device-tested for rendering, offhand interaction, and repeated operations in both single-player and multiplayer.
- 新增游戏内语言设置，支持简体中文与英文并即时切换，默认使用简体中文。
- Adds an in-game language setting for instant switching between Simplified Chinese and English, defaulting to Simplified Chinese.

## 1.0.0

- 首个稳定版本：装备栏、副手槽、精确耐久、FPS、电池温度及游戏内设置均已完成。
- 新增副手双击装入、替换和空手卸下，使用游戏原版库存请求流程。
- 修复连续操作及切换世界或服务器后副手交互失效的问题。
- 三个支持版本均已完成本机测试，并验证测试服务器与世界切换流程。
- First stable release with armor/offhand HUD, exact durability, FPS, battery temperature, and in-game settings.
- Adds native double-tap offhand equip, replacement, and empty-hand unequip.
- Fixes repeated operations and world/server transition handling on all three supported versions.

## 0.0.20

- 启用全新的 MoreInfo 图标和公开介绍页面。
- 支持 Minecraft 1.26.44.3、1.26.45.1 与 1.26.50.4。
- 在快捷栏左侧显示四个装备槽与原版物品图标、附魔光效和耐久条。
- 长按装备槽可查看装备名称与精确耐久。
- 在快捷栏右侧显示 FPS 与电池温度。
- 提供位置、缩放、字号、耐久条和槽框样式等游戏内设置。
- 未知或不匹配的游戏版本会停止加载对应功能，避免使用错误适配。
