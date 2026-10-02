# Tip jar (optional)

If this paper-trading work helped you and you want to send Bitcoin:

**Lightning (best for small tips):** `butlerwake@strike.me`

**On-chain BTC (larger tips):** `bc1qtxjpah5ntpq6fk92yukysc32zjewlz9q0sr4nv`

Network: Bitcoin (BTC), native SegWit (bc1q…).
Optional only — nothing for sale, not an investment, no guarantees, no support contract.

Live page: index.html (QRs: lightning_qr.png and btc_tip_qr.png; the BTC QR is a BIP21 URI with label/message).

## Tips steer the bots

On-chain tips can vote on one paper-bot change per week: the last digit of the tip in sats is the vote (1 = Coinbase dual, 2 = Kraken, anything else = tip, no vote). One confirmed tip = one vote. Lightning tips can't vote, because Strike payments aren't public.

- `week.json`: this week's question and deadline
- `votes.json`: tally built from the public chain (mempool.space) by `tools/count_votes.py`
- `scoreboard.json`: built from the bots' own trade logs by `tools/build_scoreboard.py`

Paper trading only. No real money traded, not investment advice, no promised returns.
