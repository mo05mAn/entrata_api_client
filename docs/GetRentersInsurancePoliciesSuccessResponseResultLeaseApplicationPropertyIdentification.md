# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_value** | **str** | Unique identifier for the property | 
**organization_name** | **str** | Organization name | 
**attributes** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentificationAttributes**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentificationAttributes.md) |  | 

## Example

```python
from openapi_client.models.get_renters_insurance_policies_success_response_result_lease_application_property_identification import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_property_identification_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_property_identification_dict = get_renters_insurance_policies_success_response_result_lease_application_property_identification_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification from a dict
get_renters_insurance_policies_success_response_result_lease_application_property_identification_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification.from_dict(get_renters_insurance_policies_success_response_result_lease_application_property_identification_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


