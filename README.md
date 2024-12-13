![](https://github.com/lizhh268/awesome_underwater_image_enhancement-UIE-/blob/main/uie.png)

# Awesome_Underwater_Image_Enhancement-UIE-
A repository of the latest work related to underwater image enhancement (awaiting continuous updates). 
We hope this can be of assistance!

**[In Construction]** 
Questions and discussions are most welcome! Upcoming works will be updated on a regular basis, feel free to contact me to add... 👍

## Underwater Image Datasets

### Image Enhancement / Restoration

- LSUI dataset: [Data](https://github.com/LintaoPeng/U-shape_Transformer_for_Underwater_Image_Enhancement), [Paper](https://arxiv.org/abs/2111.11843). (paired, Utrans)
- SUIM-E dataset: [Data](https://github.com/trentqq/SUIM-E), [Paper](https://ieeexplore.ieee.org/document/9930878). (paired, SGUIE-Net)
- UFO dataset: [Data](http://irvlab.cs.umn.edu/resources/ufo-120-dataset), [Paper](https://arxiv.org/abs/2002.01155v1). (paired, super-resolution, SESR)
- EUVP dataset: [Data](http://irvlab.cs.umn.edu/resources/euvp-dataset), [Paper](https://arxiv.org/abs/1903.09766), [Code](https://github.com/xahidbuffon/funie-gan). (paired and unpaired data; FUnIE-GAN)
- UIEB / UIEBD dataset: [Data](https://li-chongyi.github.io/proj_benchmark.html), [Paper](https://arxiv.org/abs/1901.05495), [Code](https://github.com/Li-Chongyi/Water-Net_Code). (Water-Net)
- UVEB dataset: [Data](https://github.com/yzbouc/UVEB), [Paper](https://arxiv.org/abs/2404.14542), [Code](https://github.com/yzbouc/UVEB). (video data; UVE-Net)
- SQUID dataset: [Data](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html), [Paper](https://arxiv.org/abs/1811.01343), [Code](https://github.com/danaberman/underwater-hl). (Underwater-HL)
- U-45: [Data](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-), [Paper](https://arxiv.org/abs/1906.06819). (UDAE)
- RUIE benchmark: [Data](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark), [Paper](https://arxiv.org/abs/1901.05320). (RUIE-Net)
- Jamaica port royal: [Data](https://github.com/kskin/data), [Paper](https://arxiv.org/abs/1702.07392), [Code](https://github.com/kskin/WaterGAN/). (Water-GAN)
- Virtual periscope: [Data](http://webee.technion.ac.il/~yoav/research/random_distort.html), [Paper](https://ieeexplore.ieee.org/abstract/document/7448905).
- Color restoration: [Data](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html), [Paper](https://arxiv.org/abs/1811.01343), [Code](https://github.com/danaberman/underwater-hl).
- TURBID data: [Data](http://amandaduarte.com.br/turbid/), [Paper](https://ieeexplore.ieee.org/abstract/document/7485524).
- OceanDark dataset: [Data](https://sites.google.com/view/oceandark/home), [Paper](https://www.mdpi.com/2313-433X/5/10/79).
- Underwater imagenet: [Data](http://irvlab.cs.umn.edu/resources/), [Paper](https://ieeexplore.ieee.org/document/8460552), [Code](https://github.com/cameronfabbri/Underwater-Color-Correction). (paired data; UGAN)

### Others (super-resolution and ...)
Pelase go to https://github.com/xahidbuffon/Awesome_Underwater_Datasets which also includes image enhancement, super-resoulution, object detection, image segmentation and other datasets.

## Papers and Codes

### Underwater Image Enhancement
* `CVPR2024` UVEB: A Large-scale Benchmark and Baseline Towards Real-World Underwater Video Enhancement [[Paper]](https://arxiv.org/abs/2404.14542.) [[Code]](https://github.com/yzbouc/UVEB)

* `BMVC2023` Five A+ Network: You Only Need 9KParameters for Underwater Image Enhancement [[Paper]](https://arxiv.org/abs/2305.08824#:~:text=In%20this%20work%2C%20we%20propose%20the%20Five%20A,FA%20%2B%20Net%20employs%20a%20two-stage%20enhancement%20structure.) [[Code]](https://github.com/Owen718/FiveAPlus-Network)

* `TIP2023` PUGAN: Physical Model-Guided Underwater Image Enhancement Using GAN with Dual-Discriminators [[Paper]](https://ieeexplore.ieee.org/document/10155564) [[Code]](https://github.com/rmcong/PUGAN_TIP2023)

* `TIP2022` U-shape Transformer for Underwater Image Enhancement [[Paper]](https://arxiv.org/abs/2111.11843) [[Code]](https://github.com/LintaoPeng/U-shape_Transformer_for_Underwater_Image_Enhancement)

* `TIP2022` SGUIE-Net: Semantic Attention Guided Underwater Image Enhancement With Multi-Scale Perception [[Paper]](https://ieeexplore.ieee.org/document/9930878) [[Code]](https://github.com/trentqq/SGUIE-Net_Simple)

* `TGRS2022` Reinforced Swin-Convs Transformer for Simultaneous Underwater Sensing Scene Image Enhancement and Super-resolution [[Paper]](https://arxiv.org/abs/2205.00434v1) [[Code]](https://github.com/TingdiRen/URSCT-SESR)

* `TIP2019` An Underwater Image Enhancement Benchmark Dataset and Beyond [[Paper]](https://ar5iv.labs.arxiv.org/html/1901.05495) [[Code]](https://github.com/Li-Chongyi/Water-Net_Code)

* `TIP2020` Underwater Image Enhancement via Medium Transmission-Guided Multi-Color Space Embedding [[Paper]](https://ieeexplore.ieee.org/document/9426457) [[Code]](https://github.com/Li-Chongyi/Ucolor)

* `RSS2020` Simultaneous Enhancement and Super-Resolution of Underwater Imagery for Improved Visual Perception [[Paper]](https://www.roboticsproceedings.org/rss16/p018.pdf) [[Code]](https://github.com/xahidbuffon/Deep_SESR)

## Metrics

### Full-Reference Evaluation

* PSNR (Peak Signal-to-Noise Ratio) [[Wiki]](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) [[Matlab Code]](https://www.mathworks.com/help/images/ref/psnr.html) [[Python Code]](https://github.com/aizvorski/video-quality)
* SSIM (Structural similarity) [[Wiki]](https://en.wikipedia.org/wiki/Structural_similarity) [[Matlab Code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[Python Code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py)

### Non-Reference Evaluation
* UCIQE (Underwater Colour Image Quality Evaluation) A metric uses a linear combination of chromaticity, saturation, and contrast to quantify the uneven color cast, blurriness, and low contrast characteristics of underwater engineering and surveillance images. [Paper: An Underwater Colour Image Quality Evaluation Metric]
* UIQM (Underwater Image Quality Measure) includes three underwater image quality assessments: Underwater Image Colorfulness Measure (UICM), Underwater Image Sharpness Measure (UISM), and Underwater Image Contrast Measure (UIConM). [Paper: Human-Visual-System-Inspired Underwater Image Quality Measures]

