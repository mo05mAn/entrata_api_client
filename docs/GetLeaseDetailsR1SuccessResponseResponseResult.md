# GetLeaseDetailsR1SuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_id** | **int** | Unique identifier for the lease. | 
**name** | **str** | Name of the resident. | 
**property_unit_id** | **int** | Unique identifier for the property unit. | 
**unit_number** | **str** | Unit number of the leased property. | 
**add_ons** | [**GetLeaseDetailsR1SuccessResponseResponseResultAddOns**](GetLeaseDetailsR1SuccessResponseResponseResultAddOns.md) |  | 
**scheduled_charges** | [**GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result import GetLeaseDetailsR1SuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResult from a JSON string
get_lease_details_r1_success_response_response_result_instance = GetLeaseDetailsR1SuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResult.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_dict = get_lease_details_r1_success_response_response_result_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResult from a dict
get_lease_details_r1_success_response_response_result_from_dict = GetLeaseDetailsR1SuccessResponseResponseResult.from_dict(get_lease_details_r1_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


