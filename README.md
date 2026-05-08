# Rockets From Scratch

![Rocket forces and flight model](images/rocket-forces-flight-model.png)

This course teaches rockets as physics and engineering models.

It is not a propellant-making or engine-construction manual. We will avoid
hazardous build instructions and focus on safe, conceptual, mathematical, and
simulation-friendly learning.

The goal is to understand:

```text
forces
thrust
mass changing during flight
aerodynamics
stability
delta-v
staging
orbits
mission design
```

## Fact-Checked Course Spine

This plan is based on the following high-level facts from NASA sources:

- A rocket in flight is modeled with four main forces: weight, thrust, lift, and drag.
- Rocket motion is predicted by summing forces and applying Newton's laws.
- Rocket thrust comes from accelerating mass backward and includes momentum and pressure terms.
- Specific impulse is a standard way to compare rocket propulsion performance.
- The ideal rocket equation connects delta-v, exhaust velocity or specific impulse, and mass ratio.
- Hohmann transfer orbits are a standard two-burn way to transfer between circular orbits in the same plane.

Sources are listed at the end of this README.

## Course Principles

Each lesson should be readable from top to bottom.

Every lesson should follow this pattern:

```text
start with intuition
define the quantities
draw the simple model
do one small calculation
check units
name the assumption
```

No external dependencies are required for the first version. If code or
simulation is added later, it should be optional.

## Lessons

### 01. [What A Rocket Is Actually Doing](01_what_a_rocket_is_actually_doing.md)

Core idea:

```text
a rocket accelerates mass backward so the rocket accelerates forward
```

Teach:

- rocket as a momentum machine
- system vs surroundings
- why rockets do not need air to push against
- Newton's third law without the usual vague explanation
- safe scope of the course

Tiny check:

```text
If exhaust goes backward, which way does the rocket accelerate?
```

### 02. Forces On A Rocket

Core idea:

```text
motion comes from net force
```

Teach:

- thrust
- weight
- drag
- lift or aerodynamic side force
- net force
- free-body diagrams
- why forces change during flight

Tiny check:

```text
If thrust is 1200 N upward and weight is 900 N downward, what is net force before drag?
```

### 03. Thrust And Impulse

Core idea:

```text
thrust is force; impulse is force accumulated over time
```

Teach:

- thrust in newtons
- burn time
- total impulse
- average thrust
- thrust curve as force vs time
- why peak thrust and total impulse are different

Tiny check:

```text
Average thrust = 50 N, burn time = 4 s. Total impulse = ?
```

### 04. Mass, Weight, And Thrust-To-Weight Ratio

Core idea:

```text
rockets get lighter as propellant is used
```

Teach:

- mass vs weight
- wet mass
- dry mass
- propellant mass
- thrust-to-weight ratio
- liftoff condition

Tiny check:

```text
If weight is 1000 N and thrust is 1500 N, is liftoff possible in the simple model?
```

### 05. Drag And The Atmosphere

Core idea:

```text
air resistance grows strongly with speed
```

Teach:

- drag direction
- drag depends on speed, density, area, shape
- why max dynamic pressure matters
- why rockets leave dense atmosphere quickly
- assumptions in simple drag models

Tiny check:

```text
If speed doubles, what happens to drag in a v^2 drag model?
```

### 06. Stability: Center Of Mass And Center Of Pressure

Core idea:

```text
a rocket is stable when aerodynamic forces tend to point it back into the airflow
```

Teach:

- center of mass
- center of pressure
- fins
- restoring tendency
- why long skinny rockets can still tumble
- stability as a design constraint

Tiny check:

```text
Which should usually be farther forward for passive stability: center of mass or center of pressure?
```

### 07. One-Dimensional Flight Model

Core idea:

```text
altitude and velocity can be stepped forward with net force
```

Teach:

- vertical motion
- acceleration from net force
- velocity update
- altitude update
- changing mass
- burnout
- coast
- apogee

Tiny check:

```text
If acceleration is positive upward for one second, what happens to velocity?
```

### 08. Specific Impulse

Core idea:

```text
specific impulse measures propulsion efficiency
```

Teach:

- impulse per propellant weight flow
- seconds as a unit of specific impulse
- relation to effective exhaust velocity
- why high Isp is not the same as high thrust
- tradeoff between efficiency and mission need

