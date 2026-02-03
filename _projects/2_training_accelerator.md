---
layout: page
title: 4-bit Training Accelerator
description: Mixed-precision neural network training using 4-bit block minifloat.
img: assets/img/publication_preview/bm_training_sys.jpg
importance: 2
category: PhD Research
---

[cite_start]Along with increasing DNN model scale, the training cost is becoming a new problem for DNNs. [cite_start]This project addresses energy-efficient training through the implementation of low-precision arithmetic, focusing on the development of specialized kernels and rescaling strategies for training workloads.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/nbeats_model.jpg" title="N-BEATS Training Model" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/training_loss.jpg" title="Training Convergence" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    [cite_start]Left: N-BEATS model with BM precision conversion layers for training; [cite_start]Right: Convergence analysis of the 4-bit mixed-precision training system.
</div>

### Key Contributions

- [cite_start]**First 4-bit BM Training Implementation:** We propose the block minifloat (BM) implementation for training, in the form of the first FPGA implementation of a 4-bit BM, mixed-precision neural network training of N-BEATS.
- [cite_start]**Kernel-Level Examination:** This work examines kernel design under different block arithmetic implementations specifically for deep learning training stages.
- [cite_start]**Training Advantage Demonstration:** We utilize N-BEATS based training accelerators to demonstrate the advantages of block arithmetic in handling surging computational requirements.
