#                           Die Gruppen mit

#                  quadratfreier Ordnungszahl

##                                         by Otto Hölder

From the number-theoretical properties of a group's order, one can sometimes deduce the character of the group. In various cases, one recognizes the composite nature or solvability of a group from its order. Sylow established the first theorem in this direction. According to this theorem, every group whose order has the form

$$
p_1^{k_1}p_2^{k_2}\ldots p_r^{k_r}
$$

where $p_1, p_2, \ldots p_r$ represent distinct prime numbers, and

$$
p_i > p_{i+1}^{k_{i+1}}p_{i+2}^{k_{i+2}}\ldots p_r^{k_r}
$$

is assumed, is solvable. In particular, a group is solvable when its order is a power of a prime number. A very general theorem was later shown by me, proving that every group whose order consists of only three prime numbers is solvable. Following this, Frobenius noted that the same holds true when the order consists of four prime numbers but is different from 60. Frobenius simultaneously gained a more general result by proving that every group is solvable whose order arises through multiplication of arbitrarily many but unequal prime numbers.

With the help of these results from Frobenius, I have now succeeded in determining all existing groups for the orders of the aforementioned type, namely those that are not divisible by a square. In doing so, the surprising result has emerged that all these groups can be represented by metacyclic letter permutations and are thus of a known form.

Through earlier investigations by Netto, Young, Cole and Glover, and by me, the groups of orders $p^2$, $p^3$, $p^4$, $pq$, $pq^2$, $pqr$ have been established, where $p$, $q$, $r$ should denote prime numbers. The present work thus resolves new series of orders.

§1.
Prerequisites.

From the mentioned treatise by Frobenius, I will use the following two theorems:
1) If the prime numbers $p_1, p_2, \ldots p_r$ are different, where simultaneously

$$
p_1 > p_2 > \ldots > p_r
$$

is assumed, then a group of order $p_1p_2\ldots p_r$ contains for each $\lambda$ one and only one subgroup of order $p_1p_2\ldots p_\lambda$.
2) If $\mathfrak{G}$ is an invariant (distinguished) subgroup of $G$, and if $g$ and $q$ are the orders of $\mathfrak{G}$ and $G$, and if the numbers $g$ and $\frac{q}{g}$ are coprime, then $\mathfrak{G}$ consists of all elements of $G$ whose order divides $g$.

§2.
Distinguished Cyclic Subgroups.

Now let a group $G$ be given whose order is not divisible by a square. It follows from the first of the aforementioned Frobenius theorems, when $\lambda = 1$ is set, that in the group $G$ there exists a subgroup of prime order which is simultaneously the only one of its order, thus a distinguished (invariant) subgroup. Let us assume there are $s$ different distinguished subgroups of prime order, and specifically of orders $q_1, q_2, \ldots q_s$ present; these subgroups may be generated in sequence by the operations $T_1, T_2, \ldots T_s$. The prime numbers $q_1, q_2, \ldots q_s$ are then different from each other. If namely $m_\mu \cdot q_\mu$ is the order of group $G$, then since this order contains no square, $m_\mu$ must not be divisible by $q_\mu$. One can now apply to the subgroup $\mathfrak{G}$ consisting of powers of $T_\mu$ theorem 2) from §1. If therefore $q_\nu = q_\mu$ were true, then $T_\nu$ would have to be contained in $\mathfrak{G}$ and thus be equal to a power of $T_\mu$. This contradicts the circumstance that the groups generated by $T_\mu$ and by $T_\nu$ should be different. Furthermore

$$
(T_\nu^{-1}T_\mu^{-1}T_\nu)T_\mu = T_\mu^2(T_\nu^{-1}T_\mu T_\nu)
$$

must be equal to both a power of $T_\mu$ and of $T_\nu$ and consequently equal to the identity. Thus

$$
T_\mu T_\nu = T_\nu T_\mu
$$

i.e., the operations $T_1, T_2, \ldots T_s$ can be interchanged with each other.

For interchangeable operations, an important theorem holds. If namely two such operations are of orders $\varrho$ and $\sigma$, and if $\varrho$ and $\sigma$ are coprime, then the product of the operations is of order $\varrho\cdot\sigma$. From this it follows for the product

$$
T = T_1\cdot T_2\ldots T_s
$$

of $s$ factors, that its order equals

$$
n = q_1\cdot q_2\ldots q_s
$$

The group $H$ formed by the powers of $T$ consists of the totality of all $T_1, T_2, \ldots T_s$ combined operations, and therefore $H$ is also a distinguished subgroup of the total group $G$.

