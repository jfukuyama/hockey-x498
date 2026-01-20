# Analysis Plan
- Filter to just Canadian NHL players
- Jan 1 - December 31 also corresponds to grades in school
- Plots of first half vs. second half, plots by quarter, plotting by province - are patterns of first half vs. second half of year the same across provinces?
- Using the birth data from Canada, see if the means by month are the same, want to check whether the month pattern is consistent across years, is it mostly flat
- Look at differences between countries, USA is in two-year blocks, you would expect the birth month effect to be attenuated in the US compared to Canada
- Chi square test with observed = number of NHL players with each birth month, expected = fraction of Canadian births in each month
- Poisson regression of number of births per month on month
- Logistic regression
