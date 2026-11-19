
# OptimizedRoute

The optimized route contains a summary of the values of all events, including the start time and the end time of the route and the ids of the orders that remain unplanned.

## Properties

Name | Type
------------ | -------------
`route` | [Array&lt;Stop&gt;](Stop.md)
`startTime` | Date
`endTime` | Date
`travelTime` | number
`distance` | number
`drivingTime` | number
`serviceTime` | number
`waitingTime` | number
`breakTime` | number
`unplannedTransportIds` | Array&lt;string&gt;

## Example

```typescript
import type { OptimizedRoute } from ''

// TODO: Update the object below with actual values
const example = {
  "route": null,
  "startTime": null,
  "endTime": null,
  "travelTime": null,
  "distance": null,
  "drivingTime": null,
  "serviceTime": null,
  "waitingTime": null,
  "breakTime": null,
  "unplannedTransportIds": null,
} satisfies OptimizedRoute

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as OptimizedRoute
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


