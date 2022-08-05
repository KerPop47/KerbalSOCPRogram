# 3 Segments:

## 1. Server Segment
 - manage interface with KSP API
 - hold planned maneuvers
 - send push notifications for scheduled events
 - manage login (+ server roles?)
 - run opside commands (ie orbit determination, command upload)

## 2. UI Segment
 - multiple pages per role
 - present documentation on how the SOC works
 - each role has its own tab and workflow tools
   - Pilot/Driver
   - SatCon
   - Planner
   - OA
   - Vehicle Engineer (SPH/VAB editor)

## 3. Mod Segment
 - modify physics
   - introduce precession effects
   - introduce orbital perturbations
 - modify comms
   - ground stations have limited visibility
   - upgrades include buying new ground station locations
     - alternatively, ground station part that provides perfect connection if not moving
     - 