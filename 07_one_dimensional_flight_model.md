# Lesson 07: One-Dimensional Flight Model

This lesson builds a simple rocket flight model in one dimension.

We will only track:

```text
altitude
velocity
mass
net force
```

That is enough to understand the basic flight path.

## Step 1: State Variables

A state variable is a quantity we update step by step.

For a vertical flight model:

```text
h:
    altitude

v:
    vertical velocity

m:
    mass
```

At each time step, these values can change.

## Step 2: Use Newton's Second Law

At each instant:

```text
a = F_net / m
```

Then update velocity:

```text
v_new = v_old + a Delta t
```

And altitude:

```text
h_new = h_old + v_old Delta t
```

This is a simple time-stepping model.

## Step 3: During Burn

While the engine is on:

```text
thrust is positive upward
mass decreases
```

Net force:

```text
F_net = thrust - weight - drag
```

Then acceleration follows from `F_net / m`.

## Step 4: After Burnout

After propellant is gone:

```text
thrust = 0
```

The rocket coasts under gravity and drag.

If drag is ignored in a first model:

```text
F_net = -weight
```

So velocity decreases upward and eventually becomes zero at apogee.

## Step 5: Example Step

Suppose:

```text
mass = 10 kg
thrust = 150 N
weight = 98 N
drag = 12 N
```

Net force:

```text
F_net = 150 - 98 - 12 = 40 N
```

Acceleration:

```text
a = 40 / 10 = 4 m/s^2
```

If `Delta t = 1 s` and initial velocity is `20 m/s` upward:

```text
v_new = 20 + 4*1 = 24 m/s
```

Altitude update using the old velocity:

```text
h_new = h_old + 20*1
```

That is the basic step-by-step model.

## Step 6: Why This Model Is Useful

This model is simple enough to calculate by hand.

It is also the same pattern used in simulation:

```text
compute force
compute acceleration
update velocity
update position
repeat
```

That is a real engineering habit.

## Step 7: Tiny Hand Check

A rocket at a given step has:

```text
mass = 20 kg
thrust = 300 N
weight = 196 N
drag = 24 N
```

Net force:

```text
F_net = 300 - 196 - 24 = 80 N
```

Acceleration:

```text
a = 80 / 20 = 4 m/s^2
```

If `Delta t = 2 s`, velocity changes by:

```text
Delta v = 4 * 2 = 8 m/s
```

## Step 8: Write Your Lesson 07 Notes

Write:

```markdown
# Lesson 07 Notes

## State Variables

altitude:
velocity:
mass:

## Time Step Update

Acceleration:
Velocity update:
Altitude update:

## During Burn

Net force:

## After Burnout

What changes?
```

## Done Checklist

You are done when:

- you can name the state variables
- you can compute acceleration from net force
- you can update velocity and altitude
- you can describe burn and coast phases
- you understand the step-by-step flight model

Stop here. Lesson 08 explains specific impulse.
