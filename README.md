# WorldQuant_Alphas
Investment alphas, a concept from finance, measure an investment's risk-adjusted performance relative to a benchmark. A positive alpha indicates that the investment has outperformed the benchmark, while a negative alpha indicates underperformance.

Metrics Used to determine efficiency of alphas:
1) SHARPE: Average measure of risk-adjusted returns; Sharpe = Avg. Annualized Returns / Annualized Std. Dev. of Returns
2) TURNOVER: Average measure of daily trading activity; Turnover = Value Traded / Value Held
3) FITNESS: Hybrid metric that indicates overall performance. Higher values indicate better performance. Fitness = Sharpe * Sqrt( Abs( Returns ) / Max( Turnover, 0.125 ))
4) RETURNS: Annualized average gain or loss as a fraction of the invested amount. In WorldQuant BRAIN the invested amount is equal to half the book size
5) DRAWDOWN: Drawdown is the largest reduction in PnL during a given period, expressed as a percentage
6) MARGIN: Average gain or loss per dollar traded; calculated as PnL divided by total dollars traded in a given time period

