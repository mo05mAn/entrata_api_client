# SendLeasesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**lease_start_date** | **date** | This is a required field. This field accepts single value. leaseStartDate (YYYY-MM-DD) | 
**lease_end_date** | **date** | This is a required field. This field accepts single value. leaseEndDate (YYYY-MM-DD) | 
**move_in_date** | **date** | This is a required field. This field accepts single value. moveInDate (YYYY-MM-DD) | 
**lease_term_id** | **int** | This is a required field. This field accepts single value. leaseTermId | 
**floorplan_id** | **int** | This is a required field. This field accepts single value. floorplanId | 
**unit_space_id** | **int** | This is a required field. This field accepts single value. unitSpaceId | 
**space_configuration_id** | **int** | This is an optional field. This field accepts single value. If the provided property is of type \&quot;Student\&quot;, only then \&quot;spaceConfigurationId\&quot; is required. | [optional] 
**lease_start_window_id** | **int** | This is an optional field. This field accepts single value. If the provided property is of type \&quot;Student\&quot;, only then \&quot;leaseStartWindowId\&quot; is required. | [optional] 
**first_name** | **str** | This is a required field. This field accepts single value. firstName | 
**middle_name** | **str** | This is an optional field. This field accepts single value. middleName | [optional] 
**last_name** | **str** | This is a required field. This field accepts single value. lastName | 
**customer_relationship_type_id** | **int** | This is a required field. This field accepts single value. customerRelationshipTypeId | 
**email_address** | **str** | This is an optional field. This field accepts single value. emailAddress | [optional] 
**birth_date** | **date** | This is an optional field. This field accepts single value. birthDate (YYYY-MM-DD) | [optional] 
**phone_number_type_id** | **int** | This is a required field. This field accepts single value. phoneNumberTypeId | 
**phone_number** | **int** | This is a required field. This field accepts single value. Primary phoneNumber | 
**address_type_id** | **int** | This is a required field. This field accepts single value. addressTypeId | 
**street_line1** | **str** | This is a required field. This field accepts single value. Address streetLine1 | 
**street_line2** | **str** | This is an optional field. This field accepts single value. streetLine2 | [optional] 
**city** | **str** | This is a required field. This field accepts single value. city | 
**state_code** | **str** | This is a required field. This field accepts single value. stateCode | 
**postal_code** | **int** | This is a required field. This field accepts single value. postalCode | 

## Example

```python
from openapi_client.models.send_leases_method_params import SendLeasesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeasesMethodParams from a JSON string
send_leases_method_params_instance = SendLeasesMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendLeasesMethodParams.to_json())

# convert the object into a dict
send_leases_method_params_dict = send_leases_method_params_instance.to_dict()
# create an instance of SendLeasesMethodParams from a dict
send_leases_method_params_from_dict = SendLeasesMethodParams.from_dict(send_leases_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


