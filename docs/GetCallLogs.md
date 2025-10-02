# GetCallLogs


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetCallLogsMethod**](GetCallLogsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_call_logs import GetCallLogs

# TODO update the JSON string below
json = "{}"
# create an instance of GetCallLogs from a JSON string
get_call_logs_instance = GetCallLogs.from_json(json)
# print the JSON string representation of the object
print(GetCallLogs.to_json())

# convert the object into a dict
get_call_logs_dict = get_call_logs_instance.to_dict()
# create an instance of GetCallLogs from a dict
get_call_logs_from_dict = GetCallLogs.from_dict(get_call_logs_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


