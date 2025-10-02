# UpdateLeadsR2MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Accepts the property Id value. | 
**application_id** | **int** | This is a required field. This field accepts single value. Accept the Application_Id(Lead_Id), can be obtained from getLeads API. | 
**event_id** | **int** | This is an optional field. This field accepts single value. Accepts the value for Event Id. | [optional] 
**type_id** | **int** | This is a required field. This field accepts single value. Accepts the Event Type Id value under this node. | 
**event_result_id** | **int** | This is an optional field. This field accepts single value. Value for event result id should be fetched from getLeadPickLists API. Depending on the Events this node should be considered mandatory. | [optional] 
**subtype_id** | **int** | This is an optional field. This field accepts single value. This node supports following subtypeId values, under event type \&quot;Appointment\&quot;:- 453:\&quot;Leasing Appointments\&quot;, 560:\&quot;Self-Guided Tour\&quot;, 454:\&quot; Tour\&quot;, 525:\&quot;Virtual Tour\&quot;. And under event type \&quot;Tour\&quot;:- 524:\&quot;Self-Gui ded Tour\&quot; | [optional] 
**var_date** | **date** | This is an optional field. This field accepts single value. This is the event date. During cloning, all the lead event dates will be set to the current date. | [optional] 

## Example

```python
from openapi_client.models.update_leads_r2_method_params import UpdateLeadsR2MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR2MethodParams from a JSON string
update_leads_r2_method_params_instance = UpdateLeadsR2MethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR2MethodParams.to_json())

# convert the object into a dict
update_leads_r2_method_params_dict = update_leads_r2_method_params_instance.to_dict()
# create an instance of UpdateLeadsR2MethodParams from a dict
update_leads_r2_method_params_from_dict = UpdateLeadsR2MethodParams.from_dict(update_leads_r2_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


