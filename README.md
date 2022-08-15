# Learning Enriched Features for Real Image Restoration and Enhancement

**模型描述**：MIRNet模型由卷积层（Conv）和多个递归残差组（RRGs）构成，其中卷积层用用于提取输入数据的低层特征，然后提取到的这些特征图经过RRGs产生深度特征。其中每个RRG由多个多尺度残差快（MRB）构成，在MRB中一个卷积流变成多个卷积流，并通过SKFF模块实现多分辨率的信息交流；通过DAU捕获空间和通道维度的上下文信息，最终又聚合成一个卷积流。


**参考代码在SIDD数据集上的验证结果**：PSNR＝39.72　　SSIM＝0.9192
