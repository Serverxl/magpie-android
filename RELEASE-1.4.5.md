# 1.4.5 发布记录

## 结果

| 项 | 值 |
|---|---|
| Release | https://github.com/yqing004-boop/magpie-android/releases/tag/v1.4.5 |
| tag | v1.4.5 |
| commit | 1e023b3 |
| APK | magpie-android-1.4.5.apk（77,803,466 B） |
| SHA-256 | c062b0ae83d3fc3a1e8fe20de018d316cd317063a9e988fed0a8dce89ed6691c |
| GitHub | 已发布（非草稿、非预发布） |
| 蓝奏云 | https://wwbcx.lanzout.com/ifsvQ4g71oha 提取码 174v |

## 本版内容

- 账号页「添加供应商」换成「刷新模型」「全部模型」两个按钮
- 全部模型弹窗：每个模型显示倍率 + 能力胶囊（免费/视觉/推理/生图/生视频）+ 模型 id；长按复制 pid/mid
- 局域网开关与 magpie settings.LAN 双向同步
- 通知栏地址固定 127.0.0.1
- 菜单加「复制网页登录链接」

## 备注

release.sh 的 Release 创建这次又失败（临时文件 .code 未生成，Traceback），
commit/tag 已推，Release 与 APK 手动补建补传。脚本的 Release 创建分支待修。
