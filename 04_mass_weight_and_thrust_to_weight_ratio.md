# Lesson 04: Mass, Weight, And Thrust-To-Weight Ratio

Rockets get lighter as propellant is used.

That one fact changes almost everything.

Why care about mass and thrust-to-weight ratio?

Because before you think about orbit, staging, or mission design, you need to
answer a simpler question:

```text
is thrust bigger than the rocket's weight?
```

If the answer is no, the rocket does not lift off in the simple vertical model.

If the answer is yes, the next question is:

```text
how much bigger?
```

That is what thrust-to-weight ratio measures.

## Step 1: Mass Is Not Weight

Mass tells you how much matter and inertia an object has.

Inertia means resistance to acceleration.

A more massive rocket is harder to speed up, slow down, or turn.

Mass is measured in:

```text
kg
```

Weight is different.

Weight is the gravitational force on that mass:

```text
W = m g
```

Near Earth's surface:

```text
g = 9.8 m/s^2
```

Weight is measured in:

```text
N
```

Example:

```text
mass = 100 kg
weight = 100 * 9.8
weight = 980 N
```

So:

```text
mass:
    how much inertia the rocket has

weight:
    how hard gravity pulls on it
```

## Step 2: Wet Mass And Dry Mass

Wet mass means:

```text
rocket + propellant
```

Dry mass means:

```text
rocket after propellant is gone
```

The difference is propellant mass:

```text
propellant mass = wet mass - dry mass
```

Example:

```text
wet mass = 500 kg
dry mass = 180 kg
```

Then:

```text
propellant mass = 500 - 180
propellant mass = 320 kg
```

This matters because rockets throw propellant away as exhaust.

During flight:

```text
propellant decreases
rocket mass decreases
weight decreases
```

The rocket is not the same mass at the start and end of the burn.

## Step 3: Thrust-To-Weight Ratio

Thrust-to-weight ratio compares upward engine force to downward gravitational
force.

Formula:

```text
TWR = thrust / weight
```

If:

```text
TWR = 1
```

then thrust equals weight.

In the simple vertical model, that means the rocket can barely hold itself up.

If:

```text
TWR > 1
```

then thrust is larger than weight, so liftoff is possible in the simple model.

If:

```text
TWR < 1
```

then thrust is smaller than weight, so the rocket cannot lift off vertically in
the simple model.

## Step 4: Example

Suppose:

```text
mass = 200 kg
thrust = 3000 N
```

First compute weight:

```text
W = m g
W = 200 * 9.8
W = 1960 N
```

Now compute TWR:

```text
TWR = thrust / weight
TWR = 3000 / 1960
TWR = 1.53
```

That means thrust is about `1.53` times the rocket's weight.

In the simple model:

```text
TWR > 1 -> liftoff is possible
```

## Step 5: TWR Also Hints At Acceleration

TWR does not directly give acceleration, but it gives intuition.

If `TWR` is barely above `1`, thrust is only slightly bigger than weight.

The rocket lifts off slowly.

If `TWR` is much bigger than `1`, thrust is much bigger than weight.

The rocket accelerates more strongly.

You can see this from net force:

```text
F_net = thrust - weight
```

Using the previous example:

```text
F_net = 3000 - 1960
F_net = 1040 N upward
```

Then:

```text
a = F_net / m
a = 1040 / 200
a = 5.2 m/s^2 upward
```

So TWR is a quick first check, but net force gives the actual acceleration.

## Step 6: TWR Changes During Flight

At liftoff, the rocket is heavy because it still has all its propellant.

Later, after burning propellant, the rocket is lighter.

If thrust stays similar while weight decreases:

```text
TWR increases
```

That means the rocket can accelerate harder later in the burn.

This is why rocket acceleration often increases as propellant is used.

Same engine.

Less mass.

More acceleration.

## Step 7: Liftoff Is Not Only TWR

TWR is a simple first model.

Real flight also includes:

```text
drag
wind
vehicle tilt
changing thrust
changing mass
```

But TWR is still useful because it answers the first big question:

```text
does the engine force beat gravity?
```

For now, remember:

```text
TWR = thrust / weight
TWR > 1 means thrust is bigger than weight
```

## Step 8: Three Quick Questions

Question:

```text
A rocket has mass 100 kg. What is its weight near Earth?
```

Answer:

```text
W = 100 * 9.8 = 980 N
```

Question:

```text
A rocket has thrust 1500 N and weight 1000 N. What is its TWR?
```

Answer:

```text
TWR = 1500 / 1000 = 1.5
```

Question:

```text
If propellant burns and thrust stays similar, what happens to TWR?
```

Answer:

```text
TWR increases
```

Stop here. Lesson 05 studies drag and the atmosphere.
