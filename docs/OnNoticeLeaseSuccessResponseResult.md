# OnNoticeLeaseSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the lease notice placement | 
**message** | **str** | Message regarding the lease notice placement | 

## Example

```python
from openapi_client.models.on_notice_lease_success_response_result import OnNoticeLeaseSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of OnNoticeLeaseSuccessResponseResult from a JSON string
on_notice_lease_success_response_result_instance = OnNoticeLeaseSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(OnNoticeLeaseSuccessResponseResult.to_json())

# convert the object into a dict
on_notice_lease_success_response_result_dict = on_notice_lease_success_response_result_instance.to_dict()
# create an instance of OnNoticeLeaseSuccessResponseResult from a dict
on_notice_lease_success_response_result_from_dict = OnNoticeLeaseSuccessResponseResult.from_dict(on_notice_lease_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


