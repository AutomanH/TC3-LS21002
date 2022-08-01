# LS21002
>TC3 Build 4024.20 
## 1.1更新履历

  [2022-06-09](https://github.com/AutomanH/TC3-LS21002/commit/dadd780a9d03594e35c87b4cd09d5160e1dc4833)
  - 优化过程数据记录
  - 优化机械手程序
  - 优化蠕动泵程序

  [2022-06-10](https://github.com/AutomanH/TC3-LS21002/commit/589766bdabcdaf9883239b8639c98740bfb37b4a)
  - 修改S01上料工位数据传递的时序
  - 完成各工位的报警，已完成S01-S08
  - 新增单循环运行时清除本地过程数据记录
  - 新增心跳功能块及心跳程序

[2022-06-13](https://github.com/AutomanH/TC3-LS21002/commit/e85dc65408d55dd9d82e14824fc71b984ce8424f)

- 增加`FB_EtherCatSlaveMonitor`功能块并完善EtherCAT总线报警
- 增加`LightsTest()`程序，调试的时候进行一键所有灯测试
- 修改S01上料工位程序

[2022-06-14]()

- 增加自动过程中按停止按钮必须执行完的程序
- 将链板线上料程序改成`FB_FlowLine`
- 修改S01上料自动程序中的取料逻辑。
- S01-S08工位梳理空跑逻辑
- 气缸功能块增加空跑接口

[2022-06-20](https://github.com/AutomanH/TC3-LS21002/commit/75fa6e349fea645954731f54f0b29e81ae81aa1b)

- 机构电磁阀布局有变化，更改程序。
- 为`FB_FlowLine`增加空跑接口
- 为相机`FB_Camera`增加空跑接口
- 增加编码器功能块`FB_Encoder`
- 整机初步空跑实现

[2022-06-28](https://github.com/AutomanH/TC3-LS21002/commit/c352546fad6a45a2b2319579a8d833d747b17651)

- 整机带料测试（S01-S10）OK。
- 完善与第三方设备对接并测试。

[2022-07-02]()

- 编写`FB_Encoder`功能块，计算皮带线线速度。
- 编写`FB_ATV12`功能块，实现施耐德变频器ATV12系列的启停和速度控制。
- 编写真空吸`FB_SmcVacuum`功能块，实现SMC品牌的真空吸控制。
- 各站开放相机检测功能并细化完成。

[2022-07-08](https://github.com/AutomanH/TC3-LS21002/commit/ef672a08b6741f9c4fd0b36c50ada722219190c0)

- 重写天平秤的程序`FB_MT_MKC_New`
- 完善S02蠕动泵自动校准程序及HMI界面。

[2022-07-19](https://github.com/AutomanH/TC3-LS21002/commit/158ee08dc95c8023eed40bea09e5035c21c53cb1)

- 新增`FB_LoadCell`功能块，读取/清零压力传感器。
- 压力传感器新增接线DI（9）\PD+\PD-
- 完善相机及链板线功能块版本升级至V2.0.0
- 完善贴标及NG下料程序
- 完善皮带线程序

[2022-07-20](https://github.com/AutomanH/TC3-LS21002/commit/713a6bf9aa3a462f4a553d1b65d4f2e9dd2ceb78)

- 新增`FB_Cimcor_IZN10E`功能块，用于控制离子风棒、静电消除器、吹气电磁阀。
- S03相机工位程序升级
- 整机清料程序编写

[2022-07-21]()

- 新增`FB_KF300`蠕动泵程序
- 新增蠕动泵手动单泵头测试程序并记录数据

