# Awesome-Computer-Vision-Adverse-Weather
The survey on the computer vision works under the adverse weather conditions

## :clipboard: Notations and Abbreviation

| Emoji | Description |
|:-----:|:-----------:|
|:camera:| Single Image |
|:video_camera:| Video-based |
|:artificial_satellite:| Remote Sensing Data |
| :night_with_stars: | Night |
|:bar_chart:| Benchmark |

<details>
<summary><strong>Venue Abbreviation</strong> (click to expand) </summary>

- Conference:
  
| Abbreviation | Full Name |
|:------------:|:---------:|
|CVPR | Computer Vision and Pattern Recognition |
|ICCV | International Conference on Computer Vision |
|ECCV | European Conference on Computer Vision |
|AAAI | AAAI Conference on Artificial Intelligence |
|ICASSP | IEEE International Conference on Acoustics, Speech, and Signal Processing |
|WACV | IEEE Winter Conference on Applications of Computer Vision |
|ICAR | IEEE International Conference on Robotics and Automation |
|ACCV | Asian Conference on Computer Vision |
|ACPR | Asian Conference on Pattern Recognition |
|ISM | IEEE International Symposium on Multimedia |
|ICIP | IEEE International Conference on Image Processing |
|CVM | Computational Visual Media |
|ICTC | International Conference on Information and Communication Technology Convergence |
|ITSC | IEEE International Intelligent Transportation Systems Conference |

- Journal:
  
| Abbreviation | Full Name |
|:------------:|:---------:|
|TOG | ACM Transactions on Graphics |
|TPAMI | IEEE Transactions on Pattern Analysis and Machine Intelligence |
|IJCV | International Journal of Computer Vision |
|TIP | IEEE Transactions on Image Processing |
|TCSVT | IEEE Transactions on Circuits and Systems for Video Technology |
|TIM | IEEE Transactions on Instrumentation and Measurement |
|TCI | IEEE Transactions on Computational Imaging |
|ARCME | Archives of Computational Methods in Engineering |
|OE | Optical Engineering |
|Opt. Express | Optics Express |
</details>

## 🧭 Navigation

