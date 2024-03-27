# Awesome-VQVAE
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/rese1f/awesome-VQVAE) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

A collection of resources and papers on Vector Quantized Variational Autoencoder (**VQ-VAE**) and its application.

- [Blog](#blog)
- [Paper](#paper)
   * [Image](#image)
   * [Video](#video)
   * [3D](#3d)
   * [Human Pose](#human-pose)
   * [Low-level Vision](#low-level-vision)
   * [Others](#others)
   * [Speech & Audio](#speechaudio)
## Blog

<!-- **Title** \
*author* \
[[Website](link)] \
24 Sep 2022 -->

**Understanding VQ-VAE (DALL-E Explained Pt. 1)** \
*Charlie Snell* \
[[Website](https://ml.berkeley.edu/blog/posts/vq-vae/)] \
9 Feb 2021

**How is it so good ? (DALL-E Explained Pt. 2)** \
*Charlie Snell* \
[[Website](https://ml.berkeley.edu/blog/posts/dalle2/)] \
7 Apr 2021

**VQ-VAE: A brief introduction** \
*Jianlin Su* \
[[Website](https://kexue.fm/archives/6760)] \
24 June 2019

<!-- ## Survey -->

<!-- **Title** \
*author* \
arXiv 2023. [[Paper](link)] \
13 Feb 2023 -->

## Paper

<!-- **Title** \
*author* \
arXiv 2023. [[Paper](link)] [[Github](link)] -->

### Image

**HQ-VAE: Hierarchical Discrete Representation Learning with Variational Bayes** \
*Yuhta Takida, Yukara Ikemiya, Takashi Shibuya, Kazuki Shimada, Woosung Choi, Chieh-Hsin Lai, Naoki Murata, Toshimitsu Uesaka, Kengo Uchida, Wei-Hsiang Liao, Yuki Mitsufuji* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2401.00365)]

**Towards Accurate Image Coding: Improved Autoregressive Image Generation with Dynamic Vector Quantization** \
*Mengqi Huang, Zhendong Mao, Zhuowei Chen, Yongdong Zhang* \
CVPR 2023 Highlight. [[Paper](https://arxiv.org/abs/2305.11718)]

**Not All Image Regions Matter: Masked Vector Quantization for Autoregressive Image Generation** \
*Mengqi Huang, Zhendong Mao, Quan Wang, Yongdong Zhang* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2305.13607)]

**MAGE: MAsked Generative Encoder to Unify Representation Learning and Image Synthesis** \
*Tianhong Li, Huiwen Chang, Shlok Kumar Mishra, Han Zhang, Dina Katabi, Dilip Krishnan* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2211.09117)]

**Regularized Vector Quantization for Tokenized Image Synthesis** \
*Jiahui Zhang, Fangneng Zhan, Christian Theobalt, Shijian Lu* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2303.06424)]

**All in Tokens: Unifying Output Space of Visual Tasks via Soft Token** \
*Jia Ning, Chen Li, Zheng Zhang, Zigang Geng, Qi Dai, Kun He, Han Hu* \
ICCV 2023. [[Paper](https://arxiv.org/abs/2301.02229)]

**StylerDALLE: Language-Guided Style Transfer Using a Vector-Quantized Tokenizer of a Large-Scale Generative Model** \
*Zipeng Xu, Enver Sangineto, Nicu Sebe* \
ICCV 2023. [[Paper](https://arxiv.org/abs/2303.09268)]

**Peco: Perceptual Codebook for Bert Pre-training of Vision Transformers** \
*Xiaoyi Dong, Jianmin Bao, Ting Zhang, Dongdong Chen, Weiming Zhang, Lu Yuan, Dong Chen, Fang Wen, Nenghai Yu, Baining Guo* \
AAAI 2023. [[Paper](https://arxiv.org/abs/2111.12710)]

**Designing a Better Asymmetric VQGAN for StableDiffusion** \
*Zixin Zhu, Xuelu Feng, Dongdong Chen, Jianmin Bao, Le Wang, Yinpeng Chen, Lu Yuan, Gang Hua* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2306.04632)]

**LLM Itself Can Read and Generate CXR Images** \
*Suhyeon Lee, Won Jun Kim, Jong Chul Ye* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2305.11490)]

**SPAE: Semantic Pyramid AutoEncoder for Multimodal Generation with Frozen LLMs** \
*Lijun Yu, Yong Cheng, Zhiruo Wang, Vivek Kumar, Wolfgang Macherey, Yanping Huang, David A. Ross, Irfan Essa, Yonatan Bisk, Ming-Hsuan Yang, Kevin Murphy, Alexander G. Hauptmann, Lu Jiang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2306.17842)]

**Scaling Laws for Generative Mixed-Modal Language Models** \
*Armen Aghajanyan, Lili Yu, Alexis Conneau, Wei-Ning Hsu, Karen Hambardzumyan, Susan Zhang, Stephen Roller, Naman Goyal, Omer Levy, Luke Zettlemoyer* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2301.03728)]

**MoVQ: Modulating Quantized Vectors for High-Fidelity Image Generation** \
*Chuanxia Zheng, Long Tung Vuong, Jianfei Cai, Dinh Phung* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.09002)]

**SQ-VAE: Variational Bayes on Discrete Representation with Self-annealed Stochastic Quantization** \
*Yuhta Takida, Takashi Shibuya, WeiHsiang Liao, Chieh-Hsin Lai, Junki Ohmura, Toshimitsu Uesaka, Naoki Murata, Shusuke Takahashi, Toshiyuki Kumakura, Yuki Mitsufuji* \
ICML 2022. [[Paper](https://arxiv.org/abs/2205.07547)]

**Vector-quantized Image Modeling with Improved VQGAN** \
*Jiahui Yu, Xin Li, Jing Yu Koh, Han Zhang, Ruoming Pang, James Qin, Alexander Ku, Yuanzhong Xu, Jason Baldridge, Yonghui Wu* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2110.04627)]

**BEiT v2: Masked Image Modeling with Vector-Quantized Visual Tokenizers** \
*Zhiliang Peng, Li Dong, Hangbo Bao, Qixiang Ye, Furu Wei* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.06366)]

**BEiT: BERT Pre-Training of Image Transformers** \
*Hangbo Bao, Li Dong, Songhao Piao, Furu Wei* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2106.08254)]

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer* \
CVPR 2022  [[Paper](https://arxiv.org/abs/2112.10752)]

**Vector Quantized Diffusion Model for Text-to-Image Synthesis** \
*Shuyang Gu, Dong Chen, Jianmin Bao, Fang Wen, Bo Zhang, Dongdong Chen, Lu Yuan, Baining Guo* \
CVPR 2022  [[Paper](https://arxiv.org/abs/2111.14822)]

**MaskGIT: Masked Generative Image Transformer** \
*Huiwen Chang, Han Zhang, Lu Jiang, Ce Liu, William T. Freeman* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2202.04200)]

**Autoregressive Image Generation using Residual Quantization** \
*Doyup Lee, Chiheon Kim, Saehoon Kim, Minsu Cho, Wook-Shin Han* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2203.01941)]

**VQFR: Blind Face Restoration with Vector-Quantized Dictionary and Parallel Decoder** \
*Yuchao Gu, Xintao Wang, Liangbin Xie, Chao Dong, Gen Li, Ying Shan, Ming-Ming Cheng* \
ECCV 2022. [[Paper](https://arxiv.org/abs/2205.06803)]

**Unified-IO: A Unified Model for Vision, Language, and Multi-Modal Tasks** \
*Jiasen Lu, Christopher Clark, Rowan Zellers, Roozbeh Mottaghi, Aniruddha Kembhavi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.08916)]

**Improved Vector Quantized Diffusion Models** \
*Zhicong Tang, Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.16007)]

