# 请移步：https://github.com/casbin/Summer2021

## 开源软件供应链点亮计划-暑期2020 

### 开源软件供应链点亮计划-暑期2020”是什么？

“开源软件供应链点亮计划-暑期2020”（以下简称 暑期2020）是由中科院软件所与 openEuler 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

该计划将联合各大开源社区，针对重要开源软件的开发与维护提供 mini 项目，并向全国高校学生开放报名。学生可自主选择感兴趣的项目进行申请，并在中选后获得该软件资深维护者（社区导师）亲自指导的机会。根据项目的难易程度和完成情况，参与者还可获取“开源软件供应链点亮计划-暑期2020”活动奖金和奖杯。

**“暑期2020”项目在今年（2020）首次举办，与Google Summer of Code类似，不同点是“暑期2020”只允许中国学生参加，可以看做中国版的GSoC。**

1. 官网：https://isrc.iscas.ac.cn/summer2020
2. 官方新闻：http://www.iscas.ac.cn/xshd2016/xshy2016/202004/t20200426_5563484.html

### 活动的主要参与方有哪些？

活动组织方：中国科学院软件研究所、openEuler 社区主办，中国科学院软件研究所中国科学院软件研究所南京软件技术研究院，华为技术有限公司、中科软科技股份有限公司、深圳华锐金融技术股份有限公司等公司协办，此外，活动组组委会还联合国内公司、科研院所和各大高校共同推广此次活动。

活动参与方主要角色为学生、社区和导师。

1. 学生：学生自由选择项目，与导师沟通实现方案并撰写项目计划书。被选中的学生将在导师指导下，按计划完成开发工作，并将成果贡献给社区。社区评估学生的完成度，主办方根据评估结果发放资助金额给学生。
2. 社区：社区提供项目列表和描述，并安排项目对应的导师，导师与申请者沟通方案、并从申请者中选中一位承接项目。在为期三个月的开发周期中，导师指导学生进行对应项目的开发工作。
3. 导师：社区针对每一个项目指定一个导师，与学生一起制定合适的开发计划和方案，指导学生按计划完成开发。

### 项目的奖金额度是多少？

项目难度分为高、中、低三档，对应税前奖金分别为高（12000 元）、中（9000 元）、低（6000 元）。

## Casbin开源项目介绍

Casbin是一个强大的、高效的开源访问控制框架。涉及到Go, Java, Node.js, Javascript (React), Python, PHP, .NET, Delphi, Rust等多种语言。Casbin由北京大学罗杨博士创立于2017年，核心维护团队有数十人。Casbin在业界具有广泛影响力。目前已经被Intel、VMware、Orange、RedHat、T-Mobile等公司开源使用，被腾讯云、Cisco、Verizon等公司闭源使用。具体详见Casbin主页。Casbin Go主项目目前GitHub 6700+ stars，加上所有语言的实现、插件等可达到10000+ stars。Casbin曾经在国际上多次宣讲：

1. 新加坡政府技术部门Open Government Products：https://www.youtube.com/watch?v=OTT84oplR9o
2. 俄罗斯最大在线旅游平台tutu.ru：https://www.youtube.com/watch?v=Z5dUxH4PqYM

具体请了解Casbin官网：https://casbin.org/

## 可选项目列表

下列所有项目都与Casbin一致，采用开源协议：[Apache 2.0 license](LICENSE)

### 1. Casbin核心引擎（Golang）

1. 项目标题：Casbin核心引擎（Golang）
2. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上：1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求；2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。这两个目标是Casbin的核心竞争力，对于其他Casbin语言的实现也会起到非常重要的借鉴意义。
3. 项目难度：高
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 解决Casbin Golang主仓库&相关仓库中的issues：https://github.com/casbin/casbin/issues
8. 项目技术要求：
   - 熟悉Golang语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin
   - https://github.com/casbin

### 2. Casbin官方论坛（前端React + Javascript，后端Golang）

