# OnNoticeLeaseSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**OnNoticeLeaseSuccessResponseResult**](OnNoticeLeaseSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.on_notice_lease_success_response import OnNoticeLeaseSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of OnNoticeLeaseSuccessResponse from a JSON string
on_notice_lease_success_response_instance = OnNoticeLeaseSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(OnNoticeLeaseSuccessResponse.to_json())

# convert the object into a dict
on_notice_lease_success_response_dict = on_notice_lease_success_response_instance.to_dict()
# create an instance of OnNoticeLeaseSuccessResponse from a dict
on_notice_lease_success_response_from_dict = OnNoticeLeaseSuccessResponse.from_dict(on_notice_lease_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


