# GetMitsLeadsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**lead_id** | **int** | This is an optional field. This field accepts single value. Application Id referring PSI system | [optional] 
**name** | **str** | This is an optional field. This field accepts single value. This field accepts a combination of Firstname &amp; Lastname. If either of one is provided, leads matching with given input will be returned in the response. | [optional] 
**telephone** | **int** | This is an optional field. This field accepts single value. This field accepts Primary/Mobile/Home/Work number of prospect in any format | [optional] 
**email** | **str** | This is an optional field. This field accepts single value. This field accepts email address of prospect. | [optional] 
**lead_status_ids** | **int** | This is an optional field. This field accepts single value. leadStatusIds - comma seperated | [optional] 
**ps_product_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. psProductIds - comma seperated | [optional] 
**event_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. eventTypeIds - comma seperated | [optional] 
**send_unit_spaces** | **int** | This is an optional field. This field accepts single value. sendUnitSpaces | [optional] 
**from_date_time** | **date** | This is a required field. This field accepts single value. This is an conditionally mandatory field.If name or telephone or email or leadId is provided then fromDate is not required. | [optional] 
**to_date_time** | **date** | This is a required field. This field accepts single value. This is an conditionally mandatory field. If name or telephone or emai l or leadId is provided then toDate is not required. | [optional] 
**event_date_from** | **date** | This is an optional field. This field accepts single value. eventDateFrom | [optional] 
**event_date_to** | **date** |   This is an optional field. This field accepts single value. eventDateTo | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_leads_method_params import GetMitsLeadsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsMethodParams from a JSON string
get_mits_leads_method_params_instance = GetMitsLeadsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsMethodParams.to_json())

# convert the object into a dict
get_mits_leads_method_params_dict = get_mits_leads_method_params_instance.to_dict()
# create an instance of GetMitsLeadsMethodParams from a dict
get_mits_leads_method_params_from_dict = GetMitsLeadsMethodParams.from_dict(get_mits_leads_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


