# SendApplicationMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**originating_lead_source_id** | **int** | This is a required field. This field accepts single value. | 
**leasing_agent_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**unit_space_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**move_in_date** | **date** | This is a required field. This field accepts single value. | [optional] 
**floorplan_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**lease_term_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**application_status_id** | **int** | This is an optional field. This field accepts single value. Acceptable values are 3 (COMPLETED ) &amp; 4 (APPLICATION_APPROVED ) | [optional] 

## Example

```python
from entrata_api_client.models.send_application_method_params import SendApplicationMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationMethodParams from a JSON string
send_application_method_params_instance = SendApplicationMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendApplicationMethodParams.to_json())

# convert the object into a dict
send_application_method_params_dict = send_application_method_params_instance.to_dict()
# create an instance of SendApplicationMethodParams from a dict
send_application_method_params_from_dict = SendApplicationMethodParams.from_dict(send_application_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


