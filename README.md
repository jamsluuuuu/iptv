# 直播源订阅

167 个直播频道：CCTV、卫视、地方、河北、港澳、台湾、海外。

## 订阅地址（电视 App 直接导入）

- jsDelivr CDN（国内友好，推荐）：https://cdn.jsdelivr.net/gh/jamsluuuuu/iptv@main/china-hk-mo-tw-live.m3u
- GitHub Raw：https://raw.githubusercontent.com/jamsluuuuu/iptv/main/china-hk-mo-tw-live.m3u

## 维护方式

每天 04:00 和 14:00 自动检测全部源的连通性与画面，失效源自动寻找并替换为核验过的真直播源；每天另有一次全网搜源，速度更快、画质更好的源在核验通过后自动替换。替换记录见 `status.json`。
