# Image Batch Processing For Porous Media

Author: Feng Junxi

Affiliation: College of Electronics and Information Engineering, Sichuan University, Chengdu 610065, China

This is an image batch processing software for porous media, including commonly used functions:

============2019-11-15 update============

Author: Feng Junxi

- Add batch calculation of 2D images and 3D images, supporting statistical functions and local porosity distribution (增加2D和3D图像的统计参数批量计算，支持多种统计函数和局部孔隙度分布)

- Update function of fast calculation of 3D  local porosity distribution using integral image，achieving more than 800 speedup factor(更新三维局部孔隙度分布的快速计算，速度提升超800倍)

  

============first commit============

- 2D and 3D Porosity calculation (二维和三维的孔隙度计算)
- 2D  and 3D several statistical functions (二维和三维形态刻画函数)
- 2D and 3D local porosity distribution (二维和三维局部孔隙度)
- Image  transformation, including resize, crop and segmentation (图像变换包括缩放，裁剪，分割)
- Image format conversion   （图像格式转换）
- Image shuffle （图像随机打乱输出）
- Sampling ratio calculation （采样率计算）
- 2D and 3D mathematical morphology， including dilation, erosion, close and open (二维和三维的数学形态学，包括膨胀，腐蚀，闭运算和开运算）
- Choosing training image   （选择训练图像）
- Image uniting for creating paired image data   （多组图像合并，制作配对数据集）
