# [INFPHY] Designing and Learning a Lightweight Network for Infrared Small Target Detection via Dilated Pyramid and Semantic Distillation

https://www.sciencedirect.com/science/article/abs/pii/S1350449523001299

[Chen G, Wang W, Li X. Designing and learning a lightweight network for infrared small target detection via dilated pyramid and semantic distillation[J]. Infrared Physics & Technology, 2023, 131: 104671.]

Abstract

Large-scale transformer networks can achieve state-of-the-art infrared small target detection accuracy, but the
high computational resource consumption makes their inference speed unsatisfactory. Existing lightweight
networks can certainly achieve real-time detection of infrared small targets, but no matter how carefully
designed the lightweight strategy is, there is still a gap in the accuracy of these networks compared to large-scale
networks. To address these problems, in this paper, we propose a lightweight infrared small target detection
network capable of high-speed inference and a knowledge distillation method for learning higher-order semantic
information from the transformer network. Specifically, based on depthwise separable dilated convolution, we
design each stage in the detection network, called multi-scale dilated pyramid network (MDPNet), as a multibranch
parallel pyramid. This design can enlarge the receptive field and enhance the ability to extract contextual
features of the network. Furthermore, we utilize knowledge distillation to bridge the detection performance
gap with the transformer. Based on the self-attention mechanism, a semantic distillation sub-network is constructed
between the teacher transformer and student convolution network, which enables a more efficient crossmodel
transfer of knowledge about higher-order semantic feature extraction between networks with different
mechanisms and increases the detection accuracy without computation load. We demonstrate the rationality and
effectiveness of the overall network design and learning approach through exhaustive experiments. On the
widely accepted public datasets SIRST and NUDT-SIRST, nIoU reaches 74.88 and 75.10, and PD reaches 99.08
and 97.88, outperforming other networks. With the number of parameters of only 0.23 M, the network achieves
an inference speed of 137 FPS for 320 × 320 infrared images.


Coming soon...
