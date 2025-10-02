# UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_recipient_ids** | **str** | Optional. Comma-separated recipient IDs | [optional] 
**special_trigger_type_id_prospect** | **str** | Optional. Prospect trigger type ID | [optional] 
**special_trigger_type_id_renewal** | **str** | Optional. Renewal trigger type ID | [optional] 

## Example

```python
from entrata_api_client.models.update_special_group_method_params_special_group_special_recipient_details import UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails from a JSON string
update_special_group_method_params_special_group_special_recipient_details_instance = UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.to_json())

# convert the object into a dict
update_special_group_method_params_special_group_special_recipient_details_dict = update_special_group_method_params_special_group_special_recipient_details_instance.to_dict()
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails from a dict
update_special_group_method_params_special_group_special_recipient_details_from_dict = UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.from_dict(update_special_group_method_params_special_group_special_recipient_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


