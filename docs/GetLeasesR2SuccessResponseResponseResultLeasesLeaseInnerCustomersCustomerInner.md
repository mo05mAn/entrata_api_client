# GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Customer ID | 
**customer_type** | **str** | Type of the customer | 
**first_name** | **str** | First name of the customer | 
**last_name** | **str** | Last name of the customer | 
**name_full** | **str** | Full name of the customer | 
**email_address** | **str** | Email address of the customer | 
**lease_customer_status** | **str** | Status of the customer&#39;s lease | 
**move_in_date** | **str** | Move-in date for the customer | 
**move_out_date** | **str** | Move-out date for the customer | 
**phones** | [**GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInnerPhones**](GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInnerPhones.md) |  | 
**is_active_bankruptcy** | **bool** | The Bankruptcy status of customer . | [optional] 
**bankruptcy_date** | **str** | The Bankruptcy date of customer. | [optional] 
**bankruptcy_note** | **str** | XYZ | [optional] 

## Example

```python
from entrata_api_client.models.get_leases_r2_success_response_response_result_leases_lease_inner_customers_customer_inner import GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner from a JSON string
get_leases_r2_success_response_response_result_leases_lease_inner_customers_customer_inner_instance = GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner.to_json())

# convert the object into a dict
get_leases_r2_success_response_response_result_leases_lease_inner_customers_customer_inner_dict = get_leases_r2_success_response_response_result_leases_lease_inner_customers_customer_inner_instance.to_dict()
# create an instance of GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner from a dict
get_leases_r2_success_response_response_result_leases_lease_inner_customers_customer_inner_from_dict = GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomersCustomerInner.from_dict(get_leases_r2_success_response_response_result_leases_lease_inner_customers_customer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


