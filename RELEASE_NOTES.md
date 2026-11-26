# MoreInfo 1.0.8

- 修复了在部分材质包和服务器环境下，快捷栏包含独立贴图物品（如时钟）时 HUD 装备栏与潜影盒预览出现贴图错乱的问题；统一将 HUD 绘制移至界面合批完成后执行，提升整体兼容性与稳定性。
- Fixes HUD equipment and shulker preview texture corruption with certain resource packs when standalone-texture items (such as clocks) are in the hotbar, and unifies HUD rendering to run after UI batching finishes for improved compatibility and stability.
