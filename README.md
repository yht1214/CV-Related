# Project-List

It is the page that records my projects. If you are interested in my project or have some ideas, you are welcome to discuss them with me.

## IDOL: Meeting Diverse Distribution Shifts with Prior Physics for Tropical Cyclone Multi-Task Estimation

This work was accepted by NeurIPS-2025. [[Code]](https://github.com/Zjut-MultimediaPlus/IDOL)
[[Paper]](https://neurips.cc/virtual/2025/loc/san-diego/poster/119878) 

### Abstract

<p align="justify">
Tropical Cyclone (TC) estimation aims to accurately estimate various TC attributes in real time. However, distribution shifts arising from the complex and dynamic nature of TC environmental fields, such as varying geographical conditions and seasonal changes, present significant challenges to reliable estimation. Most existing methods rely on multi-modal fusion for feature extraction but overlook the intrinsic distribution of feature representations, leading to poor generalization under out-of-distribution (OOD) scenarios. To address this, we propose an effective Identity Distribution-Oriented Physical Invariant Learning framework (IDOL), which imposes identity-oriented constraints to regulate the feature space under the guidance of prior physical knowledge, thereby dealing with distribution variability with physical invariance. Specifically, the proposed IDOL employs the wind field model and dark correlation knowledge of TC to model task-shared and task-specific identity tokens. These tokens capture task dependencies and intrinsic physical invariances of TC, enabling robust estimation of TC wind speed, pressure, innercore, and outer-core size under distribution shifts. Extensive experiments conducted on multiple datasets and tasks demonstrate the outperformance of the proposed IDOL, verifying that imposing identity-oriented constraints based on prior physical knowledge can effectively mitigate diverse distribution shifts in TC estimation.
</p>

## Phy-CoCo: Physical Constraint-Based Correlation Learning for Tropical Cyclone Intensity and Size Estimation

This work was accepted by ECAI-2024. [[Code]](https://github.com/Zjut-MultimediaPlus/Phy-CoCo)
[[Paper]](https://ebooks.iospress.nl/doi/10.3233/FAIA240744)

### Abstract

<p align="justify">
Tropical Cyclone (TC) estimation aims to estimate various attributes of TC in real-time to alleviate and prevent disasters caused by violent TCs. As artificial intelligence technology advances, various deep learning-based multi-task estimation approaches have been proposed. However, most of them only focus on extracting common features of tasks, disregarding potential negative transfer and task interactions between different tasks. This paper is thus motivated to propose a Physical Constraint-based Correlation (Phy-CoCo) learning framework from the perspective of Multi-Task Learning (MTL). Specifically, for task-specific feature learning, we introduce Correlation Modeling (CoM) based on Centrally Expanded Pooling (CEP). Furthermore, for cross-task interaction, we propose a Multi-Domain Recurrent Convolution (MDRC) module to incorporate physical constraints into MTL. These physical constraints enable the transformation of different task features by simulating the physical relations among different attributes of TC. Lastly, in combination with a task-shared network that leverages the hybrid fusion of multi-modal data, our MTL framework accurately estimates various TC attributes. Extensive experiments conducted on our constructed dataset demonstrate that the proposed Phy-CoCo outperforms previous methods in TC estimation in terms of estimation error, verifying the potential of the physics-incorporated MTL model.
</p>

## Estimating Tropical Cyclone Maximum Wind Speed and Radius Using a Multi-Modal Hybrid Guided Network

This work was under minor revision in the Journal of Geophysical Research: Atmospheres. [[code]](https://github.com/Zjut-MultimediaPlus/MHG-Net)

### Abstract

<p align="justify">
Tropical cyclones (TCs) are destructive weather systems that can trigger flooding, landslides, and other severe hazards. Accurate estimation of key TC attributes is critical for disaster risk management. In particular, the maximum sustained wind speed (MSW) and radius of maximum wind (RMW) are fundamental parameters for operational forecasting and wind-field modeling. However, existing approaches struggle to capture and fuse the diverse physical information embedded in multi-modal TC data. We propose MHG-Net, a multi-task deep learning framework that integrates satellite imagery with auxiliary physical 23
factors via soft parameter sharing and correlation graph embedding. This design enables effective inter-task collaboration while explicitly modeling underlying physical correlations essential for accurate TC estimation. Using Himawari-8/9 satellite observations and best-track data from IBTrACS, MHG-Net achieves low mean absolute errors of 6.55 knots for MSW and 6.68 nmi for RMW. Beyond performance gains, the learned correlation graphs and attribution analyses provide insights into how different physical factors influence TC attributes' evolution. 
</p>
