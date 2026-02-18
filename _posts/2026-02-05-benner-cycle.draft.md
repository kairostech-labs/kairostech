Like me you might have come across this image on social media.

![benner table](/assets/images/benner/triangle_table.png)

As a timeseries analysis enthusiast, it seems like a good opportunity to examine this cycle.

In fact I studied 300 years worth of data, thanks to the BOE.

How it applied to the Ohio farmer studying the ups and downs of pig-iron, hogs, corn and the railroad.

How it is entering the discussion again in today.

# Theory (118)

* Elements of Meteorology, by Prof. John H. Tice
* Comparison to Kondratieff
* Comparison to Jubilee

# Prophecies verified (135)

* Examples from benners book
* Panic: (1981, 1999, 2019)
* High prices: (2007, 2026?)

# Not so prophetic

* High prices: (2016)

Other cycles like Armstrong also references an event in [Asia](https://en.wikipedia.org/wiki/2015%E2%80%932016_stock_market_selloff)

# What the data shows

The range of data used for testing;

SP500 index (^GSPC) from 1927.

| symbol | resolution | min                            | max                            | count |
| ---    | ---        | ---                            | ---                            | ---   |
| ^GSPC  | 1wk        | 1927-12-26 00:00:00 EST        | 2026-02-02 00:00:00 EST        | 5119  |

* ROC summary

| high_cycle | mean_change   |
| ---        |---------------|
| 0          | -0.002518     |
| 1          | **-0.002993** |
| 8          | 0.001094      |
| 9          | **-0.000875** |
| 17         | 0.003714      |
| 18         | **0.002427**  |


## Seasons

The chart shows the mean rate of change for forward returns.

The X axis is where in the high cycle the year falls, 0 to 27.

![high prices chart](/assets/images/benner/high-prices.svg)

Rebound 2 years later?

# Conclusions

Not a good predictor of a specific crash year.

Panic years like (1981, 1999, 2019) are pretty close, but not the exact year of the crash.

There may be some promise in indicating slowdowns in years following high price years.

> 'I know of no way of judging of the future but by the past,'
> —Patrick Henry.

# References

To see the source code for the calculations, open the Jupyter Notebook here on [github](https://github.com/kairostech-labs/kairostech/blob/main/notebooks/cycles/benner_peaks.ipynb)
