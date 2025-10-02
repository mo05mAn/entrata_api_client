# GetCallLogsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **int** | This is a required field. This field accepts comma seperated multiple values. This node should accept property Id&#x60;s. | 
**call_source_id** | **int** | This is an optional field. This field accepts single value. Supported values (1, 2, 7) | [optional] 
**call_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**call_result_ids** | **int** |   This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**answer_status** | **int** |   This is an optional field. This field accepts single value. Supports only 1 (ANSWERED) &amp; 2 (UNANSWERED) | [optional] 
**voice_mail_type_id** | **int** | This is an optional field. This field accepts single value. Supported values are 1 (VOICE_MESSAGE) or 2 (UNPLAYED_VOICE_MESSAGE) o r 3 (NO_VOICE_MESSAGE). | [optional] 
**call_analyzed** | **int** | This is an optional field. This field accepts single value. Supports 1 (ANALYZED) or 0 (NON_ANALYZED) | [optional] 
**call_state** | **int** | This is an optional field. This field accepts single value. Supports 1 (NON-ARCHIVED) or 2 (ARCHIVED). | [optional] 
**start_date** | **date** | This is an optional field. This field accepts single value. This field accepts value in MM/DD/YYYY format. | [optional] 
**end_date** | **date** | This is an optional field. This field accepts single value. This field accepts value in MM/DD/YYYY format. | [optional] 

## Example

```python
from openapi_client.models.get_call_logs_method_params import GetCallLogsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetCallLogsMethodParams from a JSON string
get_call_logs_method_params_instance = GetCallLogsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetCallLogsMethodParams.to_json())

# convert the object into a dict
get_call_logs_method_params_dict = get_call_logs_method_params_instance.to_dict()
# create an instance of GetCallLogsMethodParams from a dict
get_call_logs_method_params_from_dict = GetCallLogsMethodParams.from_dict(get_call_logs_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


