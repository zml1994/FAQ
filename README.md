# 通用问题
## 清缓存方法
目前系统使用正常，请清理缓存后再重新登录一下，还有问题截图反馈具体情况。
- 说明：当系统正常，个人使用不正常时，可以采用清理缓存、重启浏览器等方法解决
- 电脑端清理缓存方法快捷键：ctrl+shift+delete，其他情况请"百度一下"
- 造成异常原因：浏览器为加速访问网页，缓存了一下资源在本地，由于系统更新，浏览器未加载最新资源，导致访问异常。
- 本系统推荐使用浏览器：chrome、火狐、360浏览器

## 问题反馈建议
- 务必表明身份：谁、身份、项目、具体业务模块等
- 务必详细表述问题：优先文字描述，说明实际所遇到的具体问题，存在的疑惑或需要做什么
- 如多处、多人存在问题。请务必要具体到哪人，什么情况，方便排查后第一时间回复
- 对出现的问题，最好全屏截图，或拍照（要清晰），反馈实际情况

## 技术支持服务说明
- 群服务时间为：法定工作日 9:00-11:30 13:30-17:00
- 非工作时间如有紧急问题请备注“紧急”
- 如有遗漏未回复，建议进一步说明情况再告知一下

# 杭州实名制

## 基础问题

### 杭州实名制基础信息（项目）
- 登录网址：http://115.233.209.232:9000/
- 杭州实名制操作手册：http://115.233.209.232:9000/staticResource/third-push-interface-doc/Manual.pdf
- 杭州工地通使用指南：http://115.233.209.232:9000/staticResource/third-push-interface-doc/constructionsite-manual.pdf
- 本系统推荐使用浏览器：chrome、火狐、360浏览器
- 杭州建管站QQ群：
    - QQ1群：532371151（已满）
    - QQ2群：112475025
    - QQ3群：885048021（已满）
      - 已加群不要重复加，加群申请：单位简称+姓名

### 网页登录网址及接口介绍
- 网页登录网址：指的是用户在浏览器打开，用来访问，界面交互的网址
- 接口地址：指的是技术人员用来传输数据的地址，并非用来浏览器访问

### 杭州实名制基础信息（实名制厂家）
- 杭州市数据对接完整接口地址：http://115.233.209.232:9089/open.api
- 实名制对接接口文档（提供给厂家用于技术对接）：http://115.233.209.232:9000/staticResource/third-push-interface-doc/HZ-InterfaceV1.pdf
- 对接流程
    - 项目方提供对应项目的appid、密钥
    - 参考接口文档，调试接口
    - 根据实际业务逻辑依次推送
        - 企业信息
        -  参见单位
        - 班组信息
        - 人员信息
        - 人员进退场
        - 考勤数据
        - 其余业务有需要的数据或主管部门、业主方要求的数据
- 实名制厂家技术支持：加朱工微信（13085424963）并表明厂家身份
### 品茗客户业务支持（桩桩）
如果你采用品茗的实名制管理系统（简称：桩桩），请加以下QQ群反馈问题。
- QQ1群：518386071（已满）
- QQ2群：1080880747

## 登录类问题
### 当前企业无相关操作业务，不需要登录系统
- 施工单位企业账号：此单位系统中无任何项目，请核对统一社会信用代码或联系主管部门添加项目
- 分包单位：项目还未上传该单位为参建单位，让总包先传实名制数据
- 建设、监理、勘查、设计等其他单位：在本系统无业务，如有需要，反馈给主管部门

### 杭州市实名制平台账号说明
- 杭州市平台账号与其他（地区）任何平台账号不共用
- 杭州市平台账号主要分3类
    - 施工单位-企业账号：账号唯一，自系统上线以来首次有项目时自动开通，应有施工企业专人管理。
        - 登录名：统一社会信用代码
        - **初始**密码：统一社会信用代码后六位（区分大小写）
    - 项目账号：由【施工单位-企业账号】自主开通，负责对应项目的操作使用
        - 登录名：企业账号创建时自主设定
        - 初始密码：企业账号创建时自主设定
    - 分包单位-企业账号：项目通过实名制接口，上传分包单位为参建单位后自动开通，与施工单位-企业账号类似
        - 登录名：统一社会信用代码
        - 初始密码：统一社会信用代码后六位

