# GetVendorsSuccessResponseResultVendorsVendorInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the vendor. | 
**vendor_name** | **str** | Name of the vendor. | 
**vendor_type_id** | **str** | Unique identifier for the vendor type. | 
**vendor_type** | **str** | Name of the vendor type. | 
**status_type_id** | **str** | Unique identifier for the status type. | 
**status** | **str** | Status of the vendor. | 
**term_id** | **str** | Unique identifier for the term. | 
**term** | **str** | Payment term for the vendor. | 
**is_consolidated** | **str** | Indicates if the vendor is consolidated. | 
**external_id** | **str** | External identifier for the vendor. | 
**is_on_site** | **str** | Indicates if the vendor is on site. | 
**vendor_category_type_id** | **str** | Unique identifier for the vendor category. | 
**vendor_category_type** | **str** | Name of the vendor category. | 
**website** | **str** | Website URL of the vendor. | 
**notes** | **str** | Notes associated with the vendor. | [optional] 
**legal_entities** | [**GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntities**](GetVendorsSuccessResponseResultVendorsVendorInnerLegalEntities.md) |  | 
**ap_remittances** | [**GetVendorsSuccessResponseResultVendorsVendorInnerApRemittances**](GetVendorsSuccessResponseResultVendorsVendorInnerApRemittances.md) |  | 
**contacts** | [**GetVendorsSuccessResponseResultVendorsVendorInnerContacts**](GetVendorsSuccessResponseResultVendorsVendorInnerContacts.md) |  | 
**locations** | [**GetVendorsSuccessResponseResultVendorsVendorInnerLocations**](GetVendorsSuccessResponseResultVendorsVendorInnerLocations.md) |  | 
**compliances** | [**GetVendorsSuccessResponseResultVendorsVendorInnerCompliances**](GetVendorsSuccessResponseResultVendorsVendorInnerCompliances.md) |  | 
**accounts** | [**GetVendorsSuccessResponseResultVendorsVendorInnerAccounts**](GetVendorsSuccessResponseResultVendorsVendorInnerAccounts.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendors_success_response_result_vendors_vendor_inner import GetVendorsSuccessResponseResultVendorsVendorInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


