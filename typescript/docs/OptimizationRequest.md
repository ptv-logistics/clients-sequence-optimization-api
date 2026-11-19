
# OptimizationRequest

An input object for the service method \'startAndCreateOptimizedRoute\'.

## Properties

Name | Type
------------ | -------------
`locations` | [Array&lt;Location&gt;](Location.md)
`vehicle` | [Vehicle](Vehicle.md)
`driver` | [Driver](Driver.md)
`transports` | [Array&lt;Transport&gt;](Transport.md)
`route` | [Array&lt;Stop&gt;](Stop.md)
`restrictions` | [Restrictions](Restrictions.md)

## Example

```typescript
import type { OptimizationRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "locations": null,
  "vehicle": null,
  "driver": null,
  "transports": null,
  "route": null,
  "restrictions": null,
} satisfies OptimizationRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as OptimizationRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


