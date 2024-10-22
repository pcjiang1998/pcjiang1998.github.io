---
permalink: /zh
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>
.tag {
    background-color: #ffccbc; /* 淡橘红色背景 */
    color: black; /* 黑色字体 */
    padding: 3px 6px; /* 更小的内边距 */
    border-radius: 10px; /* 圆角 */
    font-size: 12px; /* 更小的字体大小 */
    display: inline-block; /* 允许在文本后方 */
    margin-left: 5px; /* 标签与文本之间的间距 */
}
</style>

<span class='anchor' id='about-me'></span>
# 😉 自我评价

本人目前于*南京信息工程大学·计算机学院*攻读**博士（硕博连读）**。本人具有较强的科研能力和开发能力，掌握大部分常用的技术，具有一定的科研成果和开发经历。

本人研究方向为**演化深度学习** (Evolutionary Deep Learning)，主要包括**神经网络架构搜索** (Neural architecture search，NAS) 和**网络剪枝**(Network Pruning)。


<span class='anchor' id='-educations'></span>
# 📖 教育经历
- *2022.06 - now*，南京信息工程大学，计算机科学与技术，博士（硕博连读）
- *2020.09 - 2022.06*，南京信息工程大学，软件工程，硕士 
- *2016.09 - 2020.06*，南京信息工程大学，软件工程，本科


<span class='anchor' id='-awards'></span>
# 🎖 获奖
### 博士期间
- *2024.10* 南京信息工程大学研究生“浦芯”精英奖学金 **<font color="red">全校集成电路相关工科研究生共评选13人</font>**
- *2024.10* 南京信息工程大学“研究生优秀奖学金、学业奖学金” **二等奖** **<font color="red">（2/8，<5%）</font>**
- *2023.12* 2022-2023学年研究生“奇安信奖学金”
- *2023.12* 南京信息工程大学“**三好研究生**”
- *2023.11* 南京信息工程大学“研究生优秀奖学金、学业奖学金” **一等奖** **<font color="red">（1/8，<5%）</font>**
- *2022.11* 南京信息工程大学“研究生优秀新生奖学金、学业奖学金” **二等奖**

### 硕士期间
- *2021.12* 南京信息工程大学“研究生优秀奖学金、学业奖学金” **一等奖** **<font color="red">（3/68，<5%）</font>**
- *2021.12* 南京信息工程大学“**三好研究生**”
- *2020.12* 南京信息工程大学“研究生优秀新生奖学金、学业奖学金” **二等奖**

### 本科期间
- *2020.06* 南京信息工程大学“**优秀毕业生**”
- *2016.09 ~ 2020.06* 一次获**院级**“三好学生”、一次获**校级**”三好学生”
- *2016.09 ~ 2020.06* 多次获**校级**学业奖学金
- *2018.04* 第九届“蓝桥杯省级C/C++程序设计B组”**二等奖**
- *2017.11* 南京信息工程大学第八届程序设计大赛中荣获**三等奖**


<span class='anchor' id='-achievements'></span>
# 📝 科研成果（更新于2024/9/2）
### 正在审理/修改
- 📜 **论文：****Pengcheng Jiang**, Yu Xue, Zhongyuan Hu, Bing Xue, Mengjie Zhang. Surrogate-assisted performance ranking for evolutionary deep neural architecture search[J]. *IEEE Transactions on Knowledge and Data Engineering* (初稿修改中) [[录用后公开PDF]]()<span class="tag">Trans</span><span class="tag">SCI</span><span class="tag">中科院一区TOP</span><span class="tag">JCR Q1</span><span class="tag">IF：8.9</span><span class="tag">CCF-A</span>
- 📜 **论文：****Pengcheng Jiang**, Yu Xue, Ferrante Neri. Score predictor-assisted evolutionary neural architecture search[J]. *IEEE Transactions on Emerging Topics in Computational Intelligence* **(2024年8月16日提交大修修改稿，Trans，SCI，中科院三区，JCR分区Q1，IF：5.3)** [[录用后公开PDF]]()
- 📜 **论文：**Yu Xue, **Pengcheng Jiang**. Multi-objective self-adaptive PSO for classification in intrusion detection with high-dimensional, unbalanced and cost-sensitive data[J]. *IEEE Transactions on Industrial Informatics* **(2024年8月16日投稿，Trans，SCI，中科院一区TOP，JCR分区Q1，IF：12.3，CCF-C)** [[录用后公开PDF]]()
- 📜 **论文：**Yu Xue, **Pengcheng Jiang**, Zhenman Zhang, Mengchu Zhou. Neural architecture search based on a surrogate model with similarity measurement[J]. *IEEE Transactions on Cybernetics* **(除老师外一作，2024年7月10日投稿，Trans，SCI，中科院一区TOP，JCR分区Q1，IF：9.4，CCF-B)** [[录用后公开PDF]]()
- 📜 **论文：****Pengcheng Jiang**, Yu Xue, Ferrante Neri. Multi-objective neural architecture search as bilevel optimisation: A novel surrogate approach[J]. *IEEE Transactions on Evolutionary Computation* **(2024年7月29日投稿，Trans，SCI，中科院一区TOP，JCR分区Q1，IF：11.7，CCF-B)** [[录用后公开PDF]]()
<!--  - 📜 **论文:** Yu Xue, **Pengcheng Jiang**, Ferrante Neri, Ziming Yuan,"CoAM: Confidence attention module for deep convolutional,". **(修改中)**[[录用后公开PDF]]()   -->


