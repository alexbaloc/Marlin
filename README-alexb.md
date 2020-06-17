# Reason for repo

Original SKR mini [official repo](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/tree/master/firmware/V2.0) firmware doesn't work with BLTouch (see bug described [here](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/issues/268).

Instead, the recommended approach is to use the official Marlin bugfix-2.0.x version and apply all Ender 3 pro custom configuration on top, plus changes from the official SKR mini V2 repo.

Followed instructions available here:
https://www.reddit.com/r/ender3/comments/h8y1ia/marlin_20x_guide_skr_mini_e3_v20_ender_3/

## Features applied

Base version in this branch contains:
- all required hardware settings (speed, acceleration, motor drivers, bed sizes, etc.)
- manual bed leveling support
- NO heated bed PID tuning
- NO LINEAR ADVANCED CONFIGURATION
