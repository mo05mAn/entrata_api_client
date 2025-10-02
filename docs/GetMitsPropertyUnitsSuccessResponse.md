# GetMitsPropertyUnitsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**GetMitsPropertyUnitsSuccessResponseResult**](GetMitsPropertyUnitsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response import GetMitsPropertyUnitsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponse from a JSON string
get_mits_property_units_success_response_instance = GetMitsPropertyUnitsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponse.to_json())

# convert the object into a dict
get_mits_property_units_success_response_dict = get_mits_property_units_success_response_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponse from a dict
get_mits_property_units_success_response_from_dict = GetMitsPropertyUnitsSuccessResponse.from_dict(get_mits_property_units_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


