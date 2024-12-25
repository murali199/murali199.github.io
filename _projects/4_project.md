---
layout: page
title: ⭐ Fashion Retailing Sales Forecasting
description: Recommendation System | Multi-modality | Transformer | Computer Vision | Natural Language Processing | Master's thesis work
img: assets/img/project_img/Fashion_arch.png
importance: 1
category: pusan national university
related_publications: true
---

*  Proposed Autoregressive Multimodal Transformer modal for fashion recommendation by sales forecasting.
* Implemented zero-shot forecasting methodology for improved generalization and addressed limited historical data challenges, achieving 35% improved MAE and WAPE.
* Built an end-to-end pipeline for data preprocessing, feature extraction from multimodal and exogenous data
* This project is my masters thesis work.
* Genuine products sales data are used in this project, collected from 9oz.
* Image-based Multi-model Transformer method is proposed.
* Additionally NAVER apparel products data also used.
* Used Language / Framework: Python (PyTorch).

<br/>
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/Fashion_arch.jpg" title="Fashion_arch" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     Graphical illustration of the proposed framework for fashion
 product sales forecasting. The framework depicts the distribution of
 fashion products to stores through supply chain management practices.
 Data D is collected from both the 9oz stores and potential exogenous
 data sources. Separate data preparation techniques, including scaling
 and sorting processes, are applied to the collected data across various
 modalities.Following,positionalencodingisappliedtocapturetherela
tive order of elements within a sequence. Subsequently, the framework
 aggregates the processed feature vectors, and this enriched represen
tation is fed into an auto-regressive multimodal transformer module.
 The transformer utilizes a shared attention mechanism to address the
 sequential nature of sales data and to facilitate interaction and learning
 of joint representations across different data modalities. Ultimately, this
 framework enables accurate sales forecasting, denoted as f(x).
</div>
<br/>

<p>  Predicting future sales volumes of fashion industry products is challenging due to rapid market changes and limited historical
 sales data for recent products. As traditional forecasting methods and machine learning models often fail to address this
 problem, we propose a novel autoregressive multimodal transformer architecture to anticipate the sales volume of brand-new
 apparel items bycapturing trends amonginterrelated attributes. In this paper, we utilize authentic data from a fashion company
 that includes a limited amount of historical time-series sales data and several influencing factors like product image, textual
 descriptions, and temporal attributes. To mitigate the data inadequacies, we investigate the impact of integrating exogenous
 knowledgefromane-tailersitefiltered withfashion apparel products. Also, wefoundthatemployingthezero-shotforecasting
 approach further aids in forecasting with minimal time-series sales data. Our approach achieves the values of 1.546 and 16.42
 in terms of MAEandWAPE,respectively, by leveraging exogenous data compared to existing benchmark models. This study
 demonstrates the potential of our autoregressive multimodal transformer to predict sales volumes with more precision, and it
 highlights the importance of incorporating the zero-shot forecasting approach in the dynamic fashion industry. {% cite rajendran2025autoregressive %} </p>

 <br/>
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/Fashion_knn.png" title="Fashion_knn" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The sample sales profile forecasting approach is 
illustrated in this Figure.  To forecast sales volume, the 
model searches for similar products in the same or 
neighboring groups, as shown in Figure (a). The sales 
volume of the most similar product is then segregated, 
as depicted in Figure (b). The available data, such as 
product image, design attributes, temporal attributes, 
similar product information, and sales volume of 
similar products, are utilized by the model to predict 
the sales volume (Figure (c)). 
</div>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/Fashion_data_utilize.png" title="Fashion_data_utilize" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     In our study, we consider a forecast 
horizon of 8 months of data, although the practical 
horizon necessitates only 6 months of data due to the 
distinct 6-month duration of fashion periods, such as 
Spring-Summer (SS) and Fall-Winter (FW), as 
depicted in the above figure.
</div>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/Fashion_results.png" title="Fashion_results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The graph displays the
 Quantitative forecast results
 with other compared models in
 terms of MAE and WAPE for
 the 9oz dataset a, and the
 Visuelle dataset b. The term
 GTMTstands for
 GTM-Transformer, FuMLP
 denotes FusionMLP, and AMT
 refers to Autoregressive
 Multimodal Transformer
</div>
<br/>