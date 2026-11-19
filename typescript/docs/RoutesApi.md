# RoutesApi

All URIs are relative to *https://api.myptv.com/sequenceoptimization/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**deleteOptimizedRoute**](RoutesApi.md#deleteoptimizedroute) | **DELETE** /routes/{id} |  |
| [**getOptimizedRoute**](RoutesApi.md#getoptimizedroute) | **GET** /routes/{id} |  |
| [**startAndCreateOptimizedRoute**](RoutesApi.md#startandcreateoptimizedroute) | **POST** /routes |  |



## deleteOptimizedRoute

> deleteOptimizedRoute(id)



Deletes the optimized route whose ID is specified.

### Example

```ts
import {
  Configuration,
  RoutesApi,
} from '';
import type { DeleteOptimizedRouteRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const config = new Configuration({ 
    // To configure API key authorization: apiKeyAuth
    apiKey: "YOUR API KEY",
  });
  const api = new RoutesApi(config);

  const body = {
    // string | Unique optimized route ID.
    id: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies DeleteOptimizedRouteRequest;

  try {
    const data = await api.deleteOptimizedRoute(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | `string` | Unique optimized route ID. | [Defaults to `undefined`] |

### Return type

`void` (Empty response body)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **204** | Success with empty result. |  -  |
| **0** | Response on failure. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## getOptimizedRoute

> OptimizedRouteResponse getOptimizedRoute(id)



Retrieves the status, and if the status is SUCCEEDED, the optimized route whose ID is specified.

### Example

```ts
import {
  Configuration,
  RoutesApi,
} from '';
import type { GetOptimizedRouteRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const config = new Configuration({ 
    // To configure API key authorization: apiKeyAuth
    apiKey: "YOUR API KEY",
  });
  const api = new RoutesApi(config);

  const body = {
    // string | Unique optimized route ID.
    id: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies GetOptimizedRouteRequest;

  try {
    const data = await api.getOptimizedRoute(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | `string` | Unique optimized route ID. | [Defaults to `undefined`] |

### Return type

[**OptimizedRouteResponse**](OptimizedRouteResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | The requested result is successfully provided. |  -  |
| **0** | Response on failure. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## startAndCreateOptimizedRoute

> OptimizedRouteIdentifier startAndCreateOptimizedRoute(optimizationRequest, considerTransportPriorities)



Performs desired sequence optimization. The call is asynchronous and only one optimization can be started at a time. Returns unique optimized route ID upon success. Use the unique ID returned to subsequently track the progress of the optimization and to get the optimized route. The number of transports in the request is used to calculate the number of transactions, see [here](../../help/faq-help) for more information.

### Example

```ts
import {
  Configuration,
  RoutesApi,
} from '';
import type { StartAndCreateOptimizedRouteRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const config = new Configuration({ 
    // To configure API key authorization: apiKeyAuth
    apiKey: "YOUR API KEY",
  });
  const api = new RoutesApi(config);

  const body = {
    // OptimizationRequest | Specific instance for sequence optimization.
    optimizationRequest: ...,
    // boolean | Set transport priority consideration to true or false.  See [here](./concepts/transport-priorities) for more information. (optional)
    considerTransportPriorities: true,
  } satisfies StartAndCreateOptimizedRouteRequest;

  try {
    const data = await api.startAndCreateOptimizedRoute(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **optimizationRequest** | [OptimizationRequest](OptimizationRequest.md) | Specific instance for sequence optimization. | |
| **considerTransportPriorities** | `boolean` | Set transport priority consideration to true or false.  See [here](./concepts/transport-priorities) for more information. | [Optional] [Defaults to `false`] |

### Return type

[**OptimizedRouteIdentifier**](OptimizedRouteIdentifier.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **202** | Sequence optimization request is accepted for processing. |  -  |
| **0** | Response on failure. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)

