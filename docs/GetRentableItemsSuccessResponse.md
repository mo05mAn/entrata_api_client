# GetRentableItemsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetRentableItemsSuccessResponseResponse**](GetRentableItemsSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.get_rentable_items_success_response import GetRentableItemsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItemsSuccessResponse from a JSON string
get_rentable_items_success_response_instance = GetRentableItemsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetRentableItemsSuccessResponse.to_json())

# convert the object into a dict
get_rentable_items_success_response_dict = get_rentable_items_success_response_instance.to_dict()
# create an instance of GetRentableItemsSuccessResponse from a dict
get_rentable_items_success_response_from_dict = GetRentableItemsSuccessResponse.from_dict(get_rentable_items_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


