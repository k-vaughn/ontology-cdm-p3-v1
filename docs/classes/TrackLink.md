# TrackLink

A TrackLink is a type of TravelledWayLink that uses rails on a stabilized base.

![TrackLink Diagram](../diagrams/TrackLink.svg)

## Formalization

| Property | Value Restriction |
|----------|-------------------|
| partwhole:hasProperPart | only [TrackSegment](TrackSegment.md) |
| partwhole:properPartOf | only ([RailCorridor](RailCorridor.md) or [RailNetwork](RailNetwork.md) or [RailSection](RailSection.md)) |
| rdfs:subClassOf | [TravelledWayLink](TravelledWayLink.md) |

## Other Annotations

- **xsd:pattern**: [RailNetworkPattern](RailNetworkPattern.md)

