# Lesson 09: The Ideal Rocket Equation

The ideal rocket equation connects delta-v, exhaust speed, and mass ratio.

It is one of the most important rocket formulas in engineering.

Why care about it?

Because it explains the brutal tradeoff at the center of rocketry:

```text
more delta-v usually requires much more propellant
```

It shows why rockets are mostly propellant and why mass matters so much.

## Step 1: What Delta-V Means

Delta-v means change in velocity.

It is the total velocity change a rocket can produce by burning propellant.

Mission design often thinks in delta-v budget:

```text
how much velocity change does the mission need?
```

## Step 2: The Ideal Rocket Equation

The classic ideal rocket equation is:

```text
Delta-v = ve * ln(m0 / mf)
```

Where:

```text
Delta-v:
    total change in velocity

ve:
    effective exhaust velocity

m0:
    initial mass

mf:
    final mass after burning propellant

ln:
    natural logarithm
```

If you prefer specific impulse:

```text
Delta-v = Isp * g0 * ln(m0 / mf)
```

## Step 3: Mass Ratio

Mass ratio is:

```text
mass ratio = m0 / mf
```

It compares wet mass to dry mass.

Higher mass ratio usually means more delta-v.

## Step 4: Why The Logarithm Matters

The logarithm means rocket performance grows slowly with mass ratio.

That is a very important design fact.

To get much more delta-v, you need a lot more propellant.

That is why rocket design is hard.

## Step 5: Example

Suppose:

```text
ve = 3000 m/s
m0 = 1000 kg
mf = 500 kg
```

Mass ratio:

```text
m0 / mf = 1000 / 500 = 2
```

Delta-v:

```text
Delta-v = 3000 * ln(2)
Delta-v = 3000 * 0.693
Delta-v = 2079 m/s
```

## Step 6: What The Equation Ignores

This is an ideal equation.

It ignores:

```text
gravity losses
drag losses
throttle effects
guidance losses
changing flight path
real engine non-idealities
```

That does not make it useless.

It makes it a clean first model.

## Step 7: Tiny Hand Check

If:

```text
m0 = 200 kg
mf = 100 kg
```

mass ratio is:

```text
200 / 100 = 2
```

So the rocket has doubled its ideal mass ratio.

## Step 8: Three Quick Questions

Question:

```text
What does delta-v mean?
```

Answer:

```text
change in velocity
```

Question:

```text
If m0 = 200 kg and mf = 100 kg, what is the mass ratio?
```

Answer:

```text
200 / 100 = 2
```

Question:

```text
Why does the logarithm make rocket design hard?
```

Answer:

```text
delta-v grows slowly as mass ratio increases
```

Stop here. Lesson 10 explains staging.
