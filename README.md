# Day-077--Linear-Regression-and-Data-Visualisation-with-Seaborn
Pandas, Linear Regression with Sci-kit, and Seaborn

Pandas:
- .loc[] --> filter DataFrame based on multiple conditions
- .query() --> filter DataFrame based on multiple conditions

Seaborn (sns):
- you can use seaborn "on top of matplotlib" --> you can use matplotlib AND seaborn together

- .scatterplot() --> create a scatter plot
- .scatterplot().set() --> set additional properties of a plot

- .regplot() --> create regression plot ("scatterplot + trendline")

Sci-kit (sklearn):
- regression = LinearRegression() --> object of a class LinearRegression()
- regression.fit()

- regression.intercept_ --> "začetna vrednost" of a trendline
- regression.coef_ --> "naklon" (slope) of a trendline
- regression.score() --> R-square score that tells us, how good we describe the data with a trendline
- (the higher R-square the better model) --> if we are above 50 %, we are good
