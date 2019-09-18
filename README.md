# deep-learning-papers

## Computer Vision
### CNN Architecture
* AlexNet: ImageNet Classification with Deep Convolutional Neural Networks
* ZFNet (DeconvNet): Visualizing and Understanding Convolutional Networks ([note](https://drive.google.com/open?id=1bzkoKVxLALaD6ZWQh5-vP9qOodMdIwi0), code)
* NIN: Network in Network
* VggNet: Very Deep Convolutional Networks for Large-Scale Image Recognition
* GoogLeNet: Going Deeper with Convolutions
* ResNet:
  - ResNet-v1: Deep Residual Learning for Image Recognition
  - ResNet-v2: Identity Mappings in Deep Residual Networks
  - Wide Residual Networks ([note](https://drive.google.com/open?id=14eQSeymwXgS7JvBbAkOnudAm6MFnJify), code)
* InceptionNet:
  - Inception-v1: GoogLeNet
  - Inception-v2, v3: Rethinking the Inception Architecture for Computer Vision ([note](https://drive.google.com/open?id=1SVOpf9aElrAGCZHlX7NvYL8pbehXpw8i), code)
  - Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning 
* DenseNet:
* NASNet: Learning Transferable Architectures for Scalable Image Recognition ([note](https://drive.google.com/open?id=1o1SfbVIgEhRWGQG_mPpxKoCDyWtNoifJ), code)
* EfficientNet:


### [Visualizing CNNs](./doc/visualizing_cnn.md)
* DeconvNet
* BP: Deep inside convolutional networks: Visualising image classification models and saliency maps ([note](https://drive.google.com/open?id=1IBP1uMr08hBp3bKjvyNnwFMu0S8ORGcs))
* Guided-BP (DeconvNet+BP): Striving for simplicity: The all convolutional net ([note](https://drive.google.com/open?id=1KUq5-h_xVmjd4FudGDeBUfPV9vBMHV68), code)
* Understanding Neural Networks Through Deep Visualization


### [Weakly Supervised Localization](./doc/cam.md)
* From Image-level to Pixel-level Labeling with Convolutional Networks (2015)
* GMP-CAM: Is object localization for free? - Weakly-supervised learning with convolutional neural networks (2015) ([note](https://drive.google.com/open?id=1Xpnhq0snjkPMsxKLpmhLOpoZgfFlL9H3), code)
* GAP-CAM: Learning Deep Features for Discriminative Localization (2016) ([note](https://drive.google.com/open?id=1lrkE07E3bnLscAnScwq0OIO3AaRHrqnb), code)
* c-MWP: Top-down Neural Attention by Excitation Backprop
* Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization (2017) ([note](https://drive.google.com/open?id=10obbO7F2igia6gCcc9IqxATzOxdoPl7L), code)


### [Object Detection](./doc/detection.md)
* OverFeat - Integrated Recognition, Localization and Detection using Convolutional Networks ([note](https://drive.google.com/open?id=1O3j-ag0pPRbRjG4ovWmxnZIwhUJ0twvK), code)


### [Semantic Segmentation](./doc/semantic_segmentation.md)
* FCN_V1 (2014)에서 직접적인 영향을 받은 모델들:
  * FCN + max-pooling indices를 사용: SegNet V2 (2015) ([note](https://drive.google.com/open?id=1CDNkW-3LKVDjGAyPCgj8fOz78pMY0Pd7))
  * FCN 개선: Fully Convolutional Networks for Semantic Segmentation (FCN_V2, 2016) ([note](https://drive.google.com/open?id=1Kr2-ZdiqKmsgXP2ofaUZm_PT5UbbTyDN), [code](https://github.com/bt22dr/CarND-Semantic-Segmentation/blob/master/main.py))
  * FCN + atrous convolution과 CRF를 사용: DeepLap V2 (2016)
  * FCN + Dilated convolutions 사용: Multi-Scale Context Aggregation by Dilated Convolutions (2015)
  * FCN + Multi-scale: Predicting Depth, Surface Normals and Semantic Labels with a Common Multi-Scale Convolutional Architecture (2015)
  * FCN + global context 반영 위해 global pooling 사용: ParseNet (2015) 
  * FCN + 모든 레이어에서 skip 사용: U-Net (2015) ([note](https://drive.google.com/open?id=1Up8PiwA79J8R3ScjgYTmLzt8pYYa83EN))
* PSPNet (2016) ([note](https://drive.google.com/open?id=1xPu7Z-0jWepxb1av9fG2Py72Yz0enWym))
* DeepLabv3+ (2018) ([note](https://drive.google.com/open?id=1YFUdcwKzIrTzfmL6o94y01tDXsZ2n6vc))
* EncNet (2018)
* FastFCN (2019)
* Instance Segmentation
  * DeepMask
  * SharpMask
  * Mask R-CNN (2017) ([note](https://drive.google.com/open?id=1kFVOdctJTcWYkflfCM1Ys-J7Fo8COC6R))
* 3D / Point Cloud
  * PointNet (2017)
  * SGPN (2017)
* Weakly-supervised Segmentation

### [Style Transfer](./doc/style_transfer.md)
* ~~A Neural Algorithm of Artistic Style (2015)~~
* Image Style Transfer Using Convolutional Neural Networks (2016)
* Perceptual Losses for Real-Time Style Transfer and Super-Resolution (2016)
* Instance Normalization: 
  * Instance Normalization: The Missing Ingredient for Fast Stylization (2016)
  * Improved Texture Networks: Maximizing Quality and Diversity in Feed-forward Stylization and Texture Synthesis (2017)


### Siamese, Triplet Network
* Triplet Network
  * FaceNet: A Unified Embedding for Face Recognition and Clustering ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/FaceNet%20-%20A%20Unified%20Embedding%20for%20Face%20Recognition%20and%20Clustering.pdf), code)
  * Learning Fine-grained Image Similarity with Deep Ranking ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Learning%20Fine-grained%20Image%20Similarity%20with%20Deep%20Ranking.pdf), code)
* Siamese Network


### Mobile
* Shufflenet: An extremely efficient convolutional neural network for mobile devices
* Mobilenets: Efficient convolutional neural networks for mobile vision applications


### [Etc.](./doc/etc/md)
* A guide to convolution arithmetic for deep learning ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/A%20guide%20to%20convolution%20arithmetic%20for%20deep%20learning.pdf))


## [Generative Models](./doc/gan.md)

### Models

#### Autoregressive Models
* NADE (2011)
* RNADE (2013)
* MADE (2015)
* PixelRNN 계열
  * PixelCNN (2016): ([note](./paper/Pixel%20Recurrent%20Neural%20Networks.pdf), [code1(mnist)](./code/PixelCNN_mnist.ipynb), [code2(fashion_mnist)](./code/PixelCNN_fashionmnist.ipynb))
  * WaveNet (2016) ([note](./paper/WaveNet%20A%20Generative%20Model%20for%20Raw%20Audio.pdf), [code](./code/WaveNet.ipynb))
  * VQ-VAE: Neural Discrete Representation Learning

#### Variational Autoencoders
* VAE ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/doc/gan.md#auto-encoding-variational-bayes), [code1(mnist)](./code/vae.ipynb), [code2(fashion_mnist)](./code/vae_fashion_mnist.ipynb))
* Conditional VAE ([note](./paper/Learning%20Structured%20Output%20Representation%20using%20Deep%20Conditional%20Generative%20Models.pdf), [code](./code/conditional_vae_fashion_mnist.ipynb))
* VAE-GAN: Autoencoding beyond pixels using a learned similarity metric

#### Normalizing Flow Models
* NICE (2014) ([note](./paper/NICE%20Non-linear%20Independent%20Components%20Estimation.pdf))
* Variational Inference with Normalizing Flows (2015) ([code](https://drive.google.com/drive/folders/1-kqyXOvnuw7aeOwbAfKO2OWUkFdv3AmR))
* IAF (2016)
* MAF (2017)
* Glow (2018)

#### GANs
* GAN: Generative Adversarial Networks ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Generative%20Adversarial%20Networks.pdf), [code1(mnist)](./code/gan.ipynb), [code2(fashion_mnist)](./code/gan_fashion_mnist.ipynb))
* DCGAN ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Unsupervised%20Representation%20Learning%20with%20Deep%20Convolutional%20Generative%20Adversarial%20Networks.pdf), [code1](./code/dcgan_mnist.ipynb), [code2](./code/dcgan_celebA.ipynb))
* WGAN 계열: 
  * WGAN: Wasserstein GAN ([note(진행중)](./paper/Wasserstein%20GAN.pdf), [code](./code/wgan.ipynb))
  * WGAN_GP: Improved Training of Wasserstein GANs 
  * CT-GAN: Improving the Improved Training of Wasserstein GANs
* infoGAN
* Improved GAN: 
* SNGAN: Spectral Normalization for Generative Adversarial Networks ([note(진행중)](./paper/Spectral%20Normalization%20for%20Generative%20Adversarial%20Networks.pdf), [code](./code/sngan_fashion_mnist.ipynb))
* SAGAN: 
* CoGAN: Coupled Generative Adversarial Networks (note, code)

### [Image generation](./doc/img2img_translation.md)
#### image-to-image
* cGAN: Conditional Generative Adversarial Nets (2014) ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Conditional%20Generative%20Adversarial%20Nets.pdf), [code](./code/cgan.ipynb))
* (내맘대로)pix2pix 계열:
  * pix2pix: Image-to-Image Translation with Conditional Adversarial Networks (2016) ([note](./paper/Image-to-Image%20Translation%20with%20Conditional%20Adversarial%20Networks.pdf))
  * ~~pix2pixHD~~
  * CycleGAN: 
  * BicycleGAN
  * vid2vid: Video-to-Video Synthesis
  * SPADE: Semantic Image Synthesis with Spatially-Adaptive Normalization (2019) ([note](./paper/Semantic%20Image%20Synthesis%20with%20Spatially-Adaptive%20Normalization.pdf))
* StarGAN: 
* PGGAN: 
* ~~UNIT/MUNIT~~
* ~~iGAN~~
* StyleGAN: 

#### text-to-image
* Generative adversarial text to image synthesis
* StackGAN
* AttnGAN

### Sequence generation
* WaveGAN: ([note](./paper/WaveGAN-%20Synthesizing%20Audio%20with%20Generative%20Adversarial%20Networks.pdf), code)
* SeqGAN:

### Evaluation
* A note on the evaluation of generative models
* A Note on the Inception Score

### CS236 (Deep Generative Models)
* Introduction and Background ([slide 1](./paper/cs236_lecture1.pdf), [slide 2](./paper/cs236_lecture2.pdf))
* Autoregressive Models ([slide 3](./paper/cs236_lecture3.pdf), [slide 4](./paper/cs236_lecture4.pdf))
* Variational Autoencoders 
* Normalizing Flow Models 
* Generative Adversarial Networks 
* Energy-based models 

## NLP
* Recent Trends in Deep Learning Based Natural Language Processing ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Recent%20Trends%20in%20Deep%20Learning%20Based%20Natural%20Language%20Processing.pdf))

### RNN Architecture
* Seq2Seq
  - Learning Phrase Representations Using RNN Encoder-Decoder for Statistical Machine Translation (2014)
  - Sequence to Sequence Learning with Neural Networks (2014) ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Sequence%20to%20Sequence%20Learning%20with%20Neural%20Networks%20(2014).pdf), code)
  - A Neural Conversational Model
* Attention
  - (Luong) Effective Approaches to Attention-based Neural Machine Translation (2015)
  - (Bahdanau) Neural Machine Translation by Jointly Learning to Align and Translate (2014) ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/Neural%20Machine%20Translation%20by%20Jointly%20Learning%20to%20Align%20and%20Translate%20(2014).pdf), code)
  - Transformer: Attention Is All You Need (2017)
* Memory Network
  - Memory Networks (2014) 
  - End-To-End Memory Networks (2015)
* Residual Connection
  - Deep Recurrent Models with Fast-Forward Connections for NeuralMachine Translation (2016)
  - Google's Neural MachineTranslation: Bridging the Gap between Human and Machine Translation (2016)
* CNN
  - Convolutional Neural Networks for Sentence Classification (2014)
  - ByteNet: Neural Machine Translation in Linear Time (2017)
  - Depthwise Separable Convolutions for Neural Machine Translation (2017)
  - SliceNet: Convolutional Sequence to Sequence Learning (2017)
### Word Embedding

## Multimodal Learning
* DeVise - A Deep Visual-Semantic Embedding Model: ([note](./paper/DeViSE%20-%20A%20Deep%20Visual-Semantic%20Embedding%20Model.pdf))
* Unifying Visual-Semantic Embeddings with Multimodal Neural Language Models: ([note](./paper/Unifying%20Visual-Semantic%20Embeddings%20with%20Multimodal%20Neural%20Language%20Models.pdf))
* Show and Tell: ([note](./paper/Show%20and%20Tell%20A%20Neural%20Image%20Caption%20Generator.comp.pdf))
* Show, Attend and Tell: ([note](./paper/Show%20Attend%20and%20Tell%20Neural%20Image%20Caption%20Generation%20with%20Visual%20Attention.comp.pdf))
* Multimodal Machine Learning: A Survey and Taxonomy: ([note](./paper/Multimodal%20Machine%20Learning%20-%20A%20Survey%20and%20Taxonomy.pdf))


## [Etc.](./doc/etc.md) (Optimization, Normalization, Applications)
* An overview of gradient descent optimization algorithms ([note](https://github.com/bt22dr/deep-learning-papers/blob/master/paper/An%20overview%20of%20gradient%20descent%20optimization%20algorithms.pdf))
* Dropout:
* Batch Normalization: ([pdf+memo](./paper/Batch%20Normalization%20-%20Accelerating%20Deep%20Network%20Training%20by%20Reducing%20Internal%20Covariate%20Shift.pdf), code)
* How Does Batch Normalization Help Optimization?
* Spectral Norm Regularization for Improving the Generalizability of Deep Learning ([note(진행중)](./paper/Spectral%20Norm%20Regularization%20for%20Improving%20the%20Generalizability%20of%20Deep%20Learning.pdf), code)
* Wide & Deep Learning for Recommender Systems



## [Drug Discovery](./doc/medical.md)

