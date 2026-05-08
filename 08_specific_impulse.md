# Lesson 08: Specific Impulse

Specific impulse is a standard way to compare rocket propulsion performance.

It tells you how much impulse you get per unit of propellant weight flow.

## Step 1: Why We Need A New Metric

Thrust alone is not enough.

Two engines can produce the same thrust but use propellant differently.

One can be efficient.

One can be wasteful.

Specific impulse helps compare that.

## Step 2: Specific Impulse Definition

A common definition is:

```text
Isp = thrust / (propellant weight flow)
```

It is often reported in seconds.

Another useful idea is:

```text
effective exhaust velocity = Isp * g0
```

Where:

```text
g0 = 9.8 m/s^2
```

## Step 3: What Seconds Means Here

Seconds may look strange for engine performance.

The unit comes from dividing force by weight flow.

The result is a time scale related to exhaust efficiency.

Higher `Isp` means better use of propellant in the idealized comparison.

## Step 4: High Isp Is Not The Same As High Thrust

An engine can have:

```text
high Isp
low thrust
```

or:

```text
lower Isp
higher thrust
```

That is because efficiency and raw push are different goals.

## Step 5: Simple Comparison

Suppose two engines both have the same propellant weight flow.

Engine A produces more thrust than Engine B.

Then Engine A has higher specific impulse in the simple comparison.

That means it uses propellant more effectively.

## Step 6: Why Mission Needs Matter

Some missions care about:

```text
strong liftoff thrust
```

Some missions care about:

```text
long efficient burns in space
```

No single engine is best at everything.

That is why propulsion choices depend on mission phase.

## Step 7: Tiny Hand Check

If a propulsion system gives the same thrust with less propellant weight flow,
what happens to `Isp`?

Answer:

```text
Isp goes up
```

## Step 8: Write Your Lesson 08 Notes

Write:

```markdown
# Lesson 08 Notes

## Specific Impulse

What it compares:

## Isp Units

Why seconds show up:

## Thrust vs Isp

Are they the same thing?

## Mission Tradeoff

Why does mission phase matter?
```

## Done Checklist

You are done when:

- you can explain why we need specific impulse
- you can describe what higher Isp means
- you can explain why Isp and thrust are different
- you can connect Isp to mission needs
- you know it is a comparison metric, not the whole engine story

Stop here. Lesson 09 introduces the rocket equation.
