# Nav2 Baseline Metrics

## Objective

Establish reproducible navigation baseline performance before testing alternative path-planning algorithms.

## Primary Metrics

### Mission Success

- mission completion rate
- failed mission count
- recovery count

### Planning

- global planning latency
- replanning latency
- total path length

### Localization

- position error
- heading error
- localization-loss events

### Safety

- minimum obstacle clearance
- emergency-stop latency
- stopping distance
- unsafe continuation events

## Experimental Principle

All planner comparisons must use the same:

- map
- start pose
- goal pose
- obstacle configuration
- robot footprint
- velocity constraints
- localization configuration

RRT or RRT* must not be claimed as an improvement unless measured results outperform or address a documented limitation of the baseline.
