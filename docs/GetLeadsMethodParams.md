# GetLeadsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**lead_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**name** | **str** | This is an optional field. This field accepts single value. Accepts combination of Firstname &amp; Lastname to filter leads depending on inputs. | [optional] 
**telephone** | **int** | This is an optional field. This field accepts single value. Accepts Primary/Work/Home/Mobile number as input. | [optional] 
**email** | **str** | This is an optional field. This field accepts single value. | [optional] 
**lead_status_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**ps_product_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**include_demographics** | **int** | This is an optional field. This field accepts single value. | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. Format: MM/DD/YYYY. Conditional Mandatory. This node should return the application on the mentioned date range. | [optional] 
**to_date** | **date** | This is an optional field. This field accepts single value. Format: MM/DD/YYYY. Conditional Mandatory. This node should return the application on the mentioned date range. | [optional] 
**created_on_date_from** | **date** | This is an optional field. This field accepts single value. Format MM/DD/YYYY. This node should return the actual application crea ted on the mentioned date range. | [optional] 
**created_on_date_to** | **date** | This is an optional field. This field accepts single value. Format MM/DD/YYYY. This node should return the actual application crea ted on the mentioned date range. | [optional] 
**event_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. In the response, events will not be returned unless we pass specific E vent Type Id(s) in this node. Accepts comma-separated values with lim it 5. | [optional] 
**event_date_from** | **date** | This is an optional field. This field accepts single value. Format: MM/DD/YYYY | [optional] 
**event_date_to** | **date** | This is an optional field. This field accepts single value. Format: MM/DD/YYYY | [optional] 

## Example

```python
from entrata_api_client.models.get_leads_method_params import GetLeadsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsMethodParams from a JSON string
get_leads_method_params_instance = GetLeadsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeadsMethodParams.to_json())

# convert the object into a dict
get_leads_method_params_dict = get_leads_method_params_instance.to_dict()
# create an instance of GetLeadsMethodParams from a dict
get_leads_method_params_from_dict = GetLeadsMethodParams.from_dict(get_leads_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


