# geometry
Conics, Modern Triangle Geometry[^15], Triangle Centers, Triangle Conics[^16], Circumconics, Inconics, Triangle Cubics[^17].

## Some Properties of Conics

1. In parabola only,   
     - Mid points of any number of parallel chords are all collinear and lie on a line parallel to the axis.
     - Line joining the intersection of two tangents and the mid point of their chord-of-contact, is parallel to the axis.
     - Both have $`y`$ co-ordinate $`a(t+t')`$ where $`t`$ and $`t'`$ are parameters of the extremities of any of the parallel chords of $`y^2 = 4ax`$
       with slope $`\dfrac{1}{t+t'}`$.
     - A circle with any focal chord as diameter, is tangent to the directrix.
     - The intersection points of any three tangents to a parabola, are vertices of a triangle whose orthocenter belongs to the directrix of the parabola[^5], and the circumcircle of the triangle passes through the focus of the parabola.[^3]
     - The foot of the $`\perp`$ from the focus to any tangent, always lies on the tangent at vertex.[^3] 
3. In ellipse and hyperbola only,
     - Product of the lengths of the two $`\perp`$'s from foci on any tangent is $`b^2`$ where $`b`$ is the length of the semi-minor or semi-conjugate axis of ellipse or hyperbola respectively.
5. Reflection property for all conics.
6. For all conics,
    - Tangent intercept between point of contact and directrix, subtends $`90^\circ`$ at the (corresponding) focus.

### Hyperbola

- Angle between asymptotes, $`\theta = 2sec^{-1}(e)`$, where $`e`$ is the eccentricity.
- Tangents from a given point: 0, 1, or 2 tangents are possible depending on the location of the point.
     - If given point lies in the region inside a branch, then no tangent can be drawn to any of the two branches.
     - If given point lies on the hyperbola, only one tangent can be drawn. The given point itself will be point of tangency. The tangent will never meet, cut or touch the other branch. This is because the point of tangency already accounts for the two (equal) roots when we solve this tangent line with the hyperbola.
     - If the given point lies in the region in between the asymptotes and a branch, two tangents can be drawn. Both touching the same branch.
     - If the given point lies in the region in between the asymptotes not containing any branch, then also two tangents can be drawn. One tangent each to each branch.
- Normals from a given point: 0, 1, 2, 3, or 4 normals are possible depending on the location of the point.
     - ‼️: TODO: What are these regions that decide the number of normals that can be drawn from a point in the region?
- Number of tangents or normals from a given point relate to the Theory of Equations. Beacuse, we need to find the number of possible real roots (and their multiplicities), of the equation obtained by passing the general equation of tangent or normal, through the given point.

## Circumconics

Isogonal Conjugate (IC) of a straight line L, is a circumconic (and vice versa). We will denote the IC of L as IC(L).

