# Changelog

All notable changes to Pocket Option Bot PRO will be documented in this file, starting from the next release.

## [2.0.10] - 2026-09-02

### Improved

- RSI strategy signals are now confirmed by the shadow (wick) of the last candle: a long upper wick confirms a
  downward reversal (crossing above 70), a long lower wick confirms an upward reversal (crossing below 30). Controlled
  by the new "Shadow %" parameter in the strategy settings (default 30%, set to 0 to disable the filter).
