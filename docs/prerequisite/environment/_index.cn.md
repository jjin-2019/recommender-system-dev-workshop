---
title: 检查环境
weight: 10
---

## AWS 账号
为了完成此workshop，您需要一个具有管理员访问权限角色的 AWS 账户。 如果您没有，请点击 [此处](https://aws.amazon.com/getting-started/) 创建一个。

**成本**: 如果您的账户不到 12 个月，AWS 免费套餐将包含此workshop中所需的部分资源。 有关更多详细信息，请参阅 [AWS 免费套餐页面](https://aws.amazon.com/free/) 。 为避免在完成 workshop 后产生不需要的收费，请参阅 [清理资源](https://gcr-solutions.github.io/recommender-system-solution/cn/cleanup/) 。

## AWS 地区
一旦你选择了一个地区，你应该在该地区创建此workshop的所有资源。 我们建议您选择 **Tokyo** 地区。 使用区域下拉列表选择 **Asia Pacific (Tokyo)ap-northeast-1**。 

## 浏览器
我们建议您使用最新版本的 **Chrome** 来完成此workshop。 

## SageMaker 资源要求

为了测试此workshop的某些功能，您的 SageMaker 资源限制需要满足以下最低要求。 单击 [此处](https://sagemaker-tools.corp.amazon.com/limits) 检查并增加 SageMaker 资源限制 

|Region |Resource type |Resource | 	Required limit |
|--- |--- | --- | --- |
|ap-northeast-1|SageMaker Training |training-job/ml.p2.xlarge |2|
|ap-northeast-1|SageMaker Processing |processing-job/ml.m5.large |2|