It can be easily shown that every distinguished cyclic subgroup $\mathfrak{H}$ of the total group $G$ must be contained in $H$. If namely $\mathfrak{H}$ consists of the powers of operation $Q$, and if $Q$ did not belong to group $H$, then according to the second of the theorems cited in §1, the order of $Q$ could not divide $n$. This order would thus contain a prime number $p$ different from $q_1\ldots q_s$. The group $\mathfrak{H}$ would then, since it is cyclic, contain only one subgroup of $p$th order which, if $\mathfrak{H}$ is distinguished in $G$, must likewise be distinguished in $G$. This however contradicts the assumption made at the beginning that those $s$ groups are the only distinguished subgroups of prime order in group $G$.

Thus there exists at least one distinguished cyclic subgroup with mutually different order numbers. The largest of these contains all others.

§3.
Behaviour of the Remaining Operations to Operation $T$.

Apart from the powers of $T$, no operation is interchangeable with $T$. If namely $Q$ is not equal to any power of $T$, thus not contained in $H$, then from the reasons given in the previous paragraph, the order of $Q$ must contain a prime number $p$ different from $q_1, q_2, \ldots q_s$. If now $Q$ were interchangeable with $T$, then the same would have to be true of a power $R$ of $Q$ whose order equals $p$. If there exist different types of operations $R$ interchangeable with $T$ whose order is a prime number not contained in $q_1q_2\ldots q_s$, then one chooses the operation $R$ so that its prime order $p$ is as large as possible. The group of $p$th order consisting of the powers of $R$ is not contained in $H$ and is therefore according to §1 not contained in $G$ in a distinguished manner; there exists therefore in $G$ an operation $R'$ equivalent to $R$ which is not equal to any power of $R$. Since now the equation

$$
TR = RT
$$

existed, it follows, by transforming this equation with a suitable operation, that

$$
T^bR' = R'T
$$

where $b$ is in any case relatively prime to the order $n$ of operation $T$. Thus $R'$ is also interchangeable with $T$.

If one now thinks through combination of operations $R, R', T$ a group $J$ of order $m'\cdot p\cdot n$ derived, then $T$ must be interchangeable with all operations of this group. Let $p'$ be any prime factor of $m'$, then $p' < p$. Since namely $J$ according to Cauchy's theorem contains an operation of order $p'$, and this operation is interchangeable with $T$, the assumption $p' > p$ would contradict the circumstance that operation $R$ was chosen with the largest possible order. The number $m'p$, which is a divisor of the total group's order, contains no prime number twice and has in $p$, as we now know, its largest prime divisor. The group $J/H$, which arises from $J$ when $T$ is set equivalent to the identity, has order $m'p$; it also contains according to §1, 1) a unique subgroup of $p$th order. Two operations of $p$th order that belong to group $J/H$ are therefore powers of each other. The operations $R$ and $R'$ are operations of $p$th order in group $G$. If one considers these operations mod $H$, so it would also be conceivable that the order reduced; it would however then have to reduce to a proper divisor of $p$, i.e., to 1. This is impossible because $R$ is not contained in $H$. The operations $R$ and $R'$ therefore correspond in group $J/H$ to two operations of $p$th order; they are therefore $R$ and $R'$ mod $H$ powers of each other equivalent. One thus obtains the equation

$$
R' = R^\varrho T^\sigma
$$

This equation is contradictory. If namely $\sigma$ is divisible by $n$, then it follows, contrary to the assumption made in the introduction of $R'$, that $R'$ is a power of $R$. If however $\sigma$ is not divisible by $n$, then the order of an operation which has the form $R^\varrho T^\sigma$ must be divisible by one of the prime numbers $q_1, q_2, \ldots q_s$, while the order $p$ of $R'$ is not this.

§4.
Composition of the Group from Two Cyclic Groups.

The group $G$ to be investigated shall be of order $m\cdot n$, where again $n$ denotes the order of the largest distinguished and cyclic subgroup $H$ of $G$. The number $m$ is, just like $mn$, equal to a product of unequal prime numbers:

$$
m = p_1p_2\ldots p_r
$$

One can assume that

$$
p_1 > p_2 > p_3 > \ldots > p_r
$$

According to Cauchy's theorem, $r$ operations $S_1, S_2$, $S_3\ldots S_r$ can be found, which respectively have the orders $p_1, p_2, p_3,\ldots p_r$.

If one now transforms operation $S_i$ with $S_j$, one obtains an operation $S_i'$ of order $p_i$. The group $G/H$, which is of $m$th order, contains according to §1, 1) a unique subgroup of $p_i$th order; therefore the operations $S_i$ and $S_i'$ are mod $H$ powers of each other. This means that an equation of the form

(1)                               
$$
S_i^{-1}S_jS_i = S_i' = S_i^QT^\sigma
$$
exists, in which $\varrho$ is not divisible by $p_i$. Since group $H$ is distinguished in $G$, the relation

