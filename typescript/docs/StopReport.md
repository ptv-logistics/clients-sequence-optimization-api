
# StopReport

A stop report contains a summary of the values of the events at a stop, including the arrival time, the departure time and the service time. It also contains information about the loaded quantities when leaving the current stop.

## Properties

Name | Type
------------ | -------------
`arrivalTime` | Date
`departureTime` | Date
`serviceTime` | number
`waitingTime` | number
`breakTime` | number
`quantities` | Array&lt;number&gt;

## Example

```typescript
import type { StopReport } from ''

// TODO: Update the object below with actual values
const example = {
  "arrivalTime": null,
  "departureTime": null,
  "serviceTime": null,
  "waitingTime": null,
  "breakTime": null,
  "quantities": null,
} satisfies StopReport

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as StopReport
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


