# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**value** | **str** | Value of the concession | [optional] 
**description_header** | **str** | Header for the concession description | [optional] 
**description_body** | **str** | Body of the concession description | [optional] 
**description_footer** | **str** | Footer of the concession description | [optional] 
**attributes** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInnerAttributes**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInnerAttributes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_concession_inner import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner from a JSON string
get_mits_property_units_success_response_result_physical_property_concession_inner_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_concession_inner_dict = get_mits_property_units_success_response_result_physical_property_concession_inner_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner from a dict
get_mits_property_units_success_response_result_physical_property_concession_inner_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner.from_dict(get_mits_property_units_success_response_result_physical_property_concession_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


