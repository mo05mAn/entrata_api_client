# SendPurchaseOrdersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**po_type_id** | **int** | This is a required field. This field accepts single value. Supports purchase order types 4 and 19 (\&quot;Standard\&quot; and \&quot;Standard-Job/ Contract\&quot; respectively). | 
**ap_payee_id** | **int** | This is a required field. This field accepts single value. Supports purchase order types 4 and 19 (\&quot;Standard\&quot; and \&quot;Standard-Job/ Contract\&quot; respectively). | 
**ap_payee_location_id** | **int** | This is a required field. This field accepts single value. Child element of apHeader. Location Id of a vendor. | 
**ap_payee_account_id** | **int** | This is an optional field. This field accepts single value. Child element of apHeader. If not passed in the request, the system d efault account will be used. | [optional] 
**post_month** | **date** | This is a required field. This field accepts single value. Accepts date in MM/YYYY format. | 
**post_date** | **date** | This is a required field. This field accepts single value. Child element of apHeader. | 
**routing_tag_id** | **int** | This is an optional field. This field accepts single value. Child element of apHeader. | [optional] 
**header_memo** | **str** | This is an optional field. This field accepts single value. Child element of apHeader. | [optional] 
**shipping** | **int** | This is an optional field. This field accepts single value. This will specify the shipping amount. | [optional] 
**discount** | **int** | This is an optional field. This field accepts single value. This will specify the discount amount. | [optional] 
**sales_tax** | **int** | This is an optional field. This field accepts single value. This will specify the sales tax of the invoice. | [optional] 
**gl_account_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail.This is required if po type is standard. | [optional] 
**ap_code_id** | **int** | This is an optional field. This field accepts single value. This is child element of apDetails. This is required if po type is job costing. | [optional] 
**job_phase_id** | **int** | This is an optional field. This field accepts single value. This is child element of apDetails. This is required if po type is job costing. | [optional] 
**ap_contract_id** | **int** | This is an optional field. This field accepts single value. This is child element of apDetails. | [optional] 
**property_id** | **int** | This is a required field. This field accepts single value. Child element of apDetail. | 
**quantity** | **int** | This is a required field. This field accepts single value. Child element of apDetail. | 
**rate** | **int** | This is a required field. This field accepts single value. Child element of apDetail. | 
**gl_dimension_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. Custom Tags. | [optional] 
**company_department_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. | [optional] 
**property_unit_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. | [optional] 
**property_building_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. | [optional] 
**is_confidential** | **int** | This is an optional field. This field accepts single value. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**is_taxable** | **int** | This is an optional field. This field accepts single value. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**description** | **str** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.send_purchase_orders_method_params import SendPurchaseOrdersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrdersMethodParams from a JSON string
send_purchase_orders_method_params_instance = SendPurchaseOrdersMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrdersMethodParams.to_json())

# convert the object into a dict
send_purchase_orders_method_params_dict = send_purchase_orders_method_params_instance.to_dict()
# create an instance of SendPurchaseOrdersMethodParams from a dict
send_purchase_orders_method_params_from_dict = SendPurchaseOrdersMethodParams.from_dict(send_purchase_orders_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


