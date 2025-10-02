# GetVendorPickListsSuccessResponseResultApPayeeStatusTypes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_payee_status_type** | [**List[GetVendorPickListsSuccessResponseResultApPayeeStatusTypesApPayeeStatusTypeInner]**](GetVendorPickListsSuccessResponseResultApPayeeStatusTypesApPayeeStatusTypeInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendor_pick_lists_success_response_result_ap_payee_status_types import GetVendorPickListsSuccessResponseResultApPayeeStatusTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickListsSuccessResponseResultApPayeeStatusTypes from a JSON string
get_vendor_pick_lists_success_response_result_ap_payee_status_types_instance = GetVendorPickListsSuccessResponseResultApPayeeStatusTypes.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickListsSuccessResponseResultApPayeeStatusTypes.to_json())

# convert the object into a dict
get_vendor_pick_lists_success_response_result_ap_payee_status_types_dict = get_vendor_pick_lists_success_response_result_ap_payee_status_types_instance.to_dict()
# create an instance of GetVendorPickListsSuccessResponseResultApPayeeStatusTypes from a dict
get_vendor_pick_lists_success_response_result_ap_payee_status_types_from_dict = GetVendorPickListsSuccessResponseResultApPayeeStatusTypes.from_dict(get_vendor_pick_lists_success_response_result_ap_payee_status_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