1. 项目标题：Casbin官方论坛（前端React + Javascript，后端Golang）
2. 项目描述：Casbin社区目前采用QQ群（中文），Gitter（英文）进行社区交流，交流渠道比较有限。我们打算开发一个同时面向Casbin开发者和用户的官方论坛：Casbin-forum（https://github.com/casbin/casbin-forum ），风格与[V2EX](https://v2ex.com/)类似。该论坛的另一个功能是全方位展示Casbin访问控制的功能，后台利用[Casbin](https://github.com/casbin/casbin)进行权限管理，前台利用[casbin.js](https://github.com/casbin/casbin.js)控制UI元素，如按钮的显示。该论坛会成为Casbin技术最强有力的展示。该论坛开源，因此也欢迎其他开源社区使用。
3. 项目难度：高
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完成一个界面风格类似[V2EX](https://v2ex.com/)的论坛，作为Casbin开源社区的官方论坛
   - 后台利用[Casbin](https://github.com/casbin/casbin)进行权限管理
   - 前台利用[casbin.js](https://github.com/casbin/casbin.js)控制UI元素，如按钮的显示（[casbin.js](https://github.com/casbin/casbin.js)目前还在开发中，如果casbin.js未开发完毕则此要求作废，可自行实现前端页面访问控制）
   - 解决Casbin Forum主仓库&相关仓库中的issues：https://github.com/casbin/casbin-forum/issues
8. 项目技术要求：
   - 熟悉React、Javascript语言（前端）
   - 熟悉Golang语言（后端）
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-forum
   - https://github.com/casbin/casbin

### 3. Casbin分布式插件 （Golang)
1. 项目标题：Casbin分布式插件（Golang)
2. 项目描述：Casbin在初始化时将规则集装载到内存中，在规则集发生变更时将该次变更持久化到文件或者数据库等媒介。我们希望在此基础上： 1）基于Raft协议实现单机、分布式环境中不同Casbin实例的规则集同步；２）探索如何将规则集分组，映射到不同节点，使特定规则集的增，删以及某个请求的权限计算都在正确的节点进行，以此减轻单机的内存压力。在未来此插件可以替代 watcher。
3. 项目难度：高
4. 项目社区导师：[刘子轩 (Nodece)](https://github.com/nodece) 
5. 导师联系方式：nodeces@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 基于Raft, Tcp (with TLS)实现单机、分布式环境中不同Casbin实例之间的规则集同步
   - 正确，充足的单元/集成测试，确保Casbin在分布式环境下运行的正确性
   - 支持动态增、删节点(AKA. dynamic membership)
   - 探索如何将规则集分组，映射到不同节点，确定规则集的增，删以及某个请求的权限计算都在正确的节点进行,以此减轻单机的内存压力
   - 解决Casbin Golang主仓库&相关仓库中的issues：https://github.com/casbin/casbin/issues
8. 项目技术要求：
   - 熟悉Golang语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin
   - https://github.com/casbin

### 4. Casbin分布式高可用（Rust）

1. 项目标题：Casbin分布式高可用（Rust）
2. 项目描述：Casbin在初始化时将规则集装载到内存中，在规则集发生变更时将该次变更持久化到文件或者数据库等媒介。我们希望在此基础上： 1）基于Raft协议实现单机、分布式环境中不同Casbin实例的规则集同步；２）探索如何将规则集分组，映射到不同节点，使特定规则集的增，删以及某个请求的权限计算都在正确的节点进行，以此减轻单机的内存压力
3. 项目难度：高
4. 项目社区导师：[江成 (GopherJ)](https://github.com/GopherJ)
5. 导师联系方式：cocathecafe@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 基于Raft, Tcp (with TLS)实现单机、分布式环境中不同Casbin实例之间的规则集同步
   - 正确，充足的单元/集成测试，确保Casbin在分布式环境下运行的正确性
   - 支持动态增、删节点(AKA. dynamic membership)
   - 探索如何将规则集分组，映射到不同节点，确定规则集的增，删以及某个请求的权限计算都在正确的节点进行,以此减轻单机的内存压力
   - 解决Casbin Rust主仓库&相关仓库中的issues：https://github.com/casbin/casbin-rs/issues
8. 项目技术要求：
   - 熟悉Rust语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-rs
   - https://github.com/casbin-rs

### 5. Casbin服务化（C++）

1. 项目标题：Casbin服务化（C++）
2. 项目描述：基于C++版本的casbin探索casbin服务化的可能性，目标是在微服务架构中提供开箱即用的中心化的授权服务
3. 项目难度：中
4. 项目社区导师：[谢非 (Joey)](https://github.com/xcaptain)
5. 导师联系方式：joey.xf@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 使用C++语言实现正确、高性能的casbin基础功能
   - 添加docker、k8s部署支持
   - 使用grpc和protobuf对外提供服务调用
   - 优化在大数据和分布式环境下casbin的性能
8. 项目技术要求：
   - 熟悉C++语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-cpp

### 6. jCasbin 生态完善（Java）

1. 项目标题：jCasbin 生态完善（Java）
2. 项目描述：jCasbin 在 Java 平台上取得了不错的进展，但是我们仍然需要努力工作，以帮助 Casbin 成为世界上最受欢迎的身份授权库。目前Java语言上最流行的授权库是Apache Shiro和Spring Security，最流行的Web框架是Spring。我们需要实现Casbin针对Spring等框架的插件，使Spring用户可以无缝接入Casbin。同时要兼容Apache Shiro和Spring Security的接口，让目前正在使用Apache Shiro和Spring Security的项目可以无缝迁移到Casbin。同时jCasbin也需要及时跟踪Golang Casbin主库的最新feature并移植到Java版本中来。
3. 项目难度：中
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 实现针对Spring，包括Spring Cloud，SpringBoot等的权限认证中间件
   - 实现兼容Apache Shiro和Spring Security的接口
   - 根据用户需求，实现缺失的数据库adapter
   - 解决 jCasbin 主仓库&相关仓库中的 issues：https://github.com/casbin/jcasbin/issues
8. 项目技术要求：
   - 熟悉 Java 语言
   - 熟悉 SQL
   - 熟悉 Git、GitHub 相关操作   
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/jcasbin
   - https://github.com/jcasbin

### 7. PyCasbin完善和优化

1. 项目标题：PyCasbin完善和优化
2. 项目描述：PyCasbin 是Casbin的Python版实现，功能和 Casbin（Golang）基本一致。目前，PyCasbin实现了Casbin的主要功能，但还有少许功能尚未实现，另外代码质量还有调优的可能，PyCasbin对周边框架的支持不够完善，所以我们希望对PyCasibn进行完善和优化，同时需要对PyCasin的生态予以完善。
3. 项目难度：中
4. 项目社区导师：[techoner](https://github.com/techoner)
5. 导师联系方式：techqiang@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完善PyCasbin，和Casbin（Golang）保持一致
   - 在保证功能、结构不变的情况下，调优代码质量
   - 解决PyCasbin仓库中的issues：https://github.com/casbin/pycasbin/issues
8. 项目技术要求：
   - 熟悉Python语言
   - 熟悉Casbin其他任意一种语言的实现
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/pycasbin
   - https://github.com/pycasbin

### 8. PHP-Casbin生态完善

1. 项目标题：PHP-Casbin生态完善
2. 项目描述：[PHP-Casbin](https://github.com/php-casbin/php-casbin) 是Casbin的PHP版实现，功能和 Casbin（Golang）基本一致。目前，PHP-Casbin已经支持对`Laravel` `ThinkPHP` `Yii` `Codeigniter` `CakePHP` 等主流框架的适配。目前还需要开发对`Symfony`的扩展，C级别的框架进行支持，例如：`Phalcon Framework`，基于Swoole的框架支持，例如： `Hyperf` `easyswoole`等。除此之外，我们也希望Casbin有个PHP的C/C++扩展，以提升性能。
3. 项目难度：中
4. 项目社区导师：[techoner](https://github.com/techoner)
5. 导师联系方式：techqiang@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完成 [Symfony-Permission](https://github.com/php-casbin/symfony-permission)
   - 对C级别的框架进行支持，例如：`Phalcon Framework`
   - 对基于Swoole的框架支持，例如： `Hyperf` `easyswoole`等
   - PHP的C/C++扩展，可以基于[Casin-cpp](https://github.com/casbin/casbin-cpp)，也可以考虑通过`zephir`实现
   - 解决PHP-Casbin仓库中的issues：https://github.com/php-casbin/php-casbin/issues
8. 项目技术要求：
   - 熟悉PHP语言
   - 熟悉Git、GitHub相关操作   
9. 相关的开源软件仓库列表：
   - https://github.com/php-casbin/php-casbin
   - https://github.com/php-casbin

### 9. Node-casbin 生态完善

1. 项目标题：Node-Casbin 生态完善
2. 项目描述：Node-Casbin 在 Node.js 平台上取得了不错的进展，但是我们仍然需要努力工作，以帮助 Casbin 成为世界上最受欢迎的身份授权库。目前 Node-Casbin 已经对`koa`、`egg`、`express`、`hapi` 等主流框架提供了权限认证中间件，还需要对`nest`、`meteor` 提供支持。adapter 是 Casbin 持久化策略的插件，目前我们已经支持`TypeORM`、`Sequelize`，这些都是 ORM, 因此我们还需要考虑提供纯数据库驱动的 adapter。
3. 项目难度：低
4. 项目社区导师：[刘子轩(nodece)](https://github.com/nodece)
5. 导师联系方式：nodeces@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 实现 `nest`、`meteor` 权限认证中间件
   - 实现纯数据库驱动的 adapter: PostgresQL, Mysql, Microsoft SQL Server, Oracle, SQLite, IBM Db2.
   - 解决 Node-Casbin 主仓库&相关仓库中的 issues：https://github.com/casbin/node-casbin/issues
8. 项目技术要求：
   - 熟悉 TypeScript 语言
   - 熟悉 SQL
   - 熟悉 Git、GitHub 相关操作   
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/node-casbin
   - https://github.com/node-casbin

### 10. 项目标题：Casbin.NET生态完善

1. 项目标题：Casbin.NET生态完善
2. 项目描述：Casbin.NET是Casbin的Dotnet版实现，目前仅完成核心功能，需要对项目进行进一步的优化和完善。目前计划提供一个完成核心能力开箱即用的服务化(RESTful)的解决方案(Casbin.SamNet)，并且适配Steeltoe。
3. 项目难度：高
4. 项目社区导师：[周而易始(huazhikui)](https://github.com/huazhikui)
5. 导师联系方式：huazhikui@126.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完善和优化Casbin.NET，并解决https://github.com/casbin/Casbin.NET/issues
   - 增加并完成Casbin.SamNet解决方案（基于IdentityServer4），提供完整的权限管理、授权/认证服务（仅后端）
   - 通过Steeltoe完成与Spring Cloud生态圈的融合

8. 项目技术要求：
   - 熟悉C#、.net core
   - 熟悉OAuth 2.0
   - 熟悉java和spring
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/Casbin.NET
   - https://github.com/casbin-net/EFCore-Adapter

### 11. Casbin 仪表盘Web界面（前端Vue/React + Typescript，后端Golang/Casbin-Rs）

1. 项目标题：Casbin 仪表盘Web界面（前端Vue/React + Typescript，后端Golang/Casbin-Rs）
2. 项目描述：Casbin-Dashboard（https://dashboard.casbin.org/ ）是我们近期启动的一个项目，由于Casbin通常在后台运行，没有界面，只有API，配置起来不够友好。因此我们打算开发一个Casbin的图形化界面，即Casbin Dashboard。我们希望Casbin Dashboard能够帮助Casbin的用户，尤其是对代码不熟悉的运维人员，能够通过图形化界面的操作，管理Casbin的模型、策略、正确性、集群运行状态等等。未来一切与Casbin有关的，可图形化的操作，都会集成到Casbin Dashboard中。
3. 项目难度：中
4. 项目社区导师：[张合龙 (BetaCat0)](https://github.com/BetaCat0)
5. 导师联系方式：outman99@hotmail.com
6. 合作导师联系方式（选填）：[江成 (GopherJ)](https://github.com/GopherJ)
7. 项目产出要求：
   - 完成一个可用的Casbin 仪表盘Web界面，可以对接Casbin library，甚至Casbin-Server
   - 用户可以通过Web界面完成策略查看、修改、添加、删除，也可以在线运行测试用例，保证策略正确性
   - 用户可以通过Web界面管理多个Casbin的实体，如Model，Adapter，Enforcer等等（未来甚至可以对Casbin集群进行管理）
   - 解决Casbin Dashboard主仓库&相关仓库中的issues：https://github.com/casbin/casbin-dashboard/issues
8. 项目技术要求：
   - 熟悉Vue/React、Typescript语言（前端）
   - 熟悉Golang/Rust语言（后端）
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-dashboard
   - https://github.com/casbin/casbin

### 12. 基于 Kubernetes 构建云原生分布式访问控制应用

1. 项目标题：基于 Kubernetes 构建云原生分布式访问控制应用
2. 项目描述：随着云原生技术的普及，Kubernetes 已成为云原生的基石，依赖 Kubernetes 构建一个分布式、可管理多种应用的权限策略的访问控制应用。
3. 项目难度：高
4. 项目社区导师：[张合龙 (BetaCat0)](https://github.com/BetaCat0)
5. 导师联系方式：outman99@hotmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 根据 Casbin 现有的功能，依赖 Kubernetes 实现一个分布式、可管理多种应用的权限策略的访问控制服务端。(优先考虑分布式)
   - 该应用需提供管理端，可提供安装服务端到 Kubernetes 集群，查看应用日志，可管理应用策略
   - 实现把云原生项目接入Casbin访问控制的插件，如k8s的插件：https://github.com/casbin/casbin/issues/470 ，更多的插件实现对象参考：https://www.openpolicyagent.org/docs/latest/ecosystem/ ，我们需要实现类似的插件，扩大我们的生态
8. 项目技术要求：
   - 熟悉 Golang、Kubernetes
   - 具备一定的分布式、云原生应用知识
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin

所有可选项目详见：https://github.com/casbin/Summer2020#可选项目列表

## 候选人要求

### 工作职责：

- 每周与项目导师进行线上讨论，完成项目规定的开发任务。项目导师由开源项目创始人或其他核心成员担任；
- 积极参与开源社区的建设，参与代码提交、解决Issue、审核PR等日常工作；
- 配合完成官方要求的材料提交等事项，包括项目申请书撰写、社区反馈任务完成度追踪等。

### 职位要求：

- 本科、硕士或博士在读（已毕业、工作的无法参加）；
- 对开源软件、开源社区感兴趣；
- 熟悉一种或多种编程语言，有较强的工程能力，代码格式清晰规范，善于团队协作；
- 有一定英文读写能力，能够熟练运用英语在GitHub进行开发、协作；
- 较强的沟通能力和逻辑表达能力。

### 具有以下条件者优先：

- 熟悉计算机网络、网络安全，有相关项目经验；
- 熟悉Go, Rust等语言、分布式系统、微服务架构，有相关项目经验；
- 在GitHub较为活跃，有自己的开源项目，或参与过知名开源项目；
- 可以在项目结束后继续长期参与开源社区的开发、建设或维护。


## 投递要求

申请学生需要同时完成以下“联系社区”和“官网投递”两个环节：

### 1. 联系社区（2020年5月15日至6月20日）

1. 发送【中文简历PDF】至Casbin社区官方邮箱：admin@casbin.org 
2. 加入《Casbin访问控制社区群》（QQ大群）：[546057381](https://shang.qq.com/wpa/qunwpa?idkey=8ac8b91fc97ace3d383d0035f7aa06f7d670fd8e8d4837347354a31c18fac885)
3. 加入《Casbin软件所点亮计划-暑期2020-官方群》（QQ小群）：[632575275](https://shang.qq.com/wpa/qunwpa?idkey=699b016a2892c9e0946047622eec9ae63fc2aeff86ea48a35a075d24c465cbd4) ，联系导师，与导师沟通项目细节和方案，完善项目申请书

### 2. 官网投递（2020年6月1日至6月20日）

详见：https://isrc.iscas.ac.cn/summer2020/help/student.html#学生如何报名
