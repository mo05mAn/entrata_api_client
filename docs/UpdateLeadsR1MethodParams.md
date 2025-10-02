# UpdateLeadsR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. PropertyId | 
**application_id** | **int** | This is a required field. This field accepts single value. ApplicationId | 

## Example

```python
from entrata_api_client.models.update_leads_r1_method_params import UpdateLeadsR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR1MethodParams from a JSON string
update_leads_r1_method_params_instance = UpdateLeadsR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR1MethodParams.to_json())

# convert the object into a dict
update_leads_r1_method_params_dict = update_leads_r1_method_params_instance.to_dict()
# create an instance of UpdateLeadsR1MethodParams from a dict
update_leads_r1_method_params_from_dict = UpdateLeadsR1MethodParams.from_dict(update_leads_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


