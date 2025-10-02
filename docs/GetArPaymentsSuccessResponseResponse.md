# GetArPaymentsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request. | [optional] 
**code** | **str** | Success response code | 
**result** | [**GetArPaymentsSuccessResponseResponseResult**](GetArPaymentsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_ar_payments_success_response_response import GetArPaymentsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetArPaymentsSuccessResponseResponse from a JSON string
get_ar_payments_success_response_response_instance = GetArPaymentsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetArPaymentsSuccessResponseResponse.to_json())

# convert the object into a dict
get_ar_payments_success_response_response_dict = get_ar_payments_success_response_response_instance.to_dict()
# create an instance of GetArPaymentsSuccessResponseResponse from a dict
get_ar_payments_success_response_response_from_dict = GetArPaymentsSuccessResponseResponse.from_dict(get_ar_payments_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


