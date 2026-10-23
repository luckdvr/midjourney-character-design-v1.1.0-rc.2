# 角色设计体验版 · Lite 0.1.0

用中文从零设计一个人物，输出一条完整的英文 Midjourney 提示词。CGI、二维动画、水墨插画等画风由你选择，也可以继续做简单修改。

**[下载体验版](https://github.com/luckdvr/midjourney-character-design-v1.1.0-rc.2/archive/refs/heads/main.zip)** · **[查看 Skill](midjourney-character-design-lite/SKILL.md)** · **[三个画风示例](midjourney-character-design-lite/references/examples.md)**

## 怎么用

下载并解压，把里面的 `midjourney-character-design-lite` 文件夹安装为 Skill。文件夹内直接包含 `SKILL.md`。

在支持点名 Skill 的对话里发送：

> 使用 $midjourney-character-design-lite：设计一个阴柔俊美的成年江湖公子，水墨淡彩，衣服有个性，完整全身。

收到提示词后，在 Midjourney 中选择你使用的模型，再粘贴提示词。这个体验版负责设计和整理提示词，不自动调用生图服务。

## 可以继续修改

- 保留长相和服装，换成二维动画。
- 衣服轮廓再有设计感一点，装饰集中在领口和腰部。
- 外套的金线改成同色暗纹，金耳饰保留。
- 其他设计不动，让脸和衣服正面亮一些。

没有次数限制，会沿用上一轮已接受的文字设计。

## 范围

支持从文字出发设计单个人类角色，输出完整全身提示词；保留基本比例、服装结构、材质、持物检查和简单修改。

参考图重设计、复杂盔甲、非人结构、多视图、多图一致性及高级 MJ 参数排查，不包含在这个体验包中。

本包已完成结构和文字用例检查，尚未实际生图验证。文字描述不能保证不同图片中的脸完全一致。
