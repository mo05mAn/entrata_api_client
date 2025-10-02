# GetPurchaseOrdersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**code** | **str** | Success response code. | 
**result** | [**GetPurchaseOrdersSuccessResponseResult**](GetPurchaseOrdersSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_purchase_orders_success_response import GetPurchaseOrdersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersSuccessResponse from a JSON string
get_purchase_orders_success_response_instance = GetPurchaseOrdersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersSuccessResponse.to_json())

# convert the object into a dict
get_purchase_orders_success_response_dict = get_purchase_orders_success_response_instance.to_dict()
# create an instance of GetPurchaseOrdersSuccessResponse from a dict
get_purchase_orders_success_response_from_dict = GetPurchaseOrdersSuccessResponse.from_dict(get_purchase_orders_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