**CogView2: Faster and Better Text-to-Image Generation via Hierarchical Transformers** \
*Ming Ding, Wendi Zheng, Wenyi Hong, Jie Tang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.14217)]

**DiVAE: Photorealistic Images Synthesis with Denoising Diffusion Decoder** \
*Jie Shi, Chenfei Wu, Jian Liang, Xiang Liu, Nan Duan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00386)]

**CogView: Mastering Text-to-Image Generation via Transformers** \
*Ming Ding, Zhuoyi Yang, Wenyi Hong, Wendi Zheng, Chang Zhou, Da Yin, Junyang Lin, Xu Zou, Zhou Shao, Hongxia Yang, Jie Tang* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2105.13290)]

**Zero-Shot Text-to-Image Generation** \
*Aditya Ramesh, Mikhail Pavlov, Gabriel Goh, Scott Gray, Chelsea Voss, Alec Radford, Mark Chen, Ilya Sutskever* \
ICML 2021. [[Paper](https://arxiv.org/abs/2102.12092)]

**Generating Diverse Structure for Image Inpainting With Hierarchical VQ-VAE** \
*Jialun Peng, Dong Liu, Songcen Xu, Houqiang Li* \
CVPR 2021. [[Paper](https://arxiv.org/abs/2103.10022)]

**Taming Transformers for High-Resolution Image Synthesis** \
*Patrick Esser, Robin Rombach, B. Ommer* \
CVPR 2020. [[Paper](https://arxiv.org/abs/2012.09841)]

**Generating Diverse High-Fidelity Images with VQ-VAE-2** \
*Ali Razavi, Aäron van den Oord, Oriol Vinyals* \
NeurIPS 2019. [[Paper](https://arxiv.org/abs/1906.00446v1)]

**DVAE++: Discrete Variational Autoencoders with Overlapping Transformations** \
*Arash Vahdat, W. Macready, Zhengbing Bian, Amir Khoshaman* \
ICML 2018. [[Paper](https://arxiv.org/abs/1802.04920)]

**Neural Discrete Representation Learning** \
*Aaron van den Oord, Oriol Vinyals, Koray Kavukcuoglu* \
NeurIPS 2017. [[Paper](https://arxiv.org/abs/1711.00937)]

### Video

**VideoPoet: A Large Language Model for Zero-Shot Video Generation** \
*Dan Kondratyuk, Lijun Yu, Xiuye Gu, José Lezama, Jonathan Huang, Rachel Hornung, Hartwig Adam, Hassan Akbari, Yair Alon, Vighnesh Birodkar, Yong Cheng, Ming-Chang Chiu, Josh Dillon, Irfan Essa, Agrim Gupta, Meera Hahn, Anja Hauth, David Hendon, Alonso Martinez, David Minnen, David Ross, Grant Schindler, Mikhail Sirotenko, Kihyuk Sohn, Krishna Somandepalli, Huisheng Wang, Jimmy Yan, Ming-Hsuan Yang, Xuan Yang, Bryan Seybold, Lu Jiang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2312.14125)]

**Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation** \
*Lijun Yu, José Lezama, Nitesh B. Gundavarapu, Luca Versari, Kihyuk Sohn, David Minnen, Yong Cheng, Agrim Gupta, Xiuye Gu, Alexander G. Hauptmann, Boqing Gong, Ming-Hsuan Yang, Irfan Essa, David A. Ross, Lu Jiang* \
ICLR 2024. [[Paper](https://arxiv.org/abs/2310.05737)]

**MAGVIT: Masked Generative Video Transformer** \
*Lijun Yu, Yong Cheng, Kihyuk Sohn, José Lezama, Han Zhang, Huiwen Chang, Alexander G. Hauptmann, Ming-Hsuan Yang, Yuan Hao, Irfan Essa, Lu Jiang* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2212.05199)]

**CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers** \
*Wenyi Hong, Ming Ding, Wendi Zheng, Xinghan Liu, Jie Tang* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2205.15868)]

**Long Video Generation with Time-Agnostic VQGAN and Time-Sensitive Transformer** \
*Songwei Ge, Thomas Hayes, Harry Yang, Xi Yin, Guan Pang, David Jacobs, Jia-Bin Huang, Devi Parikh* \
ECCV 2022. [[Paper](https://arxiv.org/abs/2204.03638)]

**Latent Video Transformer** \
*Ruslan Rakhimov, Denis Volkhonskiy, Alexey Artemov, Denis Zorin, Evgeny Burnaev* \
VISIGRAPP 2021. [[Paper](https://arxiv.org/abs/2006.10704)]

**Predicting Video with VQVAE** \
*Jacob Walker, Ali Razavi, Aäron van den Oord* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2103.01950)]

**VideoGPT: Video Generation using VQ-VAE and Transformers** \
*Wilson Yan, Yunzhi Zhang, Pieter Abbeel, Aravind Srinivas* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.10157)]

### 3D

**SDFusion: Multimodal 3D Shape Completion, Reconstruction, and Generation** \
*Yen-Chi Cheng, Hsin-Ying Lee, Sergey Tulyakov, Alexander Schwing, Liangyan Gui* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2212.04493)]

**AutoSDF: Shape Priors for 3D Completion, Reconstruction and Generation** \
*Paritosh Mittal, Yen-Chi Cheng, Maneesh Singh, Shubham Tulsiani* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2203.09516)]

### Human Pose

**MotionGPT: Human Motion as a Foreign Language** \
*Biao Jiang, Xin Chen, Wen Liu, Jingyi Yu, Gang Yu, Tao Chen* \
NeurIPS 2023. [[Paper](https://arxiv.org/abs/2306.14795)]

**Human Pose as Compositional Tokens** \
*Zigang Geng, Chunyu Wang, Yixuan Wei, Ze Liu, Houqiang Li, Han Hu* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2303.11638)]

**HumanTOMATO: Text-aligned Whole-body Motion Generation** \
*Shunlin Lu, Ling-Hao Chen, Ailing Zeng, Jing Lin, Ruimao Zhang, Lei Zhang, Heung-Yeung Shum* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.12978)]

**MoConVQ: Unified Physics-Based Motion Control via Scalable Discrete Representations** \
*Heyuan Yao, Zhenhua Song, Yuyang Zhou, Tenglong Ao, Baoquan Chen, Libin Liu* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.10198)]

