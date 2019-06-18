---

copyright:
  years: 2019

lastupdated: "2019-06-17"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:important: .important}
{:tip: .tip}

# Getting started with Power Systems Virtual Servers
{: #getting-started}

{{site.data.keyword.powerSysFull}} is an infrastructure as a service offering that you can use to deploy a virtual server, also known as a logical partition (LPAR), in a matter of minutes.
{:shortdesc}

You can quickly deploy {{site.data.keyword.powerSys_notm}}s to meet your specific business needs. With {{site.data.keyword.powerSys_notm}} you can create a hybrid cloud environment that allows you to easily control workload demands.

{{site.data.keyword.powerSys_notm}}s can run AIX or IBM i workloads in different geographic locations.

## Before you begin
{: #gs-before-you-begin}

Before you create your first Power Systems Virtual Server instance, review the following prerequisites:

1. Create an IBM Cloud account. To create an IBM Cloud account, see [Sign up for IBM Cloud ![External link icon](../icons/launch-glyph.svg "External link icon")](https://cloud.ibm.com/registration){: new_window}.

1. Create a public and private SSH key that you can use to securely connect to your {{site.data.keyword.powerSys_notm}}.

1. (Optional) If you want to use a custom image for the AIX or IBM i operating systems, you must create an IBM Cloud Object Storage and upload the image. For more information, see [Configuring a custom image](/docs/infrastructure/power-iaas?topic=power-iaas-configuring-custom-image#configuring-custom-image).

1. (Optional) If you want to use a private network to connect your environment (on-premises) with the {{site.data.keyword.cloud_notm}} environment (off-premise) there are different options that require additional configuration. For more information, see [Configuring Power Systems Virtual Servers with a private network](/docs/infrastructure/power-iaas?topic=power-iaas-cpn-configuring).

## Next steps
{: #gs-next-steps}

With an IBM Cloud account and a private and public SSH key, you are now ready to [Create a {{site.data.keyword.powerSys_notm}}](/docs/infrastructure/power-iaas?topic=power-iaas-creating-power-virtual-server#creating-power-virtual-server).