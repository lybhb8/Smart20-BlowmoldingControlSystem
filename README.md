# Smart20-BlowmoldingControlSystem

基于HMI+PLC 的吹塑机控制系统 A Blowmolding Control System Base by HMI+PLC 

<img title="" src="https://cdn.staticaly.com/gh/lybhb8/pix_rep@master/blog/home.7jcq8o2ba6s0.webp" alt="" width="478">

<img title="" src="https://cdn.staticaly.com/gh/lybhb8/pix_rep@master/blog/tutieshi_480x356_117s.3zd09jw1avs0.gif" alt="" width="479">

![](https://cdn.staticaly.com/gh/lybhb8/pix_rep@master/blog/tutieshi_480x356_72s.s6zeobettww.gif)

![](https://cdn.staticaly.com/gh/lybhb8/pix_rep@master/blog/tutieshi_480x356_70s.42n9gdq0lza0.gif)

## 说明 | Notice

### 使用前必要阅读

Smart20-BlowmoldingControlSystem 由作者Bobolin及其他贡献者开发，所有版权归作者Bobolin所有，程序集源代码在遵循 Apache-2.0 license 的开源协议以及附加协议下，可免费供其他开发者二次开发或（商业）使用。

### 个人使用须知:

不得将程序集用作违法犯罪活动。
不得将程序集单独包装售卖，申请专利等。
不得擦除程序集所有有关作者的信息。
以上内容必须全部符合，个人使用授权才成立。

### 二次开发须知:

不得将程序集用作违法犯罪活动。
不得将程序集单独包装售卖，申请专利等。
不得擦除程序集所有有关作者的信息。
二次开发完成后的作品必须附带源作品所有作者信息，包括但不限于作者名、Gitee、Github 地址等。
完成后的作品（仅 Smart20-BlowmoldingControlSystem 部分）必须将发布时最新源代码提交一份给本作者，QQ 邮箱：1341979804@qq.com。
以上内容必须全部符合，二次开发授权才成立。

### 盈利性（商业）用途使用须知:

不得将程序集用作违法犯罪活动。
不得将程序集单独包装售卖，申请专利等。
不得擦除程序集所有有关作者的信息，并必须于用户可见界面（如关于）中提名。
以上内容必须全部符合，商业使用授权才成立。

### Smart20-BlowmoldingControlSystemPro 商用许可

Smart20-BlowmoldingControlSystemPro 软件框架与 Smart20-BlowmoldingControlSystem 一致，另包含增强功能模块。所有版权归作者Bobolin所有。
Smart20-BlowmoldingControlSystemPro 不公开开源，需要付费购买。

### 免责申明

在使用 Smart20-BlowmoldingControlSystem 之前请进行缜密的测试。在使用期间，由本程序集造成或间接造成的所有损失，均自己承担，与本程序集无关。

## 简介|Introduction

- Smart20 吹塑机控制系统基于HMI+PLC，构建了吹塑机控制系统主要功能和模块，Smart20-BlowmoldingControlSystem基于Apache-2.0 license协议颁布，完全可以应用于基本需求的商业产品应用中。
- HMI部分基于[**繁易**](https://www.flexem.cn/product/9000/FE9150M "点击跳转")15吋触摸屏构建，组态软件(IDE)为[FStudio 2.0](http://fs.flexem.com/zh)，功能脚本遵照C语言语法。
- PLC部分基于[**OMRON**](https://www.fa.omron.com.cn/products/category/automation-systems/programmable-controllers/index.html) **C**系列PLC(如CP1H,CJ2M)构建，编辑软件为[CX-ONE4.03及以上](https://www.aliyundrive.com/s/bRGAnchw8ZJ)。后续还会推出基于西门子S系列，三菱FX5U等版本，用户也可以自行移植构建。

## 特点|Features

- 开放的，资源友好型系统框架，成熟稳定，性能优异的HMI+PLC架构，开源免费，开箱即用，电气工程师易于上手使用。
- 系统功能齐全，配置了吹塑机控制所需的功能模块：挤出、温度、壁厚控制、开合模、移模、时间、吹针、液压、吹气、气动、报警、监控、日志、产品配方、运动控制（伺服电机）等。
- 系统模块化集成，耦合度低，弹性可裁剪，性能优异，稳定性强。用户可根据产品需求弹性组合功能模块，组态快捷，工作效率高。
- 标签变量设计，易于系统移植和二次开发。
- HMI脚本基于C语言，执行效率高，资源占用少。用户二次开发的高级功能，可基于脚本实现，还可封装编译成静态链接库文件，利于知识产权保护。
- 结构清晰，层次分明、美观时尚的UI设计。
- 专业化、国际化语言设计，便于产品出口应用。
- PLC部分封装大量功能块供用户使用，标准化了常用功能代码：液压伺服控制、挤出机驱动、温度PID、壁厚控制、开合模速度控制、移模速度控制、液压气动阀控制等。
- 详细专业的系统文档和代码注释。