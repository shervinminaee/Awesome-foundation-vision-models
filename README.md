# Awesome Foundation Vision Models

A curated list of the most influential foundation models in computer vision. These are the landmark papers that introduced architectures, pre-training methods, and models which have shaped modern visual understanding, generation, and multimodal AI. If there is a paper missing here, please open an issue or submit a pull request, and I would be happy to include it in this list.

# Background

Foundation vision models are large-scale models pre-trained on broad visual data that can be adapted to a wide range of downstream tasks. Starting with the Vision Transformer (ViT) and contrastive vision-language pre-training (CLIP), the field has rapidly evolved to include self-supervised methods, diffusion-based generators, segmentation foundation models, and unified architectures. This list focuses on the original model papers (not surveys) that have become foundational to the field.

# Table of Contents
[1. Vision Transformers & Backbone Architectures](#backbones)
[2. Self-Supervised & Masked Image Modeling](#ssl)
[3. Contrastive Vision-Language Models](#clip)
[4. Image Generation (Diffusion & Autoregressive)](#generation)
[5. Segmentation Foundation Models](#segmentation)
[6. Object Detection & Open-Vocabulary Recognition](#detection)
[7. Video Foundation Models](#video)
[8. Multimodal Large Language Models (Vision)](#mllm)
[9. 3D & Spatial Vision Models](#3d)


### 1. Vision Transformers & Backbone Architectures <a name="backbones"></a>
* [An image is worth 16x16 words: Transformers for image recognition at scale (ViT)](https://arxiv.org/abs/2010.11929) (ICLR, 2021)
* [Swin Transformer: Hierarchical vision transformer using shifted windows](https://arxiv.org/abs/2103.14030) (ICCV, 2021)
* [DeiT: Training data-efficient image transformers & distillation through attention](https://arxiv.org/abs/2012.12877) (ICML, 2021)
* [Scaling vision transformers (ViT-22B)](https://arxiv.org/abs/2302.05442) (ICML, 2023)
* [ConvNeXt: A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545) (CVPR, 2022)
* [InternImage: Exploring large-scale vision foundation models with deformable convolutions](https://arxiv.org/abs/2211.05778) (CVPR, 2023)

### 2. Self-Supervised & Masked Image Modeling <a name="ssl"></a>
* [DINO: Emerging properties in self-supervised vision transformers](https://arxiv.org/abs/2104.14294) (ICCV, 2021)
* [DINOv2: Learning robust visual features without supervision](https://arxiv.org/abs/2304.07193) (TMLR, 2024)
* [MAE: Masked autoencoders are scalable vision learners](https://arxiv.org/abs/2111.06377) (CVPR, 2022)
* [BEiT: BERT pre-training of image transformers](https://arxiv.org/abs/2106.08254) (ICLR, 2022)
* [iBOT: Image BERT pre-training with online tokenizer](https://arxiv.org/abs/2111.07832) (ICLR, 2022)

### 3. Contrastive Vision-Language Models <a name="clip"></a>
* [CLIP: Learning transferable visual models from natural language supervision](https://arxiv.org/abs/2103.00020) (ICML, 2021)
* [ALIGN: Scaling up visual and vision-language representation learning with noisy text supervision](https://arxiv.org/abs/2102.05918) (ICML, 2021)
* [SigLIP: Sigmoid loss for language image pre-training](https://arxiv.org/abs/2303.15343) (ICCV, 2023)
* [EVA-CLIP: Improved training techniques for CLIP at scale](https://arxiv.org/abs/2303.15389) (arXiv, 2023)
* [OpenCLIP: Reproducible scaling laws for contrastive language-image learning](https://arxiv.org/abs/2212.07143) (CVPR, 2023)

### 4. Image Generation (Diffusion & Autoregressive) <a name="generation"></a>
* [Denoising diffusion probabilistic models (DDPM)](https://arxiv.org/abs/2006.11239) (NeurIPS, 2020)
* [High-resolution image synthesis with latent diffusion models (Stable Diffusion)](https://arxiv.org/abs/2112.10752) (CVPR, 2022)
* [DALL·E 2: Hierarchical text-conditional image generation with CLIP latents](https://arxiv.org/abs/2204.06125) (arXiv, 2022)
* [Imagen: Photorealistic text-to-image diffusion models with deep language understanding](https://arxiv.org/abs/2205.11487) (NeurIPS, 2022)
* [Scalable diffusion models with transformers (DiT)](https://arxiv.org/abs/2212.09748) (ICCV, 2023)

### 5. Segmentation Foundation Models <a name="segmentation"></a>
* [Segment Anything (SAM)](https://arxiv.org/abs/2304.02643) (ICCV, 2023)
* [SAM 2: Segment Anything in Images and Videos](https://arxiv.org/abs/2408.00714) (arXiv, 2024)
* [Grounded SAM: Assembling open-world models for diverse visual tasks](https://arxiv.org/abs/2401.14159) (arXiv, 2024)
* [SEEM: Segment everything everywhere all at once](https://arxiv.org/abs/2304.06718) (NeurIPS, 2023)

### 6. Object Detection & Open-Vocabulary Recognition <a name="detection"></a>
* [DINO (detection): DETR with improved denoising anchor boxes](https://arxiv.org/abs/2203.03605) (ICLR, 2023)
* [Grounding DINO: Marrying DINO with grounded pre-training for open-set object detection](https://arxiv.org/abs/2303.05499) (ECCV, 2024)
* [OWL-ViT: Simple open-vocabulary object detection with vision transformers](https://arxiv.org/abs/2205.06230) (ECCV, 2022)
* [Florence: A new foundation model for computer vision](https://arxiv.org/abs/2111.11432) (arXiv, 2021)

### 7. Video Foundation Models <a name="video"></a>
* [VideoMAE: Masked autoencoders as data-efficient learners for self-supervised video pre-training](https://arxiv.org/abs/2203.12602) (NeurIPS, 2022)
* [InternVideo: General video foundation models via generative and discriminative learning](https://arxiv.org/abs/2212.03191) (arXiv, 2022)
* [Sora: Video generation models as world simulators](https://openai.com/index/video-generation-models-as-world-simulators/) (OpenAI, 2024)

### 8. Multimodal Large Language Models (Vision) <a name="mllm"></a>
* [LLaVA: Visual instruction tuning](https://arxiv.org/abs/2304.08485) (NeurIPS, 2023)
* [GPT-4V(ision) system card](https://arxiv.org/abs/2309.17421) (OpenAI, 2023)
* [Flamingo: A visual language model for few-shot learning](https://arxiv.org/abs/2204.14198) (NeurIPS, 2022)
* [InternVL: Scaling up vision foundation models and aligning for generic visual-linguistic tasks](https://arxiv.org/abs/2312.14238) (CVPR, 2024)
* [Qwen-VL: A versatile vision-language model for understanding, localization, text reading, and beyond](https://arxiv.org/abs/2308.12966) (arXiv, 2023)

### 9. 3D & Spatial Vision Models <a name="3d"></a>
* [NeRF: Representing scenes as neural radiance fields for view synthesis](https://arxiv.org/abs/2003.08934) (ECCV, 2020)
* [3D Gaussian Splatting for real-time radiance field rendering](https://arxiv.org/abs/2308.14737) (SIGGRAPH, 2023)
* [Point-E: A system for generating 3D point clouds from complex prompts](https://arxiv.org/abs/2212.08751) (arXiv, 2022)

