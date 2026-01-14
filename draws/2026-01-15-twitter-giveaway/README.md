# Twitter Giveaway – 2026-01-15

- **Platform:** Twitter
- **Context:** community giveaway
- **Draw tool version:** v1.1.2
- **Bitcoin block height:** 932330
- **Bitcoin block hash:** `<TO_BE_FILLED_AFTER_BLOCK_IS_MINED>`
- **Draw executed on:** `<YYYY-MM-DD HH:MM UTC>`

## Files

| File | Description |
|------|-------------|
| `participants.csv` | Finalized list of participants (committed before block is mined) |
| `result.txt` | Output from alien-draw-tool (added after draw) |

## Verification

```bash
alien-draw-tool draw \
  --participants participants.csv \
  --hash <BLOCK_HASH> \
  --winners <N>
```