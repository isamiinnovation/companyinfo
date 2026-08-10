# Support — Azure Cost Optimizer

**Publisher:** ISAMI INNOVATIONS CO., LTD.  
**Service:** Azure Cost Optimizer (Microsoft Azure Marketplace)

---

## Contact Support

### 📧 Email Support

For any issues, questions, or feedback, please contact us by email. Include your Azure Subscription ID and Tenant ID to help us resolve your request quickly.

**Support email:** [admin@isamiinnovations.com](mailto:admin@isamiinnovations.com)

---

## Response Time & SLA

Our support team operates **Monday – Friday, JST (UTC+9)**, excluding Japanese public holidays.

| Priority | Description | Initial Response | Resolution Target |
|---|---|---|---|
| **High** | Service completely unavailable; no workaround | 4 business hours | 2 business days |
| **Medium** | Core feature impaired; workaround available | 1 business day | 5 business days |
| **Low** | General questions, feature requests, docs | 2 business days | Best effort |

---

## What to Include in Your Support Request

Please provide the following to help us resolve your issue faster:

- **Azure Subscription ID** — found in Azure Portal → Subscriptions
- **Tenant ID** — found in Microsoft Entra ID → Overview
- **Marketplace Subscription ID** — found in your Azure Cost Optimizer dashboard
- **Description of the issue** — steps to reproduce, expected behavior, actual behavior
- **ARM template (if applicable)** — remove any secrets or credentials before attaching
- **Screenshots or error messages** — any relevant error text or browser console output

---

## Frequently Asked Questions

**How do I export an ARM template from a resource group?**  
In the Azure Portal, navigate to your Resource Group → Overview → Export template. Download the JSON file and upload it to Azure Cost Optimizer.

**Is my ARM template data stored on your servers?**  
No. ARM template data is processed transiently during analysis and deleted immediately after your session completes. We do not store your resource data unless you explicitly save a report.

**Which Azure regions are supported?**  
All public Azure regions are supported. Cost data is retrieved using the Azure Retail Prices API, which covers all generally available regions.

**How do I cancel my subscription?**  
Subscriptions can be cancelled at any time through the Microsoft Azure Marketplace portal: Marketplace → SaaS → your subscription → Cancel subscription.

**Can I analyze multiple resource groups at once?**  
The current release supports single resource group analysis per session. Multi-resource group reporting is planned for a future release.

**What Azure roles are required?**  
To export ARM templates, you need Reader access (or higher) on the target resource group. No additional Azure permissions are required by the service itself.

---

## Company Information

| | |
|---|---|
| **Company** | ISAMI INNOVATIONS CO., LTD. |
| **Support email** | [support@isamiinnovations.com](mailto:admin@isamiinnovations.com) |
| **Privacy inquiries** | [privacy@isamiinnovations.com](mailto:admin@isamiinnovations.com) |
| **Privacy Policy** | [View Privacy Policy](./privacy_policy.md) |

---

*&copy; 2026 ISAMI INNOVATIONS CO., LTD.*
