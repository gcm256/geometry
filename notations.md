# Notations

| Notation | Type | Description | Notes |
| --- | --- | --- | --- |
| $P$ | $`\cdot`$ | A Point. | $P(\tau)$ = A Point $P$ with Trilinear coordinates $(\tau_1, \tau_2, \tau_3)$.|
| $`P^*`$ | $`\cdot \to \cdot`$ | Isogonal Conjugate of $P$. | $`(P^*)^* = P`$. <br> $`P^* = P*I = P*X(1)`$.[^1] |
| $P^+$ | $`\cdot \to \cdot`$ | Isotomic Conjugate of $P$. | $(P^+)^+ = P$. <br> $`P^+ = P*X(31)`$. |
| $`P^\#`$ | $`\cdot \to \cdot`$ | Cyclocevian Conjugate of $P$. | $`(P^\#)^\# = P`$. <br> $`P^\#`$ = $`((((P^+)^©)^*)^@)^+`$.[^1] |
| $P^@$ | $`\cdot \to \cdot`$ | Anticomplement of $P$. | | 
| $P^©$ | $`\cdot \to \cdot`$ | Complement of $P$. | $(P^©)^@ = P = (P^@)^©$. <br> $(P^©)^© \neq P \iff P \neq G$. <br> $(P^@)^@ \neq P\iff P \neq G$. |
| $P/U$ | $`(\cdot , \cdot) \to \cdot`$ | $P$-Ceva-Conjugate of $U$. | Perspector of $(P_V)\Delta$ and $(U_V)^{-1}\Delta$. <br> $P/P = P$. <br> Since it is called conjugate, is $P/(P/U) = U$❓|
| $P*U$ | $`(\cdot , \cdot) \to \cdot`$ | $P$-isoconjugate of $U$. | $`P=(p:q:r) \land U=(u:v:w) \implies P*U=(p^{-1}u^{-1} ::)`$. <br> $`P*U = U*P`$. <br> $`P*(P*U) = U`$. <br> $`P*P=(p^{-2}::)`$. <br> $`P*(P*P) = P`$. <br> $`(P*P)*U=(p^2/u ::) \neq P*(P*U)=U`$. <br> Thus the isoconjugation operator is commutative but not associative.|
| $`P \div U`$ | $`(\cdot , \cdot) \to \cdot`$ | $P$-reciprocal-conjugate of $U$. | In Barycentric coordinates, $`P=(p:q:r)_b \land U=(u:v:w)_b \implies P \div U=(p/u::)_b`$. <br> $`P \div U = G \div (U \div P)`$. <br> $`P \div P = (1:1:1)_b = G`$.|
| $(P_\perp)\Delta$ | $`(\Delta , \cdot) \to \Delta`$ | Pedal Triangle of $P$ wrt Triangle $\Delta$. | |
| $(P_V)\Delta$ | $`(\Delta , \cdot) \to \Delta`$ | Cevian Triangle of $P$ wrt Triangle $\Delta$. | |
| $(P_\perp)^{-1}\Delta$ | $`(\Delta , \cdot) \to \Delta`$ | AntiPedal Triangle of $P$ wrt Triangle $\Delta$. | $`(P_\perp)(P_\perp)^{-1}\Delta = \Delta = (P_\perp)^{-1}(P_\perp)\Delta`$ |
| $(P_V)^{-1}\Delta$ | $`(\Delta , \cdot) \to \Delta`$ | AntiCevian Triangle of $P$ wrt Triangle $\Delta$. | $`(P_V)(P_V)^{-1}\Delta = \Delta = (P_V)^{-1}(P_V)\Delta`$ |
| $`\mathcal{O}(\Delta _1, \Delta _2)`$ | $`(\Delta, \Delta) \to \mathtt{Boolean}`$ | Triangles $\Delta _1$ and $\Delta _2$ are Orthologic. | $`\mathcal{O}(\Delta _1, \Delta _2) \iff \mathcal{O}(\Delta _2, \Delta _1)`$. $`\mathcal{O}`$ is symmetric. <br> $`\mathcal{O}`$ is reflexive. $`\mathcal{O}_\odot(\Delta, \Delta) = H`$ <br> $`\mathcal{O}`$ is not transitive.[^2]|
| $`\mathcal{O}_\odot(\Delta _1, \Delta _2)`$ | $`(\Delta , \Delta) \to \cdot`$ | The Orthology Center of $\Delta _1$ wrt $\Delta _2$. | $`\mathcal{O}_\odot(\Delta _1, \Delta _2)`$ need not be same as $`\mathcal{O}_\odot(\Delta _2, \Delta _1)`$ |
| $`P \oslash U`$ | $`(\cdot , \cdot) \to \cdot`$ | $P$-Cross-Conjugate of $U$.[^1] | $`P=(p:q:r) \land U=(u:v:w) \implies P \oslash U  =u(-pu^{-1} + qv^{-1} + rw^{-1})^{-1} ::`$. <br><br> $`P \oslash U = \dfrac{u}{p} \tau_1(U/P)::`$. <br><br> $`P/U = \dfrac{u}{p} \tau_1(U \oslash P) ::`$. <br> $`P \oslash U \neq U \oslash P`$. |
| $`P \times U`$ | $`(\cdot , \cdot) \to \cdot`$ | Crosspoint of $P$ and $U$.[^1] | $`P=(p:q:r) \land U=(u:v:w) \implies P \times U = pu(qw+rv) ::`$. <br> $`(P \times U) \oslash U = P = (P \oslash U) \times U`$. <br> $`P \times U = U \times P`$. |
| $`P^* \times U^*`$ | $`(\cdot , \cdot) \to \cdot`$ | Cross-sum of $P$ and $U$.[^1] | It is the crosspoint of $`P^*`$ and $`U^*`$. <br> $`P=(p:q:r) \land U=(u:v:w) \implies P^* \times U^* = (qw+rv) ::`$. |
| $`\tau(\overline{PU})`$ | $`(\cdot , \cdot) \to \cdot`$ | Cross-difference of $P$ and $U$.[^1] | It is the point whose Central Line is the line joining $P$ and $U$. <br> $`P=(p:q:r) \land U=(u:v:w) \implies \tau(\overline{PU}) = (qw-rv) ::`$. |
| $`P*X(48)`$ | $`\cdot \to \cdot`$ | Polar Conjugate of $P$.[^3] | $X(48)$-isoconjugate of $P$. |

[^1]: https://faculty.evansville.edu/ck6/encyclopedia/glossary.html
[^2]: Smarandache, Florentin and Ion Patrascu. "THE GEOMETRY OF THE ORTHOLOGICAL TRIANGLES." (2020). Section 1.2, pp. 26. Section 1.3, pp. 31,35,37. https://digitalrepository.unm.edu/math_fsp/260 https://fs.unm.edu/GeometryOrthologicalTriangles.pdf
[^3]: https://faculty.evansville.edu/ck6/encyclopedia/etc.html
