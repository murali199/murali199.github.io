---
layout: page
title:  Climate Reanalysis (SST) Forecasting
description: Time-series | Regression | RNN | U-Net | CNN | Regression | Numerical Data | Machine Learning
img: assets/img/project_img/Climate_intro_1.jpg
importance: 4
category: greenblue
---

*  Developed RNN and U-Net models for predicting Sea Surface Temperature (SST), sea currents, and salinity.
* Implemented CNN architectures for enhanced feature extraction from the East Sea and Yellow Sea data.
* Integrated numerical models like XGBoost, and Random Forest to optimize the forecast accuracy.

<div class="row mt-3 justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/img/project_img/Climate_SST_video.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

Reanalysis: (Retrospective Analysis), is a scientific method for developing a comprehensive record of how weather and climate are changing over time. 
A synthesized estimate of the state of the atmosphere, ocean and land by objectively merging observations and a numerical model information. 
A reanalysis typically extends over several decades or longer, and covers the entire globe or a region from the Earth’s surface to well above the stratosphere.

Sea surface temperature (SST) is a critical factor in the functioning of marine and terrestrial ecosystems, as well as human activities that rely on the ocean.
Sea surface temperatures have risen by 0.5–0.6 °C since the 1950s, and over the oceans this has led to 4 percent more water vapor in the atmosphere since the 1970s.
Sea surface temperature is measured by satellite instruments that record the energy emanating from the ocean surface globally. The energy is emitted at different wavelengths.

<br/>
<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project_img/Climate_sea_1.png" title="Sea of Japan" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project_img/Climate_sea_2.png" title="Yellow Sea" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Both ES3K (East Sea) data and YES3K (Yellow Sea) data have 20 years of data from 2001 to 2020. The data variables are the same in both data. The variables are listed below. 365 data are saved to a file every year. Data are provided at various sea depths from 001 meters to 500 meters each day. The "temp" variable was considered only when focusing on SST.
</div>
<br/>


<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project_img/Climate_model.png" title="Sea of Japan" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project_img/Climate_results.png" title="Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Implemented and analysed random forest, gradient boost, and xgboost models.
</div>
<br/>