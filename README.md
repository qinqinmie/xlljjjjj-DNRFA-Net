DNRFA-Net: Dense Nested Network Based on Receptive Field Attention for Faint Celestial Object Detection

We propose a method DNRFA-Net for single frame faint space object detection. The contribution of this paper are as follows:

1. We Proposed DNRFA-Net, a specialized network for faint celestial object detection that effectively addresses the low signal-to-noise ratio challenge through an enhanced dense nested U-Net structure with cross-level and cross-dimension feature propagation. This framework provides an effective solution for deep learning based spatial object detection methods.
2. Proposed the Adaptive Receptive Field Attention Module (ARFAM), which automatically adapts its receptive field size based on target scale characteristics while simultaneously computing spatial attention weights, the module effectively resolves the critical challenge of faint celestial objects being obscured by complex background interference.
3. Proposed the Cross Attention Feature Fusion Module (CAFFM), a novel multi-scale feature integration mechanism that employs cross spatial-channel attention to optimally combine high-resolution detail from shallow layers with rich semantic in-formation from deep layers.



The project structure are as follow:

* dataset: the code for building the dataset and the dataset results.
* model: algorithm source code.
* result: weight parameter file of network training results.
* eval: evaluation code.
* utils: utils code.
* outfiles: output files result directory.
