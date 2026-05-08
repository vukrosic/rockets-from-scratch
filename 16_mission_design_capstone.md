# Lesson 16: Mission Design Capstone

A rocket mission is a chain of models and assumptions.

This capstone ties the whole course together.

Why care about mission design?

Because rockets are not solved one formula at a time.

Every mission is a connected system:

```text
goal -> phases -> assumptions -> forces -> delta-v -> mass -> risk
```

## Step 1: Start With The Mission

Pick a mission goal:

```text
reach a target altitude
reach orbit
transfer orbit
reenter safely
```

Then ask:

```text
what delta-v is needed?
what mass budget is available?
what atmosphere effects matter?
what control is needed?
```

## Step 2: Break The Mission Into Phases

Example mission phases:

```text
liftoff
ascent
coast
orbit insertion
transfer
reentry
landing or recovery
```

Each phase uses a different model.

## Step 3: State The Assumptions

An engineer should always name the assumptions.

Examples:

```text
ignore wind
ignore rotation of Earth for a first pass
assume constant gravity in the first model
ignore small drag terms in space
use a simple delta-v budget
```

Then refine later if needed.

## Step 4: Build A Delta-V Budget

Write the mission as a sum of burns:

```text
burn 1 + burn 2 + burn 3 = total mission delta-v
```

Then compare that to what the rocket can deliver.

If the budget is too large, the mission needs redesign.

## Step 5: Build A Mass Budget

Mass budgeting asks:

```text
how much payload
how much propellant
how much dry structure
how many stages
```

This is where the rocket equation and staging become practical.

## Step 6: Final Engineering Loop

The course has taught a full loop:

```text
forces
motion
drag
stability
impulse
specific impulse
rocket equation
staging
orbit
reentry
control
mission design
```

That is enough to understand a lot of real rocket engineering at a first-pass
level.

## Step 7: Example Mission Model

A first-pass mission model can be very short:

```markdown
Mission:
    reach a low circular orbit

Goal:
    clear the atmosphere, build horizontal velocity, insert into orbit

Main phases:
    liftoff
    ascent
    gravity turn
    stage separation
    orbit insertion

Main assumptions:
    simple drag model
    simple delta-v budget
    staged vehicle

Main risks:
    drag losses
    gravity losses
    stability and control errors
```

Do not make it a construction plan.

Make it a model and explanation.

## Step 8: Three Quick Questions

Question:

```text
Why do engineers split a mission into phases?
```

Answer:

```text
different phases use different models and constraints
```

Question:

```text
What should you do when using a simplified model?
```

Answer:

```text
state the assumptions
```

Question:

```text
What connects rocket equation thinking to mission design?
```

Answer:

```text
delta-v and mass budgets
```

Stop here. You now have a complete first-pass rockets from scratch course.
