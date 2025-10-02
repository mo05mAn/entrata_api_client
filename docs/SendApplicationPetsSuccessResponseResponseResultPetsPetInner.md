# SendApplicationPetsSuccessResponseResponseResultPetsPetInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Success | 
**message** | **str** | Customer pets saved successfully. | 
**id** | **int** | Pet ID. | 
**customer_id** | **int** | Customer ID. | 
**type_id** | **int** | Type ID. | 
**node** | **int** | Node number. | 

## Example

```python
from openapi_client.models.send_application_pets_success_response_response_result_pets_pet_inner import SendApplicationPetsSuccessResponseResponseResultPetsPetInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationPetsSuccessResponseResponseResultPetsPetInner from a JSON string
send_application_pets_success_response_response_result_pets_pet_inner_instance = SendApplicationPetsSuccessResponseResponseResultPetsPetInner.from_json(json)
# print the JSON string representation of the object
print(SendApplicationPetsSuccessResponseResponseResultPetsPetInner.to_json())

# convert the object into a dict
send_application_pets_success_response_response_result_pets_pet_inner_dict = send_application_pets_success_response_response_result_pets_pet_inner_instance.to_dict()
# create an instance of SendApplicationPetsSuccessResponseResponseResultPetsPetInner from a dict
send_application_pets_success_response_response_result_pets_pet_inner_from_dict = SendApplicationPetsSuccessResponseResponseResultPetsPetInner.from_dict(send_application_pets_success_response_response_result_pets_pet_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


