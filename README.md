# CascadeNet
Cascade Network for Multi-view 3D Object Detection

We propose CascadeNet with multi-cameras inputs, to infer the object location from a cascade network. It generates the location from three stages, and narrows the location range of each stage by the prediction from the previous stage. The DD3D pretrained VoVNet (V2-99) is adopted as the backbone network. We do not perform test-time augmentation. We use a single model without extra training data.
