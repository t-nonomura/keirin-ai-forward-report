# ガールズ3連単バックテスト

期間: 2026-01-01 to 2026-07-16 / 生成: 2026-07-22T15:53:50+09:00

Girls trifecta v2: drop200+fill80-120 EV / all girls races / 6-13 tickets / flat 100 yen per selected ticket / final-odds research

## 主要ケース

| ケース | R数 | 買い目数 | 平均点数 | 的中率 | 投資額 | 払戻額 | 回収率 | top3除外ROI | 損益 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Girls trifecta v2 drop200 + fill 80-120 EV (through 2026-07-16 / final-odds research) * | 1162 | 7788 | 6.70 | 32.6% | 778,800円 | 893,740円 | 114.8% | 1.054 | 114,940円 |

## 月別: Girls trifecta v2 drop200 + fill 80-120 EV (through 2026-07-16 / final-odds research)

| 月 | R数 | 点数 | 的中率 | 回収率 | 損益 |
|---|---:|---:|---:|---:|---:|
| 2026-01 | 180 | 1080 | 17.8% | 71.5% | -30,760円 |
| 2026-02 | 176 | 1125 | 24.4% | 142.1% | 47,370円 |
| 2026-03 | 184 | 1404 | 38.0% | 100.5% | 740円 |
| 2026-04 | 169 | 1022 | 30.8% | 88.4% | -11,880円 |
| 2026-05 | 205 | 1366 | 40.0% | 170.3% | 96,020円 |
| 2026-06 | 152 | 1010 | 33.6% | 94.5% | -5,570円 |
| 2026-07 | 96 | 781 | 51.0% | 124.4% | 19,020円 |

## 注記

- Final odds are used by user request. This remains research-only and is not a live pre-race T-5 proof.
- Settlement is flat 100 yen per selected ticket. Hit returns use ticket-level dataset payout_units once and do not multiply by selected_count or stake again.
- Logic: remove selected tickets with odds >= 200, then fill from the same race 80-120 odds universe by prior-month EV until the source ticket count is restored, bounded to 6-13 tickets in this run.
- The 2026-01-01 to 2026-07-16 strict ROI110 research gate passed; the 2026-07-08 to 2026-07-16 62-race future slice still has top3 concentration caveats.
- 公開forward-reportのバックテスト表示に合わせ、ケース比較、月別/週別/日別/場別の内訳、日別レース詳細を出力しています。
- 払い戻しは選択買い目1点100円の平買いとして補正済みです。的中時は selected_ticket_details.payout_units の配当額だけを返戻に使い、stake倍や選択点数倍で二重計上しません。
- 今回はユーザー指定により最終オッズで検証しています。T-5/T-10の正式forward判定とは分けて扱います。
- 投資額、払戻額、損益は 1 unit = 100円で表示しています。
- 精算監査: error_count=0, audited_race_count=1162
