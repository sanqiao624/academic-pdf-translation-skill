# Materials and Manufacturing Terminology

Read this reference only when the source is substantially about materials science, mechanical or manufacturing engineering, machining, surface engineering, welding or joining, or additive manufacturing. Do not apply it to an unrelated paper solely because it contains generic words such as `material`, `process`, `surface`, `sample`, or `build`.

The paper's explicit definitions and the user's paper-specific terminology take precedence. Use the table and distinctions below to resolve genuine ambiguity, then keep the selected translation consistent throughout the paper.

## Context Decisions

- Translate `microstructure` as `微观组织` in metallurgy and materials characterization unless the paper clearly uses it in a different disciplinary sense.
- Translate `texture` as `织构` when it means crystallographic preferred orientation; use `纹理` only for visual or surface-pattern meaning.
- Distinguish `surface morphology` (`表面形貌`) from `microstructure` (`微观组织`) and `topography` (`表面形貌` or `表面拓扑形貌`, according to the measurement context).
- Distinguish `grain` (`晶粒`) from `particle` (`颗粒`) and `powder` (`粉末`). Do not translate all three as `颗粒`.
- Choose among `试样`, `样品`, `工件`, `基板`, and `基体` from the object's role, not from the English noun alone.
- Translate process names according to the actual mechanism. Do not collapse `grinding`, `lapping`, `polishing`, `machining`, `deposition`, `welding`, and `joining` into a generic `加工`.
- Keep established alloy designations, temper designations, standard numbers, instrument models, and process abbreviations unchanged.
- For a term with competing Chinese names, use the paper's definition, figures, and field usage to select one form and record the alternative only when it prevents ambiguity.

## Preferred Terms

| English | Preferred Chinese and context |
|---|---|
| material removal rate | 材料去除率 |
| surface roughness | 表面粗糙度 |
| surface morphology | 表面形貌 |
| subsurface damage | 亚表面损伤 |
| microstructure | 微观组织；材料学语境下通常不译为“微结构” |
| grain / grain boundary | 晶粒 / 晶界 |
| crystallographic texture | 晶体学织构；上下文明确后可简称“织构” |
| phase / phase transformation | 相 / 相变 |
| precipitate / precipitation | 析出相或析出物 / 析出；按组织与过程语境确定 |
| substrate | 基板 / 基体；沉积承载板常用“基板”，作为材料基体时常用“基体” |
| deposit / deposited layer | 沉积体 / 沉积层；按对象形态确定 |
| deposition | 沉积；不要在未说明堆焊机制时擅自译为“堆焊” |
| additive manufacturing | 增材制造 |
| build direction | 构建方向 / 成形方向；选择后全文统一 |
| friction stir deposition | 搅拌摩擦沉积 / 摩擦搅拌沉积；依论文及领域惯用名称统一，不与搅拌摩擦焊混同 |
| additive friction stir deposition | 增材搅拌摩擦沉积 / 增材摩擦搅拌沉积；首次出现时保留 `AFSD` |
| friction stir welding | 搅拌摩擦焊；保留 `FSW` |
| heat-affected zone | 热影响区；保留 `HAZ` |
| thermo-mechanically affected zone | 热机械影响区；保留 `TMAZ` |
| dynamic recrystallization | 动态再结晶 |
| interfacial bonding | 界面结合 |
| polishing | 抛光 |
| grinding | 磨削 |
| lapping | 研磨 / 研抛；按工艺定义确定 |
| abrasive / abrasive grain | 磨料 / 磨粒 |
| workpiece | 工件 |
| feed rate | 进给速度；若定义为每齿或每转进给量，应按原定义翻译 |
| tool wear | 刀具磨损 / 工具磨损；按工具类型确定 |
| experimental setup | 实验装置 / 实验系统；按语境确定 |
| yield strength | 屈服强度；保留原文规定的偏移量或测试定义 |
| ultimate tensile strength | 抗拉强度 / 极限抗拉强度；按论文定义与领域惯例确定 |
| elongation | 伸长率；保留标距和测试条件 |
| Vickers hardness | 维氏硬度；保留载荷标记，例如 `HV0.2` |

## High-Risk Checks

- Verify alloy numbers, temper states, chemical compositions, phase names, heat-treatment temperatures, dwell times, strain rates, feed rates, rotation rates, traverse speeds, layer heights, and force or torque values against the source.
- Preserve distinctions among mass fraction, volume fraction, atomic fraction, and weight percent; do not normalize them to one representation.
- Preserve `rpm`, `mm/min`, `μm`, `MPa`, `GPa`, `HV`, and other units exactly unless the user requests conversion.
- Keep processing direction labels such as `BD`, `TD`, `ND`, `RD`, and `PD` tied to the source definition. Do not infer their meaning from a different manufacturing process.
- Do not silently reinterpret `as-built`, `as-deposited`, `as-cast`, `as-received`, `solution-treated`, or `aged`; translate each according to the stated material condition and keep the distinction throughout.

