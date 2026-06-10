# Changelog

All notable changes to Android Calculator are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/), versioning follows [Semantic Versioning](https://semver.org/).

---

## [2.0.0] - 2024-07-01

### Added
- 🔢 **Scientific mode** — full trig (with Hyp & 2nd shift), logarithms, powers, combinatorics, constants
- 💻 **Programmer mode** — DEC/HEX/OCT/BIN conversion, bitwise operations (AND/OR/XOR/NOT/NAND/NOR/LSH/RSH), live cross-base preview panel
- 📏 **Unit converter** — 12 categories, 100+ units with precise conversion formulas
- 💱 **Currency converter** — 50+ world currencies + BTC/ETH, quick reference grid
- 🏋️ **BMI calculator** — metric + imperial, animated indicator bar, ideal weight range
- 📜 **Calculation history** — localStorage persistence, 100-entry rolling window, one-tap recall
- 🎨 **4 themes** — Dark, AMOLED, Light, Material You
- ⌨️ **Full keyboard support** — all standard keys mapped
- 🏷️ **Display badges** — DEG/RAD/GRAD, 2ND, HYP, M (memory) indicators
- 📐 **Smart display scaling** — font size adjusts to result length

### Changed
- Complete rewrite in React 18 + TypeScript + Vite
- New CSS custom property design system for instant theme switching
- Calculator engine rebuilt on `mathjs` for safe evaluation

### Fixed
- Floating-point display rounding (12 significant digits)
- Scientific notation for very large/small numbers
- Base conversion disabled keys in programmer mode

---

## [1.0.0] - 2024-01-01

### Added
- Initial release — standard calculator
- Basic arithmetic (add, subtract, multiply, divide)
- Percentage and sign toggle
