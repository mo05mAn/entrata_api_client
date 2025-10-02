# UpdateWorkOrdersR2Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateWorkOrdersR1MethodParams**](UpdateWorkOrdersR1MethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_work_orders_r2_method import UpdateWorkOrdersR2Method

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR2Method from a JSON string
update_work_orders_r2_method_instance = UpdateWorkOrdersR2Method.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR2Method.to_json())

# convert the object into a dict
update_work_orders_r2_method_dict = update_work_orders_r2_method_instance.to_dict()
# create an instance of UpdateWorkOrdersR2Method from a dict
update_work_orders_r2_method_from_dict = UpdateWorkOrdersR2Method.from_dict(update_work_orders_r2_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