### 已发表/出版
- 📜 **论文：****Pengcheng Jiang**, Ferrante Neri, Yu Xue, Ujjwal Maulik. A generalised attention mechanism to enhance the accuracy performance of neural networks[J]. *International Journal of Neural Systems*, 2024. [DOI: 10.1142/S0129065724500631](https://doi.org/10.1142/S0129065724500631)  **(SCI，中科院二区，JCR分区Q1，IF2024：6.6)** [[下载PDF]](https://www.worldscientific.com/doi/abs/10.1142/S0129065724500631)
- 📜 **论文：****蒋鹏程**,薛羽.基于排序得分预测的演化神经架构搜索方法[J].*计算机学报*, 2024, 47(11), 2522-2535. **(中文核心，CCF-A)** [[下载PDF]](https://link.cnki.net/urlid/11.1826.TP.20240906.1023.002)
- 📜 **论文：****Pengcheng Jiang**, Yu Xue, Ferrante Neri, Mohamed Wahib. Surrogate-assisted evolutionary neural architecture search with isomorphic training and prediction[C]//*2024 International Conference on Intelligent Computing (ICIC)*. Tianjing, China: Springer Nature, 2024, 14863: 191–203. [DOI: 10.1007/978-981-97-5581-3_16](https://doi.org/10.1007/978-981-97-5581-3_16) **(国际会议，CCF-C)** [[下载PDF]](https://link.springer.com/content/pdf/10.1007/978-981-97-5581-3_16.pdf)
- 📜 **论文：****Pengcheng Jiang**, Yu Xue, Ferrante Neri. Continuously evolving dropout with multi-objective evolutionary optimisation[J]. *Engineering Applications of Artificial Intelligence*, 2023, 124: 106504. [DOI: 10.1016/j.engappai.2023.106504](https://doi.org/10.1016/j.engappai.2023.106504) **(SCI，2023中科院一区TOP，JCR分区Q1，IF2023：7.5，CCF-C，被引次数4)** [[下载PDF]](http://42.192.94.151/cv_files/1-s2.0-S0952197623006887-main.pdf)
- 📜 **论文：****Pengcheng Jiang**, Yu Xue, Ferrante Neri. Convolutional neural network pruning based on multi-objective feature map selection for image classification[J]. *Applied Soft Computing*, 2023: 110229. [DOI: 10.1016/j.asoc.2023.110229](https://doi.org/10.1016/j.asoc.2023.110229) **(SCI，2022中科院一区TOP，JCR分区Q1，IF2023：7.2，被引次数19)** [[下载PDF]](http://42.192.94.151/cv_files/1-s2.0-S1568494623002478-main.pdf)
- 📜 **论文：**Yu Xue, **Pengcheng Jiang**, Ferrante Neri, Jiayu Liang. A multi-objective evolutionary approach based on graph-in-graph for neural architecture search of convolutional neural networks[J]. *International Journal of Neural Systems*, 2021, 31(09): 2150035. [DOI: 10.1142/S0129065721500350](https://doi.org/10.1142/S0129065721500350) **(除老师外一作，SCI，2021年中科院一区TOP，JCR分区Q1，IF2021：6.325，被引次数101)** [[下载PDF]](http://42.192.94.151/cv_files/s0129065721500350.pdf)
- 📜 **论文：****Pengcheng Jiang**, Yu Xue. A distributed secret sharing method with QR code based on information hiding[J]. *Journal of Cyber Security*, 2021, 3(4): 217-225. [DOI: 10.32604/jcs.2021.026022](https://doi.org/10.32604/jcs.2021.026022) **(英文外刊)** [[下载PDF]](http://42.192.94.151/cv_files/03.pdf)
- 📰 **软著：**安全二维码生成系统V1.0（2021SR0885987）
- 📜 **论文：****蒋鹏程**,熊礼治,韩啸.一种基于内容保护与优化识别的二维码方案[J].*软件导刊*,2019,18(02):119-122. **(CCF计算领域高质量期刊T3，中文SCD科学引文数据库)** [[下载PDF]](http://42.192.94.151/cv_files/02.pdf) [[知网链接]](https://kns.cnki.net/kcms2/article/abstract?v=YoFA4grnCX4wQYh6LuLmGYuLa1BxBkb1fndLONcISVT6xQjZ2ehzb07VH4dlH6qU55qtfZOmI_7nJUZBRhg9pJkPuhodvDWKt5Hu2g6ptgvHWFVWO5AkTwzDm89Lip7CLVjmveick9ctD47fOuQ-bg==)
- 📜 **论文：**韩啸,熊礼治,**蒋鹏程**,宋婷婷.一种密文图像安全性评价方案[J].*计算机应用与软件*,2019(03):148-153. **(中文核心)** [[下载PDF]](http://42.192.94.151/cv_files/01.pdf) [[知网链接]](https://kns.cnki.net/kcms2/article/abstract?v=YoFA4grnCX7wc9Xnndm6XwTtFTGEnh4EcMDP_MtedNKyvw9NgNY-xb6ALV4kk3MRqBkT4pYZv_zUvdsEK2T8XdrY-juzvmV_PA4JkNKfQ2DkGK6-PK8OiHs5ZvzuWu3ilNpLp1fY0mHDN11nCwoQ1g==)
- 📑 **专利：**熊礼治,**蒋鹏程**,王乐,韩啸,汤琳俪,曹梦琦.一种基于精准定位和安全扫码的共享单车计费方法[P]. CN109242645A,2019-01-18. **(除老师外一作)** [[下载PDF]](http://42.192.94.151/cv_files/00.pdf) [[知网链接]](https://kns.cnki.net/kcms2/article/abstract?v=YoFA4grnCX4lF5iSTPVzIEftr2rGq8LgeLAfR4A01oifAMSPEG1NWqqEeq60hHNI3mM5gKIu1qyUc77LtO8djxmJS4KW-CuvWzPFDGARfD6wgdlrqPZP7yY4d28Lk9WiGj_XtaQDdCw=)
- 📰 **软著：**一种密文图像安全性评价软件V1.0（2019SR0588758）


<span class='anchor' id='-services'></span>
# 📌 社会服务
担任以下期刊的审稿人：
- 📙 IEEE Transactions on Neural Networks and Learning Systems (SCI一区，IF:10.2)
- 📙 IEEE Transactions on Industrial Informatics (SCI一区，IF:11.7)
- 📙 Information Sciences (SCI一区，IF:8.1)
- 📙 Scientific Reports (SCI二区，IF:3.8)
- 📙 Journal of Supercomputing (SCI三区，IF:3.3)
- 📙 PeerJ Computer Science (SCI三区，IF:3.8)
- 📙 CMC-Computers Materials & Continua (SCI三区，IF:3.1)
- 📙 Knowledge and Information Systems (SCI四区，IF:2.7)
- 📙 Peer-to-Peer Networking and Applications (SCI四区，IF:3.3)


担任以下会议的分会主席 (Session Chair)：
- 📃 “Nature-Inspired Intelligent Computing, Optimization and Applications” in *2024 International Conference on Intelligent Computing (ICIC)* 

担任以下会议的审稿人：
- 📃 7th International Conference on Artificial Intelligence and Security
- 📃 8th International Conference on Artificial Intelligence and Security
- 📃 2024 IEEE Conference on Artificial Intelligence (IEEE CAI 2024)
- 📃 2024 International Joint Conference on Neural Networks (IEEE IJCNN 2024)

<span class='anchor' id='-grants'></span>
# 💬 项目经历
- *2019.04 ~ 2022.12* 国家自然科学基金（面上项目）基于自适应演化计算的大规模特征选择研究
- *2024.01 ~ 2027.12* 国家自然科学基金（面上项目）基于高效代理模型的多目标多任务演化深层神经网络研究
- *2020.10 ~ 2022.03* 中国**集团公司第**研究所（横向课题）工业机器人协同开发平台集成服务总线开发（参与）
- *2020.04 ~ 2020.10* 数据科学与智慧软件江苏省重点建设实验室（开放课题）基于演化计算的大规模无人机协同电子对抗关键技术 （参与）
- *2017.04 ~ 2019.04* 大学生创新训练项目（学生团队项目）基于精准定位和安全扫码的共享单车计费系统（第一负责人）

<span class='anchor' id='-skills'></span>
# 🔥 技术优势
### 科研能力
1. 擅长**Python**编程，对绝大多数常用的数据分析库熟悉（**numpy**，**pandas**，**scipy**等）。
2. 擅长**Pytorch**框架，熟悉**PaddlePaddle**，**Tensorflow**框架。
3. 熟悉**Linux**，能够编写**Shell**指令脚本。
4. 熟悉**深度学习**、**计算机视觉**、**群体智能**等方向。
5. 目前主要研究方向为**演化深度学习**，包括**神经网络结构搜索**和**神经网络压缩**。
6. 在团队中负责设备环境维护和配置，曾为“南京信息工程大学计算机学院”和“金陵科技学院计算机工程学院”进行过**高性能服务器**设备维护。目前在负责学院**高性能设备**和**AI MAX计算平台**的相关**维护**工作
7. 参与**管道裂痕检测**项目（使用**对象检测**，**yolo-V5**、**faster rcnn**）

### 开发能力
1. 擅长**JavaSE**和**JavaEE**编程，有使用**SWT**、**Swing**、**SSH**框架的项目经验，对**SSM**和**SpringBoot**框架也比较熟悉。
2. 擅长**Python**编程，有使用**Selenium**库爬取数据的项目经验，有使用**Flask**库在原有平台API基础上开发辅助平台相关经验。
3. 熟悉**C#**，有使用**Winform**和**ASP.NET**的项目经验。
4. 熟悉**Android**，能熟练使用**Android Studio**开发安卓软件。
5. 掌握一定的**数据库技术**，能熟练使用**SQL Server**、**MySQL**等关系型数据库和**Redis**等非关系型数据库。
6. 对**VS Code**，**Pycharm**，**Idea**，**Visual Studio**，**MyEclipse/Eclipse**，**Android Studio**等IDE比较熟悉。
7. **编程习惯**良好，**代码规范**，能运用**设计模式**，熟练使用**Git**进行**版本控制**和**团队协作**。
8. 具有比较丰富的**云产品**使用经验，曾在**阿里云**、**腾讯云**等平台使用**ECS**、**轻量级服务器**、**域名解析**、**机器翻译API**，**图片识别API**、


<span class='anchor' id='-projects'></span>
# 💬 开发经历
#### *2020.01 ~ 2020.04* 电梯PDF订单和参数表提取处理程序（独立完成）
**项目描述：**此项目为来自常州**有限公司的个人项目，内容为开发一个程序，使其能够从PDF文件格式的订单文件中，提取出分散的订单列表和详细信息，整合订单的配件参数，合并同参数订单，并插入配件的详细规格和图纸链接，最终生成处理好的Excel电子表格。

#### *2017.04 ~ 2019.04* 基于精准定位和安全扫码的共享单车计费系统（第一负责人）
**项目描述：**此项目为大学生创新训练项目，内容为开发基于精准定位和安全扫码的共享单车计费系统。

**责任描述：**在组内的职务为第一负责人，主要职责为对组员进行合理分工，负责组织项目成员和指导老师的讨论会、编写App主要功能代码、做好代码的联调，以及将研究成果成文并发表。

#### *2018.08* 基于Python和Selenium的电影数据抓取和影评分析
**项目描述：**此项目为内容为使用Python语言，开发基于Selenium工具的爬虫程序，实现电影数据抓取和和对数据进行分析处理。

**责任描述：**职务为小组组长，主要职责为对小组成员进行合理调配，负责爬虫程序的编写和对数据库代码、数据统计代码的联调工作。

#### *2018.12* 学生教务管理系统
**项目描述：**此项目内容为编写教务管理系统，对学生信息、选课信息、学生成绩等内容进行管理。项目是基于.NET4.0平台写的，是使用C#语言编写的WinForm程序，数据库使用的是SQL Server。项目中使用了MVC结构，并合理使用了一些设计模式思想。项目中有对数据的加密处理和对数据的校验，功能比较完备，并能保证安全稳定运行。

**责任描述：**职务为小组组长，主要职责为对组员进行合理分工、做好API接口的规范要求以及设定遵循设计模式的规范要求，负责定义各个接口、编写数据访问层和业务层代码，以及对整体程序进行联调。
