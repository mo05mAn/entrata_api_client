# GetPurchaseOrdersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**vendor_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**vendor_code** | **int** | This is an optional field. This field accepts single value. | [optional] 
**po_number** | **int** | This is an optional field. This field accepts single value. | [optional] 
**po_numbers** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**received_from_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**received_to_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**created_on_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**created_on_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**po_status_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**po_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**purchase_order_approval_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from openapi_client.models.get_purchase_orders_method_params import GetPurchaseOrdersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersMethodParams from a JSON string
get_purchase_orders_method_params_instance = GetPurchaseOrdersMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersMethodParams.to_json())

# convert the object into a dict
get_purchase_orders_method_params_dict = get_purchase_orders_method_params_instance.to_dict()
# create an instance of GetPurchaseOrdersMethodParams from a dict
get_purchase_orders_method_params_from_dict = GetPurchaseOrdersMethodParams.from_dict(get_purchase_orders_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


