# GetInspectionsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Identifier of the request | 
**code** | **str** | Status code of the response | 
**result** | [**GetInspectionsSuccessResponseResult**](GetInspectionsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_inspections_success_response import GetInspectionsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsSuccessResponse from a JSON string
get_inspections_success_response_instance = GetInspectionsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsSuccessResponse.to_json())

# convert the object into a dict
get_inspections_success_response_dict = get_inspections_success_response_instance.to_dict()
# create an instance of GetInspectionsSuccessResponse from a dict
get_inspections_success_response_from_dict = GetInspectionsSuccessResponse.from_dict(get_inspections_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


