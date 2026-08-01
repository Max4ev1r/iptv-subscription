# APTV 国内电视订阅

这是由家中 Mac mini 实测后生成的个人 APTV 播放列表，当前目标为
CCTV-1 至 CCTV-17、CCTV-5+ 和 20 个主要省级卫视。

- 快速源：`https://raw.githubusercontent.com/Max4ev1r/iptv-subscription/main/tv-fast.m3u`
- 主源：`https://raw.githubusercontent.com/Max4ev1r/iptv-subscription/main/tv.m3u`
- 备用一：`https://raw.githubusercontent.com/Max4ev1r/iptv-subscription/main/tv-backup-1.m3u`
- 备用二：`https://raw.githubusercontent.com/Max4ev1r/iptv-subscription/main/tv-backup-2.m3u`
- EPG：`https://raw.githubusercontent.com/Max4ev1r/iptv-subscription/main/epg.xml.gz`
- 状态：`status.json`

推荐在 APTV 中分别添加上述四个订阅，再按“快速源、主源、备用一、备用二”
的顺序创建聚合配置。APTV 会合并同名频道，并在当前线路无法播放时自动切换
到下一条备用线路。

播放地址来自第三方公开候选库，本仓库不存储或转播视频。可用性、授权状态
和地域限制由各上游负责；如果权利人认为某条链接不应收录，请提出 issue，
对应候选会从本地来源池移除。
