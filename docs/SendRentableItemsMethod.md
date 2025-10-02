# SendRentableItemsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendRentableItemsMethodParams**](SendRentableItemsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_rentable_items_method import SendRentableItemsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentableItemsMethod from a JSON string
send_rentable_items_method_instance = SendRentableItemsMethod.from_json(json)
# print the JSON string representation of the object
print(SendRentableItemsMethod.to_json())

# convert the object into a dict
send_rentable_items_method_dict = send_rentable_items_method_instance.to_dict()
# create an instance of SendRentableItemsMethod from a dict
send_rentable_items_method_from_dict = SendRentableItemsMethod.from_dict(send_rentable_items_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


