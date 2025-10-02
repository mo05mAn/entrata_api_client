# MoveOutLeaseMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property id | 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**move_out_type_id** | **int** | This is a required field. This field accepts single value. moveOutTypeId | 
**move_out_reason_id** | **int** | This is a required field. This field accepts single value. moveOutReasonId | 
**notice_date** | **date** | This is an optional field. This field accepts single value. noticeDate | [optional] 
**move_out_date** | **date** | This is a required field. This field accepts single value. moveOutDate | 
**unit_available_on_date** | **date** | This is a required field. This field accepts single value. unitAvailableOnDate | 
**end_continuing_scheduled_charges** | **int** | This is an optional field. This field accepts single value. endContinuingScheduledCharges | [optional] 
**post_accelerated_rent** | **int** | This is an optional field. This field accepts single value. postAcceleratedRent | [optional] 
**refund_method_id** | **int** |   This is an optional field. This field accepts single value. refundMethodId | [optional] 
**make_ready_end_date** | **date** | This is an optional field. This field accepts single value. According to Property Preference \&quot;Require Make Ready Work Order on Mov e-out,...\&quot; the makeReadyEndDate is conditional mandatory. | [optional] 
**street_line1** | **str** | This is an optional field. This field accepts single value. Forwarding Address street_Line1 | [optional] 
**street_line2** | **str** | This is an optional field. This field accepts single value. Forwarding Address street_Line2 | [optional] 
**street_line3** | **str** | This is an optional field. This field accepts single value. Forwarding Address street_Line3 | [optional] 
**city** | **str** | This is an optional field. This field accepts single value. Forwarding address&#x60;s city | [optional] 
**state_code** | **str** | This is an optional field. This field accepts single value. Forwarding Address&#x60;s stateCode | [optional] 
**postal_code** | **int** | This is an optional field. This field accepts single value. Forwarding Address&#x60;s Postal Code | [optional] 

## Example

```python
from openapi_client.models.move_out_lease_method_params import MoveOutLeaseMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of MoveOutLeaseMethodParams from a JSON string
move_out_lease_method_params_instance = MoveOutLeaseMethodParams.from_json(json)
# print the JSON string representation of the object
print(MoveOutLeaseMethodParams.to_json())

# convert the object into a dict
move_out_lease_method_params_dict = move_out_lease_method_params_instance.to_dict()
# create an instance of MoveOutLeaseMethodParams from a dict
move_out_lease_method_params_from_dict = MoveOutLeaseMethodParams.from_dict(move_out_lease_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


