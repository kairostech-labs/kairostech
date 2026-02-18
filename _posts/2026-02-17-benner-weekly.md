---
layout: post
title: "The Benner Cycle: Time to panic or on a high?"
date: 2026-02-17
categories:
  - markets
  - cycles
---

# Sure thing

In **1875**, an Ohio farmer Samuel Benner published this diagram in his book 'Benners Prophecies
future ups and downs in prices'.

![How to make money](assets/images/benner/94b66d849747d71f3f4ed2dc98a75d0a.jpg)

The diagram marks extreme years in 3 categories from top to bottom.

* Panics
* Good times high prices
* Hard times low prices

## The stock market: 150 years later

As successful farmer, having suffered severe losses in the market panic of 1873, he set out to study market cycles to find a way to prepare for future panics.
Although concerned with different markets in 1875 than today it is interesting that some predicted future cycles appear relevant.

Significant years that stand out in this diagram:

* **Panics:**
  * 1927: Great depression (1929)
  * 1981: Energy crisis recession (1981-1982)
  * 1999: Dotcom bubble (2000)
  * 2019: Covid crisis (2020)
* **High prices:**
    * 2007: Global financial crisis (2008)
    * 2016: Emerging market turbulence: China, Greece, Brexit (2015, 2016)

***

## Digging deeper

Let's look closed into the high prices cycle as 2026 is a marked peak.

The data used is ^GSPC from yahoo finance (SP500 index).
We aggregate weekly data in compiling the charts.

| symbol | resolution | min                            | max                            | count |
| ---    | ---        | ---                            | ---                            | ---   |
| ^GSPC  | 1wk        | 1927-12-26                     | 2026-02-02                     | 5119  |

***

The cycle spans 27 years.

The Y axis shows the average change in price for forward returns.
The X axis shows the cycle position for the year from 0 to 26.

Benner marked peaks at 8, 9 and 10 years within the 27-year cycle.
The red highlights show these areas. The fourth vertical bar represents the chart wrapping back around to zero.

![high prices chart](/assets/images/benner/high-prices.svg)

***

There seems to be some gradual increase in momentum before high years.
After which momentum drops off.

Not a good predictor of a specific year when we are likely to see a crash.
Wouldn't use it to time shorts but there's some promise for further investigation.

Would like to unpack the longer panic cycle in the future.

## Source code

To see the source code for the calculations, open the Jupyter notebook here on [github](https://github.com/kairostech-labs/kairostech/blob/main/notebooks/cycles/benner_peaks.ipynb).