(2)        
$$
S_i^{-1}TS_i = T^b
$$

exists, which through raising to the power $b$ and through multiple transformations with $S_i$ yields that

(3)                               
$$
S_i^{-\tau}T^bS_i = T^{bk}
$$


If one now sets $b = 1$ and $\tau = p_i$, one obtains the congruence
$$
k^{p_i} \equiv 1 \bmod n
$$
The number $k$, which is relatively prime to $n$, will thus mod $n$ either belong to exponent 1 or to exponent $p_i$. According to §3, $k$ cannot be interchangeable with $T$; it follows also from equation (2) that $k$ is incongruent to one, thus mod $n$ belongs to exponent $p_1$. Equation (2) is now transformed with $S_i$, whereby $S_i$ transitions to $S_i'$ and $T$ to $T^c$; $c$ is relatively prime to $n$. One thus finds the equation
$$
S_i'^{-1}T^cS_i' = T^{ck}
$$
which with respect to the expression given in (1) for $S_i'$ yields the following:
$$
S_i^{-Q}T^{\sigma Q}S_i^Q = T^{ck}
$$
Equation (3) however yields
$$
S_i^{-\tau}T^QS_i^\tau = T^{Qk}
$$
and through comparison of the last two formulas one finds
$$
k^{Q-1} \equiv 1 \bmod n
$$
Because however $k$ mod $n$ belongs to exponent $p_1$, $\varrho-1$ must be divisible by $p_1$. Equation (1) therefore transforms into

$$
S_i^{-1}S_jS_i = S_iT^\sigma
$$

or
$$
S_iS_j = S_jS_iT^\sigma
$$

The operations $S_i$ and $S_j$ are mod $H$ interchangeable with each other.

One proves exactly the same way that operation $S_1$ mod $H$ can be interchanged with every operation of the series $S_2, S_3,\ldots S_r$. It shall now be shown that any two of the operations $S_1, S_2,\ldots S_r$ can be interchanged mod $H$. Assuming it has already been proven that $S_1, S_2,\ldots S_\alpha$ are interchangeable among themselves and with $S_{\alpha+1}, S_{\alpha+2},\ldots S_r$ mod $H$, one proceeds as follows. Let

$$
\mathfrak{S} = S_1S_2S_3\ldots S_{\alpha+1}
$$

Since the operations $S_1, S_2, S_3,\ldots S_{\alpha+1}$ mod $H$ can be interchanged with each other and individually are of orders $p_1, p_2,\ldots p_{\alpha+1}$, $\mathfrak{S}$ mod $H$ is of order $\mathfrak{p} = p_1p_2\ldots p_{\alpha+1}$. The powers of operation $\mathfrak{S}$, when considered mod $H$, form a subgroup of $\mathfrak{p}$th order of group $G/H$. This subgroup, which may be called $\mathfrak{G}$, is according to the theorem of Frobenius cited in §1, 1) the unique subgroup of $\mathfrak{p}$th order, thus a distinguished subgroup of $G/H$. Every operation of group $G/H$ that is of $p_{\alpha+1}$th order must according to §1, 2) be contained in group $\mathfrak{G}$; this group however, as a cyclic group, contains only one subgroup of $p_{\alpha+1}$th order, so that thus two operations of this order that belong to group $G/H$ must be powers of each other. If now $S_\beta$ is any operation of the series $S_{\alpha+2}, S_{\alpha+3},\ldots S_r$, then the two operations

$$
S_\beta^{-1}S_{\alpha+1}S_\beta, S_{\alpha+1}
$$

are both in absolute sense and mod $H$ of $p_{\alpha+1}$th order. These two operations are thus mod $H$ powers of each other, i.e.,

$$
S_\beta^{-1}S_{\alpha+1}S_\beta = S_{\alpha+1}^QT^\sigma
$$

Since this equation now takes the place of (1), the conclusions drawn earlier for $S_i$ and $S_j$ can be applied to $S_{\alpha+1}$ and $S_\beta$

It follows that

$$
S_{\alpha+1}S_\beta = S_\beta S_{\alpha+1}T^\sigma
$$

Now one thus knows that $S_1, S_2,\ldots S_{\alpha+1}$ can be interchanged with each other and with $S_{\alpha+2}, S_{\alpha+3},\ldots S_r$ mod $H$. By continuing to conclude in this way, one finds that mod $H$ all operations $S_1, S_2,\ldots S_r$ are interchangeable with each other. Thus with

$$
S' = S_1S_2\ldots S_r \bmod H
$$

is an operation of $m$th order, which generates the entire group $G/H$.

