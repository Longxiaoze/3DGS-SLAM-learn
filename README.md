# 3DGS-SLAM-learn

This project is used for my learning of 3DGS-based SLAM.[English](https://github.com/Longxiaoze/3DGS-SLAM-learn/tree/main)

### 3DGS related works
#### [1]  3D Gaussian Splatting for Real-Time Radiance Field Rendering
- **🔗 Link**：[[Paper](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf)] [[code/project page](https://github.com/graphdeco-inria/gaussian-splatting)]
- ![3dgs](https://github.com/Longxiaoze/3DGS-SLAM-learn/blob/main/imgs/3dgs.png)
- **📝 Explanation**：🔥 开山作 first work
- 
#### [2]  2D Gaussian Splatting for Geometrically Accurate Radiance Fields
- **🔗 Link**：[[Paper](https://arxiv.org/pdf/2403.17888)] [[code/project page](https://github.com/hbb1/2d-gaussian-splatting)]
- **📝 Explanation**：🔥 使用2DGS，将椭圆球形的3DGS化为2D椭圆形片面，可以有效提取网格图
- 
### 3DGS-based SLAM related works
#### [1]  SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM
- **🔗 Link**：[[Paper](https://arxiv.org/pdf/2312.02126.pdf)] [[code/project page](https://github.com/spla-tam/SplaTAM)]
- **📝 Explanation**：🔥 首个开源的3DGS-based SLAM系统

#### [2]  Gaussian Splatting SLAM
- **🔗 Link**：[[Paper](https://arxiv.org/abs/2312.06741)] [[code/project page](https://github.com/muskie82/MonoGS)]
- **📝 Explanation**：🔥 首批3DGS-based SLAM系统

#### [3]  GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting
- **🔗 Link**：[[Paper](https://arxiv.org/abs/2312.06741)] [[code/project page](https://github.com/muskie82/MonoGS)]
- **📝 Explanation**：🔥 首批3DGS-based SLAM系统

#### [4]  RGBD GS-ICP SLAM
- **🔗 Link**：[[Paper](https://arxiv.org/abs/2403.12550)] [[code/project page](https://github.com/Lab-of-AI-and-Robotics/GS_ICP_SLAM)]
- **📝 Explanation**：🔥 首批3DGS-based SLAM系统 (区别于1-3，这个工作获得pose不是通过优化的方法，而是传统的点云匹配方法)
