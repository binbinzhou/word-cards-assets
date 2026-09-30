# word-cards-assets

英语卡片学习小程序的公开运行时资源仓库。

当前版本：`v1.5.0`

## GitHub Pages

基础地址：

```text
https://binbinzhou.github.io/word-cards-assets/
```

示例：

```text
https://binbinzhou.github.io/word-cards-assets/v1/images/fruit/01-cherry.png
https://binbinzhou.github.io/word-cards-assets/v1/audio/fruit/fruit_cherry_en.mp3
```

## jsDelivr

固定 Tag 后可以使用：

```text
https://cdn.jsdelivr.net/gh/binbinzhou/word-cards-assets@v1.5.0/
```

示例：

```text
https://cdn.jsdelivr.net/gh/binbinzhou/word-cards-assets@v1.5.0/v1/images/fruit/01-cherry.png
https://cdn.jsdelivr.net/gh/binbinzhou/word-cards-assets@v1.5.0/v1/audio/fruit/fruit_cherry_en.mp3
```

不要使用 `@main`。资源更新时创建新的版本 Tag，不要覆盖已发布 Tag。

## 目录

```text
v1/
  manifest.json
  images/
    categories/
    fruit/
    vegetables/
    drinks/
    clothes/
    furniture/
    tableware/
    stationery/
    insects/
    dinosaur/
    birds/
    scenery/
    profession/
    movement/
    country/
    time/
    site/
  audio/
    fruit/
    vegetables/
    drinks/
    clothes/
    furniture/
    tableware/
    stationery/
    insects/
    dinosaur/
    birds/
    scenery/
    profession/
    movement/
    country/
    time/
    site/
```

`manifest.json` 记录文件路径、大小和 SHA-256，用于校验发布内容和后续迁移到云存储/CDN。

## 发布规则

1. 更新资源文件。
2. 校验所有图片和音频均可访问。
3. 更新 `manifest.json`。
4. 提交到 `main`。
5. 创建不可变 Tag，例如 `v1.5.0`。
6. 推送分支和 Tag。
7. 等待 GitHub Pages 发布完成。
8. 在微信开发者工具或真机验证。

## 许可

当前运行时课程图片已全部替换为 AI 生图；历史 Microsoft Fluent Emoji 来源和 MIT 许可证继续保留在：

```text
LICENSES/FLUENTUI-EMOJI-MIT-LICENSE.txt
```

发布前仍需确认所有图片、音频和 TTS 音频的最终使用授权。
