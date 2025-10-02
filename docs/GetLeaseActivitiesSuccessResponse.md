# GetLeaseActivitiesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetLeaseActivitiesSuccessResponseResponse**](GetLeaseActivitiesSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_activities_success_response import GetLeaseActivitiesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivitiesSuccessResponse from a JSON string
get_lease_activities_success_response_instance = GetLeaseActivitiesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivitiesSuccessResponse.to_json())

# convert the object into a dict
get_lease_activities_success_response_dict = get_lease_activities_success_response_instance.to_dict()
# create an instance of GetLeaseActivitiesSuccessResponse from a dict
get_lease_activities_success_response_from_dict = GetLeaseActivitiesSuccessResponse.from_dict(get_lease_activities_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


