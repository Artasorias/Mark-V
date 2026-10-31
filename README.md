# Mark-V — Momentum Indicator

This repository contains the **Artasorias Momentum** TradingView Pine Script indicator.

## Overview

The script plots a momentum histogram and a zero-line marker. Histogram colors distinguish positive and negative momentum and whether momentum is increasing or decreasing. The zero-line color indicates the Bollinger Bands / Keltner Channels squeeze state.

## Inputs

| Input | Default | Description |
| --- | ---: | --- |
| BB Length | 8 | Lookback used for the Bollinger Bands basis and deviation |
| BB MultFactor | 8.0 | Multiplier used in the Bollinger Bands deviation calculation |
| KC Length | 4 | Lookback used for Keltner Channels and the momentum calculation |
| KC MultFactor | 4 | Multiplier used for the Keltner Channels range |
| Use TrueRange (KC) | true | Use True Range instead of high-low range for the Keltner Channels |

## Add to TradingView

1. Open the `Momentum` source file in this repository.
2. Copy its contents into TradingView's Pine Editor.
3. Add the script to a chart.
4. Adjust the inputs and verify its behavior on your intended market and timeframe.

## Important notes

- The source uses Pine Script syntax; this is not a JavaScript package.
- Indicator output is informational and is not a guarantee of future results.
- No license is currently declared for this repository. Do not assume permission to redistribute or reuse the code unless the owner specifies a license.
