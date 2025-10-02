# GetPurchaseOrdersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPurchaseOrdersMethodParams**](GetPurchaseOrdersMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_purchase_orders_method import GetPurchaseOrdersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersMethod from a JSON string
get_purchase_orders_method_instance = GetPurchaseOrdersMethod.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersMethod.to_json())

# convert the object into a dict
get_purchase_orders_method_dict = get_purchase_orders_method_instance.to_dict()
# create an instance of GetPurchaseOrdersMethod from a dict
get_purchase_orders_method_from_dict = GetPurchaseOrdersMethod.from_dict(get_purchase_orders_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


