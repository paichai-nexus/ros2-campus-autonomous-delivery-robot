# Safety Requirements

## Operating Boundary

Initial experiments are limited to low-speed restricted-area research.

Public autonomous operation is outside the MVP scope.

## Mandatory Safety Functions

- physical emergency stop
- software emergency stop
- configurable speed limit
- obstacle clearance threshold
- localization confidence monitoring
- communication watchdog
- sensor health monitoring
- safe-stop state

## Fail-Safe Principle

Loss of trustworthy localization, critical perception, control communication, or operator supervision must result in a controlled stop.

## Safety Metrics

Record:

- emergency-stop latency
- stopping distance
- obstacle clearance
- false stop events
- unsafe continuation events
