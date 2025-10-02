# GetArPaymentsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetArPaymentsSuccessResponseResponse**](GetArPaymentsSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.get_ar_payments_success_response import GetArPaymentsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetArPaymentsSuccessResponse from a JSON string
get_ar_payments_success_response_instance = GetArPaymentsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetArPaymentsSuccessResponse.to_json())

# convert the object into a dict
get_ar_payments_success_response_dict = get_ar_payments_success_response_instance.to_dict()
# create an instance of GetArPaymentsSuccessResponse from a dict
get_ar_payments_success_response_from_dict = GetArPaymentsSuccessResponse.from_dict(get_ar_payments_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


