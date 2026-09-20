# 404TV

北京联通 IPTV 直播源播放列表。

## 使用

将 `404TV.m3u` 导入支持 M3U 的播放器（如 PotPlayer、IINA、Kodi、电视盒子）即可。

包含 90 个频道：央视 21 个、卫视 35 个（含北京本地频道）、数字付费 34 个。

## 说明

- 播放地址为 `rtp://` 组播流，**仅在北京联通 IPTV 网络环境下可用**，其他网络或运营商会无法播放。
- 部分频道带 `catchup-source` 回看地址，支持时移回放（播放器需支持该属性）。
- 频道台标来自 [zzzz0317/beijing-unicom-iptv-playlist](https://github.com/zzzz0317/beijing-unicom-iptv-playlist)。
