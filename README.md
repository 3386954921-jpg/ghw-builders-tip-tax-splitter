# Tip & Tax Splitter

A single-file CNY bill-splitting calculator adapted with Cursor for MLH Global Hack Week Builders Week in November 2026. Open `index.html` in a browser to run the app.

The November version extends the author's October Cursor-generated calculator with tax input, separate tip and tax amounts, and calculation-overflow validation. Both percentages apply to the pre-tax bill. The interface supports light and dark themes and narrow screens.

## Checked examples

| Bill | Tip | Tax | People | Total | Per person |
|---|---|---|---|---|---|
| CNY100 | 10% | 0% | 4 | CNY110.00 | CNY27.50 |
| CNY100 | 10% | 5% | 4 | CNY115.00 | CNY28.75 |

Independent checks in Microsoft Edge covered these calculations, zero bills, blank and negative tax, zero and fractional people, overflow, dark mode, theme persistence, and a 390px viewport. All 11 checks passed on November 10, 2026.

The presentation and submission workflow reference was another participant's public MLH tip-calculator project. [Hasalawa/tip-calculator](https://github.com/Hasalawa/tip-calculator)
