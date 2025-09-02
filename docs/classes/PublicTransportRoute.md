# PublicTransportRoute

![PublicTransportRoute Diagram](../diagrams/PublicTransportRoute.svg)

## Restrictions

| Property | Restriction Type |
|----------|------------------|
| direction | All values from code:Code |
| partwhole:properPartOf | All values from PublicTransportLine |
| points | All values from PointOnRoute |

## Other Annotations

- **skos:note**: For example, a PublicTransportLine might use an alternate PublicTransportRoute to reach its next stop during periods of congestion.
- **terms:description**: A PublicTransportRoute represents one specific path used by a public transport vehicle to transport passengers to and from designated locations.
- **xsd:pattern**: PublicTransportSystemPattern

