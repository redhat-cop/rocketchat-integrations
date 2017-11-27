# RocketChat Integrations for GitHub

The following are the scripts we use to integrate GitHub with RocketChat.

## GitHub Event Notifications

1. Create a new Incoming WebHook
1. Select the channel where you will receive the alerts. You may wish to create a dedicated channel for your notifications.
1. Select an account from which the alerts will be posted. You may wish to create a dedicated account just for notifications.
1. Set the “Enable Scripts” option to True.
1. Copy-paste the contents of `./event_alerts.js`
1. Save the integration. This will generate a webhook URL and secret for you.
1. Go to your repository `Settings -> WebHooks & services -> Add WebHook`
1. Paste your WebHook URL from Rocket.Chat into Payload URL
1. Keep Content type as application/json
1. Leave Secret empty and save
