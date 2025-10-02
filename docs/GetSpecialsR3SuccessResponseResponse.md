# GetSpecialsR3SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **int** | Successful response code. | 
**result** | [**GetSpecialsR3SuccessResponseResponseResult**](GetSpecialsR3SuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r3_success_response_response import GetSpecialsR3SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR3SuccessResponseResponse from a JSON string
get_specials_r3_success_response_response_instance = GetSpecialsR3SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR3SuccessResponseResponse.to_json())

# convert the object into a dict
get_specials_r3_success_response_response_dict = get_specials_r3_success_response_response_instance.to_dict()
# create an instance of GetSpecialsR3SuccessResponseResponse from a dict
get_specials_r3_success_response_response_from_dict = GetSpecialsR3SuccessResponseResponse.from_dict(get_specials_r3_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


