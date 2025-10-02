# GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the legal entity. | 
**name** | **str** | Name of the legal entity. | 
**tax_id_number** | **str** | Tax ID number of the legal entity. | 
**receives1099** | **str** | Indicates if the legal entity receives a 1099 form. | 
**form1099_type_id** | **str** | Unique identifier for the 1099 form type. | 
**form1099_type** | **str** | Type of 1099 form. | 
**form1099_box_type_id** | **str** | Unique identifier for the 1099 form box type. | 
**form1099_box_type** | **str** | Box type of the 1099 form. | 

## Example

```python
from openapi_client.models.get_vendors_success_response_result_vendors_vendor_inner_legal_entities_legal_entity_inner import GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_legal_entities_legal_entity_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_legal_entities_legal_entity_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_legal_entities_legal_entity_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_legal_entities_legal_entity_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntitiesLegalEntityInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_legal_entities_legal_entity_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


