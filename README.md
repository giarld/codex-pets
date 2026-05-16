# Codex Pets

My custom Codex pets.

## Pets

| Preview | ID | Name | Description | Add |
| --- | --- | --- | --- | --- |
| <img src="./images/frierencodex-idle.gif" alt="FrierenCodex idle animation" width="120"> | `frierencodex` | FrierenCodex | Q版芙莉莲风格的冷静工程师宠物，带一本无字法典与终端工具气质。 | `npx codex-pets add frierencodex` |
| <img src="./images/jige-kunkun-idle.gif" alt="鸡哥（坤坤） idle animation" width="120"> | `jige-kunkun` | 鸡哥（坤坤） | 一个篮球主题的圆润黄色小鸡 Codex 宠物，昵称鸡哥（坤坤）。 | `npx codex-pets add jige-kunkun` |
| <img src="./images/xia-ren-idle.gif" alt="虾仁 idle animation" width="120"> | `xia-ren` | 虾仁 | 戴草帽、熊猫耳、表情包风格的虾仁宠物。 | `npx codex-pets add xia-ren` |

## Structure

Each pet lives in its own directory:

```text
<pet-id>/
  pet.json
  spritesheet.webp
```

`pet.json` defines the pet metadata:

```json
{
  "id": "pet-id",
  "displayName": "Pet Name",
  "description": "One short sentence.",
  "spritesheetPath": "spritesheet.webp"
}
```

The spritesheets are WebP atlases using the Codex pet layout:

```text
1536x1872
8 columns x 9 rows
192x208 per frame
```
