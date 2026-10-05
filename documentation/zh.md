<!-- ELUCENIA technical documentation · escala-de-resultados-de-glasgow · zh · no clinical/professional/rights approval -->

# Glasgow 预后量表（GOS）

[条件、来源与许可](https://elucenia.org/zh/tools/escala-de-resultados-de-glasgow)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 患者状态

`gos`

- `1` — 1 – 死亡
- `2` — 2 – 持续植物状态：无有意义反应，有睡眠觉醒周期
- `3` — 3 – 重度残疾：意识清楚，但日常生活依赖他人
- `4` — 4 – 中度残疾：独立但有后遗症（可使用交通、在保护性环境工作）
- `5` — 5 – 恢复良好：即使有轻微障碍也可恢复正常生活

## 方法版本

GOS/Jennett–Bond 1975：5类，4–5良好；不是8类GOSE

## 已记录的公式

选择最符合患者的类别。研究通常二分为良好（4、5）与不良（1至3）结局。

## 限制与适用人群

用于评估脑损伤后的功能结局，兼顾身体和精神方面的残障。应记录随访时间及五分类版本。不能将GOS视为等同于八分类的GOSE，也不能将其当作基于入院数据的预测。

## 参考文献

- [Jennett B, Bond M. Assessment of outcome after severe brain damage: a practical scale. Lancet, 1975.](https://doi.org/10.1016/S0140-6736(75)92830-5)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
