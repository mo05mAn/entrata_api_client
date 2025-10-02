# SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_recipient_ids** | **str** | This is an optional field. Comma separated recipient IDs. | [optional] 
**special_trigger_type_id_prospect** | **str** | This is an optional field. Special trigger type for prospects. | [optional] 
**special_trigger_type_id_renewal** | **str** | This is an optional field. Special trigger type for renewals. | [optional] 

## Example

```python
from entrata_api_client.models.send_special_group_method_params_special_group_special_recipient_details import SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails from a JSON string
send_special_group_method_params_special_group_special_recipient_details_instance = SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.to_json())

# convert the object into a dict
send_special_group_method_params_special_group_special_recipient_details_dict = send_special_group_method_params_special_group_special_recipient_details_instance.to_dict()
# create an instance of SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails from a dict
send_special_group_method_params_special_group_special_recipient_details_from_dict = SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.from_dict(send_special_group_method_params_special_group_special_recipient_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


