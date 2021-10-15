##### 初识hdrp：

* 渲染风格一般分为卡通和真实感（物理）两种
* hdrp和光线追踪都是基于物理的渲染
* 不同点是：hdrp是unity和虚幻的框架，光线追踪是算法

##### 本仓库

* 本仓库是网友的hdrp测试程序
* 同时记录我的hdrp学习

##### 原md：



![gif](https://i.imgur.com/2qlNtFC.gif)
![gif](https://i.imgur.com/K3k5ffi.gif)

![gif](https://i.imgur.com/m7lKcUh.gif)
![gif](https://i.imgur.com/p29Lrap.gif)

TestbedHDRP is a Unity project where I try custom effect ideas with
[Unity HDRP]. Currently, it only contains the following two types of effects:

- Geometry shader effects
- Many-light effects

Although the geometry shader effects are fun and exciting to use, I don't
recommend using them in production. **The geometry shader is near-obsolete
technology.** You will meet several problems if you use it in your product.

The many-light effects are mainly for benchmark purposes. I just wanted to know
how I could utilize the power of FPTL.

[Unity HDRP]:
  https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@latest

System requirements
-------------------

- Unity 2019.4
- HDRP 7.4
