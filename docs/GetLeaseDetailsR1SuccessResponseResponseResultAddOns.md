# GetLeaseDetailsR1SuccessResponseResponseResultAddOns


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assignable_items** | [**GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItems**](GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItems.md) |  | 
**rentable_items** | [**GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItems**](GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItems.md) |  | 
**services** | [**GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServices**](GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServices.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result_add_ons import GetLeaseDetailsR1SuccessResponseResponseResultAddOns

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOns from a JSON string
get_lease_details_r1_success_response_response_result_add_ons_instance = GetLeaseDetailsR1SuccessResponseResponseResultAddOns.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultAddOns.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_add_ons_dict = get_lease_details_r1_success_response_response_result_add_ons_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOns from a dict
get_lease_details_r1_success_response_response_result_add_ons_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultAddOns.from_dict(get_lease_details_r1_success_response_response_result_add_ons_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


