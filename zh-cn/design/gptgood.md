# GPT助手

原型文档： [Gptdoc.4everland.app](https://gptdoc.4everland.app/#/zh-cn/design/gpt)



## 主体组成

人员： 

- 真人患者，求职者
- 机器人医生，老师，律师，心理咨询...

工具：

- chatgpt
- Wisper 语音输入模块
- TTS微软语音输出
- ocr（文本信息转txt供ai使用）
- midjourny（头像等内容生成）
- 分析器（针对问题生成类似wbs的细化）
- 计划表playbook
- metabuilder(类似notion)

流程：

-  康复计划
- 健身计划



## 系统组成

主入口 http://www.gptgood.com

注册用户基本功能：

- 相互问答

- 单独问机器人

- 关注某人

- 关注机器人

- 病友等关注channel电台

- 活动模板playbook等基础工具

  

主要GPT功能：

- 智能医疗
  - 搜索添加机器人
  - 机器人问诊
  - 根据情况找到合适的医生
  - 智能推荐（外部链接）

- 智能教育
  - 多学科机器人
  - 智能学习进度跟进
  - 语言学习
  - 考试模拟测验
  - 面试模拟

- 商品推荐
  - 语言需求获取prompt
  - 生成易于理解的结果展示
  - 商品购买直达

- 法律顾问
  - 通过语言输入获得输赢概率
  - 生成权益最大化的法律方案
  - 模拟律师进行辩护问答

- 心理咨询
  - 佛学
  - 心理治疗
  - 历史名人
  - 权宜之计

![image-20230327103057136](C:\gptgood\gptdoc\zh-cn\images\image-20230327103057136.png)





主要助手功能：

- 定制信息管理Meta
- 定制Table
- 定制Calandar
- 个人文档管理
- Tracker管理



![image-20230327102718967](C:\gptgood\gptdoc\zh-cn\images\image-20230327102718967.png)![image-20230327102902417](C:\gptgood\gptdoc\zh-cn\images\image-20230327102902417.png)



### 活动管理

- 活动计划
- 活动进行
- 活动回顾





## 辅助功能：

- 消息推送

- 邮件服务

- 短信验证
- 运营系统
- OpenAI账号Pool



# 关联其他软件

## 微信

- 导入微信群
- 导出微信群

## JIRA

- 提交任务工单
- 回复任务

## CICD

- AWS工程
- Gitlab



##  权限

## 内置访问控制



## 细分权限



## 管理角色



## 行为审计



## 信息存档



## 数据加密转移





# 使用流程

- 用户在Mattermost上的通道选择健康医疗机器人
- 机器人通过errbot与aws进行交互，获取数据
- 在界面生成的card进行选择和交互



## 版本迭代

- 服务端更新server
- webapp打板
- update到aws的ec2
- ai@lambda



## 技术栈

- GO

- Python

- Vue