If $G$ is a group whose order contains no square and if $H$ is its largest distinguished cyclic subgroup, then $G/H$ is a cyclic group. The group $G$ can be composed of two cyclic groups. An algebraic equation with the Galois group $G$ is thereby solved by first solving an ordinary Abel equation of $m$th order and then under adjunction of a root of this equation solving a second ordinary Abel equation.

§5.
Relations.

The operation $S'$ introduced in the previous paragraph is mod $H$ of order $m$, its absolute order is some multiple of $m$. Thus a suitable power of $S'$, which we shall denote with $S$, will have the absolute order $m$. The following relations now arise

(4)                              
$$
S^m = 1, S^{-1}TS = T^a, T^n = 1
$$
When one transforms operation $T$ with operation $S$ $m$ times, one obtains the congruence

5)
$$
a^m \equiv 1 \bmod n
$$

The number $a$ however can mod $n$ belong to no proper divisor of $m$ as exponent; if for example

$$
a^{\frac{m}{p_1}} \equiv 1 \bmod n
$$
so the operation $S^{h}$, which is not equal to any power of $T$, would be interchangeable with $T$, which contradicts the result of the third paragraph. Thus $a$ must also belong to exponent $m$, i.e., each of the prime numbers $p_1$, $p_2$, ..., $p_r$ must be a divisor of at least one of the differences $q_1-1$, $q_2-1$, ..., $q_t-1$.

The group $G$ is of order $mn$ and is generated by $S$ and $T$ according to the results of the previous paragraph. One can therefore take the equations (4), which allow every expression combined from $S$ and $T$ to be reduced to one of the forms

$$
S^hT^k \quad \left(\begin{array}{l}h = 0, 1, 2, \ldots m-1\\k = 0, 1, 2, \ldots n-1\end{array}\right)
$$

as the defining relations of the presupposed group $G$.

If one now conversely takes two numbers $m$ and $n$ at will, but such that $mn$ is not divisible by any square, and chooses a number $a$ according to congruence (5), then the relations (4) must define a group in Dyck's sense. According to a principle I established in volume 43 of the Mathematical Annals p. 334, this group is indeed of order $mn$. If furthermore $m$ is a divisor of $\phi(n)$, and $a$ mod $n$ belongs to exponent $m$, then in the defined group the subgroup consisting of the powers of $T$ is also the largest cyclic distinguished subgroup. According to the result of the second paragraph, such a largest subgroup must exist and contain the powers of $T$. But under the assumptions now made, one easily calculates from relations (4) that no operation, except the powers of $T$, is interchangeable with $T$. Therefore that largest cyclic distinguished subgroup reduces to the group of order $n$ generated by $T$.

If one now introduces $n$ letters $x_\xi$ where $\xi$ runs through the residues of modulus $n$, then one can represent the substitutions of our group through the $m \cdot n$ letter permutations

$$
\left(\begin{array}{c}\xi\\a^h\xi + k\end{array}\right) \quad \left(\begin{array}{l}h = 0, 1, 2, \ldots m-1\\k = 0, 1, 2, \ldots n-1\end{array}\right)
$$

These letter permutations are metacyclic.

§6. 
Species. Distinction of Groups.

For each of the groups considered here, their order and the order of their largest cyclic and distinguished subgroup is characteristic in the first place. We want to count two groups which have the same two numbers $n$ and $m$ in common as belonging to the same species. The different groups of one species still need to be distinguished.

Let $G$ and $G'$ be two groups of the same species, $G$ represented by formulas (4), $G'$ by the formulas

$$
S'^m = 1, \quad S'^{l-1}T'S' = T'^{a'}, \quad T'^n = 1.
$$

If the groups $G$ and $G'$ are to be holoedrically isomorphic, then the largest cyclic and distinguished subgroup of $G$ must correspond to the largest cyclic and distinguished subgroup of $G'$. The operation $T$ corresponds to $T'^l$, the operation $S$ corresponds to $S'^hT'^k$. Since between $S$ and $T$ the relation

$$
S^{-1}TS = T^a
$$

exists, there must also be for the corresponding operations

$$
(S'^hT'^k)^{-1}T'^l(S'^hT'^k) = T'^{al}
$$

This equation yields with help of (6)

$$
a^h \cdot l \equiv al \pmod{n},
$$

and since $l$ must be relatively prime to $n$, $a$ is congruent to a power of $a'$. This is also sufficient for the isomorphism; because when the congruence $a^h \equiv a \pmod{n}$ exists, one only needs to assign the operations $T'$ and $S'^h$ of group $G'$ to the operations $T$ and $S$ of group $G$ to obtain an isomorphism. Thus one obtains the result:

All groups of a certain species are obtained by inserting into relations (4) for all numbers belonging to exponent $m$ mod $n$. Two numbers $a$ that are powers of each other mod $n$ yield the same group, so that thus each $\phi(m)$ incongruent residues of modulus $n$ lead to the same group.

