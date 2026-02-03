---
layout: page
title: Delay Update: Efficient Block Arithmetic Rescaling for Neural Network Training Acceleration
description: Efficient block arithmetic rescaling for neural network training acceleration.
importance: 3
category: PhD Research
---



Rescaling is a critical challenge associated with block arithmetic as it requires converting high-precision partial sums back into low-precision formats. [cite_start]This work introduces a proposed delayed scaling method, termed the "delay update," to reduce the rescaling computation in block-based deep learning accelerators. [cite_start]The method addresses hardware bottlenecks at the arithmetic level while maintaining numerical performance.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/delay_logic.jpg" title="Delay Update Logic" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/resource_comp.jpg" title="Resource Comparison" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    [cite_start]左图：论文 Figure 5.1，描述了延迟更新（Delay Update）机制的逻辑实现，旨在减少硬件缩放频率 [cite: 1][cite_start]；右图：对比了延迟更新方案与传统最大值校准（Maximum Calibration）方案在硬件资源占用上的显著优势 。
</div>

### Key Contributions:
- [cite_start]**Innovative Rescaling Method:** Proposed the delay update method to significantly reduce the computational overhead of rescaling in block arithmetic.
- [cite_start]**Hardware Advantage:** Empirical studies show that the delay update scheme provides a significant hardware implementation advantage over commonly used calibration methods.
- [cite_start]**Accuracy Maintenance:** Demonstrated that the proposed scheme achieves nearly the same accuracy as the maximum calibration method, ensuring reliable training convergence.
