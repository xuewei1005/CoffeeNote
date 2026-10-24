<p align="center"><img src="assets/logo.png" width="80" alt="CoffeeNote"></p>

# CoffeeNote · 咖啡风味笔记

记录每一杯咖啡的最佳参数。

**[English](README_EN.md)** · **[下载 Android APK](https://github.com/xuewei1005/CoffeeNote/releases/latest)** · **[更新日志](CHANGELOG.md)**

CoffeeNote 是一款面向家庭咖啡爱好者的 Android 咖啡记录工具。把咖啡豆、风味、养豆状态、冲煮参数和器具收进自己的豆仓，下一杯直接找到熟悉的配方。

无需注册账号。豆子、照片、器具与偏好保存在本机；豆袋文字识别在设备上完成。

> 本仓库用于发布 APK、功能介绍和示例截图，**不提供 App 源代码，也不授予开源许可**。

## 下载安装

- 最新版本：**2.8.0**。
- 系统要求：**Android 8.0 及以上**。
- 安装文件：[`CoffeeNote-2.8.0-release.apk`](https://github.com/xuewei1005/CoffeeNote/releases/download/v2.8.0/CoffeeNote-2.8.0-release.apk)，约 51 MiB。
- 通用安装包，包含 `arm64-v8a`、`armeabi-v7a`、`x86`、`x86_64`，无需另选架构。

打开 [Releases](https://github.com/xuewei1005/CoffeeNote/releases)，下载正式版 APK，在 Android 手机上按系统提示安装。更新时可直接覆盖旧版；卸载或清除应用数据前，请先导出备份。

SHA-256：

```text
65A4B9CDC67732B83C24F191AD4ECFE648821308D982DC5B9198C289EF51FD3A
```

## App 功能

| 功能 | 可以做什么 |
| --- | --- |
| 我的豆仓 | 保存品牌、豆名、产地、处理法、烘焙度、烘焙日、开封日和风味；搜索与筛选“在喝 / 养豆 / 喝完”。 |
| 豆袋识别 | 拍照或选择相册图片后自动识别并填入；内置中文、日文、韩文和英文/拉丁文字模型，识别语言可自动或手动选择。 |
| 字段匹配 | 辅助匹配 16 个品牌及其别名；区分商品名、产地、烘焙度和风味，过滤“非添加”等说明，无法确定时留空核对。 |
| 冲煮配方 | 在意式、手冲、冰手冲三个标签间单选切换；只有实际填写过参数的方法才会显示在卡片上，各方法参数独立，意式默认 25 秒。 |
| 养豆建议 | 按烘焙度、冲泡类型和部分处理法给出养豆天数，默认取建议区间中间值，也可自行调整。 |
| 咖啡器具 | 分组管理磨豆机、手冲器具和意式机，可关联到豆子的参数记录。 |
| 卡片管理 | 长按进入管理状态，拖动排序或点击“×”删除；删除前确认，顺序在重启后保留。 |
| 外观与语言 | 浅色、深色、跟随系统；界面支持简体中文、日本語、한국어、English，默认跟随系统语言。 |
| 本地备份 | 导出包含照片、豆子、器具和偏好的 JSON 备份；确认后合并导入，也可单独清理豆袋照片。 |
| 示例豆仓 | 无需先录入数据即可浏览示例，随时退出，不覆盖个人记录。 |

## 软件宣传片

[下载 / 观看 CoffeeNote 2.8.0 竖屏宣传片（1080×1920）](https://github.com/xuewei1005/CoffeeNote/releases/download/v2.8.0/CoffeeNote-2.8.0-promo-vertical-1080x1920.mp4)

宣传片和 APK 一起附在 [v2.8.0 Release](https://github.com/xuewei1005/CoffeeNote/releases/tag/v2.8.0) 中。

## 功能截图

以下是 App 实际界面在移动尺寸下的预览截图，使用虚构示例记录；品牌与豆名组合仅用于功能展示，不代表真实商品参数或推荐。没有使用用户个人豆仓、家庭照片或实际识别历史。截图不代表已完成真机摄像头识别准确率测试。

<table>
<tr>
<td align="center"><b>我的豆仓</b><br><img src="screenshots/01-shelf-light-zh.png" width="240" alt="浅色豆仓、搜索与状态筛选"></td>
<td align="center"><b>冲煮配方</b><br><img src="screenshots/02-bean-detail-zh.png" width="240" alt="意式参数、研磨度与状态"></td>
<td align="center"><b>豆袋档案</b><br><img src="screenshots/03-coffee-profile-zh.png" width="240" alt="拍照入口、豆名、烘焙度和风味标签"></td>
</tr>
<tr>
<td align="center"><b>排序与删除</b><br><img src="screenshots/04-sort-delete-zh.png" width="240" alt="长按卡片后的排序和删除状态"></td>
<td align="center"><b>咖啡器具</b><br><img src="screenshots/05-coffee-gear-zh.png" width="240" alt="磨豆机、滤杯和意式机分组管理"></td>
<td align="center"><b>主题与语言</b><br><img src="screenshots/06-settings-dark-zh.png" width="240" alt="深色主题、中日韩英语言与默认值"></td>
</tr>
<tr>
<td align="center"><b>备份与数据</b><br><img src="screenshots/07-backup-privacy-zh.png" width="240" alt="完整备份、导入和照片清理"></td>
<td align="center"><b>English settings</b><br><img src="screenshots/08-settings-dark-en.png" width="240" alt="English settings in dark mode"></td>
<td align="center"><b>English shelf</b><br><img src="screenshots/09-shelf-dark-en.png" width="240" alt="Dark coffee shelf with English example data"></td>
</tr>
</table>

## 快速上手

1. 点击右上角“＋”添加豆子，或先打开示例豆仓看看。
2. 点击“拍照”，选择拍摄或相册。自动填入后核对品牌、豆名与风味；反光、褶皱、模糊或缺字可能需要重拍、手动填写。
3. 选择一种冲泡类型，保留默认参数或填写自己的配方，然后保存。
4. 在“全部”且无搜索词时长按卡片可拖动排序；管理状态中点击“×”并确认即可删除。筛选或搜索结果中也可长按删除。
5. 点击左上角杯子图标进入设置，切换外观、语言、默认值或导出备份。

识别语言与界面语言独立设置。品牌词库只匹配读出的文字，不会仅凭某个商品名猜品牌；已有手动填写内容会保留。养豆天数是口感参考，请按自己的豆子与偏好调整。

## 数据说明

应用没有账号和云同步功能。JSON 备份包含本机记录及照片，换机时需要自行传输并导入；导入会保留已有相同记录 ID 的数据，并恢复备份中的偏好。点击 GitHub 作者链接会打开外部浏览器。

## 关于

作者：**曹好远** · GitHub：[@xuewei1005](https://github.com/xuewei1005)

问题或建议请通过 [Issues](https://github.com/xuewei1005/CoffeeNote/issues) 提交，并注明版本号、手机型号和重现步骤；请先遮盖照片或截图中的个人信息。
