# SendWorkOrdersSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **int** | Successful response code. | 
**result** | [**SendWorkOrdersSuccessResponseResponseResult**](SendWorkOrdersSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_work_orders_success_response_response import SendWorkOrdersSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrdersSuccessResponseResponse from a JSON string
send_work_orders_success_response_response_instance = SendWorkOrdersSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrdersSuccessResponseResponse.to_json())

# convert the object into a dict
send_work_orders_success_response_response_dict = send_work_orders_success_response_response_instance.to_dict()
# create an instance of SendWorkOrdersSuccessResponseResponse from a dict
send_work_orders_success_response_response_from_dict = SendWorkOrdersSuccessResponseResponse.from_dict(send_work_orders_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


