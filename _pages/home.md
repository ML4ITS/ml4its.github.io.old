---
title: "ML4ITS - Home"
layout: homelay
excerpt: "ML4ITS - Machine Learning for Irregular Time Series"
sitemap: true
permalink: /
---


(More details in [Research](research))

<img src="{{ site.url }}{{ site.baseurl }}/images/logopic/ml4its.png" style="float: right;width: 140px"> Time series are everywhere. Data recorded from sensors in mobile phones, financial data like accounting figures and climate indicators are all examples of time series society and individuals are exposed to daily. Understanding such time series are essential for technological advance and making informed decisions. 

Many of these time series are irregular in some sense. They may have missing data, which may occur if sensors fail, if a person forgets to insert a number in a spreadsheet, or if the phenomenon we are interested in may only be observed at certain points in time. They may also be very noisy: for example, using cheap sensors may allow us to get data from more sensors at the expense of the measurement having more noise than when using a more expensive sensor. 

The project **Machine Learning for Irregular Time Series** (ML4ITS) addresses some core challenges for irregular time series. In particular, the project develop methodology that handles irregular time series for the following tasks:

 - *Forecasting*: predicting the future values of the time series based on current/past data.
 - *Imputation/denoising*: creating “clean” data in the scenario there is missing or noisy data
 - *Anomaly detection* and *failure prediction*: knowing which observations are unusual or indicating that a system is in a critical state.
 - *Synthetic data creation*.
 
The last point addresses the need for creating datasets that are privacy preserving. For example, the sensor data on a cell phone may not be anonymous, but it may be possible to create a synthetic dataset that behaves like the original data in a statistical sense that at the same time preserves privacy. Furthermore, the project aims to make reproducible research and develop open source software that will benefit the research ecosystem.

The project is a collaboration between [Sintef Digital](https://www.sintef.no/digital/) and three departments at [NTNU](https://www.ntnu.edu/): [Department of Computer Science](https://www.ntnu.edu/idi), [Department of Mathematical Sciences](https://www.ntnu.edu/imf) and [Department of Electronic Systems](https://www.ntnu.edu/ies).


 **We are  hiring two PhD students and Master students to join the team** [(more info)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


We are grateful for funding from [The Research Council of Norway](href="https://www.forskningsradet.no/")</a> within the IKTPLUSS initiative. .

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/sintef.png" style="width: 180px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/ntnu.png" style="width: 140px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/ailab.png" style="width: 120px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/nfr.png" style="width: 110px">
</figure>
<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/telenor.png" style="width: 140px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/refinitiv.png" style="width: 140px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/exabel.png" style="width: 140px">
</figure>