# NNIE_tutorial
根据自身项目经验,结合华为的官方文档和样例写的教程,目前更新了第一部分video.iaas.sdc服务的教程样例,后面的部分会逐步更新.
### 主要内容
由浅入深的对SDC(Software Defined Camera 软件定义相机)进行讲解,项目中的代码中有大量的中文注释,配合注释基本可以快速弄懂SDC以及NNIE框架的使用方法.

项目结构:
- Part_1: 该文件夹下的为video.iaas.sdc服务的教程样例,摄像头视频数据IO相关
- Part_2 该文件夹下为algorithem.iaas.sdc服务的教程样例,包含图像转换以及模型加载/初始化等相关操作
  - 图像转换(已更新)
  - 模型加载(已更新)
  - 模型初始化(未更新)
  - 后处理函数(未更新)
  - 前向推导函数(未更新)
### 主要贡献
- 迁移到C++平台上,现在各大服务都集成为类的形式进行调用了
- 添加了CMAKE用的文件,现在使用CLION等IDE能够很好的进行代码补全,加快写代码的速度
- 对华为海思SDC的API进行了封装,原先华为给的demo非常乱,现在各类服务的注册和通讯都封装在了各个类方法中,对用户透明化
- 修正了样例代码的一些小BUG


