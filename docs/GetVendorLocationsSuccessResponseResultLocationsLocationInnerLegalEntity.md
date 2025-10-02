# GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**value** | **str** | Legal entity name. | 
**attributes** | [**GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntityAttributes**](GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntityAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response_result_locations_location_inner_legal_entity import GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity from a JSON string
get_vendor_locations_success_response_result_locations_location_inner_legal_entity_instance = GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity.to_json())

# convert the object into a dict
get_vendor_locations_success_response_result_locations_location_inner_legal_entity_dict = get_vendor_locations_success_response_result_locations_location_inner_legal_entity_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity from a dict
get_vendor_locations_success_response_result_locations_location_inner_legal_entity_from_dict = GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity.from_dict(get_vendor_locations_success_response_result_locations_location_inner_legal_entity_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


