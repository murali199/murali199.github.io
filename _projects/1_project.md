---
layout: page
title: ⭐ Explainable Rip Current Detection
description: XAI | YOLO | Faster-RCNN | Object Detection | Computer Vision | Deep Learning
img: assets/img/project_img/RipDetection_preview.png
importance: 1
category: greenblue
related_publications: true
---

<br/>
<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/RipDetection_intro.png" title="RipDetection_intro" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        <ul>
            <li>Rip current is a powerful narrow flow of water that moves away from the shore, posing a danger to swimmers and surfers.</li>
            <li>They form due to interactions between waves and uneven underwater features.</li>
            <li>They're strong & fast, pulling even strong swimmers away.</li>
        </ul>
    </div>
</div>
<br/>

<p>  Rip currents have long posed a serious threat to 
beachgoers and swimmers. Despite numerous preventive 
measures throughout the period, the fatality rate underscores 
the need for a robust rip current detection system. Recently deep 
learning models have shown promising results in rip current 
detection, outperforming traditional methods. However, these 
models still exhibit some accuracy limitations due to insufficient 
data distribution. To address this challenge, we incorporate a 
novel largest dataset comprising over 110,215 Korean coastline 
images. Through the comparative study of the state-of-the-art 
models, we aim to analyze the detection accuracy of each model 
and gain a deeper understanding of their intensity over rip current 
detection. In comparison to the other rip current datasets, the 
evaluation results on our proposed dataset demonstrate a 
remarkable elevation in accuracy, reaching 79.4 mAP. Further, 
we employ the EigenCAM (Eigen Class Activation Maps) to 
interpret the intense regions of the rip currents and to gain a 
deeper comprehension of rip current explainability. This 
comprehensive analysis marks a significant step toward 
improving rip current safety and understanding. {% cite choi2024explainable %} <p>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/RipDetection_sample_dataset.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample rip current detection
</div>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/RipDetection_preview.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image is an illustration of predictions of visible rip currents on the coastline. 
Eigen-CAM method interprets the predicted rip currents on Haeundae Beach. 
(a) The original image, (b) Bounding box prediction of YOLOv8 model, (c) 
Visual explanations of Eigen-CAM over the same model and image.
</div>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project_img/RipDetection_results_tbl.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project_img/RipDetection_results.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The latest model YOLOv8 demonstrates exceptional capabilities in rip current detection, even when multiple rip currents are present.
    The YOLOv8 outperforms the Faster RCNN and YOLOv5 models, especially the nano-sized model.
</div>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/RipDetection_pr_curve.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Plots showing the mean Average Precision values of different models with different sizes.
    In this PR curve plot, while the x-axis denotes recall, the y-axis refers to precision.
</div>
<br/>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_img/RipDetection_loss_tbl.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The below table provides the box losses and object losses over training and validation datasets.
    The YOLOv8 nano model has lesser loss values compared to other models. 
    After the YOLOv8n model, the YOLOv5n model achieves less loss values comparatively.
</div>
<br/>
