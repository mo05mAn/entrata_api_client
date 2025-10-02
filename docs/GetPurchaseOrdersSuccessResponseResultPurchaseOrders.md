# GetPurchaseOrdersSuccessResponseResultPurchaseOrders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**purchase_order** | [**List[GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner]**](GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_purchase_orders_success_response_result_purchase_orders import GetPurchaseOrdersSuccessResponseResultPurchaseOrders

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersSuccessResponseResultPurchaseOrders from a JSON string
get_purchase_orders_success_response_result_purchase_orders_instance = GetPurchaseOrdersSuccessResponseResultPurchaseOrders.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersSuccessResponseResultPurchaseOrders.to_json())

# convert the object into a dict
get_purchase_orders_success_response_result_purchase_orders_dict = get_purchase_orders_success_response_result_purchase_orders_instance.to_dict()
# create an instance of GetPurchaseOrdersSuccessResponseResultPurchaseOrders from a dict
get_purchase_orders_success_response_result_purchase_orders_from_dict = GetPurchaseOrdersSuccessResponseResultPurchaseOrders.from_dict(get_purchase_orders_success_response_result_purchase_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


