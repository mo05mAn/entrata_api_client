# GetAmenitiesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amenities** | [**GetAmenitiesSuccessResponseResultAmenities**](GetAmenitiesSuccessResponseResultAmenities.md) |  | 

## Example

```python
from entrata_api_client.models.get_amenities_success_response_result import GetAmenitiesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResult from a JSON string
get_amenities_success_response_result_instance = GetAmenitiesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResult.to_json())

# convert the object into a dict
get_amenities_success_response_result_dict = get_amenities_success_response_result_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResult from a dict
get_amenities_success_response_result_from_dict = GetAmenitiesSuccessResponseResult.from_dict(get_amenities_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


