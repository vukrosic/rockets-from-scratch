# Lesson 02: Forces On A Rocket

A rocket's motion is determined by the net force on it.

This lesson turns the first rocket picture into a force picture.

NASA Glenn summarizes rocket flight with four useful forces:

```text
thrust
weight
drag
lift
```

For a simple rocket, lift may be small or zero, but thrust, weight, and drag are
always worth thinking about.

## Step 1: Define Net Force

Net force means the vector sum of all forces acting on the rocket:

```text
F_net = thrust + weight + drag + lift
```

The signs depend on your coordinate system.

If upward is positive:

```text
thrust: positive
weight: negative
drag: usually opposite the velocity
lift: depends on direction
```

Net force tells you acceleration:

```text
F_net = m a
```

## Step 2: Weight

Weight is gravity's force on the rocket:

```text
W = m g
```

Where:

```text
g = 9.8 m/s^2
```

If a rocket has mass `100 kg`, its weight near Earth is:

```text
W = 100 * 9.8 = 980 N
```

Weight points downward.

## Step 3: Thrust

Thrust is the engine force that pushes the rocket forward.

Thrust direction is usually along the rocket body or engine axis.

In launch problems, we often choose upward as positive and treat thrust as
positive if the engine points upward.

Example:

```text
thrust = 1500 N upward
```

## Step 4: Drag

Drag is the force from air resistance.

It points opposite the rocket's motion through the air.

If the rocket is moving upward, drag points downward.

Drag becomes more important when:

```text
speed increases
air is denser
rocket is wider
rocket shape is less streamlined
```

We will model drag more carefully in Lesson 05.

## Step 5: Lift Or Side Force

Lift is an aerodynamic force perpendicular to the airflow.

For a simple straight launch, lift may be ignored at first.

But in reality, airflow and vehicle angle can produce side forces.

We keep it in the force picture because real rockets are not perfectly ideal.

## Step 6: Example Force Balance

Suppose:

```text
thrust = 1500 N upward
weight = 980 N downward
drag = 120 N downward
lift = 0
```

Take upward as positive.

Net force:

```text
F_net = 1500 - 980 - 120
F_net = 400 N upward
```

If mass is `100 kg`, acceleration is:

```text
a = F_net / m
a = 400 / 100
a = 4 m/s^2 upward
```

## Step 7: Liftoff Condition

A rocket begins to accelerate upward when upward thrust exceeds downward
forces.

Simple liftoff condition:

```text
thrust > weight
```

With drag included during the actual climb:

```text
thrust > weight + drag
```

This is why a rocket can have enough thrust to leave the pad but still climb
slowly at first.

## Step 8: Free-Body Diagram

Draw the rocket as a box or point.

Draw:

```text
thrust arrow up
weight arrow down
drag arrow opposite motion
```

If the rocket is rising, drag points down.

That picture is often enough to solve the first rocket force problem.

## Step 9: Tiny Hand Check

A rocket has:

```text
thrust = 1200 N
weight = 900 N
drag = 100 N
```

Upward positive:

```text
F_net = 1200 - 900 - 100
F_net = 200 N upward
```

If the rocket mass is `50 kg`:

```text
a = 200 / 50 = 4 m/s^2 upward
```

## Step 10: Write Your Lesson 02 Notes

Write:

```markdown
# Lesson 02 Notes

## Net Force

Formula:

## Four Forces

Thrust:
Weight:
Drag:
Lift:

## Liftoff

Simple condition:

## Tiny Example

thrust:
weight:
drag:
net force:
acceleration:
```

## Done Checklist

You are done when:

- you can name the four rocket forces
- you can explain net force
- you can compute weight from mass
- you can compute a simple liftoff force balance
- you can draw a basic rocket free-body diagram

Stop here. Lesson 03 studies thrust and impulse.
