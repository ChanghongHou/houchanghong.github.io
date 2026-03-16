# 个人简介 

**姓名**：侯长鸿\
**单位**：中国矿业大学（北京）、中国自然资源航空物探遥感中心\
**研究方向**：地质灾害隐患智能识别，地质灾害预警智能体，多模态大模型，雷达遥感，地理信息系统

## 项目经验

1.  时空信息协同的崩滑隐患关联要素智能识别技术研发
2.  广域重大地质灾害隐患综合遥感识别技术研发
3.  工程重大地质灾害星空监测预警关键技术与装备研究

## 个人能力

1.  编程分析： 熟练掌握 Python，具备扎实的编程能力。
2.  空间制图： 熟悉 ArcGIS、QGIS 等 GIS 平台，擅长空间分析与地图制图。
3.  算法模型： 熟练掌握传统深度学习算法和大模型算法。掌握数据预处理，模型训练，预测推理，结果可视化等全流程代码实现能力。掌握参数微调，RAG，MCP等大模型智能体全栈技术。
4.  语言写作： 具备良好的英文文献阅读、科研写作、沟通汇报能力。

------------------------------------------------------------------------

# 深度学习算法开发 

基于视觉基础模型的滑坡语义分割迁移学习方法：TransLandSeg

**技术背景**：Segment Anything Model (SAM)作为图像分割领域的Foundation Model具有出色的性能。然而，训练SAM的数据为自然图像，缺乏遥感影像，这使得SAM在遥感影像中识别滑坡语义信息是一个挑战。

**解决方案**：为了解决SAM在滑坡分割任务中的适配问题，本文基于SAM提出了TransLandSeg模型。

**核心创新**： - 设计自适应迁移学习(ATL)模块，仅需1.3%的SAM参数即可实现功能迁移 - 在TransLandSeg模型中，设计了一个即插即用的瓶颈模块Adaptive Transfer Learning（ATL），将ATL模块插入到SAM的image encoder中 - 训练时冻结SAM中image encoder的参数，只对ATL模块和mask decoder进行训练

**技术优势**： - MIoU比其他SOTA语义分割模型增加了1.48%-13.01% - 在毕节滑坡数据集和Landslide4Sense数据集上分别达到88.1%、75.99%的MIoU - 训练参数只有其他模型的5-10%，极大缩短训练时间

**模型结构图**： ![](https://pic3.zhimg.com/80/v2-0325feebe89b6df16fa8e690ba3fe68a_1440w.webp)

**实验结果对比**： ![](https://pic1.zhimg.com/80/v2-0f225fea2bf30c13080e1341201b59e0_1440w.webp) ![](https://pic4.zhimg.com/80/v2-5904d486cb1f5503aeaa2a6750422a49_1440w.webp)

**性能对比图**： ![](https://pic1.zhimg.com/80/v2-3aaeee5051647e9ec1cf5eafc4253034_1440w.webp) ![](https://pic3.zhimg.com/80/v2-596ab1bf763c5340c2a21e6f821a2d4c_1440w.webp)

**ATL结构优化**： ![](https://picx.zhimg.com/80/v2-30823351706b327d8ae7777abee90089_1440w.webp)

**实验数据集**： - 毕节滑坡数据集: [Link](http://gpcv.whu.edu.cn/data/Bijie_pages.html) - Landslide4Sense 数据集: [Link](https://github.com/iarai/Landslide4Sense-2022)

------------------------------------------------------------------------

# 全流程滑坡识别智能体

**项目简介**：开发全流程滑坡识别智能体，实现从数据输入到结果输出的智能化处理流程。

**系统架构**： ![](https://pic1.zhimg.com/80/v2-0705d56c2aebfb639076252b364c3132_1440w.webp)

**演示视频**：[点击B站链接观看](https://www.bilibili.com/video/BV1HLwTzVETM?t=228.5) - 详细效果展示

**功能特点**： - 自动化数据读取 - 智能识别滑坡 - 智能化可视化结果展示和报告生成

------------------------------------------------------------------------

# 学术论文成果 

发表论文

**论文标题**：A Transfer Learning Approach for Landslide Semantic Segmentation Based on Visual Foundation Model\
**期刊**：IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (JSTARS)\
**发表时间**：2025年\
**DOI**：10.1109/JSTARS.2025.3559884\
**论文链接**：[IEEE Xplore](https://ieeexplore.ieee.org/document/10962290?source=authoralert)

**作者**：侯长鸿，于峻川\*，葛大庆，杨柳，郗来典，庞云璇\
**单位**：中国矿业大学（北京）、中国自然资源航空物探遥感中心

开源代码

**GitHub仓库**：[TransLandSeg](https://github.com/JunchuanYu/TransLandSeg)

------------------------------------------------------------------------

# 联系方式

**姓名**：侯长鸿\
**邮箱**：changhong_cumtb\@163.com\
**电话**：18811320582\
**研究方向**：人工智能与地质灾害隐患识别

*后续将持续更新，请关注*\
*最后更新：2026年3月15日*
