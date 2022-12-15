# {{classname}}

All URIs are relative to *http://examples.apimatic.io/apps/calculator*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Calculate**](SimpleCalculatorApi.md#Calculate) | **Get** /{operation} | Calculate

# **Calculate**
> float64 Calculate(ctx, operation, x, y)
Calculate

Calculates the expression using the specified operation.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **operation** | [**OperationType**](.md)| The operator to apply on the variables | 
  **x** | **float64**| The LHS value | 
  **y** | **float64**| The RHS value | 

### Return type

**float64**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

