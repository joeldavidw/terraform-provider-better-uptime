---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "betteruptime_metadata Resource - terraform-provider-better-uptime"
subcategory: ""
description: |-
  https://betterstack.com/docs/uptime/api/metadata/
---

# betteruptime_metadata (Resource)

https://betterstack.com/docs/uptime/api/metadata/



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **key** (String) The key of this Metadata.
- **owner_id** (Number) The ID of the owner of this Metadata.
- **owner_type** (String) The type of the owner of this Metadata. Valid values: `Monitor`, `Heartbeat`, `Incident`, `WebhookIntegration`, `EmailIntegration`, `IncomingWebhook`
- **value** (String) The value of this Metadata.

### Read-Only

- **created_at** (String) The time when this metadata was created.
- **id** (String) The ID of this Metadata.
- **updated_at** (String) The time when this metadata was updated.

