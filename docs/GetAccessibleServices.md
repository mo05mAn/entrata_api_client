# GetAccessibleServices


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetAccessibleServicesMethod**](GetAccessibleServicesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_accessible_services import GetAccessibleServices

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleServices from a JSON string
get_accessible_services_instance = GetAccessibleServices.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleServices.to_json())

# convert the object into a dict
get_accessible_services_dict = get_accessible_services_instance.to_dict()
# create an instance of GetAccessibleServices from a dict
get_accessible_services_from_dict = GetAccessibleServices.from_dict(get_accessible_services_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


