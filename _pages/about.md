---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently studying at the School of Artificial Intelligence, Beijing University of Posts and Telecommunications(BUPT), advised by [Xueming Li](). And I graduated from the school of Digital Media and Designing Art, BUPT with a bachelor's degree in 2021.

I have great passion on generation models, and mainly interested in image generation like GANs and diffusion models. I have published a paper about GAN on old photo restoration task. And I have worked on Neural Radiance Field (NeRF) during my internship in Qcraft, that was mainly about reconstructing unbounded scenes using NeRF. Also I have payed some attention on large language models, but I haven't worked on that.

I participates open source community competitions and won some prizes, such as paddle implemented hand written formula recognition model _[CAN](https://aistudio.baidu.com/projectdetail/4922214)_ , wich is merged to the official repository of PaddleOCR.

I use Python most and familiar with the Pytorch, OpenCV, Numpy, Scipy and Matplotlib. And I also know some C/C++ programing skills, and worked as a software intern in Huawei.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SSHRF-GAN: Spatial-Spectral Joint High Receptive Field GAN for Old Photo Restoration](https://link.springer.com/chapter/10.1007/978-981-99-8546-3_40)

**Duren Wen**, Xueming Li & Yue Zhang

- Towards the old photo restoration problem, proposed a novel fully convolution network named SSHRF-GAN(Spatial-Spectral joint High Receptive Field GAN) to tackle the mixed degradation in old photos.

</div>
</div>

# 🔨 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PaddleOCR</div><img src='images/can.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CAN(Paddle)](https://aistudio.baidu.com/projectdetail/4922214)[🔥 fork 116]

- Implements the Counting Aware Network for hand wriitten mathematic expression reconition in paddle, and modulates the model into standard modules and the models have been merged into PaddleOCR official repository.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<img src='images/anim.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Animation Character Generation based on VAE](https://github.com/dorren002/VAE-animation-character)

- Implements the Convolutional Variational AutoEncoder trained on Animation Character digits.

</div>
</div>

- Face Recognitioin Demo based on FaceNet[repo](https://github.com/dorren002/FaceRecognition)
- Pedestrian Detection based on HOG & SVM[repo](https://github.com/dorren002/HumanDetection_HOG_SVM).
- SIFT Algorithm based on Python[repo](https://github.com/dorren002/SIFT)
- NLP basic Algorathms like skip gram[repo](https://github.com/dorren002/NLP-curriculum-design)

# 🎖 Honors and Awards

- _2023.10 Postgraduate Scholarship, First Place_.
- _2022.09 Winner in Paddlepaddle Open Source Community Competition_
- _2021.06 Outstanding Graduates of BUPT._
- _2020.10 Undergraduate Scholarship, Second Place._

# 📖 Educations

- _2021.09 - 2024.06 (now)_, School of Artificial Intelligence, BUPT.
- _2017.09 - 2021.06_, School of Digital Media and Designing Art, BUPT.

# 💻 Internships

- _2023.07 - 2023.09_, Huawei inc, Beijing.
- _2022.12 - 2023.06_, Qcraft, Beijing.
- _2022.07 - 2022.08_, AIIT, Hangzhou.
