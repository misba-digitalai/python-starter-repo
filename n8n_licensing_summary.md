# n8n Licensing Summary for Business Use
*A practical guide for using n8n in products serving multiple customers*

## 🎯 Executive Summary

n8n uses a **Sustainable Use License** (not traditional open source) that allows **free use for internal business purposes** but requires a **commercial license for customer-facing products**. For businesses building products that serve multiple customers, you'll likely need n8n's **Embed license**.

## 📜 License Types

### 1. Sustainable Use License (Free)
- **What it covers**: n8n core functionality
- **Cost**: Free
- **Key restriction**: Internal business purposes only

### 2. Enterprise License (Paid)
- **What it covers**: Enterprise features (`.ee.` files)
- **Cost**: Paid subscription
- **Use case**: Advanced features for self-hosted deployments

### 3. n8n Embed (Commercial)
- **What it covers**: Embedding n8n in customer-facing products
- **Cost**: Commercial agreement required
- **Contact**: [license@n8n.io](mailto:license@n8n.io)

## ✅ What's ALLOWED Under Free License

### Internal Business Operations
- ✅ Sync your company's data (CRM to database)
- ✅ Automate internal workflows
- ✅ Create custom n8n nodes for your products
- ✅ Provide n8n consulting services
- ✅ Set up and maintain n8n on company servers
- ✅ Use n8n as backend with **your company's credentials**

### Customer-Facing Use Cases (Limited)
- ✅ **AI chatbot powered by n8n** (using your company's AI credentials)
- ✅ Backend automation where customers don't directly interact with n8n
- ✅ Features where **no customer credentials** are collected

## ❌ What's NOT ALLOWED Under Free License

### Direct Customer Access
- ❌ White-labeling n8n and selling it to customers
- ❌ Hosting n8n and charging customers for access
- ❌ Collecting customer credentials to access their data
- ❌ **Customer HubSpot sync** (using customer's HubSpot credentials)

### Revenue-Generating Features
- ❌ Products where value derives entirely from n8n functionality
- ❌ Reselling n8n capabilities as a service
- ❌ Multi-tenant n8n instances for customers

## 🎯 Business Decision Framework

### Use Free License When:
```
✅ Internal automation only
✅ Your credentials, your workflows
✅ Customers interact with your app, not n8n directly
✅ n8n provides supporting functionality, not core value
```

### Need Commercial License When:
```
❌ Customers connect their own accounts
❌ Multi-tenant workflow automation service
❌ White-labeled workflow solution
❌ Core product value depends on n8n
```

## 💼 Real-World Examples

### ✅ ALLOWED Examples

**1. Customer Support Automation**
- Your app uses n8n to route support tickets
- Uses your company's Slack/email credentials
- Customers interact with your support interface, not n8n

**2. AI-Powered Product Features**
- n8n orchestrates AI workflows behind the scenes
- Uses your OpenAI/Claude credentials
- Customers see AI features in your app

**3. Data Processing Pipeline**
- n8n processes customer data using your infrastructure
- No customer credentials collected
- Customers upload data through your interface

### ❌ NOT ALLOWED Examples

**1. "Zapier Alternative" Product**
- Customers connect their own Google/Slack accounts
- Multi-tenant n8n deployment
- **Requires n8n Embed license**

**2. Workflow-as-a-Service**
- Customers build workflows directly in n8n
- White-labeled n8n interface
- **Requires n8n Embed license**

**3. Integration Platform**
- Customers authenticate with their own services
- n8n provides the core automation value
- **Requires n8n Embed license**

## 🚀 Getting Started Recommendations

### Phase 1: Validate with Free License
1. Build internal automation workflows
2. Create proof-of-concept with your credentials
3. Test customer-facing features (without customer auth)

### Phase 2: Scale with Commercial License
1. Contact n8n team: [license@n8n.io](mailto:license@n8n.io)
2. Discuss n8n Embed pricing and terms
3. Implement multi-tenant architecture

### Phase 3: Enterprise Features
1. Evaluate Enterprise license needs
2. Consider self-hosted vs. cloud deployment
3. Implement advanced security and compliance

## 📞 Next Steps

### For Internal Use Only
- ✅ Start building immediately with free license
- ✅ Download and deploy n8n
- ✅ Begin automating internal workflows

### For Customer-Facing Products
1. **Contact n8n**: [license@n8n.io](mailto:license@n8n.io)
2. **Describe your use case** in detail
3. **Get commercial pricing** and terms
4. **Negotiate n8n Embed agreement**

### When Uncertain
- 📧 Email: [license@n8n.io](mailto:license@n8n.io)
- 🔗 Reference: [n8n Embed page](https://n8n.io/embed)
- 📖 Full License: [Sustainable Use License](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)

## ⚖️ Risk Assessment

### Low Risk (Free License)
- Internal automation only
- Your credentials, your data
- Clear separation from customer-facing features

### Medium Risk (Clarification Needed)
- Mixed internal/external use
- Unclear credential ownership
- Complex product integration

### High Risk (Commercial License Required)
- Customer credential collection
- Multi-tenant architecture
- Workflow automation as core value

---

**Remember**: When in doubt, ask n8n directly. They encourage discussions about licensing and are generally helpful in clarifying edge cases. The key principle is whether customers directly interact with n8n functionality or provide their own credentials for automation.

**Contact**: [license@n8n.io](mailto:license@n8n.io) | **Reference**: [Official License FAQ](https://docs.n8n.io/sustainable-use-license/)
