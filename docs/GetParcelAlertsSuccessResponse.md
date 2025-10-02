# GetParcelAlertsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetParcelAlertsSuccessResponseResponse**](GetParcelAlertsSuccessResponseResponse.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_parcel_alerts_success_response import GetParcelAlertsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlertsSuccessResponse from a JSON string
get_parcel_alerts_success_response_instance = GetParcelAlertsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlertsSuccessResponse.to_json())

# convert the object into a dict
get_parcel_alerts_success_response_dict = get_parcel_alerts_success_response_instance.to_dict()
# create an instance of GetParcelAlertsSuccessResponse from a dict
get_parcel_alerts_success_response_from_dict = GetParcelAlertsSuccessResponse.from_dict(get_parcel_alerts_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


