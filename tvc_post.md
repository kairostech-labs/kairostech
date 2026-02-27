---
layout: page
title: Tradingview test post
permalink: /tvc/
---

# TVC Post

You can paste directly from clipboard into markdown!

![img.png](/assets/images/benner/tradingview.png)

{% raw %}
<div class="tradingview-widget-container">
  <div id="tradingview_chart"></div>
  <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
  <script type="text/javascript">
    new TradingView.widget({
      "container_id": "tradingview_chart",
      "symbol": "SPX",
      "interval": "W",
      "width": "100%",
      "height": 600,
      "theme": "dark"
    });
  </script>
</div>
{% endraw %}

{% raw %}
<iframe>
src="https://s.tradingview.com/widgetembed/?symbol=SPX&interval=W"
width="100%"
height="500"
frameborder="0"
></iframe>
{% endraw %}
