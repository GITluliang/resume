# 任发凯 </br>
本科 ｜ 5年工作经验 ｜15506466566 ｜ rfk1118@gmail.com </br>

## 求职意向 </br>
Java开发工程师 ｜ 全职 ｜ 北京 ｜ 薪资面议 ｜ 到岗时间面议</br>


## 掌握技能 </br>

* 开发语言: 精通 Java、了解 Golang、汇编</br> 
* 后端框架: 精通 Spring、SpringMvc、Mybatis、SpringBoot、熟悉 SpringData、Struts2、Hibernate 了解 SpringCloud</br>
* 数据库: 精通 Oracle、Mysql 熟悉 Redis</br>
* 中间件: 熟悉 Kafka 了解 Zookeeper、Tidb、Netty</br>
* 服务器: 熟悉 Tomcat</br>
* 构建工具: 熟悉 Maven 了解 Ant</br>
* 项目管理工具: 熟悉 Git</br>
* 脚本语言: 熟悉 Shell</br>
* 设计模式: 熟悉 23 种设计模式</br>
* 网络:了解 Wireshark

## 工作经历 <br/>  

### 沣邦融资租赁（上海）有限公司     Java开发工程师     2018.7-至今 </br>
公司简介:沣邦融资租赁（上海）有限公司（简称“沣邦租赁”）成立于2016年1月，为中信产业基金与滴滴出行投资企业，注册资本130,000万元，总部位于北京。
公司主营个人新车与二手车融资租赁、经销商融资租赁、租赁交易咨询与担保、商业保理等业务，致力于为主机厂、经销商、企事业机构和个人客户提供综合性汽车金融解决方案。</br>

工作描述:
   * 维护旧版扣款系统
   * 负责支付路由设计、搭建、开发、优化和维护
   * 负责账户体系设计、搭建、开发和维护
   
#### 支付路由平台       负责人        2019.8-至今  

项目描述
该项目意在解决沣邦划扣用户月租金、用户便捷支付、沣邦代付、资金方转付、自动化对账、用户要素验证和签约。</br>
扣款通道支持通联、银联、中金、宝付、邮储直联、滴滴钱包。<br/> 

责任描述
* 使用桶排序思想和 Fork/join 框架设计批量划扣,提高扣款执行效率,将旧版的扣款从1h减少到5min;  
* 使用模版设计模式设计扣款结果查询,提供代码复用性和查询模版的隔离;  
* 使用 ByteBuddy 更改中金源代码,使中金在单程序内支持多商户动态切换;  
* 自动化代付使用代付上下文,状态码精细化,对网络故障提供重发功能,提高放款时效性;  
* 使用 Redis.Redlock 分布式锁解决扣款、代付订单校验和发送问题;  
* 自动化对账解决扣款结果跨天问题和扣款数据的准确性;  
* 向Kafka推送扣款结果数据;  

相关技术  
SpringBoot、SpringMvc、Mybatis、Oracle、Kafka、Maven、Redis、Git


#### 财务个人账户系统        负责人        2018.10-至今  

项目描述:
该项目意图搭建财务个人账户,主要包含用户的可用余额、保证金、退款、代偿余额、逾期罚息。</br>
使用业务订单生成引擎保证用户还款，账户根据用户还款对账户进行出入帐及代偿余额处理来支持财务凭证系统。</br>
与系统与资金方(微众银行、工行、中关村银行、江苏金租银行、华瑞银行、中建投银行)进行对接,保证用户增长和资方方扣款的入账。</br>

责任描述
* 使用享元设计模式管理引擎节点,根据业务模版位图选择节点,支持批量扣款,单笔实时和便捷支付;  
* 使用乐观锁设计了账户锁,支持业务场景互斥;  
* 使用责任链设计模式校验和处理账户出入账; 
* 使用位图设计用户提前结清数据权限，多角色权限模版使用或运算合并权限;  
* 提前结清各资方金额计算逻辑编写和抽象;  
* 使用策略设计模式处理资方代偿余额,进行Etl标准化;  
* 逾期罚息计算,根据不同资方使用不同策略进行计算;  
* 使用 Redis.Redlock 解决账户在不同线程互斥问题;  
* Kafka消费订单扣款结果,资方日末解析数据;  

