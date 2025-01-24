# TroubleKit
A collection of debug and troubleshooting tools.

These tools are experimental and not battle-tested.  Use at your own risk.

## Component Lifecycle Tracer
A troubleshooting tool used to visualize the lifecycle of a component by tracing its virtual function calls.  Useful for troubleshooting the order of operations during component initialization, serialization, destruction, etc.

Attach to an actor, then look for LogComponentLifecycle log messages.  Traces will display the address and name of the owning actor (if known) alongside each call to the components' virtual functions.