# GetPropertyFeesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request | 
**code** | **int** | Success response code | 
**result** | [**GetPropertyFeesSuccessResponseResponseResult**](GetPropertyFeesSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_fees_success_response_response import GetPropertyFeesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyFeesSuccessResponseResponse from a JSON string
get_property_fees_success_response_response_instance = GetPropertyFeesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetPropertyFeesSuccessResponseResponse.to_json())

# convert the object into a dict
get_property_fees_success_response_response_dict = get_property_fees_success_response_response_instance.to_dict()
# create an instance of GetPropertyFeesSuccessResponseResponse from a dict
get_property_fees_success_response_response_from_dict = GetPropertyFeesSuccessResponseResponse.from_dict(get_property_fees_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


