# GetParcelAlertsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**GetParcelAlertsSuccessResponseResponseResult**](GetParcelAlertsSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_parcel_alerts_success_response_response import GetParcelAlertsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlertsSuccessResponseResponse from a JSON string
get_parcel_alerts_success_response_response_instance = GetParcelAlertsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlertsSuccessResponseResponse.to_json())

# convert the object into a dict
get_parcel_alerts_success_response_response_dict = get_parcel_alerts_success_response_response_instance.to_dict()
# create an instance of GetParcelAlertsSuccessResponseResponse from a dict
get_parcel_alerts_success_response_response_from_dict = GetParcelAlertsSuccessResponseResponse.from_dict(get_parcel_alerts_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


