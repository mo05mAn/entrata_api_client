# SendLeadsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. This is a required field. This field accepts a single integer value fo r Property ID. | 
**subtype_id** | **int** | This is an optional field. This field accepts single value. This node supports following subtypeId values, under event type \&quot;Appointment\&quot;:- 453:\&quot;Leasing Appointments\&quot;, 560:\&quot;Self-Guided Tour\&quot;, 454:\&quot; Tour\&quot;, 525:\&quot;Virtual Tour\&quot; | [optional] 

## Example

```python
from entrata_api_client.models.send_leads_method_params import SendLeadsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsMethodParams from a JSON string
send_leads_method_params_instance = SendLeadsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendLeadsMethodParams.to_json())

# convert the object into a dict
send_leads_method_params_dict = send_leads_method_params_instance.to_dict()
# create an instance of SendLeadsMethodParams from a dict
send_leads_method_params_from_dict = SendLeadsMethodParams.from_dict(send_leads_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