**MoMask: Generative Masked Modeling of 3D Human Motions** \
*Chuan Guo, Yuxuan Mu, Muhammad Gohar Javed, Sen Wang, Li Cheng* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2312.00063)]

**Vector Quantized Diffusion Model with CodeUnet for Text-to-Sign Pose Sequences Generation** \
*Pan Xie, Qipeng Zhang, Zexian Li, Hao Tang, Yao Du, Xiaohui Hu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09141)]

### Low-level Vision

**Adverse Weather Removal with Codebook Priors** \
*Tian Ye, Sixiang Chen, Jinbin Bai, Jun Shi, Chenghao Xue, Jingxia Jiang, Junjie Yin, Erkang Chen, Yun Liu* \
ICCV 2023. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Ye_Adverse_Weather_Removal_with_Codebook_Priors_ICCV_2023_paper.html)]

### Others

**CityDreamer: Compositional Generative Model of Unbounded 3D Cities** \
*Haozhe Xie, Zhaoxi Chen, Fangzhou Hong, Ziwei Liu* \
arXiv 2023. [[Paper](http://arxiv.org/abs/2309.00610)]

### Speech&Audio

**SoundStream: An End-to-End Neural Audio Codec** \
*Neil Zeghidour, Alejandro Luebs, Ahmed Omran, Jan Skoglund, Marco Tagliasacchi* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2107.03312)]

