# 场景提示词扩写 Skill

> 给一个主题、物件、人物或一句粗糙的 AI 视频提示，扩成电影级的中文场景 / 图像提示词。

## 功能

- 从一个短主题扩写成分镜级或图像级提示词
- 覆盖镜头焦段、光圈、景深、布光、氛围、材质细节与负向提示
- 输出可直接用于 Midjourney / SD / DALL·E / 即梦等平台
- 中文为主，术语保留英文便于模型理解

## 用法

```bash
mkdir -p ~/.claude/skills/expand-scene-prompt
cp -r SKILL.md agents ~/.claude/skills/expand-scene-prompt/
```

对话里直接给主题，例如“帮我把‘雨夜便利店’扩成电影级画面提示词”。