§7.
Number of Groups.

To determine the number of all groups contained in one species, one has according to the preceding to calculate the number of residues $a$ belonging to exponent $m$ of modulus $n$ and divide this number by $\phi(m)$. One can now decompose the number $a$ into a product of numbers that respectively belong to the exponents $p_1$, $p_2$, ..., $p_r$. For this purpose define the numbers $b_\alpha$ through the congruences

$$
b_\alpha^\frac{m}{p_\alpha} \equiv 1 \pmod{p_\alpha} \quad (\alpha = 1, 2, \ldots r).
$$

It is now easy to see, since $m = p_1p_2...p_r$, that

$$
b_1\frac{m}{p_1} + b_2\frac{m}{p_2} + \cdots + b_r\frac{m}{p_r} \equiv 1 \pmod{m},
$$

and if one sets

$$
a^{b_\alpha\frac{m}{p_\alpha}} \equiv a_\alpha \pmod{n}
$$

then the decomposition

$$
a \equiv a^{b_1\frac{m}{p_1}}a^{b_2\frac{m}{p_2}}\cdots a^{b_r\frac{m}{p_r}} \equiv a_1a_2\cdots a_r \pmod{n}
$$

follows.

From the determination of $b_\alpha$ it follows that $b_\alpha$ is relatively prime to $p_\alpha$, and therefore $a_\alpha$ belongs to exponent $p_\alpha$.

If on the other hand one chooses $r$ residues $a_1$, $a_2$, ..., $a_r$ of modulus $n$ such that they belong to the exponents $p_1$, $p_2$, ..., $p_r$ respectively, otherwise arbitrarily, then their product $a$ is a number belonging to exponent $m$, and it follows by itself that

$$
a^{b_\alpha\frac{m}{p_\alpha}} \equiv a_\alpha \pmod{n}.
$$

It follows from these considerations that a residue $a$ belonging to exponent $m$ can be decomposed, and in only one way, into components that belong to the exponents $p_1$, $p_2$, ..., $p_r$, and that conversely these components can be chosen somehow and independently of each other corresponding to their exponents.

Now the component $a_\alpha$, which belongs to exponent $p_\alpha$ with respect to modulus $n$, must belong with respect to each of the moduli $q_1$, $q_2$, ..., $q_t$ contained in $n$ to exponent 1 or to exponent $p_\alpha$ and at least with respect to one of these moduli $q$ to exponent $p_\alpha$. If $q_\alpha$ is a number for which $q_\alpha-1$ is not divisible by $p_\alpha$, then $a_\alpha \equiv 1 \pmod{q_\alpha}$. If $q_\alpha$ is a number for which $q_\alpha-1$ is divisible by $p_\alpha$, then $a_\alpha \pmod{q_\alpha}$ can first take $p_\alpha$ values; these values that $a_\alpha$ can take with respect to the different moduli $q_\alpha$ can be combined in any way, only they must not all be congruent to 1. We now establish that $c_\alpha$ should mean the number of differences $q_1-1$, $q_2-1$, ..., $q_t-1$ that contain the factor $p_\alpha$. It then follows that $a_\alpha \pmod{n}$ can be taken in $p_\alpha^{c_\alpha}-1$ ways, thus

$$
a \equiv a_1a_2 \ldots a_r \pmod{n}
$$

can be taken in

$$
\prod_{\alpha=1}^r(p_\alpha^{c_\alpha}-1)
$$

ways.

The number of groups in the species characterized by the numbers $m$ and $n$ is

$$
\prod_{\alpha=1}^r\frac{p_\alpha^{c_\alpha}-1}{p_\alpha-1}.
$$

§8.
Division into Species.

If a given group $G$, whose largest cyclic and distinguished subgroup is of order $n$, is to be represented by relations of the form (4), then the number $a$ is only arbitrary up to a certain degree. This number belongs mod $n$ to exponent $m$, and one can set for it, without changing the group, another such number that is simultaneously congruent to a power $a^h$ of $a$; here $h$ must be relatively prime to $m$. When $h_1$, $h_2$, ..., $h_t$ denote the smallest positive residues of $h$ with respect to the moduli $p_1$, $p_2$, ..., $p_r$ contained in $m$, then these residues can independently take on the values 1, 2, ..., $p_1-1$; 1, 2, ..., $p_2-1$; 1, 2, ..., $p_r-1$.

As a consequence of equation (7) we have

$$
a' \equiv a_1^{h_1} a_2^{h_2} \ldots a_r^{h_r} \pmod{n};
$$

