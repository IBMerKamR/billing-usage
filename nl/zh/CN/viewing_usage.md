---

copyright:
  years: 2017, 2019
lastupdated: "2019-01-28"

keywords: view usage, view cost, service usage, usage access, usage report

subcollection: billing-usage

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}


# 查看使用情况
{: #viewingusage}

您可以在 {{site.data.keyword.Bluemix}} 控制台中的“使用情况”页面中查看使用情况详细信息，包括组织中每月使用的所有资源、服务和支持套餐的估算费用摘要。
{:shortdesc}

记帐管理者只能查看他们在其中拥有“记帐管理者”角色的组织的详细信息。
{: note}


## 查看使用情况许可权
{: #view-usage-permissions}

对于 Cloud Foundry 管理的资源，必须在组织级别应用“记帐管理者”角色。要查看 {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) 资源使用情况，必须对资源组应用“查看者”角色。有关许可权角色的更多信息，请参阅 [IAM 访问权](/docs/iam?topic=iam-userroles)、[Cloud Foundry 访问权](/docs/iam?topic=iam-cfaccess)或[经典基础架构许可权](/docs/iam?topic=iam-infrapermission)。

## 查看服务使用情况详细信息
{: #services}

在“服务”部分中，可以查看服务的列表以及与这些服务关联的估算成本。要查看特定资源的所有实例的估算费用摘要，请完成以下步骤：

1. 转至**管理 > 计费和使用情况**，然后选择**使用情况**。
2. 单击**查看实例**以查看特定类型资源的所有实例。  
3. 要查看特定资源类型的每个实例的估算费用详细摘要，请单击**查看实例详细信息**。还可以查看所选实例的每月详细使用量度量值。

在每个计费周期结束时，向帐户所有者收取所有组织中发生的总使用量费用。每个计费周期为一个月。

帐户所有者可以按组过滤使用量摘要，并选择使用量的时间范围。所显示的费用表示该月向您（作为帐户所有者）收取的金额。

如果从**按组过滤**列表中选择特定组织，那么可以看到该组织的总使用量，包括属于免费层的任何使用量。免费层使用量在帐户级别显示为免费，但在组织级别不会显示为免费。查看组织使用量时，会看到该组织的实际使用量，包括免费使用量和收费使用量。除去免费层后，所有组织使用量都会累积到帐户使用量上。

现收现付帐户的帐户管理者可以针对运行时和服务以及针对单个服务（排除第三方服务）根据帐户总成本设置花费通知。有关更多信息，请参阅[设置花费通知](/docs/billing-usage?topic=billing-usage-spending)。

## 将使用情况详细信息导出为 `.csv` 文件
{: #export-csv}

您可以将使用情况的摘要或有关服务和实例的信息导出为 CSV 文件。通过导出为 CSV 文件，您可以方便地查找每个资源的使用情况和成本估算信息，以便向客户退款或了解有关成本的更多信息。

1. 转至**管理 > 计费和使用情况**，然后选择**使用情况**。
2. 单击**导出为 CSV**。  
