---
title: "Extra Edit Reward"
num: 13.6
---

Updates a Custom Channel Points Reward created on your channel, allowing you to change additional settings that are not accessible from the regular [Edit Reward](twitch#editreward) command.

{% include alert.html text="You can only edit rewards that were previously created with SAMMI (you can verify it says 'Owned' in Twitch Connections - Edit Rewards window, and dupe it if needed)" type="warning" %} 

| Box Name | Type | Description | 
|-------|--------|--------
|Login Name|String|Your Twitch login name (all lowercase characters)
|Reward (ID required)|Dropdown|ID of the custom reward to update. 
|Description|String|Description of the reward.
|Color|Dropdown|Display colour of the reward on Twitch.
|User Input|Checkbox|If enabled, requires a viewer's input.
|Skip Queue|Checkbox|If enabled, allows the redemption to skip the queue.
|Cooldown (s)|Number {% include asterisk.html%}|Amount of seconds the reward will be on a cooldown.
|Max/User|Number {% include asterisk.html%}|Number of allowed redemptions per user.
|Max/Stream|Number {% include asterisk.html%}|Number of allowed redemptions per stream.
{:class='table table-primary'}










