# UpdateWorkOrdersR1Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateWorkOrdersR1MethodParams**](UpdateWorkOrdersR1MethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_work_orders_r1_method import UpdateWorkOrdersR1Method

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR1Method from a JSON string
update_work_orders_r1_method_instance = UpdateWorkOrdersR1Method.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR1Method.to_json())

# convert the object into a dict
update_work_orders_r1_method_dict = update_work_orders_r1_method_instance.to_dict()
# create an instance of UpdateWorkOrdersR1Method from a dict
update_work_orders_r1_method_from_dict = UpdateWorkOrdersR1Method.from_dict(update_work_orders_r1_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


