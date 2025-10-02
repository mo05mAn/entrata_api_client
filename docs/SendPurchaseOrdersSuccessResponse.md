# SendPurchaseOrdersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**SendPurchaseOrdersSuccessResponseResult**](SendPurchaseOrdersSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_purchase_orders_success_response import SendPurchaseOrdersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrdersSuccessResponse from a JSON string
send_purchase_orders_success_response_instance = SendPurchaseOrdersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrdersSuccessResponse.to_json())

# convert the object into a dict
send_purchase_orders_success_response_dict = send_purchase_orders_success_response_instance.to_dict()
# create an instance of SendPurchaseOrdersSuccessResponse from a dict
send_purchase_orders_success_response_from_dict = SendPurchaseOrdersSuccessResponse.from_dict(send_purchase_orders_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