相关技术  
SpringBoot、SpringMvc、Mybatis、Oracle、Kafka、Maven、Redis 、Git

#### 核心系统维护        核心开发        2018.8-2019.11 

项目描述
该项目主要提供了用户贷款申请风控、合同管理、催收模块、财务模块管理、视频面签等功能。</br>

责任描述
* 核心系统批量扣款业务维护,主要包含宝付协议支付、银联、通联、邮储直联
* 单笔实时扣款从手动拆单变更为系统拆单
* 单笔实时扣款通道从宝付迁移到通联支付
* 核心系统还款计划表入账

相关技术  
Spring、Struts2、Hibernate、Jsp、Ant


### 逸途（北京）科技有限公司        Java开发工程师        2015.8-2018.7 </br>
公司简介: 逸途(北京)科技有限公司成立于2015年，是一家专注于人工智能，境外旅游垂直领域研究、开发、生产及销售
的高科技企业。主要产品有逸途旅行、皮皮虾旅行、逸豆等APP，以及逸豆-全能旅行管家翻译机。</br>  
工作描述
   * 参与 AI 智能问答框架的设计和搭建，负责 AI 智能问答核心功能开发和稳定性建设;  
   * 负责翻译机服务 器开发，为翻译机硬件提供软件服务;  
   * 对逸途旅游问答社区开发，为人工智能提供清洗后的数据;  
  
   
#### 智能问答机器人        核心人员        2017.8-2018.7  
项目描述
聚合人工智能和多数据源来实现智能问答，使用 Hanlp 进行自然语言处理，根据词性将问题路由到不同的场景，上行对外提供RPC服务，下行调用相关的模型和数据源服务。</br>  

责任描述
* 将 Hanlp 集成到项目对问题进行自然语言处理;  
* 将 ElasticSearch 上 IK 分词插件替换为 Hanlp 插件，提高引擎搜索命中率;  
* 对分词后的词语使用评分功能进行场景路由;  
* 尝试使用 Tidb 集群替换 ElasticSearch 进行性能优化;  

相关技术  
SpringBoot、SpringMvc、Mybatis、Mysql、ElasticSearch、Redis 、Git

#### 逸途翻译机项目        核心人员        2016.4-2017.7  
项目描述
项目为硬件翻译机提供绑定、解绑及配置、翻译记录云服务，集成讯飞语音合成和FFmpeg为翻译机和逸豆APP提供景点语音。 </br>  

责任描述
* 根据产品需求，翻译机绑定、解绑和翻译记录云服务功能的开发;    
* 参与公司硬件产品翻译机令牌的设计，对token机制有深入的研究;   
* 使用讯飞语音合成景点语音，FFmpeg进行压缩后的语音上传到云服务器，减少客户端重复合成产生的
  费用和减少传输文本的不安全性;  
* 研究服务器合成语音并使用WebSocket推送给客户端，减少翻译机客户端语音合成;   

相关技术  
SpringBoot、 SpringMvc、Mybatis、Mysql、FFmpeg、WebSocket


####  逸途电商系统        核心人员        2015.8-2018.7
项目描述: 该系统为公司参考成熟电商规划的专门针对旅游市场的B2B2C系统，分为B2B的平台管理端、B2C的商家管理
端、WEB展示端及手机展示端，意在统筹管理旅游资源，为用户提供合理的出行服务。 </br>   
责任描述
* 学习电商系统业务;  
* 向电商系统迁移现有后端管理系统所有功能;  
* 根据产品及市场需求，实现对商品、订单、会员、优惠券、配置等业务的维护;  
* 根据产品及市场需求，重构后台管理模式并衍生新的电商系统，如线路系统、签证系统等;  

相关技术  
Spring、SpringMvc、Mybatis、Mysql、Freemarker、Jquery、Ajax、Git


## 自我评价 <br/>  
爱看技术书籍，一年看 10 本书左右，最近在看《领域驱动设计》、《代码大全2》、《编码:隐匿在计算机软硬件背后的语言》等;
爱学习，今年已经学完了Go语言基本语法、Netty、左耳听风分布式系统;














