<!-- ELUCENIA technical documentation · controle-da-asma-gina · zh · no clinical/professional/rights approval -->

# 哮喘症状控制（GINA）

[条件、来源与许可](https://elucenia.org/zh/tools/controle-da-asma-gina)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 每周日间症状超过 2 次

`diurno`

### 哮喘导致夜间醒来

`noturno`

### 缓解药物（SABA）使用超过每周 2 次

`alivio`

### 哮喘导致活动受限

`limit`

## 方法版本

GINA策略2021：4周症状控制，4问；缓解用SABA；0/1–2/3–4

## 已记录的公式

统计过去4周存在的项目：日间症状\>2次/周；因哮喘夜间醒来；缓解用SABA\>2次/周（不含运动前使用）；活动受限。

0=控制良好 · 1–2=部分控制 · 3–4=未控制。

## 限制与适用人群

此处计算的GINA 2021评估涵盖成人和年龄大于5岁的儿童过去四周的症状控制，缓解药物问题指短效β受体激动剂（SABA）。该计数不能全面评估未来急性加重风险、肺功能、合并疾病、吸入技术或治疗依从性。症状控制与哮喘严重程度并不等同。材料的改编仍受权利持有人规定的条件约束。

## 参考文献

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

哮喘控制良好

维持治疗；若已控制3个月，可考虑降阶。


### 2

哮喘部分控制

在升级治疗前，检查吸入技术、依从性、合并症和危险因素。


### 3

哮喘未控制

检查技术、依从性和诱因；考虑升级治疗。

