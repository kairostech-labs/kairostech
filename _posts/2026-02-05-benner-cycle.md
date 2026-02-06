---
layout: post
title: "The Benner Cycle: How accurate is it"
date: 2026-02-05
categories:
  - cycles
  - markets
---

Like me you might have come across this image on social media.

![benner table](/assets/images/benner/triangle_table.png)

As a timeseries analysis enthusiast, it seems like a good opportunity to examine this cycle.

How it applied to the Ohio farmer studying the ups and downs of pig-iron, hogs, corn and the railroad.

How it is entering the discussion again in today.

# Theory (118)

* Elements of Meteorology, by Prof. John H. Tice
* Comparison to Kondratieff

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

Forward returns in high years

| "year"(datetime_local) | sum(forward_returns) |
| ---                    | ---                  |
| 1935                   | 4.53                 |
| 1945                   | 4.669999             |
| 1953                   | -1.15                |
| 1962                   | -4.810005            |
| 1972                   | 16.400002            |
| 1980                   | 23.559998            |
| 1989                   | 71.529999            |
| 1999                   | 166.380005           |
| 2007                   | -8.689941            |
| 2016                   | 354.949951           |

Forward returns, the year following a high year

| "year"(datetime_local) | sum(forward_returns) |
| ---                    | ---                  |
| 1927                   | 0.0                  |
| 1936                   | 3.7                  |
| 1946                   | -2.889999            |
| 1954                   | 10.400002            |
| 1963                   | 11.389999            |
| 1973                   | -26.209999           |
| 1981                   | -13.929993           |
| 1990                   | -36.970001           |
| 2000                   | -143.119995          |
| 2008                   | -510.670044          |
| 2017                   | 466.169922           |

## Seasons

The chart shows the mean rate of change for forward returns.

The X axis is where in the high cycle the year falls, 0 to 27.

![high prices chart](/assets/images/benner/high-prices.svg)

# Conclusions

Not a good predictor of a specific crash year.

Panic years like (1981, 1999, 2019) are pretty close, but not the exact year of the crash.

There may be some promise in indicating slowdowns in years following high price years.

> 'I know of no way of judging of the future but by the past,'
> —Patrick Henry.
