# Lesson 10: Staging

Staging means dropping empty structure so the remaining rocket does not have to
carry dead mass.

This is one of the main ways rockets increase total delta-v.

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

The total mission delta-v is roughly the sum of stage delta-v contributions.

That is why rocket design is often a budget problem.

## Step 7: Tiny Hand Check

Suppose a stage has:

```text
wet mass = 1000 kg
dry mass = 200 kg
```

Mass ratio:

```text
1000 / 200 = 5
```

If you can drop a dry stage and start another burn, the next stage no longer
carries those `200 kg`.

## Step 8: Write Your Lesson 10 Notes

Write:

```markdown
# Lesson 10 Notes

## Why Staging Helps

## Before And After Separation

## Mass Terms

Wet mass:
Dry mass:
Payload:

## Tiny Example

mass ratio before staging:
why the next stage benefits:
```

## Done Checklist

You are done when:

- you can explain staging in one sentence
- you can explain why empty stages are dropped
- you can define wet mass, dry mass, and payload
- you can explain why staging helps delta-v
- you can read a simple stage sequence

Stop here. Lesson 11 starts orbital motion.
