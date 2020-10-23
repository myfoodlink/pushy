# Pushy::PushResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** |  | [optional] 
**success** | **Boolean** |  | [optional] 
**info** | [**Object**](.md) | Contains additional information about the notification, for debugging purposes. | [optional] 

## Code Sample

```ruby
require 'Pushy'

instance = Pushy::PushResponse.new(id: 5ea9b214b47cad768a35f13a,
                                 success: true,
                                 info: {&quot;devices&quot;:1})
```


