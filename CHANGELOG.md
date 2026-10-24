# Changelog / 更新日志

## 2.8.0 · 2026-10-24

- 冲泡类型改为意式、手冲、冰手冲三个固定单选标签；每种方法参数独立，只有实际填写的方法显示在卡片上。/ Replaced multi-select brewing types with three single-select tabs; each method has independent parameters and only methods with real values appear on cards.
- 新增删除当前冲煮信息、状态标签和自适应卡片高度；多产地逐行展示。/ Added delete-current-recipe, compact status labels, adaptive card heights and one-line-per-origin display.
- 强化多产地与不同处理法的配对，清理产地/风味分隔符并过滤包装说明。/ Improved pairing of multiple origins with their processing methods, cleaned field separators and filtered packaging disclaimers.
- 重新识别会更新识别到的字段，同时保留本次编辑中手动修改的内容。/ Re-recognition updates detected fields while preserving values manually changed during the current edit.
- 发布 2.8.0 APK、双语介绍、功能截图和竖屏宣传片；应用源代码不公开。/ Published the 2.8.0 APK, bilingual documentation, feature screenshots and vertical promo video; the application source remains private.

## 2.6.14 · 2026-10-24

- 长按卡片可排序或删除；删除前确认。/ Long-press cards to reorder or delete, with confirmation before deletion.
- 改进商品名、SOE 标题、产地和同行多字段拆分。/ Improved product-name, SOE-title, origin and multi-field row parsing.
- 过滤“非添加”等包装说明，防止进入风味标签。/ Filtered packaging disclaimers out of flavor tags.
- 新增 16 个品牌及别名的离线词库，保留不明确项供核对。/ Added an offline dictionary of 16 brands and aliases, leaving uncertain fields for review.

## 2.6.13 · 2026-10-24

- 新增浅色/深色/跟随系统主题，中日韩英界面及独立 OCR 语言设置。/ Added light/dark/system themes, four interface languages and independent OCR language settings.
- 简化拍照区，保留手动内容，支持本地完整备份、导入和照片清理。/ Simplified photo entry, preserved manual input and added full local backup, import and photo cleanup.
- 新增长按拖动排序，优化图标留白与页头透明背景。/ Added long-press reordering and improved icon spacing and header transparency.

## 2.6.12 · 2026-10-23

- 修复照片与弹窗事件、示例退出和器具输入问题，开封日期默认当天。/ Fixed photo/modal events, demo exit and gear input; the opened date defaults to today.

Screenshots use example data. Parser/UI regression checks and Android build/signature validation have been performed; real-device camera/OCR testing has not been completed.

截图使用示例数据。已完成字段规则/界面回归、Android 编译和签名校验，尚未完成真机摄像头/OCR 测试。
