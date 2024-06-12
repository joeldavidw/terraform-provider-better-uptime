---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "betteruptime_slack_integration Data Source - terraform-provider-better-uptime"
subcategory: ""
description: |-
  Slack integration lookup.
---

# betteruptime_slack_integration (Data Source)

Slack integration lookup.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **slack_channel_name** (String) Name of the connected Slack channel.

### Read-Only

- **id** (String) The ID of this Slack integration.
- **integration_type** (String) Type of the Slack integration. Possible values: legacy, verbose, thread, channel
- **on_call_notifications** (Boolean) Whether to post a notification when the current on-call person changes.
- **slack_channel_id** (String) Slack ID of the connected channel.
- **slack_status** (String) Status of the connected Slack account. Possible values: active, account_inactive
- **slack_team_id** (String) Slack ID of the connected team.
- **slack_team_name** (String) Name of the connected Slack team.

