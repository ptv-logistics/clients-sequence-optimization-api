
# Location

A specific location where goods have to be picked up or delivered, or where the vehicle is located. A location is either a depot location or a customer location. Depot locations may be found at start or end of **route-stops**.  See [here](./concepts/locations-transports-and-stops) for more information.

## Properties

Name | Type
------------ | -------------
`id` | string
`type` | [LocationType](LocationType.md)
`latitude` | number
`longitude` | number
`roadAccess` | [RoadAccess](RoadAccess.md)
`includeLastMeters` | boolean
`matchSideOfStreet` | boolean
`openingIntervals` | [Array&lt;TimeInterval&gt;](TimeInterval.md)
`customerLocationAttributes` | [CustomerLocationAttributes](CustomerLocationAttributes.md)
`depotLocationAttributes` | [DepotLocationAttributes](DepotLocationAttributes.md)

## Example

```typescript
import type { Location } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "type": null,
  "latitude": null,
  "longitude": null,
  "roadAccess": null,
  "includeLastMeters": null,
  "matchSideOfStreet": null,
  "openingIntervals": null,
  "customerLocationAttributes": null,
  "depotLocationAttributes": null,
} satisfies Location

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Location
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


