---
title: "Slack"
excerpt: ""
---
## Overview
This topic explains how to set up and use the [LaunchDarkly Slack app](https://slack.com/apps/AKEEF9DTM-launchdarkly).

You can use the LaunchDarkly Slack app to view, monitor, and control feature flags for your organization from your team's Slack workspace. Use the app to find feature flags, subscribe to notifications about flag changes, and toggle flags on or off.
<Callout intent="alert">
  <CalloutTitle>Slack app permissions</CalloutTitle>
   <CalloutDescription>The actions you can perform in Slack are limited by your LaunchDarkly role. 
For more information, see [Understanding the Slack App's Permissions](./slack-app-account-management#understanding-the-slack-apps-permissions).</CalloutDescription>
</Callout>

## Why should I use the Slack app?
The LaunchDarkly Slack app lets you see the feature flags associated with a project, monitor updates to existing flags, and make changes to flag targeting when you need to, all from your Slack workspace. You can use it to:

- Call up and view flag details from within Slack for reference or debugging
- Subscribe to all flags tagged for Project X to a Slack channel for Project X to monitor via change notifications
- Create a changelog channel by subscribing to all flag changes in an entire LaunchDarkly project or environment 
- Subscribe to a single flag that controls a key feature to Slack for continuous monitoring
- Turn flag targeting on or off from within Slack

See [setup, accounts, and permissions](./slack-app-account-management) for how to authorize the app.
## 

## Getting Help & Slash Commands
The Slack app has a help menu that can give you details about what you can do, and it describes the slash commands that you can use to interact with the app and your feature flags.

To access the Help menu:


1. Type `/launchdarkly` or `/launchdarkly help` in your Slack client's text bar and press **Enter**. The LaunchDarkly help menu appears with a list of available options.

[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/4f580b0-Screen_Shot_2019-08-15_at_4.16.45_PM.png",
        "Screen Shot 2019-08-
1. at 4.16.45 PM.png",
        1144,
        1160,
        "#f1eeef"
      ],
      "caption": "The help menu"
    }
  ]
}
[/block]