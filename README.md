# Efficient-Frontier-Modeling
**Markowitz-Efficient-Frontier**

**📈 Efficient Frontier Modeling for MAG 7 US Companies**<br>
**1).Overview**<br>

a). This project implements Modern Portfolio Theory (MPT) by constructing the Efficient Frontier using the Magnificent 7 (MAG7) US stocks:<br>
b). Apple (AAPL), Microsoft (MSFT), Alphabet (GOOGL), Amazon (AMZN), Nvidia (NVDA), Meta (META), and Tesla (TSLA).<br>
c). By simulating random portfolio combinations of these stocks, this model evaluates their risk-return profiles and highlights the efficient frontier — the set of portfolios offering the maximum expected return for a given level of risk.<br>

**📊 Process**<br>
**1. Data Collection**<br>
Historical adjusted closing prices for MAG 7 stocks are pulled using yfinance.<br>
Daily log returns are computed from price data.<br>

**2. Portfolio Simulation**<br>
Generate 500 random portfolios using random weight allocation (summing to 1).<br>
For each portfolio:<br>
Calculate expected return.<br>
Calculate standard deviation (risk) using the covariance matrix.<br>
Calculate Sharpe Ratio (return per unit of risk).<br>

**3. Efficient Frontier Construction**<br>
Plot all portfolios on a risk-return scatter plot.<br>
Overlay the Efficient Frontier:<br>
Sort portfolios by increasing risk.<br>
Retain only portfolios that offer higher returns than all previous ones — forming the upper edge of the feasible set.<br>

**💼 Applications**<br>
1). Portfolio Optimization: Helps investors build optimal portfolios among top tech stocks.<br>
2). Risk Management: Visualizes the trade-off between return and volatility.<br>
4). Financial Decision Support: Assists analysts and retail investors in making data-driven portfolio choices.<br>
