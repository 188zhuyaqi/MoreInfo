# 更新记录 / Changelog

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
