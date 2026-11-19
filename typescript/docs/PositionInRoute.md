
# PositionInRoute

If specified, this stop has to be the very first/last customer stop in the route whenever there is a stop at this location. There can only be one stop at a customer location with a position in route of type FIRST_CUSTOMER_STOP/LAST_CUSTOMER_STOP.   If specified, routeSectionNumber must not be set for the same location.   * `FIRST_CUSTOMER_STOP` - A stop at a customer location with this position type has to be the very first customer stop in the route.  * `LAST_CUSTOMER_STOP` - A stop at a customer location with this position type has to be the very last customer stop in the route.  See [here](./concepts/route-sections-and-position-route) for more information.

## Properties

Name | Type
------------ | -------------

## Example

```typescript
import type { PositionInRoute } from ''

// TODO: Update the object below with actual values
const example = {
} satisfies PositionInRoute

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as PositionInRoute
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


