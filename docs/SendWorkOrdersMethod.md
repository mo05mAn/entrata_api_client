# SendWorkOrdersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendWorkOrdersMethodParams**](SendWorkOrdersMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_work_orders_method import SendWorkOrdersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrdersMethod from a JSON string
send_work_orders_method_instance = SendWorkOrdersMethod.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrdersMethod.to_json())

# convert the object into a dict
send_work_orders_method_dict = send_work_orders_method_instance.to_dict()
# create an instance of SendWorkOrdersMethod from a dict
send_work_orders_method_from_dict = SendWorkOrdersMethod.from_dict(send_work_orders_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


