# UpdateAmenitiesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**UpdateAmenitiesSuccessResponseResponseResult**](UpdateAmenitiesSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_amenities_success_response_response import UpdateAmenitiesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateAmenitiesSuccessResponseResponse from a JSON string
update_amenities_success_response_response_instance = UpdateAmenitiesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateAmenitiesSuccessResponseResponse.to_json())

# convert the object into a dict
update_amenities_success_response_response_dict = update_amenities_success_response_response_instance.to_dict()
# create an instance of UpdateAmenitiesSuccessResponseResponse from a dict
update_amenities_success_response_response_from_dict = UpdateAmenitiesSuccessResponseResponse.from_dict(update_amenities_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


