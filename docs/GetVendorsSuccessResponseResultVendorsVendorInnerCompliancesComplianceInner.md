# GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**legal_entity_id** | **str** | ID of the legal entity. | 
**legal_entity** | **str** | Name of the legal entity. | 
**property_id** | **str** | ID of the property. | 
**status_id** | **str** | ID of the compliance status. | 
**status** | **str** | Compliance status. | 

## Example

```python
from entrata_api_client.models.get_vendors_success_response_result_vendors_vendor_inner_compliances_compliance_inner import GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_compliances_compliance_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_compliances_compliance_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_compliances_compliance_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_compliances_compliance_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInnerCompliancesComplianceInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_compliances_compliance_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


