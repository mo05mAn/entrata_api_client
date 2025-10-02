# GetSpecialsR1SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | The unique ID for the request. | 
**result** | [**GetSpecialsR1SuccessResponseResponseResult**](GetSpecialsR1SuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_specials_r1_success_response_response import GetSpecialsR1SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR1SuccessResponseResponse from a JSON string
get_specials_r1_success_response_response_instance = GetSpecialsR1SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR1SuccessResponseResponse.to_json())

# convert the object into a dict
get_specials_r1_success_response_response_dict = get_specials_r1_success_response_response_instance.to_dict()
# create an instance of GetSpecialsR1SuccessResponseResponse from a dict
get_specials_r1_success_response_response_from_dict = GetSpecialsR1SuccessResponseResponse.from_dict(get_specials_r1_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