one can thus, without changing the group, let the numbers $a_1^{h_1}, a_2^{h_2}, \ldots a_r^{h_r}$ take the place of $a_1, a_2, \ldots a_r$. If therefore $q$, $q'$, $q''$... denote those prime divisors of $n$ with respect to which $a_1$ belongs to exponent $p_1$, then due to the arbitrariness in $h_1$, one can let any number take the place of $a_1$ which, for example, is congruent mod $q$ to some number belonging to exponent $p_1$; but then the residues of $a_1$ with respect to the moduli $q'$, $q''$, ... are determined such that these residues can no longer be chosen.

We now want to call two prime numbers $p_\alpha$ and $q_\sigma$ conjugate in group $G$ when the number $a_\alpha \pmod{q_\sigma}$ belongs to exponent $p_\alpha$. This definition is independent of the arbitrariness still present in the representation of the group. When $p_\alpha$ with $q_\sigma$ is conjugate, then $p_\alpha$ is a divisor of $q_\sigma-1$. Each number $p_\alpha$ is conjugate with at least one of the numbers $q_1, q_2, \ldots q_t$.

The considered groups can now be characterized up to a certain degree through symbols. For example, the symbol

$$
\overline{3, \overline{5; 7}, 31, 61}
$$

shall represent all groups of order 3.5.7.31.61 whose largest cyclic and distinguished subgroup is of order 7.31.61, and in which 3 and 7, 3 and 31, 3 and 61, 5 and 31, 5 and 61 are pairs of conjugate prime numbers. The groups that are represented by the same symbol shall be grouped together. Groups of the same species are of the same type when the same prime number pairs are conjugate in them.

How one finds all groups of one type may be shown using the example (8) just mentioned. If we set

$$
p_1 = 3, \quad p_2 = 5, \quad q_1 = 7, \quad q_2 = 31, \quad q_3 = 61,
$$

then one has to determine two numbers $a_1$ and $a_2$ with respect to the three moduli 7, 31 and 61. Now $a_1$ must belong to exponent $p_1 = 3$ with respect to each of these moduli, since $p_1$ is conjugate with $q_1$, $q_2$ and $q_3$. However, one can set $a_1$ with respect to one of the moduli, for example with respect to modulus 7, congruent to any residue belonging to exponent 3, without the group being more precisely determined thereby. Afterwards however, to obtain all groups, one must give the number $a_1$ both residues belonging to exponent 3 of modulus 31 and both residues belonging to the same exponent of modulus 61 and combine these residues in all possible ways. This gives therefore 4 ways of determining $a_1 \pmod{n}$. The number $a_2$ is, since $p_2$ is not conjugate with $q_1$, congruent to 1 mod 7. With respect to mod 31 one can set $a_2$ congruent to any residue belonging to exponent 5; but then the number $a_2$ mod 61 can be given four residues. Since $a \equiv a_1a_2 \pmod{n}$, sixteen ways of determination for $a \pmod{n}$ result. The type represented by the above symbol thus contains 16 different groups.

We want to set up another example of all species and types of groups. We choose the order 3.5.31.61. First the order number must be decomposed into a product $m \cdot n$ where $m$ and $n$ are relatively prime, and each prime factor of $m$ must be contained in at least one of the differences $q_1-1$, $q_2-1$, ..., $q_t-1$. One thus obtains four possible decompositions: $m = 1$, $n = 3.5.31.61$ or $m = 3$, $n = 5.31.61$ or $m = 5$, $n = 3.31.61$ or $m = 3.5$, $n = 31.61$; thereby arise four species. The first species yields only one type, in which one single group, the cyclic group of order 3.5.31.61 is contained. The second species yields three types, represented by the symbols

$$
\overline{3, 5, 31, 61} \quad \overline{3; 5, 31, 61} \quad \overline{3; 5, 31, 61}
$$

The third species also comprises three types, namely

$$
\overline{5; 3, 31, 61} \quad \overline{5; 3, 31, 61} \quad \overline{5; 3, 31, 61}
$$

In the fourth species are the 9 types

$$
\begin{array}{ccc}
\overline{3, 5; 31, 61} & \overline{3, 5; 31, 61} & \overline{3, 5; 31, 61} \\
\overline{3, 5; 31, 61} & \overline{3, 5; 31, 61} & \overline{3, 5; 31, 61} \\
\overline{3, 5; 31, 61} & \overline{3, 5; 31, 61} & \overline{3, 5; 31, 61}
\end{array}
$$

contained. Thus 16 types have resulted. Of these contain the 4th, 14th, 15th two groups each, the 7th, 10th, 13th, 13te four groups; the last type contains 8 groups, all other types consist of a single group.

The number of types of a species is generally

$$
\prod_{\alpha=1}^r(2^{c_\alpha}-1),
$$

where $c_\alpha$ means the same as in the previous paragraph; the number of different groups of a type is

