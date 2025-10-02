# OnNoticeLeaseMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property id | 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**move_out_type_id** | **int** | This is a required field. This field accepts single value. moveOutTypeId | 
**move_out_reason_id** | **int** | This is a required field. This field accepts single value. moveOutReasonId | 
**notice_date** | **date** | This is a required field. This field accepts single value. noticeDate (YYYY-MM-DD) | [optional] 
**move_out_date** | **date** | This is a required field. This field accepts single value. moveOutDate (YYYY-MM-DD) | 
**unit_available_on_date** | **date** | This is a required field. This field accepts single value. unitAvailableOnDate (YYYY-MM-DD) | 
**make_ready_end_date** | **date** | This is a required field. This field accepts single value. According to Property Preference \&quot;Require Make Ready Work Order on Mov e-out,...\&quot; the makeReadyEndDate is conditional mandatory. | 
**submit_refund_details** | **int** | This is a required field. This field accepts single value. submitRefundDetails | 
**refund_method_id** | **int** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;refundMet hodId\&quot; is required. | [optional] 
**street_line1** | **str** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;streetLie 1\&quot; is required. | [optional] 
**street_line2** | **str** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;streetLie 2\&quot; is required. | [optional] 
**street_line3** | **str** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;streetLie 3\&quot; is required. | [optional] 
**city** | **str** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;city\&quot; is required. | [optional] 
**state_code** | **str** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;stateCode\&quot; is required. | [optional] 
**postal_code** | **int** | This is an optional field. This field accepts single value. If the value of \&quot;submitRefundDetails\&quot; is \&quot;1\&quot;, only then the \&quot;postalCod \&quot; is required. | [optional] 

## Example

```python
from entrata_api_client.models.on_notice_lease_method_params import OnNoticeLeaseMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of OnNoticeLeaseMethodParams from a JSON string
on_notice_lease_method_params_instance = OnNoticeLeaseMethodParams.from_json(json)
# print the JSON string representation of the object
print(OnNoticeLeaseMethodParams.to_json())

# convert the object into a dict
on_notice_lease_method_params_dict = on_notice_lease_method_params_instance.to_dict()
# create an instance of OnNoticeLeaseMethodParams from a dict
on_notice_lease_method_params_from_dict = OnNoticeLeaseMethodParams.from_dict(on_notice_lease_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


