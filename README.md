# from_land

Public-safe land signal surface.

## Purpose

`from_land` is the public-safe surface for land, station, weather, terrain, environmental, and ground-context artifacts after private validation and release review.

## Boundary

This repo may contain:

```text
public-safe land artifacts
public-safe station context
public-safe weather summaries
public-safe environmental summaries
public-safe terrain or ground-context layers
user-facing documentation
```

This repo must not contain:

```text
operational control logic
raw ingest logic
private source data
sensitive coordinates
receiver credentials
private keys
raw image or audio payloads
person tracking fields
identity judgment
public threat labels
law-enforcement tasking fields
weapons guidance fields
confidential operational notes
actionable operational procedures
```

## Authority chain

```text
fides-supra-protocol -> ctl-injest -> Control -> public-safe artifact -> from_land
```

Control remains the authority for validation, routing, packet contracts, state, and output authorization.
