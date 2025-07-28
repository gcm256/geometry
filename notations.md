# Notations

| Notation | `Ascii`-Notation | Type | Description | Notes |
| --- | --- | --- | --- | --- |
| $P$ | `P` | $`\cdot`$ | A Point. | $P(\tau)$ = A Point $P$ with Trilinear coordinates $(\tau_1, \tau_2, \tau_3)$.|
| $`P^*`$ | `P^*` | $`\cdot \to \cdot`$ | Isogonal Conjugate of $P$. | $`(P^*)^* = P`$. <br> $`P^* = P*I = P*X(1)`$.[^1] |
| $P^+$ | `P^+` | $`\cdot \to \cdot`$ | Isotomic Conjugate of $P$. | $(P^+)^+ = P$. <br> $`P^+ = P*X(31)`$. |
| $`P^\#`$ | `P^#` | $`\cdot \to \cdot`$ | Cyclocevian Conjugate of $P$. | $`(P^\#)^\# = P`$. <br> $`P^\#`$ = $`((((P^+)^©)^*)^@)^+`$.[^1] |
| $P^@$ | `P^@` | $`\cdot \to \cdot`$ | Anticomplement of $P$. | | 
| $P^©$ | `P^c` | $`\cdot \to \cdot`$ | Complement of $P$. | $(P^©)^@ = P = (P^@)^©$. <br> $(P^©)^© \neq P \iff P \neq G$. <br> $(P^@)^@ \neq P\iff P \neq G$. |
| $P/U$ | `P-vU` | $`\cdot \to (\cdot \to \cdot)`$ | $P$-Ceva-Conjugate of $U$. | Perspector of $(P_V)\Delta$ and $(U_V)^{-1}\Delta$. <br> $P/P = P$. <br> Since it is called conjugate, is $P/(P/U) = U$❓ Yes. See [^4]. <br> So the $`(P/)`$ **transformation** is an **involution**.[^1][^5] |
| $P*U$ | `P*U` | $`\cdot \to (\cdot \to \cdot)`$ | $P$-isoconjugate of $U$. | $`P=(p:q:r) \land U=(u:v:w) \implies P*U=(p^{-1}u^{-1} ::)`$. <br> $`P*U = U*P`$. <br> $`P*(P*U) = U`$. <br> $`P*P=(p^{-2}::)`$. <br> $`P*(P*P) = P`$. <br> $`(P*P)*U=(p^2u^{-1} ::) \neq P*(P*U)=U`$. <br> Thus the isoconjugation operator is commutative but not associative.|
| $`P /_b U`$ | `P-/U` | $`\cdot \to (\cdot \to \cdot)`$ | $P$-reciprocal-conjugate of $U$. | In Barycentric coordinates, $`P=(p:q:r)_b \land U=(u:v:w)_b \implies P /_b U=(pu^{-1}::)_b`$. <br> $`P /_b U = G /_b (U /_b P)`$. <br> $`P /_b P = (1:1:1)_b = G`$.|
| $(P_\perp)\Delta$ | `P_L` | $`(\Delta , \cdot) \to \Delta`$ | Pedal Triangle of $P$ wrt Triangle $\Delta$. | |
| $(P_V)\Delta$ | `P_V` | $`(\Delta , \cdot) \to \Delta`$ | Cevian Triangle of $P$ wrt Triangle $\Delta$. | |
| $(P_\perp)^{-1}\Delta$ | `P_-L` | $`(\Delta , \cdot) \to \Delta`$ | AntiPedal Triangle of $P$ wrt Triangle $\Delta$. | $`(P_\perp)(P_\perp)^{-1}\Delta = \Delta = (P_\perp)^{-1}(P_\perp)\Delta`$ |
| $(P_V)^{-1}\Delta$ | `P_-V` | $`(\Delta , \cdot) \to \Delta`$ | AntiCevian Triangle of $P$ wrt Triangle $\Delta$. | $`(P_V)(P_V)^{-1}\Delta = \Delta = (P_V)^{-1}(P_V)\Delta`$ |
| $`\mathcal{O}(\Delta _1, \Delta _2)`$ | `(T1)o(T2)` | $`(\Delta, \Delta) \to \mathtt{Boolean}`$ | Triangles $\Delta _1$ and $\Delta _2$ are Orthologic. | $`\mathcal{O}(\Delta _1, \Delta _2) \iff \mathcal{O}(\Delta _2, \Delta _1)`$. $`\mathcal{O}`$ is symmetric. <br> $`\mathcal{O}`$ is reflexive. $`\mathcal{O}_\odot(\Delta, \Delta) = H`$ <br> $`\mathcal{O}`$ is not transitive.[^2]|
| $`\mathcal{O}_\odot(\Delta _1, \Delta _2)`$ | `(T1)oc(T2)` | $`(\Delta , \Delta) \to \cdot`$ | The Orthology Center of $\Delta _1$ wrt $\Delta _2$. | $`\mathcal{O}_\odot(\Delta _1, \Delta _2)`$ need not be same as $`\mathcal{O}_\odot(\Delta _2, \Delta _1)`$ |
| $`P \oslash U`$ | `P-xU` | $`\cdot \to (\cdot \to \cdot)`$ | $P$-Cross-Conjugate of $U$.[^1] | $`P=(p:q:r) \land U=(u:v:w) \implies P \oslash U  =u(-pu^{-1} + qv^{-1} + rw^{-1})^{-1} ::`$. <br><br> $`P \oslash U = \dfrac{u}{p} \tau_1(U/P)::`$. <br><br> $`P/U = \dfrac{u}{p} \tau_1(U \oslash P) ::`$. <br> $`P \oslash U \neq U \oslash P`$. <br> The $`(P \oslash)`$ **transformation** is an **involution**[^1] ie $P \oslash (P \oslash U) = U$. |
| $`P \times U`$ | `PxU` | $`(\cdot , \cdot) \to \cdot`$ | Crosspoint of $P$ and $U$.[^1] | $`P=(p:q:r) \land U=(u:v:w) \implies P \times U = pu(qw+rv) ::`$. <br> $`(P \times U) \oslash U = P = (P \oslash U) \times U`$. <br> $`P \times U = U \times P`$. |
| $`P^* \times U^*`$ | `P^* x U^*` | $`(\cdot , \cdot) \to \cdot`$ | Cross-sum of $P$ and $U$.[^1] | It is the crosspoint of $`P^*`$ and $`U^*`$. <br> $`P=(p:q:r) \land U=(u:v:w) \implies P^* \times U^* = (qw+rv) ::`$. |
| $`\tau(\overleftrightarrow{PU})`$ | `Px-xU` | $`(\cdot , \cdot) \to \cdot`$ | Cross-difference of $P$ and $U$.[^1] | It is the point whose Central Line is the line joining $P$ and $U$. <br> $`P=(p:q:r) \land U=(u:v:w) \implies \tau(\overleftrightarrow{PU}) = (qw-rv) ::`$. |
| $`P*X(48)`$ | `P*X(48)` | $`\cdot \to \cdot`$ | Polar Conjugate of $P$.[^3] | $X(48)$-isoconjugate of $P$. |
| $`P \vee U`$ <br> | `PvU` | $`(\cdot , \cdot) \to \cdot`$ | Cevapoint of $P$ and $U$. <br> (Note that it is the isogonal-conjugate of the cross-sum of $P$ and $U$). | $`P=(p:q:r) \land U=(u:v:w) \implies P \vee U = (qw + rv)^{-1}::`$. <br> Thus, $`P \vee U = (P^* \times U^*)^*`$. <br> Clearly, $`P \vee U = U \vee P`$. <br> $`P = (P/U) \vee U`$. <br> $`P = (P \vee U) / U`$. So, $P$ is Perspector of $((P \vee U)_V)\Delta$ and $(U_V)^{-1}\Delta$. <br> $`U = (P \vee U) / P`$. And, $U$ is Perspector of $((P \vee U)_V)\Delta$ and $(P_V)^{-1}\Delta$. |
| $P.U$ | `P.U` | $`(\cdot , \cdot) \to \cdot`$ | Trilinear Product of $P$ and $U$. | $`P=(p:q:r) \land U=(u:v:w) \implies P.U = pu::`$. |
| $P..U$ | `P..U` | $`(\cdot , \cdot) \to \cdot`$ | Barycentric Product of $P$ and $U$. | $`P=(p:q:r)_b \land U=(u:v:w)_b \implies P..U = (pu::)_b`$. |
| $PU(X)$ | `PU(X)` | $`\cdot \to (\cdot , \cdot)`$ | Bicentric Pair of Triangle Center $X$.[^6] | $`X=(x:y:z) \implies PU(X) = (P(X) = \dfrac{y}{z} : \dfrac{z}{x} : \dfrac{x}{y}, U(X) = \dfrac{z}{y} : \dfrac{x}{z} : \dfrac{y}{x})`$. <br> $P(X)$ is called as the 1st Bicentric Quotient of $X$. <br> $U(X)$ is called as the 2nd Bicentric Quotient of $X$. <br> Note: $`U(X) = (P(X))^*`$. <br> $`P(X^*) = U(X) = (P(X))^*`$. <br> $`U(X^*) = P(X) = (U(X))^*`$. |

