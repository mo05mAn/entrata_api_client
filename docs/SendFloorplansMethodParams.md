# SendFloorplansMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. This node accepts the property id on which the floorplan will get added. | 
**name** | **str** | This is a required field. This field accepts single value. This node accepts the name of the floorplan. | 
**description** | **str** | This is an optional field. This field accepts single value. This node accepts the description of the floorplan | [optional] 
**seo_title** | **str** | This is an optional field. This field accepts single value. This node accepts the seoTitle of the floorplan | [optional] 
**seo_description** | **str** | This is an optional field. This field accepts single value. This node accepts the seoDescription of the floorplan | [optional] 
**seo_keywords** | **str** | This is an optional field. This field accepts single value. This node accepts the seoKeywords of the floorplan | [optional] 
**is_published** | **int** | This is an optional field. This field accepts single value. This flag accepts 1 or 0, whether the floorplan needs to be published or not. | [optional] 
**is_disabled_virtual_move_in** | **int** | This is an optional field. This field accepts single value. This flag accepts 1 or 0. | [optional] 
**min_square_feet** | **int** | This is an optional field. This field accepts single value. This node accepts the minimum square feet value of the floorplan. | [optional] 
**max_square_feet** | **int** | This is an optional field. This field accepts single value. This node accepts the maximun square feet value of the floorplan. | [optional] 
**number_of_bed_rooms** | **int** | This is a required field. This field accepts single value. This node accepts a total number of bedrooms. | 
**number_of_bath_rooms** | **int** | This is a required field. This field accepts single value. This node accepts a total number of bathrooms. | 
**is_featured** | **int** | This is an optional field. This field accepts single value. This flag accepts 1 or 0. | [optional] 

## Example

```python
from openapi_client.models.send_floorplans_method_params import SendFloorplansMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendFloorplansMethodParams from a JSON string
send_floorplans_method_params_instance = SendFloorplansMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendFloorplansMethodParams.to_json())

# convert the object into a dict
send_floorplans_method_params_dict = send_floorplans_method_params_instance.to_dict()
# create an instance of SendFloorplansMethodParams from a dict
send_floorplans_method_params_from_dict = SendFloorplansMethodParams.from_dict(send_floorplans_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