**High Fidelity Neural Audio Compression** \
*Alexandre Défossez, Jade Copet, Gabriel Synnaeve, Yossi Adi* \
TMLR 2023. [[Paper](https://arxiv.org/abs/2210.13438)]

**AudioDec: An Open-source Streaming High-fidelity Neural Audio Codec** \
*Yi-Chiao Wu, Israel D. Gebru, Dejan Marković, Alexander Richard* \
ICASSP 2023. [[Paper](https://arxiv.org/abs/2305.16608)]

**High-Fidelity Audio Compression with Improved RVQGAN** \
*Rithesh Kumar, Prem Seetharaman, Alejandro Luebs, Ishaan Kumar, Kundan Kumar* \
NeurIPS 2023. [[Paper](https://arxiv.org/abs/2306.06546)]

**RepCodec: A Speech Representation Codec for Speech Tokenization** \
*Dongchao Yang, Songxiang Liu, Rongjie Huang, Jinchuan Tian, Chao Weng, Yuexian Zou* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2305.02765)]

**HiFi-Codec: Group-residual Vector quantization for High Fidelity Audio Codec** \
*Zhichao Huang, Chutong Meng, Tom Ko* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.00169)]

**SpeechTokenizer: Unified Speech Tokenizer for Speech Large Language Models** \
*Xin Zhang, Dong Zhang, Shimin Li, Yaqian Zhou, Xipeng Qiu* \
ICLR 2024. [[Paper](https://arxiv.org/abs/2308.16692)]

**NaturalSpeech 3: Zero-Shot Speech Synthesis with Factorized Codec and Diffusion Models** \
*Zeqian Ju, Yuancheng Wang, Kai Shen, Xu Tan, Detai Xin, Dongchao Yang, Yanqing Liu, Yichong Leng, Kaitao Song, Siliang Tang, Zhizheng Wu, Tao Qin, Xiang-Yang Li, Wei Ye, Shikun Zhang, Jiang Bian, Lei He, Jinyu Li, Sheng Zhao* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2403.03100)]
