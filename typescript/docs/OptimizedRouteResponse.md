
# OptimizedRouteResponse

Contains the results of an optimization. If the \'status\' is \'RUNNING\', the calculation is still running and no further properties are set. If the \'status\' is \'SUCCEEDED\', the optimization result is present as property \'optimizedRoute\'. If the \'status\' is \'FAILED\', the failure result is present as property \'error\'.

## Properties

Name | Type
------------ | -------------
`status` | [OperationStatus](OperationStatus.md)
`optimizedRoute` | [OptimizedRoute](OptimizedRoute.md)
`error` | [ErrorResponse](ErrorResponse.md)
`warnings` | [Array&lt;Warning&gt;](Warning.md)

## Example

```typescript
import type { OptimizedRouteResponse } from ''

// TODO: Update the object below with actual values
const example = {
  "status": null,
  "optimizedRoute": null,
  "error": null,
  "warnings": null,
} satisfies OptimizedRouteResponse

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as OptimizedRouteResponse
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


