# ���¼�¼ / Changelog

## 1.0.4

- �޸��˲��ֲ��ʰ����������⡣
- Fixed compatibility issues with some resource packs.

## 1.0.3

- �޸����԰��л���ɫǱӰ��ʱ�����ˣ�������ɫ��Ŷ�ȡ��ʹ�õ��ڲ��������͡�
- Fixes a development-build crash when selecting colored shulker boxes by correcting the internal object type used to read their color value.
- ǱӰ��Ԥ������������ɫ�仯������δȾɫ��ȫ�� 16 ��Ⱦɫ����ɫ�߿����ͬɫϵ��ɫ�װ壬��Ʒͼ�걣��ԭɫ��������������������������ͣԤ������һ�¡�
- Shulker preview panels follow the box color, including undyed and all 16 dyed variants. Colored borders and dark matching backgrounds preserve original item colors across hotbar, inventory, container, and mouse-hover previews.
- LL �� MoreInfo �������������� Debug ���飬�ṩ��־������ʵ�ʱ���Ŀ¼��Ĭ�Ϲرգ�������������ơ�XUID���豸��ģ�����д�뱾����־�����ڸ������⡣
- Adds a Debug category to MoreInfo's LL settings, with a logging switch and the actual log location. Off by default; when enabled, player name, XUID, device details, and mod diagnostics are recorded locally to help reproduce issues.
- ���䱳�������򡢱����ڿ������������ԭ���λ�����ͣԤ�����ƿ������أ����ܿ������ʾʱ�����ƣ�OTG �����ͣԤ���������ʵ��ͨ����
- Adds native slot-hover shulker previews in the main inventory, its bottom hotbar, and containers, hiding on mouse exit and ignoring the hotbar duration. OTG mouse-hover previews have passed player testing.

## 1.0.2

- ���� Minecraft 1.26.60.4 ֧�֣����޸��°澭������¿����װ����״̬��Ϣ����ʾ�����⡣
- Adds Minecraft 1.26.60.4 support and fixes missing equipment/status information in its updated classic UI.
- ����ǱӰ�� 27 ������Ԥ����֧�ֿ�����������������������ɵ�����С��λ�ã����ֱ��������Ԥ������ʾ��
- Adds 27-slot shulker box previews in the hotbar, inventory, and containers, with scale/position controls and separate visibility switches.
- Ԥ������ʱ�滻��Ӧ��ԭ������˵�����޸�������������˸��֧�� `��` ��ɫ���ƣ��պ���������ʾ�ո��ӡ�
- Enabled previews replace corresponding vanilla descriptions. Fixes title/count flicker, supports `��` colored names, and renders empty boxes as empty slots.
- ������ѡ������ⲿ�ر�Ԥ������Ĭ�Ϲرգ����ڱ����������б�����Ʒѡ��״̬����һ�ε������ִ��ԭ�������
- Adds optional ��Tap outside to close preview�� (off by default), preserving the selected item in inventory/container screens so the next tap works normally.
- ��������Ʒ��Ԥ����ʾʱ�������룬Ĭ�� `0` ������ʾ�������Կ����ѡ��Ԥ����ʱ���������������������Ԥ������Ӱ�졣
- Adds ��Hotbar preview duration�� in seconds, defaulting to `0` for persistent display. Inventory, container, and mouse-hover previews are unaffected.

## 1.0.1

- ���� Minecraft 1.26.52.3 ���䣬����������������е���ʾ�����ֽ�����������������ͨ��������ԡ�
- Adds Minecraft 1.26.52.3 compatibility, device-tested for rendering, offhand interaction, and repeated operations in both single-player and multiplayer.
- ������Ϸ���������ã�֧�ּ���������Ӣ�Ĳ���ʱ�л���Ĭ��ʹ�ü������ġ�
- Adds an in-game language setting for instant switching between Simplified Chinese and English, defaulting to Simplified Chinese.

## 1.0.0

- �׸��ȶ��汾��װ���������ֲۡ���ȷ�;á�FPS������¶ȼ���Ϸ�����þ�����ɡ�
- ��������˫��װ�롢�滻�Ϳ���ж�£�ʹ����Ϸԭ�����������̡�
- �޸������������л��������������ֽ���ʧЧ�����⡣
- ����֧�ְ汾������ɱ������ԣ�����֤���Է������������л����̡�
- First stable release with armor/offhand HUD, exact durability, FPS, battery temperature, and in-game settings.
- Adds native double-tap offhand equip, replacement, and empty-hand unequip.
- Fixes repeated operations and world/server transition handling on all three supported versions.

## 0.0.20

- ����ȫ�µ� MoreInfo ͼ��͹�������ҳ�档
- ֧�� Minecraft 1.26.44.3��1.26.45.1 �� 1.26.50.4��
- �ڿ���������ʾ�ĸ�װ������ԭ����Ʒͼ�ꡢ��ħ��Ч���;�����
- ����װ���ۿɲ鿴װ�������뾫ȷ�;á�
- �ڿ�����Ҳ���ʾ FPS �����¶ȡ�
- �ṩλ�á����š��ֺš��;����Ͳۿ���ʽ����Ϸ�����á�
- δ֪��ƥ�����Ϸ�汾��ֹͣ���ض�Ӧ���ܣ�����ʹ�ô������䡣
