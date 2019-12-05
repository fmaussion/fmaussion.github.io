---
layout: post
title: "Bokeh viz: Glacier evolution in the Alps"
excerpt: "A simple line plot can take some time"
image:
  feature: fm-header-6.jpg
modified:
categories:
date: 2019-12-05T00:00:00
draft: false
comments: true
---

I pursue my efforts to try to understand how [Holoviews](http://holoviews.org)
work. After much trial and error, here is a plot I feel comfortable to share.

It shows the future evolution of Alpine glaciers' volume under various
scenarios and for selected countries/regions. The change is given in % of their
estimated volume in 2017. Data is from  
[Zekollari et al. (2019)](https://www.the-cryosphere.net/13/1125/2019/).

<iframe src="/images/blog/bokeh-alps/alps_future.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="300"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

Data: [Zekollari et al. (2019)](https://www.the-cryosphere.net/13/1125/2019/).
Code: on [GitHub](https://gist.github.com/fmaussion/2ce2496774639f16f8c5bddeece3473a).
Larger plot: [here](/images/blog/bokeh-alps/alps_future_large.html).
