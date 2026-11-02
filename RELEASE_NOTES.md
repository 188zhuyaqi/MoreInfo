# MoreInfo 1.0.2 — 潜影盒预览与 1.26.60.4 适配

- 新增 Minecraft 1.26.60.4 适配，修复新版经典界面下装备和状态信息不显示的问题。
- 新增潜影盒 27 格内容预览，可在快捷栏、背包、箱子、木桶和末影箱等界面查看物品图标与数量，并调整缩放和位置。
- 快捷栏预览与背包、容器预览可分别开关；预览启用时隐藏对应的原版文字说明，避免重复显示。
- 新增“点击外部关闭预览”（默认关闭）：在背包、容器里，第一次外部点击只关闭面板并保留物品选中，下一次点击正常操作。
- 新增“物品栏预览显示时长”，单位为秒，默认 `0` 持续显示；仅对快捷栏选中预览计时，背包、容器及鼠标悬浮预览不受影响。
- 支持 `§` 代码改名后的彩色潜影盒名称；空盒子正常渲染空格子，名称和数量保持稳定显示。
- 保留装备、副手双击交互、精确耐久、FPS、电池温度及中英文游戏内设置。
- 支持 Minecraft 1.26.44.3、1.26.45.1、1.26.50.4、1.26.52.3 和 1.26.60.4（Android ARM64）。

潜影盒预览以客户端收到的数据为准，服务器未发送的内容无法显示。

# MoreInfo 1.0.2 — Shulker Box Previews and 1.26.60.4 Support

- Adds Minecraft 1.26.60.4 support and fixes missing equipment/status information in its updated classic UI.
- Adds 27-slot shulker box previews with item icons and counts in the hotbar, inventory, chests, barrels, ender chests, and other containers, with scale and position controls.
- Separate switches control hotbar and inventory/container previews. Enabled previews replace the corresponding vanilla text descriptions.
- Adds optional “Tap outside to close preview” (off by default): in inventories and containers, the first outside tap closes only the panel and keeps the item selected; the next tap works normally.
- Adds “Hotbar preview duration” in seconds, defaulting to `0` for persistent display. Only selected hotbar previews are timed; inventory, container, and mouse-hover previews are unaffected.
- Preserves `§` color codes in renamed shulker titles. Empty boxes display empty slots, and titles and counts remain stable.
- Retains equipment, double-tap offhand interaction, exact durability, FPS, battery temperature, and Chinese/English in-game settings.
- Supports Minecraft 1.26.44.3, 1.26.45.1, 1.26.50.4, 1.26.52.3, and 1.26.60.4 on Android ARM64.

Shulker previews use data received by the client; contents not sent by a server cannot be displayed.
