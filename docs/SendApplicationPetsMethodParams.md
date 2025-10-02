# SendApplicationPetsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **int** |   This is a required field. This field accepts single value. Required parameter, accepts integer value. | 
**property_id** | **int** | This is a required field. This field accepts single value. Required parameter, accepts integer value. | 
**id** | **int** | This is an optional field. This field accepts single value. Optional parameter, accepts integer value. If provided we will update the pet record | [optional] 
**customer_id** | **int** | This is an optional field. This field accepts single value. Conditionally required. Accepts integer value. If id is not provided, this parameter is required | [optional] 
**type_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**name** | **str** | This is an optional field. This field accepts single value. | [optional] 
**breed** | **str** | This is an optional field. This field accepts single value. | [optional] 
**gender** | **str** | This is an optional field. This field accepts single value. | [optional] 
**color** | **str** | This is an optional field. This field accepts single value. | [optional] 
**weight** | **int** | This is an optional field. This field accepts single value. | [optional] 
**age** | **int** | This is an optional field. This field accepts single value. | [optional] 
**description** | **str** | This is an optional field. This field accepts single value. | [optional] 
**license_city** | **str** | This is an optional field. This field accepts single value. | [optional] 
**license_number** | **str** | This is an optional field. This field accepts single value. | [optional] 
**is_assistance_animal** | **int** | This is an optional field. This field accepts single value. | [optional] 
**is_pet_spayed_or_neutered** | **int** | This is an optional field. This field accepts single value. | [optional] 
**pet_spayed_or_neutered_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**is_house_broken** | **int** | This is an optional field. This field accepts single value. | [optional] 
**special_provisions** | **str** | This is an optional field. This field accepts single value. | [optional] 
**is_delete** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.send_application_pets_method_params import SendApplicationPetsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationPetsMethodParams from a JSON string
send_application_pets_method_params_instance = SendApplicationPetsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendApplicationPetsMethodParams.to_json())

# convert the object into a dict
send_application_pets_method_params_dict = send_application_pets_method_params_instance.to_dict()
# create an instance of SendApplicationPetsMethodParams from a dict
send_application_pets_method_params_from_dict = SendApplicationPetsMethodParams.from_dict(send_application_pets_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


