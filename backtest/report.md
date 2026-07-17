# ガールズ3連単バックテスト

期間: 2026-01-01 to 2026-07-07 / 生成: 2026-07-17T15:33:21+09:00

ガールズ3連単 v2 / 全ガールズ毎レース購入 / 6-18点目安 / 選択買い目を各100円で平買い / 最終オッズ研究検証

## 主要ケース

| ケース | R数 | 買い目数 | 平均点数 | 的中率 | 投資額 | 払戻額 | 回収率 | top3除外ROI | 損益 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| ガールズ3連単 v2 core ticket model gate keep60/prob（2026-07-07まで・最終オッズ研究） * | 1100 | 8227 | 7.48 | 35.9% | 822,700円 | 972,260円 | 118.2% | 1.078 | 149,560円 |

## 月別: ガールズ3連単 v2 core ticket model gate keep60/prob（2026-07-07まで・最終オッズ研究）

| 月 | R数 | 点数 | 的中率 | 回収率 | 損益 |
|---|---:|---:|---:|---:|---:|
| 2026-01 | 180 | 1080 | 17.8% | 71.5% | -30,760円 |
| 2026-02 | 176 | 1212 | 26.1% | 135.0% | 42,430円 |
| 2026-03 | 184 | 1973 | 57.1% | 120.2% | 39,910円 |
| 2026-04 | 169 | 1090 | 31.4% | 83.6% | -17,930円 |
| 2026-05 | 205 | 1503 | 44.9% | 149.3% | 74,150円 |
| 2026-06 | 152 | 1078 | 36.8% | 141.7% | 44,970円 |
| 2026-07 | 34 | 291 | 32.4% | 89.0% | -3,210円 |

## 注記

- Rendered in the same forward-report style: case comparison, month/week/day/venue breakdowns, and daily race details.
- Settlement is flat 100 yen per selected ticket. Hit returns use dataset/selected_ticket_details payout_units once and do not multiply by selected_count or stake again.
- Final odds are used for this research report by user request; this is separate from a T-5/T-10 formal forward-grade verdict.
- Scope: all girls races from 2026-01-01 through 2026-07-07, always buy, 6-18 selected tickets target.
- The displayed candidate is the current core ticket model gate best: keep60/prob/source-count fill after 40-80 and 5-20 gate stages.
- Strict research gate note: overall ROI and hit-rate pass the current target, while high-odds-hit-excluded ROI remains below 1.00 and is still under audit.
- 公開forward-reportのバックテスト表示に合わせ、ケース比較、月別/週別/日別/場別の内訳、日別レース詳細を出力しています。
- 払い戻しは選択買い目1点100円の平買いとして補正済みです。的中時は selected_ticket_details.payout_units の配当額だけを返戻に使い、stake倍率で二重計上しません。
- 今回はユーザー指定により最終オッズで検証しています。T-5/T-10の正式forward判定とは分けて扱います。
- 投資額、払戻額、損益は 1 unit = 100円で表示しています。
- 精算監査: error_count=0, audited_race_count=1100
