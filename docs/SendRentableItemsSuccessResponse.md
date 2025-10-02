# SendRentableItemsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**SendRentableItemsSuccessResponseResult**](SendRentableItemsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_rentable_items_success_response import SendRentableItemsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentableItemsSuccessResponse from a JSON string
send_rentable_items_success_response_instance = SendRentableItemsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendRentableItemsSuccessResponse.to_json())

# convert the object into a dict
send_rentable_items_success_response_dict = send_rentable_items_success_response_instance.to_dict()
# create an instance of SendRentableItemsSuccessResponse from a dict
send_rentable_items_success_response_from_dict = SendRentableItemsSuccessResponse.from_dict(send_rentable_items_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


