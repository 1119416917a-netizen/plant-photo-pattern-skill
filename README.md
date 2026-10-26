# Plant Photo Pattern Skill

把植物照片转成平面插画、线条艺术和无缝重复图案的 Codex skill。

## 能做什么

- 分析植物照片中的花朵、茎、叶片、姿态和主色
- 将摄影细节压缩为有限色块与干净线稿
- 组织旋转、翻转、缩放后的植物单元，生成可平铺的重复图案
- 区分“矢量风格位图”和真正可编辑的 SVG/矢量文件
- 检查植物辨识度、边缘连续性、色块闭合和无缝性

## 安装

将仓库目录复制到 Codex skills 目录：

```text
~/.codex/skills/plant-photo-pattern
```

## 调用

```text
使用 $plant-photo-pattern 把这张植物照片转成平面插画、线条艺术和无缝重复图案
```

## 文件结构

- `SKILL.md`：完整工作流、提示词结构和质量检查规则
- `agents/openai.yaml`：Codex 界面元数据

## 许可

本项目采用 MIT License，详见 [LICENSE](LICENSE)。
