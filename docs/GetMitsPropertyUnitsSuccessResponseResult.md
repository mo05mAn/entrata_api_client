# GetMitsPropertyUnitsSuccessResponseResult

Result data containing detailed property information

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**physical_property** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty**](GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result import GetMitsPropertyUnitsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResult from a JSON string
get_mits_property_units_success_response_result_instance = GetMitsPropertyUnitsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResult.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_dict = get_mits_property_units_success_response_result_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResult from a dict
get_mits_property_units_success_response_result_from_dict = GetMitsPropertyUnitsSuccessResponseResult.from_dict(get_mits_property_units_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


