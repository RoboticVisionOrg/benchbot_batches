**NOTE: this software is part of the BenchBot software stack, and not intended to be used in isolation. For a working BenchBot system, please install the BenchBot software stack by following the instructions [here](https://github.com/RoboticVisionOrg/benchbot)**

# BenchBot Batches

BenchBot batches is a set of environment lists used in both development, and challenge evaluation. The files allow easy replication of a static list of environments, which can be used with:
- the `-E` argument of the `benchbot_batch` script (from the [BenchBot software stack](https://github.com/RoboticVisionOrg/benchbot)) when autonomously running a submission through multiple environments,
- evaluation to require a certain set of environments (TODO: flag to specify a required environments not yet released).

## Descriptions for each batch

Batches are organised by whether they are for development, or a challenge, & the target task. Development batches only include environments that come with a publicly available ground-truth file (so that you can evaluate your performance on the batch locally). Challenge batches solely use environments with no publicly available ground-truth. These batches will be used in public challenges for evaluating the performance of your algorithm.

Please see the table below for a list of batch details:

| Filename | Use Case | Target task |
|----------|:--------:|:-----------:|
|`./challenge/sslam_passive_gt` | Challenge submission | semantic_slam:passive:ground_truth |
|`./challenge/scd_active_gt` | Challenge submission | scd:active:ground_truth |
|`./challenge/sslam_active_dr` | Challenge submission | semantic_slam:active:dead_reckoning |
|`./challenge/scd_active_dr` | Challenge submission | scd:active:dead_reckoning |
|`./challenge/scd_passive_gt` | Challenge submission | scd:passive:ground_truth |
|`./challenge/sslam_active_gt` | Challenge submission | semantic_slam:active:ground_truth |
|`./develop/sslam_passive_gt` | Developing solutions | semantic_slam:passive:ground_truth |
|`./develop/scd_active_gt` | Developing solutions | scd:active:ground_truth |
|`./develop/sslam_active_dr` | Developing solutions | semantic_slam:active:dead_reckoning |
|`./develop/scd_active_dr` | Developing solutions | scd:active:dead_reckoning |
|`./develop/scd_passive_gt` | Developing solutions | scd:passive:ground_truth |
|`./develop/sslam_active_gt` | Developing solutions | semantic_slam:active:ground_truth |
