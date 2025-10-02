# SendInvoicesR2MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invoice_type_id** | **int** | This is an optional field. This field accepts single value. Supports 1&#x3D;\&quot;Standard\&quot;, 8 &#x3D; \&quot;Catalog\&quot; and 17 &#x3D; \&quot;Standard-Job/Contract\&quot; types. By default type \&quot;Standard\&quot; is inserted. | [optional] 
**ap_payee_id** | **int** | This is a required field. This field accepts single value. Child element of apHeader. Id of a vendor who generated the invoice. | 
**ap_payee_location_id** | **int** | This is a required field. This field accepts single value. Child element of apHeader. Location Id of a vendor who generated the invoice. | 
**routing_tag_id** | **int** | This is an optional field. This field accepts single value. Child element of apHeader. This is conditionally required, depends upo n the \&quot;Require Routing Tags on Invoices\&quot; setting. | [optional] 
**invoice_number** | **str** | This is a required field. This field accepts single value. Child element of apHeader. Invoice Number. | 
**post_month** | **date** | This is an optional field. This field accepts single value. Accepts date in MM/YYYY format. | [optional] 
**invoice_date** | **date** | This is a required field. This field accepts single value. Child element of apHeader. Invoice date. Must be of format MM/DD/YYYY. | 
**due_date** | **date** | This is an optional field. This field accepts single value. Accepts date in MM/DD/YYYY format. | [optional] 
**shipping** | **int** | This is an optional field. This field accepts single value. This will specify the shipping amount. | [optional] 
**discount** | **int** | This is an optional field. This field accepts single value. This will specify the discount amount. | [optional] 
**sales_tax** | **int** | This is an optional field. This field accepts single value. This will specify the sales tax of the invoice. | [optional] 
**invoice_total** | **int** | This is a required field. This field accepts single value. Child element of apHeader. Total amount of invoice. | 
**note** | **str** |   This is an optional field. This field accepts single value. This field will be used to specify the additional details of the invoice. | [optional] 
**invoice_image_url** | **str** | This is an optional field. This field accepts single value. If this node is provided, it should be a valid URL. | [optional] 
**is_consolidated** | **int** | This is an optional field. This field accepts single value. Child element of apHeader. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**is_on_hold** | **int** | This is an optional field. This field accepts single value. Child element of apHeader. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**property_id** | **int** |   This is a required field. This field accepts single value. Child element of apDetail. | 
**gl_account_id** | **int** | This is a required field. This field accepts single value. Child element of apDetail. | 
**property_building_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. | [optional] 
**property_unit_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. | [optional] 
**description** | **str** | This is a required field. This field accepts single value. Child element of apDetail. | 
**quantity** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. | [optional] 
**rate** | **int** | This is a required field. This field accepts single value. Child element of apDetail. | 
**unit_of_measure_id** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. Only valid for Catalog type invoices. | [optional] 
**is_waive1099** | **int** | This is an optional field. This field accepts single value. Child element of apDetail. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**po_detail_id** | **int** | This is an optional field. This field accepts single value. This node accepts \&quot;Line Item Id\&quot; of Purchase Order. | [optional] 
**receiving_record_id** | **int** | This is an optional field. This field accepts single value. Conditional Required(Node is mandatory only if the poDetailId value is provided in request). This node accepts \&quot;Receiving Record Id\&quot; of Purc hase Order Line Item for the \&quot;Catalog\&quot; type. | [optional] 
**invoice_payment_id** | **str** | This is an optional field. This field accepts single value. Child element of invoicePayment. | [optional] 
**payment_amount** | **int** | This is an optional field. This field accepts single value. Child element of invoicePayment under apDetail. | [optional] 
**file_data** | **str** | This is an optional field. This field accepts single value. Child element of file. Base64 encoded file data. | [optional] 
**is_paused** | **int** | This is an optional field. This field accepts single value. Child element of apBatch. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**is_posted** | **int** | This is an optional field. This field accepts single value. This node specifies whether the invoice is posted or unposted. Accepts \&quot;0\&quot; or \&quot;1\&quot; Only. | [optional] 
**payment_type_id** | **int** | This is an optional field. This field accepts single value. Child element of invoicePayment. | [optional] 
**payment_number** | **str** | This is an optional field. This field accepts single value. Child element of invoicePayment under invoicePayments. | [optional] 
**payment_date** | **date** | This is an optional field. This field accepts single value. Child element of invoicePayment under invoicePayments. Must be of for mat MM/DD/YYYY. | [optional] 
**payment_memo** | **str** | This is an optional field. This field accepts single value. Child element of invoicePayment under invoicePayments. | [optional] 
**custom_tag_id** | **int** | This is an optional field. This field accepts single value. This node accepts custom Tag Id of the invoice. If customTagId is not provided, then PO&#x60;s custom Tag Id would gets associates to invoice thr ough poDetailId node | [optional] 
**ap_code_id** | **int** | This is a required field. This field accepts single value. The required node in case of jobCost invoiceType | 
**ap_contract_id** | **int** | This is a required field. This field accepts single value. The required node in case of jobCost invoiceType | 

## Example

```python
from entrata_api_client.models.send_invoices_r2_method_params import SendInvoicesR2MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR2MethodParams from a JSON string
send_invoices_r2_method_params_instance = SendInvoicesR2MethodParams.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR2MethodParams.to_json())

# convert the object into a dict
send_invoices_r2_method_params_dict = send_invoices_r2_method_params_instance.to_dict()
# create an instance of SendInvoicesR2MethodParams from a dict
send_invoices_r2_method_params_from_dict = SendInvoicesR2MethodParams.from_dict(send_invoices_r2_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