- **[Low-level Vision](#low-level-vision)**
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [:fog: Haze removal / Fog Removal / Dehazing / Defogging](#fog-haze-removal--fog-removal--dehazing--defogging)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [:cloud_with_rain: Rain removal / Deraining / De-raining](#cloud_with_rain-rain-removal--deraining--de-raining)
  <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [:umbrella: Rain Streak Removal](#umbrella-rain-streak-removal)
  <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [:droplet: Raindrop Removal](#droplet-raindrop-removal)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [:snowflake: Snow Removal / Desnowing / De-snowing](#snowflake-snow-removal--desnowing--de-snowing)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [All-in-One (AiO) Adverse Weather Removal](#all-in-one-aio-adverse-weather-removal)
  
- **[High-level Vision](#high-level-vision)**
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [Object Detection](#object-detection)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [Semantic Segmentation](#semantic-segmentation)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [Object Tracking](#object-tracking)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [Depth Estimation](#depth-estimation)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [Autonomous Driving](#autonomous-driving)
  <br>&nbsp;&nbsp;&nbsp;&nbsp; [Scene Stylization](#scene-stylization)
  
- **[Citation](#citation)** | **[Contributing](#contributing)**

# Related Literature Review 

| Paper | Venue | Year | Data | Link | Code |
|-------|-------|------|------|------|------|
|A comprehensive review of computational dehazing techniques<br><sub></sub> | ARCME | 2018 | :camera: | [Paper](https://search.proquest.com/openview/678da16cd4b56253ac84ca71f505366e/1?pq-origsite=gscholar&cbl=1486352) | |


# Low-level Vision

## :fog: Haze removal / Fog Removal / Dehazing / Defogging

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Data | Method | Link | Code |
|-------|-------|------|------|--------|------|------|
|Visibility in bad weather from a single image<br><sub>Robby T. Tan</sub> | CVPR | 2008 | 📷 | Model-based | [Paper](https://ieeexplore.ieee.org/abstract/document/4587643) | [Code](https://tanrobby.github.io/research/fog/index.html) |
|Benchmarking single-image dehazing and beyond<br><sub>Boyi Li; Wenqi Ren; Dengpan Fu; Dacheng Tao; Dan Feng; Wenjun Zeng</sub> | TIP | 2018 | :camera:📊 |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8451944/) | [Code](https://github.com/Boyiliee/RESIDE-dataset-link/tree/master) |
|Single image dehazing<br><sub>Raanan Fattal</sub> | TOG | 2008 | :camera: | Model-based | [Paper](https://dl.acm.org/doi/abs/10.1145/1360612.1360671) | [Code](https://www.cs.huji.ac.il/w~raananf/projects/defog/) |
|Enhanced pix2pix dehazing network<br><sub>Yanyun Qu; Yizi Chen; Jingying Huang; Yuan Xie</sub> | CVPR | 2019 | :camera: | CNN | [Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Qu_Enhanced_Pix2pix_Dehazing_Network_CVPR_2019_paper.html) | [Code](https://github.com/ErinChen1/EPDN) |
|Contrastive learning for compact single image dehazing<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Wu_Contrastive_Learning_for_Compact_Single_Image_Dehazing_CVPR_2021_paper.html) | |
|Non-local image dehazing<br><sub></sub> |  | 2016 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2016/html/Berman_Non-Local_Image_Dehazing_CVPR_2016_paper.html) | |
|Vision transformers for single image dehazing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10076399/) | |
|Cycle-dehaze: Enhanced cyclegan for single image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w13/html/Engin_Cycle-Dehaze_Enhanced_CycleGAN_CVPR_2018_paper.html) | |
|Single image dehazing by multi-scale fusion<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6514885/) | |
|Dehazing using color-lines<br><sub></sub> | TOG | 2014 | :camera: | Model-based | [Paper](https://dl.acm.org/doi/abs/10.1145/2651362) | [Code](https://github.com/maxcrous/dehazing_using_color_lines) |
|A comprehensive review on analysis and implementation of recent image dehazing methods<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11831-022-09755-2) | |
|Single image dehazing via multi-scale convolutional neural networks<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_10) | |
|A review of remote sensing image dehazing<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.mdpi.com/1424-8220/21/11/3926) | |
|Aod-net: All-in-one dehazing network<br><sub></sub> |  | 2017 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_iccv_2017/html/Li_AOD-Net_All-In-One_Dehazing_ICCV_2017_paper.html) | |
|An all-in-one network for dehazing and beyond<br><sub></sub> |  | 1707 | :camera: |  | [Paper](https://arxiv.org/abs/1707.06543) | |
|An investigation of dehazing effects on image and video coding<br><sub></sub> |  | 2011 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6008642/) | |
|Griddehazenet: Attention-based multi-scale network for image dehazing<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Liu_GridDehazeNet_Attention-Based_Multi-Scale_Network_for_Image_Dehazing_ICCV_2019_paper.html) | |
|Fast image dehazing method based on linear transformation<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7814312/) | |
|Domain adaptation for image dehazing<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Shao_Domain_Adaptation_for_Image_Dehazing_CVPR_2020_paper.html) | |
|Perceiving and modeling density for image dehazing<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-19800-7_8) | |
|Densely connected pyramid dehazing network<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_Densely_Connected_Pyramid_CVPR_2018_paper.html) | |
|Single remote sensing image dehazing<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6476634/) | |
|Single image dehazing using haze-lines<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8540862/) | |
|D-hazy: A dataset to evaluate quantitatively dehazing algorithms<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7532754/) | |
|Recent advances in image dehazing<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://www.ieee-jas.net/article/doi/10.1109/JAS.2017.7510532?pageType=en) | |
|Gated fusion network for single image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Ren_Gated_Fusion_Network_CVPR_2018_paper.html) | |
|Dehazegan: When image dehazing meets differential programming.<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://www.pengxi.me/wp-content/uploads/Papers/2018-IJCAI-DehazeGAN.pdf) | |
|Semi-supervised image dehazing<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8902220/) | |
|Instant dehazing of images using polarization<br><sub></sub> |  | 2001 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/990493/) | |
|Single image dehazing based on the physical model and MSRCR algorithm<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7984895/) | |
|Trident dehazing network<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Liu_Trident_Dehazing_Network_CVPRW_2020_paper.html) | |
|Review of dehazing techniques: challenges and future trends<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11042-023-17603-z) | |
|Investigating haze-relevant features in a learning framework for image dehazing<br><sub></sub> |  | 2014 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2014/html/Tang_Investigating_Haze-relevant_Features_2014_CVPR_paper.html) | |
|Single image dehazing using saturation line prior<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10141557/) | |
|EENet: An effective and efficient network for single image dehazing<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320324008252) | |
|Efficient image dehazing with boundary constraint and contextual regularization<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://www.cv-foundation.org/openaccess/content_iccv_2013/html/Meng_Efficient_Image_Dehazing_2013_ICCV_paper.html) | |
|Quality evaluation of image dehazing methods using synthetic hazy images<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8654007/) | |
|Single image dehazing via conditional generative adversarial network<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Li_Single_Image_Dehazing_CVPR_2018_paper.html) | |
|Initial results in underwater single image dehazing<br><sub></sub> |  | 2010 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5664428/) | |
|Frequency and spatial dual guidance for image dehazing<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-19800-7_11) | |
|End-to-end united video dehazing and detection<br><sub></sub> |  | 2018 | :video_camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/12287) | |
|Dehazing evaluation: Real-world benchmark datasets, criteria, and baselines<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9099036/) | |
|Single image dehazing using ranking convolutional neural network<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8100962/) | |
|Rethinking performance gains in image dehazing networks<br><sub></sub> |  | 2209 | :camera: |  | [Paper](https://arxiv.org/abs/2209.11448) | |
|Learning deep priors for image dehazing<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Learning_Deep_Priors_for_Image_Dehazing_ICCV_2019_paper.html) | |
|FAMED-Net: A fast and accurate multi-scale end-to-end dehazing network<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8753731/) | |
|A comparative study of image dehazing algorithms<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9138037/) | |
|Color image dehazing using the near-infrared<br><sub></sub> |  | 2009 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5413700/) | |
|Image dehazing using polarization effects of objects and airlight<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://opg.optica.org/abstract.cfm?uri=oe-22-16-19523) | |
|An iterative image dehazing method with polarization<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8471192/) | |
|Effective single image dehazing by fusion<br><sub></sub> |  | 2010 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5651263/) | |
|Perceptual evaluation of single image dehazing algorithms<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7351475/) | |
|Curricular contrastive regularization for physics-aware single image dehazing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Zheng_Curricular_Contrastive_Regularization_for_Physics-Aware_Single_Image_Dehazing_CVPR_2023_paper.html) | |
|Zero-shot image dehazing<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9170880/) | |
|Light-DehazeNet: a novel lightweight CNN architecture for single image dehazing<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9562276/) | |
|Image dehazing using residual-based deep CNN<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8355803/) | |
|A fast image dehazing algorithm using morphological reconstruction<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8568017/) | |
|Efficient single image dehazing and denoising: An efficient multi-scale correlated wavelet approach<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1077314217301431) | |
|A review on dark channel prior based image dehazing algorithms<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://link.springer.com/article/10.1186/s13640-016-0104-y) | |
|Physics-based feature dehazing networks<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-58577-8_12) | |
|Deep video dehazing with semantic segmentation<br><sub></sub> |  | 2018 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8492451/) | |
|Hazerd: an outdoor scene dataset and benchmark for single image dehazing<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8296874/) | |
|U-shaped vision mamba for single image dehazing<br><sub></sub> |  | 2402 | :camera: |  | [Paper](https://arxiv.org/abs/2402.04139) | |
|FFA-Net: Feature fusion attention network for single image dehazing<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/6865) | |
|O-haze: a dehazing benchmark with real hazy and haze-free outdoor images<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w13/html/Ancuti_O-HAZE_A_Dehazing_CVPR_2018_paper.html) | |
|Image dehazing transformer with transmission-aware 3d position embedding<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Guo_Image_Dehazing_Transformer_With_Transmission-Aware_3D_Position_Embedding_CVPR_2022_paper.html) | |
|Single image dehazing based on contrast enhancement<br><sub></sub> |  | 2011 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5946643/) | |
|RefineDNet: A weakly supervised refinement framework for single image dehazing<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9366772/) | |
|Underwater image enhancement by wavelength compensation and dehazing<br><sub></sub> |  | 2011 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6104148/) | |
|Knowledge transfer dehazing network for nonhomogeneous dehazing<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Wu_Knowledge_Transfer_Dehazing_Network_for_NonHomogeneous_Dehazing_CVPRW_2020_paper.html) | |
|Near-infrared guided color image dehazing<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6738487/) | |
|A review on intelligence dehazing and color restoration for underwater images<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8267119/) | |
|UCL-dehaze: Toward real-world image dehazing via unsupervised contrastive learning<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10431709/) | |
|Enhanced variational image dehazing<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://epubs.siam.org/doi/abs/10.1137/15M1008889) | |
|Optimized contrast enhancement for real-time image and video dehazing<br><sub></sub> |  | 2013 | :video_camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1047320313000242) | |
|Multi-scale boosted dehazing network with dense feature fusion<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Dong_Multi-Scale_Boosted_Dehazing_Network_With_Dense_Feature_Fusion_CVPR_2020_paper.html) | |
|Deep multi-model fusion for single-image dehazing<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Deng_Deep_Multi-Model_Fusion_for_Single-Image_Dehazing_ICCV_2019_paper.html) | |
|Image dehazing by artificial multiple-exposure image fusion<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0165168418301063) | |
|A survey of image dehazing approaches<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7162616/) | |
|Depth information assisted collaborative mutual promotion network for single image dehazing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Depth_Information_Assisted_Collaborative_Mutual_Promotion_Network_for_Single_Image_CVPR_2024_paper.html) | |
|IDGCP: Image dehazing based on gamma correction prior<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8931242/) | |
|You only look yourself: Unsupervised and untrained single image dehazing neural network<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-021-01431-5) | |
|Mixdehazenet: Mix structure block for image dehazing network<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10651326/) | |
|IDRLP: Image dehazing using region line prior<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9594664/) | |
|Night-time dehazing by fusion<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7532760/) | |
|Detection-friendly dehazing: Object detection in real-world hazy scenes<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10012056/) | |
|Self-guided image dehazing using progressive feature fusion<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9677961/) | |
|Ridcp: Revitalizing real image dehazing via high-quality codebook priors<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Wu_RIDCP_Revitalizing_Real_Image_Dehazing_via_High-Quality_Codebook_Priors_CVPR_2023_paper.html) | |
|On the duality between retinex and image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Galdran_On_the_Duality_CVPR_2018_paper.html) | |
|From synthetic to real: Image dehazing collaborating with unlabeled real data<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3474085.3475331) | |
|A comprehensive survey and taxonomy on single image dehazing based on deep learning<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3576918) | |
|Single image dehazing using color ellipsoid prior<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8101508/) | |
|A cascaded convolutional neural network for single image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8323372/) | |
|Single image dehazing through improved atmospheric light estimation<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11042-015-2977-7) | |
|Improved wavelet transform algorithm for single image dehazing<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0030402614002022) | |
|Uncertainty-driven dehazing network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/19973) | |
|Ultra-high-definition image dehazing via multi-guided bilateral learning<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9578433/) | |
|Multi-scale single image dehazing using perceptual pyramid deep network<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w13/html/Zhang_Multi-Scale_Single_Image_CVPR_2018_paper.html) | |
|Single image dehazing via multi-scale convolutional neural networks with holistic edges<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-019-01235-8) | |
|Single image dehazing using color attenuation prior.<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://www.bmva-archive.org.uk/bmvc/2014/files/paper111.pdf) | |
|Progressive feature fusion network for realistic image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-20887-5_13) | |
|Advancing real-world image dehazing: Perspective, modules, and training<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10564179/) | |
|Fusion-based variational image dehazing<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7792620/) | |
|Self-augmented unpaired image dehazing via density and depth decomposition<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Yang_Self-Augmented_Unpaired_Image_Dehazing_via_Density_and_Depth_Decomposition_CVPR_2022_paper.html) | |
|Image dehazing via enhancement, restoration, and fusion: A survey<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1566253522000641) | |
|Improved single image dehazing using geometry<br><sub></sub> |  | 2009 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5384980/) | |
|Fast image dehazing using guided joint bilateral filter<br><sub></sub> |  | 2012 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00371-012-0679-y) | |
|PDR-Net: Perception-inspired single image dehazing network with refinement<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8792133/) | |
|A novel fast single image dehazing algorithm based on artificial multiexposure image fusion<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9198924/) | |
|Multi-scale optimal fusion model for single image dehazing<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0923596518308804) | |
|Single image dehazing with a generic model-agnostic convolutional neural network<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8686264/) | |
|LIDN: a novel light invariant image dehazing network<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S095219762301014X) | |
|Proximal dehaze-net: A prior learning-based deep network for single image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ECCV_2018/html/Dong_Yang_Proximal_Dehaze-Net_A_ECCV_2018_paper.html) | |
|Single image dehazing using a multilayer perceptron<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/journals/Journal-of-Electronic-Imaging/volume-27/issue-4/043022/Single-image-dehazing-using-a-multilayer-perceptron/10.1117/1.JEI.27.4.043022.short) | |
|Gated context aggregation network for image dehazing and deraining<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8658661/) | |
|PSD: Principled synthetic-to-real dehazing guided by physical priors<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Chen_PSD_Principled_Synthetic-to-Real_Dehazing_Guided_by_Physical_Priors_CVPR_2021_paper.html) | |
|Blind dehazing using internal patch recurrence<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7492870/) | |
|Video dehazing with spatial and temporal coherence<br><sub></sub> |  | 2011 | :video_camera: |  | [Paper](https://link.springer.com/article/10.1007/s00371-011-0569-8) | |
|Single image dehazing using improved cycleGAN<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1047320320302248) | |
|Recent advances in image dehazing: Formal analysis to automated approaches<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1566253523004670) | |
|ICycleGAN: Single image dehazing based on iterative dehazing model and CycleGAN<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1077314220301521) | |
|Fast single image dehazing using saturation based transmission map estimation<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8882514/) | |
|Single image dehazing using a new color channel<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1047320320302212) | |
|Real-time dehazing for image and video<br><sub></sub> |  | 2010 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5693028/) | |
|AIPNet: Image-to-image single image dehazing with atmospheric illumination prior<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8454467/) | |
|I-HAZE: A dehazing benchmark with real hazy and haze-free indoor images<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-01449-0_52) | |
|AED-Net: A single image dehazing<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9684922/) | |
|NH-HAZE: An image dehazing benchmark with non-homogeneous hazy and haze-free images<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Ancuti_NH-HAZE_An_Image_Dehazing_Benchmark_With_Non-Homogeneous_Hazy_and_Haze-Free_CVPRW_2020_paper.html) | |
|Fast image dehazing using improved dark channel prior<br><sub></sub> |  | 2012 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6221729/) | |
|Fsad-net: feedback spatial attention dehazing network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9705517/) | |
|Towards domain invariant single image dehazing<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/17162) | |
|DEA-Net: Single image dehazing based on detail-enhanced convolution and content-guided attention<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10411857/) | |
|LKD-Net: Large kernel convolution network for single image dehazing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10219934/) | |
|Mb-taylorformer: Multi-branch efficient transformer expanded by taylor formula for image dehazing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Qiu_MB-TaylorFormer_Multi-Branch_Efficient_Transformer_Expanded_by_Taylor_Formula_for_Image_ICCV_2023_paper.html) | |
|IDE: Image dehazing and exposure using an enhanced atmospheric scattering model<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9332266/) | |
|A fast image dehazing algorithm based on negative correction<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0165168414000863) | |
|Single image dehazing with an independent detail-recovery network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705122007961) | |
|DRCDN: learning deep residual convolutional dehazing networks<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00371-019-01774-8) | |
|Single image dehazing with a physical model and dark channel prior<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231214010157) | |
|Distilling image dehazing with heterogeneous task imitation<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Hong_Distilling_Image_Dehazing_With_Heterogeneous_Task_Imitation_CVPR_2020_paper.html) | |
|Single image dehazing using deep neural networks<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0167865519302235) | |
|Multi-level feature interaction and efficient non-local information enhanced channel attention for image dehazing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S089360802300134X) | |
|Unsupervised multi-branch network with high-frequency enhancement for image dehazing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320324005144) | |
|Dehazing for images with large sky region<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231217302412) | |
|Single image dehazing using the change of detail prior<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231215000478) | |
|Color channel transfer for image dehazing<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8790649/) | |
|Progressive negative enhancing contrastive learning for image dehazing and beyond<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10480609/) | |
|Delving deeper into image dehazing: A survey<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10325493/) | |
|Pyramid global context network for image dehazing<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9252912/) | |
|QCNN-H: Single-image dehazing using quaternion neural networks<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10040717/) | |
|Day and night-time dehazing by local airlight estimation<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9076820/) | |
|Dense-haze: A benchmark for image dehazing with dense-haze and haze-free images<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8803046/) | |
|Dehazing for multispectral remote sensing images based on a convolutional neural network with the residual architecture<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8325417/) | |
|Single image dehazing using CNN<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1877050919302194) | |
|Generative adversarial and self-supervised dehazing network<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10284536/) | |
|IDeRs: Iterative dehazing method for single remote sensing image<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0020025519301732) | |
|Dual-scale single image dehazing via neural augmentation<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9901449/) | |
|Single image dehazing via NIN-DehazeNet<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8930499/) | |
|A database with reference for image dehazing evaluation<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://jbthomas.org/Journals/2018aJIST.pdf) | |
|USID-Net: Unsupervised single image dehazing network via disentangled representations<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9745359/) | |
|A novel bi-stream network for image dehazing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197624010911) | |
|Underwater image dehazing using joint trilateral filter<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0045790613002644) | |
|Deep retinex network for single image dehazing<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9274531/) | |
|A comprehensive survey on image dehazing for different atmospheric scattering models<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11042-023-17292-8) | |
|Nighttime dehazing with a synthetic benchmark<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413763) | |
|Joint transmission map estimation and dehazing using deep networks<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8695091/) | |
|High-quality image dehazing with diffusion model<br><sub></sub> |  | 2308 | :camera: |  | [Paper](https://arxiv.org/abs/2308.11949) | |
|Trinity-net: Gradient-guided swin transformer-based remote sensing image dehazing and beyond<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10149032/) | |
|Improved single image dehazing using segmentation<br><sub></sub> |  | 2010 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5651964/) | |
|Image dehazing using deep learning techniques<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1877050920308796) | |
|Deep learning based single image dehazing<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2018_workshops/w21/html/Suarez_Deep_Learning_Based_CVPR_2018_paper.html) | |
|Towards compact single image dehazing via task-related contrastive network<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417423016329) | |
|A region-wised medium transmission based image dehazing method<br><sub></sub> |  | 2017 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7835739/) | |
|Deep hybrid model for single image dehazing and detail refinement<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320322007063) | |
|Multi-scale single image dehazing using Laplacian and Gaussian pyramids<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9606591/) | |
|PhDnet: A novel physic-aware dehazing network for remote sensing images<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1566253524000551) | |
|Frequency compensated diffusion model for real-scene dehazing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608024002053) | |
|Image dehazing by an artificial image fusion method based on adaptive structure decomposition<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9040575/) | |
|DENSE123'COLOR Enhancement Dehazing Network<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPRW_2019/html/NTIRE/Guo_Dense_123_Color_Enhancement_Dehazing_Network_CVPRW_2019_paper.html) | |
|Unsupervised single image dehazing using dark channel prior loss<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8897130/) | |
</details>

