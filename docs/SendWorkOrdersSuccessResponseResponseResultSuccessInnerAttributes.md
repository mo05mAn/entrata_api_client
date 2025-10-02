# SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes

Attributes of the success message

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message** | **str** | Message indicating success | [optional] 
**node** | **int** | Node ID where the operation was performed | [optional] 
**reference_id** | **int** | Reference ID associated with the operation | [optional] 

## Example

```python
from entrata_api_client.models.send_work_orders_success_response_response_result_success_inner_attributes import SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes from a JSON string
send_work_orders_success_response_response_result_success_inner_attributes_instance = SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes.to_json())

# convert the object into a dict
send_work_orders_success_response_response_result_success_inner_attributes_dict = send_work_orders_success_response_response_result_success_inner_attributes_instance.to_dict()
# create an instance of SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes from a dict
send_work_orders_success_response_response_result_success_inner_attributes_from_dict = SendWorkOrdersSuccessResponseResponseResultSuccessInnerAttributes.from_dict(send_work_orders_success_response_response_result_success_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


