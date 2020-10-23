# Pushy::PushNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**to** | **String** |  | [optional] 
**data** | [**Object**](.md) | The payload data you want to push to devices, limited to 4kb and accessible in your notification listener. | [optional] 
**notification** | [**Notification**](Notification.md) |  | [optional] 
**time_to_live** | **Integer** | Specifies how long (in seconds) the push notification should be kept if the device is offline. The default value is 1 month. The maximum value is 1 year. | [optional] 

## Code Sample

```ruby
require 'Pushy'

instance = Pushy::PushNotification.new(to: a6345d0278adc55d3474f5,
                                 data: {&quot;message&quot;:&quot;Hello World!&quot;},
                                 notification: null,
                                 time_to_live: null)
```


