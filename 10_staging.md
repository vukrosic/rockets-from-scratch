# Lesson 10: Staging

Staging means dropping empty structure so the remaining rocket does not have to
carry dead mass.

This is one of the main ways rockets increase total delta-v.

Why care about staging?

Because the rocket equation punishes dead mass.

An empty tank, empty engine section, or empty booster still has mass.

If you keep carrying it, every later burn must accelerate that useless mass.

## Step 1: Why Staging Helps

The rocket equation depends on mass ratio.

If you throw away empty hardware after it is no longer useful, the next stage
has a better mass ratio.

That means more delta-v for the remaining vehicle.

## Step 2: Simple Staging Picture

Before staging:

```text
rocket = first stage + upper stage + payload + propellant
```

After first stage burnout and separation:

```text
remaining rocket = upper stage + payload + propellant
```

The empty first stage is gone.

## Step 3: Why Not Keep Everything

If you keep the empty stage attached, the upper stage must accelerate dead mass.

That wastes delta-v.

Staging is the engineering answer.

## Step 4: Multi-Stage Mission Flow

Common simplified flow:

```text
lift off
first stage burns
first stage drops
second stage burns
payload reaches target
```

Each stage is optimized for its part of the mission.

## Step 5: Stage Mass Terms

Useful terms:

```text
wet mass:
    stage plus propellant

dry mass:
    empty stage after propellant is gone

payload:
    what the rocket is carrying
```

The stage dry mass still matters because it is dead weight until separation.

## Step 6: Delta-V By Stage

Each stage has its own mass ratio and exhaust performance.

For a real stage calculation, the mass ratio should include everything that
stage is pushing during that burn:

```text
stage
upper stages
payload
remaining propellant
```

The total mission delta-v is roughly the sum of the stage delta-v
contributions.

That is why rocket design is often a budget problem.

## Step 7: Tiny Hand Check

Suppose a stage alone has:

```text
wet mass = 1000 kg
dry mass = 200 kg
```

Mass ratio:

```text
1000 / 200 = 5
```

That simple number describes the stage by itself.

During an actual launch, the stage also carries upper stages and payload.

The key staging idea is still:

```text
after separation, the next stage no longer carries the empty first stage
```

## Step 8: Three Quick Questions

Question:

```text
Why do rockets drop empty stages?
```

Answer:

```text
so later stages do not have to accelerate dead mass
```

Question:

```text
What does dry mass mean?
```

Answer:

```text
the stage mass after propellant is gone
```

Question:

```text
How do stage delta-v contributions combine in a simple mission budget?
```

Answer:

```text
they are roughly added together
```

Stop here. Lesson 11 starts orbital motion.
