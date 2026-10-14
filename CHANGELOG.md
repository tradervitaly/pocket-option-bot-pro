# Changelog

All notable changes to Pocket Option Bot PRO will be documented in this file, starting from the next release.

## [2.0.12] - 2026-10-14

### Added

- Strategy and settings descriptions: a book icon next to the strategy selector (and next to the Martingale toggle)
  opens a detailed description of the selected strategy on [2bot.top](https://2bot.top), in your interface language
  when available.
- Built-in Martingale calculator: each Martingale step now shows the trade amount for that step, and the total amount
  of the whole series is shown below the steps — highlighted in red when it exceeds your balance and in green
  otherwise.

### Improved

- Refined the bot window interface.

## [2.0.11] - 2026-09-14

### Fixed

- Fixed a crash in the MACD and Stochastic Oscillator strategies when there aren't enough candles yet (e.g. right
  after starting the bot or switching pairs/timeframe) — the strategy check now skips the signal instead of throwing
  an error.

## [2.0.10] - 2026-09-02

### Improved

- RSI strategy signals are now confirmed by the shadow (wick) of the last candle: a long upper wick confirms a
  downward reversal (crossing above 70), a long lower wick confirms an upward reversal (crossing below 30). Controlled
  by the new "Shadow %" parameter in the strategy settings (default 30%, set to 0 to disable the filter).
