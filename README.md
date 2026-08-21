# 野猪的随听广播源

这是给 **野猪的随听** 使用的网络广播列表仓库，主要保存可导入 APP 的 `radio.m3u` 电台源。

## 订阅地址

在 APP 里导入下面这个 Raw 链接：

```text
https://raw.githubusercontent.com/xcq8080/radio-list/main/radio.m3u
```

## 使用方法

1. 打开 **野猪的随听**。
2. 进入 `FM收音机`。
3. 点击 `导入源`。
4. 粘贴上面的 Raw 链接。
5. 保存后，APP 会读取 `radio.m3u` 里的网络电台。

## 文件格式

本仓库使用标准 M3U 格式：

```m3u
#EXTM3U
#EXTINF:-1,电台名称
https://example.com/live.m3u8
#EXTINF:-1,另一个电台
https://example.com/radio.mp3
```

## 说明

网络电台直播地址可能会失效、限地区或临时维护。如果某个频道无法播放，通常需要更换新的直播源地址。

建议定期检查 `radio.m3u`，删除失效源，保留可播放源。
