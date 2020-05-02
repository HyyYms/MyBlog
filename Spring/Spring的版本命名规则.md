# Spring的版本命名规则

## 常见的软件的版本号命名

| 软件         | 升级过程                | 说明                                                  |
| ------------ | ----------------------- | :---------------------------------------------------- |
| Linux Kernel | 0.0.1 1.0.0 2.6.32      | 若用X.Y.Z表示，则偶数Y表示稳定版本，奇数Y表示开发版本 |
| Windows      | Windows 98 Windows 2000 | 最大的特点为杂乱无章                                  |
| SSH Client   | 0.9.8                   |                                                       |
| OpenStack    | 2014.1.3 2015.1.1.dev8  |                                                       |

## 语义化版本命名通用规则

| 序号 | 格式要求 | 说明                                                         |
| ---- | -------- | ------------------------------------------------------------ |
| X    | 非负整数 | 表示主版本号（Major），当API的兼容性变化时，X需递增          |
| Y    | 非负整数 | 表示次版本号（Minor），当增加功能时（不影响API的兼容性），Y需递增 |
| Z    | 非负整数 | 表示修订号（Patch），当做Bug修复时（不影响API的兼容性），Z需递增 |

## Spring版本命名规则

| 描述方式 | 说明     | 含义                                                     |
| -------- | -------- | -------------------------------------------------------- |
| Snapshot | 快照版   | 尚不稳定，仍处于开发中的版本                             |
| Release  | 稳定版   | 功能相对稳定，可以对外发行，但有时间限制                 |
| GA       | 正式版   | 代表广泛可用的稳定版（General Availability）             |
| M        | 里程碑版 | （M是Milestone的意思）具有一些全新的功能或是有意义的版本 |
| RC       | 终测版   | Release Candidate（最终测试），即将作为正式版发布        |

### 相关版本号图片

#### Snapshot

![image-20200502234443230](C:\Users\huang\AppData\Roaming\Typora\typora-user-images\image-20200502234443230.png)

#### Release

![image-20200502234529080](C:\Users\huang\AppData\Roaming\Typora\typora-user-images\image-20200502234529080.png)

#### GA

![image-20200502234352063](C:\Users\huang\AppData\Roaming\Typora\typora-user-images\image-20200502234352063.png)

#### M

![image-20200502234555102](C:\Users\huang\AppData\Roaming\Typora\typora-user-images\image-20200502234555102.png)

#### RC

![image-20200502234622485](C:\Users\huang\AppData\Roaming\Typora\typora-user-images\image-20200502234622485.png)

### 商业软件中常见的版本修饰词

| 描述方式     | 说明   | 含义                                                        |
| :----------- | :----- | :---------------------------------------------------------- |
| Snapshot     | 快照版 | 尚不稳定、尚处于开发中的版本                                |
| Alpha        | 内部版 | 严重缺陷基本完成修正并通过复测，但需要完整的功能测试        |
| Beta         | 测试版 | 相对alpha有很大的改进，消除了严重的错误，但还是存在一些缺陷 |
| RC           | 终测版 | Release Candidate（最终测试），即将作为正式版发布           |
| Demo         | 演示版 | 只集成了正式版部分功能升级，无法升级                        |
| SP           | SP1    | 是service pack的意思表示升级包，相信大家在windows中都见过   |
| Release      | 稳定版 | 功能相对稳定，可以对外发行，但有时间限制                    |
| Trial        | 试用版 | 试用版，仅对部分用户发行                                    |
| Full Version | 完整版 | 即正式版，已发布                                            |
| Unregistered | 未注册 | 有功能或时间限制的版本                                      |
| Standard     | 标准版 | 能满足正常使用的功能的版本                                  |
| Lite         | 精简版 | 只含有正式版的核心功能                                      |
| Enhance      | 增强版 | 正式版，功能优化的版本                                      |
| Ultimate     | 旗舰版 | 在标配版本升级体验感更好的版本                              |
| Professiona  | 专业版 | 针对更高要求功能，专业性更强的使用群体发行的版本            |
| Free         | 自由版 | 自由免费使用的版本                                          |
| Upgrade      | 升级版 | 有功能增强或修复已知bug                                     |
| Retail       | 零售版 | 单独发售                                                    |
| Cardware     | 共享版 | 公用许可证（IOS签证）                                       |
| LTS          | 维护版 | 该版本需要长期维护                                          |