### 杭州市实名制重置密码说明

- 施工、分包单位企业密码重置：
    - 外地（杭州市外）企业联系建管站（市场管理科）
    - 本地企业联系企业注册地的住建局（通常是建管科）
    - 由于施工、分包单位账号全杭州市只有一个，应有单位专人管理，避免反复重置密码。
- 项目账号密码重置：
    - 由企业账号负责管理，如需新增/重置密码，联系你们自己企业账号的负责人

### 杭州实名制平台企业账号无法登录（账号、密码错误）
- 首先请阅读账号说明及密码重置说明
- 企业账号由企业专人管理；非企业实名制负责人不要尝试登陆企业账号，防止被锁定。
- 如工作交接、长时间忘记密码请走密码重置流程并妥善保存。
- 还有问题可反馈具体情况，作为技术方可以适当排查或解答问题，但无权为您重置密码

## 对接类问题
### 项目报备步骤及说明
- 项目报备需要由**施工单位**企业账号进行报备
- 【系统管理】【项目库】需要有该项目，没有项目联系主管部门添加项目
- 项目状态需要为"在建"状态，"非在建"状态不可报备
- 项目报备前，需要在【项目库】完善项目信息
    - 施工企业**首次**使用本平台，需要在【工资保证金】**登记在杭州市的保证金缴纳情况**
- 最后在【实名制管理】【项目报备】【未报备】标签页中，点击"报备"，选择项目
    - 如果系统提示需要完善信息，可点击"完善信息"跳转到项目库完善上一步骤：完善信息
    - 如选择不到项目，按上述步骤先检查一下
- 项目报备完成后，系统生成"appid"和""密钥""，在"详情页"查看   
### 实名制数据如何对接

- 杭州市参照全国平台的对接模式及技术对接标准，**实名制相关数据由项目方上报**
- 项目方可结合实际情况，自己建设实名制管理系统或采购第三方厂家系统或服务
- 项目施工单位的企业账号在杭州市平台【实名制管理】【项目报备】完成报备，系统生成appid、密钥
- 施工单位账号、项目账号，均可通过【项目报备】中"详情"获取appid、密钥，提供给厂家用于数据对接
- 实时推送实名制相关数据（参建单位、班组、人员、考勤信息等）。
### 项目上系统数据与杭州市平台数据不符

- 数据对接原理：
    - 项目方（实名制厂家）需要上报数据
    - 平台根据业务规则，处理数据并返回结果
    - 对于平台接收成功的数据，通过会在平台实时展示
- 问题排查思路：
    - 实名制厂家已上报数据是前提条件，平台没数据需要先反馈给厂家展开排查
    - 厂家推送数据后，平台如处理失败并返回结果，应由厂家展开排查，调整业务规则
    - 厂家推送数据后，平台如未处理，可能数据处理较慢，应让厂家反馈给我们，我们针对性排查
    - 数据推送后返回结果成功，建议耐心等待界面展示，如长时间未展示，反馈具体哪条数据给我（平台方），我们会展开排查
- 各环节对接都存在一定的时间差，非技术人员不要简单认为数据马上会在对应平台展示
### 系统中无参建单位、劳务分包等。

- 系统中项目除基础信息由界面添加外，其余实名制数据需要通过接口上传。
- 平台界面数据基本实时展示，如平台界面没有，建议先联系实名制厂家排查

### 数据对接规则（参建、班组、人员进退场及考勤数据）

- 参建单位推送后，参见类型不可变更，如监理单位变成劳务分包
- 班组：同一项目的班组名称不可重复
- 人员：同一项目下，人员不可在多班组，如需调整班组，在退场状态下，可修改人员所在班组
- 进退场：必须符合业务逻辑，按照进-退-进的顺序推送
- 考勤：上传人员即可上传考情数据，但非在场人员，有考勤数据也不纳入统计

### 杭州市实名制平台测试项目

