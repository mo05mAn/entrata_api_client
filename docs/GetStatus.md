# GetStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetStatusMethod**](GetStatusMethod.md) |  | 

## Example

```python
from openapi_client.models.get_status import GetStatus

# TODO update the JSON string below
json = "{}"
# create an instance of GetStatus from a JSON string
get_status_instance = GetStatus.from_json(json)
# print the JSON string representation of the object
print(GetStatus.to_json())

# convert the object into a dict
get_status_dict = get_status_instance.to_dict()
# create an instance of GetStatus from a dict
get_status_from_dict = GetStatus.from_dict(get_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


