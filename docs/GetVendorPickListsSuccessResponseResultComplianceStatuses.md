# GetVendorPickListsSuccessResponseResultComplianceStatuses


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**compliance_status** | [**List[GetVendorPickListsSuccessResponseResultComplianceStatusesComplianceStatusInner]**](GetVendorPickListsSuccessResponseResultComplianceStatusesComplianceStatusInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendor_pick_lists_success_response_result_compliance_statuses import GetVendorPickListsSuccessResponseResultComplianceStatuses

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickListsSuccessResponseResultComplianceStatuses from a JSON string
get_vendor_pick_lists_success_response_result_compliance_statuses_instance = GetVendorPickListsSuccessResponseResultComplianceStatuses.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickListsSuccessResponseResultComplianceStatuses.to_json())

# convert the object into a dict
get_vendor_pick_lists_success_response_result_compliance_statuses_dict = get_vendor_pick_lists_success_response_result_compliance_statuses_instance.to_dict()
# create an instance of GetVendorPickListsSuccessResponseResultComplianceStatuses from a dict
get_vendor_pick_lists_success_response_result_compliance_statuses_from_dict = GetVendorPickListsSuccessResponseResultComplianceStatuses.from_dict(get_vendor_pick_lists_success_response_result_compliance_statuses_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