杭州市平台暂无测试环境，此项目为正式环境的项目，请不要推送不文明数据或频繁发送请求。  
1、登录所提供的项目账号，在【项目报备】-【已报备（非在建）】可找到对应项目。
2、对于对接的数据，尽可能拿真实数据推送测试，严禁乱编，乱填或出现"测试"的字眼等 
3、对接测试完后，停止数据推送，不要再私自对接，或将此信息转发给他人

   - 项目名称：萧政储出（2017）12号地块居住项目二标段
   - 施工单位：浙江杰立建设集团有限公司
   - appid：330109191123010160
   - 项目编码：330109191123010160
   - 密钥：G85qF5JP-7PO#Mx#JT#mmaeOJ6tcf!v-
   - 杭州市对接完整接口地址：http://115.233.209.232:9089/open.api
   - 实名制对接接口文档（提供给厂家用于技术对接）：http://115.233.209.232:9000/staticResource/third-push-interface-doc/HZ-InterfaceV1.pdf
   - 平台地址：http://115.233.209.232:9000/
   - 项目账号：13375717532
   - 密码：Aa123456

## 业务问题

### 杭州市实名制平台项目添加说明
企业账号在【系统管理】【项目库】中无对应项目，请联系主管部门添加。
- 市本级项目由杭州市建管站（市场管理科）添加
- 区县项目由项目对应区县主管部门（通常都是住建局-建管科）添加
- 我这边没法提供对应的联系方式
### 项目形象进度维护

- 项目形象进度由施工单位-企业账号、项目账号如实进行维护
- 维护方法：  
    - 企业账号、项目账号-系统管理-项目库-选中项目-点击【形象进度维护】按钮
    - 选择对应状态：未开工、在建、停工、终止监督。
    - 根据界面提示，完善信息，并保存
- 其他说明：  
    - 维护【终止监督】后，不可恢复，相应凭证无法修改
### 考勤暂停说明
- 考勤暂停，由项目账号进行操作，施工单位的企业账号无权限
- 根据主管部门要求，系统关闭"项目暂停"的功能；人员、班组暂停功能保持不变
- 项目如长期停工，请维护状态至"停工"，具体以各区县主管部门要求为准
- 不要通过人员、班组暂停功能进行全员考勤暂停，会导致考勤率为0%
### 春节假期停工问题
- 如果整个项目停工，反馈给主管部门，以主管部门管理要求为准。
- 如果项目还有人施工，维护人员进退场或暂停考勤
### 项目信息完善
- 按照实际情况，完善项目基础信息
- 项目位置：在地图上结合参照物选点后保存
- 五方责任主体
    - 施工许可证上无相应单位的，选择"施工许可证上未见（无）"
    - 施工许可证上有的，但是系统选不到的，反馈相应单位名称、统一社会信用代码，由管理员添加。
    

## 统计问题

### 统计数据不一致说明
- 【项目报备】【实时考勤统计】：这里实时展示的平台所接受到的所有实名制数据，比如你推送半年前的进退场、考勤数据成功接收后都会实时展示。
- 【统计报表】：统计报表每天凌晨2：00统计前一天的数据，并固化数据；补推的数据将不在统计报表中统计。
- 【统计报表】：统计报表，涉及今日数据的，1小时刷新一次，并非实时刷新。
- 【统计报表】：各统计报表区分参建单位、工种，区分统计。
### 考勤数据及明细
- **蓝色**的统计数字，均可以"点击"查看明细，有导出按钮的可以导出
- 每日考勤数据的所有明细（包括扫码考勤、**数据上传时间**），均可【项目报备】-【出勤统计】-导出考勤明细后查看
- 本平台无各项目所需的各类考勤报表功能，建议让实名制厂家提供。如需扫码考勤数据，可通过实名制考情数据查询接口查询
- 实时考勤统计仅展示近两个月（包含本月）的考勤数据及明细
### 考勤率：有考勤人员/在场人员
- 有考勤人员：在场人员推送了考勤数据
- 在场人员：人员推送了进场但未退场
- 进退场逻辑说明：  
  - 进场：可以理解为入职；
    - 非新增人员，必须离职才可进场；
    - 进场时间不能早与退场时间，晚于当前时间；
    - 如当天进场，当天生效。
  - 退场：可以理解为离职；
     - 仅有在职人员，才可退场；
     - 退场时间不能早于进场时间，晚于当前时间；
     - 当天退场，当天为在职状态，次日生效
