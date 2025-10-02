# GetInspectionTemplatesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Identifier of the request | 
**code** | **str** | Status code of the response | 
**result** | [**GetInspectionTemplatesSuccessResponseResult**](GetInspectionTemplatesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_inspection_templates_success_response import GetInspectionTemplatesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplatesSuccessResponse from a JSON string
get_inspection_templates_success_response_instance = GetInspectionTemplatesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplatesSuccessResponse.to_json())

# convert the object into a dict
get_inspection_templates_success_response_dict = get_inspection_templates_success_response_instance.to_dict()
# create an instance of GetInspectionTemplatesSuccessResponse from a dict
get_inspection_templates_success_response_from_dict = GetInspectionTemplatesSuccessResponse.from_dict(get_inspection_templates_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


