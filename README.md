# fuck⭐nku⭐physics⭐experiments

# 如果本仓库给你的大物实验带来了便利，请star这个仓库以表示支持 ~~♡啊啊难道是个连star都不会的杂鱼?～~~

# ♡才不是想和你一起维护项目呢！！

笔者是22级的老东西, 现在已经脱离了大物实验一线, 发布的表格如果不维护就难以维系, 目前极其希望能得到其他志愿维护者的协助，尤其是本校23级的同学。  

维护工作并不需要很高深的技术力和知识，可以根据当届的情况改一改excel再pull request上来，可以贡献一些自己的数据和预习题答案，具体可以做的事情写在下面的todo一栏中了，欢迎一切交流合作，fork，issue，pull request，以及小窗（qq792405142）。  

考虑到本校物理实验每年教学内容，ppt和教材可能的变化（甚至据我所知有的实验每个助教讲的都不一样），表格公式的可编辑性和可移植性会较为重要，也方便外校学生fork后自行改编。

---

## ♡大物实验君是一个变态！！

本仓库旨在提供针对南开张春玲版《大学基础物理实验》的解决方案，包括但不限于数据处理excel和预习题。  

- 表格可手动通过审阅-保护工作表开启公式保护.使公式处于保护状态防止误操作改动公式
- excel中的大部分物理量名称与张春玲版《大学基础物理实验》一致，可对照书本，尤其是书本上的数据处理表格填入数据。
- beta分支提供了有限的保留位数支持,不过不一定准,仅供参考

## ♡笨蛋！连这点事情都不清楚吗！

- 如何保留小数位数: https://zhuanlan.zhihu.com/p/412879917
- 保护公式的方法：https://baijiahao.baidu.com/s?id=1773006612140140395&wfr=spider&for=pc （建议提交新excel之前过一遍这个流程来保护新写出来的公式格子）
- 大框架来自：https://www.bilibili.com/video/BV13T411g7J1?p=1 的农大版，特向该视频p主juebukeyi致谢。
- 比实验老师授课好一万倍的绪论课：https://www.bilibili.com/video/BV13T411g7J1?p=2
- 主要用到的excel函数教学：https://www.bilibili.com/video/av201021490 以及用于计算置信系数t代替查表的ROUND(TINV(1-置信度,自由度),2)。
- excel绘图教程：https://www.bilibili.com/video/BV14b4y1b7Jj
- 理论指导：https://survivesjtu.gitbook.io/survivesjtumanual/li-zhi-pian/zong-you-geng-zhi-de-zuo-de-shi-qing

## ♡这些事情才不会告诉你呢！！

- 本人的此门课最终给分很差,然而已知的用了这个数据处理表格的其他同学分数表现却很好(同样境遇的还有友链中的一位latex圣手同学),后续推测计算正确度和报告美观度并不是分数密码,最重要的是实验数据要好和保留有效位数这两项,前者可以通过某个表格解决,后者现在还是todo育碧阶段
- 本仓库暂时不能处理保留有效数位，请自行保留正确的数位,**这一点很可能成为助教罚分的重要依据**
- 对于每个使用者而言，为了避免对雷同实验报告的抄袭指控（严重者会直接挂零），笔者建议**使用时请尽量不在实验报告中留下明显痕迹。也不要在课程人员能看见的地方使用和宣传。**

## ♡要做的事情要溢出来了...

- [ ] 八里台校区only的实验补全（hotfix 5.18：碰撞实验的e值计算有大问题，已换源）
- [x] 预习题答案/预习题库
  > 题库已经接近完成，应该会整理好格式一点点传上去，可能剩下的就是答案的捉虫工作了。
- [ ] 补全物理量的单位和写法，使其和南开课本尽量吻合
- [ ] 对表格中的物理量在表头加上文字说明
- [ ] 标明或直接在公式中处理物理量保留位数
  > 关于保留小数的问题（这是目前比较大的问题），有三种方式可用，第一种是直接采用保留小数位数的单元格格式，第二种是用一些函数在excel中保留小数数位（但无法完美实现,round之类的函数不会显示末尾补齐的0,要么就得变成文本再处理），第三种是直接在表头写明保留几位，本人更倾向于第一种+第三种的组合（第一种好改但是维护有点困难，第二种多少有点问题,第三种好改好维护但是得费点脑子）  
  > beta分支里笔者用单元格数字和科学计数法的格式粗略实现了下保留位数的功能,但是还不太完善,大家帮帮
- [ ] 终极目标：https://github.com/feixukeji/PhyX 像科大这样做成在线版的

## ♡最喜欢大家了！！

https://github.com/JFYStudy/NKU_experiment-report 实验报告LATEX版。  
https://github.com/shesl-meow/PhysicsAnalysis 无名南开学长的贡献，使用cpp。  
https://github.com/Lunaticsky-tql/NKU_PhysicExp 同届大佬的项目,使用python.  
https://github.com/feixukeji/PhyX 科大的项目，内附详细的文档和在线数据处理工具。  
https://github.com/nkuflw/nku-physics-exp 实验报告word版。  
以上。

## ♡什么？在想我的事？

Licensed by GPL v3.
Posted on https://github.com/Axolyz/fuck-university-physics-experiments.  
Welcome for stars, issues & contributions.  
