# GetLeaseDetailsR1SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **int** | Successful response code. | 
**result** | [**GetLeaseDetailsR1SuccessResponseResponseResult**](GetLeaseDetailsR1SuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_lease_details_r1_success_response_response import GetLeaseDetailsR1SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponse from a JSON string
get_lease_details_r1_success_response_response_instance = GetLeaseDetailsR1SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponse.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_dict = get_lease_details_r1_success_response_response_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponse from a dict
get_lease_details_r1_success_response_response_from_dict = GetLeaseDetailsR1SuccessResponseResponse.from_dict(get_lease_details_r1_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