## :cloud_with_rain: Rain removal / Deraining / De-raining

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Data | Metohd | Link | Code |
|-------|-------|------|------|--------|------|------|
|Progressive image deraining networks: A better and simpler baseline<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Ren_Progressive_Image_Deraining_Networks_A_Better_and_Simpler_Baseline_CVPR_2019_paper.html) | |
|Single image deraining: From model-based to data-driven and beyond<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9096521/) | |
|Data-driven single image deraining: A comprehensive review and new perspectives<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320323004387) | |
|Single image deraining: A comprehensive benchmark analysis<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_Single_Image_Deraining_A_Comprehensive_Benchmark_Analysis_CVPR_2019_paper.html) | |
|Multi-scale progressive fusion network for single image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Jiang_Multi-Scale_Progressive_Fusion_Network_for_Single_Image_Deraining_CVPR_2020_paper.html) | |
|Learning a sparse transformer network for effective image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Chen_Learning_a_Sparse_Transformer_Network_for_Effective_Image_Deraining_CVPR_2023_paper.html) | |
|Towards unified deep image deraining: A survey and a new benchmark<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10945649/) | |
|Residual-guide network for single image deraining<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3240508.3240694) | |
|Detail-recovery image deraining via context aggregation networks<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Deng_Detail-recovery_Image_Deraining_via_Context_Aggregation_Networks_CVPR_2020_paper.html) | |
|Spatial attentive single-image deraining with a high quality real rain dataset<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Spatial_Attentive_Single-Image_Deraining_With_a_High_Quality_Real_Rain_CVPR_2019_paper.html) | |
|Conditional variational image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9084254/) | |
|Lightweight pyramid networks for image deraining<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8767931/) | |
|Single image deraining using bilateral recurrent network<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9096546/) | |
|Variational image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_WACV_2020/html/Du_Variational_Image_Deraining_WACV_2020_paper.html) | |
|Freqmamba: Viewing mamba from a frequency perspective for image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680862) | |
|Syn2real transfer learning for image deraining using gaussian processes<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Yasarla_Syn2Real_Transfer_Learning_for_Image_Deraining_Using_Gaussian_Processes_CVPR_2020_paper.html) | |
|A comprehensive benchmark analysis of single image deraining: Current challenges and future perspectives<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-020-01416-w) | |
|Multi-scale fusion and decomposition network for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10348527/) | |
|Robust representation learning with feedback for single image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Chen_Robust_Representation_Learning_With_Feedback_for_Single_Image_Deraining_CVPR_2021_paper.html) | |
|Video desnowing and deraining based on matrix decomposition<br><sub></sub> |  | 2017 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2017/html/Ren_Video_Desnowing_and_CVPR_2017_paper.html) | |
|Smartassign: Learning a smart knowledge assignment strategy for deraining and desnowing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Wang_SmartAssign_Learning_a_Smart_Knowledge_Assignment_Strategy_for_Deraining_and_CVPR_2023_paper.html) | |
|Unpaired deep image deraining using dual contrastive learning<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Chen_Unpaired_Deep_Image_Deraining_Using_Dual_Contrastive_Learning_CVPR_2022_paper.html) | |
|Semi-deraingan: A new semi-supervised single image deraining network<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://arxiv.org/abs/2001.08388) | |
|Beyond monocular deraining: Stereo image deraining via semantic understanding<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-58583-9_5) | |
|Rethinking multi-scale representations in deep deraining transformer<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27865) | |
|Gated context aggregation network for image dehazing and deraining<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8658661/) | |
|Recurrent squeeze-and-excitation context aggregation net for single image deraining<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ECCV_2018/html/Xia_Li_Recurrent_Squeeze-and-Excitation_Context_ECCV_2018_paper.html) | |
|Multi-scale hybrid fusion network for single image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9547423/) | |
|Efficientderain: Learning pixel-wise dilation filtering for high-efficiency single-image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16239) | |
|Beyond monocular deraining: Parallel stereo deraining network via semantic prior<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-022-01620-w) | |
|Etdnet: An efficient transformer deraining model<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9524626/) | |
|Unsupervised deraining: Where contrastive learning meets self-similarity<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Ye_Unsupervised_Deraining_Where_Contrastive_Learning_Meets_Self-Similarity_CVPR_2022_paper.html) | |
|Deraincyclegan: Rain attentive cyclegan for single image deraining and rainmaking<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9420312/) | |
|Unsupervised single image deraining with self-supervised constraints<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8803238/) | |
|Memory oriented transfer learning for semi-supervised image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Huang_Memory_Oriented_Transfer_Learning_for_Semi-Supervised_Image_Deraining_CVPR_2021_paper.html?ref=https://githubhelp.com) | |
|Rethinking image deraining via rain streaks and vapors<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-58520-4_22) | |
|Dreaming to prune image deraining networks<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Zou_Dreaming_To_Prune_Image_Deraining_Networks_CVPR_2022_paper.html) | |
|FMRNet: Image deraining via frequency mutual revision<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29186) | |
|Hybrid cnn-transformer feature fusion for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25111) | |
|Residual multiscale based single image deraining<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://openresearch-repository.anu.edu.au/items/64b4c572-3f33-40b6-86f8-92bf5eb112f3) | |
|Sginet: Toward sufficient interaction between single image deraining and semantic segmentation<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548241) | |
|Drt: A lightweight single image deraining recursive transformer<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Liang_DRT_A_Lightweight_Single_Image_Deraining_Recursive_Transformer_CVPRW_2022_paper.html) | |
|Not just streaks: Towards ground truth for single image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-20071-7_42) | |
|Networks are slacking off: Understanding generalization problem in image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5aca18e0192b2c1300479e5b700c76a9-Abstract-Conference.html) | |
|Semi-supervised image deraining using knowledge distillation<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9829841/) | |
|Continual image deraining with hypergraph convolutional networks<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10035447/) | |
|Bidirectional multi-scale implicit neural representations for image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2024/html/Chen_Bidirectional_Multi-Scale_Implicit_Neural_Representations_for_Image_Deraining_CVPR_2024_paper.html) | |
|Memory uncertainty learning for real-world single image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9789487/) | |
|Single-image deraining using an adaptive nonlocal means filter<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6738189/) | |
|A two-stage density-aware single image deraining method<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9499966/) | |
|Single image deraining via recurrent hierarchy enhancement network<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3343031.3351149) | |
|A coarse-to-fine multi-stream hybrid deraining network for single image deraining<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8970838/) | |
|Frame-consistent recurrent video deraining with dual-level flow<br><sub></sub> |  | 2019 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Yang_Frame-Consistent_Recurrent_Video_Deraining_With_Dual-Level_Flow_CVPR_2019_paper.html) | |
|Rain-free and residue hand-in-hand: A progressive coupled network for real-time image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9515582/) | |
|Danet: Image deraining via dynamic association learning.<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://scholar.archive.org/work/sbvhut3ebzhfzkapgn2kf5hokm/access/wayback/https://www.ijcai.org/proceedings/2022/0137.pdf) | |
|Efficient frequency-domain image deraining with contrastive regularization<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72940-9_14) | |
|Learning a spiking neural network for efficient image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://arxiv.org/abs/2405.06277) | |
|Towards ultra-high-definition image deraining: A benchmark and an efficient method<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://arxiv.org/abs/2405.17074) | |
|Physical model guided deep image deraining<br><sub></sub> |  | 2003 | :camera: |  | [Paper](https://arxiv.org/pdf/2003.13242) | |
|Toward real-world single image deraining: A new benchmark and beyond<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://arxiv.org/abs/2206.05514) | |
|PFDN: Pyramid feature decoupling network for single image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9942954/) | |
|Decomposition makes better rain removal: An improved attention-guided deraining network<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9294056/) | |
|A hybrid transformer-mamba network for single image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://arxiv.org/abs/2409.00410) | |
|A comprehensive survey: Image deraining and stereo‐matching task‐driven performance analysis<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/ipr2.12347) | |
|Semi-supervised image deraining using gaussian processes<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9489290/) | |
|Multi-decoding deraining network and quasi-sparsity based training<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Wang_Multi-Decoding_Deraining_Network_and_Quasi-Sparsity_Based_Training_CVPR_2021_paper.html) | |
|Learning rain location prior for nighttime deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Zhang_Learning_Rain_Location_Prior_for_Nighttime_Deraining_ICCV_2023_paper.html) | |
|DECTNet: A detail enhanced CNN-Transformer network for single-image deraining<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S2667241325000011) | |
|Single-image deraining via recurrent residual multiscale networks<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9311197/) | |
|Rainmamba: Enhanced locality learning with state space models for video deraining<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680916) | |
|Unpaired learning for deep image deraining with rain direction regularizer<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2021/html/Liu_Unpaired_Learning_for_Deep_Image_Deraining_With_Rain_Direction_Regularizer_ICCV_2021_paper.html) | |
|Progressive network based on detail scaling and texture extraction: A more general framework for image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S092523122301189X) | |
|SDNet: mutil-branch for single image deraining using swin<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://arxiv.org/abs/2105.15077) | |
|Fouriermamba: Fourier learning integration with state space models for image deraining<br><sub></sub> |  | 2405 | :camera: |  | [Paper](https://arxiv.org/abs/2405.19450) | |
|Mffdnet: Single image deraining via dual-channel mixed feature fusion<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10379038/) | |
|Structure-preserving deraining with residue channel prior guidance<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2021/html/Yi_Structure-Preserving_Deraining_With_Residue_Channel_Prior_Guidance_ICCV_2021_paper.html) | |
|Magic ELF: Image deraining meets association learning and transformer<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://arxiv.org/abs/2207.10455) | |
|Scale-free single image deraining via visibility-enhanced recurrent wavelet learning<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8610325/) | |
|Single image deraining using scale-aware multi-stage recurrent network<br><sub></sub> |  | 1712 | :camera: |  | [Paper](https://arxiv.org/abs/1712.06830) | |
|Intensity-aware single-image deraining with semantic and color regularization<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9565368/) | |
|Dilated convolutional transformer for high-quality image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2023W/UG2/html/Li_Dilated_Convolutional_Transformer_for_High-Quality_Image_Deraining_CVPRW_2023_paper.html) | |
|Wavelet approximation-aware residual network for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10227544/) | |
|Semi-supervised video deraining with dynamical rain generator<br><sub></sub> |  | 2021 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Yue_Semi-Supervised_Video_Deraining_With_Dynamical_Rain_Generator_CVPR_2021_paper.html) | |
|Exploring overcomplete representations for single image deraining using cnns<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9264746/) | |
|Fastderainnet: A deep learning algorithm for single image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9139246/) | |
|DPNet: Detail-preserving image deraining via learning frequency domain knowledge<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1051200422003578) | |
|Image deraining via invertible disentangled representations<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197624013654) | |
|Deep scale-space mining network for single image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022W/UG2/html/Li_Deep_Scale-Space_Mining_Network_for_Single_Image_Deraining_CVPRW_2022_paper.html) | |
|Nasnet: A neuron attention stage-by-stage net for single image deraining<br><sub></sub> |  | 1912 | :camera: |  | [Paper](https://www.researchgate.net/profile/Xu-Qin-12/publication/337830328_NASNet_A_Neuron_Attention_Stage-by-Stage_Net_for_Single_Image_Deraining/links/5e193ee3299bf10bc3a34e94/NASNet-A-Neuron-Attention-Stage-by-Stage-Net-for-Single-Image-Deraining.pdf) | |
|Unsupervised image deraining: Optimization model driven deep cnn<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3474085.3475441) | |
|Residual-guide feature fusion network for single image deraining<br><sub></sub> |  | 1804 | :camera: |  | [Paper](https://arxiv.org/abs/1804.07493) | |
|Semi-swinderain: Semi-supervised image deraining network using swin transformer<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10095214/) | |
|Unsupervised video deraining with an event camera<br><sub></sub> |  | 2023 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Wang_Unsupervised_Video_Deraining_with_An_Event_Camera_ICCV_2023_paper.html) | |
|DerainGAN: Single image deraining using wasserstein GAN<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11042-021-11442-6) | |
|Enhanced spatio-temporal interaction learning for video deraining: faster and better<br><sub></sub> |  | 2022 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9706330/) | |
|Recurrent multi-frame deraining: Combining physics guidance and adversarial learning<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9439949/) | |
|Context-enhanced representation learning for single image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-020-01425-9) | |
|Single image deraining using time-lapse data<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9115884/) | |
|Utilizing two-phase processing with FBLS for single image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9069421/) | |
|SAPNet: Segmentation-aware progressive network for perceptual contrastive deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/WACV2022W/VAQ/html/Zheng_SAPNet_Segmentation-Aware_Progressive_Network_for_Perceptual_Contrastive_Deraining_WACVW_2022_paper.html) | |
|Dawn: Direction-aware attention wavelet network for image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3611697) | |
|Selective wavelet attention learning for single image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-020-01421-z) | |
|DSDNet: Toward single image deraining with self-paced curricular dual stimulations<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1077314223000371) | |
|Dual heterogeneous complementary networks for single image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Nanba_Dual_Heterogeneous_Complementary_Networks_for_Single_Image_Deraining_CVPRW_2022_paper.html) | |
|Single image deraining with continuous rain density estimation<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9613794/) | |
|Video deraining and desnowing using temporal correlation and low-rank matrix completion<br><sub></sub> |  | 2015 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7101234/) | |
|Image deraining with frequency-enhanced state space model<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/ACCV2024/html/Yamashita_Image_Deraining_with_Frequency-Enhanced_State_Space_Model_ACCV_2024_paper.html) | |
|DRD-Net: Detail-recovery image deraining via context aggregation networks<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://arxiv.org/abs/1908.10267) | |
|Context-detail-aware united network for single image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3639407) | |
|Online-updated high-order collaborative networks for single image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20140) | |
|An end-to-end cascaded image deraining and object detection neural network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9833233/) | |
|RCDNet: An interpretable rain convolutional dictionary network for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10012418/) | |
|A two-stage network with wavelet transformation for single-image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00371-022-02533-y) | |
|Explore internal and external similarity for single image deraining with graph neural networks<br><sub></sub> |  | 2406 | :camera: |  | [Paper](https://arxiv.org/abs/2406.00721) | |
|Single image deraining network with rain embedding consistency and layered LSTM<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/WACV2022/html/Li_Single_Image_Deraining_Network_With_Rain_Embedding_Consistency_and_Layered_WACV_2022_paper.html) | |
|Image Deraining via Self-supervised Reinforcement Learning<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://arxiv.org/abs/2403.18270) | |
|Joint self-attention and scale-aggregation for self-calibrated deraining network<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413559) | |
|A novel dual-stage progressive enhancement network for single image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197623015956) | |
|Deep single image deraining via modeling haze-like effect<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9154545/) | |
|Adaptive Frequency Enhancement Network for Single Image Deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10831025/) | |
|Single image deraining using a recurrent multi-scale aggregation and enhancement network<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8784948/) | |
|Single traffic image deraining via similarity-diversity model<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10359459/) | |
|Real‐World Image Deraining Using Model‐Free Unsupervised Learning<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://onlinelibrary.wiley.com/doi/abs/10.1155/2024/7454928) | |
|RainFormer: a pyramid transformer for single image deraining.<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://search.ebscohost.com/login.aspx?direct=true&profile=ehost&scope=site&authtype=crawler&jrnl=09208542&AN=162205336&h=1el%2Fxz34bABHhJCs0nyW%2BTKdU98iqVV%2BmFP6YmAv3tvx6xZC%2BZv1LvHhzg3Qa6PNY14kMxsBkEDBJXxgJIstEQ%3D%3D&crl=c) | |
|Wavelet channel attention module with a fusion network for single image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9190720/) | |
|Nightrain: Nighttime video deraining via adaptive-rain-removal and adaptive-correction<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28124) | |
|Event-aware video deraining via multi-patch progressive learning<br><sub></sub> |  | 2023 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10122854/) | |
|Cross-domain collaborative learning for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S095741742201661X) | |
|Unrolling a rain-guided detail recovery network for singleimage deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S209657962200047X) | |
|Exploring Local Sparse Structure Prior for Image Deraining and Desnowing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10812906/) | |
|Cycle contrastive adversarial learning with structural consistency for unsupervised high-quality image deraining transformer<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608024003526) | |
|Single image deraining using scale constraint iterative update network<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417423018419) | |
|Recurrent wavelet structure-preserving residual network for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320322007737) | |
|Pixel-wise content attention learning for single-image deraining of autonomous vehicles<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S095741742300492X) | |
|Dual recursive network for fast image deraining<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8803308/) | |
|Unsupervised deraining: Where asymmetric contrastive learning meets self-similarity<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10269093/) | |
|Recovering a clean background: A parallel deep network architecture for single-image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0167865524000060) | |
|Event-driven heterogeneous network for video deraining<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-024-02148-x) | |
|Meta-learning based relation and representation learning networks for single-image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320321003113) | |
|Contrastive unfolding deraining network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9894377/) | |
|Rain2Avoid: Learning Deraining by Self-Supervision<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10891564/) | |
|Self-aligned video deraining with transmission-depth consistency<br><sub></sub> |  | 2021 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Yan_Self-Aligned_Video_Deraining_With_Transmission-Depth_Consistency_CVPR_2021_paper.html) | |
|Progressive subtractive recurrent lightweight network for video deraining<br><sub></sub> |  | 2021 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9645369/) | |
|Close the loop: A unified bottom-up and top-down paradigm for joint image deraining and segmentation<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20033) | |
|Image deraining transformer with sparsity and frequency guidance<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10219850/) | |
|Image de-raining using a conditional generative adversarial network<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8727938/) | |
|Single-image deraining via a recurrent memory unit network<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705121000952) | |
|UC-former: A multi-scale image deraining network using enhanced transformer<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1077314224001784) | |
|Image de-raining transformer<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9798773/) | |
|Ultra-Fast Deraining Plugin for Vision-Based Perception of Autonomous Driving<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10786924/) | |
|Ensemble single image deraining network via progressive structural boosting constraints<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0923596521002204) | |
|Hpcnet: A hybrid progressive coupled network for image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10219881/) | |
|Synthesized rain images for deraining algorithms<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231222004040) | |
|Model-based deep network for single image deraining<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8955865/) | |
|Local and global knowledge distillation with direction-enhanced contrastive learning for single-image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705123002307) | |
|EfficientDeRain+: Learning Uncertainty-Aware Filtering via RainMix Augmentation for High-Efficiency Deraining<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-024-02281-7) | |
|FoNet: Focused network for single image deraining<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00034-025-03009-9) | |
|Distributed feedback network for single-image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0020025521002371) | |
|High-level task-driven single image deraining: Segmentation in rainy days<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-63830-6_30) | |
|From coarse to fine: A stage-wise deraining net<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8735735/) | |
|Pearl: Preprocessing enhanced adversarial robust learning of image deraining for semantic segmentation<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612164) | |
|Triple-level model inferred collaborative network architecture for video deraining<br><sub></sub> |  | 2021 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9628137/) | |
|Neural Schrödinger bridge for unpaired real-world image deraining<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0020025524011137) | |
|Aggregating global and local representations via hybrid transformer for video deraining<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10458690/) | |
|Single image deraining via deep shared pyramid network<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00371-020-01944-z) | |
|A convolutional network for joint deraining and dehazing from a single image for autonomous driving in rain<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8967644/) | |
|Alternating attention transformer for single image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1051200423002397) | |
|Rethinking image deraining via text-guided detail reconstruction<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10688071/) | |
|Deep image deraining<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10378907/) | |
|GKC-Net: gated KAN with Channel-Position attention mechanism for image deraining<br><sub></sub> |  | 2026 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S003132032500740X) | |
|Rethinking video rain streak removal: A new synthesis model and a deraining network with video rain prior<br><sub></sub> |  | 2022 | :video_camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-19800-7_33) | |
|A framework of single-image deraining method based on analysis of rain characteristics<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7533128/) | |
|Single image deraining via decorrelating the rain streaks and background scene in gradient domain<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320318300700) | |
|Pixel Adaptive Deep Unfolding Network with State Space Model for Image Deraining<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608025007257) | |
|Image deraining algorithm based on multi-scale features<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.mdpi.com/2076-3417/14/13/5548) | |
|Multi-scale hourglass hierarchical fusion network for single image deraining<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021W/UG2/html/Chen_Multi-Scale_Hourglass_Hierarchical_Fusion_Network_for_Single_Image_Deraining_CVPRW_2021_paper.html) | |
|A single image deraining algorithm guided by text generation based on depth information conditions<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1568494625008178) | |
|Tpsence: Towards artifact-free realistic rain generation for deraining and object detection in rain<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Zheng_TPSeNCE_Towards_Artifact-Free_Realistic_Rain_Generation_for_Deraining_and_Object_WACV_2024_paper.html) | |
|Fluid: Few-shot self-supervised image deraining<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/WACV2022/html/Nandan_FLUID_Few-Shot_Self-Supervised_Image_Deraining_WACV_2022_paper.html) | |
|Unpaired photo-realistic image deraining with energy-informed diffusion model<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680560) | |
</details>

