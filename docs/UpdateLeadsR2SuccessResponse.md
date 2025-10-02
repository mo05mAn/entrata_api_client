# UpdateLeadsR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response status code. | 
**result** | [**UpdateLeadsR2SuccessResponseResult**](UpdateLeadsR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_leads_r2_success_response import UpdateLeadsR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR2SuccessResponse from a JSON string
update_leads_r2_success_response_instance = UpdateLeadsR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR2SuccessResponse.to_json())

# convert the object into a dict
update_leads_r2_success_response_dict = update_leads_r2_success_response_instance.to_dict()
# create an instance of UpdateLeadsR2SuccessResponse from a dict
update_leads_r2_success_response_from_dict = UpdateLeadsR2SuccessResponse.from_dict(update_leads_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


