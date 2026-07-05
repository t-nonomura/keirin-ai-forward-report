# ガールズ3連単バックテスト

期間: 2026-01-01 to 2026-07-03 / 生成: 2026-07-05T16:40:29+09:00

ガールズ3連単 v2 / 全レース購入 / 6-18点目安 / 選択買い目を各100円で平買い / 最終オッズ研究検証

## 主要ケース

| ケース | R数 | 買い目数 | 平均点数 | 的中率 | 投資額 | 払戻額 | 回収率 | top3除外ROI | 損益 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| ガールズ3連単 v2 セグメント安全切替（本線・7/1まで） * | 1068 | 10782 | 10.10 | 37.6% | 1,078,200円 | 1,261,400円 | 117.0% | 1.091 | 183,200円 |
| ガールズ3連単 v2 欠損補完ブリッジ（7/3まで・参考） | 1080 | 10984 | 10.17 | 38.0% | 1,098,400円 | 1,274,780円 | 116.1% | 1.083 | 176,380円 |

## 月別: ガールズ3連単 v2 セグメント安全切替（本線・7/1まで）

| 月 | R数 | 点数 | 的中率 | 回収率 | 損益 |
|---|---:|---:|---:|---:|---:|
| 2026-01 | 180 | 1080 | 17.8% | 71.5% | -30,760円 |
| 2026-02 | 176 | 1742 | 32.4% | 174.5% | 129,780円 |
| 2026-03 | 184 | 2406 | 59.8% | 105.7% | 13,630円 |
| 2026-04 | 169 | 1869 | 35.5% | 86.3% | -25,570円 |
| 2026-05 | 205 | 1921 | 37.6% | 96.6% | -6,480円 |
| 2026-06 | 152 | 1740 | 42.8% | 158.7% | 102,170円 |
| 2026-07 | 2 | 24 | 50.0% | 117.9% | 430円 |

## 注記

- Rendered in the same forward-report style: case comparison, month/week/day/venue breakdowns, and daily race details.
- Settlement is corrected as flat 100 yen per selected ticket. Hit returns use payout_units once and do not multiply by stake again.
- Final odds are used for this research report by user request; this is separate from a T-5/T-10 formal forward-grade verdict.
- Main case: segment safety switch through 2026-07-01. Monthly switch rules are selected only from prior-month races.
- For each evaluated month, segment cutpoints and switch triggers are computed only from races in earlier months. Current-month returns are used only after tickets are selected.
- Reference case: 12 missing races on 2026-07-02 and 2026-07-03 are filled by the entropy18 fallback source. Source choice is priority-based, not outcome-based.
- For each race this helper uses the first source in CLI order that has preselected tickets. Actual outcomes are used only to settle those already-selected tickets.
- 公開forward-reportのバックテスト表示に合わせ、ケース比較、月別/週別/日別/場別の内訳、日別レース詳細を出力しています。
- 払い戻しは選択買い目1点100円の平買いとして補正済みです。的中時は selected_ticket_details.payout_units の配当額だけを返戻に使い、stake倍率で二重計上しません。
- 今回はユーザー指定により最終オッズで検証しています。T-5/T-10の正式forward判定とは分けて扱います。
- 投資額、払戻額、損益は 1 unit = 100円で表示しています。
- 精算監査: error_count=0, audited_race_count=2148
