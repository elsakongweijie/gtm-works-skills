---
name: jolt-indecision
description: |
  Diagnoses a stalled deal as indecision rather than a lost competitive bake-off, then uses JOLT.
  Use when a buyer says they need to think about it after a demo.
  Trigger with "没人拍板", "再看看", "丢单", "JOLT", "犹豫"
---

# 成交卡在犹豫，不在竞品

来源：Matt Dixon，《The JOLT Effect》。https://www.youtube.com/watch?v=cUzEgRetmC4

## When to use
- 对方没有选别人，只是停住了。

## When not to use
- 对方已经签了竞品。那时去复盘你讲错了什么，而不是做安心包。

## Required inputs
- 买家是谁：{{买家}}
- 他们停住时的原话：{{停住的话}}
- 你正准备加的动作：{{你在加码}}

## The framework
多数单子不是输给竞品，是输给犹豫。犹豫来自怕做错，不是怕错过。加大错过的恐惧，常常适得其反。JOLT：先判断犹豫有多深；给出一个明确建议，而不是更多选项；限制他们继续无止境地比较；把买错的风险从桌上拿掉。Challenger 的另一半是：不要只问对方今晚愁什么，指出一个他们还没看见、但你见过的风险。

## Workflow
1. 读 {{停住的话}}。分成两类：已经选了别人，或还没能做决定。
2. 若是犹豫：停掉 {{你在加码}} 里加大恐惧或加选项的部分。
3. 给 {{买家}} 一个建议：就他们的情况，买 / 不买 / 先做哪一小步。只留一个。
4. 写一个把风险拿掉的条件：试点范围、可退出、成功长什么样。
5. 补一句他们可能没看见的风险。必须是你真知道的，不许编。

## Failure patterns
- 用“名额不多了”推一个害怕犯错的人。
- 再发三份资料，让探索继续。
- 把“再看看”一律当成价格问题。

## Output format
- 这单卡在哪：竞品 / 犹豫
- 只留的一个建议
- 拿掉风险的条件
- 这周不要发的东西
