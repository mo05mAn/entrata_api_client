# SendRentableItems


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendRentableItemsMethod**](SendRentableItemsMethod.md) |  | 

## Example

```python
from openapi_client.models.send_rentable_items import SendRentableItems

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentableItems from a JSON string
send_rentable_items_instance = SendRentableItems.from_json(json)
# print the JSON string representation of the object
print(SendRentableItems.to_json())

# convert the object into a dict
send_rentable_items_dict = send_rentable_items_instance.to_dict()
# create an instance of SendRentableItems from a dict
send_rentable_items_from_dict = SendRentableItems.from_dict(send_rentable_items_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