$$
\prod_{\alpha=1}^r(p_\alpha-1)^{e_\alpha-1},
$$

where $p_\alpha$ is conjugate with $e_\alpha$ prime numbers of the series $q_1, q_2, \ldots q_t$.

§9.
Decomposable and Indecomposable Types.

From the symbol one recognizes whether the groups it represents decompose or not. Groups of the same type are either all decomposable or all indecomposable. Indeed the following will be proved. A group is indecomposable when in the symbol that represents its type, all prime numbers are directly or indirectly connected; in the other case the group is decomposable. From this it follows that, for example, the type

$$
\overline{3, \overline{5; 31}, 61}
$$

is an indecomposable one, while for example each group of the type

$$
\overline{3, 5; 31, 61}
$$

decomposes. The order 3.5.31.61 contains in total 11 decomposable types with together 15 groups and 5 indecomposable types with 20 groups.

For the purpose of the proof one starts from equations (4). If one further sets (compare §7)

$$
S = S_1S_2 \ldots S_r, \quad S_\alpha = S^{b_\alpha\frac{m}{p_\alpha}},
$$

whereby $S$ is decomposed into components of orders $p_1^{k_1}$, $p_2^{k_2}$, ..., $p_r^{k_r}$, and if one similarly decomposes $T$ according to the formula

$$
T = T_1T_2 \ldots T_t
$$

into operations of orders $q_1^{k_1}$, $q_2^{k_2}$, ..., $q_t^{k_t}$, then generally

$$
T_\mu S_\alpha = S_\alpha T_\mu^{a_\alpha}.
$$

If now $p_\alpha$ and $q_\mu$ are not conjugate, then $a_\alpha \equiv 1 \pmod{q_\mu}$, and $S_\alpha$ is interchangeable with $T_\mu$; if $p_\alpha$ and $q_\mu$ are conjugate, this is not the case.

If then the prime numbers $p_1, p_2, \ldots p_r, q_1, q_2, \ldots q_t$ can be divided into two categories such that no prime number of one category is conjugate with a prime number of the other category, then let the prime numbers $p$ of the first category be denoted by $p_\beta$, the prime numbers $p$ of the second category by $p_\gamma$, the prime numbers $q$ of the first category by $q_\beta$, the prime numbers $q$ of the second category by $q_\gamma$. The operations $S_\beta$ and the operations $T_\beta$ then generate a group of order $\prod p_\beta\prod q_\beta$ of operations $A$, and the operations $S_\gamma$ generate with the operations $T_\gamma$ a group of order $\prod p_\gamma\prod q_\gamma$ of operations $B$. At the same time it can be recognized that each operation $A$ may be interchanged with each operation $B$, and that each operation of the total group $G$ can be put in the form $AB$ in exactly one way. Thus group $G$ decomposes.

The group $G$ can decompose only in this way. If namely the operations of $G$ can be put in the indicated way in the form $AB$, and if $A_o B_o$ is a particular operation, then $\prod p_\gamma\prod q_\gamma$ is their order, i.e., the least common multiple of the orders of $A_o$ and $B_o$. But since the order of the group consisting of operations $A$ divides the order of the group $B$, because otherwise the order of the total group would have to contain a square, the order of $A_o B_o$ equals the product of the orders of $A_o$ and $B_o$. Each operation of prime order thus belongs to either the $A$ or to the $B$, and therefore the operations $S_1, S_2, \ldots S_r$, $T_1, T_2, \ldots T_t$ and thus also the prime numbers $p_1, p_2, \ldots p_r$, $q_1, q_2, \ldots q_t$ must be able to be divided in the indicated way into 2 categories.

§ 10.
Distribution of Operations within a Group.

The classification of operations of one of our groups remains to be undertaken. Let $Q = S^hT^i$; we determine the order of $Q$ and the operations equivalent to $Q$. From the second of equations (4) follows

$$
T^iS^h = S^hT^{ia^h}
$$

and from this follows further

$$
(S^hT^i)^s = S^hT^iS^hT^i\ldots S^hT^i = S^{sh}T^{i(1+a^h+a^{2h}+\cdots+a^{(s-1)h})}
$$

For $Q^t = 1$ to hold, it is necessary that

$$
hk \equiv 0 \bmod m
$$

$$
i(1 + a^h + a^{2h} + \cdots + a^{(t-1)h}) \equiv 0 \bmod n
$$

Of the prime numbers in the sequence $p_1, p_2, \ldots p_r$, let those that are contained in $h$ be denoted by $p_2$, and those that are not contained in $h$ be denoted by $p_1$. A prime number $q$ that is conjugate with at least one of the prime numbers $p_2$ shall be called $q_2$; a prime number $q$ that is not conjugate with any of the prime numbers $p_1$ shall be called $q_1$ if it is contained in $i$, and $q_2$ if it is not contained in $i$.

