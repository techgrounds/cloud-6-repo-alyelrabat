# Azure Monitor 

Azure Monitor is a service in the cloud that helps you increase the performance and availability of your applications and services,
by collecting, analyzing and acting on telemetry from your cloud and on-premise environments.
You are actually using Azure Monitor from the moment you create a natural resource. Metrics are automatically collected that measure its performance and 
logs are collected that show the activity in your Azure subscription. With a little configuration (diagnostics settings) you can collect more detailed logs for 
further insights on your resources and operations. You can access much of this information from each resources menu in the Azure Portal, or go to the Azure monitor menu 
to access a wider set of features, and to work with monitoring data collected across all your aplications and services.

The data that Azure Monitor collects starts with the Azure platform. This includes sign on information from Active Directory audit logs, the activity log for service health
and configuration changes for your Azure resources, resource logs, platform metrics which provide details to the operation details of each resource.
Compute resources such as Virtual Machines supporting your applications infrastructure, recuire an agent to collect logs and performance data, from the guest operating systems workloads.
These VMs can live in Azure, another cloud and or on-premises. you can also connect and existing systme center operations manager environment.
For your application it self, use the application insights feature of Azure Monitor, to collect detailed metrics and logs, related to the performance and operation
of an application written in any lanuage in any environment. 

For anything else Azure Monitor has API,s that will allow you to collect data from any REST API client.
Data collected from all resources is collected together in Azure Monitor into either metrics or logs. This allows you to analyze data across all of your resources using a common set of methods and tools.
Metrics are stored in the time series database, and are lightweight and capable to supporting near to real time scenarios, making them particulary useful for 
alerting, and fast detection of issues. Logs contain different kinds of data that you can analyze together with a powerful query lanuage.
They,re especially useful for performing complex analysis accross data from a variety of sources. Once data has been collected, Azure monitor has a complete set of feautures
to analyze and act on that data. You can interactively work with metric data, using metrics explorer in the Azure portal. Analyze metrics from a single resource, or combine multiple metrics
accross different resources. 

Log analytics is a tool that lets you write queries to analyze all of your log data, and interactively work with the results. Add metric
graphs and output from your queries to Azure dashboards, to visualize them with other data. Or go to the next level with workbooks, wich combine text, log queries,
metrics and parameters into interactive reports. In addition to interactively working with monitoring data, Azure monitor can proactively alert you when a metric value,
or the results of a log query indicate a problem. you can define automated actions such as calling a webhook, launching an automation runbook or Azure function, or 
starting an Azure logic app, wich are all fully intergrated with Azure monitor,s data. Use auto scale to automatically add or remove compute recources, based
on the load measured biometric values.

Insights provides a customized monitoring experience built on Azure Monitor data and features,

