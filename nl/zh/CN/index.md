---

copyright:
  years: 2016,2018
lastupdated: "2018-03-26"
---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# 关于 {{site.data.keyword.composeForMySQL}}
{: #about-compose-for-mysql}

借助大量 ANSI SQL 99 子集及其自己的广泛扩展集，包括 JSON 文档、全文搜索和可更新视图，MySQL 为开发者提供了内容丰富的选用板，供其在自己的应用程序中使用。此外，还为管理员提供了诸多数据库管理工具，可选择用于处理 MySQL。{{site.data.keyword.composeForMySQL_full}} 通过为您管理 MySQL，并提供易于使用、自动扩展的部署系统以交付高可用性、冗余性和自动备份功能，从而扩展 MySQL 的功能。
{:shortdesc}

## 创建 {{site.data.keyword.composeForMySQL}} 服务实例

您可以在 {{site.data.keyword.cloud_notm}}“目录”的 [{{site.data.keyword.composeForMySQL}} 页面](https://console.{DomainName}/catalog/services/compose-for-mysql/)中创建 {{site.data.keyword.composeForMySQL}} 服务。

选择服务名称以及要在其中供应该服务的区域、组织和空间。可以使用**选择数据库版本**字段从可用数据库版本中进行选择。

供应 {{site.data.keyword.composeForMySQL}} 实例时，可以选择*标准*或*企业*套餐。使用*企业*套餐，您可以将 {{site.data.keyword.composeForMySQL}} 实例供应到可用的 {{site.data.keyword.composeEnterprise}} 集群中。{{site.data.keyword.composeEnterprise}} 提供企业合规性所需的安全性和隔离，并使用专用网络来确保已部署的数据库的性能。有关更多详细信息，请参阅 [Compose Enterprise 文档](../ComposeEnterprise/index.html)。

## 管理 {{site.data.keyword.composeForMySQL}}

您可以从服务仪表板管理服务。您可以在此找到有关 {{site.data.keyword.cloud}} Compose 数据库以及如何连接到该数据库的信息。您还可以：
- 管理备份
- 为服务分配更多资源
- 更改服务密码
- 使用白名单来限制对数据库的访问。 

有关更多信息，请参阅[设置](./dashboard-settings.html)。

{{site.data.keyword.composeForMySQL}} 依赖于 Cloud Foundry 角色来管理对服务的访问权。只有具有开发者角色的用户才能查看或使用服务仪表板。有关 Cloud Foundry 角色的更多信息，请参阅 [Cloud Foundry 访问权](https://console.bluemix.net/docs/iam/cfaccess.html#cfaccess)和[管理 Cloud Foundry 访问权](https://console.bluemix.net/docs/iam/mngcf.html#mngcf)页面。
{: .tip}

## 连接到 {{site.data.keyword.composeForMySQL}}

您可以使用随服务一起创建的凭证，或者使用服务仪表板*概述*选项卡中提供的连接字符串和命令行，来连接到服务。

## 将 {{site.data.keyword.cloud_notm}} 应用程序连接到 {{site.data.keyword.composeForMySQL}}

要将 {{site.data.keyword.cloud_notm}} 应用程序连接到服务，请使用随服务一起创建的凭证。您可以在[连接 {{site.data.keyword.cloud_notm}} 应用程序](./connecting-bluemix-app.html)中查找有关如何将 {{site.data.keyword.cloud_notm}} 应用程序连接到服务的信息。

## 从外部 {{site.data.keyword.cloud_notm}} 连接到 {{site.data.keyword.composeForMySQL}}

如果要从外部 {{site.data.keyword.cloud_notm}} 连接到服务，可以使用提供的连接字符串或命令行。您可以在[连接外部应用程序](./connecting-external.html)中找到有关如何连接的信息。