The congruence (10) requires that $h$ must be divisible by all prime numbers $p_1$. If, on the other hand, one takes $h$ this way, then congruence (10) is satisfied, and simultaneously

$$
(1-a^h)(1+a^h+a^{2h}+\cdots+a^{(t-1)h}) = -a^h+1 \equiv 0 \bmod n
$$

since $a \bmod n$ belongs to the exponent $m$. Now congruence (11) is to be decomposed into $s$ congruences with moduli $q_1, q_2, \ldots q_s$, and one recognizes from (12) that (11) $\bmod q_u$ is automatically satisfied if only $a^h \bmod q_u$ is incongruent to one. Now

$$
a \equiv a_1a_2\ldots a_r \bmod q_u
$$
and therefore the exponent to which $a \bmod q_u$ belongs is equal to the product of all prime numbers $p_1$ that are conjugate with $q_u$. The number $q$ thus belongs to an exponent that contains at least one prime number $p_1$, and therefore

$$
a^h \not\equiv 1 \bmod q_u
$$

On the other hand, $\bmod q_v$ and $\bmod q_r$

$$
a^h \equiv 1
$$

For the moduli $q_v$ therefore (11) is automatically satisfied; for the moduli $q_u$ and $q_r$ follows from (11) with help of (13) that $i \equiv 0$. Thus $k$ must also be divisible by the prime numbers $q_r$. This suffices together with the earlier condition for $Q^t = 1$. The order of the operation $Q = S^hT^i$ is thus equal to $\Pi p_1\Pi q_r$. A divisor of $m\cdot n$ is only then the order of an operation of the group when it contains no two prime numbers that are conjugate. The number of operations of order $\Pi p_1\Pi q_r$ is $\Pi(p_1-1)\Pi q_r\Pi(q_r-1)$.

To determine the number of operations equivalent to $Q$, form with help of (9) the expression

$$
(S^fT^g)^{-1}(S^hT^i)(S^fT^g) = S^hT^{g(1-a^h)+ia^f}
$$

The exponent $h$ thus remains unchanged in the transformation, and it only depends on which values of

$$
E = g(1-a^h) + ia^f
$$

$\bmod n$ are taken when $g \bmod n$ and $f \bmod m$ run through all residues. Now $E \equiv 0 \bmod q_u$ (according to (13)) and

$$
E \equiv ia^f \bmod \Pi q_r
$$

If one now denotes by $p_{21}$ a prime number that is conjugate with any prime number $q_r$, then the $p_{21}$ are contained in the sequence of the $p_2$, and it follows that $a \equiv a_1a_2\ldots a_r \bmod \Pi q_r$ belongs to the exponent $\Pi p_{21}$. The number $E$ thus becomes, by letting $f$ run through all $\Pi p_{21}$ residues of modulus $\Pi q_r$ congruent. In relation to a modulus $q_v$, $a^h \equiv 1$, therefore

$$
E = g(1-a^h) + ia^f
$$

after $f$ has already been chosen, can still be made congruent to any residue of modulus $q_v$ through the choice of $g$. The number $E$ thus takes on $\Pi p_{21}\Pi q_v$ values $\bmod n$ in total. The operation $Q = S^hT^i$ possesses, including itself, $\Pi p_{21}\Pi q_v$ equivalents.

The distribution of operations in a group represented by the symbol $p_1, p_2; q_1, q_2$ is shown by the following table:

| Order    | Number of Operations   | Number of Equivalents |
| -------- | ---------------------- | --------------------- |
| $p_1p_2$ | $(p_1-1)(p_2-1)q_1q_2$ | $q_1q_2$              |
| $p_1$    | $(p_1-1)q_1q_2$        | $q_1q_2$              |
| $p_2q_2$ | $(p_2-1)q_2(q_1-1)$    | $p_1q_1$              |
| $p_2$    | $(p_2-1)q_1$           | $q_1$                 |
| $q_1q_2$ | $(q_1-1)(q_2-1)$       | $p_1p_2$              |
| $q_1$    | $q_1-1$                | $p_1p_2$              |
| $q_2$    | $q_2-1$                | $p_1$                 |
| 1        | 1                      | 1                     |

In this table, for example, the first horizontal row states that there are $(p_1-1)(p_2-1)q_1q_2$ operations of order $p_1p_2$, and that all $q_1q_2$ operations belong together as equivalents. In every other case, the distribution of operations can be given in an equally simple way. It follows simultaneously that in two groups belonging to the same type, thus represented by the same symbol, the operations are distributed in the same way according to their orders and their equivalence.

Tübingen, May 16, 1895.