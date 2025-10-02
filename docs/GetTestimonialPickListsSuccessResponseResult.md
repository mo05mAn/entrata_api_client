# GetTestimonialPickListsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**testimonial_types** | [**GetTestimonialPickListsSuccessResponseResultTestimonialTypes**](GetTestimonialPickListsSuccessResponseResultTestimonialTypes.md) |  | 
**testimonial_rating_types** | [**GetTestimonialPickListsSuccessResponseResultTestimonialRatingTypes**](GetTestimonialPickListsSuccessResponseResultTestimonialRatingTypes.md) |  | 

## Example

```python
from openapi_client.models.get_testimonial_pick_lists_success_response_result import GetTestimonialPickListsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetTestimonialPickListsSuccessResponseResult from a JSON string
get_testimonial_pick_lists_success_response_result_instance = GetTestimonialPickListsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetTestimonialPickListsSuccessResponseResult.to_json())

# convert the object into a dict
get_testimonial_pick_lists_success_response_result_dict = get_testimonial_pick_lists_success_response_result_instance.to_dict()
# create an instance of GetTestimonialPickListsSuccessResponseResult from a dict
get_testimonial_pick_lists_success_response_result_from_dict = GetTestimonialPickListsSuccessResponseResult.from_dict(get_testimonial_pick_lists_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


