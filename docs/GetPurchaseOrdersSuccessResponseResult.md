# GetPurchaseOrdersSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**purchase_orders** | [**GetPurchaseOrdersSuccessResponseResultPurchaseOrders**](GetPurchaseOrdersSuccessResponseResultPurchaseOrders.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_purchase_orders_success_response_result import GetPurchaseOrdersSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersSuccessResponseResult from a JSON string
get_purchase_orders_success_response_result_instance = GetPurchaseOrdersSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersSuccessResponseResult.to_json())

# convert the object into a dict
get_purchase_orders_success_response_result_dict = get_purchase_orders_success_response_result_instance.to_dict()
# create an instance of GetPurchaseOrdersSuccessResponseResult from a dict
get_purchase_orders_success_response_result_from_dict = GetPurchaseOrdersSuccessResponseResult.from_dict(get_purchase_orders_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