### :umbrella: Rain Streak Removal

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Data | Link | Code |
|-------|-------|------|------|------|------|
</details>

### :droplet: Raindrop Removal

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Data | Method | Link | Code |
|-------|-------|------|------|--------|------|------|
|Attentive generative adversarial network for raindrop removal from a single image<br><sub></sub> |  | 2018 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Qian_Attentive_Generative_Adversarial_CVPR_2018_paper.html) | |
|Learning from synthetic photorealistic raindrop for single image raindrop removal<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/PBDL/Hao_Learning_From_Synthetic_Photorealistic_Raindrop_for_Single_Image_Raindrop_Removal_ICCVW_2019_paper.html) | |
|Adherent raindrop modeling, detection and removal in video<br><sub></sub> |  | 2015 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7299675/) | |
|Raindrop clarity: A dual-focused dataset for day and night raindrop removal<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72658-3_1) | |
|Raingan: Unsupervised raindrop removal via decomposition and composition<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/WACV2022W/VAQ/html/Yan_RainGAN_Unsupervised_Raindrop_Removal_via_Decomposition_and_Composition_WACVW_2022_paper.html) | |
|Dual attention-in-attention model for joint rain streak and raindrop removal<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9527103/) | |
|Adherent raindrop detection and removal in video<br><sub></sub> |  | 2013 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2013/html/You_Adherent_Raindrop_Detection_2013_CVPR_paper.html) | |
|Feature-aligned video raindrop removal with temporal constraints<br><sub></sub> |  | 2022 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9769883/) | |
|Dual-pixel raindrop removal<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10636073/) | |
|Uncertainty guided multi-scale attention network for raindrop removal from a single image<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9423583/) | |
|Removing raindrops and rain streaks in one go<br><sub></sub> |  | 2021 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2021/html/Quan_Removing_Raindrops_and_Rain_Streaks_in_One_Go_CVPR_2021_paper.html) | |
|STRRNet: Semantics-guided two-stage raindrop removal network<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2025W/NTIRE/html/Rong_STRRNet_Semantics-guided_Two-stage_Raindrop_Removal_Network_CVPRW_2025_paper.html) | |
|Uav-rain1k: A benchmark for raindrop removal from uav aerial imagery<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2024W/UG2/html/Chang_UAV-Rain1k_A_Benchmark_for_Raindrop_Removal_from_UAV_Aerial_Imagery_CVPRW_2024_paper.html) | |
|Raindrop detection and removal from long range trajectories<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-16808-1_38) | |
|Raindrop detection and removal using salient visual features<br><sub></sub> |  | 2012 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6467016/) | |
|UnfairGAN: An enhanced generative adversarial network for raindrop removal from a single image<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417422013811) | |
|Context and detail interaction network for stereo rain streak and raindrop removal<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608023003702) | |
|Joint raindrop and haze removal from a single image<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9222513/) | |
|NTIRE 2025 challenge on day and night raindrop removal for dual-focused images: Methods and results<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2025W/NTIRE/html/Li_NTIRE_2025_Challenge_on_Day_and_Night_Raindrop_Removal_for_CVPRW_2025_paper.html) | |
|Selective generative adversarial network for raindrop removal from a single image<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231220315861) | |
|Weakly supervised learning for raindrop removal on a single image<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9157928/) | |
|A review of detection and removal of raindrops in automotive vision systems<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.mdpi.com/2313-433X/7/3/52) | |
|Adherent raindrop removal with self-supervised attention maps and spatio-temporal generative adversarial networks<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/ADW/Alletto_Adherent_Raindrop_Removal_with_Self-Supervised_Attention_Maps_and_Spatio-Temporal_Generative_ICCVW_2019_paper.html) | |
|Mask-guided progressive network for joint raindrop and rain streak removal in videos<br><sub></sub> |  | 2023 | :video_camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612001) | |
|Raindrop-removal image translation using target-mask network with attention module<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.mdpi.com/2227-7390/11/15/3318) | |
|Raindrop removal with light field image using image inpainting<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9040628/) | |
|Laplacian encoder-decoder network for raindrop removal<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0167865522001143) | |
|Review on raindrop detection and removal in weather degraded images<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6588763/) | |
|Raindrop removal from a single image using a two-step generative adversarial network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11760-021-02007-z) | |
|Removal of rain in video based on motion and shape characteristics of raindrops<br><sub></sub> |  | 2014 | :video_camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0030402614003362) | |
|Adherent mist and raindrop removal from a single image using attentive convolutional network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231222008918) | |
|Unsupervised Network for Single Image Raindrop Removal<br><sub></sub> |  | 2412 | :camera: |  | [Paper](https://arxiv.org/abs/2412.03019) | |
|Robust attention deraining network for synchronous rain streaks and raindrops removal<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3547932) | |
|Removing raindrops from a single image using synthetic data<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9412888/) | |
|A2Net: Adjacent Aggregation Networks for Image Raindrop Removal<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9045941/) | |
|Detection and removal of rain from videos<br><sub></sub> |  | 2004 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/1315077/) | |
|A survey of single image rain removal based on deep learning<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3625818) | |
|Single-image raindrop removal using concurrent channel-spatial attention and long-short skip connections<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0167865519303757) | |
|Rain drop detection and removal using k-means clustering<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7435707/) | |
|Improved sea-ice identification using semantic segmentation with raindrop removal<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9709781/) | |
|All in one bad weather removal using architectural search<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_All_in_One_Bad_Weather_Removal_Using_Architectural_Search_CVPR_2020_paper.html) | |
|Detection and removal of raindrop from images using deeplearning<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-37218-7_142) | |
|Raindrop Removal for In-Vehicle Camera Images with Generative Adversarial Network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9945304/) | |
|Iterative contrastive learning for single image raindrop removal<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9897979/) | |
|Removal of rain from videos: a review<br><sub></sub> |  | 2014 | :video_camera: |  | [Paper](https://link.springer.com/article/10.1007/s11760-012-0373-6) | |
|Image raindrop removal method for generative adversarial network based on difference learning<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://iopscience.iop.org/article/10.1088/1742-6596/1544/1/012099/meta) | |
|Single Image Raindrop Removal Using a Non-Local Operator and Feature Maps in the Frequency Domain<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9869812/) | |
|Deep learning for seeing through window with raindrops<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Quan_Deep_Learning_for_Seeing_Through_Window_With_Raindrops_ICCV_2019_paper.html) | |
|Raindrop Removal using Image Inpainting<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10220866/) | |
|Mutual channel prior guided dual-domain interaction network for single image raindrop removal<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0097849323000432) | |
|Recovering raindrop removal images under heavy rain.<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://www.scitepress.org/Papers/2020/93256/93256.pdf) | |
|X-net for single image raindrop removal<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9191073/) | |
|Removing rain and snow in a single image using guided filter<br><sub></sub> |  | 2012 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6272780/) | |
|Not All Areas Are Equal: A Novel Separation‐Restoration‐Fusion Network for Image Raindrop Removal<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14162) | |
|RIADNet: single image deraining network for raindrops and rain streaks removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s10994-025-06854-6) | |
|An Image Raindrop Removal Method Based on Squeeze-Excitation and Residual Fusion<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10545865/) | |
|A dual CNN architecture for single image raindrop and rain streak removal<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9993091/) | |
|Raindrop‐impact‐induced erosion processes and prediction: a review<br><sub></sub> |  | 2005 | :camera: |  | [Paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/hyp.5788) | |
|Cycle-spinning gan for raindrop removal from images<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8909824/) | |
|Application research on improved CGAN in image raindrop removal<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/joe.2019.1092) | |

