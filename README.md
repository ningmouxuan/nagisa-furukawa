# 古河渚 Codex 宠物

这个仓库保存了一套可直接使用的 Codex 自定义宠物资源，角色为《CLANNAD》中的古河渚。

![古河渚动作总览](nagisa-furukawa/contact-sheet.png)

## 角色信息

- 名称：古河渚
- 标识：`nagisa-furukawa`
- 风格：Q 版校园系
- 特征：短棕发、团子发饰、米白校服、温柔害羞气质

## 仓库内容

`nagisa-furukawa/` 目录包含以下文件：

- `pet.json`：宠物元信息
- `spritesheet.webp`：宠物动画图集
- `contact-sheet.png`：动作总览图
- `run-summary.json`：生成结果摘要

## 使用方法

如果你想在本机 Codex 中使用这只宠物，可以把 `nagisa-furukawa` 整个目录放到下面的位置：

```text
C:\Users\DEll\.codex\pets\
```

目标结构如下：

```text
C:\Users\DEll\.codex\pets\
  nagisa-furukawa\
    pet.json
    spritesheet.webp
```

其中：

- `pet.json` 是必需文件
- `spritesheet.webp` 是运行时使用的主图集
- `contact-sheet.png` 和 `run-summary.json` 主要用于预览和留档

## 说明

当前仓库保存的是已经完成的宠物成品，适合直接归档、分享或继续做轻量说明整理。

## 工作树

当前项目还保留了两个独立工作树，方便并行修改：

- 主仓库：`C:\Users\DEll\Documents\Codex\2026-05-17\111`
- 展示分支工作树：`C:\Users\DEll\Documents\Codex\2026-05-17\111-readme-polish`
- 宠物说明分支工作树：`C:\Users\DEll\Documents\Codex\2026-05-17\111-pet-docs`

对应分支：

- `master`
- `feature/readme-polish`
- `feature/pet-docs`
