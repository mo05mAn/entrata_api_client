# SendScheduledChargesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**charge_timing_id** | **int** | This is a required field. This field accepts single value. chargeTimingId | 
**charge_code_type_id** | **int** | This is a required field. This field accepts single value. chargeCodeTypeId | 
**charge_code_id** | **int** | This is a required field. This field accepts single value. chargeCodeId | 
**amount** | **int** | This is a required field. This field accepts single value. amount | 
**start_date** | **date** | This is a required field. This field accepts single value. startDate | 
**lease_interval_id** | **int** | This is an optional field. This field accepts single value. leaseIntervalId | [optional] 

## Example

```python
from openapi_client.models.send_scheduled_charges_method_params import SendScheduledChargesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendScheduledChargesMethodParams from a JSON string
send_scheduled_charges_method_params_instance = SendScheduledChargesMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendScheduledChargesMethodParams.to_json())

# convert the object into a dict
send_scheduled_charges_method_params_dict = send_scheduled_charges_method_params_instance.to_dict()
# create an instance of SendScheduledChargesMethodParams from a dict
send_scheduled_charges_method_params_from_dict = SendScheduledChargesMethodParams.from_dict(send_scheduled_charges_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


