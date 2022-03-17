# Readme

This are some of the projects done in the Certificate of Quatitative Finance (CQF) program.



The `FinalProject.ipynb` is the final project of the topic "Portfolio Construction with Robust Covariance".

- Data source is from Yahoo Finance.
- The first part is to construct the portfolio by using assets from 4 uncorrelated asset categories. And analyze the correlation between them. Then use the denoising techniques to gain a robust covariance matrix.
- The second part is to use the robust covariance matrix, and implement the Black-Litterman model on the incoming views on the assets to adjust the expected return.
- The third part is to use the equilibrium return to construct the portfolio, and optimize the weightings of the assets by using mean-variance, max Sharpe ratio optimization method. Backtesting and compared with the benchmark and equal weighting.



The `MonteCarlo.ipynb` is an assignment about using Monte Carlo simulation to realize the pricing of Asian option and Lookback option.

- The core idea of using Monte Carlo simulation is to benefit from the Law of Large Numbers. 
- Firstly, we set a suitable distribution for the random number generator, and generate random number out of that. The random number represents the potential path of the underlying asset price movement. 
- Secondly, we use the random number to generate paths for the underlying asset price movement and repeat that for large number of times, like 10,000.
- Thirdly, we compute the price of the option by using the final status of each generated paths to get a list of option price corresponding to each path.
- Lastly, we take the average of all the option prices and get the final price for the option.

This is an estimation. However, since the suitable distribution should be close to the real path distribution of the underlying asset, the final outcome should close to the real.



The `REPORT_E3.ipynb` is a machine learning based project. To build a classification model on the rise and drop of the asset.