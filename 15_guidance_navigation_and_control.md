# Lesson 15: Guidance, Navigation, And Control

A rocket or spacecraft must know where it is, where it should go, and how to
correct its motion.

That is guidance, navigation, and control.

Why care about GNC?

Because physics alone does not make the vehicle follow the mission.

The vehicle needs a loop:

```text
estimate state -> compare to goal -> command correction
```

## Step 1: The Three Words

Guidance:

```text
decides the desired path
```

Navigation:

```text
estimates where the vehicle currently is and how it is moving
```

Control:

```text
turns guidance commands into actual motion changes
```

## Step 2: Feedback Loop

Control systems compare:

```text
desired state
current state
```

Then they correct the difference.

This is feedback.

Rockets and spacecraft need feedback because real flight is not perfectly
predictable.

## Step 3: Sensors And Actuators

Sensors measure things like:

```text
orientation
rate of rotation
position
velocity
```

Actuators change motion, such as by:

```text
gimbaling engines
using small attitude jets
changing aerodynamic surfaces
```

We are keeping this conceptual only.

## Step 4: Stability Versus Control

Passive stability helps the rocket naturally point the right way.

Control helps actively correct and steer it.

Real vehicles often use both.

## Step 5: Tiny Example

Suppose a vehicle is tilting right when it should point straight.

The controller detects the error and commands a correction left.

That is the basic feedback idea.

## Step 6: Why This Matters

Without guidance, navigation, and control:

```text
the rocket may miss the target
the orbit may be wrong
reentry may be unsafe
```

So this is not optional at real scale.

## Step 7: Three Quick Questions

Question:

```text
Which part decides the desired path?
```

Answer:

```text
guidance
```

Question:

```text
Which part estimates the current position and motion?
```

Answer:

```text
navigation
```

Question:

```text
Which part turns commands into actual motion changes?
```

Answer:

```text
control
```

Stop here. Lesson 16 is the mission capstone.
