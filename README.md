# Smart20-BlowmoldingControlSystem

基于HMI+PLC 的吹塑机控制系统 A Blowmolding Control System Base by HMI+PLC 

## 演示 | Show

### 首页

<img title="" src="https://cdn.staticaly.com/gh/lybhb8/pix_rep@master/blog/home.7jcq8o2ba6s0.webp" alt="" width="640">

### 部分1

![](https://github.com/lybhb8/images_store/blob/main/blowmoldingsystem/tutieshi_640x475_151s.5vbxphu2a9c0.gif)

### 部分2

![](https://github.com/lybhb8/images_store/blob/main/blowmoldingsystem/tutieshi_640x475_107s.1ium3e7yxuf4.gif)

## 说明 | Notice

### 使用前必要阅读

**Smart20-BlowmoldingControlSystem** 由作者Bobolin及其他贡献者开发，所有版权归作者Bobolin所有，程序集源代码在遵循 **Apache-2.0 license**的开源协议以及附加协议下，可免费供其他开发者二次开发或（商业）使用。

### 个人使用须知:

- 不能将程序集用作违法犯罪活动。

- 不能将程序集单独包装售卖，申请专利等。

- 不能擦除程序集所有有关作者的信息。

- 以上内容必须全部符合，个人使用授权才成立。

### 二次开发须知:

- 不能将程序集用作违法犯罪活动。

- 不能将程序集单独包装售卖，申请专利等。

- 不能擦除程序集所有有关作者的信息。

- 二次开发完成后的作品必须附带源作品所有作者信息，包括但不限于作者名、Gitee、Github 地址等。

- 完成后的作品（仅 **Smart20-BlowmoldingControlSystem**部分）必须将发布时最新源代码提交一份给本作者，QQ 邮箱：**1341979804@qq.com**。

- 以上内容必须全部符合，二次开发授权才成立。

### 盈利性（商业）用途使用须知:

- 不能将程序集用作违法犯罪活动。

- 不能将程序集单独包装售卖，申请专利等。

- 不能擦除程序集所有有关作者的信息，并必须于用户可见界面（如关于）中提名。

- 以上内容必须全部符合，商业使用授权才成立。

### Smart20-BlowmoldingControlSystemPro 商用许可

- **Smart20-BlowmoldingControlSystemPro**软件框架与 **Smart20-BlowmoldingControlSystem**是一致的，只另包含增强功能模块。

- **Smart20-BlowmoldingControlSystemPro**所有版权归作者Bobolin所有。

- **Smart20-BlowmoldingControlSystemPro**不公开开源，需要付费购买。

### 免责申明

在使用 Smart20-BlowmoldingControlSystem 之前请进行缜密的测试。在使用期间，由本程序集造成或间接造成的所有损失，均自己承担，与本程序集无关。

## 简介|Introduction

- Smart20 吹塑机控制系统基于HMI+PLC，构建了吹塑机控制系统主要功能和模块，**Smart20-BlowmoldingControlSystem** 基于Apache-2.0 license协议颁布，完全可以免费应用于基本需求的商业产品中。
- HMI部分基于[繁易](https://www.flexem.cn/product/9000/FE9150M) 15吋触摸屏构建，组态软件(IDE)为[FStudio 2.0](http://fs.flexem.com/zh)，功能脚本遵照C语言语法。
- PLC部分基于[OMRON](https://www.fa.omron.com.cn/products/category/automation-systems/programmable-controllers/index.html) **C**系列PLC(如CP1H,CJ2M)构建，编辑软件为[CX-ONE4.03及以上](https://www.aliyundrive.com/s/bRGAnchw8ZJ)。后续还会推出基于西门子S7系列，三菱FX5U等版本，用户也可以自行移植构建。

## 特点|Features

- 开放的，资源友好型系统框架，成熟稳定，性能优异的HMI+PLC架构，开源免费，开箱即用，电气工程师易于上手使用。
- 系统功能齐全，配置了吹塑机控制所需的功能模块：挤出、温度、壁厚控制、开合模、移模、时间、吹针、液压、吹气、气动、报警、监控、日志、产品配方、运动控制（伺服电机）等。
- 系统模块化集成，耦合度低，弹性可裁剪，性能优异，稳定性强。用户可根据产品需求弹性组合功能模块，组态快捷，工作效率高。
- 标签变量设计，易于系统移植和二次开发。
- HMI脚本基于C语言，执行效率高，资源占用少。用户二次开发的高级功能，可基于脚本实现，还可封装编译成静态链接库文件，利于知识产权保护。
- 结构清晰，层次分明、美观时尚的UI设计。
- HMI 页面和功能，结合国内外用户使用操作习惯进行了优化。
- 专业化、国际化语言设计，便于产品出口应用。
- PLC部分封装大量功能块供用户使用，标准化了常用功能代码：液压伺服控制、挤出机驱动、温度PID、壁厚控制、开合模速度控制、移模速度控制、液压气动阀控制等。
- 详细专业的系统文档和代码注释。

## 开源 |Open Source

- 吹塑机控制系统中，[倍福](https://www.beckhoff.com.cn/zh-cn/industries/plastics-machines/blow-molding/)、[贝加莱](https://www.br-automation.com/zh/)、[杰弗伦](https://www.gefran.cn/%E4%BA%A7%E5%93%81/%e8%bd%af%e4%bb%b6/%e6%a8%a1%e6%9d%bf/plastic-blow-template-%e8%87%aa%e5%8a%a8%e5%8c%96%e5%b9%b3%e5%8f%b0/)等虽然系统成熟稳定，但也存在系统封闭、难于上手，学习成本高、功能扩展性差，系统成本高。

- 国内吹塑机生产商大多采用Moog壁厚控制器+HMI+PLC构成系统（秦川为HMI+PLC自研系统），存在系统集成度低，数据不易交互，HMI页面设计美观度低，层次比较凌乱，专业性不足，用户使用度差，多语言专业性用词欠缺，物联网、5G技术无法应用，系统成本高。

- 随之物联网、5G技术的发展，其在工业自动化实践中的应用如雨后春笋般爆发。

- 自主的、开放的、先进的、功能强大的、性能稳定的、易用的、经济的**吹塑机控制系统**是行业的迫切需求。

- 多年来，有感于吹塑机控制系统行业现状，有心想在这方面做点事情，尝试开发一套理想的**吹塑机控制系统**。

- 技术架构综合了技术开发和应用等多个因素，确定HMI（附加物联网功能）+PLC。

- HMI硬件选型经过了一系列痛苦的“**选择**->**放弃**”的过程，国内常见的HMI主流品牌都做过开发过程，全部不能达到系统开发要求。其中的原因五花八门，实际可以归纳成一点：技术架构落后，封闭不开放。
  
  也尝试用工控机+SCADA实现，典型的SCADA软件是西门子WINCC7.5。开始时，自己还比较乐观，主要原因还是比较迷信西门子的东西。当项目试建时，其封闭性的弊端显现出来。在搭建<u><strong>壁厚控制</strong></u>模块时，Wincc的<u><strong>函数趋势控件FunctionTrendControl</strong></u>需要结合<u><strong>User Archive用户归档</strong></u>，才能实现多点（X、Y）坐标值的读写（将多点X、Y坐标变量如TagX0,TagX1,TagX2...TagY0,TagY1,TagY2...看作两个变量TagX,TagY的多个归档，自己当时无法理解西门子为什么这样做？后来才明白因为西门子WINCC的Tag数量与售价紧密关联，**都是“月亮”惹的祸！**）。可当用C脚本实现100点变量操作时，却无法保证所有数据的正确和有序（期待Wincc高手指导），也只好放弃。

- 也是偶然的机会，圈内的朋友推荐**繁易HMI**，初步尝试时，在别的平台难于实现的系统功能，却能很快组态完成，测试模拟很成功。经过进一步系统搭建，**繁易HMI**平台的优势逐步呈现出来:
  
  - 基于成熟的Linux操作系统。
  
  - 长期高可靠的嵌入式内存管理技术。
  
  - 实用的HMI控件，满足各种使用要求。
  
  - 传统的组态操作方法，组态工作效率高。
  
  - 高性能实时C语言脚本技术，能完成各种高级组态功能。
  
  - 原生的C语言系统平台，足够的系统开放性，可以调用大量的C库函数，增强组态工作。



当时想着自己也开发一套，但是后来没时间，当时也没那个技术积累。

后来学了Go语言，又在无意间遇到了[Mindoc](https://github.com/lifei6671/mindoc)，然后我们公司([掘金量化](https://www.myquant.cn/) )也恰巧让我开发公司官网和文档系统，然后我就对[Mindoc](https://github.com/lifei6671/mindoc)做了二次开发。

本来是不想开源的，因为自己写代码的时候，写着写着，代码改来改去，然后代码就乱七八糟了，怕开源出来丢人现眼。但是踏入IT行业三年多时间以来，自身也受益于各种开源书籍和开源组件，所以最终还是决定将BookStack开源出来。

其中肯定还是有不足的地方，大家在使用的过程中，遇到问题，欢迎反馈。

## 参与开发 | Development

我们欢迎您在 **Smart20-BlowmoldingControlSystem**项目的 GitHub 上报告 issue 或者 pull request。

如果您还不熟悉GitHub的Fork and Pull开发模式，您可以阅读[克隆仓库 - GitHub 文档](https://docs.github.com/zh/repositories/creating-and-managing-repositories/cloning-a-repository?platform=windows))获得更多的信息。(**1小时学会GitHub**，[请点击:【狂神说Java】Git最新教程通俗易懂](https://www.bilibili.com/video/BV1FE411P7B3/?spm_id_from=333.337.search-card.all.click&vd_source=72d47f920610891857fb5340afefeb8e))

## 感谢 | Thanks

- 
