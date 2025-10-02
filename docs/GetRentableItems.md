# GetRentableItems


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetRentableItemsMethod**](GetRentableItemsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_rentable_items import GetRentableItems

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItems from a JSON string
get_rentable_items_instance = GetRentableItems.from_json(json)
# print the JSON string representation of the object
print(GetRentableItems.to_json())

# convert the object into a dict
get_rentable_items_dict = get_rentable_items_instance.to_dict()
# create an instance of GetRentableItems from a dict
get_rentable_items_from_dict = GetRentableItems.from_dict(get_rentable_items_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


