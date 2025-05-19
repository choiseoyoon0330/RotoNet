# RotoNet: Rotoscoping-Based Artistic Style Transfer Networks
> **Abstract:** RotoNet is a novel deep-learning framework designed for automated rotoscoping-based artistic style transfer in videos. Unlike conventional video style transfer approaches that focus on general stylization, RotoNet captures the distinctive aesthetic qualities of rotoscoping animation-precision in motion tracing, line expressiveness, and artistic interpretation of human movement. 
## 1. Introduction


## 2. Method
### 2.1. Object Tracking & Segmentation
For object tracking and segmentation, I used [SAMURAI](https://github.com/yangchris11/samurai). SAMURAI offers high-quality mask prediction, supports multi-object tracking, and leverages region-level attention to maintain accurate segmentation across video frames. Another advantage of SAMURAI is that it supports **zero-shot** video object segmentation. With just a prompt on the first frame-such as a point, box, or mask-SAMURAI can segment and track the target object throughout the entire video without any additional training.

### 2.2. Style Transfer

## 3. Experiment
| Original            | Object Tracking & Segmentation              | 
|----------------------------|---------------------------|
|<img src="https://github.com/user-attachments/assets/22dcbc6d-9b56-4c08-a7fa-c1dae10c6e75" width="400"/>|<img src="https://github.com/user-attachments/assets/749f8815-a52a-4fb0-aefd-8b4d8a55bc4f" width="400"/>|

| Binary Mask            | Final             | 
|----------------------------|---------------------------|
|<img src="https://github.com/user-attachments/assets/4594b6d9-c3c0-4247-b9f8-f4c6251e6500" width="400"/>|<img src="https://github.com/user-attachments/assets/f4b39b6c-06cc-4d7d-a67c-09ceae0bed09" width="400"/>|


## 4. Conclusion

## Acknowledgement
This is the project for the course &lt;Introduction to Generative AI>.
- [SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory](https://github.com/yangchris11/samurai)
- [Neural Style Transfer Transition Video Processing](https://github.com/westgarthb/style-transfer-video-processor)
