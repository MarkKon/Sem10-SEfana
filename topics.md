# Themen Seminar Funktionalanalysis SS2023

## K

1. Produktintegrale:
  - gewöhnliches Riemannintegral $\int_a^b g(t) dt = \lim_{|\mathcal R|\to 0}\sum_{j=1}^{n(\mathcal R)}(\xi_j-\xi_{j-1} g(\alpha_j)$, $\mathcal R = ((\xi_j)_{j= 0}^{n(\mathcal R)}, (\alpha_j)_{j= 1}^{n(\mathcal R)})$
  - Sei $A: [a,b]\to L_b(X)$. Definiere 
     $$ P_\up(A, \mathcal R) = \prod_{j= n(\mathcal R)}^1 (I + (\xi_j-\xi_{j-1})A(\alpha_j) = (I + (\xi_n-\xi_{n-1})A(\alpha_n)\cdot \dots \cdot ((I + (\xi_1-\xi_{0})A(\alpha_1)$$
     und analog: $$ P_\down(A, \mathcal R) = \prod^{j= n(\mathcal R)}_1 (I + (\xi_j-\xi_{j-1})A(\alpha_j) = (I + (\xi_1-\xi_0)A(\alpha_n)\cdot \dots \cdot ((I + (\xi_n-\xi_{n-1})A(\alpha_n)$$
  - Betrachte dann $\lim_{|\mathcal R|}\to 0}P_\up (A,\mathcal R) = \prod_a^b(I+A(t)dt)$ und analog $\lim_{|\mathcal R|}\to 0}P_\down (A,\mathcal R) =: (I+A(t)dt)\prod_a^b$
2. ...:
  - $f:(0,+\infty)\to \mathbb R$ heißt completely monotone genau dann wenn $f\in C^\infty, (-1)^nf^{(n)} \geq 0 \forall n\in \mathbb N\cup \{0\}$.
  - Satz von Berstein: $f$ completely monotone genau dann wenn $\exists \mu$ positives Maß auf den Borelmengen von $[0,+\infty)$ mit $f(\lambda) = \int_{[0,+\infty)} e^{-\lambda t}d\mu(t)$
  - Erinnere Laplace Transformation: $\mathcal L(f)(\lambda) = \int_{[0,+\infty)}e^{-\lambda t}f(t) d\lamba(t)$
  - Inhalt: Beweis des Satzes und Beziehung zur Trafo
3. Subnormal Operators
  - $S\in L_b(H)$ heißt Subnormal genau dann wenn $\exists N\in L_b(\tilde H), \tilde H\supseteq H, N(H)\subseteq H, S = N|_H, N$ normal.
  - Betrachte $N: H\oplus H^\perp \to H\oplus H^\perp$ als Blockoperation (Matrixschreibweise), dann geben die Eigenschaften die Darstellung $$S&N_{12}\\ 0&N_{22}$$
  - $S\in L_b(H)$ heißt quasinormal genau dann wenn $S(S^*S) = (S^*S)S$. Daraus folgt subnormal.
4. Double Operator Integrals:
  - $H$ Hilbertraum, $T\in L_b(H), E,F$ Spektralmaße (die im Allgemeinen nicht kommutieren) für $\langle \mathbb R, \mathcal A_\sigma(\mathcal T_1), H\rangle, \phi: \mathbb R\times mathbb R \to \mathbb R$. Dieses $\phi$ "kompliziert".
  - Definiere $W(T) = \int\int\phi(s,t)dF(t)TdE(s)

## W
