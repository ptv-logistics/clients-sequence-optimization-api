
# Vehicle

The vehicle used to transport goods.

## Properties

Name | Type
------------ | -------------
`capacities` | Array&lt;number&gt;
`profile` | string
`startLocationId` | string
`endLocationId` | string
`routeStartInterval` | [TimeInterval](TimeInterval.md)
`maximumDistance` | number

## Example

```typescript
import type { Vehicle } from ''

// TODO: Update the object below with actual values
const example = {
  "capacities": null,
  "profile": null,
  "startLocationId": null,
  "endLocationId": null,
  "routeStartInterval": null,
  "maximumDistance": null,
} satisfies Vehicle

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Vehicle
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


