# Subscriptions
Subscriptions is a relatively new feature in ArticBot, and is definitely a popular command. This command allows users to subscribe to notifications by assigning a specific role to them, and then it allows you to message all your subscribers directly, and send a general announcement. Therefore, you are only pinging people that have subscribed, but everyone can see the announcement.

!!! warning
    Before users can subscribe, you must set up a subscription role, otherwise user's will receive an error. For more information on setting the subscription role up, click [here](commands/settings/set-configuration/#subscriptions).

## Syntax
To subscribe, use `$subscribe` and to unsubscribe, use `$unsubscribe`.

To send a message to all subscribers, use `$sub-message [message]`.