</details>

## :snowflake: Snow Removal / Desnowing / De-snowing

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Data | Method | Link | Code |
|-------|-------|------|------|--------|------|------|
|All snow removed: Single image desnowing algorithm using hierarchical dual-tree complex wavelet representation and contradict channel loss<br><sub></sub> |  | 2021 | :camera: | | | [Paper](http://openaccess.thecvf.com/content/ICCV2021/html/Chen_ALL_Snow_Removed_Single_Image_Desnowing_Algorithm_Using_Hierarchical_Dual-Tree_ICCV_2021_paper.html) | |
|Smartassign: Learning a smart knowledge assignment strategy for deraining and desnowing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Wang_SmartAssign_Learning_a_Smart_Knowledge_Assignment_Strategy_for_Deraining_and_CVPR_2023_paper.html) | |
|Video desnowing and deraining based on matrix decomposition<br><sub></sub> |  | 2017 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content_cvpr_2017/html/Ren_Video_Desnowing_and_CVPR_2017_paper.html) | |
|A scalable and accurate de-snowing algorithm for LiDAR point clouds in winter<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.mdpi.com/2072-4292/14/6/1468) | |
|Hcsd-net: Single image desnowing with color space transformation<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3613789) | |
|Image desnowing via deep invertible separation<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10004991/) | |
|Towards efficient single image dehazing and desnowing<br><sub></sub> |  | 2204 | :camera: |  | [Paper](https://arxiv.org/abs/2204.08899) | |
|Deep unfolding network for image desnowing with snow shape prior<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10830558/) | |
|Enabling renewable energy technologies in harsh climates with ultra‐efficient electro‐thermal desnowing, defrosting, and deicing<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://advanced.onlinelibrary.wiley.com/doi/abs/10.1002/adfm.202201521) | |
|Semi-supervised video desnowing network via temporal decoupling experts and distribution-driven contrastive regularization<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72684-2_5) | |
|SnowFormer: Context interaction transformer with scale-awareness for single image desnowing<br><sub></sub> |  | 2208 | :camera: |  | [Paper](https://arxiv.org/abs/2208.09703) | |
|Video deraining and desnowing using temporal correlation and low-rank matrix completion<br><sub></sub> |  | 2015 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7101234/) | |
|Enhancing outdoor vision: Binocular desnowing with dual-stream temporal transformer<br><sub></sub> |  | 2026 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320325007356) | |
|De-snowing LiDAR point clouds with intensity and spatial-temporal features<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9812241/) | |
|De-snowing algorithm for long-wavelength LiDAR<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10588657/) | |
|Fast and accurate desnowing algorithm for LiDAR point clouds<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9180326/) | |
|LiDAR De-Snow Score (DSS): combining quality and perception metrics for optimised de-noising<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/11008847/) | |
|Towards real-time high-definition image snow removal: Efficient pyramid network with asymmetrical encoder-decoder architecture<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/ACCV2022/html/Ye_Towards_Real-time_High-Definition_Image_Snow_Removal_Efficient_Pyramid_Network_with_ACCV_2022_paper.html) | |
|Dual gradient based snow attentive desnowing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10070780/) | |
|An efficient video desnowing and deraining method with a novel variant dataset<br><sub></sub> |  | 2021 | :video_camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87156-7_16) | |
|Simultaneous snow mask prediction and single image desnowing with a bidirectional attention transformer network<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-981-97-8685-5_21) | |
|LiDAR de-snowing method with density and intensity fusion<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-981-97-1103-1_27) | |
|An integrated multi-scale context-aware network for efficient desnowing<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197625007699) | |
|Event-Based De-Snowing for Autonomous Driving<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://arxiv.org/abs/2507.20901) | |
|Video Desnower: An Adaptive Feature Fusion Understanding Video Desnowing Model With Deformable Convolution and KNN Point Cloud Transformer<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10606460/) | |
|Msp-former: Multi-scale projection transformer for single image desnowing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10095605/) | |
|Lightweight image de-snowing: A better trade-off between network capacity and performance<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608023003404) | |
|SnowMaster: Comprehensive Real-world Image Desnowing via MLLM with Multi-Model Feedback Optimization<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Lai_SnowMaster_Comprehensive_Real-world_Image_Desnowing_via_MLLM_with_Multi-Model_Feedback_CVPR_2025_paper.html) | |
|Optimized connections and feature interactions for more efficient single-image desnowing<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1568494625004648) | |
|Context-aware coarse-to-fine network for single image desnowing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11042-023-17674-y) | |
|Two-Stage Nighttime Desnowing Diffusion Model Based on Pseudo-Scenario Reconstruction<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10779380/) | |
|Video desnowing and deraining via saliency and dual adaptive spatiotemporal filtering<br><sub></sub> |  | 2021 | :video_camera: |  | [Paper](https://www.mdpi.com/1424-8220/21/22/7610) | |
|Uncertainty-driven dynamic degradation perceiving and background modeling for efficient single image desnowing<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612003) | |
|Exploring Local Sparse Structure Prior for Image Deraining and Desnowing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10812906/) | |
|RVDNet: a two-stage network for real-world video desnowing with domain adaptation<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10448423/) | |
|Slide: Self-supervised lidar de-snowing through reconstruction difficulty<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-19842-7_17) | |
|FedDeSnowNet: Federated De-snowing Network for LiDAR Point Clouds<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-981-96-2864-3_12) | |
|Image snow removal methods for robotic environment fusion<br><sub></sub> |  | 2019 | :camera: |  | [Paper](http://www.cjmenet.com.cn/EN/abstract/abstract3559.shtml) | |
|Stacked dense networks for single-image snow removal<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231219309634) | |
|LIDAR De-Snow Score (DSS): combining quality and perception metrics for optimised data filtering<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.171259681.14859329) | |
|Wavelet-Enhanced Desnowing: A Novel Single Image Restoration Approach for Traffic Surveillance under Adverse Weather Conditions<br><sub></sub> |  | 2503 | :camera: |  | [Paper](https://arxiv.org/abs/2503.01339) | |
|Unsupervised Domain Adaptive Learning for Image Desnowing with Real-World Data<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10222719/) | |
|Snow removal in video: A new dataset and a novel method<br><sub></sub> |  | 2023 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10377855/) | |
|Deep dense multi-scale network for snow removal using semantic and depth priors<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9515587/) | |
|Deraining and Desnowing Algorithm on Adaptive Tolerance and Dual-tree Complex Wavelet Fusion<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://reunir.unir.net/handle/123456789/12840) | |
|Feature Fusion Attention Network with CycleGAN for Image Dehazing, De-Snowing and De-Raining<br><sub></sub> |  | 2503 | :camera: |  | [Paper](https://arxiv.org/abs/2503.06107) | |
|Stereo video deraining and desnowing based on spatiotemporal frame warping<br><sub></sub> |  | 2014 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7026099/) | |
|Desnowformer: an effective transformer-based image desnowing network<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10008815/) | |
|Star-Net: Improving Single Image Desnowing Model With More Efficient Connection and Diverse Feature Interaction<br><sub></sub> |  | 2303 | :camera: |  | [Paper](https://arxiv.org/abs/2303.09988) | |
|Check for updates Lidar De-snowing Method with Density and Intensity Fusion<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://books.google.com/books?hl=en&lr=&id=P-oEEQAAQBAJ&oi=fnd&pg=PA300&dq=desnowing&ots=aM-w9bPP02&sig=EAabmIZ60-vCyP2vqzC2_X4m9tU) | |
|Single‐image snow removal algorithm based on generative adversarial networks<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/ipr2.12887) | |
|Degradation-adaptive neural network for jointly single image dehazing and desnowing<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://dl.acm.org/doi/abs/10.1007/s11704-023-2764-y) | |
|Thermal characterisation of electroconductive layers for anti-icing and de-snowing applications on roads<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.tandfonline.com/doi/abs/10.1080/14680629.2020.1827013) | |
|Snowed autoencoders are efficient snow removers<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0097849323000729) | |
|Rain and Snow Removal<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-981-16-6429-8_7) | |
|Single image rain/snow removal using distortion type information<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11042-022-12012-0) | |
|SnowSTNet: A Spatial-Temporal LiDAR Point Cloud Denoising Network for Autonomous Driving in Snowy Weather<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://isprs-archives.copernicus.org/articles/XLVIII-G-2025/921/2025/) | |
|Denoising framework based on multiframe continuous point clouds for autonomous driving LiDAR in snowy weather<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10418150/) | |
|Cross-Stitched Multi-task Dual Recursive Networks for Unified Single Image Deraining and Desnowing<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10152113/) | |
|Adaptive two-stage filter for de-snowing LiDAR point clouds<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9870722/) | |
|Ultra-efficient and ultra-rapid solar cell de-icing and de-snowing<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11824/118240C/Ultra-efficient-and-ultra-rapid-solar-cell-de-icing-and/10.1117/12.2598078.short) | |
|Single Image Desnow Based on Vision Transformer and Conditional Generative Adversarial Network for Internet of Vehicles.<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://search.ebscohost.com/login.aspx?direct=true&profile=ehost&scope=site&authtype=crawler&jrnl=15261492&AN=164664320&h=i%2Fv%2B7iDpy6DEMW0lLXgupL0HmOcDtC6sk0o%2FbwmcIuEgkbbKK6PYKYN0Q4NtJ0Ucjdolr%2FHMsrtpFEgCLvZM2g%3D%3D&crl=c) | |
|Weatherstream: Light transport automation of single image deweathering<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Zhang_WeatherStream_Light_Transport_Automation_of_Single_Image_Deweathering_CVPR_2023_paper.html) | |
|Parameter-efficient fine-tuning for single image snow removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417424027684) | |
|Snow removal for LiDAR point clouds with spatio-temporal conditional random fields<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10238808/) | |
|Desnow-Gnn: Spatiotemporal Graph Neural Network for Robust Lidar Point Cloud Denoising in Adverse Weather<br><sub></sub> |  | 5364 | :camera: |  | [Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5364005) | |
|SnowMamba: Achieving More Precise Snow Removal with Mamba<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.mdpi.com/2076-3417/15/10/5404) | |
|Video Desnowing Algorithm Based on Multi-Channel Fusion and Group Sparse Coding<br><sub></sub> |  | 2023 | :video_camera: |  | [Paper](https://www.sciopen.com/article/10.13568/j.cnki.651094.651316.2022.02.07.0001) | |
|Beyond the snowfall: Enhancing snowy day object detection through progressive restoration and multi-feature fusion<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10446306/) | |
|A simulation computation of twist of De-Snowing electric wires due to snow accretion<br><sub></sub> |  | 1976 | :camera: |  | [Paper](https://www.jstage.jst.go.jp/article/seppyo1941/38/3/38_3_127/_article/-char/ja/) | |
|Restoring snow-degraded single images with wavelet in vision transformer<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10246273/) | |
|SnowTextNet: Detection-Guided Restoration Dual-Branch Network for Text Detection in Snowy Scenes<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-981-96-9964-3_31) | |
|How Hard Is Snow? A Paired Domain Adaptation Dataset for Clear and Snowy Weather: CADC+<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://arxiv.org/abs/2506.16531) | |
|Restoring vision in adverse weather conditions with patch-based denoising diffusion models<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10021824/) | |
|Simulating Marine Snow Images: Pipeline, Data Set, and Benchmark<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/11129633/) | |
</details>

