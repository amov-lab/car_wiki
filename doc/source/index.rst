.. home:

amovcar 使用文档
==============================

本文档是R200及R300无人车的在线资源平台，您可以在这里了解到所有关于R系列无人车的内容。

我们建议第一次使用无人车的朋友，通过文档左边的目录找到对应产品并逐章节阅读。无人车使用及开发需要用户 **有一定技术基础**.

需要使用者掌握一定的 **Linux/ROS/C++/Python/PX4** 基本知识。如果您是第一次接触Linux或者ROS。请参考下面的链接，补充相关基础知识。

其中：
   1. Linux需要掌握的知识有：Linux系统文件结构及其常用命令(https://www.runoob.com/linux/linux-file-content-manage.html)
   2. ROS需要掌握的知识有：ROS通信框架、gazebo仿真、TF等。非常建议大家去ROS官网学习(http://wiki.ros.org/).
      或者前往B站，观看赵虚左老师的ROS教程(https://www.bilibili.com/video/BV1Ci4y1L7ZZ?from=search&seid=3011252633328555279&spm_id_from=333.337.0.0)
   3. C++ / Python：ROS支持这两种开发语言。可以根据您个人的习惯，选择C++或者Python作为您的主要开发语言。 **R300大部分采用C++语言，只有少部分脚本采用Python语言编写**。
   4. PX4：R300具有室外导航及动态避障功能，该功能使用mavros(http://wiki.ros.org/mavros)作为通信协议。配合PX4飞控(飞控中使用的是APM Rover固件)，来实现该功能。


.. note::
   本手册由阿木实验室实时维护。若您有对本手册的内容有疑问，可以通过电子邮件或论坛发帖的方式向我们提问。若您希望对本手册提出修改意见，请发送邮件至service@amovauto.com，对于有建设性的意见我们将赠与阿木币！（阿木币可以1：1兑换成人民币）

.. note::
   本项目所有代码均开源！ amovcar自主无人车项目：https://gitee.com/amovlab/amovcar
   
   欢迎关注阿木实验室B站频道：https://space.bilibili.com/432575320?from=search&seid=13705682698139641872 我们会在B站发布有趣的测试视频。
   记得一键三连，不要下次一定！

祝您使用愉快！

   

.. toctree::
   :maxdepth: 2
   :caption: AMOV官网

   阿木实验室 <https://www.amovlab.com/>

.. toctree::
   :maxdepth: 2
   :caption: 系列产品概况

   无人车产品介绍 <docs/bases/无人车产品介绍>
   硬件模块介绍 <docs/bases/硬件模块介绍>
   遥控器介绍 <docs/bases/遥控器介绍>
   Mission Planner地面站介绍 <docs/bases/Mission Planner地面站介绍>
   无人车软件文件结构 <docs/bases/无人车软件文件结构>
   无人车硬件接线图介绍 <docs/bases/无人车硬件接线图介绍>
   无人车通信链路介绍 <docs/bases/无人车通信链路介绍>
   术语 <docs/bases/术语>


.. toctree::
   :maxdepth: 2
   :caption: R200

   硬件框架介绍 <docs/R200/硬件框架介绍>
   软件框架介绍 <docs/R200/软件框架介绍>
   操作流程 <docs/R200/操作流程>
   R200仿真 <docs/R200/R200仿真>
   常见问题处理 <docs/R200/常见问题处理>

.. toctree::
   :maxdepth: 2
   :caption:   R300

   硬件框架介绍 <docs/R300/硬件框架介绍>
   软件框架介绍 <docs/R300/软件框架介绍>
   开始使用 <docs/R300/开始使用>
   R300仿真 <docs/R300/R300仿真>
   常见问题处理 <docs/R300/常见问题处理>

.. toctree::
   :maxdepth: 2
   :caption: Turtlebot3

   简介<docs/Turtlebot3/简介>
