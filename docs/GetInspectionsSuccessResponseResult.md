# GetInspectionsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inspections** | [**GetInspectionsSuccessResponseResultInspections**](GetInspectionsSuccessResponseResultInspections.md) |  | 

## Example

```python
from openapi_client.models.get_inspections_success_response_result import GetInspectionsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsSuccessResponseResult from a JSON string
get_inspections_success_response_result_instance = GetInspectionsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsSuccessResponseResult.to_json())

# convert the object into a dict
get_inspections_success_response_result_dict = get_inspections_success_response_result_instance.to_dict()
# create an instance of GetInspectionsSuccessResponseResult from a dict
get_inspections_success_response_result_from_dict = GetInspectionsSuccessResponseResult.from_dict(get_inspections_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


