DataSimba产品FAQ

## 目 录

[工作空间管理](#工作空间管理)1.1

[【首页】登录DataSimba时，系统提示"当前用户不是启用状态"](#首页登录datasimba时系统提示当前用户不是启用状态)1.1.1

[【工作空间概览】账号尚未授予"工作空间数据概览"权限，但实际上可以查看该页面](#工作空间概览账号尚未授予工作空间数据概览权限但实际上可以查看该页面)1.1.2

[【工作空间】开启短信登录验证，但收不到验证码](#工作空间开启短信登录验证但收不到验证码)1.1.3

[【首页】登录DataSimba时，系统提示"工作空间不可用"](#首页登录datasimba时系统提示工作空间不可用)1.1.4

[【权限管理】自己建的表没有读写权限](#权限管理自己建的表没有读写权限)1.1.5

[[集成]{.underline}](#集成)1.2

[【集成】数据同步时，日志提示"ssl.SSLException inbound before receiving
peer\'s
close_notify"](#集成数据同步时日志提示ssl.sslexception-inbound-before-receiving-peers-close_notify)1.2.1

[【数据同步】可视化模式转称脚本模式后，可以再转回可视化模式吗？](#数据同步可视化模式转称脚本模式后可以再转回可视化模式吗)1.2.2

[【集成】任务运行报错"Date类型转换错误"](#集成任务运行报错date类型转换错误)1.2.3

[【数据源】当API数据源，REQUEST
BODY是XML，返回内容是JSON时，该怎么配置](#数据源当api数据源request-body是xml返回内容是json时该怎么配置)1.2.4

[【数据源】数据文件能下载吗？](#数据源数据文件能下载吗)1.2.5

[【数据同步】如何查看数据插入表中的时间？](#数据同步如何查看数据插入表中的时间)1.2.6

[【离线数据同步】来源库的表名，能否根据日期动态更新？](#离线数据同步来源库的表名能否根据日期动态更新)1.2.7

[【数据同步】在「选择来源」时报错"权限校验失败"](#数据同步在选择来源时报错权限校验失败)1.2.8

[【规范建表】规范建表失败，报错"用户没有权限操作该code"](#规范建表规范建表失败报错用户没有权限操作该code)1.2.9

[【数据源】数据同步任务失败，并且搜索不到对应数据源](#数据源数据同步任务失败并且搜索不到对应数据源)1.2.10

[【数据同步】数据量600万，导致同步任务失败](#数据同步数据量600万导致同步任务失败)1.2.11

[【数据同步】源表中间插入新字段，映射关系会出现错行的情况吗](#数据同步源表中间插入新字段映射关系会出现错行的情况吗)1.2.12

[【数据源】规范建表，新建表的时候会选不了数据源](#数据源规范建表新建表的时候会选不了数据源)1.2.13

[【数据同步】传输到impala的数据量为0](#数据同步传输到impala的数据量为0)1.2.14

[[研发]{.underline}](#研发)1.3

[【研发】在IDE界面执行select count(1)
语句，结果返回为0](#研发在ide界面执行select-count1-语句结果返回为0)1.3.1

[【研发】即席查询执行SQL失败，提示：ERROR processing query/statement.
Error Code: 0, SQL state: TStatus(statusCode, sqlState,
errorMessage:AnalysisException: Could not resolve table reference:
\'ods_crm_hyk_jfbdjlmx_di\'](#研发即席查询执行sql失败提示error-processing-querystatement.-error-code-0-sql-state-tstatusstatuscode-sqlstate-errormessageanalysisexception-could-not-resolve-table-reference-ods_crm_hyk_jfbdjlmx_di)1.3.2

[【研发】离线计算按小时周期调度，23点\~24点的数据丢失](#研发离线计算按小时周期调度23点24点的数据丢失)1.3.3

[【治理】已删除的表，在研发页面查询不到，但在资产检索中可以查看](#治理已删除的表在研发页面查询不到但在资产检索中可以查看)1.3.4

[【研发】使用Hive的from_unixtime函数进行"时间戳转化日期格式"时，发现时间差8小时](#研发使用hive的from_unixtime函数进行时间戳转化日期格式时发现时间差8小时)1.3.5

[【研发】在IDE界面执行select \* from where 语句，SQL执行失败并报错error
retrieving next
row](#研发在ide界面执行select-from-where-语句sql执行失败并报错error-retrieving-next-row)1.3.6

[【调度】小时调度任务配置不生效](#调度小时调度任务配置不生效)1.3.7

[【服务】调用外部SDK，平台提示"request was
expired"，错误码为：8018023](#服务调用外部sdk平台提示request-was-expired错误码为8018023)1.3.8

[【服务工厂】DataSimba中API对外提供数据时，每页数据量是否可以上调](#服务工厂datasimba中api对外提供数据时每页数据量是否可以上调)1.3.9

[【研发】使用truncate删除表时，报错"HQL语法检查/鉴权配置不通过"](#研发使用truncate删除表时报错hql语法检查鉴权配置不通过)1.3.10

[【研发】数据开发任务运行失败，报错"用户没有权限操作该code，请求异常：schema
of both sides of union should
match"](#研发数据开发任务运行失败报错用户没有权限操作该code请求异常schema-of-both-sides-of-union-should-match)1.3.11

[【任务依赖】小时任务依赖天任务的逻辑是什么](#任务依赖小时任务依赖天任务的逻辑是什么)1.3.12

[【数据开发】任务执行报错，镜像文件路径错误"sh: /usr/local/bin/python:
No such file or
directory\"](#数据开发任务执行报错镜像文件路径错误sh-usrlocalbinpython-no-such-file-or-directory)1.3.13

[【数据开发】提交任务时，报错"下发队列已满，请稍后再试"](#数据开发提交任务时报错下发队列已满请稍后再试)1.3.14

[【研发】即席查询报错0 of scratch is currently in use by this Impala
Daemon (0 by this
query)](#研发即席查询报错0-of-scratch-is-currently-in-use-by-this-impala-daemon-0-by-this-query)1.3.15

[【实时计算】如何引用本地表，平台目前不支持，该如何解决](#实时计算如何引用本地表平台目前不支持该如何解决)1.3.16

[【数据开发】同一项目下不能使用同名的作业或任务](#数据开发同一项目下不能使用同名的作业或任务)1.3.17

[【研发】SQL中存在\--字符会导致SQL语句解析失败，认为字符后面是注释](#研发sql中存在--字符会导致sql语句解析失败认为字符后面是注释)1.3.18

[【数据开发】一张输出表只能被一个作业写入](#数据开发一张输出表只能被一个作业写入)1.3.19

[【指标工厂】数据建模的表字段数量和实际的表字段数量不一致](#指标工厂数据建模的表字段数量和实际的表字段数量不一致)1.3.20

[【数据开发】同一张表，用hivesql查询有数据，用pyspark查询数据为空](#数据开发同一张表用hivesql查询有数据用pyspark查询数据为空)1.3.21

[【研发】函数管理中新建UDF函数报错](#研发函数管理中新建udf函数报错)1.3.22

[【指标工厂】规范建模中，使用DDL语句建表提示调用存储域建表失败](#指标工厂规范建模中使用ddl语句建表提示调用存储域建表失败)1.3.23

[【服务工厂】API开发的数据API代码中，修改了一个字段导致参数不识别](#服务工厂api开发的数据api代码中修改了一个字段导致参数不识别)1.3.24

[【任务依赖】任务依赖机制是怎么样的](#任务依赖任务依赖机制是怎么样的)1.3.25

[【指标工厂】快捷模式下创建表失败](#指标工厂快捷模式下创建表失败)1.3.26

[[运维]{.underline}](#运维)1.4

[【运维】巡检系统检测到任务异常，该任务强制置为失败状态](#运维巡检系统检测到任务异常该任务强制置为失败状态)1.4.1

[【运维】数据质量运维-规则配置，自定义sql写日期参数无法传参成功，但是替换成固定日期可以试跑成功](#运维数据质量运维-规则配置自定义sql写日期参数无法传参成功但是替换成固定日期可以试跑成功)1.4.2

[【运维】批量补数据，结果不正确](#运维批量补数据结果不正确)1.4.3

[【运维】任务失败，内存溢出](#运维任务失败内存溢出)1.4.4

[【数据质量运维】DataSimba如何针对表的数据量进行监控预警](#数据质量运维datasimba如何针对表的数据量进行监控预警)1.4.5

[【智能监控】当发生基线告警时，该如何处理？](#智能监控当发生基线告警时该如何处理)1.4.6

[【周期任务】点击「立即生成实例」后，原来的实例会被替代](#周期任务点击立即生成实例后原来的实例会被替代)1.4.7

[【邮件告警】配置邮件告警，需要提供哪些信息？](#邮件告警配置邮件告警需要提供哪些信息)1.4.8

[【质量运维】告警信息发送到多个人的邮箱里](#质量运维告警信息发送到多个人的邮箱里)1.4.9

[[服务]{.underline}](#服务)1.5

[【API接口】DataSimba的API接口是否支持https的方式对外提供调用](#api接口datasimba的api接口是否支持https的方式对外提供调用)1.5.1

[【服务工厂】创建的服务不能删除](#服务工厂创建的服务不能删除)1.5.2

[[治理]{.underline}](#治理)1.6

[「资产地图」与「资产分析」中表存储量的统计值不一致](#资产地图与资产分析中表存储量的统计值不一致)1.6.1

[【资产目录】选根目录的话，子目录的表显示不出来](#资产目录选根目录的话子目录的表显示不出来)1.6.2

[[安全]{.underline}](#安全)1.7

[【安全】数据审计、风险识别触发后产生的"危险操作记录（即：明细数据）"是永久保留？](#安全数据审计风险识别触发后产生的危险操作记录即明细数据是永久保留)1.7.1

[【数据安全】静态脱敏的作用及识别规则](#数据安全静态脱敏的作用及识别规则)1.7.2

[【数据安全】敏感数据识别后如何进行动态脱敏](#数据安全敏感数据识别后如何进行动态脱敏)1.7.3

[数据开发](#数据开发)1.8

[任务运行报错，return code 2](#任务运行报错return-code-2)1.8.1

[作业执行报错Caused by: java.lang.AssertionError: Capacity must be a
power of
two](#作业执行报错caused-by-java.lang.assertionerror-capacity-must-be-a-power-of-two)1.8.2

[作业执行报错Error while compiling
statement](#作业执行报错error-while-compiling-statement)1.8.3

[任务运行失败，报错提示：Number of dynamic partitions created is 1001,
which is more than 1000. To solve this try to set
hive.exec.max.dynamic.partitions to at least
1001.](#任务运行失败报错提示number-of-dynamic-partitions-created-is-1001-which-is-more-than-1000.-to-solve-this-try-to-set-hive.exec.max.dynamic.partitions-to-at-least-1001.)1.8.4

[两个字段排序，字段排序不生效](#两个字段排序字段排序不生效)1.8.5

[数据写入其他用户的表里面怎么配置](#数据写入其他用户的表里面怎么配置)1.8.6

[数据过滤这里要实现功能需要怎么写](#数据过滤这里要实现功能需要怎么写)1.8.7

[任务运行报错"Table insclause-0 has 72 columns, but query has 71
columns"](#任务运行报错table-insclause-0-has-72-columns-but-query-has-71-columns)1.8.8

[运行任务无权限操作code](#运行任务无权限操作code)1.8.9

[任务保存后运行还是旧代码](#任务保存后运行还是旧代码)1.8.10

[实时任务停不下来](#实时任务停不下来)1.8.11

[数据中台写Python代码，缺少依赖的包](#数据中台写python代码缺少依赖的包)1.8.12

# 工作空间管理

# 【首页】登录DataSimba时，系统提示"当前用户不是启用状态"

**问题描述**：登录DataSimba平台时，提示"当前用户不是启用状态，无法登录"

**涉及版本**：DataSimba R4及以上版本

**问题分类**：使用问题

示例说明**：**

![45c180498dfa652b9a834430072aff45.png](./media/media/45c180498dfa652b9a834430072aff45.png){width="6.5in"
height="3.013888888888889in"}

原因及方案**：**

该账号被"禁用"或"到期时间"已到。请联系平台管理员账号给该账号进行"启用"或延长到期时间。

![4fa77d352ca5e0d02806a1937cd03979.png](./media/media/4fa77d352ca5e0d02806a1937cd03979.png){width="6.5in"
height="5.277777777777778in"}

![4fd3cfa46520bedb376b4af2cedd9a87.png](./media/media/4fd3cfa46520bedb376b4af2cedd9a87.png){width="6.5in"
height="2.0972222222222223in"}

# 【工作空间概览】账号尚未授予"工作空间数据概览"权限，但实际上可以查看该页面

**问题描述**：账号尚未授予"工作空间数据概览"权限，但实际上可以查看该页面

**问题分类**：使用问题

**涉及版本**：R4及以上版本

![247c9b429b587828ced4ff619d1357a6.png](./media/media/247c9b429b587828ced4ff619d1357a6.png){width="6.5in"
height="2.111111111111111in"}

![52a5b14471d4aeacec213968dd5cf1b7.png](./media/media/52a5b14471d4aeacec213968dd5cf1b7.png){width="6.5in"
height="7.083333333333333in"}

问题原因**：**

目前，平台级角色只支持内置的平台管理员和平台访客（不支持自定义）。【工作空间数据概览】模块是平台级功能，目前还不支持自定义配置。

**关联JIRA**:<https://jira.startdt.net/browse/PPTWOM-5955>

# 【工作空间】开启短信登录验证，但收不到验证码

**问题描述**：开启短信登录验证后，页面提示"验证码已发送至手机号"，但一直收不到短信

**涉及版本**：DataSimba R4及以上版本

**问题分类**：使用问题

示例说明**：**

![f07bbb62155cea12102183bdff7a9d20.png](./media/media/f07bbb62155cea12102183bdff7a9d20.png){width="6.5in"
height="4.097222222222222in"}

**问题原因**：客户没有购买短信服务包，未开通短信服务。

处理方式**：**

1.  询问客户是否需要短信验证服务，若需要，联系CSM或销售，走商务流程；

2.  若不需要，联系数据云运维同学，执行如下sql，关闭短信验证功能；

update \`simba_os_upms\`.\`tbl_simba_os_product_security_config\`\
set sms_code_needed = 0\
where product_id = 10;

注：运维工程师在执行SQL前，请找研发仔细确认**。**

**关联jira**：<https://jira.startdt.net/browse/PPTWOM-3453>

# 【首页】登录DataSimba时，系统提示"工作空间不可用"

**问题描述**：登录DataSimba平台，系统提示"工作空间不可用"

**涉及版本**：DataSimba R4及以上版本

**问题分类**：使用问题

：

![5fa1c0e3ec4357aa7901411e1ef512d6.png](./media/media/5fa1c0e3ec4357aa7901411e1ef512d6.png){width="6.5in"
height="2.611111111111111in"}

**原因一**：登陆地址错误，域名和IP地址访问只能选择其中一种。

处理方式**：**

1.询问客户出现"工作空间不可用"的异常后，能否正常进入DataSimba且不影响各个功能正常使用，若能正常登陆，可判断DataSimba不存在问题。

2.询问客户目前使用IP还是域名登陆。

-   若使用IP登陆，出现"工作空间不可用"的异常，则询问客户是否将登陆地址映射为域名；

-   若使用域名登陆，出现"工作空间不可用"的异常，则询问客户是否有更换过域名；

3.让客户提供域名后，联系数据云运维，将登陆地址修改为域名

4.若存在其他情况，则看原因二

**原因二**：DataSimba服务异常

处理方式**：**

1.  若非原因一，则提交工单，联系数据云运维处理。

域名和IP地址访问只能选择其中一种。DataSimba初始登陆地址，配置的是IP地址，客户将IP映射成域名后，同时需要联系数据云运维同学，将登陆地址修改为域名

# 【权限管理】自己建的表没有读写权限

**问题描述**：自己创建的表，却没有读写权限。\
提示【数据权限校验不通过，中止作业执行】

报错日志如下：\
Permission denied: user \[daishi@datasimba\] does not have
table:\[ods_weclient_plan_task_conditions_di\] privilege on
\[/coach_cdp_db/ods_weclient_plan_task_conditions_di/id,plan_id,task_id,conditions,content,content_type,created_at,updated_at,deleted_at\]

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

**问题原因**：没有目标表的权限

**解决方案**：请在「工作空间控制台-数据权限策略」中调整权限策略的授权范围，或者重新创建新的权限策略，以赋予操作账户对目标表的读写权限。

![963e007d6f2f2ea1f6cdc26ceb96b50a.png](./media/media/963e007d6f2f2ea1f6cdc26ceb96b50a.png){width="6.5in"
height="7.208333333333333in"}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6785>

# 集成

集成频道主要面向数据和算法开发工程师，致力于在复杂网络环境下，实现异构数据源间高速稳定的数据移动与同步，从而高效地为研发工作提供准确、及时的数据准备。

# 【集成】数据同步时，日志提示"ssl.SSLException inbound before receiving peer\'s close_notify"

**问题描述**：【集成】数据同步时，日志提示"ssl.SSLException inbound
before receiving peer\'s close_notify"

**问题分类**：使用问题

**涉及版本**![72aaa7131e4a8874fe2814c0d4d3a043.png](./media/media/72aaa7131e4a8874fe2814c0d4d3a043.png){width="6.5in"
height="2.4166666666666665in"}

解释说明**：**

在连接数据库时，在不验证服务器身份的情况下建立了SSL连接，根据mysql5.5.45+、5.6.26+、5.7.6+的要求，如果设置没有显示选项，那么缺省情况下必须建立SSL连接，为了符合不使用SSL的现有应用程序，需要通过设置useSSL=false显示禁用SLL。

解决方案**：**

在数据源jdbc加上参数useSSL=false。例如：jdbc:mysql://255.255.255.255:3306/simba_test?serverTimezone=Asia/Shanghai&***useSSL=false***

# 【数据同步】可视化模式转称脚本模式后，可以再转回可视化模式吗？

**问题描述**：当将可视化模式转换为脚本模式后，是否可以再次将其转换回可视化模式？

**问题分类**：使用问题

**涉及版本**：所有DataSimba版本

**问题回复**：不能。目前的转换逻辑是单向的。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5879>

# 【集成】任务运行报错"Date类型转换错误"

**问题描述**：从DataSimba
Hive库同步数据到MySQL库，字段均为date类型。在规范建表时，运行任务报错"Data类型转换错误"。如图所示，new_sqrq是date类型，在日志中显示string类型。

**问题类型**：使用问题

**涉及版本**：DataSimba R4以上版本

![10e1d70eb8a12c6a55073511fa48171e.png](./media/media/10e1d70eb8a12c6a55073511fa48171e.png){width="6.5in"
height="4.236111111111111in"}

![22cea71e8377bba768adca71e04489c9.png](./media/media/22cea71e8377bba768adca71e04489c9.png){width="6.5in"
height="4.152777777777778in"}

![a9ed8963d428b2ed4b2e4b6ba9d98909.png](./media/media/a9ed8963d428b2ed4b2e4b6ba9d98909.png){width="6.5in"
height="2.4722222222222223in"}

**问题原因**：当前版本中，PARQUET结构的Hive表不支持date类型

**解决方式**：将hive表中所有data字段类型改为string类型

**关联jira**：<https://jira.startdt.net/browse/PPTWOM-5344>

# 【数据源】当API数据源，REQUEST BODY是XML，返回内容是JSON时，该怎么配置

**问题描述**：当APi数据源，REQUEST
DODY是XML，返回内容是JSON时，该怎么配置？目前产品页面上只能设置请求参数，无法设置REQUEST
RAYLOAD

**问题类型**：使用问题

**涉及版本**：DataSimba R4.X及以上版本

解决方式**：**

目前数据集成对于API数据源不支持设置payload，只能通过pyspark或Python脚本来解析获取动态API的数据，并将请求数据放入表中。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5858>

# 【数据源】数据文件能下载吗？

**问题描述**：数据源管理中，数据文件是否能下载？

**问题类型**：使用问题

**涉及版本**：DataSimba所有版本

![233382ec4e60aa2c4fe5b524773eaf3f.png](./media/media/233382ec4e60aa2c4fe5b524773eaf3f.png){width="6.5in"
height="1.4722222222222223in"}

问题回复**：**

DataSimba是数据使用的平台，而不是类似于网盘系统这样的存储平台，故DataSimba产品功能不支持下载数据文件。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6047>

# 【数据同步】如何查看数据插入表中的时间？

**问题描述**：数据插入表中的时间有日志能查到吗？

**问题分类**：使用问题

**涉及版本**：所有DataSimba版本

解释说明**：**

集成同步作业的日志结尾会记录数据插入的时间，而研发任务的日志中通常没有明确的时间标注。一般来说，我们认为当日志结束时，数据插入也就结束了，可以根据日志结束时间来参考。此外，在某些情况下，数开用户可以在表中新增一个etl_time字段，用于记录数据入库时的当前系统时间。这样就可以更准确地记录数据的时间信息了。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6042>

# 【离线数据同步】来源库的表名，能否根据日期动态更新？

**问题描述**：离线数据同步，来源库的表名，能否是动态的？类似于tab\_{yyyyMM}，这个月自动识别为202406，下个月自动识别为202407\
客户上游库是采用自动分库分表模式，同步到下游
hive，按照分区来存储不同周期表的数据

![abb0da1afcc220644575a440699f7e09.png](./media/media/abb0da1afcc220644575a440699f7e09.png){width="3.875in"
height="3.0972222222222223in"}

**问题分类**：使用问题

**涉及版本**：所有DataSimba版本

问题回复**：**

打开同步任务，点击【转化脚本】，在脚本模式下，修改 reader
下的表名，在表名后添加
\${yyyyMM}，任务运行的时候，就会将动态的时间参数替换为日期，实现表名自动根据日期变化的效果

![64a0d847ba2ef80587a27d5a18cffddd.png](./media/media/64a0d847ba2ef80587a27d5a18cffddd.png){width="4.902777777777778in"
height="3.7777777777777777in"}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6292>

# 【数据同步】在「选择来源」时报错"权限校验失败"

**问题描述**：在数据同步过程中，当用户选择数据来源时，页面会弹出一个错误提示，显示"权限校验失败"。

**问题分类**：使用问题

**涉及版本**：DataSimba R4及以上所有版本

![aab1fa1cb2089541192492310a8a55e0.png](./media/media/aab1fa1cb2089541192492310a8a55e0.png){width="6.5in"
height="1.7222222222222223in"}

问题原因**：**

操作账号无目标表操作权限

解决方案**：**

请在「工作空间控制台-数据权限策略」中调整权限策略的授权范围，或者重新创建新的权限策略，以赋予操作账户对目标表的读写权限。

**关联Issue**: <https://jira.startdt.net/browse/PPTWOM-6532>

# 【规范建表】规范建表失败，报错"用户没有权限操作该code"

问题描述：【**规范建表**】规范建表失败，报错"用户没有权限操作该code"

**问题分类**：使用问题

**涉及版本**：所有版本

![9908d5b8dabe99548dcc1fd6a4c499af.png](./media/media/9908d5b8dabe99548dcc1fd6a4c499af.png){width="6.5in"
height="6.888888888888889in"}

**问题原因一**：权限认证服务通信异常

解决方式**：**

1、询问客户其他账号进行同样的规范建表操作，是否报同样的错误；

2、若其他账号同样报错，则提交工单，检查是否服务存在异常；

3、若只有该账号规范建表时报错，则将账号移出项目并重新添加；

4、若以上方式不能解决问题，则看原因二

**问题原因二**：源表的字段或注释信息不符合数据开发规范

解决方式**：**

1、请客户提供源表的字段和注释信息，例如：mysql数据源，使用show create
table xxx 将结果提供出来

2、查看源表的字段或注释信息是否有不符合数据开发规范的

如该问题中的源表信息为：

![e6f9c142ca78c353354d62c9cd18f988.png](./media/media/e6f9c142ca78c353354d62c9cd18f988.png){width="5.25in"
height="9.0in"}

字段的注释中包含分号，被识别为多张表

3、删除注释中的分号

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-4367>

# 【数据源】数据同步任务失败，并且搜索不到对应数据源

**问题描述**：数据同步任务失败，并且作业当中显示的数据源信息，在实际的列表中搜索不到。

**问题分类**：使用问题

**涉及版本**![3cd01aed64e23c3bd59884b8119bd050.png](./media/media/3cd01aed64e23c3bd59884b8119bd050.png){width="6.5in"
height="7.597222222222222in"}

![cb7cbd2d01dd72934360b2e1d70266d2.png](./media/media/cb7cbd2d01dd72934360b2e1d70266d2.png){width="6.5in"
height="5.75in"}

**问题原因**：数据源名称修改后，作业中的数据源名称没有修改保存。

**解决方案**：修改数据源名称之后 需要重新选择一下数据源和表 保存一下作业

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6854>

# 【数据同步】数据量600万，导致同步任务失败

**问题描述**：数据中台同步任务数据有600多万条
现在同步都报错，是要配置什么吗

**问题分类**：咨询问题

**涉及版本**![8e56480a59ff6fed37bb4c2f4ccc5f20.png](./media/media/8e56480a59ff6fed37bb4c2f4ccc5f20.png){width="4.861111111111111in"
height="9.0in"}

**问题原因**：数据量过大导致同步报错

**解决方案**：需要调整并发，\
1.可以使用 5M/s 5并发，\
2.可以使用 10M/s 10并发，需要调节jvm，默认的1g扛不住：jvm=-Xms1g -Xmx2g

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6959>

# 【数据同步】源表中间插入新字段，映射关系会出现错行的情况吗

**问题描述**：数据同步作业源表和目标表的映射关系选择同行映射时，如果源表中间插入一个新字段，原来的映射关系会出现错行的情况么？

例如：源表原有A1、B1、C1这3个字段，选择同行映射，分别对应目标表A2、B2、C2，目前在源表A1和B1中间插入一个字段D1，源表和目标表的关系是保持不变为A1-A2、B1-B2、C1-C2，还是会变成A1-A2、D1-B1、B1-C2

**问题分类**：咨询问题

**涉及版本**：DataSimba 所有版本

**解释说明**：源表新增字段会打乱索引，即会出现错行的情况

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6832>

# 【数据源】规范建表，新建表的时候会选不了数据源

**问题描述**：数据源是连通的，使用规范建表中可视化建表的时候选不了TiDB数据源。

**问题分类**：使用问题

**涉及版本**![7245f31ae62663eb3ce6c55a87948298.png](./media/media/7245f31ae62663eb3ce6c55a87948298.png){width="4.791666666666667in"
height="9.0in"}

**问题原因**：当前版本规范建表中可视化建表不支持该数据源，对数据源类型有限制，当前只支持选择MySQL、SQLServer、Oracle、PgSQL、Hive、DB2这六个数据源。

**解决方案**：规范建表中不使用可视化建表，使用DDL建表的方式，手动创建TiDB到Hive的同步作业

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6790>

# 【数据同步】传输到impala的数据量为0

**问题描述**：传输到impala的数据量为0，但是任务显示成功。

**问题分类**：使用问题

**涉及版本**：DataSimba3.x

解释说明**：**

![a6083e511fb9de5a04fc5eaa78cf63a2.png](./media/media/a6083e511fb9de5a04fc5eaa78cf63a2.png){width="4.319444444444445in"
height="9.0in"}

针对Simba
Shell任务的状态为什么是成功的问题，客户使用impala-shell与impala
server进行交互式任务提交，错误信息是impala-server返回给impala-shell的日志，这些信息属于数据任务内部的业务逻辑，对于Shell来说就是正常的交互信息，DataSimba只有在Shell中异常退出的情况下才会设置任务的状态为失败，若想要避免数据传输为0且任务成功，可以在shell任务中自定义实现捕获异常日志，通知shell进程异常退出，进而DataSimba根据异常判断任务成功与否。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6727>

# 研发

# 【研发】在IDE界面执行select count(1) 语句，结果返回为0

**问题描述**：在IDE界面执行select count(1) 语句，结果返回为0

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x LTS版

示例说明**：**

![f45466f06e71f6d8160533cec1267aaa.png](./media/media/f45466f06e71f6d8160533cec1267aaa.png){width="6.5in"
height="4.125in"}

问题原因及**：**

这个问题可能是由于Hive中的一个优化参数\[hive.compute.query.using.stats\]导致的。当该参数设置为true时，对于一些使用频率较高的SQL会进行查询优化，提高响应速度。然而，对于某些查询如select
count(1)，它可能仅利用元数据存储中保存的状态信息返回结果，导致查询结果为0。

解决方案**：**

将【***hive.compute.query.using.stats***】参数设置为***false***，即set
hive.compute.query.using.stats=false，然后再运行count查询即可得到正确的结果。

# 【研发】即席查询执行SQL失败，提示：ERROR processing query/statement. Error Code: 0, SQL state: TStatus(statusCode, sqlState, errorMessage:AnalysisException: Could not resolve table reference: \'ods_crm_hyk_jfbdjlmx_di\'

**问题描述**：即席查询执行SQL失败，提示：ERROR processing
query/statement. Error Code: 0, SQL state: TStatus(statusCode, sqlState,
errorMessage:AnalysisException: Could not resolve table reference:
\'ods_crm_hyk_jfbdjlmx_di\'

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x 系列

解释说明**：**

由于Impala组件特性所致，需要手动清除Impala catalog里的缓存，通过【
invalid metadata 表名 】命令进行刷新。

解决方案**：**

1.  在研发IDE界面，创建Impala SQL任务；

2.  数据开发工程师（TM）在研发模块执行 invalidate metadata;

3.  数据开发工程师（TM）到即席查询界面执行 select 语句，验证结果。

# 【研发】离线计算按小时周期调度，23点\~24点的数据丢失

**问题描述**：离线计算按小时周期调度，23点\~24点的数据丢失

**问题分类**：使用问题

**涉及版本**：DataSimba R3.8.0

示例说明**：**

某月25号分区的晚上23点至24点数据丢失。23点最后一次调度完成后，新的一天0点开始抽的数据几乎为空。

解决方法**：**

1.  数据同步任务：小时调度将数据写入目标端的相应小时分区。

2.  数据同步的下游任务：将小时分区合并到日分区。

# 【治理】已删除的表，在研发页面查询不到，但在资产检索中可以查看

**问题描述**：已删除的表，在研发页面查询不到，但在资产检索中可以查看

**问题分类**：使用问题

**涉及版本**：DataSimba R4.4.0

原因及方案**：**

这是因为表被删除后，元数据信息没有及时更新。解决方法是在工作空间管理中，使用"重置元数据"功能对项目的元数据进行重置。

# 【研发】使用Hive的from_unixtime函数进行"时间戳转化日期格式"时，发现时间差8小时

**问题描述**：使用Hive的from_unixtime函数进行"时间戳转化日期格式"时，发现时间差8小时

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x

示例说明**：**

select from_unixtime(1706614631)\
\
计算结果时间：2024-01-30 11:37:11\
\
实际北京时间：2024-01-30 19:37:11

原因及方案**：**

首先，导致这个问题的原因是Hive
3.1.3的特性，它默认返回的是UTC格式。解决方法：数据开发工程师应根据实际时区格式进行处理。例如：

-   不可靠SQL：在Hive
    3.1.3及以后版本的特性，from_unixtime函数的默认结果如下：

select from_unixtime(1706614631);\
\
计算结果时间：2024-01-30 11:37:11

-   可靠SQL：在Hive
    3.1.3及以后版本的特性，from_unixtime函数的默认结果如下：

select cast(from_utc_timestamp(cast(1706614631 as bigint) \* 1000,
\'GMT+8\') as string);\
\
计算结果时间：2024-01-30 19:37:11

# 【研发】在IDE界面执行select \* from where 语句，SQL执行失败并报错error retrieving next row

**问题描述**：在IDE界面执行select \* from where
语句，SQL执行失败并报错error retrieving next row

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

示例说明**：**

![a2dd2b79dd641f1c1ef10a20dee32cff.png](./media/media/a2dd2b79dd641f1c1ef10a20dee32cff.png){width="6.5in"
height="6.277777777777778in"}

解释说明**：**

该SQL报错是因为：hive客户端去查询数据时使用hive引擎机制，从HDFS拉取数据下来，在hive内存中计算匹配符合条件的数据，导致数据匹配超时，并且该表的数据量也比较大，当前平台客户端超时时间是60s，该SQL每次查询都是在60+，如果在系统空闲时，低于60s可以正常查询出来。

解决方案**：**

通过 ***order by*** 排序算子，让SQL强制上yarn，可解决该问题select \*
from ods_idcst10_ccc_file_df where ds = \'20240229\' and ccc01 =
\'82900001\' order by ccc01,ccc02;

# 【调度】小时调度任务配置不生效

**问题描述**：小时调度任务配置不生效

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

示例说明**：**

任务1调度时间配置01时,10时；任务2调度时间配置00时,09时。任务2依赖任务1。观察运行结果。

解决说明**：**

在小时调度中，只有当调度时间相同时，才会形成有效的依赖配置，否则依赖将不会生效。

# 【服务】调用外部SDK，平台提示"request was expired"，错误码为：8018023

**问题描述**：调用外部SDK，平台提示"request was
expired"，错误码为：8018023

**问题分类**：使用问题

**涉及版本**：DataSimba R4.9.0.4

示例说明**：**

![b488c1b8a8a05dfb46f8fdf0a16ad4fa.png](./media/media/b488c1b8a8a05dfb46f8fdf0a16ad4fa.png){width="6.5in"
height="4.208333333333333in"}

解释说明**：**

若时间戳（timestamp）超过当前时间5分钟，则会提示请求已失效。

解决方案**：**

将时间戳（timestamp）设置为当前时间。

# 【服务工厂】DataSimba中API对外提供数据时，每页数据量是否可以上调

**问题描述**：【服务工厂】DataSimba中API对外提供数据时，每页数据量是否可以上调

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

示例说明**：**

客户在代码中，设置参数 pagesize,pagenum
调整每页返回数量，每页设置5000，但是每页返回依旧是2000条。如图：

![0907b0c5aef32cd444ac7e6797e61a38.png](./media/media/0907b0c5aef32cd444ac7e6797e61a38.png){width="6.5in"
height="2.1527777777777777in"}

原因及方案**：**

在服务工厂进行API开发后，如数据量较大，返回参数配置里勾选上【返回结果分页】；（以下截图为R5.2.0旗舰版，与当前客户环境版本菜单可能会存在一定不同，但整体逻辑不变）。

![b93202faaac13a1219e1e14b10a5a919.png](./media/media/b93202faaac13a1219e1e14b10a5a919.png){width="6.5in"
height="2.513888888888889in"}

保存API后，在【测试】中调试API或实际请求时，可根据实际场景需要，配置pageSize、pageNum参数，来调整每页返回条数。

![388cc40743163f5d8fe670a7d00bc86c.png](./media/media/388cc40743163f5d8fe670a7d00bc86c.png){width="6.5in"
height="3.236111111111111in"}

# 【研发】使用truncate删除表时，报错"HQL语法检查/鉴权配置不通过"

**问题描述**：Hive
SQL作业中，使用truncate删除外部表时，报错"HQL语法检查/鉴权配置不通过，中止作业运行"

**问题分类**：使用问题

**涉及版本**：DataSimba R5.2.0

![fd35a473f444f1bfd7b7bb46c7bef1d1.png](./media/media/fd35a473f444f1bfd7b7bb46c7bef1d1.png){width="6.5in"
height="6.388888888888889in"}

问题原因**：**

Hive SQL 作业中，因为外部表的数据不是存放在Meta
Store中，故不能使用truncate删除外部表。

**文献参考**：<https://blog.csdn.net/gdkyxy2013/article/details/81200924>

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-3039>

# 【研发】数据开发任务运行失败，报错"用户没有权限操作该code，请求异常：schema of both sides of union should match"

**问题描述**：数据开发任务运行失败，报错"用户没有权限操作该code，请求异常：schema
of both sides of union should match"

**问题分类**：使用问题

**涉及版本**：所有版本

![09b77afa67f05357eac2bb1915a4b0ad.png](./media/media/09b77afa67f05357eac2bb1915a4b0ad.png){width="6.5in"
height="4.652777777777778in"}

问题原因**：**

union
会把查询结果拼接起来，但是要求两个查询结果的列数、列名必须保持一致。

解决方案**：**

请用户自查sql，使两个查询结果的列数、列名保持一致

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-3112>

# 【任务依赖】小时任务依赖天任务的逻辑是什么

**问题描述**：如果小时任务前置依赖天任务，天任务定时时间设置到0点，小时任务每小时执行一次，天任务执行成功后，1点以后的小时任务会按照定时时间正常执行么？

**问题分类**：咨询问题

**涉及版本**：DataSimba R4.x 系列

解释说明**：**

小时任务依赖的天任务时，只有相同时间的实例才会形成依赖，其它时间点的不会形成依赖。\
场景如下：

-   任务情况：小时任务2小时执行一次，天任务6点执行。

-   实例： 小时2，小时4、小时6、小时8、小时10\...\...。

-   依赖关系：小时6依赖天6点，其他时间点实例不依赖天任务。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5832>

# 【数据开发】任务执行报错，镜像文件路径错误"sh: /usr/local/bin/python: No such file or directory\"

**问题描述**：任务执行报错，镜像文件路径错误，报错："sh:
/usr/local/bin/python: No such file or directory\"

**问题分类**：使用问题

**涉及版本**：DataSimba R5.2.0

![78d27b035ea80d1d4610f48e8d646b4c.png](./media/media/78d27b035ea80d1d4610f48e8d646b4c.png){width="6.5in"
height="3.3333333333333335in"}

问题原因**：**

镜像文件路径错误

解决方式**：**

1.  检查构建镜像的dockerfile文件中配置的路径是否为/usr/local/bin/python（dockerfile文件示例如下）

2.  如果不是则需要将对应作业基本信息中的执行路径修改为dockerfile中对应的路径。

![e0741bc7187de752f5580572cbc32b50.png](./media/media/e0741bc7187de752f5580572cbc32b50.png){width="6.5in"
height="4.888888888888889in"}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5835>

# 【数据开发】提交任务时，报错"下发队列已满，请稍后再试"

**问题描述**：提交任务时，报错"下发队列已满，请稍后再试"

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x及以上

![02d26cb405dc60c3e8113984052b56c0.png](./media/media/02d26cb405dc60c3e8113984052b56c0.png){width="6.5in"
height="2.7083333333333335in"}

解释说明**：**

DataSimba提交任务后，会首先进入DataSimba本身的队列，然后再被下发到底层的引擎执行。当出现这个异常时，意味着DataSimba本身的队列已经满载，这可能是因为当前有大量任务正在下发导致的。建议稍等片刻后再尝试提交任务。

**关联Issue**:<https://jira.startdt.net/browse/PPTWOM-5870>

# 【研发】即席查询报错0 of scratch is currently in use by this Impala Daemon (0 by this query)

**问题描述**：即席查询时出现错误：java.sql.SQLException\[Cloudera\][[ImpalaJDBCDriver]{.underline}](#研发即席查询报错0-of-scratch-is-currently-in-use-by-this-impala-daemon-0-by-this-query)
ERROR processing query/statement. Error Code: 0, SQL state: Could not
create files in any configured scratch directories (\--scratch_dirs=) on
backend \'dgprod-5:27000\'. 0 of scratch is currently in use by this
Impala Daemon (0 by this query). See logs for previous errors that may
have prevented creating or writing scratch files. The following
directories were at capacity:

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x及以上

问题原因**：**

Impala使用临时目录来存储执行查询时的临时数据。当出现报错信息 \"0 of
scratch is currently in use by this Impala Daemon (0 by this query)\"
时，意味着没有足够的空间来存储本次查询的临时数据。

解决方式**：**

请数开同学优化查询执行语句，减少查询时的临时数据。

# 【实时计算】如何引用本地表，平台目前不支持，该如何解决

**问题描述**：实时计算需要引用本地表，平台目前不支持，该如何解决

**问题分类**：咨询问题

**涉及版本**：所有DataSimba版本

解决方案**：**

目前实时模块尚不支持引用本地表的功能。实时计算仅支持临时表，其中临时表源端和结果端分别映射到源表和结果表。源端和结果端均支持各类通用业务库。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5935>

# 【数据开发】同一项目下不能使用同名的作业或任务

**问题描述**：新建离线作业时，报错"当前项目下作业名称已经存在"。但在作业开发中查询该表名时，查询不到。

**问题分类**：使用问题

**涉及版本**：DataSimba所有版本

![d576538ccca9b775dd55c7b4a93a2ef0.png](./media/media/d576538ccca9b775dd55c7b4a93a2ef0.png){width="6.5in"
height="2.8333333333333335in"}

![de17f4069a259a0bb54a225ef29ebe3b.png](./media/media/de17f4069a259a0bb54a225ef29ebe3b.png){width="6.5in"
height="1.8888888888888888in"}

问题原因**：**

同一个项目下不能使用同名的作业或任务

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5958>

# 【研发】SQL中存在\--字符会导致SQL语句解析失败，认为字符后面是注释

**问题描述**：SQL中存在"\--"字符会导致SQL语句解析失败，认为字符后面是注释

**问题类型**：使用问题

**涉及版本**：DataSimba所有版本

![399322935e38768188b9296c2dd22028.png](./media/media/399322935e38768188b9296c2dd22028.png){width="6.5in"
height="1.7083333333333333in"}

问题原因**：**

simba-osmicro-processor项目SparkSqlTaskRunner.replaceComment()类在解析sparkSql的时候，正则匹配将\'\-\--\'识别成了注释；当前正则匹配逻辑如下：

private static final String REGEX =
\"(\--.\*)+\|/\\\\\*\[\^\\\\+\](\\\\n\|.)\*?\\\\\*/\";

解决方案**：**

平台一直都是准守以上正则的匹配逻辑，会匹配\--.\*作为注释截取，请数开遵循平台规范进行开发。

**关联Issue**:<https://jira.startdt.net/browse/PPTWOM-6005>

# 【数据开发】一张输出表只能被一个作业写入

**问题描述**：运行任务，报错"作业'XXX'的输出表已存在于任务定时调度中，输出表名称：xxx"

**问题分类**：使用问题

**涉及版本**：DataSimba所有版本

![955f4d39e63f2984163d99b2549158f7.png](./media/media/955f4d39e63f2984163d99b2549158f7.png){width="6.5in"
height="2.9305555555555554in"}

问题原因**：**

为了确保数据写入的正确性，产品设计了该机制，即「不允许多个作业里存在同一个输出表」。如果没有这个限制，就会存在多个作业往一个表中写入数据的情况，可能会导致数据相互覆盖的问题，影响写入数据的正确性。

解决方案**：**

建议使用规范建表创建原始表，创建原始表的同时选择生成同步作业，即「任务名
= 表名」，使每个表只存在一个任务中。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6090>

# 【指标工厂】数据建模的表字段数量和实际的表字段数量不一致

**问题描述**：在指标工厂和研发模块中查看同一张表时，发现字段数量显示不一致。

**问题分类**：使用问题

**涉及版本**：DataSimba R5LTS及以下所有版本

![87c739421951d50abf0b4f4d038f3bd0.png](./media/media/87c739421951d50abf0b4f4d038f3bd0.png){width="6.5in"
height="2.4444444444444446in"}

![19ce21c4e359b0ceecfe05f743b84877.png](./media/media/19ce21c4e359b0ceecfe05f743b84877.png){width="6.5in"
height="2.8055555555555554in"}

问题原因**：**

在DataSimba中直接使用HiveSQL修改表字段会导致指标的业务数据与实际的Hive源数据不一致。

解决方案**：**

删除表并重新构建。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6466>

# 【数据开发】同一张表，用hivesql查询有数据，用pyspark查询数据为空

**问题描述**：当在使用HiveSQL查询时，同一张表返回了数据；然而，当使用PySpark查询相同表时，结果却为空。

**问题分类**：使用问题

**涉及版本**：DataSimba R4及以上所有版本

![e6f5b1fcfc2e2ad76460d3d82f45bb69.png](./media/media/e6f5b1fcfc2e2ad76460d3d82f45bb69.png){width="6.5in"
height="4.013888888888889in"}

![7cc0c703c133b3bcfea11710b502d44c.png](./media/media/7cc0c703c133b3bcfea11710b502d44c.png){width="6.5in"
height="4.097222222222222in"}

**问题原因**：当使用PySpark查询Hive时，无法直接支持union操作

解决方案**：**

该问题有两种解决方案

方案1：请先检查所查表的格式，然后在环境变量中添加相应的配置。

若所查表为parquet格式的表，添加如下配置：\
spark.hive.mapred.supports.subdirectories=true\
spark.hadoop.mapreduce.input.fileinputformat.input.dir.recursive=true\
spark.hadoop.mapred.input.dir.recursive=true\
spark.sql.hive.convertMetastoreParquet=false

若所查表为orc格式的表，添加如下配置：\
spark.hive.mapred.supports.subdirectories=true\
spark.hadoop.mapreduce.input.fileinputformat.input.dir.recursive=true\
spark.hadoop.mapred.input.dir.recursive=true\
spark.sql.hive.convertMetastoreOrc=false

如图所示：

![692e48050704bb8a2ed8d2ef352ee4a9.png](./media/media/692e48050704bb8a2ed8d2ef352ee4a9.png){width="6.5in"
height="3.0694444444444446in"}

方案2：新建临时表，并将数据写入其中，然后通过查询临时表的方式来检索数据。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6495>

# 【研发】函数管理中新建UDF函数报错

**问题描述**：在函数管理中新建UDF函数，提示系统错误，请联系管理员。

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

![bcc3625c83675702a1512543d6a9d0c7.png](./media/media/bcc3625c83675702a1512543d6a9d0c7.png){width="5.611111111111111in"
height="9.0in"}

**问题原因**：类名必须与资源中的类名一致，类名没有填写完整

**解决方案**：将类名填写完整，类名必须与资源中的类名一致

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6902>

# 【指标工厂】规范建模中，使用DDL语句建表提示调用存储域建表失败

**问题描述**：在规范建模中，使用DDL语句建表提示调用存储域建表失败

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x版本

![2f7e1ab7f3f252c26427c979da012386.png](./media/media/2f7e1ab7f3f252c26427c979da012386.png){width="4.402777777777778in"
height="9.0in"}

**问题原因**：建表语句中有重复字段

**解决方案**：删除或修改重复字段

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6908>

# 【服务工厂】API开发的数据API代码中，修改了一个字段导致参数不识别

**问题描述**：API开发的数据API代码中，修改了fwtype字段导致参数不识别，提示API未配置请求参数，请开启返回结果分页功能。一定要去开那个分页功能吗

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x版本

![56f2dd4da7babd31857ee2181adb0f5f.png](./media/media/56f2dd4da7babd31857ee2181adb0f5f.png){width="3.611111111111111in"
height="9.0in"}

**问题原因**：语法解析树解析不出来多层case when 的内容，客户使用多层case
when的形式导致报错。

使用多层case when报错 代码如下：

case\
when fwtype=0 then fwtype\
when fwtype=1 and substr(cast(NOW() as String),9,2)\>=15 then 2\
when fwtype=1 and substr(cast(NOW() as String),9,2)\<=15 then fwtype\
end as fwType,

**解决方案**：优化代码，使用单层case when的形式

优化示例代码如下：

case\
when fwtype=1 and substr(cast(NOW() as String),9,2)\>=15 then 2 else
fwtype\
end as fwType,

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6934>

# 【任务依赖】任务依赖机制是怎么样的

**问题描述**：如果一个任务下线了，有下游任务的依赖，那运行的时候是什么情况？是直接无视依赖直接跑了，还是永远等待中？就是任务2依赖任务1。我现在把任务1下线了，任务2是无视依赖运行还是一直在等待

**问题分类**：咨询问题

**涉及版本**：DataSimba 所有版本

**解释说明**：该场景下，任务1冻结或下线，都会导致依赖该任务的下游等待，需要手动解除依赖。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6779>

# 【指标工厂】快捷模式下创建表失败

**问题描述**：在规范建模中，使用快捷模式建表提示调用存储域建表失败

**问题分类**：使用问题

**涉及版本**![08259c1c45f0cc967b89a49f657ba73d.png](./media/media/08259c1c45f0cc967b89a49f657ba73d.png){width="4.208333333333333in"
height="9.0in"}

**问题原因**![f3110db4291676b31e8ae2d7544e5fe6.png](./media/media/f3110db4291676b31e8ae2d7544e5fe6.png){width="6.5in"
height="4.194444444444445in"}

**解决方案**：需要删除"；"号

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6987>

# 运维

# 【运维】巡检系统检测到任务异常，该任务强制置为失败状态

**问题描述**：巡检系统检测到任务异常，该任务强制置为失败状态

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x及以上

解释说明**：**

这种情况属于系统机制。当任务出现异常时，例如任务状态卡住或者任务实际已经结束但状态仍显示为运行中时，系统巡检机制会检测并强制停止任务运行。

# 【运维】数据质量运维-规则配置，自定义sql写日期参数无法传参成功，但是替换成固定日期可以试跑成功

**问题描述**：【运维】数据质量运维-规则配置，自定义sql写日期参数无法传参成功，但是替换成固定日期可以试跑成功

**问题分类**：使用问题

**涉及版本**：DataSimba R4.3.0至R4.8.0版本

解释说明**：**

DataSimba R4.3.0版本不支持自定义日期参数。只有在DataSimba
R4.9.0及更高版本中才支持自定义日期参数。因此，在使用DataSimba
R4.3.0版本时，需要将自定义日期参数替换为固定日期。

# 【运维】批量补数据，结果不正确

**问题描述**：在补数据实例中，需要补过去N天的任务，在选择执行N-1天的时候，就会有N-1个补数据实例。并且在执行这些实例时，并没有按照日期顺序执行，而是随机执行。目前任务都是依赖前一天的结果数据跑的，这样补数据实例跑出来的结果就是不正确的

**问题分类**：使用问题

**涉及版本**：所有版本

![2fe3487bc616218e8b8ee358bce973de.png](./media/media/2fe3487bc616218e8b8ee358bce973de.png){width="6.5in"
height="3.763888888888889in"}

解释说明**：**

作业的执行依赖于先前任务实例输出的数据，这种情况存在两种情况：

1.  首次补录先前未生成过实例的日期，则只需要编辑对应作业，在配置依赖属性中，打开每个节点"自依赖"开关；然后重新提交一下任务，再到运维发起补录数据即可；

2.  如果是历史数据变动，需要补录历史的数据，只能单个日期补录，暂时不支持批量补录，否则会存在任务实例运行正常，但数据错误的问题。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-2976>

# 【运维】任务失败，内存溢出

**问题描述**：实例运行失败，报错OutOfMemoryError

**问题分类**：使用问题

**涉及版本**：所有版本

![dd318244de047747ff75247ea3d2d6ff.png](./media/media/dd318244de047747ff75247ea3d2d6ff.png){width="6.5in"
height="3.111111111111111in"}

问题原因一**：**

数据量太大导致datax跑任务时内存溢出

解决方案**：**

增加DataX内存参数。例如，在作业中修改环境参数 jvm=-Xms2g
-Xmx2g，观察任务是否会出现内存溢出。若仍然出现内存溢出情况，则可以再增加
JVM 内存。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-3074>

**原因二**：任务缺少内存或CPU参数

解决方案**：**

在脚本中设置任务参数：

1、tez.am.resource.memory.mb：指定 Tez application
master（AM）可以使用的内存大小（以 MB 为单位）。

如果任务比较大，可以增加这个参数的值，例如：set
tez.am.resource.memory.mb=4096;

2、tez.task.resource.memory.mb：指定每个 Tez task 可以使用的内存大小（以
MB 为单位）。如果任务需要更多的内存，可以增加这个参数的值，例如：set
tez.task.resource.memory.mb=2048;

3、tez.task.resource.cpu.vcores：指定每个 Tez task 可以使用的 CPU
核心数量。如果任务需要更多的 CPU 核心，可以增加这个参数的值，例如：set
tez.task.resource.cpu.vcores=2;

4、tez.grouping.max-size：指定 Tez Shuffle
阶段进行数据分组时可以使用的最大内存大小（以 MB
为单位）。如果任务需要进行大量的数据分组，可以增加这个参数的值，例如：set
tez.grouping.max-size=2048;

5、tez.runtime.io.sort.mb：指定 Tez
运行时进行数据排序时可以使用的内存大小（以 MB
为单位）。如果任务需要进行大量的数据排序，可以增加这个参数的值，例如：set
tez.runtime.io.sort.mb=1024;

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-4434>

# 【数据质量运维】DataSimba如何针对表的数据量进行监控预警

**问题描述**：DataSimba是否可以创建"表数据量大小"的监控？即：表的数据量不在某个范围内则报异常。

**问题分类**：使用问题

**涉及版本**：DataSimba R4.X 及以上版本

解决方式**：**

通过数据质量运维功能来实现该功能。

1.  首先在"规则模板"中创建一个值域检查的模板，确保配置了所需的预期值范围；

![b0e30c285a6059865651c482b9976246.png](./media/media/b0e30c285a6059865651c482b9976246.png){width="6.5in"
height="3.8472222222222223in"}\`

2.  打开"规则配置"页面，勾选需要应用该模板的表，并将该模板添加到表中。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6057>

# 【智能监控】当发生基线告警时，该如何处理？

**问题描述**：当发生基线告警时，该如何处理？

**问题分类**：使用问题

**涉及版本**：DataSimba R4.3 及以上版本

解决方式**：**

基线是一个水位线，用来监控特定任务是否在触达基线前顺利完成。如果任务没有按时完成，系统会发出告警，便于数据开发人员提前介入。基线告警并不意味着任务失败，只是提醒任务可能需要数据开发人员提前干预或注意。用户可以在平台上查看基线对应的任务，在确认无误后解除告警，这样系统就不会重复发出告警。

![e5dcf1d8e7793ce346cfeb386b56382e.png](./media/media/e5dcf1d8e7793ce346cfeb386b56382e.png){width="6.5in"
height="2.0694444444444446in"}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6067>

# 【周期任务】点击「立即生成实例」后，原来的实例会被替代

**问题描述**：点击「立即生成实例」后，原来的实例会被替代

**问题分类**：使用问题

**涉及版本**：DataSimba R4.X 及以上版本

解决方式**：**

修改任务并提交后，点击\"立即生成实例\"按钮，原来的实例将被替换为新实例，下图展示了点击\"立即生成实例\"的影响效果。

![aafed3ada5225ff7192a41258009950a.png](./media/media/aafed3ada5225ff7192a41258009950a.png){width="6.5in"
height="3.4166666666666665in"}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6135>

# 【邮件告警】配置邮件告警，需要提供哪些信息？

**问题描述**：配置邮件告警，需要提供哪些信息？

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

解决方式**：**

1.  前提条件：需要客户有自己的邮件告警服务；

2.  让客户提供相应的smtp服务器地址+端口，邮箱的账号+密码；

3.  联系数据云运维修改相应邮箱配置；

4.  因部署DataSimba的节点均有可能作为邮件的发送源，需要告知客户将部署DataSimba的节点IP全部添加白名单。

**关联jira**：<https://jira.startdt.net/browse/PPTWOM-3999>

# 【质量运维】告警信息发送到多个人的邮箱里

**问题描述**：数据质量模块，配置邮箱告警后，需要将告警信息发送给多个人（即：告警信息发送到多个人的邮箱里）

**问题分类**：使用问题

**涉及版本**![89001702809d82781221c0759e4d454d.png](./media/media/89001702809d82781221c0759e4d454d.png){width="4.569444444444445in"
height="9.0in"}**解释说明**：

现在质量规则的告警是自动发送告警给规则下所配置作业的作业责任人，无法新增其他告警对象。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6840>

# 服务

# 【API接口】DataSimba的API接口是否支持https的方式对外提供调用

**问题描述**：数据服务模块开发好的API接口，是否支持https对外提供调用

**问题分类**：使用问题

**涉及版本**：DataSimba 所有版本

解决方式**：**

API调用支持https。需要客户将https的域名绑定现有的调用地址，并且联系数据云运维同学修改nacos相关配置。域名与证书绑定的相关工作，由客户在自己的代理服务上配置。

**关联jira**：<https://jira.startdt.net/browse/PPTWOM-3882>

# 【服务工厂】创建的服务不能删除

**问题描述**![357f9a3d9b9e7bb96287718517b25e87.png](./media/media/357f9a3d9b9e7bb96287718517b25e87.png){width="6.013888888888889in"
height="9.0in"}**问题分类**：咨询问题

**涉及版本**：DataSimba R4.x及以上版本

**解释说明**：\
在服务中心中无法删除，下线的入口在：运维-服务运维

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6752>

# 治理

# 「资产地图」与「资产分析」中表存储量的统计值不一致

**问题描述**：治理模块的「资产地图」与「资产分析」中表存储量的统计值不一致

**问题分类**：咨询问题

**涉及版本**：DataSimba所有版本

![36ec6f97ffb9e4fb24d2284479a6b381.png](./media/media/36ec6f97ffb9e4fb24d2284479a6b381.png){width="6.5in"
height="2.3194444444444446in"}

![665d0d9341f2906a2123256dca00f649.png](./media/media/665d0d9341f2906a2123256dca00f649.png){width="6.5in"
height="7.75in"}

**解释说明**：「资产地图」与「资产分析」中表存储量的统计口径不同。

-   资产地图中为单副本，由元数据域进行统计，且实时更新统计数据。

-   资产分析中为多副本，由元仓进行统计，统计时间为T+1。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6127>

# 【资产目录】选根目录的话，子目录的表显示不出来

**问题描述**：选根目录，为什么子目录的表显示不出来

**问题分类**：咨询问题

**涉及版本**：DataSimba R4.x版本

![f01e6d2052103db1b1576649c1b42902.png](./media/media/f01e6d2052103db1b1576649c1b42902.png){width="6.5in"
height="8.458333333333334in"}

**解释说明**：当前的产品设计逻辑是父级目录只展示添加在本文件目录下的资产，不展示子目录下的资产信息

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6792>

# 安全

# 【安全】数据审计、风险识别触发后产生的"危险操作记录（即：明细数据）"是永久保留？

**问题描述**：【安全】数据审计、风险识别触发后产生的"危险操作记录（即：明细数据）"是永久保留？

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x版本

解释说明**：**

-   数据审计：每天都会进行识别，但由于数据量很大，产品前端界面可能会出现响应超时的问题。因此，在产品侧（前端界面）限制了只展示一个月的数据，用户可以通过底层系统查看对应的历史信息。

-   风险识别：每天都会进行风险规则的识别，前提是相应的规则必须是开启状态。只有当用户触发了某条规则，系统才会记录相关信息。如果用户不删除该规则并一直保持开启状态，系统将持续记录风险结果。

# 【数据安全】静态脱敏的作用及识别规则

问题描述**：**

静态脱敏里有车牌号(car_no)这个识别规则名称，但是在识别规则配置页面没有这个名称，这样静态脱敏是不是就不起作用。

**问题分类**：使用问题

**涉及版本**：DataSimba R4.x版本

解释说明**：**

1.  静态脱敏主要是应用在【集成-数据同步】对目标表的具体字段进行自主性的脱敏配置，数据同步入库后存储和展示都为脱敏状态。因此静态脱敏和数据类型（int/long..）相关，跟数据的敏感类别（身份证/手机号\....）没有关联性。

2.  动态脱敏是基于识别后的敏感数据类别进行统一的脱敏展示，即如果应用"手机号"的识别规则识别出10张表分别有1-2个字段是"手机号"的敏感类别，用户在查询这10张表的对应字段时，展示为脱敏状态。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6680>

# 【数据安全】敏感数据识别后如何进行动态脱敏

# 数据开发

# 任务运行报错，return code 2

问题类型一、资源不足

问题描述**：**

任务运行报错，Error while processing statement: FAILED: Execution Error,
undefined from org.apache.hadoop.hive.ql.exec.tez.TezTask. Vertex
failed, vertexName=Reducer 3, vertexId=vertex_1704447145212_362488_1_03,
diagnostics=\[Task failed, taskId=task_1704447145212_362488_1_03_000000,
diagnostics=\[TaskAttempt 0 failed, info=\[Error: Error while running
task ( failure ) : undefined

**问题分类**：数据开发

问题原因**：**

失败日志提示：return code 2、java.lang.OutOfMemoryError: Java heap
space\
，这是资源不足导致的失败，一般是当前环境运行任务过多，没有足够资源，或者这个任务计算量过大，默认资源不足导致。

解决方式**：**

1.  通过配置增加任务资源:

-   SET hive.tez.container.size=4096;

-   SET hive.tez.java.opts=-Xmx3072m;

2.  若表的数据量过大，通过修改代码，使用更高效的处理逻辑。如：

select \* from a000_zjb_bltp where wlph in (select DISTINCT wlph1  from
 a000_zjb_tpblhz)

修改为：

  select wlph,newph     from     (         select wlph,newph from
a000_zjb_bltp     )A1     inner join     (         select wlph1,count(1)
        from  a000_zjb_tpblhz          group by wlph1     )A2 on A1.wlph
= A2.wlph1

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6140>

**问题描述**：日志提示：Error while processing statement: FAILED:
Execution Error, return code 2 from
org.apache.hadoop.hive.ql.exec.tez.TezTask. Counters limit exceeded: Too
many counters: 10001 max=10000

**问题分类**：数据开发

问题原因**：**

日志提示Too many
counters，计数器数量超过了Tez配置的最大限制，应该是一段代码中，使用了过多的join和union等操作

解决方式**：**

-   优化代码逻辑：将12个月分的fcst_qty指标，从12列变成12行，是一个列转行的需求,可以通过concat(february,march,april\...\...)
    的方式将要转行的列，整合为一个字符串,再用LATERAL VIEW explode
    的窗口函数进行列转行操作。如下：

SELECT id, value FROM my_table LATERAL VIEW explode(split(values,
\',\')) tbl AS value; 

-   引入临时表：将过程中的join和union操作，先写入临时表后再处理，如先将6个月的写到临时表，两个临时表再union，这样就不会导致
    Too many counters 错误。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6272>

### 问题类型二、任务数据量大

**问题分类**：数据开发

**问题描述**：代码没跑成功过

![a945d2b2dc4a4144d31274f8a6b8c7cc.png](./media/media/a945d2b2dc4a4144d31274f8a6b8c7cc.png){width="6.5in"
height="1.125in"}

问题原因**：**

客户代码的编写方式会对所有分区数据进行操作。由于数据量庞大，可能会导致代码错误。

解决方式**：**

可以修改为只选择一个分区进行处理。如：\
select count(case when a.c_mk_store_id=\'1\' then \'11888\' else
a.c_mk_store_id end) as jkhys,case when a.c_mk_store_id=\'1\' then
\'11888\' else a.c_mk_store_id end as store_idfrom
std_crm_tb_card_his_df aleft join std_crm_tb_customer_df b on
a.c_customer=b.c_nowhere a.c_cardname in (\'新橙家金卡\',\'金卡\') and
a.ds=\'\${bdp.system.bizdate}\' and b.ds=\'\${bdp.system.bizdate}\' and
etldt=TO\\\_DATE(\'\${bdp.system.bizdate}\')group by c_mk_store_id;

修改为

select count(case when a.c_mk_store_id=\'1\' then \'11888\' else
a.c_mk_store_id end) as jkhys ,case when a.c_mk_store_id=\'1\' then
\'11888\' else a.c_mk_store_id end as store_id  from (     select \*
from std_crm_tb_card_his_df     where ds=\'\${bdp.system.bizdate}\'     
and c_cardname in (\'新橙家金卡\',\'金卡\')      and
etldt=\'\${yyyy-MM-dd,-1d}\') ) a left join (     select \* from
std_crm_tb_customer_df     where ds=\'\${bdp.system.bizdate}\' ) b on
a.c_customer=b.c_no group by c_mk_store_id;

etldt=TO_DATE(\'\${bdp.system.bizdate}\')\
这段代码有问题。修改为 etldt=\'\${yyyy-MM-dd,-1d}\'，即可以正常运行

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-3134>

### 问题类型三、任务数据量小

数据量很少的情况下，数据、结构、文件异常，也会导致code
2的情况，一般需要对使用的表删表重建

**问题描述**：增加一个筛选条件后，任务运行code 2

**问题分类**：数据开发

**问题原因**：\
不是资源引起的，按照以往的经验，大概率是数据文件或表结构异常导致的，这类问题很难排查具体导致的原因

解决方式**：**

可以尝试，先把表数据写到临时表中，然后删表重建创建表结构，再从临时表动态分区的方式写到各个分区中

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6524>

### 问题类型四、code 2的部分情况是字段内容异常

客户尝试增加资源配置后依旧失败，code
2大部分时候是资源问题，也有部分情况是异常问题

**问题描述**：内存不足了怎么办，平时都可以跑得 今天不行了

**问题分类**：数据开发

**问题原因**：\
可能某个字段的内容有异常，如有特殊的字符等，导致后续处理过程出错。

**解决方式**：\
客户需要逐步排查一下字段语句，可能某个字段内容有特殊的字符，需要清洗一下数据

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-7004>

# 作业执行报错Caused by: java.lang.AssertionError: Capacity must be a power of two

**问题描述**：任务参数已经改为2的幂了，但仍会偶发性报错。其日志报错Caused
by: java.lang.AssertionError: Capacity must be a power of two

**问题分类**：数据开发

问题原因**：**

-   容量必须是二的幂

-   客户代码中采用了 row_number\
    导致资源占用过大。在任务调度过程中，当资源不足时会出现报错，但资源充足时则会正常运行。这也是偶发性报错的原因。

**解决方式**：经过新建临时表和对代码进行优化，任务可以正常运行。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-3138>

# 作业执行报错Error while compiling statement

**问题描述**：作业执行报错Error while compiling statement

**问题分类**：数据开发

问题原因**：**

compile
statement报错，错误原因有语法错误、无效的表或列名、数据类型不匹配等

解决方式**：**

-   检查SQL语句的语法是否正确，联系数开进行代码优化。

-   确认所有引用的表和列名在数据库中存在且拼写正确。

-   确保数据类型与数据库中的列定义相匹配。

-   如果涉及权限，确保执行该语句的用户有足够的权限。

-   查看具体的错误信息，进行进一步分析处理。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-3206>

# 任务运行失败，报错提示：Number of dynamic partitions created is 1001, which is more than 1000. To solve this try to set hive.exec.max.dynamic.partitions to at least 1001.

**问题描述**：日志提示：Number of dynamic partitions created is 1001,
which is more than 1000. To solve this try to set
hive.exec.max.dynamic.partitions to at least 1001.

**问题分类**：数据开发

问题原因**：**

动态分区数量超过了系统设置的上线。

解决方式**：**

1.  数据开发优化任务降低数据。

2.  临时增加该任务的动态分区数量上限。\
    SET hive.exec.max.dynamic.partitions = 2000

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-5862>

# 两个字段排序，字段排序不生效

**问题描述**：\
根据两个字段排序，第一个字段值相等时，第二个字段不生效

![4469da78c925ebc11b2ffe4358a58421.png](./media/media/4469da78c925ebc11b2ffe4358a58421.png){width="6.5in"
height="6.833333333333333in"}

**问题分类**：数据开发

问题原因**：**

第一列字段类型是字符串，字符串排序方式是字典排序，数据111和2比较,2就排在111后面

解决方式**：**

如果想按照数字大小排序，请将该字段转换成数字

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6170>

# 数据写入其他用户的表里面怎么配置

**问题描述**![cb7c5d28c7dab4da1baddcfb4e480d65.png](./media/media/cb7c5d28c7dab4da1baddcfb4e480d65.png){width="6.5in"
height="2.1666666666666665in"}

**问题分类**：数据开发

**问题原因**：connector 不同，参数配置不同，客户用错了参数，oracle-cd 和
oracle 两种连接器的要求不同

解决方式**：**

1、尝试更改参数

参数名改为\'schema-name\'\\\`\
\
在\'table-name\'中，修改表名为\'HF\\\_BI.bc\\\_kafka\\\_order\\\_master\'\\\`

2、参考不同情况的写法

WITH ( \'connector\' = \'oracle-cdc\' , \'hostname\' = \'10.10.xxx.xxx\'
, \'port\' = \'1521\' , \'password\' = \'xxxxxx\' , \'database-name\' =
\'ORCL\' , \'schema-name\' = \'DC\\\_TEST\' , \'table-name\' =
\'SRC\\\_TEST\\\_111\' WITH ( \'connector\' = \'oracle\' , \'url\'
=\'jdbc\\:oracle\\:thin:@//10.10.xxx.xxx:1521/orcl\' , \'username\' =
\'xxx\' , \'password\' = \'xxxxxx\' , \'table-name\' =
\'DC\\\_TEST.TARGET\\\\\\\_TEST\\\_111\'

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6143>

# 数据过滤这里要实现功能需要怎么写

**问题描述**：默认抽取数据的时候，先清理accuralmonth=当前月和上个月，两个月的数据，然后再抽取，抽取前先数据过滤，筛选出当前月和上个月，然后再清理，插入，从sqlserver里只同步当月和上个月的数据。

数据过滤中的代码，是simba发送到sqlserver执行的，所以必须用sqlserver的语法

![b33f5ad7da957b562c95df10a3dd1b1a.png](./media/media/b33f5ad7da957b562c95df10a3dd1b1a.png){width="4.569444444444445in"
height="3.9583333333333335in"}

**问题分类**：使用问题

**涉及版本**：所有DataSimba版本

问题回复**：**

用\'\${yyyyMM，1M}\'
表示前一个月的年月，对代码进行修改，112是convert的样式代码，可以查一下sqlserver的语法

修改代码为：

AccuralMonth in (\'CONVERT(varchar(6) ,\'\${bdp.system.bizdate}',
112),\'CONVERT(varchar(6) ,\'\${bdp.system.bizdate,-1M}', 112))

\`\`

相关参数：

-   \* 后N年：\${yyyyMMdd,Ny}

-   \* 前N年：\${yyyyMMdd,-Ny}

-   \* 后N个月：\${yyyyMMdd,NM}

-   \* 前N个月：\${yyyyMMdd,-NM}

-   \* 后N周：\${yyyyMMdd,NW}

-   \* 前N周：\${yyyyMMdd,-NW}

-   \* 后N天：\${yyyyMMdd,Nd}

-   \* 前N天：\${yyyyMMdd,-Nd}

-   \* 后N小时：\${yyyyMMddHH,NH}

-   \* 前N小时：\${yyyyMMddHH,-NH}

-   \* 后N分钟：\${yyyyMMddHHmm,Nm}

-   \* 前N分钟：\${yyyyMMddHHmm,-Nm}

-   \* 季度第一天：\${yyyyMMdd,FQ}

-   \* 季度最后一天：\${yyyyMMdd,EQ}

-   \* 月第一天：\${yyyyMMdd,FM}

-   \* 月最后一天：\${yyyyMMdd,EM}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6169>

# 任务运行报错"Table insclause-0 has 72 columns, but query has 71 columns"

**问题描述**：任务运行报错"Table insclause-0 has 72 columns, but query
has 71 columns"\
日志提示：Cannot insert into target table because column number/types
are different \'\'20240117\'\': Table insclause-0 has 72 columns, but
query has 71 columns.taskId-2949331,error\
说明写入表有72个字段，但写入的查询语句只有71个字段，任务运行失败

**问题分类**：数据开发

**问题原因**：Simba产品的运维逻辑中，会23点整生成第二天的所有实例，客户在23点之前对代码进行了修改，此时已经生成实例，导致写数据入表的代码中，字段数量与结果表的数量不匹配

**解决方式**：\
Simba产品的运维逻辑中，会23点整生成明天的所有实例。所以23点后提交的代码，不会影响第二天的实例逻辑。建议不要再22点后修改任务，可能导致任务逻辑跟预期不符。

建议手动运行研发中的任务，或者使用运维补数据的功能，把任务运行成功。然后再手动设置任务为成功，保证后续任务继续正常运行。任务后续的实例，就会以最新版本的代码生成，避免这个问题。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-4342>

# 运行任务无权限操作code

**问题描述**：任务运行都显示没有权限

![d29c6f1ea8390c948e0cc1752b4dadda.png](./media/media/d29c6f1ea8390c948e0cc1752b4dadda.png){width="6.5in"
height="2.5833333333333335in"}**问题分类**：数据开发

问题原因**：**

内存不足导致触发OOM（Out of Memory killer ）进而导致任务运行失败。

解决方式**：**

-   **增加内存资源**：
    为任务或应用程序分配更多的内存或增加副本（联系研发处理），确保其在执行过程中不会触发
    OOM。

-   **优化代码和配置**：
    检查任务的内存使用模式，优化算法或配置参数（如调低并行度、减少内存消耗的中间数据）。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6903>

# 任务保存后运行还是旧代码

**问题描述**：任务保存之后运行还是旧代码

**问题分类**：使用问题

问题原因**：**

相关作业开发里面已经对SQL进行修改，但是在任务开发里面还是执行旧的代码。

解决方式**：**

关于作业的变更提交，注意一下几点：

1、作业中修改好代码后，需要保存\
2、到任务中，找到改作业，查看作业代码，确保是最新的\
3、任务中，需要做一些调整，否则提交按钮不生效。随意拖动一下某个作业即可，再提交\
4、检查运维中的任务更新时间，是否是当前时间。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-7038>

# 实时任务停不下来

**问题描述**：实时任务运行后停不下来，实时的job更新后还运行老代码。

**问题分类**：数据开发

问题原因**：**

![0f0f40ca1fc0b7dbb4aed52d7340dda2.png](./media/media/0f0f40ca1fc0b7dbb4aed52d7340dda2.png){width="6.5in"
height="7.694444444444445in"}

解决方式**：**

-   更新代码后，直接研发模块提交上线即可生效；如果担心未生效或想暂停消费数据，可以先停止任务，再提交上线，并到运维模块，启动任务。

-   实时任务点击停止未停止，可以等待一段时间再看（分钟级）。

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6734>

# 数据中台写Python代码，缺少依赖的包

**问题描述**：数据中台写Python代码，缺少相关模块。

**问题分类**：数据开发

问题原因**：**

客户欲通过python连接SQLserver数据库，在导入pymssql的时候报没有该模块。

ModuleNotFoundError: No module named \'pymssql\'\
code{0001B10069}-message{运行k8s job失败}

解决方式**：**

1.  新建镜像，镜像中需要有对应python包（镜像是指docker镜像，将python环境和pypi的依赖包提前安装在镜像中）

2.  创建python任务，指定上传的镜像

![a6bf406f6039694529216528ddeea3ee.png](./media/media/a6bf406f6039694529216528ddeea3ee.png){width="1.9305555555555556in"
height="9.0in"}

**关联Issue**：<https://jira.startdt.net/browse/PPTWOM-6689>
