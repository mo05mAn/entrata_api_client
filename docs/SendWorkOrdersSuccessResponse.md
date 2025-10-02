# SendWorkOrdersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**SendWorkOrdersSuccessResponseResponse**](SendWorkOrdersSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.send_work_orders_success_response import SendWorkOrdersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrdersSuccessResponse from a JSON string
send_work_orders_success_response_instance = SendWorkOrdersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrdersSuccessResponse.to_json())

# convert the object into a dict
send_work_orders_success_response_dict = send_work_orders_success_response_instance.to_dict()
# create an instance of SendWorkOrdersSuccessResponse from a dict
send_work_orders_success_response_from_dict = SendWorkOrdersSuccessResponse.from_dict(send_work_orders_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


