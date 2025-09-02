# RoadLinkUserType

![RoadLinkUserType Diagram](../diagrams/RoadLinkUserType.svg)

## Restrictions

| Property | Restriction Type |
|----------|------------------|
| speedLimit | All values from cityunits:Speed |
| travelTime | All values from cityunits:Duration |
| userCategory | All values from code:Code |
| uses | All values from RoadLink |

## Other Annotations

- **terms:description**: A RoadLinkUserType represents the unique combination of a RoadLink and a UserType such that speed limits and other characteristics can be defined to apply to specific user types when operating along a particular road link.
- **xsd:pattern**: RoadNetworkPattern

