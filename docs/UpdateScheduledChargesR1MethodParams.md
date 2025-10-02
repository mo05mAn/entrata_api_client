# UpdateScheduledChargesR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | This is a required field. This field accepts single value. scheduledChargeid | 
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**amount** | **int** | This is a required field. This field accepts single value. amount | [optional] 
**is_deleted** | **int** | This is an optional field. This field accepts single value. This field support value 0 and 1. | [optional] 

## Example

```python
from openapi_client.models.update_scheduled_charges_r1_method_params import UpdateScheduledChargesR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScheduledChargesR1MethodParams from a JSON string
update_scheduled_charges_r1_method_params_instance = UpdateScheduledChargesR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateScheduledChargesR1MethodParams.to_json())

# convert the object into a dict
update_scheduled_charges_r1_method_params_dict = update_scheduled_charges_r1_method_params_instance.to_dict()
# create an instance of UpdateScheduledChargesR1MethodParams from a dict
update_scheduled_charges_r1_method_params_from_dict = UpdateScheduledChargesR1MethodParams.from_dict(update_scheduled_charges_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