- 退场功能说明：
  原则上项目应有自己的实名制管理系统（系统、闸机等），产生的所有实名制数据**通过接口**实时推送至杭州市平台。考虑到项目方在厂家支持不足的情况下，杭州市平台提供手动退场功能，用于临时手动维护，但务必保障数据的真实性以及多平台数据的一致性，避免给后期带来影响。
  - 杭州市手动退场：【项目报备】【班组信息】在场人员，可进行手动退场
    - 杭州市手动进场：项目已经推送参建、班组数据，且进场人员，在整个杭州市有推送过人员信息。
    - 杭州市手动退场：【项目报备】【班组信息】在场人员，可进行手动退场
  

## 杭州工地码

### 工地码下载

- 进入【实名制管理】-【项目报备】"详情"页面中，在下半页的"标签页"中找到“杭州工地码二维码”，点击“工地码下载”。
### 杭州工地码扫码不在范围内
- 个别人无法扫码：排查该扫码设备、支付宝的定位权限
- 个别人能扫，大部分不能扫：尽可能精确的调整项目定位
- 所有人都不在范围内：调整项目位置
- 调整项目位置方法
    - 登录系统平台，在【系统管理】【项目库】，点击"修改"
    - 找到"标注地图"，点击，根据参照物，在系统界面选择项目位置。（尽量不要用搜索）
    - 选择位置后，务必"确认"，"保存"
    - 切换到别的界面，再回来核实一下位置是否正确；
    - 扫码考勤默认定位范围为半径1km，如线性工程等特殊情况，请说明情况并告知最大跨度
### 复工、未复工的解释
- 根据2020年4月展开疫情后的复工复产工作，系统根据人员扫码工地码情况，来判断时候复工，与闸机上传数据无关。
- 如管理部门有管理要求，现场人员扫工地码即可。
### 实名制与非实名制人员说明

- 根据建筑行业实名制管理，对于现场作业人员，项目方通过技术手段，将实名制数据推送至平台，此类人员归为：实名制人员，及系统展示的"在场人员"
- 根据2020年3月推行的杭州市工地码，所有人均可扫码，如未通过实名制数据上传人员的，归为：非实名制人员
    - 实名制人员扫工地码后，产生数据纳入考勤明细，在"导出考勤明细"中可以区分
    - 非实名制人员如果是劳务工人、管理人员，需要将这些人员通过接口上报

# 萧山云平台
## 基础问题
### 项目信息完善


## 登录问题



## 安监问题
### 


## 起重机械问题



## 质监问题
### 项目验收流程
质量验收针对的是这个项目的单体进行验收，务必在工程库中维护正确的单体信息。
- 基础验收：工程库登记的所有单体都要验收，而不是仅验收地下室
- 主体验收：所有单体的基础验收都必须完成，不然无法发起主体验收
- 竣工验收：所有单体的主体验收都必须完成，不然无法发起竣工验收


## 关键人员、实名制问题

### 萧山区实名制对接

- 萧山区对接完整网址：http://xiaoshan-rn-api.pinming.cn/open.api 
### 用户服务（萧山云平台使用用户）
- 品茗技术服务团队
- 问题反馈渠道：
   - QQ1群：553214142（已满）
   - QQ2群：754440406
- 咨询固话：0571-56035577（8044分机号）
- 服务时间：工作日 9:00-11:30  13:30-17:30 
### 萧山区厂家申请密钥
申请密钥的项目注意以下几点：
- 务必确认项目已经开通了银行专户
- 务必确认厂家与银行对应，没有签约合同的反馈给胡科
- 根据以下链接，填写信息以便留底记录
【腾讯文档】萧山实名制密钥申请
https://docs.qq.com/form/fill/DR0tnUVlzaWh4RWxY?_w_tencentdocx_form=1

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

