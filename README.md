# Snappy

Snappy is a Github Action which creates a snapshot tag
using the commit SHA and the current timestamp.

## Inputs
`BASE_VERSION`

This is the base semantic version that will be used to create
the snapshot. For example, v3.4.3

## Outputs
`SNAPSHOT_VERSION`

This is the snapshot version that is generated by the action.

For example, v3.4.3-20200712152333-a007e621125e