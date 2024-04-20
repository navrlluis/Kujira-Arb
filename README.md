**Kujira Stablecoin Arbitrage and Lending Bot**

**Overview**
This project is designed to interact with the Kujira ecosystem, specifically targeting the stablecoins USDC, axlUSDC, and USK. It utilizes Kujira Fin, a decentralized exchange (DEX), to analyze and trade between stablecoin pairs, and Kujira Ghost, a money market platform, to lend stablecoins and optimize for the best annual percentage rate (APR).

**Features**
    Stablecoin Pair Analysis: Monitors the exchange rates for USDC-USK, axlUSDC-USK, and axlUSDC-USDC pairs on Kujira Fin.
    APR Comparison: Retrieves and compares lending rates for USDC, axlUSDC, and USK on Kujira Ghost.
    Automated Trading: Executes trades on Kujira Fin based on the analysis to acquire the most undervalued or promising stablecoin.
    Optimized Lending: Lends out the stablecoin with the highest lending APR on Kujira Ghost.
    
**Smart Contracts**
    DataAnalysisContract: Interacts with Kujira Fin to retrieve and analyze exchange rates.
    LendingAnalysisContract: Retrieves lending rates from Kujira Ghost and performs comparisons.
    TradingContract: Executes trades on Kujira Fin based on the analysis.
    LendingContract: Lends stablecoins on Kujira Ghost for the best APR.

**Contributing**
Contributions are welcome! Please read the CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

**Disclaimer**
This bot is for educational purposes only. Users should do their own due diligence and understand the risks before using or deploying real funds in a live environment.
