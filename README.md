# 163-os_test_automation

制作轻量级测试操作系统


## 项目描述
该项目要求实现一个轻量级的测试操作系统。该系统启动后会自动运行内置测试程序，用来收集该系统的硬件信息和一些硬件性能测试结果，测试完成后可以自动上传对应的测试报告给到对应的服务器上或者如果接入了u盘的话会自动把测试报告导出到u盘上。

## 所属赛道

2022全国大学生操作系统比赛的“OS功能挑战”赛道



## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生（2022年春季学期或之后毕业的本科生及研究生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求



## 项目导师

* 付  强: fuqiang@kylinos.cn
* 李玉沛: liyupei@kylinos.cn



## 难度

中等


## 特征

1.轻量级
2.自动化
3.操作系统
4.良好的硬件平台可移植性

## License
任意开源license都可


## 预期目标
1.支持光盘或U盘引导；
2.支持UEFI启动；能同时支持legacy启动为加分项。
3.系统启动后需自动收集机器硬件相关信息：包括处理器CPU信息，内存信息，显卡信息，主板信息，显示器信息，主硬盘信息，声卡信息
4.进行相关的测试：包括cpu性能测试，内存性能测试，显示性能测试，网络测试，硬盘读写测试，ltp相关的压力测试等等。测试过程有准确的进度显示为加分项。
5.生成最终的测试报告；测试报告可以按实际网络环境和使用环境，提示用户是否在线保存或离线保存。