- Iff L is line at infinity, IC(L) is the circumcircle.
- Iff L does not meet the circumcircle, IC(L) is a circumellipse.
- Iff L is tangent to the circumcircle, IC(L) is a circumparabola.
- Iff L cuts the circumcircle, IC(L) is a circumhyperbola.
   - Iff L passes through $`O`$, the circumcenter, ie L is a circumcircle diameter, then the IC(L) circumhyperbola is a rectangular hyperbola. Every rectangular circumhyperbola:
       - Is the IC of a circumcircle diamater L.
       - Passes through the orthocenter $`H`$ (Since $`O`$ and $`H`$ are isogonal conjugates (ICs)).
       - Has its center on the nine-point circle[^7], where the two ($`\perp`$) Simson lines at the ends of the diameter L meet.
         - These two Simson lines are the asymptotes. See [below](#circumhyperbolas).

### Circumcircle

- The two Simson lines at the ends of any diameter to the circumcircle are $`\perp`$ to each other and meet on the nine-point circle.

### Circumhyperbolas

- If the angle between asymptotes of IC(L) is $`\theta`$ and the angle of incidence of L on the circumcircle is $`i`$, then $`\theta + i = 90^\circ`$.[^4]
    - And, we already know that eccentricity $e = \sec \dfrac{\theta}{2}$ (see [above](#hyperbola)). 
- The asymptotes of Circumhyperbola IC(L) are the two Simson lines at the two points where the straight line L cuts the circumcircle. 

### Using Trilinear

- IC of line $`f(x, y, z) = 0`$ is the circumconic $`f(\dfrac{1}{x}, \dfrac{1}{y}, \dfrac{1}{z})`$, and vice versa.
- Let line L be $`\tau_1x + \tau_2y + \tau_3z = 0`$. Then IC(L) is $`\dfrac{\tau_1}{x} + \dfrac{\tau_2}{y} + \dfrac{\tau_3}{z} = 0`$. L is called the Central Line of the point $`(\tau_1 : \tau_2 : \tau_3)`$.
- Center of IC(L) is $`\tau_1(-a\tau_1 + b\tau_2 + c\tau_3) : do : do`$.
- 4th Point of IC(L) is $`(a\tau_2 - b\tau_1)(a\tau_3 - c\tau_1) : do : do`$.
- The point $`(\tau_1 : \tau_2 : \tau_3)`$ is the perspector of the reference Triangle $`\Delta ABC`$ and its Polar Triangle (Tangential Triangle) wrt the circumconic $`\dfrac{\tau_1}{x} + \dfrac{\tau_2}{y} + \dfrac{\tau_3}{z} = 0`$.
     - Note: The perspector of $`\Delta ABC`$ and its polar triangle with respect to a given conic is simply called the perspector of that conic.
     - ❓ What is equation of the perspectrix (perspective axis) of the reference Triangle $`\Delta ABC`$ and its Polar Triangle (Tangential Triangle) wrt the circumconic  $`\dfrac{\tau_1}{x} + \dfrac{\tau_2}{y} + \dfrac{\tau_3}{z} = 0`$❓ Is it the Trilinear Polar of $`(\tau_1 : \tau_2 : \tau_3)`$?
     - Trilinear Polar (TP) of Point $`P(\tau_1 : \tau_2 : \tau_3)`$ is the perspectrix of the reference Triangle $`\Delta ABC`$ and $P$'s Cevian Triangle. Their perspector is $P$ by definition. Equation of TP of $P$ is $`\dfrac{x}{\tau_1} + \dfrac{y}{\tau_2} + \dfrac{z}{\tau_3} = 0`$. $\therefore$ TP of $P$ is the Central Line of IC($P$), and vice versa.
     - $\therefore$ A point $P(\tau_1 : \tau_2 : \tau_3)$ is the perspector of 3 triangles: the reference Triangle $`\Delta ABC`$, $P$'s Cevian Triangle, and the Polar (Tangential) Triangle wrt the circumconic  $`\dfrac{\tau_1}{x} + \dfrac{\tau_2}{y} + \dfrac{\tau_3}{z} = 0`$. So do these 3 triangles also have the same perspectrix (namely the Trilinear Polar of $P$)?❓
- Point $Q$ is the Center of the IC of Central Line L of Point $P$ iff Point $P$ is the Center of the IC of Central Line L of Point $Q$.
     - ie, $$Q = Center(IC(L(P))) \iff P = Center(IC(L(Q))$$.
     - This means, the center of circumconic $`\dfrac{\tau_1}{x} + \dfrac{\tau_2}{y} + \dfrac{\tau_3}{z} = 0`$ is the perspector of the circumconic centered at $`(\tau_1 : \tau_2 : \tau_3)`$, and vice versa. This is because the Center of the circumconic $`\dfrac{\tau_1(-a\tau_1 + b\tau_2 + c\tau_3)}{x} : \dfrac{do}{y} : \dfrac{do}{z} = 0`$ is simply the point $`(\tau_1 : \tau_2 : \tau_3)`$.
- Point $`X_n`$, say $`(\tau_1 : \tau_2 : \tau_3)`$, is the crossdifference of every pair of points on line $`\tau_1x + \tau_2y + \tau_3z = 0`$. This line is denoted by $`L_n`$ in ETC. Further, $`X_n`$ is the only point that is the crossdifference of any pair of points on this line.

## Trilinear Polar

Trilinear Polar of:
- $I$: $x + y + z = 0$ ie $L_1$ (Anti-orthic Axis)
- $G$: $ax + by + cz = 0$ ie $L_6$ or $L_\infty$ (Line at Infinity)
- $O$: $x { } \sec A + y { } \sec B + z { } \sec C = 0$ ie $L_4$ (What is its name?❓)
- $H$: $x { } \cos A + y { } \cos B + z { } \cos C = 0$ ie $L_3$ (Orthic Axis)
- $K$: $\dfrac{x}{a} + \dfrac{y}{b} + \dfrac{z}{c} = 0$ ie $L_2$ (Lemoine Axis)

## Nine-Point Circle[^14], Incircle, Excircles

We know that isogonal conjugate points share the same Pedal Circle, with their midpoint as its center. 
- When the isogonal conjugates are $O$ and $H$, their common Pedal Circle is the Nine-Point-Circle.
- When the point is $I$ (which is its own isogonal conjugate), the (trivially common) Pedal Circle is the Incircle.
- **Feuerbach's Theorem:**[^8]
    - The Nine-Point-Circle is tangent, internally, to the Incircle (at ETC[^9] Point $X(11)$ called the Feuerbach Point).
    - The Nine-Point-Circle is also tangent, externally, to the 3 Excircles.

### Incenter-Excenter Lemma[^10]

The line segment between the Incenter ($I$) and an Excenter (say $J_1$), or between any two Excenters (say $J_2$ and $J_3$), is the diamater of a circle[^11][^12] whose center lies on the circumcircle and which passes through two vertices of the reference triangle.

This is because the Incenter $I$ and the 3 Excenters $J_1$, $J_2$, $J_3$ form an Orthocentric System[^13] whose common Nine-Point-Circle is the Circumcircle of the reference triangle.

Also, the centers of an $I-J$ circle and its corresponding $J-J$ circle (of the remaining 2 Excenters), are circumcircle Antipodes of each other.

## Questions 
- Is the Steiner Circumellipse the only triangle-conic whose center ($G$) is its own perspector?
- Is the circumconic $`\dfrac{\tau_1(-a\tau_1 + b\tau_2 + c\tau_3)}{x} : \dfrac{do}{y} : \dfrac{do}{z} = 0`$ the only circumconic with center $`(\tau_1 : \tau_2 : \tau_3)`$?
- What is the angle of intersection of a line $`\tau_1x + \tau_2y + \tau_3z = 0`$ with the circumcircle ($`\dfrac{a}{x} + \dfrac{b}{y} + \dfrac{c}{z} = 0`$)?
- What is the equation of the polar wrt the circumcircle (circumcircle polar), of a point $`(\tau_1 : \tau_2 : \tau_3)`$ in trilinear form?
     - Is it $`\sum \dfrac{ax}{\tau^2} = 0`$ ?
     - In general, is $`\sum \dfrac{\tau 'x}{\tau^2} = 0`$ the Polar of point $`P(\tau_1 : \tau_2 : \tau_3)`$ wrt the circumconic $`\sum \dfrac{\tau '}{x} = 0`$ ?
          - If so, putting $`\tau ' = \tau`$ above, is the Trilinear Polar of $P(\tau$) ie $`\sum \dfrac{x}{\tau} = 0`$, also the Polar of $P$ wrt its own circumconic $`\sum \dfrac{\tau}{x} = 0`$? (This circumconic is the IC of $P$'s own Central Line).
- Is the Lemoine Axis the only line which is the circumcircle polar of a point (K) and also the central line of that point's IC ie. G?
     - In other words, is K the only point whose circumcircle polar (CP) and Trilinear Polar (TP) are the same? (Both CP and TP being the Lemoine Axis).
- What kind of circumconics are IC's of $L_1$, $L_3$, $L_4$ ? ❓ [^1][^2]
- When is the Circumcircle of the Polar Triangle wrt $`\sum \dfrac{\tau}{x} = 0`$ (ie Anticevian Triangle of $`P(\tau)`$) tangent to the circumcircle of the reference Triangle $\Delta ABC$?
     - Note: Circumcircle of the Polar Triangle wrt $`\sum \dfrac{\tau}{x} = 0`$ is $\color{red}NOT$ the Polar Circle. Because, Polar Circle is not wrt a conic but is a circle wrt which $\Delta ABC$ is self-polar[^6] ie Polar Triangle wrt Polar Circle is the reference Triangle $\Delta ABC$.
- When can a circumhyperbola have $e > \sqrt{2}$?
- What is the locus of a circumconic IC(L)'s center, if its eccentricity is given? eg For $e=\sqrt{2}$ (ie when L cuts circumcircle at $90^\circ$ ie L passes through the circumcenter), the locus of the center of the circumconic (which is rectangular circumhyperbola) is the 9-Point-Circle.

## Geometry Journals

- [International Journal of Geometry](https://ijgeometry.com/volumes/)
- https://geometry.ru/
- [Journal of Classical Geometry](https://jcgeometry.org/articles.php)
- [Journal for Geometry and Graphics](https://www.heldermann.de/JGG/jggcover.htm)
- [KoG - Journal of Croatian Society for Geometry and Graphics](https://hrcak.srce.hr/en/kog)
- [MDPI Journal of Geometry](https://www.mdpi.com/journal/geometry)
- [International Journal of Computer Discovered Mathematics (IJCDM)](https://www.journal-1.eu/index.htm)

## References
[^3]: Ross Honsberger, ***Episodes in Nineteenth and Twentieth Century Euclidean Geometry***, Mathematical Assoc. of Amer., Chapter 5, pp. 47-48, 1995.
[^4]: [John Casey, ***A Treatise on the Analytical Geometry of the Point, Line, Circle, and Conic Sections, Containing an Account of Its Most Recent Extensions, with Numerous Examples., 2nd rev. enl. ed.*** Dublin: Hodges, Figgis, & Co., Article 342, p. 428, 1893.](https://archive.org/details/treatiseonanalyt00caseuoft/treatiseonanalyt00caseuoft/page/n465/mode/2up)
[^5]: Steiner's Theorem. [John Wellesley Russell, ***An Elementary Treatise on Pure Geometry with Numerous Examples***, p. 161, 1893](https://archive.org/details/cu31924059551501/page/n184/mode/1up)
[^1]: https://www.geogebra.org/classic/nvvcfq36
[^2]: https://www.geogebra.org/m/nvvcfq36
[^6]: https://mathworld.wolfram.com/Self-PolarTriangle.html
[^7]: Feuerbach's Conic Theorem: The 9-point-circle is the locus of the centers of all rectangular circumhyperbolas. https://mathworld.wolfram.com/FeuerbachsConicTheorem.html
[^8]: https://mathworld.wolfram.com/FeuerbachsTheorem.html
[^9]: https://faculty.evansville.edu/ck6/encyclopedia/etc.html
[^10]: https://en.wikipedia.org/wiki/Incenter%E2%80%93excenter_lemma
[^11]: https://mathworld.wolfram.com/Incenter-ExcenterCircle.html
[^12]: https://mathworld.wolfram.com/Excenter-ExcenterCircle.html
[^13]: https://en.wikipedia.org/wiki/Orthocentric_system , https://mathworld.wolfram.com/OrthocentricSystem.html
[^14]: https://mathworld.wolfram.com/Nine-PointCircle.html
[^15]: https://mathworld.wolfram.com/topics/TriangleProperties.html
[^16]: https://mathworld.wolfram.com/topics/TriangleConics.html , https://mathworld.wolfram.com/topics/TriangleCircles.html , https://mathworld.wolfram.com/CentralCircle.html
[^17]: https://mathworld.wolfram.com/topics/TriangleCubics.html
