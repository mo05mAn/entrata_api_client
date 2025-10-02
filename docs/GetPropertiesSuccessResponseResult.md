# GetPropertiesSuccessResponseResult

Result containing the property details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**physical_property** | [**GetPropertiesSuccessResponseResultPhysicalProperty**](GetPropertiesSuccessResponseResultPhysicalProperty.md) |  | 

## Example

```python
from entrata_api_client.models.get_properties_success_response_result import GetPropertiesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesSuccessResponseResult from a JSON string
get_properties_success_response_result_instance = GetPropertiesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesSuccessResponseResult.to_json())

# convert the object into a dict
get_properties_success_response_result_dict = get_properties_success_response_result_instance.to_dict()
# create an instance of GetPropertiesSuccessResponseResult from a dict
get_properties_success_response_result_from_dict = GetPropertiesSuccessResponseResult.from_dict(get_properties_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


