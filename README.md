Analysis
The plot shows the loss over 100 epochs for the neural network training, with the best configuration using 32 neurons, a learning rate of 0.001, the 'tanh' activation function, and a look-back window of 36 months. The training loss starts relatively high and quickly decreases, stabilizing around epoch 20. After this point, the loss fluctuates slightly but remains mostly flat, indicating that the model has converged and further training does not significantly improve the performance.
The low and stable final loss value around 0.1578 suggests that the model is well-tuned and has achieved good performance with minimal overfitting. However, the slight fluctuations in the loss after stabilization might indicate that the learning rate could be fine-tuned further or that more epochs could help confirm convergence more robustly.

 
  Mean Beta Values:
• Agriculture, Forestry, and Fishing (SICCD 1 – 999): Beta values vary slightly between 0.09 and 0.11,
indicating moderately low volatility in comparison to the broader market.
• Mining (SICCD 1000 – 1499): This sector has some variability, with beta values ranging between 0.09 and 0.11, suggesting average risk but some spread in volatility.
• Construction (SICCD 1500 – 1799): Beta values hover around 0.10 to 0.11, reflecting fairly consistent and moderate risk levels.
• Manufacturing (SICCD 2000 – 3999): There is significant clustering around 0.10 to 0.11, implying stable beta values, though some points suggest a slight increase in volatility for certain firms.
• Transportation and Utilities (SICCD 4000 – 4999): This sector has more spread, but the beta values are clustered between 0.09 and 0.11, indicating moderate risk with a slight tendency towards higher volatility.
• Wholesale and Retail Trade (SICCD 5000 – 5999): The data shows a strong concentration of beta values between 0.10 and 0.11, reflecting low volatility and consistent risk levels.
• Finance, Insurance, and Real Estate (SICCD 6000 – 6799): Similar to Wholesale and Retail Trade, this sector exhibits tight clustering of beta values between 0.10 and 0.11, showing low risk and steady volatility.
• Services (SICCD 7000 – 8999): Beta values for this sector are scattered between 0.09 and 0.11, reflecting a diverse set of service industries with varying degrees of volatility.

Standard Deviation of Beta:
• Agriculture, Forestry, and Fishing (SICCD 1 – 999): Standard deviations are relatively low, between
0.04 and 0.05, indicating consistent risk levels across the industry.
• Mining (SICCD 1000 – 1499): This sector has higher variability, with standard deviations between 0.04 and 0.06, reflecting more fluctuating risk.
• Construction (SICCD 1500 – 1799): The standard deviations fall within the range of 0.04 to 0.05, suggesting stable risk levels with little variation.
• Manufacturing (SICCD 2000 – 3999): Standard deviations for this industry are clustered between 0.04 and 0.06, indicating some risk variation but overall consistency.
• Transportation and Utilities (SICCD 4000 – 4999): This sector displays a standard deviation between 0.04 and 0.06, with a few outliers, implying stable risk but with potential volatility spikes.
• Wholesale and Retail Trade (SICCD 5000 – 5999): Standard deviations are mostly concentrated between 0.04 and 0.06, indicating low volatility across the sector.
• Finance, Insurance, and Real Estate (SICCD 6000 – 6799): The standard deviation values are tightly grouped between 0.04 and 0.06, reflecting consistent and low risk.
• Services (SICCD 7000 – 8999): The standard deviations show more scatter, between 0.04 and 0.07, indicating more variable risk across different service industries.

• Beta Mean Shift: The average beta values have shifted slightly across industries, such as in SICCD 3674 and 4813. Incorporating Fama-French factors like SMB, HML, and Mkt-RF helped refine the beta estimation.
• Reduced Standard Deviation: Some industries (e.g., SICCD 3670) saw reduced beta standard deviation, indicating more stable beta values when factoring in Fama-French variables.
• Outliers and Extremes: Extreme values, such as the minimum and maximum beta estimates, appear less severe for certain industries, like SICCD 6036, indicating the model smoothed out some previously exaggerated beta estimates.
• RMSE Change: The Root Mean Squared Error (RMSE) is expected to be lower with this model due to better explanatory power provided by the additional factors, reducing model error.
• Beta Refinement: Overall, the beta values are more refined, and the distribution is less skewed compared to the previous model that did not incorporate these factors.
Step 10:

 The first graph shows the cumulative returns of equal-weighted portfolios across quintiles based on the predicted betas. While Quintile 5 exhibits the highest cumulative returns, there is noticeable variation in the lower quintiles. Quintile 1 and Quintile 2 show negative returns, with the lowest performance observed in Quintile 2. Quintile 3 and 4 remain relatively flat, suggesting minimal difference in cumulative returns between these mid-level beta portfolios. The sharp rise in Quintile 5 aligns with the expectation that higher-beta portfolios (more risk) tend to yield higher returns, while the negative returns in the lower quintiles may point to inefficiencies or poor performance of low-beta stocks during the observed period.
In the second graph, which depicts the cumulative returns of value-weighted portfolios by quintile, the returns show a steady increase from Quintile 1 to Quintile 5. Unlike the equal-weighted portfolios, the value- weighted portfolios begin with slightly positive returns even in Quintile 1. Quintile 5 continues to offer the highest cumulative returns, though the overall rise is more gradual compared to the equal-weighted portfolios. This suggests that larger firms with higher market capitalizations, especially in the higher-beta quintiles, still generate higher returns but with a less dramatic rise than their equal-weighted counterparts. The steady increase in cumulative returns across quintiles implies that size has a stabilizing effect on volatility, reflecting more consistent performance as firm size increases.In both cases, the highest returns are associated with the

higher beta portfolios (Quintile 5), indicating that firms with higher risk levels tend to offer greater compensation through returns.