> [!TIP]
> Any binary operator which looks <ins>**vertically-symmetric**</ins> is <ins>**commutative**</ins>. eg:
> -  `*` (isoconjugate)
> -  `x-x` (cross-difference)
>     - $\tau(\overleftrightarrow{\\; })$ 
> -  `x` (crosspoint) and (cross-sum)
>     - $\times$ 
> -  `v` (cevapoint)
>     - $\vee$
> - `.` (Trilinear Product)
>     - $.$ 
> - `..` (Barycentric Product)
>     - $..$
> 
> Any binary operator which looks <ins>**vertically-asymmetric**</ins> is <ins>**non-commutative**</ins>. eg:
> - `-v` (ceva-conjugate)
>   - $/$
> - `-x` (cross-conjugate)
>   - $\oslash$
> - `-/` (reciprocal-conjugate)
>   - $/_b$
> 

> [!NOTE]
> For $A$ (`operator`) $B$
> 
> - (`operator`) is "iso" iff $A$ (`operator`) $B$ = $B$ (`operator`) $A$.
> - (`operator`) is "conjugate" iff $A$ (`operator`) ($A$ (`operator`) $B$) = $B$.
>

## Questions

- Is every $P$-something-Conjugate **transformation** an **involution**? \[Since it is called "conjugate" eg $P$-Ceva-Conjugate\]

[^1]: https://faculty.evansville.edu/ck6/encyclopedia/glossary.html
[^2]: Smarandache, Florentin and Ion Patrascu. "THE GEOMETRY OF THE ORTHOLOGICAL TRIANGLES." (2020). Section 1.2, pp. 26. Section 1.3, pp. 31,35,37. https://digitalrepository.unm.edu/math_fsp/260 https://fs.unm.edu/GeometryOrthologicalTriangles.pdf
[^3]: https://faculty.evansville.edu/ck6/encyclopedia/etc.html
[^4]: [./Ceva-Conjugate--Construction-Protocol.html](./Ceva-Conjugate--Construction-Protocol.html)
[^5]: https://mathworld.wolfram.com/Involution.html, https://en.wikipedia.org/wiki/Involution_(mathematics), https://encyclopediaofmath.org/index.php?title=Involution
[^6]: See P(113) in https://faculty.evansville.edu/ck6/encyclopedia/BicentricPairs.html
