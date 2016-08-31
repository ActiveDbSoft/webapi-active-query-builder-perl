# SQL::QueryBuilder::WebApi::Object::ConditionGroup

Group of conditions joined with the same boolean operator.

## Load the model package
```perl
use SQL::QueryBuilder::WebApi::Object::ConditionGroup;
```

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**junction_type** | **string** | Type of junction. All &#x3D; AND; Any &#x3D; OR. | [optional] 
**conditions** | [**ARRAY[Condition]**](Condition.md) | List of conditions to join. | [optional] 
**condition_groups** | [**ARRAY[ConditionGroup]**](ConditionGroup.md) | List of nested condition groups to join them with a different boolean operator. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


