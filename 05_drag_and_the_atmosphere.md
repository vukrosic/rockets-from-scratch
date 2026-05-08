# Lesson 05: Drag And The Atmosphere

Drag is the force that resists motion through air.

Rockets spend part of their flight in atmosphere, so drag matters.

## Step 1: Drag Direction

Drag points opposite the direction of motion through air.

If the rocket is going up, drag points down.

If the rocket is coming down, drag points up.

## Step 2: What Drag Depends On

Drag depends on things like:

```text
speed
air density
reference area
shape
```

A simple drag model is:

```text
F_drag = (1/2) rho v^2 C_d A
```

Where:

```text
rho:
    air density

v:
    speed through air

C_d:
    drag coefficient

A:
    reference area
```

We use this as a model, not as a construction instruction.

## Step 3: Why Speed Matters So Much

The `v^2` term means drag grows quickly with speed.

If speed doubles:

```text
drag becomes 4 times larger
```

That is why rockets are careful during the thick lower atmosphere.

## Step 4: Example

Suppose:

```text
rho = 1.2 kg/m^3
v = 100 m/s
C_d = 0.5
A = 0.2 m^2
```

Then:

```text
F_drag = (1/2)(1.2)(100^2)(0.5)(0.2)
F_drag = 0.6 * 10000 * 0.1
F_drag = 600 N
```

That is a large force.

## Step 5: Max Dynamic Pressure

Dynamic pressure is:

```text
q = (1/2) rho v^2
```

It is a useful way to think about aerodynamic loading.

As a rocket climbs, air gets thinner, so `rho` decreases.

As speed increases, `v^2` increases.

The combination can produce a maximum load region during flight.

## Step 6: Rockets Leave Dense Air Quickly

Rockets try to reduce drag losses by climbing out of the dense lower atmosphere.

That is one reason launch trajectories and vehicle shape matter.

We do not need a full fluid mechanics course to understand the first effect:

```text
denser air and higher speed make drag harder
```

## Step 7: Tiny Hand Check

If speed goes from `50 m/s` to `100 m/s` in the same air:

```text
drag multiplies by 4
```

because:

```text
100^2 / 50^2 = 4
```

## Step 8: Write Your Lesson 05 Notes

Write:

```markdown
# Lesson 05 Notes

## Drag Direction

## Drag Model

Formula:
What each symbol means:

## Speed Effect

If speed doubles:

## Tiny Example

rho:
v:
C_d:
A:
drag:
```

## Done Checklist

You are done when:

- you can state drag direction
- you can name the drag model variables
- you can explain why drag grows quickly with speed
- you can compute a simple drag example
- you know why dense atmosphere matters

Stop here. Lesson 06 studies rocket stability.
