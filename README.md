# The Marginal Cost of Information When Is Enough Data Enough for Time Series Analytics

Published: 2025-02-19
Medium: [https://medium.com/@kyle-t-jones/the-marginal-cost-of-information-when-is-enough-data-enough-for-time-series-analytics-a0e8c2a5e2b0](https://medium.com/@kyle-t-jones/the-marginal-cost-of-information-when-is-enough-data-enough-for-time-series-analytics-a0e8c2a5e2b0)

## Business context

Information is never free. Whether it is collected through surveys, purchased from a third party, extracted from public records, or generated through experimentation, acquiring data always incurs costs. These costs can be direct, such as paying for proprietary data or running a costly field study, or indirect, such as the time spent cleaning, processing, and analyzing raw information. Every additional piece of data comes with diminishing returns --- the first few data points might drastically improve decision-making, but after a certain threshold, the value of additional data flattens out, while costs continue to rise.

Economists describe this phenomenon as the marginal cost of information. Just as in production, where each additional unit of output requires more inputs, each additional piece of data requires effort to collect, store, and analyze. The challenge for decision-makers and analysts is knowing when to stop --- when the cost of acquiring more information exceeds the expected benefit of improved decision-making.

The theory of optimal stopping provides a structured way to approach this problem. In many decision-making scenarios, we must balance exploration (gathering more information) with exploitation (acting on what we already know). The famous secretary problem is a classic example: Imagine you are hiring a secretary and must decide whether to hire a candidate immediately or keep searching, knowing that once you reject someone, you cannot return to them. Mathematically, the optimal strategy suggests reviewing about 37% of the candidates without hiring, then selecting the first one who is better than all previous ones.



## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).