Tiny check:

```text
If two engines use propellant at the same weight flow, which one gives more thrust: higher or lower Isp?
```

### 09. The Ideal Rocket Equation

Core idea:

```text
delta-v depends logarithmically on mass ratio
```

Teach:

- delta-v
- exhaust velocity
- mass ratio
- wet mass and dry mass
- why carrying propellant to carry propellant is painful
- what the ideal equation ignores

Tiny check:

```text
If wet mass is 100 kg and dry mass is 50 kg, what is mass ratio?
```

### 10. Staging

Core idea:

```text
throw away empty structure so later propellant does not carry dead mass
```

Teach:

- why staging helps
- stage dry mass
- stage propellant mass
- payload
- serial staging
- delta-v budget by stage
- tradeoffs and complexity

Tiny check:

```text
Why does dropping an empty first stage help the upper stage?
```

### 11. Getting To Orbit

Core idea:

```text
orbit is falling around Earth fast enough to keep missing the ground
```

Teach:

- vertical launch is not enough
- horizontal speed
- gravity losses
- drag losses
- circular orbit intuition
- why orbit is about speed, not just altitude

Tiny check:

```text
At the same altitude, what mainly separates a high arc from orbit?
```

### 12. Orbital Energy And Delta-V

Core idea:

```text
spacecraft maneuver by changing velocity
```

Teach:

- circular orbit speed intuition
- burns change orbit shape
- prograde burn
- retrograde burn
- apoapsis and periapsis
- delta-v as mission currency

Tiny check:

```text
What does a prograde burn generally do to the opposite side of the orbit?
```

### 13. Hohmann Transfers

Core idea:

```text
two well-timed burns can transfer between circular orbits
```

Teach:

- lower circular orbit
- transfer ellipse
- higher circular orbit
- first burn raises apoapsis
- second burn circularizes
- why timing matters

Tiny check:

```text
How many main burns does the simple Hohmann transfer use?
```

### 14. Reentry And Heating

Core idea:

```text
reentry converts orbital kinetic energy into heat and atmospheric motion
```

Teach:

- kinetic energy at orbital speed
- drag as energy transfer
- heating
- blunt bodies
- heat shields
- why shallow vs steep entry matters

Tiny check:

```text
Why is reentry not just falling down slowly?
```

### 15. Guidance, Navigation, And Control

Core idea:

```text
a rocket must know where it is, where it is pointing, and how to correct itself
```

Teach:

- guidance
- navigation
- control
- sensors
- actuators
- gimbals
- reaction control
- feedback loops

Tiny check:

```text
Which part estimates the vehicle state: guidance, navigation, or control?
```

### 16. Mission Design Capstone

Core idea:

```text
a mission is a sequence of models connected by assumptions
```

Teach:

- define mission goal
- payload
- environment
- phases of flight
- delta-v budget
- mass budget
- risk and assumptions
- final explanation

Capstone:

```text
Design a safe paper mission profile:
ground -> ascent -> coast/orbit -> transfer -> arrival/reentry
```

No propellant recipes. No hazardous construction. The output is an engineering
explanation, not a build manual.

## Recommended First Build Path

If turning this into full lessons, write them in this order:

```text
1-4:
    forces, thrust, impulse, mass

5-7:
    atmosphere, stability, vertical flight model

8-10:
    Isp, rocket equation, staging

11-13:
    orbit, delta-v, Hohmann transfer

14-16:
    reentry, control, mission capstone
```

This keeps the course from becoming random rocket trivia.

It builds from Newton's laws to mission design.

## Sources

- NASA Glenn Research Center, [Four Forces on a Rocket](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/four-rocket-forces/)
- NASA Glenn Research Center, [Basic Rocket Motion](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/basic-rocket-motion/)
- NASA Glenn Research Center, [Specific Impulse](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/specific-impulse/)
- NASA Glenn Research Center, [Thrust Equations Summary](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/thrust-equations-summary/)
- NASA Glenn Research Center, [Ideal Rocket Equation](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/ideal-rocket-equation/)
- NASA Science, [Hohmann Transfer Orbit](https://science.nasa.gov/resource/hohmann-transfer-orbit/)
- NASA Science, [Basics of Space Flight: Trajectories](https://science.nasa.gov/learn/basics-of-space-flight/chapter4-1/)
