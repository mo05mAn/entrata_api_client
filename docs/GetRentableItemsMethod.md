# GetRentableItemsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPropertyAddOnsMethodParams**](GetPropertyAddOnsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_rentable_items_method import GetRentableItemsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItemsMethod from a JSON string
get_rentable_items_method_instance = GetRentableItemsMethod.from_json(json)
# print the JSON string representation of the object
print(GetRentableItemsMethod.to_json())

# convert the object into a dict
get_rentable_items_method_dict = get_rentable_items_method_instance.to_dict()
# create an instance of GetRentableItemsMethod from a dict
get_rentable_items_method_from_dict = GetRentableItemsMethod.from_dict(get_rentable_items_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


