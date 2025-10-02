# SendJournalEntriesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**gl_account_id** | **int** | This is a required field. This field accepts single value. | 
**gl_header_type_id** | **int** | This is an optional field. This field accepts single value. If the value for glHeaderTypeId is not provided take default as Standard | [optional] 
**reference** | **str** | This is an optional field. This field accepts single value. | [optional] 
**accounting_method** | **str** | This is an optional field. This field accepts single value. If not provided, the accounting method of \&quot;Both\&quot; is used. | [optional] 
**gl_book_id** | **int** | This is a required field. This field accepts single value. | 
**post_date** | **date** | This is an optional field. This field accepts single value. If not provided then the default date will be the current date. The pa st date is acceptable | [optional] 
**post_month** | **date** | This is an optional field. This field accepts single value. If not provided then the default will be the current post month. Past post month is acceptable | [optional] 
**is_reverse** | **int** | This is an optional field. This field accepts single value. By default value will be false. | [optional] 
**reverse_post_month** | **date** | This is an optional field. This field accepts single value. Conditionally required. Based on \&quot;isReverse\&quot; flag. | [optional] 
**routing_tag_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**notes** | **str** | This is an optional field. This field accepts single value. | [optional] 
**default_property_unit_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**default_property_building_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**default_gl_dimension_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**memo** | **str** | This is an optional field. This field accepts single value. | [optional] 
**debit_amount** | **int** | This is an optional field. This field accepts single value. Conditional Required. If the Credit amount is passed then this should be 0. | [optional] 
**credit_amount** | **int** | This is an optional field. This field accepts single value. Conditional Required. If Debit amount is passed this should be 0 | [optional] 
**unit_space_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**property_unit_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**property_building_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**gl_dimension_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**default_job_phase_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**default_ap_contract_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**job_phase_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**ap_contract_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**ap_code_id** | **int** | This is an optional field. This field accepts single value | [optional] 

## Example

```python
from openapi_client.models.send_journal_entries_method_params import SendJournalEntriesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendJournalEntriesMethodParams from a JSON string
send_journal_entries_method_params_instance = SendJournalEntriesMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendJournalEntriesMethodParams.to_json())

# convert the object into a dict
send_journal_entries_method_params_dict = send_journal_entries_method_params_instance.to_dict()
# create an instance of SendJournalEntriesMethodParams from a dict
send_journal_entries_method_params_from_dict = SendJournalEntriesMethodParams.from_dict(send_journal_entries_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


