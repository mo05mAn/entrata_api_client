# GetCustomersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **str** | Response code indicating the status of the request | 
**result** | [**GetCustomersSuccessResponseResult**](GetCustomersSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_customers_success_response import GetCustomersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersSuccessResponse from a JSON string
get_customers_success_response_instance = GetCustomersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetCustomersSuccessResponse.to_json())

# convert the object into a dict
get_customers_success_response_dict = get_customers_success_response_instance.to_dict()
# create an instance of GetCustomersSuccessResponse from a dict
get_customers_success_response_from_dict = GetCustomersSuccessResponse.from_dict(get_customers_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


