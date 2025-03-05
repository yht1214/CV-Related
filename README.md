# Project-List

It is the page that records my projects. If you are interested in my project or have some ideas, you are welcome to discuss them with me.

## MHG-Net: Multi-Modal Hybrid Guided Network for Tropical Cyclone Intensity and Inner-core Size Estimation

This work was under minor revision in the Journal of Geophysical Research: Atmospheres. [[code]](https://github.com/Zjut-MultimediaPlus/MHG-Net)

### Abstract

Tropical Cyclone (TC) is a disastrous weather event that can cause considerable destruction, such as river flooding, mudslides, and other disasters. As a result, the government needs accurate TC estimation methods to formulate appropriate policies. TC structure is usually divided into inner-core and outer-core regions, with the Radius of Maximum Winds (RMW) and 34-knots Winds (R34) serving as their typical indicators. Given the significant importance of inner-core wind radius for TCs, particularly regarding intensity and disaster forecasting, this study proposes a Multi-Modal Hybrid Guided Network (MHG-Net) to estimate TC Maximum Sustained Wind speed (MSW) and RMW. The proposed MHGNet, consisting of a CNN Backbone (Share-Net), TC Development Network (Dev-Net), and Multi-Modal Hybrid Guided structures (MHG), realize effective fusion of real-time satellite data and auxiliary information of TC. We performed experiments on the observation area of the Himawari-8/9 satellite, using The International Best Track Archive for Climate Stewardship (IBTrACS) datasets to verify the MHG-Net effectiveness; we obtained low Mean Absolute Error (MAE) in TC MSW and RMW estimation, respectively. Utilizing spatial-temporal and development information about TC at different stages, our approach introduces a physical information-guided learning method for TC estimation and
a new perspective on complex interactions between TC and their development information.

## Phy-CoCo: Physical Constraint-Based Correlation Learning for Tropical Cyclone Intensity and Size Estimation

This work was accepted by ECAI-2024. [[Code]](https://github.com/Zjut-MultimediaPlus/Phy-CoCo)
[[Paper]](https://ebooks.iospress.nl/doi/10.3233/FAIA240744)

### Abstract

Tropical Cyclone (TC) estimation aims to estimate various attributes of TC in real-time to alleviate and prevent disasters caused by violent TCs. As artificial intelligence technology advances, various deep learning-based multi-task estimation approaches have been proposed. However, most of them only focus on extracting common features of tasks, disregarding potential negative transfer and task interactions between different tasks. This paper is thus motivated to propose a Physical Constraint-based Correlation (Phy-CoCo) learning framework from the perspective of Multi-Task Learning (MTL). Specifically, for task-specific feature learning, we introduce Correlation Modeling (CoM) based on Centrally Expanded Pooling (CEP). Furthermore, for cross-task interaction, we propose a Multi-Domain Recurrent Convolution (MDRC) module to incorporate physical constraints into MTL. These physical constraints enable the transformation of different task features by simulating the physical relations among different attributes of TC. Lastly, in combination with a task-shared network that leverages the hybrid fusion of multi-modal data, our MTL framework accurately estimates various
TC attributes. Extensive experiments conducted on our constructed dataset demonstrate that the proposed Phy-CoCo outperforms previous methods in TC estimation in terms of estimation error, verifying the potential of the physics-incorporated MTL model.

## Tropical Cyclones Tracking Based on Satellite Cloud Images: Database and Comprehensive Study

This work was under review at a CCF-A conference (2025). 

### Abstract

The objective of Tropical Cyclone (TC) estimation is to estimate various attributes of TC in realtime accurately. However, multiple distribution shifts caused by TC’s polytropic environmental fields, including different geographical conditions and seasonal changes, pose a significant challenge to accurate TC estimation. Since existing deep learning models estimate TC solely from the perspective of multi-modal fusion, they overlook the above challenge, making it difficult to generalize well when confronted with different distributions in TC data. Therefore, this paper introduces an effective Identity Distribution-oriented Physical invariant learning framework (IDPil), which incorporates prior physical knowledge in the form of graphs, dealing with distribution variability with physical invariance. Specifically, the proposed IDPil employs the wind field model and dark correlation knowledge of TC to regulate the distribution of features for intrinsic invariant learning, facilitating the accurate estimation of TC wind speed, pressure, inner-core, and outer-core size. Extensive experiments conducted on multiple datasets and tasks demonstrate the outperformance of the proposed IDPil, verifying that the corporation of prior physics by invariant learning could meet diverse distribution shifts.
