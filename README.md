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
- S02/S03工位梳理空跑逻辑
- 气缸功能块增加空跑接口

