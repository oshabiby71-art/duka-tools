# DukaTools

**Simple pricing and stock tracking for independent shops.** DukaTools is a small, free, offline-friendly browser app designed for shopkeepers who need a quick way to calculate a selling price and keep a basic stock count.

## What it does

- Calculates a suggested selling price from unit cost and target gross margin.
- Shows gross profit per unit and the resulting margin after rounding the price up to a whole Kenyan shilling.
- Keeps a simple product and quantity list in the browser on the current device.
- Lets you add or remove one unit, remove a product, and export the list as CSV.
- Works without an account, a server, or external libraries. It does not send entered data anywhere.

## Use it

Open `index.html` in a current browser. Add a product name, unit cost, and target margin, then choose **Add to stock list**. Use **Export CSV** to make a backup.

The list is stored in local browser storage, so it stays on that browser and device. Clearing browser data can erase it. Export a CSV backup before changing devices or browsers. This is a simple stock aid, not a replacement for accounting or tax advice.

## Pricing formula

`suggested price = round up(unit cost / (1 - target margin / 100))`

Gross margin is different from markup. For example, a 25% margin on a KSh 100 cost requires a KSh 134 selling price after rounding up, giving approximately 25.4% gross margin.

## Contribute

Suggestions and contributions are welcome. Start with a GitHub issue describing the need, or open a pull request with a focused improvement. Keep the app lightweight, accessible, and usable on low-cost phones. Do not add analytics or transmit shop data without clear user consent.

This is a newly created community tool. It has no established user base or adoption figures yet; feedback from shopkeepers will guide what to build next.

## License

MIT. See [LICENSE](LICENSE).
