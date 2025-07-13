# Triangle Formulas for Angles

- $\angle BIC = 90^º + \dfrac{A}{2}$
- $\angle BGC$ No formula since $G$ is an affine object. $G$ is affine-invariant and does not play nice with angles.
- $\angle BOC = 2A$
- $\angle BHC = 180^º - A$

<!--img width="691" alt="Orthic Triangle" src="https://github.com/user-attachments/assets/5aebd298-5d6b-4850-ac37-47229b98b945" /-->
<img width="719" alt="Orthic Triangle" src="https://github.com/user-attachments/assets/d0626ef4-e792-4b7e-9c99-1f81d16c6143" />

- In an Orthic Triangle (See Figure)
  - $\angle H_cH_aH_b = 180^º - 2A = 2\theta$
  - Line $\overline{HH_a}$ bisects $\angle H_cH_aH_b$. Hence $H$ is the Incenter of the Orthic Triangle.

---

# Formulas for Distances of $O$, $G$, $I$, $H$ from a Vertex. Also Formulas for Their Cevian[^1] Lengths

<img width="719" alt="Cevian Lengths" src="https://github.com/user-attachments/assets/4acef8fb-35c2-4a0c-8bc6-01fe4bafc061" />

---
🟠
- $\overline{AO} = R$
- $\overline{OO_a} = R \dfrac{\cos A}{\cos (B-C)}$
- $\overline{AO_a} = \overline{AO} + \overline{OO_a}$
- $\overline{OM_a} = R\\, \cos A = \dfrac{1}{2}\overline{AH}$

---
🟢
- $\overline{AG} = \dfrac{2}{3} \overline{AM_a}$
- $\overline{GM_a} = \dfrac{1}{3} \overline{AM_a}$
- $\overline{AM_a} = \dfrac{1}{2}\sqrt{2b^2 + 2c^2 - a^2}$

---
🟣
- $\overline{AI} = 4R\\: \sin \dfrac{B}{2} \\: \sin \dfrac{C}{2}$
- $\overline{II_a} = \overline{AI_a} - \overline{AI}$
- $\overline{AI_a} = \dfrac{2bc}{b+c} \cos \dfrac{A}{2}$
- $\dfrac{\overline{BI_a}}{\overline{CI_a}} = \dfrac{c}{b}$

---
🔴
- $\overline{AH} = 2R\\: \cos A$
- $\overline{HH_a} = 2R\\: \cos B\\: \cos C$
- Height $$h_a = \overline{AH_a} = 2R\\: \sin B\\: \sin C = \dfrac{2\Delta}{a}$$

---

🟠🔴

$\therefore \\; \overline{OM_a} = R\\, \cos A = \dfrac{1}{2}\overline{AH}$

---

## Formulas for Exradius and Inradius[^2][^3]

- $r_a^{-1} + r_b^{-1} + r_c^{-1} = r^{-1} = h_a^{-1} + h_b^{-1} + h_c^{-1}$
- $r_a + r_b + r_c = 4R + r$
- $rr_ar_br_c = \Delta ^2$
  - $\because \\:\\:  r = \dfrac{\Delta }{s} \\:\\:$, $r_a = \dfrac{\Delta }{s-a}\\:$ and so on.

## Formulas for Distances Amongst $O$, $G$, $I$, $H$

- 🟣🟢 $\overline{IG} =$ See [^18][^19][^20]
- 🟣🟠 $\overline{IO} = \sqrt{R^2 - 2Rr}$ [^20][^21]
- 🟣🔴 $\overline{IH} = \sqrt{2r^2 - 4R^2 \\: \cos A \\: \cos B \\: \cos C}$ [^22]
- 🟠🔴 $\overline{OH} = R\sqrt{1 - 8\\: \cos A \\: \cos B \\: \cos C} = 3R\sqrt{1 - \dfrac{a^2+b^2+c^2}{9R^2}}$

> [!NOTE]
> And, we already know:
> - 🟢🟠 $\overline{GO} = \dfrac{1}{3}\overline{OH}$
> - 🟢🔴 $\overline{GH} = \dfrac{2}{3}\overline{OH}$

# Pedal Triangle[^4], Pedal Circle[^5], Cevian Triangle[^6]

- Radius of Pedal Circle of a point $P$\
  $$r_P = \dfrac{\overline{PA}.\overline{PB}.\overline{PC}}{2(R^2 - \overline{PO}^2)}$$

> [!NOTE] 
> Notation:
> 
> $P$ = A Point.
>
> $P^*$ = Isogonal Conjugate of $P$.[^7]
>
> $P^+$ = Isotomic Conjugate of $P$.[^8]
>
> $P^\\#$ = Cyclocevian Conjugate of $P$.[^9]

- Pedal Triangles of $P$ and $P^*$ share the same circumcircle.
- Cevian Triangles of $P$, $P^+$, $P^\\#$ (by defn of Cyclocevian Conjugate), $(P^+)^\\#$ (also by defn of Cyclocevian Conjugate), and $(P^\\#)^+$ (because of $P^\\#$) share the same circumcircle.
- ❓Is $(P^+)^\\#$ the same point as $(P^\\#)^+$ ? ie is the Cyclocevian Conjugate of the Isotomic Conjugate of a point $P$, the same as the Isotomic Conjugate of the Cyclocevian Conjugate of $P$ ? ie do Cyclocevian Conjugation and Isotomic Cojugation operations commute with each other?❓ (Most probably No. Check this.)

## Pedal-Cevian Points[^10], CPCC Points[^11], Darboux Cubic[^12], Thomson Cubic[^13], Lucas Cubic[^14][^15]

See CTC[^12] Table http://bernard-gibert.fr/Tables/table11.html
See [^16][^17]

[^1]: https://mathworld.wolfram.com/Cevian.html
[^2]: https://mathworld.wolfram.com/Excircles.html
[^3]: https://mathworld.wolfram.com/Exradius.html
[^4]: https://mathworld.wolfram.com/PedalTriangle.html
[^5]: https://mathworld.wolfram.com/PedalCircle.html
[^6]: https://mathworld.wolfram.com/CevianTriangle.html
[^7]: https://mathworld.wolfram.com/IsogonalConjugate.html
[^8]: https://mathworld.wolfram.com/IsotomicConjugate.html
[^9]: https://mathworld.wolfram.com/CyclocevianConjugate.html
[^10]: https://mathworld.wolfram.com/Pedal-CevianPoint.html
[^11]: http://bernard-gibert.fr/Tables/table11.html
[^12]: https://en.wikipedia.org/wiki/Catalogue_of_Triangle_Cubics
[^13]: https://en.wikipedia.org/wiki/Thomson_cubic
[^14]: https://en.wikipedia.org/wiki/Cubic_plane_curve#Lucas_cubic
[^15]: https://mathworld.wolfram.com/LucasCubic.html
[^16]: https://mathworld.wolfram.com/PivotalIsocubic.html
[^17]: https://mathworld.wolfram.com/topics/TriangleCubics.html
[^18]: https://gogeometry.com/center/distance_incenter_centroid_formula_sides.htm
[^19]: https://math.stackexchange.com/questions/1833476/finding-the-distance-between-incenter-and-centroid-of-a-triangle
[^20]: https://mathworld.wolfram.com/Incenter.html
[^21]: https://mathworld.wolfram.com/Circumcenter.html
[^22]: https://mathworld.wolfram.com/Orthocenter.html
