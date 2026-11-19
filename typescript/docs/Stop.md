
# Stop

A stop groups subsequent pickups and/or deliveries at the same location. At a customer location, transports are scheduled in order of their type: pickups after deliveries. At a depot location a stop groups either pickups or deliveries.  See [here](./concepts/route-sections-and-position-route) for more information.

## Properties

Name | Type
------------ | -------------
`locationId` | string
`deliveryIds` | Array&lt;string&gt;
`pickupIds` | Array&lt;string&gt;
`reportForWayToStop` | [WayReport](WayReport.md)
`reportForStop` | [StopReport](StopReport.md)
`eventsOnWayToStop` | [Array&lt;Event&gt;](Event.md)
`eventsAtStop` | [Array&lt;Event&gt;](Event.md)
`violationsOnWayToStop` | [Array&lt;Violation&gt;](Violation.md)
`violationsAtStop` | [Array&lt;Violation&gt;](Violation.md)

## Example

```typescript
import type { Stop } from ''

// TODO: Update the object below with actual values
const example = {
  "locationId": null,
  "deliveryIds": null,
  "pickupIds": null,
  "reportForWayToStop": null,
  "reportForStop": null,
  "eventsOnWayToStop": null,
  "eventsAtStop": null,
  "violationsOnWayToStop": null,
  "violationsAtStop": null,
} satisfies Stop

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Stop
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


