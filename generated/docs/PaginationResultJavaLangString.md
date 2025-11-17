# PaginationResultJavaLangString


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**values** | **List[str]** |  | [optional] 
**total** | **int** |  | 
**offset** | **int** |  | 
**limit** | **int** |  | 

## Example

```python
from torizon_io_api.models.pagination_result_java_lang_string import PaginationResultJavaLangString

# TODO update the JSON string below
json = "{}"
# create an instance of PaginationResultJavaLangString from a JSON string
pagination_result_java_lang_string_instance = PaginationResultJavaLangString.from_json(json)
# print the JSON string representation of the object
print(PaginationResultJavaLangString.to_json())

# convert the object into a dict
pagination_result_java_lang_string_dict = pagination_result_java_lang_string_instance.to_dict()
# create an instance of PaginationResultJavaLangString from a dict
pagination_result_java_lang_string_from_dict = PaginationResultJavaLangString.from_dict(pagination_result_java_lang_string_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