## All-in-One (AiO) Adverse Weather Removal

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Data | Method | Link | Code |
|-------|-------|------|------|--------|------|------|
| All in One Bad Weather Removal Using Architectural Search<br><sub>Ruoteng Li, Robby T. Tan, Loong-Fah Cheong</sub> | CVPR | 2020 | :camera: | | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_All_in_One_Bad_Weather_Removal_Using_Architectural_Search_CVPR_2020_paper.pdf) |  |
|Interactive (de) weathering of an image using physical models<br><sub></sub> |  | 2003 | :camera: |  | [Paper](https://cave.cs.columbia.edu/Statics/publications/pdfs/Narasimhan_CPMCV03.pdf) | |
|Weatherstream: Light transport automation of single image deweathering<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Zhang_WeatherStream_Light_Transport_Automation_of_Single_Image_Deweathering_CVPR_2023_paper.html) | |
|Learning real-world image de-weathering with imperfect supervision<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28164) | |
|Residual deformable convolution for better image de-weathering<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320323007902) | |
|Automatic image de-weathering using physical model and maximum entropy<br><sub></sub> |  | 2008 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/4670921/) | |
|Review on state of art image enhancement and restoration methods for a vision based driver assistance system with De-weathering<br><sub></sub> |  | 2011 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6089128/) | |
|Pseudo-Label Guided Real-World Image De-weathering: A Learning Framework with Imperfect Supervision<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://arxiv.org/abs/2504.09949) | |
|Highlights on weathering effects: Improving the appearance modeling of weathering effects on images<br><sub></sub> |  | 2010 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00371-010-0495-1) | |
|Fast single image and video deweathering using look-up-table approach<br><sub></sub> |  | 2015 | :video_camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1434841115002538) | |
|Automatic image de-weathering using curvelet-based vanishing point detection<br><sub></sub> |  | 2007 | :camera: |  | [Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=0e0e64326c81f6bbe6881b83cfbf8dce9044a36d) | |
|Image de-weathering for road based on physical model<br><sub></sub> |  | 2009 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/5365298/) | |
|Gpu-accelerated real-time surveillance de-weathering<br><sub></sub> |  | 2013 | :camera: |  | [Paper](https://www.diva-portal.org/smash/record.jsf?pid=diva2:647937) | |
|Real time image and video deweathering: The future prospects and possibilities<br><sub></sub> |  | 2016 | :video_camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0030402615014370) | |
|Identifying decadal trends in deweathered concentrations of criteria air pollutants in Canadian urban atmospheres with machine learning approaches<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://acp.copernicus.org/articles/24/7773/2024/) | |
|A hybrid approach for a vision based driver assistance system with de-weathering<br><sub></sub> |  | 2012 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/6202464/) | |
|Machine learning 'De-Weathering 'of urban NOx data to quantify meteorological impacts at two traffic sites in Germany<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://febuko.tropos.de/images/Posterseite/Poster/2020/Abstract_Faraday_Discussions_2020.pdf) | |
|Meteorological Normalization or Deweathering for Predicting Air Pollutant Concentration: Pitfalls and Limitations<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://chemrxiv.org/engage/chemrxiv/article-details/67126f38cec5d6c14285002e) | |
|Spatial, temporal features and influence of meteorology on PM2. 5 and O3 association across urban and rural environments of India<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S2590162124000327) | |
|Significant changes in chemistry of fine particles in wintertime Beijing from 2007 to 2017: impact of clean air actions<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.est.9b04678) | |
|Identifying decadal trends in deweathered concentrations of criteria air pollutants in Canadian urban atmospheres with machine learning approaches<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://egusphere.copernicus.org/preprints/2023/egusphere-2023-2968/) | |
|A Review on Deweathering Methods: Fog & Haze Removal<br><sub></sub> |  | 2016 | :camera: |  | [Paper](https://ijarest.org/index.php/ijarest/article/download/1131/1105) | |
|Impacts of emergency health protection measures upon air quality, traffic and public health: evidence from Oxford, UK<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0269749121021667) | |
|Causes of the unexpected slowness in reducing winter PM2. 5 for 2014–2018 in Henan Province<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0269749122021431) | |
|Deep learning-based weather image recognition<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8644946/) | |
|Evaluating the real changes of air quality due to clean air actions using a machine learning technique: Results from 12 Chinese mega-cities during 2013–2020<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0045653522011018) | |
|Abrupt but smaller than expected changes in surface air quality attributable to COVID-19 lockdowns<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://www.science.org/doi/abs/10.1126/sciadv.abd6696) | |
|Does COVID-19 lockdown matter for air pollution in the short and long run in China? A machine learning approach to policy evaluation<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S030147972402601X) | |
|The impact of urban mobility on air pollution in Kampala, an exemplar sub-Saharan African city<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S1309104224000229) | |
|Measuring the emission changes and meteorological dependence of source‐specific BC aerosol using factor analysis coupled with machine learning<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2023JD038696) | |
|Space weathering (and de-weathering) of asteroids.<br><sub></sub> |  | 2014 | :camera: |  | [Paper](https://ui.adsabs.harvard.edu/abs/2014MSAIS..26...53P/abstract) | |
|Quantifying the impact of clean air policy interventions for air quality management<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://epapers.bham.ac.uk/4040/) | |
|Unraveling the O3-NOX-VOCs relationships induced by anomalous ozone in industrial regions during COVID-19 in Shanghai<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S135223102300290X) | |
|Decadal Trends of Criteria Pollutants and PM2. 5 Components in Canadian Cities<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ui.adsabs.harvard.edu/abs/2022AGUFM.A12O1292Z/abstract) | |
|Investigating the impact of meteorology and emissions on PM2.5 and PM10 in Delhi using machine learning<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://egusphere.copernicus.org/preprints/2025/egusphere-2025-2300/) | |
|Adverse weather removal with codebook priors<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Ye_Adverse_Weather_Removal_with_Codebook_Priors_ICCV_2023_paper.html) | |
|Language-driven all-in-one adverse weather removal<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_Language-driven_All-in-one_Adverse_Weather_Removal_CVPR_2024_paper.html) | |
|Learning multiple adverse weather removal via two-stage knowledge learning and multi-contrastive regularization: Toward a unified model<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Chen_Learning_Multiple_Adverse_Weather_Removal_via_Two-Stage_Knowledge_Learning_and_CVPR_2022_paper.html) | |
|Exploring the application of large-scale pre-trained models on adverse weather removal<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10453462/) | |
|Mowe: mixture of weather experts for multiple adverse weather removal<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.researchgate.net/profile/Rui_Zhao106/publication/369540540_MoWE_Mixture_of_Weather_Experts_for_Multiple_Adverse_Weather_Removal/links/64b93df2b9ed6874a53138a9/MoWE-Mixture-of-Weather-Experts-for-Multiple-Adverse-Weather-Removal.pdf) | |
|Learning weather-general and weather-specific features for image restoration under multiple adverse weather conditions<br><sub></sub> |  | 2023 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Zhu_Learning_Weather-General_and_Weather-Specific_Features_for_Image_Restoration_Under_Multiple_CVPR_2023_paper.html) | |
|Transweather: Transformer-based restoration of images degraded by adverse weather conditions<br><sub></sub> |  | 2022 | :camera: |  | [Paper](http://openaccess.thecvf.com/content/CVPR2022/html/Valanarasu_TransWeather_Transformer-Based_Restoration_of_Images_Degraded_by_Adverse_Weather_Conditions_CVPR_2022_paper.html) | |
|Continuous adverse weather removal via degradation-aware distillation<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Lu_Continuous_Adverse_Weather_Removal_via_Degradation-Aware_Distillation_CVPR_2025_paper.html) | |
|DRR: A new method for multiple adverse weather removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417424031154) | |
|Image all-in-one adverse weather removal via dynamic model weights generation<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705124009584) | |
|Always clear days: Degradation type and severity aware all-in-one adverse weather removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10829609/) | |
|Continual all-in-one adverse weather removal with knowledge replay on a unified network structure<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10473168/) | |
|CMAWRNet: Multiple Adverse Weather Removal via a Unified Quaternion Neural Architecture<br><sub></sub> |  | 2505 | :camera: |  | [Paper](https://arxiv.org/abs/2505.01882) | |
|Genuine knowledge from practice: Diffusion test-time adaptation for video adverse weather removal<br><sub></sub> |  | 2024 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10656364/) | |
|Rethinking all-in-one adverse weather removal for object detection<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11760-024-03493-7) | |
|SemiDDM-Weather: A Semi-supervised Learning Framework for All-in-one Adverse Weather Removal<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://arxiv.org/abs/2409.19679) | |
|Framework for generation and removal of multiple types of adverse weather from driving scene images<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.mdpi.com/1424-8220/23/3/1548) | |
|Robust Adverse Weather Removal via Spectral-based Spatial Grouping<br><sub></sub> |  | 2507 | :camera: |  | [Paper](https://arxiv.org/abs/2507.22498) | |
|Multimodal prompt state space models for unified adverse weather removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197625016689) | |
|Multiple Adverse Weather Removal Using Masked-Based Pre-Training and Dual-Pooling Adaptive Convolution<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10506517/) | |
|Video adverse-weather-component suppression network via weather messenger and adversarial backpropagation<br><sub></sub> |  | 2023 | :video_camera: |  | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Yang_Video_Adverse-Weather-Component_Suppression_Network_via_Weather_Messenger_and_Adversarial_Backpropagation_ICCV_2023_paper.html) | |
|All in one bad weather removal using architectural search<br><sub></sub> |  | 2020 | :camera: |  | [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_All_in_One_Bad_Weather_Removal_Using_Architectural_Search_CVPR_2020_paper.html) | |
|Decoupling degradation and content processing for adverse weather image restoration<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://arxiv.org/abs/2312.05006) | |
|WM-MoE: Weather-aware multi-scale mixture-of-experts for blind adverse weather removal<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://arxiv.org/abs/2303.13739) | |
|Prompt to Restore, Restore to Prompt: Cyclic Prompting for Universal Adverse Weather Removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://arxiv.org/abs/2503.09013) | |
|All-in-one adverse weather removal via dual state space-based diffusion model with degradation-aware guidance<br><sub></sub> |  | 2026 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320325007411) | |
|RestoreCUFormer: Transformers to Make Strong Encoders via Two-stage Knowledge Learning For Multiple Adverse Weather Removal<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10650830/) | |
|Learning to remove bad weather: towards robust visual perception for self-driving<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9722965/) | |
|Restoring images in adverse weather conditions via histogram transformer<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72670-5_7) | |
|Removing Multiple Hybrid Adverse Weather in Video via a Unified Model<br><sub></sub> |  | 2025 | :video_camera: |  | [Paper](https://arxiv.org/abs/2503.06200) | |
|WeatherClean: An Image Restoration Algorithm for UAV-Based Railway Inspection in Adverse Weather<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.mdpi.com/1424-8220/25/15/4799) | |
|Low-rank adaptation-based all-weather removal for autonomous navigation<br><sub></sub> |  | 2411 | :camera: |  | [Paper](https://arxiv.org/abs/2411.17814) | |
|TAP: Parameter-efficient Task-Aware Prompting for Adverse Weather Removal<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://arxiv.org/abs/2508.07878) | |
|Point cloud processing under adverse weather: a survey of datasets, enhancement, and denoising methods<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11760-025-04352-9) | |
|DDCNet: Advanced Decoupling of Degradation and Content for Adverse Weather Image Restoration<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/11115131/) | |
|Multiple adverse weather removal using adversarial and contrastive learning<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10448702/) | |
|ART-SS: an adaptive rejection technique for semi-supervised restoration for adverse weather-affected images<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-19797-0_40) | |
|Restoring vision in adverse weather conditions with patch-based denoising diffusion models<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10021824/) | |
|4denoisenet: Adverse weather denoising from adjacent point clouds<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9976208/) | |
|Combating bad weather part i: Rain removal from video<br><sub></sub> |  | 2014 | :video_camera: |  | [Paper](https://books.google.com/books?hl=en&lr=&id=ibksBgAAQBAJ&oi=fnd&pg=PR13&dq=adverse+weather+removal&ots=uAzNymZoxJ&sig=-DBQSffiF85DMmB46vrx9udcJ24) | |
|Allweather-net: Unified image enhancement for autonomous driving under adverse weather and low-light conditions<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-78113-1_11) | |
|A Review of Unmanned Visual Target Detection in Adverse Weather<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.mdpi.com/2079-9292/14/13/2582) | |
|Disentangled bad weather removal gan for pedestrian detection<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9860865/) | |
|Learning to Restore Arbitrary Hybrid adverse weather Conditions in one go<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320325001645) | |
|Analysis of adverse weather for excusable delays<br><sub></sub> |  | 2010 | :camera: |  | [Paper](https://ascelibrary.org/doi/abs/10.1061/(ASCE)CO.1943-7862.0000242) | |
|Current and future approaches to wet weather flow management: A review<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/wer.1506) | |
|Towards real-world adverse weather image restoration: Enhancing clearness and semantics with vision-language models<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72649-1_9) | |
|Multi-weather city: Adverse weather stacking for autonomous driving<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/ICCV2021W/AVVision/html/Musat_Multi-Weather_City_Adverse_Weather_Stacking_for_Autonomous_Driving_ICCVW_2021_paper.html) | |
|Weathergs: 3d scene reconstruction in adverse weather conditions via gaussian splatting<br><sub></sub> |  | 2412 | :camera: |  | [Paper](https://arxiv.org/abs/2412.18862) | |
|Study of Filtering the Weather Adverse Effects to Object Detection<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1134/S1063779624030766) | |
|Learning with confidence the likelihood of flight diversion due to adverse weather at destination<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10021220/) | |
|… Encoder and Decoder-Based Transformer Fusion with Deep Residual Attention for Restoration of Degraded Images and Clear Visualization in Adverse Weather …<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s13369-023-08342-2) | |
|Cfmw: Cross-modality fusion mamba for multispectral object detection under adverse weather conditions<br><sub></sub> |  | 2404 | :camera: |  | [Paper](https://arxiv.org/abs/2404.16302) | |
|Framework of degraded image restoration and simultaneous localization and mapping for multiple bad weather conditions<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/journals/optical-engineering/volume-62/issue-4/048102/Framework-of-degraded-image-restoration-and-simultaneous-localization-and-mapping/10.1117/1.OE.62.4.048102.short) | |
|Problems related to the operation of autonomous vehicles in adverse weather conditions<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://yadda.icm.edu.pl/baztech/element/bwmeta1.element.baztech-407eba4f-2e43-4eec-beb5-66d447cf0b14) | |
|TANet: Triplet attention network for all-in-one adverse weather image restoration<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/ACCV2024/html/Wang_TANet_Triplet_Attention_Network_for_All-In-One_Adverse_Weather_Image_Restoration_ACCV_2024_paper.html) | |
|Power Line Aerial Image Restoration Under Adverse Weather: Datasets and Baselines<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10930826/) | |
|Unified multi-weather visibility restoration<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9966834/) | |
|Degradation type-aware image restoration for effective object detection in adverse weather<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.mdpi.com/1424-8220/24/19/6330) | |
|Da-raw: Domain adaptive object detection for real-world adverse weather conditions<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10611219/) | |
|Cnn-based lidar point cloud de-noising in adverse weather<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8990038/) | |
|Let it snow: On the synthesis of adverse weather image data<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9565008/) | |
|DS-Diff: a dual-stage network with degradation-aware and semantic-aware for adverse weather removal based on diffusion models<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s00530-024-01606-3) | |
|AdverseNet: A Unified LiDAR Point Cloud Denoising Network for Autonomous Driving in Adverse Weather<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10832503/) | |
|Contrast restoration of weather degraded images<br><sub></sub> |  | 2003 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/1201821/) | |
|Teaching tailored to talent: Adverse weather restoration via prompt pool and depth-anything constraint<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72673-6_6) | |
|Enhancing robustness of weather removal: preprocessing-based defense against adversarial attacks<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13033/130330L/Enhancing-robustness-of-weather-removal--preprocessing-based-defense-against/10.1117/12.3019864.short) | |
|Role of adverse weather in key crash types on limited-access: roadways implications for advanced weather systems<br><sub></sub> |  | 1998 | :camera: |  | [Paper](https://journals.sagepub.com/doi/abs/10.3141/1621-02) | |
|Survey on lidar perception in adverse weather conditions<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10186539/) | |
|Gridformer: Residual dense transformer with grid structure for image restoration in adverse weather conditions<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s11263-024-02056-0) | |
|Vehicle detection and tracking in adverse weather using a deep learning framework<br><sub></sub> |  | 2020 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9184996/) | |
|Rethinking LiDAR object detection in adverse weather conditions<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9812039/) | |
|Visual quality enhancement of images under adverse weather conditions<br><sub></sub> |  | 2018 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8569536/) | |
|Worsening perception: Real-time degradation of autonomous vehicle perception performance for simulation of adverse weather conditions<br><sub></sub> |  | 2021 | :camera: |  | [Paper](https://arxiv.org/abs/2103.02760) | |
|Depth-aware blind image decomposition for real-world adverse weather recovery<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-73007-8_22) | |
|Robust object detection in challenging weather conditions<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Gupta_Robust_Object_Detection_in_Challenging_Weather_Conditions_WACV_2024_paper.html) | |
|Gradient-Guided Parameter Mask for Multi-Scenario Image Restoration Under Adverse Weather<br><sub></sub> |  | 2411 | :camera: |  | [Paper](https://arxiv.org/abs/2411.16739) | |
|Wavelet-Enhanced Desnowing: A Novel Single Image Restoration Approach for Traffic Surveillance under Adverse Weather Conditions<br><sub></sub> |  | 2503 | :camera: |  | [Paper](https://arxiv.org/abs/2503.01339) | |
|IDP-YOLOV9: Improvement of Object Detection Model in Severe Weather Scenarios from Drone Perspective.<br><sub></sub> |  | 2076 | :camera: |  | [Paper](https://pdfs.semanticscholar.org/2c8f/0d4b713be1171f6a5d6eca1ee74ebcc4bda1.pdf) | |
|Object Detection in Adverse Weather Conditions using Machine Learning<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10421471/) | |
|Weather removal with a lightweight quaternion Chebyshev neural network<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12526/125260V/Weather-removal-with-a-lightweight-quaternion-Chebyshev-neural-network/10.1117/12.2664858.short) | |
|Q-KAN: enhancing robustness of weather removal: preprocessing-based defense against adversarial attacks<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13457/134570O/Q-KAN--enhancing-robustness-of-weather-removal--preprocessing/10.1117/12.3054177.short) | |
|MODEM: A Morton-Order Degradation Estimation Mechanism for Adverse Weather Image Recovery<br><sub></sub> |  | 2505 | :camera: |  | [Paper](https://arxiv.org/abs/2505.17581) | |
|Perception methods for adverse weather based on vehicle infrastructure cooperation system: A review<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://www.mdpi.com/1424-8220/24/2/374) | |
|ARODNet: adaptive rain image enhancement object detection network for autonomous driving in adverse weather conditions<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://www.spiedigitallibrary.org/journals/optical-engineering/volume-62/issue-11/118101/ARODNet--adaptive-rain-image-enhancement-object-detection-network-for/10.1117/1.OE.62.11.118101.short) | |
|AWRaCLe: All-weather image restoration using visual in-context learning<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32716) | |
|Dsor: A scalable statistical filter for removing falling snow from lidar point clouds in severe winter weather<br><sub></sub> |  | 2109 | :camera: |  | [Paper](https://arxiv.org/abs/2109.07078) | |
|The impact of adverse weather conditions on autonomous vehicles: How rain, snow, fog, and hail affect the performance of a self-driving car<br><sub></sub> |  | 2019 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/8666747/) | |
|Prompt-guided and degradation prior supervised transformer for adverse weather image restoration<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s10489-024-06050-4) | |
|Adverse weather target detection algorithm based on adaptive color levels and improved YOLOv5<br><sub></sub> |  | 2022 | :camera: |  | [Paper](https://www.mdpi.com/1424-8220/22/21/8577) | |
|Test-time Adaptation for Real-World Video Adverse Weather Restoration with Meta Batch Normalization<br><sub></sub> |  | 2025 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10833729/) | |
|Restoring images captured in arbitrary hybrid adverse weather conditions in one go<br><sub></sub> |  | 2023 | :camera: |  | [Paper](https://arxiv.org/abs/2305.09996) | |
|Unifying Physically-Informed Weather Priors in A Single Model for Image Restoration Across Multiple Adverse Weather Conditions<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10966874/) | |
|Perception-friendly video enhancement for autonomous driving under adverse weather conditions<br><sub></sub> |  | 2022 | :video_camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/9811870/) | |
|A decision support method for flight cancellations in adverse weather: An airport perspective<br><sub></sub> |  | 2015 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/7311348/) | |
|AdWeatherNet: Adverse Weather Denoising with Point Cloud Spatiotemporal Attention<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://ieeexplore.ieee.org/abstract/document/10849938/) | |
|Adaptive enhancement of spatial information in adverse weather<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/article/10.1007/s41324-024-00577-x) | |
|WRRT-DETR: weather-robust RT-DETR for drone-view object detection in adverse weather<br><sub></sub> |  | 2025 | :camera: |  | [Paper](https://www.mdpi.com/2504-446X/9/5/369) | |
|Rethinking data augmentation for robust lidar semantic segmentation in adverse weather<br><sub></sub> |  | 2024 | :camera: |  | [Paper](https://link.springer.com/content/pdf/10.1007/978-3-031-72640-8_18.pdf) | |
</details>




# High-level Vision

## Object Detection

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Weather | Data | Link | Code |
|-------|-------|------|---------|------|------|------|
| Three-Channel Infrared Imaging for Object Detection in Haze<br><sub>Beinan Yu, Yifan Chen, Si-Yuan Cao, Hui-Liang Shen, Junwei Li</sub> | TIM | 2022 | Haze | :camera: | [Paper](https://ieeexplore.ieee.org/abstract/document/9745969) |  |
| Detection-Friendly Dehazing: Object Detection in Real-World Hazy Scenes<br><sub>Chengyang Li; Heng Zhou; Yang Liu; Caidong Yang; Yongqiang Xie; Zhongbo Li</sub> | TPAMI | 2023 | Haze | :camera: | [Paper](https://ieeexplore.ieee.org/abstract/document/10012056) | 
| Unified Density-Aware Image Dehazing and Object Detection in Real-World Hazy Scenes<br><sub>Zhengxi Zhang⋆, Liang Zhao⋆, Yunan Liu, Shanshan Zhang, Jian Yan</sub> | ACCV | 2020 | Haze | :camera: | [Paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Zhang_Unified_Density-Aware_Image_Dehazing_and_Object_Detection_in_Real-World_Hazy_ACCV_2020_paper.pdf) | [Code](https://github.com/xiqi98/UDnD) |
|HazyDet: Open-Source Benchmark for Drone-View Object Detection with Depth-Cues in Hazy Scenes<br><sub>Changfeng Feng, Zhenyuan Chen, Xiang Li, Chunping Wang, Jian Yang, Ming-Ming Cheng, Yimian Dai, Qiang Fu</sub> | ArXiv | 2024 | Haze | 📷 :bar_chart: | [Paper](https://arxiv.org/abs/2409.19833) | [Code](https://github.com/GrokCV/HazyDet) |
|Rain Rendering for Evaluating and Improving Robustness to Bad Weather<br><sub>Maxime Tremblay, Shirsendu Sukanta Halder, Raoul de Charette & Jean-François Lalonde</sub> | IJCV | 2020 | 🌧️ | 📷 | [Paper](https://link.springer.com/article/10.1007/s11263-020-01366-3) | [Code](https://github.com/astra-vision/rain-rendering) |
</details>

## Semantic Segmentation

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Weather | Data | Link | Code |
|-------|-------|------|---------|------|------|------|
|Rain Rendering for Evaluating and Improving Robustness to Bad Weather<br><sub>Maxime Tremblay, Shirsendu Sukanta Halder, Raoul de Charette & Jean-François Lalonde</sub> | IJCV | 2020 | 🌧️ | 📷 | [Paper](https://link.springer.com/article/10.1007/s11263-020-01366-3) | [Code](https://github.com/astra-vision/rain-rendering) |
</details>

## Object Tracking

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Weather | Data | Link | Code |
|-------|-------|------|---------|------|------|------|
</details>

## Depth Estimation
<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>

| Paper | Venue | Year | Weather | Data | Link | Code |
|-------|-------|------|---------|------|------|------|
|DEHRFormer: Real-Time Transformer for Depth Estimation and Haze Removal from Varicolored Haze Scenes<br><sub>Sixiang Chen; Tian Ye; Jun Shi; Yun Liu; JingXia Jiang; Erkang Chen</sub> | ICASSP | 2023 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/10096828) | |
|Depth Estimation for Hazy Images Using Deep Learning<br><sub>Laksmita Rahadianti; Fumihiko Sakaue; Jun Sato</sub> | ACPR | 2017 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/8575830) | |
|CNN-Based Simultaneous Dehazing and Depth Estimation<br><sub>Byeong-Uk Lee; Kyunghyun Lee; Jean Oh; In So Kweon</sub> | ICRA | 2020 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/9197358) | |
|S2DNet: Depth Estimation From Single Image and Sparse Samples<br><sub>Praful Hambarde; Subrahmanyam Murala</sub> | TCI | 2020 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/9040600) | |
|Depth-Centric Dehazing and Depth-Estimation from Real-World Hazy Driving Video<br><sub>Junkai Fan, Kun Wang, Zhiqiang Yan, Xiang Chen, Shangbing Gao, Jun Li, Jian Yang</sub> | AAAI | 2025 | :fog: | 📹 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32291) | [Code](https://github.com/fanjunkai1/DCL) |
|Combining semantic scene priors and haze removal for single image depth estimation<br><sub>Ke Wang; Enrique Dunn; Joseph Tighe; Jan-Michael Frahm</sub> | WACV | 2014 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/6836021) | |
|Depth Estimation from Single Hazy Images with 2-Phase Training<br><sub>Laksmita Rahadianti; Fumihiko Sakaue; Jun Sato</sub> | ICACSIS | 2020 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/9263244) | |
|Progressive dehazing and depth estimation from a single hazy image<br><sub>Jeonghoon Kim, Sungyoon Kim, Changhoon Pyo, Hyeongmyeon Kim, Changhoon Yi</sub> | IEIE SPC | 2022 | :fog: | 📷 | [Paper](https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11151164) | |
|Image-Based PM2.5 Estimation and its Application on Depth Estimation<br><sub>Jian Ma; Kun Li; Yahong Han; Pufeng Du; Jingyu Yang</sub> | ICASSP | 2018 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/8461776) | |
|S2DNet: Depth Estimation From Single Image and Sparse Samples<br><sub>Praful Hambarde; Subrahmanyam Murala</sub> | TCI | 2020 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/9040600) | |
|Robust Depth Estimation in Foggy Environments Combining RGB Images and mmWave Radar<br><sub>Mengchen Xiong; Xiao Xu; Dong Yang; Eckehard Steinbach</sub> | ISM | 2022 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/10019611) | |
|FoggyDepth: Leveraging Channel Frequency and Non-Local Features for Depth Estimation in Fog<br><sub>Mengjiao Shen; Liuyi Wang; Xianyou Zhong; Chengju Liu; Qijun Chen</sub> | TCSVT | 2025 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/10772035) | |
|Fog density estimation and image defogging based on surrogate modeling for optical depth<br><sub>Yutong Jiang; Changming Sun; Yu Zhao; Li Yang</sub> | TIP | 2017 | :fog: | :camera: | [Paper](https://ieeexplore.ieee.org/abstract/document/7918592) | |
|Example based depth from fog<br><sub>Kristofor B. Gibson; Serge J. Belongie; Truong Q. Nguyen</sub> | ICIP | 2013 | :fog: | :camera: | [Paper](https://ieeexplore.ieee.org/abstract/document/6738150) | |
|An enhanced window-variant dark channel prior for depth estimation using single foggy image<br><sub>Jie Chen; Lap-Pui Chau</sub> | ICIP | 2013 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/6738724) | |
|Self-supervised monocular depth estimation in fog<br><sub>Bo Tao†, Jiaxin Hu†, Du Jiang, Gongfa Li, Baojia Chen, Xinbo Qian</sub> | OE | 2022 | :fog: | 📷 | [Paper](https://www.spiedigitallibrary.org/journals/optical-engineering/volume-62/issue-3/031208/Self-supervised-monocular-depth-estimation-in-fog/10.1117/1.OE.62.3.031208.short) | [Code](https://github.com/Hjxin02AIsharing-Wust/DepthEstimationInFog) |
|Estimating Fog Parameters From an Image Sequence Using Non-Linear Optimisation<br><sub>Yining Ding, Andrew M. Wallace, Sen Wang</sub> | WACV | 2024 | :fog: | 📷 | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Ding_Estimating_Fog_Parameters_From_an_Image_Sequence_Using_Non-Linear_Optimisation_WACV_2024_paper.html) | |
|Factorizing Scene Albedo and Depth from a Single Foggy Image<br><sub>Louis Kratz; Ko Nishino</sub> | ICCV | 2009 | :fog: | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/5459382/) | |
|Self-supervised Monocular Depth Estimation: Let's Talk About The Weather<br><sub>Kieran Saunders, George Vogiatzis, Luis J. Manso</sub> | ICCV | 2023 | :fog::cloud_with_rain::snowflake: | 📷 | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Saunders_Self-supervised_Monocular_Depth_Estimation_Lets_Talk_About_The_Weather_ICCV_2023_paper.html) | [Code](https://kieran514.github.io/Robust-Depth-Project/) |
|Unsupervised Monocular Depth Estimation for Foggy Images with Domain Separation and Self-Depth Domain Conversion<br><sub>Fuyang Liu, Jianjun Li</sub> | CVM | 2025 | 🌫️ | 📷 | [Paper](https://link.springer.com/chapter/10.1007/978-981-96-5812-1_21) | |
|Depth from phasor distortions in fog<br><sub>Takeshi Muraji, Kenichiro Tanaka, Takuya Funatomi, Yasuhiro Mukaigawa</sub> | Optics Express| 2019 | :fog: | 📷 | [Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-13-18858&id=414675) | [Code]() |
|Gated2Gated: Self-Supervised Depth Estimation from Gated Images<br><sub>Amanpreet Walia, Stefanie Walz, Mario Bijelic, Fahim Mannan, Frank Julca-Aguilar, Michael Langer, Werner Ritter, Felix Heide</sub> | CVPR | 2022 | :fog:❄️ | 📷 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Walia_Gated2Gated_Self-Supervised_Depth_Estimation_From_Gated_Images_CVPR_2022_paper.html) | [Code](https://github.com/princeton-computational-imaging/Gated2Gated) |
|<br><sub></sub> | | | | | [Paper]() | [Code]() |
|Rain Rendering for Evaluating and Improving Robustness to Bad Weather<br><sub>Maxime Tremblay, Shirsendu Sukanta Halder, Raoul de Charette & Jean-François Lalonde</sub> | IJCV | 2020 | 🌧️ | 📷 | [Paper](https://link.springer.com/article/10.1007/s11263-020-01366-3) | [Code](https://github.com/astra-vision/rain-rendering) |
|Robust Monocular Depth Estimation under Challenging Conditions<br><sub>Stefano Gasperini, Nils Morbitzer, HyunJun Jung, Nassir Navab, Federico Tombari</sub> | ICCV | 2023 | 🌧️🌃 | 📷 | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Gasperini_Robust_Monocular_Depth_Estimation_under_Challenging_Conditions_ICCV_2023_paper.html) | [Code](https://md4all.github.io) |
|Empirical Study: Monocular Depth Estimation from RGB, NIR, Thermal Image in Adverse Weather Conditions<br><sub>Ukcheol Shin; Soonmin Hwang; Jean Oh</sub> | ICTC | 2023 | 🌧️❄️🌃 | | [Paper](https://ieeexplore.ieee.org/abstract/document/10393306) | |
</details>

## Autonomous Driving

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Weather | Data | Link | Code |
|-------|-------|------|---------|------|------|------|
</details>


## Scene Stylization

<details open="true">
<summary><strong>Paper List</strong> (click to expand) </summary>
  
| Paper | Venue | Year | Weather | Data | Link | Code |
|-------|-------|------|---------|------|------|------|
|Dehazing-NeRF: Neural Radiance Fields from Hazy Images<br><sub>Tian Li, LU Li, Wei Wang, Zhangchi Feng</sub> | Arxiv | 2023 | 🌫️ | 📷 | [Paper](https://arxiv.org/abs/2304.11448) | [Code](https://github.com/nulllt/dehazing-nerf) |
|DehazeNeRF: Multiple Image Haze Removal and 3D Shape Reconstruction using Neural Radiance Fields<br><sub>Wei-Ting Chen, Wang Yifan, Sy-Yen Kuo, Gordon Wetzstein</sub> | 3DV | 2024 | 🌫️ | 📷 | [Paper](https://arxiv.org/abs/2303.11364) | [Code](https://github.com/weitingchen83/DehazeNeRF/tree/main) |
|RainyScape: Unsupervised Rainy Scene Reconstruction using Decoupled Neural Rendering<br><sub>Xianqiang Lyu, Hui Liu, Junhui Hou</sub> | MM | 2024 | 🌧️ | 📷 | [Paper](https://dl.acm.org/doi/10.1145/3664647.3681290) | [Code](https://github.com/lyuxianqiang/RainyScape) |
|DeRainGS: Gaussian Splatting for Enhanced Scene Reconstruction in Rainy Environments<br><sub>Shuhong Liu, Xiang Chen, Hongming Chen, Quanfeng Xu, Mingrui Li</sub> | AAAI | 2025 | 🌧️ | 📷 | [Paper](https://arxiv.org/abs/2408.11540) | |
|DerainNeRF: 3D Scene Estimation with Adhesive Waterdrop Removal<br><sub>Yunhao Li, Jing Wu, Lingzhe Zhao, Peidong Liu</sub> | ICRA | 2024 | 💧 | 📷 | [Paper](https://ieeexplore.ieee.org/abstract/document/10609981/) | [Code](https://github.com/yunhaoli2020/DerainNeRF) |
|Weathergs: 3d scene reconstruction in adverse weather conditions via gaussian splatting<br><sub>Chenghao Qian, Yuhu Guo, Wenjing Li, Gustav Markkula</sub> | ICRA | 2025 | 🌧️❄️ | 📷 | [Paper](https://arxiv.org/pdf/2412.18862) | [Code](https://github.com/Jumponthemoon/WeatherGS) |
|ClimateNeRF: Extreme Weather Synthesis in Neural Radiance Field<br><sub>Yuan Li, Zhi-Hao Lin, David Forsyth, Jia-Bin Huang, Shenlong Wang</sub> | ICCV | 2023 | 🌫️❄️ | 📷 | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Li_ClimateNeRF_Extreme_Weather_Synthesis_in_Neural_Radiance_Field_ICCV_2023_paper.html) | [Code](https://github.com/y-u-a-n-l-i/Climate_NeRF) |
|Rain Rendering for Evaluating and Improving Robustness to Bad Weather<br><sub>Maxime Tremblay, Shirsendu Sukanta Halder, Raoul de Charette & Jean-François Lalonde</sub> | IJCV | 2020 | 🌧️ | 📷 | [Paper](https://link.springer.com/article/10.1007/s11263-020-01366-3) | [Code](https://github.com/astra-vision/rain-rendering) |
|WeatherDiffusion: Weather-Guided Diffusion Model for Forward and Inverse Rendering<br><sub>Yixin Zhu, Zuoliang Zhu, Miloš Hašan, Jian Yang, Jin Xie, Beibei Wang</sub> | Arxiv | 2025 | :fog:🌧️❄️ | 📷 | [Paper](https://arxiv.org/abs/2508.06982) | |
|Physics-Based Rendering for Improving Robustness to Rain<br><sub>Shirsendu Halder; Jean-Francois Lalonde; Raoul De Charette</sub> | ICCV | 2019 | 🌧️ | 📷 | [Paper](https://ieeexplore.ieee.org/document/9010641) | [Code](https://team.inria.fr/rits/computer-vision/weather-augment/) |
|ScatterNeRF: Seeing Through Fog with Physically-Based Inverse Neural Rendering<br><sub>Andrea Ramazzina, Mario Bijelic, Stefanie Walz, Alessandro Sanvito, Dominik Scheuble, Felix Heide</sub> | ICCV | 2023 | :fog: | :camera: | [Paper](http://openaccess.thecvf.com/content/ICCV2023/html/Ramazzina_ScatterNeRF_Seeing_Through_Fog_with_Physically-Based_Inverse_Neural_Rendering_ICCV_2023_paper.html) | [Code](https://github.com/princeton-computational-imaging/scatternerf) |
|ClimateGS: Real-Time Climate Simulation with 3D Gaussian Style Transfer<br><sub>Yuezhen Xie, Meiying Zhang, Qi Hao</sub> | Arxiv | 2025 | :snow: | 📷 | [Paper](https://arxiv.org/abs/2503.14845) | |
|WeatherEdit: Controllable Weather Editing with 4D Gaussian Field<br><sub>Chenghao Qian, Wenjing Li, Yuhu Guo, Gustav Markkula</sub> | Arxiv | 2025 | :fog:🌧️❄️ | 📷 | [Paper](https://arxiv.org/abs/2505.20471) | [Code](https://github.com/Jumponthemoon/WeatherEdit) |
</details>

# Benchmark

D-hazy: A dataset to evaluate quantitatively dehazing algorithms



|<br><sub></sub> | | | | | [Paper]() | [Code]() |
