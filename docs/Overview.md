# Overview

## Article Metadata

Follow these rules to modify article properties within a Freshdesk article.

---

### Tags for Product Pricing Table

Each article has a pricing plan on top that shows which SKUs and tiers apply to the article.  
Use the following tags to add that table. Features in a tier are available in every higher tier, so each tag cascades upwards. Add only the tag for the lowest applicable plan per product SKU.

```markdown
|         | Free+             | Growth+           | Pro+           | Enterprise           |
|---------|------------------|-------------------|----------------|----------------------|
| Freshdesk | freshdesk_free   | freshdesk_growth  | freshdesk_pro  | freshdesk_enterprise |
| Freshchat | freshchat_free   | freshchat_growth  | freshchat_pro  | freshchat_enterprise |
