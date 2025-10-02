# SendWorkOrdersSuccessResponseResponseResult

Result object containing the success details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | [**List[SendWorkOrdersSuccessResponseResponseResultSuccessInner]**](SendWorkOrdersSuccessResponseResponseResultSuccessInner.md) | List of success messages | [optional] 

## Example

```python
from entrata_api_client.models.send_work_orders_success_response_response_result import SendWorkOrdersSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrdersSuccessResponseResponseResult from a JSON string
send_work_orders_success_response_response_result_instance = SendWorkOrdersSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrdersSuccessResponseResponseResult.to_json())

# convert the object into a dict
send_work_orders_success_response_response_result_dict = send_work_orders_success_response_response_result_instance.to_dict()
# create an instance of SendWorkOrdersSuccessResponseResponseResult from a dict
send_work_orders_success_response_response_result_from_dict = SendWorkOrdersSuccessResponseResponseResult.from_dict(send_work_orders_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


