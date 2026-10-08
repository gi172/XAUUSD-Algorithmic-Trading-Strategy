# XAUUSD-Algorithmic-Trading-Strategy

Professional intraday algorithmic trading strategy for GOLD/XAUUSD on TradingView Pine Script v5.

## Asset and timeframe
- Asset: XAUUSD / GOLD
- Principal timeframe: 1H
- Lower-timeframe confirmations: 15M and 5M
- Strategy style: intraday, confluence-based, no repainting

## What is included
- Market structure detection (HH, HL, LH, LL, BOS, CHOCH)
- Support and resistance levels
- Liquidity sweep logic and stop-hunt detection
- Premium/discount and equilibrium visualization
- Fair value gap / imbalance consideration
- Session awareness for Asian, London and New York
- Risk management with SL/TP/BE/trailing stop
- Setup scoring from 0 to 100
- Alert system for key events
- No-lookahead, no-repaint logic

## Files
- `strategy/gold_intraday_1h_strategy.pine` — main Pine Script strategy
- `docs/strategy_logic.md` — methodology and rules

## How to use
1. Open TradingView.
2. Open Pine Editor.
3. Paste the strategy code from `strategy/gold_intraday_1h_strategy.pine`.
4. Apply it to XAUUSD on the 1H chart.
5. Use 15M/5M as lower-timeframe confirmation.
6. Review the backtest in Strategy Tester.

## Important note
This project is designed as a robust, testable trading system for research and educational use. It is not a guarantee of profitability.
