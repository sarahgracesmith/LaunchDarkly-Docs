---
title: "Custom properties"
excerpt: ""
---
## Overview
This topic explains how to set up and use custom properties in LaunchDarkly.

If you're building an integration for LaunchDarkly, it might be helpful to store data for your integration with a LaunchDarkly feature flag. Custom properties allow you to do this. 

Each custom property you add to a feature flag can contain a list of associated values. For example, if you create an integration with an issue tracking service, you may want to associate a flag with a list of issues related to a feature's development.
## Setting a custom property
You can set a custom property from the LaunchDarkly UI or by using API calls. To learn more, read the [REST API Documentation](https://apidocs.launchdarkly.com/docs/feature-flags-overview).

To add a custom property to a flag through the UI:

1. Navigate to the flag's **Settings** page.
2. Click **Add custom property**.
3. Choose a property type from the dropdown.
4. Enter **Values** associated with the custom property.
5. Click **Save**.
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/244d9f3-Screen_Shot_2018-05-29_at_2.07.21_PM.png",
        "Screen Shot 2018-05-29 at 2.07.21 PM.png",
        689,
        1099,
        "#f7f7f6"
      ],
      "sizing": "80",
      "caption": "A flag's custom property configuration fields."
    }
  ]
}
[/block]

<Callout intent="alert">
  <CalloutTitle>Custom property restrictions</CalloutTitle>
  <CalloutDescription>Custom properties have the following restrictions\n- You can set a maximum of 64 custom properties\n- Each custom property's name and key must be at most 64 characters</CalloutDescription>
</Callout>