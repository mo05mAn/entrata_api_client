# OnNoticeLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**OnNoticeLeaseMethod**](OnNoticeLeaseMethod.md) |  | 

## Example

```python
from openapi_client.models.on_notice_lease import OnNoticeLease

# TODO update the JSON string below
json = "{}"
# create an instance of OnNoticeLease from a JSON string
on_notice_lease_instance = OnNoticeLease.from_json(json)
# print the JSON string representation of the object
print(OnNoticeLease.to_json())

# convert the object into a dict
on_notice_lease_dict = on_notice_lease_instance.to_dict()
# create an instance of OnNoticeLease from a dict
on_notice_lease_from_dict = OnNoticeLease.from_dict(on_notice_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


