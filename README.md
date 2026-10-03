# Short Notice Arranging

Single-page site for short-notice re-scoring and arranging for bands and orchestras.

- `index.html` — the whole site: styles, script and the treble-clef font are inline, so it opens by double-clicking.
- Preview (Claude artifact): https://claude.ai/artifact/1eqUPzGP5w2yxS1FMpBqrM
- Decisions and rates: Claude project doc 《急件网页-已定事项-2026-10-02》

## Settings in the script

| Constant | Meaning | Value |
|---|---|---|
| `MIN_MINUTES` | minimum billed minutes per job | 3 |
| `MIN_PER_DAY` | promised minutes of finished music per working day (start day counts as day 1) | 3 |
| `CUTOFF_HOUR` | all three in before this UK hour = start that day, otherwise next day | 14 |
| `NEW_ARR` | multiplier for new arrangements (melody, lead sheet, recording, piano score) | 1.5 |
| `MIN_FEE` | minimum fee per job in £ (0 = off) | 0 |
| `R` | per-minute rates | see script |

## Still to do

- Domain: shortnoticearranging.co.uk / .com
- Wire "Send this brief" to the form-to-email service (option A)
- Deploy to static hosting
