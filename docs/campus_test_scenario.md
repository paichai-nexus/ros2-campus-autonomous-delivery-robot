# Campus Test Scenarios

## Scenario 1 — Flat Restricted Route

Validate waypoint navigation and basic localization.

Metrics:

- mission completion rate
- localization error
- path deviation

## Scenario 2 — Steep Slope

Evaluate navigation and stopping behavior on inclined terrain.

Metrics:

- slope traversal success rate
- velocity tracking error
- stopping distance

## Scenario 3 — Static Obstacle

Evaluate obstacle detection and replanning.

Metrics:

- replanning latency
- minimum obstacle clearance
- mission recovery rate

## Scenario 4 — Pedestrian Crossing

Evaluate dynamic obstacle response.

Metrics:

- detection-to-stop latency
- minimum clearance
- safe mission recovery

## Scenario 5 — Localization Degradation

Evaluate system behavior under degraded localization.

The robot must reduce autonomy or enter a safe-stop state rather than continuing with unreliable pose estimates.

## Scenario 6 — Emergency Stop

Measure:

- trigger latency
- controller reaction latency
- stopping distance
