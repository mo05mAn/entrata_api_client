# GetLeaseActivitiesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **int** | Success response code | 
**result** | [**GetLeaseActivitiesSuccessResponseResponseResult**](GetLeaseActivitiesSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_activities_success_response_response import GetLeaseActivitiesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivitiesSuccessResponseResponse from a JSON string
get_lease_activities_success_response_response_instance = GetLeaseActivitiesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivitiesSuccessResponseResponse.to_json())

# convert the object into a dict
get_lease_activities_success_response_response_dict = get_lease_activities_success_response_response_instance.to_dict()
# create an instance of GetLeaseActivitiesSuccessResponseResponse from a dict
get_lease_activities_success_response_response_from_dict = GetLeaseActivitiesSuccessResponseResponse.from_dict(get_lease_activities_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


