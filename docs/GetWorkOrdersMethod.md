# GetWorkOrdersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetWorkOrdersMethodParams**](GetWorkOrdersMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_work_orders_method import GetWorkOrdersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersMethod from a JSON string
get_work_orders_method_instance = GetWorkOrdersMethod.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersMethod.to_json())

# convert the object into a dict
get_work_orders_method_dict = get_work_orders_method_instance.to_dict()
# create an instance of GetWorkOrdersMethod from a dict
get_work_orders_method_from_dict = GetWorkOrdersMethod.from_dict(get_work_orders_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


