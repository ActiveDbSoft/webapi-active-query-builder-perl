# SQL::QueryBuilder::WebApi::Object::Condition

## Load the model package
```perl
use SQL::QueryBuilder::WebApi::Object::Condition;
```

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**field** | **string** | Column of original query to which a constraint will applied. | [optional] 
**condition_operator** | **string** | Condition operator. | [optional] 
**values** | **ARRAY[string]** | List of values for a constraint. \&quot;IsNull\&quot;, \&quot;IsNotNull\&quot; need no values; \&quot;Between\&quot;, \&quot;NotBetween\&quot; require 2 values; \&quot;In\&quot; accepts one or more values; other conditions accept single value only. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


