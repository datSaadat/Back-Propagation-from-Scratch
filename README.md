# Back-Propagation-from-Scratch

The updated file includes most updated scratch implementation of back-propagation using only numpy.

This file also includes the fake-quantization, if we required it. All inputs to matrix multiplications are quantized, not only the feedforward calculations. This is to mimic the training of the models in low bit processors (i.e., MCUs in edge devices, RRAMs). This is different from Quantize-Aware Training (QAT)

To know more about QAT and Fake-Quantization, you might read: https://towardsdatascience.com/inside-quantization-aware-training-4f91c8837ead
