# Lesson 03: Thrust And Impulse

Thrust is a force.

Impulse is that force accumulated over time.

Why care about impulse?

Because thrust alone tells you only the push at one moment.

Impulse tells you the total push delivered across the burn.

That is what changes the rocket's momentum.

If you want to compare two burns, you need both:

```text
how hard the engine pushes
how long it pushes
```

This lesson teaches the difference between:

```text
how hard the rocket is pushed
how long the rocket is pushed
```

Both matter.

## Step 1: Thrust Is The Push Right Now

Thrust is measured in newtons:

```text
N = kg m/s^2
```

If a rocket has:

```text
thrust = 1000 N
```

that means the engine is pushing with a force of `1000 N` at that moment.

But a rocket engine does not only push once.

It pushes for some amount of time.

That is why we need impulse.

## Step 2: Impulse Is Push Over Time

Impulse measures how much force is delivered over a time interval.

For constant force:

```text
J = F Delta t
```

Where:

```text
J:
    impulse

F:
    force

Delta t:
    time interval
```

Impulse unit:

```text
N s
```

Read that as:

```text
newton-seconds
```

So if a rocket engine pushes with `50 N` for `4 s`:

```text
J = 50 * 4
J = 200 N s
```

That means the engine delivered `200 newton-seconds` of push.

## Step 3: Impulse Changes Momentum

Impulse is useful because it tells you how much momentum changes:

```text
J = Delta p
```

This is the bridge back to Lesson 01.

Lesson 01 said rockets work by changing momentum:

```text
exhaust gains backward momentum
rocket gains forward momentum
```

Impulse is the amount of momentum change caused by a force over time.

So a short way to say it is:

```text
force over time -> impulse -> momentum change
```

## Step 4: Same Thrust, Longer Time

Suppose one engine pushes with:

```text
F = 80 N
t = 2 s
```

Impulse:

```text
J = 80 * 2
J = 160 N s
```

Now keep the same force, but push for longer:

```text
F = 80 N
t = 5 s
```

Impulse:

```text
J = 80 * 5
J = 400 N s
```

The force did not change.

The burn lasted longer.

So the total push was larger.

## Step 5: Thrust Curves

Real thrust is often not perfectly constant.

It may:

```text
rise
peak
fall
```

A thrust curve is a graph of:

```text
thrust vs time
```

If thrust is on the vertical axis and time is on the horizontal axis, then
impulse is the area under the curve.

For a constant thrust example, the area is just a rectangle:

```text
area = height * width
area = thrust * time
```

That is the same as:

```text
J = F t
```

For a changing thrust curve, the idea is the same:

```text
total impulse = total area under the thrust curve
```

You do not need calculus yet.

Just remember:

```text
taller curve -> more impulse
wider curve -> more impulse
```

## Step 6: Peak Thrust Is Not Total Impulse

Peak thrust is the largest force reached at one moment.

Total impulse is the total force delivered across the whole burn.

These are different.

Imagine two engines:

```text
Engine A:
    high peak thrust
    short burn

Engine B:
    lower thrust
    long burn
```

Engine A may feel like a sharp kick.

Engine B may feel like a long steady push.

Either one could have more total impulse depending on the area under its thrust
curve.

That is why you cannot judge a rocket engine only by peak thrust.

You also need burn time and total impulse.

## Step 7: Average Thrust

If you know total impulse and burn time, average thrust is:

```text
average thrust = total impulse / burn time
```

Example:

```text
total impulse = 200 N s
burn time = 4 s
```

Then:

```text
average thrust = 200 / 4
average thrust = 50 N
```

Average thrust means:

```text
the constant thrust that would give the same total impulse
```

It does not mean the engine actually produced exactly `50 N` every moment.

It is a useful simplification.

## Step 8: Three Quick Questions

Question:

```text
If thrust is 30 N and burn time is 6 s, what is total impulse?
```

Answer:

```text
J = 30 * 6 = 180 N s
```

Question:

```text
On a thrust curve, what does the area under the curve represent?
```

Answer:

```text
total impulse
```

Question:

```text
Can an engine with lower peak thrust have more total impulse than an engine
with higher peak thrust?
```

Answer:

```text
yes, if it pushes for long enough
```

Stop here. Lesson 04 studies mass, weight, and thrust-to-weight ratio.
