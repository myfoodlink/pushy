# Pushy::ApiError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **String** |  | [optional] 
**error** | **String** |  | [optional] 

## Code Sample

```ruby
require 'Pushy'

instance = Pushy::ApiError.new(code: NO_RECIPIENTS,
                                 error: No devices matched the specified condition.)
```


