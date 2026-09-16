---
AIGC:
  ContentProducer: '001191110102MAD55U9H0F10002'
  ContentPropagator: '001191110102MAD55U9H0F10002'
  Label: '1'
  ProduceID: 'f2b7487c-15cd-4ceb-bc89-dbf1b13c51fa'
  PropagateID: 'f2b7487c-15cd-4ceb-bc89-dbf1b13c51fa'
  ReservedCode1: '5e109181-df46-415b-a0ad-81c121e37bea'
  ReservedCode2: '5e109181-df46-415b-a0ad-81c121e37bea'
---

# 俄罗斯方块 · Tetris

一个纯原生 HTML/CSS/JavaScript 单文件实现的俄罗斯方块小游戏，无任何依赖，双击 `index.html` 即可离线游玩。

## 在线体验（GitHub Pages）

https://arbingan.github.io/tetris-test/

## 玩法与操作

| 按键 | 功能 |
| --- | --- |
| ← / → | 左右移动 |
| ↑ 或 X | 旋转 |
| ↓ | 软降（+1 分/格） |
| 空格 | 硬降（+2 分/格） |
| P | 暂停 / 继续 |
| R | 重新开始 |

## 功能特性

- 经典 7 种方块，7-bag 随机算法（发牌更均匀）
- 幽灵落点提示、下一个方块预览
- 消行计分（1/2/3/4 行 = 100/300/500/800 × 等级），每 10 行升级加速
- 最高分本地保存（localStorage）
- 支持键盘 + 移动端触屏虚拟按键

## 说明

仅做测试使用。

> AI生成