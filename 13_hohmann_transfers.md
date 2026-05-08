# Lesson 13: Hohmann Transfers

A Hohmann transfer is a standard two-burn way to move between circular orbits in
the same plane.

It is one of the simplest useful orbital maneuvers.

Why care about it?

Because it is the first clean example of using orbital mechanics instead of
just "pointing at the destination."

A spacecraft does not drive through space in a straight line.

It changes orbit, coasts, then changes orbit again.

## Step 1: The Two-Burn Idea

The basic plan:

```text
burn 1:
    enter transfer ellipse

burn 2:
    circularize at the destination orbit
```

That is the core Hohmann transfer.

## Step 2: First Burn

The first burn is usually prograde.

It raises the opposite side of the orbit so the craft follows an ellipse.

The new path touches both the starting orbit and the target orbit.

## Step 3: Coast Along The Ellipse

After the first burn, the spacecraft coasts.

No second burn yet.

The orbit naturally carries it to the destination side.

## Step 4: Second Burn

At the destination point, the spacecraft burns again to circularize.

That makes the new orbit match the destination circular orbit.

## Step 5: Why It Is Efficient

The Hohmann transfer is efficient because it uses orbital geometry well.

It is not the only transfer, but it is a standard baseline for simple missions.

## Step 6: Same Plane Assumption

The classic Hohmann transfer assumes the orbits are in the same plane.

If the orbital planes differ, additional delta-v is needed.

That is a more advanced topic.

## Step 7: Tiny Hand Check

How many main burns are in a basic Hohmann transfer?

Answer:

```text
2
```

## Step 8: Three Quick Questions

Question:

```text
How many main burns are in a basic Hohmann transfer?
```

Answer:

```text
2
```

Question:

```text
What happens after the first burn?
```

Answer:

```text
the spacecraft coasts along a transfer ellipse
```

Question:

```text
What does the second burn do?
```

Answer:

```text
it circularizes at the destination orbit
```

Stop here. Lesson 14 covers reentry and heating.
