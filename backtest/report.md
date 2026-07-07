# ガールズ3連単バックテスト

期間: 2026-01-01 to 2026-07-07 / 生成: 2026-07-07T22:25:48+09:00

ガールズ3連単 v2 / 全レース購入 / 6-18点目安 / 選択買い目を各100円で平買い / 最終オッズ研究検証

## 主要ケース

| ケース | R数 | 買い目数 | 平均点数 | 的中率 | 投資額 | 払戻額 | 回収率 | top3除外ROI | 損益 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| ガールズ3連単 v2 セグメント安全切替（7/7まで・研究） * | 1100 | 12102 | 11.00 | 43.5% | 1,210,200円 | 1,376,320円 | 113.7% | 1.067 | 166,120円 |

## 月別: ガールズ3連単 v2 セグメント安全切替（7/7まで・研究）

| 月 | R数 | 点数 | 的中率 | 回収率 | 損益 |
|---|---:|---:|---:|---:|---:|
| 2026-01 | 180 | 1080 | 17.8% | 71.5% | -30,760円 |
| 2026-02 | 176 | 1742 | 32.4% | 174.5% | 129,780円 |
| 2026-03 | 184 | 2521 | 66.8% | 112.1% | 30,530円 |
| 2026-04 | 169 | 1977 | 41.4% | 89.5% | -20,710円 |
| 2026-05 | 205 | 2395 | 54.1% | 113.7% | 32,920円 |
| 2026-06 | 152 | 1874 | 40.8% | 112.0% | 22,580円 |
| 2026-07 | 34 | 513 | 67.6% | 103.5% | 1,780円 |

## 注記

- Rendered in the same forward-report style: case comparison, month/week/day/venue breakdowns, and daily race details.
- Settlement is corrected as flat 100 yen per selected ticket. Hit returns use selected_ticket_details.payout_units once and do not multiply by stake again.
- Final odds are used for this research report by user request; this is separate from a T-5/T-10 formal forward-grade verdict.
- Scope: all girls races from 2026-01-01 through 2026-07-07, always buy, 6-18 selected tickets.
- Monthly segment switches are derived only from prior-month races; current-month outcomes are used only after tickets are selected.
- After 2026-07-04, missing primary coverage is filled by defensive_coverage_fallback, so the newest slice remains a stability-audit target.
- For each evaluated month, segment cutpoints and switch triggers are computed only from races in earlier months where both primary and defensive sources exist. Coverage fallback, when enabled, uses defensive tickets only for races missing from primary before outcomes are inspected. Current-month returns are used only after tickets are selected.
- 公開forward-reportのバックテスト表示に合わせ、ケース比較、月別/週別/日別/場別の内訳、日別レース詳細を出力しています。
- 払い戻しは選択買い目1点100円の平買いとして補正済みです。的中時は selected_ticket_details.payout_units の配当額だけを返戻に使い、stake倍率で二重計上しません。
- 今回はユーザー指定により最終オッズで検証しています。T-5/T-10の正式forward判定とは分けて扱います。
- 投資額、払戻額、損益は 1 unit = 100円で表示しています。
- 精算監査: error_count=0, audited_race_count=1100
