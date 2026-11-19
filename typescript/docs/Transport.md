
# Transport

A transport is the order to transport goods, that is, to pick them up at one location and deliver them to another location.  See [here](./concepts/locations-transports-and-stops) for more information.

## Properties

Name | Type
------------ | -------------
`id` | string
`quantities` | Array&lt;number&gt;
`pickupLocationId` | string
`pickupServiceTime` | number
`deliveryLocationId` | string
`deliveryServiceTime` | number
`priority` | number

## Example

```typescript
import type { Transport } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "quantities": null,
  "pickupLocationId": null,
  "pickupServiceTime": null,
  "deliveryLocationId": null,
  "deliveryServiceTime": null,
  "priority": null,
} satisfies Transport

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Transport
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


