> _cries in mlsp_

# QwinIR

## An MLP-based Shifted Window Model for Image Super Resolution

By Mark Bauer and Quinn Ouyang

### Abstract

Famous for its shifted window representation, the Swin Transformer backbone
architecture has consistently showcased state-of-the-art performance across a range
of well-established computer vision benchmarks. To enhance computational effi-
ciency, the Swin Mixer architecture adopts this structure but substitutes its attention
layers with simpler multi-layer perceptrons (MLPs). In line with this design, we
introduce QwinSR, an application of this all-MLP architecture tailored for single
image super-resolution. This adaptation simplifies the Swin Transformer-based
image restoration model, SwinIR. QwinSR leverages MLPs to extract essential
features and subsequently aggregates them within a compact convolutional neu-
ral network, facilitating image reconstruction. We anticipate that our model will
yield competitive accuracy-to-computation metrics, particularly when compared to
SwinIR and other leading models in the field. Our (untested) code is available at
https://github.com/quinnouyang/QwinSR.

> See paper [here](/paper/out/my-little-perceptron.pdf)
