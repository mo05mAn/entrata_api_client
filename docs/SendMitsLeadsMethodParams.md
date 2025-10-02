# SendMitsLeadsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property id | 
**do_not_send_confirmation_email** | **int** | This is an optional field. This field accepts single value. Allows restricting the guest card confirmation emails to prospect/prop erty if set to 1. | [optional] 
**is_wait_list** | **int** | This is an optional field. This field accepts single value. When sent as 1, Units will be listed in waitlist. | [optional] 
**last_update_date** | **date** | This is a required field. This field accepts single value. LastUpdateDate | [optional] 

## Example

```python
from openapi_client.models.send_mits_leads_method_params import SendMitsLeadsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendMitsLeadsMethodParams from a JSON string
send_mits_leads_method_params_instance = SendMitsLeadsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendMitsLeadsMethodParams.to_json())

# convert the object into a dict
send_mits_leads_method_params_dict = send_mits_leads_method_params_instance.to_dict()
# create an instance of SendMitsLeadsMethodParams from a dict
send_mits_leads_method_params_from_dict = SendMitsLeadsMethodParams.from_dict(send_mits_leads_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


