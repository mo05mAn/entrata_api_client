# SendInvoicesR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_payee_id** | **int** | This is a required field. This field accepts single value. Child element of ApHeader. Id of a vendor who generated the invoice. | 
**ap_payee_location_id** | **int** | This is a required field. This field accepts single value. Child element of ApHeader. Location Id of a vendor who generated the invoice. | 
**invoice_total** | **int** | This is a required field. This field accepts single value. Child element of ApHeader. Total amount of invoice. | 
**invoice_number** | **str** | This is a required field. This field accepts single value. Child element of ApHeader. Invoice Number. | [optional] 
**invoice_date** | **date** | This is a required field. This field accepts single value. Child element of ApHeader. Invoice date. Must be of format MM/DD/YYYY. | 
**is_consolidated** | **int** | This is an optional field. This field accepts single value. Child element of ApHeader. | [optional] 
**is_on_hold** | **int** | This is an optional field. This field accepts single value. Child element of ApHeader. | [optional] 
**property_id** | **int** | This is a required field. This field accepts single value. Child element of ApDetail. | 
**gl_account_id** | **int** | This is a required field. This field accepts single value. Child element of ApDetail. | 
**description** | **str** | This is a required field. This field accepts single value. Child element of ApDetail. | 
**quantity** | **int** | This is an optional field. This field accepts single value. Child element of ApDetail. | [optional] 
**rate** | **int** | This is a required field. This field accepts single value. Child element of ApDetail. | 
**is_waive1099** | **int** | This is an optional field. This field accepts single value. Child element of ApDetail. | [optional] 
**file_data** | **str** | This is an optional field. This field accepts single value. Child element of File. Base64 encoded file data. | [optional] 
**note** | **str** | This is an optional field. This field accepts single value. | [optional] 
**due_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**end_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**is_paused** | **int** | This is an optional field. This field accepts single value. Child element of ApBatch. | [optional] 
**invoice_image_url** | **str** | This is an optional field. This field accepts single value. InvoiceImageUrl accepts valid URL only. | [optional] 
**is_posted** | **int** | This is an optional field. This field accepts single value. IsPosted allows inserting posted invoices. | [optional] 
**property_building_id** | **int** | This is an optional field. This field accepts single value. Child element of ApDetail. | [optional] 
**property_unit_id** | **int** | This is an optional field. This field accepts single value. Child element of ApDetail. | [optional] 

## Example

```python
from entrata_api_client.models.send_invoices_r1_method_params import SendInvoicesR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1MethodParams from a JSON string
send_invoices_r1_method_params_instance = SendInvoicesR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1MethodParams.to_json())

# convert the object into a dict
send_invoices_r1_method_params_dict = send_invoices_r1_method_params_instance.to_dict()
# create an instance of SendInvoicesR1MethodParams from a dict
send_invoices_r1_method_params_from_dict = SendInvoicesR1MethodParams.from_dict(send_invoices_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


