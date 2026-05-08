# Lesson 13: Hohmann Transfers

A Hohmann transfer is a standard two-burn way to move between circular orbits in
the same plane.

It is one of the simplest useful orbital maneuvers.

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

## Step 8: Write Your Lesson 13 Notes

Write:

```markdown
# Lesson 13 Notes

## Hohmann Transfer

What is it?

## Burn 1

## Burn 2

## Assumptions

Same plane:
Circular start and end:
```

## Done Checklist

You are done when:

- you can explain the two-burn structure
- you can explain the coasting ellipse
- you can explain circularization
- you can state the same-plane assumption
- you know Hohmann transfer is a standard baseline maneuver

Stop here. Lesson 14 covers reentry and heating.
