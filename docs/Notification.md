# Pushy::Notification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**body** | **String** | The main alert message, visible on the lock screen and in other areas on iOS. Supports Apple Emojis via their unicode representation. | [optional] 
**badge** | **Integer** | The number to display as the badge of the app icon. | [optional] 
**sound** | **String** | The filename of a sound in the app bundle or in the Library/Sounds folder of your app&#39;s data container, or a sound dictionary object (iOS 12, more info) . | [optional] 

## Code Sample

```ruby
require 'Pushy'

instance = Pushy::Notification.new(body: Hello World ✌,
                                 badge: 1,
                                 sound: ping.aiff)
```


