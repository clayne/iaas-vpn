---

copyright:
  years: 1994, 2024
lastupdated: "2024-06-20"

keywords: SSL VPN access, user SSL VPN, IBM Cloud SSL VPN

subcollection: iaas-vpn

---

{{site.data.keyword.attribute-definition-list}}

# Activating or deactivating SSL VPN access for a user
{: #activate-or-deacivate-ssl-vpn-access-for-a-user}
{: help}
{: support}

To get started, you must enable VPN access on each account that needs VPN access. To enable SSL VPN access, follow these steps:

1. Log in to the [{{site.data.keyword.cloud_notm}} console](https://{DomainName}/){: external}.
1. Click **Manage > Access (IAM)**, and select **Users**.
   If you need to add a user, click **Add VPN-only user** or **Invite users**. For more information, see [Inviting users to an account](/docs/account?topic=account-iamuserinv){: external}.
   {: note}

1. Select the name of the user that you want to assign SSL VPN access.
1. From the Manage _User_ page, select the **Classic Infrastructure** tab and then click **VPN subnets**.
1. Select the **Enable SSL VPN Access** checkbox and click **Save**.

   SSL access must be activated before a user can connect by using SSL.
   {: note}
