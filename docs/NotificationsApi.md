# Pushy::NotificationsApi

All URIs are relative to *https://api.pushy.me*

Method | HTTP request | Description
------------- | ------------- | -------------
[**push_post**](NotificationsApi.md#push_post) | **POST** /push | 



## push_post

> PushResponse push_post(push_notification)



### Example

```ruby
# load the gem
require 'pushy'
# setup authorization
Pushy.configure do |config|
  # Configure API key authorization: ApiKeyAuth
  config.api_key['api_key'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  #config.api_key_prefix['api_key'] = 'Bearer'
end

api_instance = Pushy::NotificationsApi.new
push_notification = Pushy::PushNotification.new # PushNotification | 

begin
  result = api_instance.push_post(push_notification)
  p result
rescue Pushy::ApiError => e
  puts "Exception when calling NotificationsApi->push_post: #{e}"
end
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **push_notification** | [**PushNotification**](PushNotification.md)|  | 

### Return type

[**PushResponse**](PushResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

