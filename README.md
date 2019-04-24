# pingpong
Simulate ping pong ball trajectory

## Aim
The goal is to simulate ball and paddle collision to study some basic properties. 

## Facts

- ball weight 2.7 g
- diameter 40mm
- typical speed 12~14 m/s
- maxspeed 110 km/hour, or 30.5 m/s
- ball free drop and bounce on table, return 70% height, 10% speed loss before and after bounce. According to speed loss, the ball should return to (1-0.1)^2 = 0.81 of the original height. The additional loss must be due to air resistance.
- contact time around 1ms

## Approach

The simulation will mostly be based mass spring systems. Ball, rubber, paddle will be modeled as mass springs. 

1. Determine realistic Hook constants for ball, rubber.
