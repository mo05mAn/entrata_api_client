# UpdateWorkOrdersR1SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**UpdateWorkOrdersR1SuccessResponseResponseResult**](UpdateWorkOrdersR1SuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_work_orders_r1_success_response_response import UpdateWorkOrdersR1SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR1SuccessResponseResponse from a JSON string
update_work_orders_r1_success_response_response_instance = UpdateWorkOrdersR1SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR1SuccessResponseResponse.to_json())

# convert the object into a dict
update_work_orders_r1_success_response_response_dict = update_work_orders_r1_success_response_response_instance.to_dict()
# create an instance of UpdateWorkOrdersR1SuccessResponseResponse from a dict
update_work_orders_r1_success_response_response_from_dict = UpdateWorkOrdersR1SuccessResponseResponse.from_dict(update_work_orders_r1_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


