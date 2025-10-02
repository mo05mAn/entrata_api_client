# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy

Property policies

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pet** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInner.md) | Pet policy | [optional] 
**general** | **str** | General policies for the property | [optional] 

## Example

```python
from openapi_client.models.get_mits_property_units_success_response_result_physical_property_policy import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy from a JSON string
get_mits_property_units_success_response_result_physical_property_policy_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_policy_dict = get_mits_property_units_success_response_result_physical_property_policy_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy from a dict
get_mits_property_units_success_response_result_physical_property_policy_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy.from_dict(get_mits_property_units_success_response_result_physical_property_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


