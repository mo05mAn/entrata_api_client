# GetLeasesR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**application_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**customer_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**lease_status_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**lease_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**event_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**scheduled_ar_code_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**unit_number** | **str** | This is an optional field. This field accepts single value. | [optional] 
**building_name** | **str** | This is an optional field. This field accepts single value. | [optional] 
**move_in_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**move_in_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**event_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**event_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**lease_expiring_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**lease_expiring_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**move_out_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**move_out_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**include_other_income_leases** | **int** | This is an optional field. This field accepts single value. | [optional] 
**resident_friendly_mode** | **int** | This is an optional field. This field accepts single value. | [optional] 
**include_lease_history** | **int** | This is an optional field. This field accepts single value. | [optional] 
**include_ar_transactions** | **int** | This is an optional field. This field accepts single value. This should return the Ar Transactions associated with the lease. | [optional] 

## Example

```python
from entrata_api_client.models.get_leases_r1_method_params import GetLeasesR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1MethodParams from a JSON string
get_leases_r1_method_params_instance = GetLeasesR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1MethodParams.to_json())

# convert the object into a dict
get_leases_r1_method_params_dict = get_leases_r1_method_params_instance.to_dict()
# create an instance of GetLeasesR1MethodParams from a dict
get_leases_r1_method_params_from_dict = GetLeasesR1MethodParams.from_dict(get_leases_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


