# SendApplicationEmployersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **int** |   This is a required field. This field accepts single value. Required parameter, accepts integer value. | 
**property_id** | **int** | This is a required field. This field accepts single value. Required parameter, accepts integer value. | 
**id** | **int** | This is an optional field. This field accepts single value. Conditionally Required parameter. If provided, it will update the empl oyer record on provided application. otherwise insert the employer record. | [optional] 
**income_type_id** | **int** | This is an optional field. This field accepts single value. Conditionally Required parameter. If \&quot;id\&quot; is not provided, this parame ter is required. | [optional] 
**customer_id** | **int** | This is an optional field. This field accepts single value. Conditionally Required parameter. If \&quot;id\&quot; is not provided, this parame ter is required. | [optional] 
**frequency_id** | **int** | This is an optional field. This field accepts single value. Optional parameter, accepts integer value. If provided should be a val id frequency range which are: 3 [ weekly ], 4 [ Monthly ] and 6 [ Yearly ] | [optional] 
**position** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_name** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_phone_number** | **str** | This is an optional field. This field accepts single value. Optional parameter, accept string value. If provided, should be valid phone number. | [optional] 
**institution_street_line1** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_street_line2** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_street_line3** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_city** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_state_code** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_province** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_postal_code** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**institution_country_code** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**amount** | **int** | This is an optional field. This field accepts single value. Conditionally Required parameter, accepts float value with two decimal points. If Id is not provided, this becomes required. | [optional] 
**contact_name** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**contact_phone** | **str** | This is an optional field. This field accepts single value. Optional parameter, accept string value. If provided, should be valid phone number. | [optional] 
**contact_email** | **str** | This is an optional field. This field accepts single value. Optional parameter, accepts string value | [optional] 
**income_effective_date** | **date** | This is an optional field. This field accepts single value. Optional parameter, accept date in MM/DD/YYYY or YYYY-MM-DD format. | [optional] 
**date_started** | **date** | This is an optional field. This field accepts single value. Optional parameter, accept date in MM/DD/YYYY or YYYY-MM-DD format. | [optional] 
**date_ended** | **date** | This is an optional field. This field accepts single value. Optional parameter, accept date in MM/DD/YYYY or YYYY-MM-DD format. if provided, then dateStarted and dateEnded should be in valid range. da teStarted should be less than dateEnded. | [optional] 
**is_delete** | **int** | This is an optional field. This field accepts single value. Optional parameter, accept either 1 or 0. if provided value as 1 then id is required and the employer record will be removed from applicatio n. | [optional] 

## Example

```python
from entrata_api_client.models.send_application_employers_method_params import SendApplicationEmployersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationEmployersMethodParams from a JSON string
send_application_employers_method_params_instance = SendApplicationEmployersMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendApplicationEmployersMethodParams.to_json())

# convert the object into a dict
send_application_employers_method_params_dict = send_application_employers_method_params_instance.to_dict()
# create an instance of SendApplicationEmployersMethodParams from a dict
send_application_employers_method_params_from_dict = SendApplicationEmployersMethodParams.from_dict(send_application_employers_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


