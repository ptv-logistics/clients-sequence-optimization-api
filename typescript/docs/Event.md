
# Event

An event specifies what happens on a route at a certain point in time. It can describe the driver\'s activity such as driving or performing service, or it can denote the start/end of a route.

## Properties

Name | Type
------------ | -------------
`type` | [EventType](EventType.md)
`startTime` | Date
`duration` | number
`transportId` | string

## Example

```typescript
import type { Event } from ''

// TODO: Update the object below with actual values
const example = {
  "type": null,
  "startTime": null,
  "duration": null,
  "transportId": null,
} satisfies Event

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Event
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


