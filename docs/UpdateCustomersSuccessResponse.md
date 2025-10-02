# UpdateCustomersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The response code indicating the status of the request. | 
**result** | [**UpdateCustomersSuccessResponseResult**](UpdateCustomersSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.update_customers_success_response import UpdateCustomersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomersSuccessResponse from a JSON string
update_customers_success_response_instance = UpdateCustomersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomersSuccessResponse.to_json())

# convert the object into a dict
update_customers_success_response_dict = update_customers_success_response_instance.to_dict()
# create an instance of UpdateCustomersSuccessResponse from a dict
update_customers_success_response_from_dict = UpdateCustomersSuccessResponse.from_dict(update_customers_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


