# SendRentableItemsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**category_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**name** | **str** | This is an optional field. This field accepts single value. | 
**show_on_website** | **int** | This is an optional field. This field accepts single value. | [optional] 
**is_marketed** | **int** | This is an optional field. This field accepts single value. | [optional] 
**has_inventory** | **int** | This is an optional field. This field accepts single value. | [optional] 
**availability_status_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**description** | **str** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.send_rentable_items_method_params import SendRentableItemsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentableItemsMethodParams from a JSON string
send_rentable_items_method_params_instance = SendRentableItemsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendRentableItemsMethodParams.to_json())

# convert the object into a dict
send_rentable_items_method_params_dict = send_rentable_items_method_params_instance.to_dict()
# create an instance of SendRentableItemsMethodParams from a dict
send_rentable_items_method_params_from_dict = SendRentableItemsMethodParams.from_dict(send_rentable_items_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


