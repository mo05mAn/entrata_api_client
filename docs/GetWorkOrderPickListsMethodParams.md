# GetWorkOrderPickListsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. The node accepts multiple propertyIds as the input value. | [optional] 

## Example

```python
from openapi_client.models.get_work_order_pick_lists_method_params import GetWorkOrderPickListsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickListsMethodParams from a JSON string
get_work_order_pick_lists_method_params_instance = GetWorkOrderPickListsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickListsMethodParams.to_json())

# convert the object into a dict
get_work_order_pick_lists_method_params_dict = get_work_order_pick_lists_method_params_instance.to_dict()
# create an instance of GetWorkOrderPickListsMethodParams from a dict
get_work_order_pick_lists_method_params_from_dict = GetWorkOrderPickListsMethodParams.from_dict(get_work_order_pick_lists_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


