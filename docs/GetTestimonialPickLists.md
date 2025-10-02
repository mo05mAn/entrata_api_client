# GetTestimonialPickLists


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetTestimonialPickListsMethod**](GetTestimonialPickListsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_testimonial_pick_lists import GetTestimonialPickLists

# TODO update the JSON string below
json = "{}"
# create an instance of GetTestimonialPickLists from a JSON string
get_testimonial_pick_lists_instance = GetTestimonialPickLists.from_json(json)
# print the JSON string representation of the object
print(GetTestimonialPickLists.to_json())

# convert the object into a dict
get_testimonial_pick_lists_dict = get_testimonial_pick_lists_instance.to_dict()
# create an instance of GetTestimonialPickLists from a dict
get_testimonial_pick_lists_from_dict = GetTestimonialPickLists.from_dict(get_testimonial_pick_lists_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


