# Saliency-Relevance-Propagation

PyTorch implementation of Layer-wise Relevance Propagation based on [this tutorial][tutorial], which is used in this paper [Beyond Saliency: Understanding Convolutional Neural Networks from Saliency Prediction on Layer-Wise Relevance Propagation][beyond].  
We also applies context-aware saliency detection which is available [here][saliency]. 

## Prerequisites

 - Python 3.x
 - PyTorch
 - Jupyter Notebook
 - pre-trained VGG-Face model  
   PyTorch does not provide a pre-trained VGG-Face model. But you can download a Torch model from [here][vgg-face] and then convert it to a PyTorch model using [this tool][convert]. 
 - Large Scale Visual Recognition Challenge 2012 (ILSVRC2012) validation dataset

## Citation
If you use this code for your research, please cite our paper [Beyond Saliency: Understanding Convolutional Neural Networks from Saliency Prediction on Layer-Wise Relevance Propagation][beyond]

```
@article{li2017beyond,
title={Beyond saliency: understanding convolutional neural networks from saliency prediction on layer-wise relevance propagation},
author={Li, Heyi and Mueller, Klaus and Chen, Xin},
journal={arXiv preprint arXiv:1712.08268},
year={2017}
}
```

[beyond]: https://arxiv.org/abs/1712.08268
[vgg-face]: http://www.robots.ox.ac.uk/~vgg/software/vgg_face/
[convert]: https://github.com/clcarwin/convert_torch_to_pytorch
[tutorial]: http://heatmapping.org/tutorial/
[saliency]: http://webee.technion.ac.il/cgm/Computer-Graphics-Multimedia/Software/Saliency/Saliency.html
