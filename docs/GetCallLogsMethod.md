# GetCallLogsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetCallLogsMethodParams**](GetCallLogsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_call_logs_method import GetCallLogsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetCallLogsMethod from a JSON string
get_call_logs_method_instance = GetCallLogsMethod.from_json(json)
# print the JSON string representation of the object
print(GetCallLogsMethod.to_json())

# convert the object into a dict
get_call_logs_method_dict = get_call_logs_method_instance.to_dict()
# create an instance of GetCallLogsMethod from a dict
get_call_logs_method_from_dict = GetCallLogsMethod.from_dict(get_call_logs_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


