> 1. Does perihelion advance happen only in Mercury, or all planets, and in general, for any astro object revolving around any other astro object?
>
> 2. Why only Mercury was the exception demanding explanation in terms of gen relativity?

Great questions. The short answers are:

1. **Perihelion advance happens for all orbiting bodies.**
2. **Mercury was special because the amount of its perihelion advance could not be fully explained by Newtonian physics.**

Here's the full picture.

### 1. Does perihelion advance happen only for Mercury?

No. Any object moving in a bound orbit around another massive object can experience **apsidal precession** (the gradual rotation of the orbit's major axis). Around the Sun, this is called **perihelion precession**.

This applies to:

* Mercury
* Venus
* Earth
* Mars
* Asteroids
* Comets
* Exoplanets around other stars
* Binary stars
* Even stars orbiting a supermassive black hole

So the phenomenon is completely general.

The precession can arise from several causes:

* **Gravitational perturbations** from other bodies (the largest effect for most planets).
* The central body's **non-spherical shape** (if it is oblate).
* **General relativity**, which predicts an additional advance because spacetime is curved.
* Other small effects such as tidal forces in some systems.

---

### 2. Why was Mercury the famous case?

Astronomers in the 19th century measured Mercury's perihelion very precisely.

Its perihelion advances by about **574 arcseconds per century**.

Most of that can be explained using Newtonian gravity:

* Gravitational pulls from Venus, Earth, Jupiter, and the other planets account for nearly all of it.
* Effects like the precession of Earth's equinoxes also contribute to the observed motion.

After accounting for all known Newtonian effects, there remained an unexplained residual of about

**43 arcseconds per century.**

That tiny discrepancy persisted despite increasingly careful calculations.

When Albert Einstein developed general relativity in 1915, one of its first major successes was predicting **exactly** this additional 43 arcseconds per century, with no arbitrary adjustment. This agreement became one of the classic early tests of the theory.

---

### Why wasn't Earth considered a problem?

General relativity also predicts perihelion precession for Earth and the other planets.

Approximate relativistic contributions are:

* Mercury: **43 arcseconds/century**
* Venus: **8.6 arcseconds/century**
* Earth: **3.8 arcseconds/century**
* Mars: **1.35 arcseconds/century**

Mercury's effect is much larger because:

* It is **closest to the Sun**, where spacetime curvature is strongest.
* It has the **most eccentric** orbit among the major planets, which increases the relativistic effect.

For the other planets, the relativistic contribution was much smaller and was buried within observational uncertainties for a long time.

---

### Is this only a Solar System phenomenon?

Not at all.

General relativity predicts orbital precession for **any** sufficiently compact gravitational system.

For example:

* Binary pulsars show relativistic periastron advance much larger than Mercury's.
* Stars orbiting the Sagittarius A* exhibit measurable relativistic precession.
* Some close-in exoplanets are also expected to show detectable relativistic apsidal precession.

In these strong-gravity systems, the effect can be thousands of times larger than in the Solar System.

So Mercury wasn't unique because it precesses—it was unique because its **remaining unexplained 43 arcseconds per century** provided a clear observational puzzle that general relativity solved precisely.

===
===

> How does TGR explain the 43 secs, rather how does TGR contribute to apsidal precession?

This gets to one of the most beautiful predictions of general relativity. The key idea is that **in Newtonian gravity, the Sun's gravitational field is exactly an inverse-square force, so bound orbits are perfect ellipses. In general relativity, gravity is not a force in the same sense—it's the curvature of spacetime—and that changes the orbit slightly.**

### Newtonian picture

In Newtonian gravity,

$$
F=\frac{GMm}{r^2}.
$$

This produces the familiar elliptical orbits described by Johannes Kepler. After one complete revolution, the planet returns to exactly the same perihelion.

So an isolated Sun and Mercury would produce **no perihelion advance** in Newtonian mechanics.

---

### General relativity's picture

General relativity says that the Sun curves the spacetime around it.

Mercury follows the straightest possible path (a **geodesic**) in this curved spacetime.

The geometry outside a spherical, non-rotating Sun is described by the Schwarzschild metric.

When you solve the geodesic equations for Mercury, the orbit equation becomes

$$\frac{d^2u}{d\phi^2}+u = \frac{GM}{h^2} + \frac{3GM}{c^2}u^2$$,

where

* (u=1/r),
* (h) is the angular momentum per unit mass,
* (c) is the speed of light.

Notice the extra term

$$
\frac{3GM}{c^2}u^2.
$$

That term **does not exist in Newtonian gravity.**

It is the relativistic correction arising from spacetime curvature.

---

### Why does this cause precession?

In Newtonian gravity, the solution is

$$
u=\frac{GM}{h^2}(1+e\cos\phi),
$$

which repeats perfectly every (2\pi) radians.

With the relativistic correction, the solution becomes approximately

$$
u\simeq
\frac{GM}{h^2}
\left[1+e\cos((1-\delta)\phi)\right],
$$

where ($`\delta`$) is a tiny positive number.

Now the cosine repeats after

$$
\phi=\frac{2\pi}{1-\delta}
\approx
2\pi+2\pi\delta.
$$

Instead of closing after one revolution, the orbit must rotate a tiny extra angle before repeating.

The ellipse therefore slowly turns.

Imagine drawing an ellipse on transparent paper and rotating it by a tiny angle after every orbit. After many revolutions, the perihelion traces out a slow rotation around the Sun.

---

### The prediction

General relativity predicts the advance per orbit to be

$$
\boxed{\Delta\phi =
\frac{6\pi GM}
{a(1-e^2)c^2}},
$$

where

* (a) is the semi-major axis,
* (e) is the eccentricity.

This formula has **no adjustable parameters**. Plug in Mercury's measured orbit and the Sun's mass.

You get

$$
\Delta\phi
\approx
0.103\ \text{arcseconds per orbit}.
$$

Mercury completes about **415 orbits per century**, so

$$
415\times0.103
\approx
43\ \text{arcseconds per century},
$$

exactly the unexplained residual.

---

### An intuitive picture

A useful analogy is to compare a flat sheet of paper with a gently curved bowl.

* On a flat sheet, if you draw an ellipse, it closes perfectly.
* On a curved surface, trying to follow the "same" geometric path doesn't bring you back to exactly the same orientation. The path is slightly twisted by the surface's curvature.

Mercury's orbit is like the second case: because spacetime around the Sun is curved, the "ellipse" is not a closed curve. The closest point to the Sun shifts a tiny amount each revolution.

This is one of the few situations where the geometry of spacetime has a directly observable effect on planetary motion. The remarkable point is that the amount of this shift follows from Einstein's equations alone, yielding the precise (43) arcseconds per century without any extra assumptions.

===
===

> 1. What do you mean by "This formula has no adjustable parameters."? a and e are the orbital parameters, different for different planets, no? Or, even if you consider only one planet, then also, what would be a possible adjustable param, like an initial condition?
> 
> 2. Please explain: "On a curved surface, trying to follow the "same" geometric path". What kind of curved surface, all kinds or certain kinds? Let's say for surface of a sphere, you can certainly draw an "ellipse" which closes perfectly. Same for the surface of a hyperboloid too, no?

These are exactly the right questions. They touch on what made Einstein's result so convincing and on where the surface analogy starts to break down.

## 1. What does "no adjustable parameters" mean?

You're correct that (a) (semi-major axis) and (e) (eccentricity) differ from planet to planet. But they are **measured independently** from observations of the orbit—they are not chosen to make the theory fit.

The GR prediction is

$$
\Delta\phi=\frac{6\pi GM}{a(1-e^2)c^2}.
$$

Every quantity on the right-hand side is already known:

* (G): measured in the lab.
* (M): the Sun's mass, determined independently (e.g., from planetary motion).
* (a): measured from Mercury's orbit.
* (e): measured from Mercury's orbit.
* (c): measured in the lab.

There is **nothing left to tune**.

### What would an adjustable parameter look like?

Suppose Einstein's theory had instead predicted

$$
\Delta\phi =
k\frac{6\pi GM}{a(1-e^2)c^2},
$$

where (k) was an unknown constant.

Then one could simply choose

$$
k=0.998,\quad 1.02,\quad 1.15,\ldots
$$

until the prediction matched Mercury.

That would be "fitting the data."

Instead, GR predicts **(k=1)** automatically.

Similarly, the initial position of Mercury or where you start counting angles is **not** an adjustable parameter. Changing the initial conditions only rotates the entire orbit; it doesn't change how much the perihelion advances each orbit.

This is what physicists mean when they say the prediction was parameter-free.

---

## 2. About the curved-surface analogy

You're also right to challenge the wording.

I said:

> "On a curved surface, trying to follow the same geometric path..."

That was imprecise.

A better statement is:

> On a curved surface, the analogue of a "straight line" is a **geodesic**, and geodesics generally behave differently from straight lines in Euclidean geometry.

But even that isn't enough to explain Mercury.

### Your sphere example

You said:

> On a sphere, I can draw an ellipse that closes perfectly.

Exactly.

In fact, you can draw infinitely many closed curves on a sphere.

The important point is that **Mercury is not free to follow an arbitrary curve.**

Its path is determined by Einstein's equations.

The orbit is the solution of a differential equation.

---

### Why the analogy is limited

Suppose we have:

* a plane,
* a sphere,
* a saddle (hyperbolic surface).

On each of them, you can draw closed ellipses if you want.

Nature doesn't let Mercury choose one.

Instead, the equations governing motion determine a particular trajectory.

Changing the geometry changes those equations.

That's the real origin of the precession.

---

## A better analogy

Imagine a harmonic oscillator.

If

$$
x''+\omega^2x=0,
$$

every oscillation has exactly the same period.

Now perturb it slightly:

$$
x''+\omega^2x+\varepsilon x^3=0.
$$

The oscillation is still periodic, but its frequency changes slightly.

Nothing dramatic happened.

A tiny extra term changed the phase a little every cycle.

Mercury is similar.

Newton gives one orbit equation.

GR adds a tiny correction.

The correction changes the "angular frequency" of the radial oscillation relative to the angular motion.

The two no longer stay perfectly synchronized.

That loss of synchronization is precisely the perihelion advance.

---

## An even deeper viewpoint

This is, in my opinion, the cleanest way to understand it.

In Newtonian gravity, two motions occur simultaneously:

* the planet goes around the Sun (angular motion),
* the planet moves from perihelion to aphelion and back (radial motion).

For a perfect ellipse,

> **one complete radial oscillation occurs during exactly one complete revolution.**

So after one orbit,

* angle advanced = ($`2\pi`$),
* radial cycle completed = 1,

and the planet returns to the same perihelion.

General relativity changes this delicate equality.

The radial oscillation and the angular revolution acquire slightly different natural rates. After the planet has gone from perihelion to aphelion and back once, it has turned through **slightly more than (2\pi)** in angle. The next perihelion therefore occurs at a new direction.

This viewpoint is especially powerful because it doesn't rely on visualizing curved surfaces at all. It highlights that the precession arises because spacetime curvature slightly alters the relationship between radial and angular motion. The orbit doesn't close because those two "clocks" no longer tick in perfect lockstep.

===
===

> 1. But you said "On a curved surface, trying to follow the "same" geometric path doesn't bring you back to exactly the same orientation." So here you mean a person is trying to draw a path ie he is unconstrained?
> 
> 2. Wrt "Changing the geometry changes those equations.", what is the parameter for the geometry in the GR equation of orbit you gave? 


Excellent questions. They get at exactly where analogies stop being reliable and where the mathematics takes over.

### 1. Yes—my wording there was misleading.

I wrote:

> "On a curved surface, trying to follow the same geometric path doesn't bring you back to exactly the same orientation."

That isn't literally true for arbitrary paths.

As you pointed out, on a sphere or hyperboloid you can certainly draw many closed curves (including ellipse-like ones) that return to the same orientation.

What I **should** have said is something much more specific:

> **The equations that determine "free motion" on a curved manifold are different from those on a flat manifold. Consequently, the trajectories selected by those equations need not be closed.**

So the "person drawing a path" picture is actually a poor analogy, because the person is unconstrained and can draw whatever curve they like.

Mercury isn't drawing an arbitrary curve. It is following the unique curve determined by the equations of motion.

---

## 2. What is the "geometry parameter" in GR?

This is the deeper question.

The answer is:

**There isn't one geometry parameter.**

The geometry is encoded in the **metric tensor**

[
g_{\mu\nu}(x).
]

This is the object that tells spacetime:

* how to measure distances,
* how to measure time,
* what the straightest possible paths (geodesics) are.

Everything about the geometry is contained in (g_{\mu\nu}).

---

For empty space outside the Sun, Einstein's equations uniquely determine the metric to be the Schwarzschild metric:

[
ds^2
====

-\left(1-\frac{2GM}{rc^2}\right)c^2dt^2
+
\left(1-\frac{2GM}{rc^2}\right)^{-1}dr^2
+
r^2d\Omega^2.
]

Notice something remarkable.

The only physical parameter appearing is

[
M,
]

the Sun's mass.

So the geometry itself is determined by the mass.

There is no extra "curvature knob."

---

### Where does the extra term come from?

Earlier I wrote the orbit equation

[
u''+u
=====

\frac{GM}{h^2}
+
\frac{3GM}{c^2}u^2.
]

That equation is **not** postulated.

It comes from solving the geodesic equation

[
\frac{D^2x^\mu}{d\tau^2}=0
]

using the Schwarzschild metric.

In other words,

> metric
> (\rightarrow)
> Christoffel symbols
> (\rightarrow)
> geodesic equation
> (\rightarrow)
> orbit equation.

The extra

[
\frac{3GM}{c^2}u^2
]

is simply what drops out after the algebra.

---

## Can we identify *which part* of the metric causes it?

Yes.

In Newtonian gravity, only the time-time component is effectively modified:

[
g_{tt}
\approx
-\left(1+\frac{2\Phi}{c^2}\right),
]

where (\Phi=-GM/r).

If that were the whole story, you would recover Newtonian gravity.

General relativity also changes the **spatial** geometry:

[
g_{rr}
======

\left(1-\frac{2GM}{rc^2}\right)^{-1},
]

meaning that radial distances are no longer Euclidean.

So spacetime around the Sun is not merely a curved "time" dimension—it also has curved **space**.

Both effects contribute to the perihelion advance.

Historically, Einstein himself noted something interesting: if you include only the curvature of time (and keep space flat), you obtain only part of the observed advance—roughly one-third to one-half, depending on the approximation used. The full 43 arcseconds per century emerges only when both the temporal and spatial curvature dictated by the Schwarzschild solution are included.

---

So, unlike the analogy with a curved 2D surface, in GR the "geometry" isn't described by a single curvature parameter. It is encoded in the entire metric tensor (g_{\mu\nu}), and the perihelion advance is a consequence of the specific way the Schwarzschild metric modifies both the flow of time and the geometry of space around the Sun. This is why the orbit equation acquires that extra (3GMu^2/c^2) term.

===
===

> 1. So can we say after simplifying the tensor equation to a scalar form, the mass M of the central object (around which the orbital motion occurs), determines the geometry? Or M only captures the "strength" of the geometry, not the "type" of geometry. To give a 2D example, let's say the tensor determines if the geometry of the path is a "circle", "parabola", "ellipse", "hyperbola", or even some other plane curve, and M captures the eccentricity (of the type (if it is a conic)) or the curvature function (if it is some arbitrary plane curve)? Again I am just giving an analogy.
> 
> 2. So to understand apsidal precession, if there are only two point masses (therefore no oblateness / irregular shape issues, no tidal forces, no other masses to consider), pre-GR (ie Newton) laws predict that there will be no apsidal precession, ie the period of the angular motion is equal to the period of the radial motion, both are 2π. But in GR, there is a correction so the radial period (2π+∂) is slightly greater than the angular period (2π), correct?

These are very insightful formulations. Let me refine them a bit.

## 1. Does (M) determine the geometry, or just its "strength"?

The best answer is:

> **The mass (M) determines the specific geometry within a given family of geometries.**

Here's what I mean.

Einstein's field equations are

[
G_{\mu\nu}=\frac{8\pi G}{c^4}T_{\mu\nu}.
]

Once you specify the matter distribution (T_{\mu\nu}), the equations determine the metric (g_{\mu\nu}).

For your Mercury problem, the assumptions are:

* static,
* spherically symmetric,
* vacuum outside the Sun.

Under these assumptions, there is a theorem (Birkhoff's theorem) that says there is only **one** possible exterior geometry: the Schwarzschild geometry.

Within that family, (M) is the only free parameter.

So your statement

> "M determines the geometry"

is correct **provided you've already fixed the symmetry assumptions.**

If you change the physical situation, you get different geometries.

For example:

* non-rotating spherical body → Schwarzschild metric
* rotating body → Kerr metric
* electrically charged body → Reissner–Nordström metric
* expanding universe → Friedmann–Lemaître–Robertson–Walker metric

So (M) does **not** choose the "type" of geometry. The physical assumptions do.

Once the type is fixed, (M) fixes how strongly curved that geometry is.

---

### Your conic analogy

I actually like it, with one caveat.

Think of it like this.

Suppose someone tells you

> "The curve is an ellipse."

Then

* eccentricity,
* semi-major axis,

tell you **which** ellipse.

Likewise,

> "The spacetime is Schwarzschild."

Then

* (M)

tells you **which Schwarzschild spacetime.**

So yes, (M) is more analogous to a parameter *within* a family than to the family itself.

---

# 2. About the radial and angular periods

You are **extremely close**, but there is one subtle reversal.

You wrote

> radial period = (2\pi+\delta),
>
> angular period = (2\pi).

Actually it's the opposite way of thinking.

Here's why.

---

### Newton

Suppose you start at perihelion.

After

* one radial oscillation
  (perihelion → aphelion → perihelion),

the planet has rotated by exactly

[
2\pi.
]

So

[
\Omega_\phi=\Omega_r,
]

where

* (\Omega_\phi) = angular frequency,
* (\Omega_r) = radial frequency.

The orbit closes.

---

### GR

The radial oscillation is still

> perihelion → aphelion → perihelion.

That defines one radial period.

But during that same radial cycle, the planet has turned by

[
2\pi+\Delta\phi.
]

So it has rotated **more** than one full revolution before reaching the next perihelion.

Equivalently,

[
\Omega_\phi>\Omega_r.
]

The angular motion is slightly "ahead."

So the next perihelion occurs after the planet has swept out slightly more than (360^\circ).

That's exactly the perihelion advance.

---

Another way to express it is:

Let

* (T_r) = radial period,
* (T_\phi) = time to rotate through (2\pi).

Then in GR,

[
T_\phi<T_r.
]

The planet completes one full (360^\circ) revolution **before** it has completed one radial oscillation. By the time it returns to perihelion, it has already gone an additional tiny angle (\Delta\phi).

So your qualitative picture—that GR breaks the equality between the radial and angular motions—is exactly right. The only correction is the direction: it's the **angular** motion that gets slightly ahead of the radial oscillation, not the other way around.

---

This frequency viewpoint is actually how relativists often think about the problem. In more advanced GR (for example, when studying stars orbiting black holes), one naturally talks about three fundamental frequencies: radial, polar, and azimuthal. Whenever those frequencies are not equal or not in simple rational ratios, the orbit does not close. Mercury's perihelion advance is the simplest and historically first example of this general phenomenon.

===
===

> ok got it. You mentioned about different geometries for different assumptions/scenarios eg non-rotating spherical body → Schwarzschild metric etc. What about the gremetry/metric when I assume point mass? In this case, will GR also give zero apsidal precession?

This is a very good question because it exposes a subtle point: **"point mass" is a Newtonian concept, and in GR it is not quite the same thing as "spherical body."**

The short answer:

> **No. A point mass in GR does not give zero apsidal precession. In the appropriate limit, it gives the Schwarzschild geometry, and bound orbits do precess.**

Let's unpack why.

---

## 1. What is the GR equivalent of a point mass?

In Newtonian gravity, a point mass means:

[
\rho(\mathbf{x})=M\delta(\mathbf{x})
]

and the gravitational field outside it is:

[
\Phi=-\frac{GM}{r}.
]

For a spherical extended body, Newton's shell theorem says the outside field is exactly the same as a point mass. So Newtonian mechanics does not care whether the Sun is a point or a sphere.

In GR, the analogous statement is:

> Outside any **static, spherically symmetric** mass distribution, the spacetime is Schwarzschild.

This is the content of Birkhoff's theorem.

So:

* point mass,
* spherical star,
* spherical planet,

all produce the **same exterior metric** (assuming no rotation and no other complications).

The metric is:

[
ds^2=
-\left(1-\frac{2GM}{rc^2}\right)c^2dt^2
+
\left(1-\frac{2GM}{rc^2}\right)^{-1}dr^2
+
r^2d\Omega^2.
]

So the "point mass" assumption does **not** lead to a new metric with zero precession. It leads to Schwarzschild.

---

## 2. Why doesn't the point-mass case behave like Newtonian gravity?

This is the key distinction.

In Newtonian mechanics:

[
V(r)=-\frac{GM}{r}
]

has a special property: all bound orbits close.

This is not true for most potentials.

For example:

* (V(r)\propto r^2) → closed ellipses (harmonic oscillator)
* (V(r)\propto -1/r) → closed ellipses (gravity)
* most other potentials → precessing ellipses

This is related to the Joseph Bertrand theorem: only those two central potentials produce closed orbits for all initial conditions.

---

In GR, even though the Newtonian potential is still approximately:

[
-\frac{GM}{r},
]

the **effective potential** for orbital motion gets an additional term.

The radial equation can be written schematically as:

Newton:

[
\dot r^2 + V_{\rm eff}(r)=E
]

with

[
V_{\rm eff}
===========

-\frac{GM}{r}
+\frac{L^2}{2r^2}.
]

GR adds a correction:

[
V_{\rm eff}^{GR}
================

-\frac{GM}{r}
+\frac{L^2}{2r^2}
-\frac{GML^2}{c^2r^3}
+\cdots
]

That extra:

[
-\frac{GML^2}{c^2r^3}
]

term breaks the exact balance that makes the Newtonian ellipse close.

The orbit becomes a slowly rotating ellipse.

---

## 3. A subtle point: "point mass" actually makes GR more interesting

If the central object is a point mass, the spacetime has a singularity at:

[
r=0.
]

The Schwarzschild solution describes a black hole if the mass is compressed within its Schwarzschild radius:

[
r_s=\frac{2GM}{c^2}.
]

For the Sun:

[
r_s\approx3,\text{km}.
]

The actual solar radius is about (700,000) km, so the Sun is nowhere near a black hole, but its **external spacetime is still Schwarzschild**.

---

## 4. Your original two-body assumption

You asked:

> only two point masses, no oblateness, no tides, no other masses

In that idealization:

### Newton:

* inverse-square force exactly
* closed ellipse
* zero apsidal precession

### GR:

* Schwarzschild geometry (for one dominant central mass)
* non-closed orbit
* nonzero apsidal precession

The only caveat is that the exact GR two-body problem is not simply "a test particle orbiting a fixed mass." If the two masses are comparable, both bodies curve spacetime and orbit the system's center of mass. Then you need the full two-body GR solution (usually treated using post-Newtonian approximations or numerical relativity).

But for Mercury around the Sun, the test-particle approximation is extraordinarily good.

So the surprising result is:

> The very idealized case you might expect to remove all complications—two perfect point masses—is precisely the case where GR predicts a clean, unavoidable apsidal precession purely from spacetime curvature.

===
===

> Ah ok I got it. Just as in Newtonian mechanics, outside the mass, it does not matter if it was a perfect sphere or a point (we can take the COM as the point mass, and result will be same), in GR also, it must be same, ie non-rotating spherical body → Schwarzschild metric already covers point mass body.

Exactly. Your understanding is now aligned with the key idea.

The analogy between Newtonian gravity and GR is:

### Newtonian gravity

Outside a spherically symmetric body:

[
\Phi(r)=-\frac{GM}{r}
]

regardless of whether the mass is:

* a point mass,
* a solid sphere,
* a shell,
* a star with complicated internal density profile,

as long as it is **spherically symmetric**.

The outside world only "sees" the total mass (M).

---

### General relativity

The corresponding statement is even stronger:

> Outside any **static, spherically symmetric** matter distribution, the spacetime geometry is Schwarzschild.

So:

* point mass (idealized)
* non-rotating spherical planet
* non-rotating spherical star

all give the same external metric:

[
ds^2=
-\left(1-\frac{2GM}{rc^2}\right)c^2dt^2
+
\left(1-\frac{2GM}{rc^2}\right)^{-1}dr^2
+
r^2d\Omega^2.
]

The only parameter is (M).

So yes, for Mercury's orbit, the Sun can be treated as a point mass **as far as the external gravitational field is concerned**. The Sun's radius, density distribution, etc., do not enter the Schwarzschild metric.

---

There is one subtle refinement, though.

In Newtonian mechanics, we often say:

> "Take the center of mass as the point mass."

This is literally a statement about replacing an extended distribution by an equivalent source.

In GR, we have to be more careful:

* A spherical body has an exterior Schwarzschild geometry.
* A point mass also has a Schwarzschild geometry outside (r=0).
* But the interior solutions are different.

For example:

* Inside the Sun: not Schwarzschild; it requires a solution involving pressure and density (e.g., the interior Schwarzschild solution for an idealized constant-density star).
* Inside a black hole horizon: a completely different situation again.

But for an orbit **outside** the body, these differences are irrelevant.

---

This also explains why Mercury was such a clean test of GR:

Astronomers did not need a complicated model of the Sun's interior. They only needed:

1. Sun's mass (M)
2. Mercury's orbital parameters (a,e)
3. Schwarzschild exterior geometry

and GR predicted the extra:

[
43''/\text{century}
]

from pure spacetime geometry.

---

One final subtle distinction:

The "point mass equivalence" works only because the central object is assumed:

* non-rotating,
* spherically symmetric.

If the body rotates, then the exterior is no longer Schwarzschild. For example, a rotating Sun produces a tiny frame-dragging effect described by a different geometry (the Kerr metric in the idealized case). Similarly, the Sun's oblateness produces a small Newtonian correction.

Those are additional effects layered on top of the dominant Schwarzschild perihelion advance.

===
===

> 1. What if the body is non-rotating, but the surface has mass moving around eg plasma flows, plasma storms etc.?
> 
> 2. Also, since the sun is in fact rotating, there will be further corrections also, no? Because we have to use Kerr metric.
> 
> 3. Also, does superposition work ie lets say if it is a rotating and charged body, then can we simply "add" (ie do some generic tensor/metric addition operation on) the Kerr metric and the RN metric? And so on?

These are excellent questions because they move from the "clean textbook cases" into what real astrophysical objects actually require.

## 1. Non-rotating body, but moving mass on the surface (plasma flows, storms, etc.)

If the **total object is non-rotating and perfectly spherically symmetric**, then Schwarzschild applies.

But if there are **mass motions that break spherical symmetry**, then Schwarzschild is no longer exact.

The key point is:

> In GR, it is not only the total mass that matters. The full stress-energy tensor (T_{\mu\nu}) matters.

Einstein's equation is:

[
G_{\mu\nu}=\frac{8\pi G}{c^4}T_{\mu\nu}.
]

The right side contains:

* energy density,
* momentum density (mass currents),
* pressure,
* stresses.

So a plasma storm contributes not only because of its mass, but also because the plasma is moving.

Examples:

### Solar granulation / plasma flows

These are tiny effects. The moving plasma velocities and mass involved are negligible compared with the Sun's total mass.

### A large asymmetric mass flow

Suppose a star had a huge asymmetric jet or a large clump of mass moving around its surface. Then:

* the exterior gravitational field would have multipole corrections,
* there could be small deviations from Schwarzschild,
* gravitational radiation could occur if the asymmetry changes with time.

In practice, the Sun is extremely close to spherical, so these effects are much smaller than the Schwarzschild correction.

---

## 2. Since the Sun rotates, shouldn't we use Kerr instead of Schwarzschild?

Conceptually, yes.

A rotating mass produces **frame dragging**, and the exact idealized solution is the Kerr metric.

The Kerr metric has parameters:

* (M): mass
* (J): angular momentum

instead of only (M).

The extra term is roughly associated with the gravitomagnetic field created by the rotating mass.

For Mercury, the solar rotation correction exists, but it is **tiny** compared with the main Schwarzschild perihelion advance.

The contributions are roughly:

* Schwarzschild GR effect:
  [
  43''/\text{century}
  ]

* Solar quadrupole/oblateness effect:
  [
  \sim 0.025''/\text{century}
  ]

* Solar frame dragging:
  [
  \sim 0.001''/\text{century}
  ]

(order of magnitude)

So yes, the exact calculation should include the Sun's rotation, but historically and observationally the dominant "43 arcseconds" is the Schwarzschild part.

---

## 3. Can we add Kerr + Reissner–Nordström to get a rotating charged body?

This is the most interesting question.

The short answer:

> No. GR does not obey a simple superposition principle like Newtonian fields do.

This is a fundamental difference.

In Newtonian gravity:

[
\Phi=\Phi_1+\Phi_2+\cdots
]

because the equations are linear.

In electromagnetism:

[
\mathbf{E}=\mathbf{E}_1+\mathbf{E}_2+\cdots
]

because Maxwell's equations are linear.

But Einstein's equations are nonlinear:

[
G_{\mu\nu}(g)=\frac{8\pi G}{c^4}T_{\mu\nu}.
]

The left side contains products of the metric and its derivatives.

So generally:

[
g_{\mu\nu}^{(1)}+g_{\mu\nu}^{(2)}
]

is **not** another valid solution.

---

However, there is a very interesting special case.

There is an exact solution for a:

* rotating,
* charged,
* isolated mass.

It is called the Kerr–Newman metric.

It has three parameters:

[
M,\quad J,\quad Q
]

where:

* (M) = mass
* (J) = angular momentum
* (Q) = electric charge

So nature does not combine:

[
\text{Kerr}+\text{Reissner–Nordström}
]

by addition.

Instead, Einstein's equations are solved again with the combined requirements, producing a new geometry.

---

## A useful hierarchy

The standard progression is:

### 1. Newtonian point mass

[
M
]

↓

### 2. GR non-rotating spherical mass

[
\text{Schwarzschild}
]

parameters:

[
M
]

↓

### 3. Rotating mass

[
\text{Kerr}
]

parameters:

[
M,J
]

↓

### 4. Rotating charged mass

[
\text{Kerr–Newman}
]

parameters:

[
M,J,Q
]

Each step is **not** obtained by adding the previous solutions. It is a new solution of the field equations.

---

A nice way to summarize:

* **Spherical symmetry hides internal complexity** → Schwarzschild outside.
* **Rotation introduces angular momentum into spacetime itself** → Kerr.
* **Charge introduces electromagnetic stress-energy** → Reissner–Nordström/Kerr–Newman.
* **GR effects combine nonlinearly**, so there is no general "metric superposition."

===
===

> ok got it thx.

You're welcome! These were unusually good questions because they moved through the hierarchy of ideas in the right order:

1. **Newtonian gravity**

   * Spherical mass distributions → same external field as a point mass.
   * Inverse-square potential → closed Kepler ellipses.

2. **GR with spherical symmetry**

   * Exterior geometry is fixed by the Schwarzschild solution.
   * The mass (M) sets the strength of that geometry.
   * Even a point mass and a spherical star have the same exterior spacetime.

3. **Why precession appears**

   * The Schwarzschild correction changes the relation between radial and angular motion.
   * The Newtonian coincidence that makes ellipses close is broken.

4. **Real astrophysical corrections**

   * Rotation → Kerr/frame dragging.
   * Charge → Reissner–Nordström or Kerr–Newman.
   * Irregular mass distributions → multipole corrections.
   * No simple addition because GR is nonlinear.

A particularly nice conceptual takeaway is this:

> In Newtonian physics, gravity is a field **on** spacetime.
> In GR, gravity is the geometry **of** spacetime itself.

That single change is why ideas like "adding gravitational fields" or "just adding metrics" stop working in the straightforward way they do for electromagnetism.

It was a pleasure discussing this—your questions were exactly the kind that expose the structure behind the equations rather than just the formulas.
