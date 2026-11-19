---
name: value-metric
description: |
  Picks the value metric so a large buyer and a small buyer do not pay the same amount.
  Use when everyone pays one flat price regardless of the value they get.
  Trigger with "价值单位", "一个价", "大客户", "value metric", "该涨价"
---

# 按价值收费，不要大家一个价

来源：Patrick Campbell。定价杠杆里，按什么收费通常比数字本身更值得先定。多数公司大约三年才改一次价格；太久没改，就该再看。

## When to use
- 客群大小差很多，账单却一样。

## When not to use
- 你卖的是一件物理商品，用量不会跟着价值变。先别套软件的按量逻辑。

## Required inputs
- 最小和最大的客户：{{谁在付钱}}
- 现在怎么计价：{{现在的价}}
- 价值跟着什么变大：{{价值跟着什么变}}

## The framework
先定收费单位：按人、按次数、按结果，而不是先吵一个数字。单位选对，大客户付得起他们得到的，小客户不必为用不到的规模买单。数字本身可以很久不动；如果已经很久没有认真改过，你欠一次重新定价，而不是再加功能。

## Workflow
1. 用 {{价值跟着什么变}} 写一个客户自己算得清的单位。算不清的，换。
2. 用这个单位给 {{谁在付钱}} 各写一笔月费怎么变。两笔不该相等。
3. 对照 {{现在的价}}，指出谁被多收、谁被少收。
4. 这周只改单位的说法和两档价格，不改产品。
5. 写明什么样的拒绝说明单位错了，什么样的拒绝只是数字高了。

## Failure patterns
- 先拍一个数字，再找理由解释。
- 用客户看不懂的内部成本做单位。
- 大客户和小客户继续付同一笔。

## Output format
- 收费单位
- 小客户和大客户各一笔
- 这周只改的价
- 拒绝时怎么判断
