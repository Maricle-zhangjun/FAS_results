# Paper results of Face Anti-spoofing

🔔 If experiment results are derived from a non-original paper, the paper needs to be tagged in 'Results From'.

---

## Contents
- [Cross test](#cross)
- [Intra test](#intra)
  - [CASIA-FASD & Replay-attack](#C&R)
  - [OULU-NPU](#O)
  - [SiW](#S) 

---

<a name="cross" />

### Cross test

| Method | Results From | O&C&I to M <br> HTER(%) AUC(%) | O&M&I to C <br> HTER(%) AUC(%) | O&C&M to I <br> HTER(%) AUC(%) | I&C&M to O <br> HTER(%) AUC(%) | Year Notes | Code |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [MADDG](https://ieeexplore.ieee.org/abstract/document/8953226) |[DSCI](https://ieeexplore.ieee.org/abstract/document/10288514)| 17.69 88.06 | 24.50 84.51 | 22.19 84.99 | 27.89 80.02 | 2019 CVPR | [Code](https://github.com/rshaojimmy/MADDoG) |
| [PAD-GAN](https://ieeexplore.ieee.org/document/9156555) |[DSCI](https://ieeexplore.ieee.org/abstract/document/10288514)| 17.02 90.10 | 19.68 87.43 | 20.87 86.72 | 25.02 81.47 |  2020 CVPR |
| [SSDG](https://ieeexplore.ieee.org/document/9156366) |[DSCI](https://ieeexplore.ieee.org/abstract/document/10288514)| 7.38 97.17 | 10.44 95.94 | 11.71 96.59 | 15.61 91.54 |  2020 CVPR | [Code](https://github.com/taylover-pei/SSDG-CVPR2020) |
| [DDAM](https://ojs.aaai.org/index.php/AAAI/article/view/16199) |[DSCI](https://ieeexplore.ieee.org/abstract/document/10288514)| 12.70 95.66 | 20.98 85.58 | 15.43 91.22 | 15.27 90.87 | 2021 AAAI |
| [DTN](https://ieeexplore.ieee.org/document/9507460) || 19.40 86.87 | 22.03 87.71 | 21.43 88.81 | 18.26 89.40 | 2021 TIFS |
| [SSAN](https://ieeexplore.ieee.org/document/9879842) |[DSCI](https://ieeexplore.ieee.org/abstract/document/10288514)| 6.67 98.75 | 10.00 96.67 | 8.88 96.79 | 13.72 93.63 |  2022 CVPR | [Code](https://github.com/wangzhuo2019/SSAN) |
| [CIFAS](https://ieeexplore.ieee.org/document/9859783) |[DSCI](https://ieeexplore.ieee.org/abstract/document/10288514)| 5.95 96.32 | 10.66 95.30 | 8.50 97.24 | 13.17 93.44 |  2022 ICME |
| [SgDN](https://link.springer.com/chapter/10.1007/978-981-99-8469-5_1) || 10.46 94.43 | 10.95 94.73 | 9.95 95.57 |  17.78 88.93 |  2023 PRCV |
| [DSCI](https://ieeexplore.ieee.org/abstract/document/10288514) || 5.48 97.39 | 8.00 97.50 | 5.71 98.44 |  12.59 94.57 |  2024 TIFS |

---

<a name="intra" />

### Intra test

<a name="C&R" />

#### CASIA-FASD & Replay-attack

| Method | Results From | CASIA-FASD <br> EER(%) | Repaly-Attack <br> EER(%) HTER(%)| Year Notes | Code |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [LBP](https://ieeexplore.ieee.org/document/6313548) |[Color LBP](https://ieeexplore.ieee.org/abstract/document/7351280)| 18.2 | 13.9 13.8 | 2012 BIOSIG |
| [LBP-TOP](https://link.springer.com/chapter/10.1007/978-3-642-37410-4_11) |[Color LBP](https://ieeexplore.ieee.org/abstract/document/7351280)| 10.6 | 7.80 7.60 | 2012 ACCVW |
| [LBP-TOP](https://link.springer.com/chapter/10.1007/978-3-642-37410-4_11) |[SURF-FV](https://ieeexplore.ieee.org/document/7748511)| 10.0 | 7.90 7.60 | 2012 ACCVW |
| [Motion-Mag](https://ieeexplore.ieee.org/document/6595861) |[Color LBP](https://ieeexplore.ieee.org/abstract/document/7351280)| 14.4 | 0.20 0.00 | 2013 CVPRW |
| [Color LBP](https://ieeexplore.ieee.org/abstract/document/7351280) || 6.20 | 0.40 2.90 | 2015 ICIP | [Code](https://github.com/Elroborn/Face-anti-spoofing-based-on-color-texture-analysis) |
| [New Color LBP](https://ieeexplore.ieee.org/document/7454730) || 3.20 | 0.00 3.50 | 2016 TIFS |
| [SURF-FV](https://ieeexplore.ieee.org/document/7748511) || 2.80 | 0.10 2.20 | 2017 SPL |
| [HASC](https://www.sciencedirect.com/science/article/abs/pii/S0952197623019723) || 2.85 | 1.67 2.67 | 2024 EAAI |
| [CNN](https://arxiv.org/abs/1408.5601) |[New Color LBP](https://ieeexplore.ieee.org/document/7454730)| 7.40 | 6.10 2.10 | 2014 arXiv |[Code1](https://github.com/mnikitin/Learn-Convolutional-Neural-Network-for-Face-Anti-Spoofing?tab=readme-ov-file) [Code2](https://github.com/RizhaoCai/Learn-Convolutional-Neural-Network-for-Face-Anti-Spoofing) [Code3](https://github.com/Elroborn/Learn-Convolutional-Neural-Network-for-Face-Anti-Spoofing_pytorch)|
| [Partial CNN](https://ieeexplore.ieee.org/document/7821013) || 4.50 | 2.90 6.10 | 2016 IPTA |
| [Patch CNN](https://ieeexplore.ieee.org/document/8272713) || 2.67 | 0.79 0.72 | 2017 IJCN | [Code](https://github.com/shicaiwei123/patch_based_cnn) |
| [DDGL](https://ieeexplore.ieee.org/document/7867821) || - |  - 0.00 | 2017 TIFS |
| [3D-CNN](https://ieeexplore.ieee.org/document/8335313) || 1.40 | 0.30  1.20 | 2018 TIFS |
| [Att Two Streem-CNN (ATS-CNN)](https://ieeexplore.ieee.org/document/8737949) || 3.14 | 0.13 0.25 | 2020 TIFS | [Code](https://github.com/Vincent9797/Attention-Based-Two-Stream-Convolutional-Networks-for-Face-Spoofing-Detection) |
| [Deep Transfer Net (DTN)](https://ieeexplore.ieee.org/document/9507460) || 1.34 | 0.06 0.02 | 2021 TIFS |
| [CIFL](https://ieeexplore.ieee.org/document/9336714) || 0.89 | - - | 2021 TIFS |
| [TSViT](https://www.sciencedirect.com/science/article/abs/pii/S1047320322000621) || 0.00 | 0.00 0.00 | 2022 JVCIR |

<a name="O" />

#### OULU-NPU

| Protocol | Method | Results From | APCER(%) | BPCER(%) | ACER(%) | Year Notes | Code |
| :---: | :---: | :---: | :---: |:---: | :---: | :---: | :---: |
| Pro.1 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 0.4 | 1.7 | 1.0 | 2020 CVPR | [Code](https://github.com/ZitongYu/CDCN) |
| Pro.1 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 0.4 | 0.0 | 0.2 | 2020 CVPR |
| Pro.1 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 1.7 | 0.8 | 1.3 | 2020 ECCV |
| Pro.1 | [ATS-CNN](https://ieeexplore.ieee.org/document/8737949) |[SAFPAD](https://ieeexplore.ieee.org/document/9650907)| 5.1 | 6.7 | 5.9 | 2020 TIFS | [Code](https://github.com/Vincent9797/Attention-Based-Two-Stream-Convolutional-Networks-for-Face-Spoofing-Detection) |
| Pro.1 | [CIFL](https://ieeexplore.ieee.org/document/9336714) || 3.8 | 2.9 | 3.4 | 2021 TIFS |
| Pro.1 | [NAS-FAS](https://ieeexplore.ieee.org/abstract/document/9252183) || 0.4 | 0 | 0.2 | 2021 TPAMI |
| Pro.1 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 0.6 | 1.2 | 0.9 | 2022 TIFS |
| Pro.1 | [TSViT](https://www.sciencedirect.com/science/article/abs/pii/S1047320322000621) || 1.7 | 0 | 0.9 | 2022 JVCIR |
| Pro.1 | [DSDG](https://ieeexplore.ieee.org/document/9641836) || 0.6 | 0 | 0.3 | 2022 TCSVT | [Code](https://github.com/JDAI-CV/FaceX-Zoo/tree/main/addition_module/DSDG) |
| Pro.1 | [DE-ViT](https://link.springer.com/chapter/10.1007/978-3-031-30111-7_29) || 0.9 | 0.1 | 0.5 | 2022 ICONIP |
| Pro.1 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 0.0 | 0.8 | 0.4 | 2022 TPAMI |
| Pro.1 | [AAD-FAS](https://ieeexplore.ieee.org/document/10208287) || 0.8 | 0 | 0.4 | 2023 CVPRW |
| Pro.1 | [GAIN](https://ieeexplore.ieee.org/abstract/document/10208551) || 0 | 0 | 0 | 2023 CVPRW |
| Pro.2 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 1.5 | 1.4 | 1.5 | 2020 CVPR |
| Pro.2 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 1.8 | 0.8 | 1.3 | 2020 CVPR |
| Pro.2 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 1.1 | 3.6 | 2.4 | 2020 ECCV |
| Pro.2 | [ATS-CNN](https://ieeexplore.ieee.org/document/8737949) || 7.6 | 2.2 | 4.9 | 2020 TIFS |
| Pro.2 | [CIFL](https://ieeexplore.ieee.org/document/9336714) || 3.6 | 1.2 | 2.4 | 2021 TIFS |
| Pro.2 | [NAS-FAS](https://ieeexplore.ieee.org/abstract/document/9252183) || 1.5 | 0.8 | 1.2 | 2021 TPAMI |
| Pro.2 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 2.2 | 2.6 | 2.4 | 2022 TIFS |
| Pro.2 | [TSViT](https://www.sciencedirect.com/science/article/abs/pii/S1047320322000621) || 0.8 | 1.3 | 1.1 | 2022 JVCIR |
| Pro.2 | [DSDG](https://ieeexplore.ieee.org/document/9641836) || 1.5 | 0.8 | 1.2 | 2022 TCSVT |
| Pro.2 | [DE-ViT](https://link.springer.com/chapter/10.1007/978-3-031-30111-7_29) || 3.0 | 0.3 | 1.7 | 2022 ICONIP |
| Pro.2 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 1.2 | 1.3 | 1.3 | 2022 TPAMI |
| Pro.2 | [AAD-FAS](https://ieeexplore.ieee.org/document/10208287) || 1.5 | 0.9 | 1.2 | 2023 CVPRW |
| Pro.2 | [GAIN](https://ieeexplore.ieee.org/abstract/document/10208551) || 0.8 | 0.8 | 0.8 | 2023 CVPRW |
| Pro.3 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 2.4±1.3 | 2.2±2.0 | 2.3±1.4 | 2020 CVPR |
| Pro.3 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 1.7±1.5 | 2.0±1.2 | 1.8±0.7 | 2020 CVPR |
| Pro.3 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 2.8±2.2 | 1.7±2.6 | 2.2±2.2 | 2020 ECCV |
| Pro.3 | [ATS-CNN](https://ieeexplore.ieee.org/document/8737949) || 3.9±2.8 | 7.3±1.1 | 5.6±1.6 | 2020 TIFS |
| Pro.3 | [CIFL](https://ieeexplore.ieee.org/document/9336714) || 3.8±1.3 | 1.1±1.1 | 2.5±0.8 | 2021 TIFS |
| Pro.3 | [NAS-FAS](https://ieeexplore.ieee.org/abstract/document/9252183) || 2.1±1.3 | 1.4±1.1 | 1.7±0.6 | 2021 TPAMI |
| Pro.3 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 2.2±2.0 | 2.8±3.7 | 2.5±2.6 | 2022 TIFS |
| Pro.3 | [TSViT](https://www.sciencedirect.com/science/article/abs/pii/S1047320322000621) || 2.4±2.6 | 1.4±2.2 | 1.9±1.3 | 2022 JVCIR |
| Pro.3 | [DSDG](https://ieeexplore.ieee.org/document/9641836) || 1.2±0.8 | 1.7±3.3 | 1.4±1.5 | 2022 TCSVT |
| Pro.3 | [DE-ViT](https://link.springer.com/chapter/10.1007/978-3-031-30111-7_29) || 1.4±1.0 | 1.9±3.5 | 1.7±1.5 | 2022 ICONIP |
| Pro.3 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 1.7±1.4 | 2.2±3.5 | 1.9±2.3 | 2022 TPAMI |
| Pro.3 | [AAD-FAS](https://ieeexplore.ieee.org/document/10208287) || 1.2±1.2 | 2.2±1.8 | 1.7±1.6 | 2023 CVPRW |
| Pro.3 | [GAIN](https://ieeexplore.ieee.org/abstract/document/10208551) || 0.9±0.8 | 0.8±0.8 | 0.9±0.8 | 2023 CVPRW |
| Pro.4 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 4.6±4.6 | 9.2±8.0 | 6.9±2.9 | 2020 CVPR |
| Pro.4 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 4.2±3.4 | 5.8±4.9 | 5.0±2.9 | 2020 CVPR |
| Pro.4 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 5.4±2.9 | 3.3±6.0 | 4.4±3.0 | 2020 ECCV |
| Pro.4 | [ATS-CNN](https://ieeexplore.ieee.org/document/8737949) || 11.3±3.9 | 9.7±4.8 | 9.8±4.2 | 2020 TIFS |
| Pro.4 | [CIFL](https://ieeexplore.ieee.org/document/9336714) || 5.9±3.3 | 6.3±4.7 | 6.1±4.1 | 2021 TIFS |
| Pro.4 | [NAS-FAS](https://ieeexplore.ieee.org/abstract/document/9252183) || 4.2±5.3 | 1.7±2.6 | 2.9±2.8 | 2021 TPAMI |
| Pro.4 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 6.6±7.1 | 6.0±5.5 | 6.3±5.9 | 2022 TIFS |
| Pro.4 | [TSViT](https://www.sciencedirect.com/science/article/abs/pii/S1047320322000621) || 7.4±5.0 | 1.2±2.2 | 4.3±1.9 | 2022 JVCIR |
| Pro.4 | [DSDG](https://ieeexplore.ieee.org/document/9641836) || 2.1±1.0 | 2.5±4.2 | 2.3±2.3 | 2022 TCSVT |
| Pro.4 | [DE-ViT](https://link.springer.com/chapter/10.1007/978-3-031-30111-7_29) || 5.7±4.8 | 1.5±3.2 | 3.5±3.4 | 2022 ICONIP |
| Pro.4 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 2.3±3.6 | 4.2±5.4 | 3.6±4.2 | 2022 TPAMI |
| Pro.4 | [AAD-FAS](https://ieeexplore.ieee.org/document/10208287) || 4.9±3.2 | 5.7±6.2 | 5.3±2.9 | 2023 CVPRW |
| Pro.4 | [GAIN](https://ieeexplore.ieee.org/abstract/document/10208551) || 4.6±2.2 | 4.2±1.9 | 4.4±2.0 | 2023 CVPRW |

<a name="S" />

#### SiW

| Protocol | Method | Results From | APCER(%) | BPCER(%) | ACER(%) | Year Notes | Code |
| :---: | :---: | :---: | :---: |:---: | :---: | :---: | :---: |
| Pro.1 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 0.07 | 0.17 | 0.12 | 2020 CVPR |[Code](https://github.com/ZitongYu/CDCN) |
| Pro.1 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 0.07 | 0.17 | 0.12 | 2020 CVPR |
| Pro.1 | [HMP](https://link.springer.com/chapter/10.1007/978-3-030-58571-6_33) || 0.55 | 0.17 | 0.36 | 2020 ECCV |
| Pro.1 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 0.07 | 0.50 | 0.28 | 2020 ECCV |
| Pro.1 | [STDN](https://link.springer.com/chapter/10.1007/978-3-030-58523-5_24) || 0.00 | 0.00 | 0.00 | 2020 ECCV | [Code](https://github.com/yaojieliu/ECCV20-STDN) |
| Pro.1 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 0.89 | 0.97 | 0.93 | 2022 TIFS |
| Pro.1 | [DSFL](https://ieeexplore.ieee.org/document/9706972) || 0.00 | 0.00 | 0.00 | 2022 WACV |
| Pro.1 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 0.00 | 0.00 | 0.00 | 2022 TPAMI |
| Pro.2 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 0.00±0.00 | 0.13±0.09 | 0.06±0.04 | 2020 CVPR |
| Pro.2 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 0.00±0.00 | 0.09±0.10 | 0.04±0.05 | 2020 CVPR |
| Pro.2 | [HMP](https://link.springer.com/chapter/10.1007/978-3-030-58571-6_33) || 0.08±0.17 | 0.15±0.00 | 0.11±0.08 | 2020 ECCV |
| Pro.2 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 0.08±0.17 | 0.13±0.09 | 0.10±0.04 | 2020 ECCV |
| Pro.2 | [STDN](https://link.springer.com/chapter/10.1007/978-3-030-58523-5_24) || 0.00±0.00 | 0.00±0.00 | 0.00±0.00 | 2020 ECCV |
| Pro.2 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 0.39±0.31 | 0.29±0.23 | 0.34±0.27 | 2022 TIFS |
| Pro.2 | [DSFL](https://ieeexplore.ieee.org/document/9706972) || 0.00±0.00 | 0.00±0.00 | 0.00±0.00 | 2022 WACV |
| Pro.2 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 0.00±0.00 | 0.00±0.00 | 0.00±0.00 | 2022 TPAMI |
| Pro.3 | [CDCN](https://ieeexplore.ieee.org/document/9156660) || 1.67±0.11 | 1.76±0.12 | 1.71±0.11 | 2020 CVPR |
| Pro.3 | [CDCN++](https://ieeexplore.ieee.org/document/9156660) || 1.97±0.33 | 1.77±0.10 | 1.90±0.15 | 2020 CVPR |
| Pro.3 | [HMP](https://link.springer.com/chapter/10.1007/978-3-030-58571-6_33) || 2.55±0.89 | 2.34±0.47 | 2.45±0.68 | 2020 ECCV |
| Pro.3 | [DRL](https://link.springer.com/chapter/10.1007/978-3-030-58529-7_38) || 9.35±6.14 | 1.84±2.60 | 5.59±4.37 | 2020 ECCV |
| Pro.3 | [STDN](https://link.springer.com/chapter/10.1007/978-3-030-58523-5_24) || 8.3±3.3 | 7.5±3.3 |  7.9±3.3 | 2020 ECCV |
| Pro.3 | [SAFPAD](https://ieeexplore.ieee.org/document/9650907) || 8.26±1.98 | 8.12±2.17 | 8.19±2.24 | 2022 TIFS |
| Pro.3 | [DSFL](https://ieeexplore.ieee.org/document/9706972) || 4.77±5.04 | 2.44±2.74 | 3.58±3.93 | 2022 WACV |
| Pro.3 | [STDN+](https://ieeexplore.ieee.org/document/9779478) || 13.1±9.4 | 1.6±0.6 | 7.4±4.3 | 2022 TPAMI |
