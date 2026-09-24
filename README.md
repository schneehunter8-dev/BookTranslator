# BookTranslator（书译）

BookTranslator 是一款面向图片书籍的 Windows 屏幕 OCR 与悬浮翻译工具。

## 功能

- `Ctrl + Shift + Space` 框选屏幕区域并翻译；
- 选择目标窗口进行实时可见区域翻译；
- OCR 原文与译文均可复制；
- 滚动停止后再识别，过滤低置信度与重复内容；
- 缓存近期确认页面，返回时快速恢复译文；
- 合并书籍排版产生的硬换行。

## 隐私

OCR 在本机完成，不上传书页截图。只有识别后的文字会在用户首次明确授权后用于微软/必应翻译；拒绝后不发送文字，也不会反复提示。

## 下载

请前往 [Releases](../../releases/latest) 下载 `BookTranslator.exe`。

## 文件校验

```text
SHA-256  9C442CB867E437476859D79097D6765DEA6433C1EBF99F749A3C27693B4ECC5F
```

## 使用方法

1. 下载并启动 `BookTranslator.exe`；
2. 在主窗口选择译文语言；
3. 按 `Ctrl + Shift + Space` 后框选需要识别的区域；
4. 如需实时模式，在系统托盘菜单中选择目标窗口。

> 这是个人产品实践，目前仅提供 Windows 单文件版本。
