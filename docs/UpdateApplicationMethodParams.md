# UpdateApplicationMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **int** | This is a required field. This field accepts single value. This node accepts application id which needs to be updated. | 
**property_id** | **int** | This is a required field. This field accepts single value. This node accepts the property id. | 
**application_status_id** | **int** | This is an optional field. This field accepts single value. This node accept the status id. | [optional] 
**floorplan_id** | **int** | This is an optional field. This field accepts single value. This node accept the associated floorplan id or the floorplan which ne eds to be associated with the application. | [optional] 
**unit_space_id** | **int** | This is an optional field. This field accepts single value. This node accept the associated unit space id or the unit space which needs to be associated with the application. | [optional] 
**lease_term_id** | **int** | This is an optional field. This field accepts single value. This node accepts the lease length. | [optional] 
**leasing_agent_id** | **int** | This is an optional field. This field accepts single value. This node accepts the associated leasing agent or the leasing agent wh ich needs to be updated. | [optional] 
**move_in_date** | **date** | This is an optional field. This field accepts single value. This node accepts the move-in date. In ISO format as well. | [optional] 
**originating_lead_source_id** | **int** | This is an optional field. This field accepts single value. This node accepts the lead source id. | [optional] 
**id** | **int** |   This is an optional field. This field accepts single value. This node accepts the applicants id. | [optional] 
**first_name** | **str** |   This is an optional field. This field accepts single value. This node accepts the applicants first name. | [optional] 
**last_name** | **str** |   This is an optional field. This field accepts single value. This node accepts applicants last name. | [optional] 
**maternal_name** | **str** | This is an optional field. This field accepts single value. This node accepts applicants maternal name. | [optional] 
**preferred_name** | **str** |   This is an optional field. This field accepts single value. This node accepts applicants preferred name. | [optional] 
**birth_date** | **date** | This is an optional field. This field accepts single value. This node accepts applicants birth date. Supports ISO format. | [optional] 
**customer_relationship_type_id** | **int** | This is an optional field. This field accepts single value. This node accepts customer relationship id. | [optional] 
**email** | **str** |   This is an optional field. This field accepts single value. This node accepts the applicants email. | [optional] 
**phone_number_type_id** | **int** | This is an optional field. This field accepts single value. This node accepts applicants phone number type id. This is condition al mandatory node, if phoneNumber is provided then phoneNumberTypeId is required. | [optional] 
**phone_number** | **int** | This is an optional field. This field accepts single value. This node accepts applicants phone number. This is conditional manda tory node, if value for phoneNumberTypeId is provided then this node is required. | [optional] 
**address_type_id** | **int** | This is an optional field. This field accepts single value. This node accepts address type id. | [optional] 
**address_line1** | **str** | This is an optional field. This field accepts single value. | [optional] 
**address_line2** | **str** | This is an optional field. This field accepts single value. | [optional] 
**address_line3** | **str** | This is an optional field. This field accepts single value. | [optional] 
**city** | **str** | This is an optional field. This field accepts single value. | [optional] 
**postal_code** | **int** | This is an optional field. This field accepts single value. | [optional] 
**state_code** | **str** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from openapi_client.models.update_application_method_params import UpdateApplicationMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateApplicationMethodParams from a JSON string
update_application_method_params_instance = UpdateApplicationMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateApplicationMethodParams.to_json())

# convert the object into a dict
update_application_method_params_dict = update_application_method_params_instance.to_dict()
# create an instance of UpdateApplicationMethodParams from a dict
update_application_method_params_from_dict = UpdateApplicationMethodParams.from_dict(update_application_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


