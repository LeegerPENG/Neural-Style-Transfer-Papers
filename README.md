# Neural-Style-Transfer-Papers <img class="emoji" alt=":art:" height="30" width="30" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f3a8.png">
Selected papers, corresponding codes and pre-trained models in our review paper "**[Neural Style Transfer: A Review](https://arxiv.org/abs/1705.04058)**"

*(This Paper is under a major revision and the organization below may not be consistent with the original paper. We will release the newest version of the paper ASAP. Any comment is welcomed! Thank you very much!)*

## Citation
If you find this repository useful for your research, please cite

```
@article{jing2017neural,
  title={Neural Style Transfer: A Review},
  author={Jing, Yongcheng and Yang, Yezhou and Feng, Zunlei and Ye, Jingwen and Yu, Yizhou and Song, Mingli},
  journal={arXiv preprint arXiv:1705.04058},
  year={2017}
}
```
## Materials corresponding to Our Paper

- [**Supplementary Materials**](http://yongchengjing.com/pdf/review_supp.pdf)

- [**Pre-trained Models**](https://www.dropbox.com/s/37lje23pb75ecob/Models_neuralStyleTransferReview.zip?dl=0)

- [**Images**](https://www.dropbox.com/s/hfv1z6eyltd5js2/Images_neuralStyleTransferReview.zip?dl=0)

## A Taxonomy of Current Methods

### 1. "Slow" Neural Methods Based On Image Optimization

###  1.1. Parametric "Slow" Neural Methods with Summary Statistics

-  [**A Neural Algorithm of Artistic Style**] [[Paper]](https://arxiv.org/pdf/1508.06576.pdf) *(First Neural Style Transfer Paper)*

> **Code:**

*   [Torch-based](https://github.com/jcjohnson/neural-style)
*   [TensorFlow-based](https://github.com/anishathalye/neural-style)
*   [TensorFlow-based with L-BFGS optimizer support](https://github.com/cysmith/neural-style-tf)
*   [Caffe-based](https://github.com/fzliu/style-transfer)
*   [Keras-based](https://github.com/titu1994/Neural-Style-Transfer)
*   [MXNet-based](https://github.com/pavelgonchar/neural-art-mini)
*   [MatConvNet-based](https://github.com/aravindhm/neural-style-matconvnet)

-  [**Image Style Transfer Using Convolutional Neural Networks**] [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) *(CVPR 2016)*

-  [**Stable and Controllable Neural Texture Synthesis and Style Transfer Using Histogram Losses**] [[Paper]](https://arxiv.org/pdf/1701.08893.pdf)

-  [**Demystifying Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1701.01036.pdf)  *(Theoretical Explanation)* *(IJCAI 2017)*

> **Code:**

*   [MXNet-based](https://github.com/lyttonhao/Neural-Style-MMD)

-  [**Content-Aware Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1601.04568.pdf)

-  [**Towards Deep Style Transfer: A Content-Aware Perspective**] [[Paper]](http://www.bmva.org/bmvc/2016/papers/paper008/paper008.pdf)  *(BMVC 2016)*

-  [**Incorporating Long-range Consistency in CNN-based Texture Generation**] [[Paper]](https://arxiv.org/pdf/1606.01286.pdf)  *(ICLR 2017)*

> **Code:**

*   [Theano-based](https://github.com/guillaumebrg/texture_generation)

###  1.2. Non-parametric "Slow" Neural Methods with MRFs

-  [**Combining Markov Random Fields and Convolutional Neural Networks for Image Synthesis**] [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Li_Combining_Markov_Random_CVPR_2016_paper.pdf)  *(CVPR 2016)*

> **Code:**

*   [Torch-based](https://github.com/chuanli11/CNNMRF)

-  [**Neural Doodle_Semantic Style Transfer and Turning Two-Bit Doodles into Fine Artwork**] [[Paper]](https://arxiv.org/pdf/1603.01768.pdf)

###  2. "Fast" Neural Methods Based On Model Optimization

### 2.1. Per-Style-Per-Model "Fast" Neural Methods


-  [**Perceptual Losses for Real-Time Style Transfer and Super-Resolution**] [[Paper]](https://arxiv.org/pdf/1603.08155.pdf)  *(ECCV 2016)*

> **Code:**

*   [Torch-based](https://github.com/jcjohnson/fast-neural-style)
*   [TensorFlow-based](https://github.com/lengstrom/fast-style-transfer)
*   [Chainer-based](https://github.com/yusuketomoto/chainer-fast-neuralstyle)

> **Pre-trained Models:**

*   [Torch-models](https://github.com/ProGamerGov/Torch-Models)
*   [Chainer-models](https://github.com/gafr/chainer-fast-neuralstyle-models)


-  [**Texture Networks: Feed-forward Synthesis of Textures and Stylized Images**] [[Paper]](http://www.jmlr.org/proceedings/papers/v48/ulyanov16.pdf)  *(ICML 2016)*

> **Code:**

*   [Torch-based](https://github.com/DmitryUlyanov/texture_nets)
*   [TensorFlow-based](https://github.com/tgyg-jegli/tf_texture_net)

-  [**Improved Texture Networks: Maximizing Quality and Diversity in Feed-forward Stylization and Texture Synthesis**] [[Paper]](https://arxiv.org/pdf/1701.02096.pdf)  *(CVPR 2017)*

> **Code:**

*   [Torch-based](https://github.com/DmitryUlyanov/texture_nets)

-  [**Precomputed Real-Time Texture Synthesis with Markovian Generative Adversarial Networks**] [[Paper]](https://arxiv.org/pdf/1604.04382.pdf)  *(ECCV 2016)*

> **Code:**

*   [Torch-based](https://github.com/chuanli11/MGANs)

-  [**Multimodal Transfer: A Hierarchical Deep Convolutional Neural Network for Fast Artistic Style Transfer**] [[Paper]](https://arxiv.org/pdf/1612.01895.pdf)  *(CVPR 2017)*

### 2.2. Multiple-Style-Per-Model "Fast" Neural Methods

-  [**A Learned Representation for Artistic Style**] [[Paper]](https://arxiv.org/pdf/1610.07629.pdf)  *(ICLR 2017)*

> **Code:**

*   [TensorFlow-based](https://github.com/tensorflow/magenta/tree/master/magenta/models/image_stylization)

-  [**Multi-style Generative Network for Real-time Transfer**] [[Paper]](https://arxiv.org/pdf/1703.06953.pdf)

> **Code:**

*   [PyTorch-based](https://github.com/zhanghang1989/PyTorch-Style-Transfer)
*   [Torch-based](https://github.com/zhanghang1989/MSG-Net)

-  [**StyleBank: An Explicit Representation for Neural Image Style Transfer**] [[Paper]](https://arxiv.org/pdf/1703.09210.pdf)  *(CVPR 2017)*

-  [**Diversified Texture Synthesis With Feed-Forward Networks**] [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Diversified_Texture_Synthesis_CVPR_2017_paper.pdf)  *(CVPR 2017)*

> **Code:**

*   [Torch-based](https://github.com/Yijunmaverick/MultiTextureSynthesis)

### 2.3. Arbitrary-Style-Per-Model "Fast" Neural Methods

-  [**Fast Patch-based Style Transfer of Arbitrary Style**] [[Paper]](https://arxiv.org/pdf/1612.04337.pdf)

> **Code:**

*   [Torch-based](https://github.com/rtqichen/style-swap)

-  [**Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization**] [[Paper]](https://arxiv.org/pdf/1703.06868.pdf)  *(ICCV 2017)*

> **Code:**

*   [Torch-based](https://github.com/xunhuang1995/AdaIN-style)
*   [TensorFlow-based with Keras](https://github.com/eridgd/AdaIN-TF)
*   [TensorFlow-based without Keras](https://github.com/elleryqueenhomels/arbitrary_style_transfer)


## Slight Modifications of Current Methods

###  1. Modifications of "Slow" Neural Methods

-  [**Exploring the Neural Algorithm of Artistic Style**] [[Paper]](https://arxiv.org/pdf/1602.07188.pdf)

-  [**Improving the Neural Algorithm of Artistic Style**] [[Paper]](https://arxiv.org/pdf/1605.04603.pdf)

-  [**Preserving Color in Neural Artistic Style Transfer**] [[Paper]](https://arxiv.org/pdf/1606.05897.pdf)

-  [**Controlling Perceptual Factors in Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1611.07865.pdf)  *(CVPR 2017)*

> **Code:**

*   [Torch-based](https://github.com/leongatys/NeuralImageSynthesis)

###  2. Modifications of "Fast" Neural Methods

-  [**Instance Normalization：The Missing Ingredient for Fast Stylization**] [[Paper]](https://arxiv.org/pdf/1607.08022.pdf)

> **Code:**

*   [Torch-based](https://github.com/DmitryUlyanov/texture_nets)

-  [**Depth-Preserving Style Transfer**] [[Paper]](https://github.com/xiumingzhang/depth-preserving-neural-style-transfer/blob/master/report/egpaper_final.pdf)

> **Code:**

*   [Torch-based](https://github.com/xiumingzhang/depth-preserving-neural-style-transfer)

-  [**Depth-Aware Neural Style Transfer**]  *(NPAR 2017)*

## Extensions

### Videos

-  [**Son of Zorn's Lemma Targeted Style Transfer Using Instance-aware Semantic Segmentation**] [[Paper]](https://arxiv.org/pdf/1701.02357.pdf)  *(ICASSP 2017)*

-  [**Artistic Style Transfer for Videos**] [[Paper]](https://arxiv.org/pdf/1604.08610.pdf)  *(GCPR 2016)*

> **Code:**

*   [Torch-based](https://github.com/manuelruder/artistic-videos)

- [**Artistic style transfer for videos and spherical images**] [[Paper]](https://arxiv.org/abs/1708.04538)

-  [**DeepMovie: Using Optical Flow and Deep Neural Networks to Stylize Movies**] [[Paper]](https://arxiv.org/pdf/1605.08153.pdf)

-  [**Coherent Online Video Style Transfer**] [[Paper]](https://arxiv.org/pdf/1703.09211.pdf)  *(ICCV 2017)*  *(First end-to-end video style transfer?)*

-  [**Real-Time Neural Style Transfer for Videos**] [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Real-Time_Neural_Style_CVPR_2017_paper.pdf)  *(CVPR 2017)*

-  [**Characterizing and Improving Stability in Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1705.02092.pdf))  *(ICCV 2017)*

### Other Extensions

-  [**Semantic Style Transfer and Turning Two-Bit Doodles into Fine Artwork**] [[Paper]](https://arxiv.org/pdf/1603.01768.pdf)

> **Code:**

*   [Torch-based](https://github.com/alexjc/neural-doodle)

-  [**Painting Style Transfer for Head Portraits Using Convolutional Neural Networks**] [[Paper]](http://dl.acm.org/citation.cfm?id=2925968)  *(SIGGRAPH 2016)*

-  [**Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN**] [[Paper]](https://arxiv.org/pdf/1706.03319.pdf)

-  [**Deep Photo Style Transfer**] [[Paper]](https://arxiv.org/pdf/1703.07511.pdf)  *(CVPR 2017)*

-  [**Decoder Network Over Lightweight Reconstructed Feature for Fast Semantic Style Transfer**] [[Paper]](http://feng-xu.com/papers/iccv2017_style.pdf)  *(ICCV 2017)*


> **Code:**

*   [Torch-based](https://github.com/luanfujun/deep-photo-styletransfer)
*   [TensorFlow-based](https://github.com/LouieYang/deep-photo-styletransfer-tf)

## Application

-  [**Prisma**](https://prisma-ai.com/)

-  [**Ostagram**](https://ostagram.ru/)

> **Code:**

*   [Website code](https://github.com/SergeyMorugin/ostagram)

-  [**Artisto**](https://artisto.my.com)


## Application Papers

-  [**Bringing Impressionism to Life with Neural Style Transfer in Come Swim**] [[Paper]](https://arxiv.org/pdf/1701.04928.pdf)

-  [**Imaging Novecento. A Mobile App for Automatic Recognition of Artworks and Transfer of Artistic Styles**] [[Paper]](https://www.micc.unifi.it/wp-content/uploads/2017/01/imaging900.pdf)

## Blogs

-  [**Caffe2Go**][https://code.facebook.com/posts/196146247499076/delivering-real-time-ai-in-the-palm-of-your-hand/]

-  [**Supercharging Style Transfer**][https://research.googleblog.com/2016/10/supercharging-style-transfer.html]

-  [**Issue of Layer Chosen Strategy**][http://yongchengjing.com/pdf/Issue_layerChosenStrategy_neuralStyleTransfer.pdf]

-  [**Picking an optimizer for Style Transfer**][https://blog.slavv.com/picking-an-optimizer-for-style-transfer-86e7b8cba84b]

## Exciting New Directions

-  **Character Style Transfer**

*   [**Awesome Typography: Statistics-based Text Effects Transfer**][[Paper]](https://arxiv.org/abs/1611.09026)  *(CVPR 2017)*

> **Code:**

*   [Matlab-based](https://github.com/williamyang1991/Text-Effects-Transfer)

*   [**Rewrite: Neural Style Transfer For Chinese Fonts**][[Project]](https://github.com/kaonashi-tyc/Rewrite)

-  **Visual Attribute Transfer through Deep Image Analogy**[[Paper]](https://arxiv.org/pdf/1705.01088.pdf)  *(SIGGRAPH 2017)*

> **Code:**

*   [Caffe-based](https://github.com/msracver/Deep-Image-Analogy)

-  **Fashion Style Generator** [[Paper]](https://www.ijcai.org/proceedings/2017/0520.pdf)  *(IJCAI 2017)*

## Unclassified (To Be Updated Soon)



-  [**Exploring the Structure of a Real-time, Arbitrary Neural Artistic Stylization Network**] [[Paper]](https://arxiv.org/pdf/1705.06830.pdf)  *(BMVC 2017)*



-  [**Laplacian-Steered Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1707.01253.pdf)  *(ACM MM 2017)*

> **Code:**

*   [Torch-based & TensorFlow-based](https://github.com/askerlee/lapstyle)
