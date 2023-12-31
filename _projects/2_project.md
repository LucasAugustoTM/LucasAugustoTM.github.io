---
layout: page
title: AR Guide
description: Semi-dynamic tool for the creation of guides in AR for mobile systems
img: assets/img/arguideplacas.png
importance: 2
category: work
---

This Unity project implements an Augmented Reality LASER cutting machine operation guide for mobile systems, developed as the Final Paper for the Bacharel's Degree in Computer Science at PUCRS. The algorithm projects prefabs above specified images in accordance with a user defined order, whene these images are tracked by the smartphone's camera. The images, prefabs/3D models and order can be easily altered in Unity, before building the apk. The order (a .txt file) can be modified at runtime as well.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/arguidegif.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The app in execution.
</div>

The default assets included with the release were made for specific use at the Fablab laboratory at PUCRS. These assets and the menus are currently in Portuguese. The default order already included can be reverted back to normal at runtime in the "Configuração de Ordem" menu. There is currently a release for Android systems, with plans for a future iOS release.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/arguidetelastart.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/arguidetelaconfig.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/arguidetelafim.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In-app menu screens.
</div>

[Check it out on Github!](https://github.com/LucasAugustoTM/ARGuide)

