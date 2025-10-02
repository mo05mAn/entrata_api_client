# UpdatePropertyResponseMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**testimonial_id** | **int** | This is an optional field. This field accepts single value. | 
**review_response** | **str** | Test Review Response | [optional] 
**is_publish** | **bool** | This is a required field. This field accepts single value. | 

## Example

```python
from openapi_client.models.update_property_response_method_params import UpdatePropertyResponseMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyResponseMethodParams from a JSON string
update_property_response_method_params_instance = UpdatePropertyResponseMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyResponseMethodParams.to_json())

# convert the object into a dict
update_property_response_method_params_dict = update_property_response_method_params_instance.to_dict()
# create an instance of UpdatePropertyResponseMethodParams from a dict
update_property_response_method_params_from_dict = UpdatePropertyResponseMethodParams.from_dict(update_property_response_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


