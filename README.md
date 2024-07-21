## Course website: https://hanlab.mit.edu/courses/2023-fall-65940

## List of papers:

### Neural Architecture Search(NAS):
Early NAS methods using RNN-based controllers 
- [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578), ICLR 2017
- [Learning Transferable Architectures for Scalable Image Recognition](https://arxiv.org/abs/1707.07012) NASNet, CVPR 2018
- [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/abs/1807.11626)

Differentiable NAS methods
- [DARTS: Differentiable Architecture Search](https://arxiv.org/abs/1806.09055), ICLR 2019
- [ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware](https://arxiv.org/abs/1812.00332), ICLR 2019
- [FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search](https://arxiv.org/abs/1812.03443), CVPR 2019
- [Single Path One-Shot Neural Architecture Search with Uniform Sampling](https://arxiv.org/abs/1904.00420), ECCV 2020

State of the art (used in the lab's notebook)
- [Once-for-All: Train One Network and Specialize it for Efficient Deployment](https://arxiv.org/abs/1908.09791)

MCUNets
- [MCUNet: Tiny Deep Learning on IoT Devices](https://arxiv.org/abs/2007.10319)
- [MCUNetV2: Memory-Efficient Patch-based Inference for Tiny Deep Learning](https://arxiv.org/abs/2110.15352)

COCO datasets
- [Microsoft COCO: Common Objects in Context](https://arxiv.org/abs/1405.0312)

Inverted MobileNet blocks
- [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://arxiv.org/abs/1801.04381)

Efficiency constraints in real world
- [Visual Wake Words with TensorFlow Lite Micro](https://blog.tensorflow.org/2019/10/visual-wake-words-with-tensorflow-lite_30.html) TensorFlow Blog

### TinyEngine and Parallel Processing:
- MCUNet: Tiny Deep Learning on IoT Devices [Lin et al., NeurIPS 2020]
- On-Device Training Under 256KB Memory [Lin et al., NeurIPS 2022]
- [Parallel Computing Tutorial](https://github.com/mit-han-lab/parallel-computing-tutorial)
- [What Is Multithreading In OS? Understanding The Details](https://unstop.com/blog/multithreading-in-os)
- [Multithreading Models in Operating System](https://www.javatpoint.com/multithreading-models-in-operating-system)
- [Stanford CS 149: PARALLEL COMPUTING](https://gfxcourses.stanford.edu/cs149/fall23)

### Vision Transformer:
- An image is worth 16x16 words
- Segment Anything
- EfficientViT: multi-scale linear attention
- Flamingo: a Visual Language Model for Few-Shot Learning [Alayrac et al., 2022]
- PaLM-E: An Embodied Multimodal Language Model [Driess et al., 2022]

### GAN, Video, and Point Cloud
- Generative Adversarial Networks [Goodfellow et al., 2014]
- [Overview of GAN Structure](https://developers.google.com/machine-learning/gan/gan_structure)

### Diffusion Model
- [Tutorial](https://cvpr2022-tutorial-diffusion-models.github.io/)
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239), [Ho et al., NeuriPS 2020]
- [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.net/blog/2021/score/)
- [CMU 16-726](https://learning-image-synthesis.github.io/sp23/static_files/lectures/Lecture9_generative_models_(partII).pdf)
- [Deep Unsupervised Learning using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585)
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
- [Adding Conditional Control to Text-to-Image Diffusion Models](https://arxiv.org/abs/2302.05543) [Zhang et al., ICCV 2023]
- [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598) [Ho & Salimans, 2021]
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) [Rombach et al., CVPR 2022]
- [Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502) [Song et al., ICLR 2021]
- On Distillation of Guided Diffusion Models [Meng et al., CVPR 2023]
- Efficient Spatially Sparse Inference for Conditional GANs and Diffusion Models [Li et al., NeurIPS 2022]
- Q-Diffusion: Quantizing Diffusion Models [Li et al., ICCV 2023]

### Distributed Training
- Scaling Distributed Machine Learning with the Parameter Server. Mu Li et al. 2014
- ZeRO: Memory Optimizations Toward Training Trillion Parameter Models
- Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism
- Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM
- DeepSpeed: Extreme-scale model training for everyone
- Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning [Zheng et al. 2022]
