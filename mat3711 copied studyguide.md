



# MAT3711

#REAL ANALYSIS

Dr Oghenetega Ighedo

Department of Mathematical SciencesUniversity of South AfricaSouth Africa.





# Contents

# 0 PREFACE

# 

#1

# PREFACE

# 

#1

01 INTRODUCTION 102 ABOUT THE STUDY GUIDE 103 ABOUT MASTERING THIS COURSE 2

# 1 PRELIMINARIES 4

01 NOTATION 402 REAL NUMBERS 403 DENSENESS OF Q IN $\mathbb{R}$ 904 CARDINALITY 11

# 2 METRIC SPACES 19

01 METRIC SPACES 1902 OPEN SETS AND INTERIOR 2103 CLOSED SETS AND CLOSURE 3204 BOUNDED SETS, DIAMETERS AND DISTANCES 4005 THE BOLZANO-WEIERSTRASS THEOREM 42

# 3 CONVERGENCE AND COMPLETENESS 46

01 SEQUENCES AND SUBSEQUENCES 4602 CAUCHY SEQUENCES AND COMPLETENESS 5103 SEQUENCES WITH TERMS IN $\mathbb{R}$ 57

# 4 COMPACTNESS 62

01 COMPACT SETS 6202 CHARACTERISATIONS OF COMPACTNESS 66





# CONNECTEDNESS 75

01 CONNECTED SETS . 75

# 3 CONTINUITY 80

01 CONTINUOUS FUNCTIONS 8002 UNIFORM CONTINUITY 8403 CONTINUITY AND COMPACTNESS 8804 CONTINUITY AND CONNECTEDNESS 9105 CONTRACTION MAPPINGS 94

# 7 FUNCTION SPACES 98

01 SPACES OF BOUNDED FUNCTIONS 9802 POINTWISE AND UNIFORM CONVERGENCE 10403 MISCELLANEOUS EXAMPLES 115

# 8 LINEAR ANALYSIS 120

01 BASIC INEQUALITIES 12002 NORMED VECTOR SPACES 12903 BOUNDED LINEAR OPERATORS 134

# 9 THE RIEMANN-STIELTJES INTEGRAL 148

01 THE INTEGRAL 14802 THE FUNDAMENTAL THEOREM OF CALCULUS 16703 INTEGRATION AND CONVERGENCE 17104 IMPROPER INTEGRALS 173





# LEARNING UNIT 0

# PREFACE

# 01 INTRODUCTION

Good day and welcome to the module Real Analysis. We hope you will find engaging with the module interesting and rewarding. You should first turn to Tutorial Letter 101 for important information such as assignments, due dates, contact details and other relevant information. You also need to log onto MyUnisa weekly for pertinent information. The following is some information about the Study Guide.

# 02 ABOUT THE STUDY GUIDE

This study guide is a self-contained treatment of a standard syllabus on Real Analysis as currently taught to undergraduate students in South Africa. In compiling it I have assumed familiarity with elementary Real Analysis (MAT2613) and rudiments of Linear Algebra.

All concepts discussed herein have been carefully defined. A few exceptions (such as "subset", "element of", "differentiable function", etc.) are things you have learnt at first and second year levels.

You are therefore advised to revise them.

The notation I have used is fairly standard. In particular:

(a) If $A$ and $B$ are sets, $A \subseteq B$ means $A$ is a subset of $B$.

(b) If $A$ and $B$ are sets, $A \backslash B = \{x \mid x \in A \text{but} x \notin B\}$.

(c) If $f : X \to Y$ is a function and $A \subseteq X$, $B \subseteq Y$, then





$f[A]=\{f(x)\mid x\in A\}$, the image of $A$ under $f$

$f^{-1}[B]=\{x\in X\mid f(x)\in B\}$, the pre-image of $B$ under $f$.

It should be noted that in some books $f[A]$ and $f^{-1}[B]$ are denoted by $f(A)$ and $f^{-1}(B)$ respectively.

(d) If $\mathcal{C}$ is a collection of sets, $\bigcup\mathcal{C}$ denotes the union of all the sets in $\mathcal{C}$.

(e) The set of all $x$ that satisfy some property $P$ is denoted by

$$
\{ x \mid x \mathrm { ~ s a t i s f i e s ~ } P \} \ \ \mathrm { o r } \ \ \{ x : x \mathrm { ~ s a t i s f i e s ~ } P \} ,
$$

whichever is convenient.

# 03 ABOUT MASTERING THIS COURSE

The purpose of this module is to ensure that qualifying students who engage in this module have a sound grounding in the theory of metric spaces, linear analysis and Riemann-Stieltjes integration. Students engaging in this module will obtain knowledge, skills and values which will support further studies and applications in the sector of science in the field of Mathematics, as part of the Degree of Science. These competencies contribute to the development of scientific knowledge and mathematical understanding in Southern Africa, Africa or globally. Enrolled students for this module have to be connected to myUnisa during the semester.

The outcomes for this module are:

Demonstrate the concept of countability of sets.

Demonstrate the concepts of upper and lower bounds, suprema and infima.

Demonstrate the concept of a metric space.

Demonstrate the concept of a compact metric space.

Demonstrate the concept of continuity.

Demonstrate the concept of convergence of function spaces.

Demonstrate the concept of linear analysis.

Demonstrate the concept of the Riemann–Stieltjes Integral.





As with all branches of mathematics, the first step of course is to understand clearly what each definition says. Definitions are the building blocks for this course.

Real Analysis is typical of the Definition-Theorem-Proof type of mathematics. Indeed, in most instances, after defining a particular concept I have given some examples of objects with properties provided by the definition. Where it is illustrative to do so, I have also given examples of objects that do not satisfy a particular definition.

Having fully grasped a definition (or a number of definitions) you will encounter a theorem and its proof. Once again you must study the statement of a theorem thoroughly and make sure you understand it before studying the proof. Some proofs are fairly routine and easy to follow, others are quite involved. In all instances make sure you see why a particular statement follows from what has gone before it.

Apropos of proofs, there are cases where you will need to fill in the gaps. Some such cases are where a proof (or part of a proof) is stated to be an exercise; others are instances where it is stated "it is easy to see that..." or "one checks easily that..."

Exercises are part of the course. There are results which are stated in the exercises and used in the development of the theory or in proofs of certain theorems. You must do all activities.

We start off with the next preliminaries learning units.

Dr O. IghedoUNISAAugust 22, 2016.





# LEARNING UNIT 1

# PRELIMINARIES

The outcomes for this learning unit are;

Demonstrate the concept of countability of sets.

Demonstrate the concepts of upper and lower bounds, suprema and infima.

We commence with properties of real numbers that are relevant for this module. Some of these properties will be familiar to you from MAT2613 or MAT2615. Throughout the study guide we shall use the following notation pertaining to certain subsets of the set of real numbers.

# 01 NOTATION

$\mathbb{N}=\{1,2,3,\ldots\}=\text{the set of natural numbers}$

$\mathbb{Z}=\{\ldots-3,-2,-1,0,1,2,\ldots\}=\text{the set of integers}$

$\mathbb{Q}=\{\frac{m}{n}\mid m,n\in\mathbb{Z},\ n\neq0\}=\text{the set of rational numbers}$

$\mathbb{R}=\{x\mid x\text{ is a real number}\}.$

# 02 REAL NUMBERS

The real number system $\mathbb{R}$ is an ordered field which has the least-upper-bound property. What do we mean by this? We need to explain the terms "field", "ordered" and "has the least upper-bound property".

To say $\mathbb{R}$ is a field means $\mathbb{R}$ is equipped with two operations $+ : \mathbb{R} \times \mathbb{R} \rightarrow \mathbb{R}$ (called addition) and $\cdot : \mathbb{R} \times \mathbb{R} \rightarrow \mathbb{R}$ (called multiplication) such that the following axioms hold:





A1. For any $x,y\in\mathbb{R}$, $x+y\in\mathbb{R}$;

A2. $x+y=y+x$ for all $x,y\in\mathbb{R}$;

A3. $x+(y+z)=(x+y)+z$ for all $x,y,z\in\mathbb{R}$;

A4. There exists a unique element $0\in\mathbb{R}$ (called zero) such that $x+0=x$ for all $x\in\mathbb{R}$;

A5. For every $x\in\mathbb{R}$ there exists a unique element $y\in\mathbb{R}$ such that $x+y=0$. [We denote such an element by $-x$];

M1. For any $x,y\in\mathbb{R},x\cdot y\in\mathbb{R}$. [We write $xy$ in place of $x\cdot y$];

M2. $xy=yx$ for all $x,y\in\mathbb{R}$;

M3. $x(yz)=(xy)z$ for all $x,y,z\in\mathbb{R}$;

M4. $x(y+z)=xy+xz$ for all $x,y,z\in\mathbb{R}$;

M5. There exists a unique element $1\in\mathbb{R}$ such that $x\cdot 1=x$ for all $x\in\mathbb{R}$;

M6. For each nonzero $x\in\mathbb{R}$ there exists a unique element (denoted by $\frac{1}{x}$ or $x^{-1}$) such that $x\cdot \frac{1}{x}=1$.

To say $\mathbb{R}$ is ordered means $\mathbb{R}$ is equipped with an order relation $<$ which satisfies the following axioms:

O1. For all $x,y\in\mathbb{R}$, either $x<y$, $y<x$ or $x=y$;

O2. If $x<y$, then $x+z<y+z$ for all $z\in\mathbb{R}$;

O3. If $x<y$ and $0<z$, then $xz<y$;

O4. $x<y$ and $y<z\Rightarrow x<z$ for all $x,y,z\in\mathbb{R}$.

If $x < y$ we also write $y > x$. The relation $x \leq y$ (also written as $y \geq x$) is defined by: $x \leq y \Leftrightarrow x < y$ or $x = y$.

Note.

(a) Given $x,y\in\mathbb{R}$; either $x\leq y$, or $x\geq y$ (prove this).

(b) The elements $0,1$ are distinct; ie $0\neq1$.

Please engage with the following example.





Example 02.1. Show that for every $x,y\in\mathbb{R}$

(a) $x \cdot 0 = 0$

(b) $-x = (-1) \cdot x$

(c) $-(-x) = x$

(d) $-(x + y) = (-x) + (-y)$

(e) $(-1) \cdot (-1) = 1$

(f) $xy = 0 \Rightarrow x = 0$ or $y = 0$

(g) $(-x) (-y) = xy$.

Theorem 02.1. If $a \in \mathbb{R}$ and $a \neq 0$ then $a^2 > 0$. Hence $1 > 0$.

Proof. Either $a > 0$ or $a < 0$. If $a > 0$, then by O3 and the exercise above, $a \cdot a > a \cdot 0$, ie $a^2 > 0$. If $a < 0$ then $-a > 0$ (verify this), so that $(-a) \cdot (-a) > 0$ where $a^2 > 0$. Now $1 = 1 \cdot 1 = 1^2$; so $1 > 0$. $\square$

The theorem above shows that some of the properties of real numbers that we have "always" known (and even taken for granted) can actually be deduced from a carefully selected set of axioms that characterises the real number system. Note that we have not yet explained what we mean by "least-upper-bound property". Before we do that, let us prove another property of the reals that is frequently useful.

Theorem 02.2. Let $a,b\in\mathbb{R}$. If $a\leq b+\varepsilon$ for every $\varepsilon>0$, then $a\leq b$.

Proof. We prove the result by contradiction. So, suppose, that by way of contradiction, that $a \nleq b$. Then $b < a$, which implies that $a - b > 0$. So $\frac{1}{2}(a - b) > 0$. Now put $\varepsilon = \frac{1}{2}(a - b)$ in the statement of the theorem to obtain

$$
\begin{array}{rl} & { a \leq b + \frac { a - b } { 2 } } \\& { = \frac { a + b } { 2 } } \\& { < \frac { a + a } { 2 } } \\& { = a . } \end{array}
$$

We get the absurdity that says $a < a$.

Next we prepare the ground for the explanation of the last property we stated for $\mathbb{R}$.





Definition 02.3. Let $S$ be a nonempty subset of $\mathbb{R}$. We say $S$ is

bounded above in case $\exists b \in R$ such that $x \leq b \ \ \forall x \in S$;

bounded below in case $\exists c \in R$ such that $c \leq x \ \ \forall x \in S$;

bounded if $S$ is bounded above and below.

Thus a nonempty subset $S$ of $\mathbb{R}$ is bounded above (resp. below) if there is a real number which is bigger than or equal to (resp. smaller than or equal to) all elements of the set $S$. Such a real number is called an upper bound (resp. lower bound) for the set $S$.

Quite clearly, if $b$ is an upper bound for $S$, then any real number bigger than $b$ is also an upper bound for $S$. Likewise, any number smaller than a lower bound is itself a lower bound. Among upper (resp. lower) bounds, we are interested in the smallest (resp. largest). It is given a special name mentioned in the following definition.

Definition 02.4. Let $S$ be a nonempty subset of $\mathbb{R}$ which is bounded above. A real number $\alpha$ is called the supremum of $S$, denoted $\alpha = \sup S$, if

$\alpha$ is an upper bound for $S$; and

for any upper bound $b$ of $S$, $\alpha \leq b$.

Thus, the supremum of a set is an upper bound which is smaller than any other upper bound. It is for that reason that if $\alpha = \sup S$ we also say $\alpha$ is the least upper bound (abbreviated l.u.b.) of $S$.

On the other hand we have the following definition.

Definition 02.5. Let $S$ be a nonempty subset of $\mathbb{R}$ which is bounded below. A real number $\beta$ is called the infimum of $S$, denoted $\beta = \inf S$, if

$\beta$ is a lower bound for $S$; and

for any lower bound $d$ of $S$, $\beta \geq d$.

The infimum of a set $S$ is also called the greatest lower bound (abbreviated g.l.b.) of $S$.

CAUTION: There is nothing in the definition that says the supremum (or infimum) of a set must be an element of the set. It may or may not belong to the set. If $\sup S \in S$





then in fact $\sup S$ is the largest element of $S$. In this case we say $\sup S$ is the maximum element of $S$ and (frequently) write $\max S$ in place of $\sup S$. Similarly, if $\inf S \in S$ we say it is the minimum element of $S$ and may write $\min S$ instead of $\inf S$.

CAUTION: You should never write $\min S$ (or $\max S$) if the infimum (or supremum) is not in $S$.

Theorem 02.6. (a) $\alpha=\sup S\Leftrightarrow(i)$ $\alpha\geq x\forall\,x\in S$; and

(ii) $\forall\,a<\alpha,\exists s\in S$ such that $a<s\leq\alpha$.

(b) $\beta=\inf S\Leftrightarrow(i)$ $\beta\leq x$ $\forall x\in S$; and

(ii) $\forall\ b>\beta,\exists w\in S$ such that $\beta\leq w<b.$

Proof. Activity.

The following axiom characterizes $\mathbb{R}$.

Least-upper-bound property. Every nonempty subset of $\mathbb{R}$ that is bounded above has the supremum.

What the l.u.b. property says is that if $S \subseteq \mathbb{R}$ is nonempty and bounded above, then there is a real number $\alpha$ such that $\alpha = \sup S$. In order to fully appreciate the power of this axiom, let us consider a situation where we pretend the only numbers we know are rational numbers. Then the concepts of bounded above and supremum are definable in $\mathbb{Q}$ exactly as we did in $\mathbb{R}$.

Now $\mathbb{Q}$ does not have the l.u.b. property. Indeed if we let

$$
S = \left\{ x \in \mathbb { Q } \mid x ^{2} < 2 \right\}
$$

then $S$ is a nonempty subset of $\mathbb{Q}$ which is bounded above. However there is no rational number $r$ such that $r=\sup S$. However working in $\mathbb{R}$, we have that $\sup S=\sqrt{2}$.

Remark 02.1. The l.u.b. property is also known as the Completeness Axiom for $\mathbb{R}$.

Activity 02.1. Please do each activity.

(a) Let $S=\left\{\frac{1}{m}-\frac{1}{n}\mid m,n\in\mathbb{N}\right\}$. Show that $S$ is bounded and find $\sup S$ and $\inf S$.





(b) Let $S, T$ be subsets of $\mathbb{R}$ that are bounded above. Put $R = \{x + y \mid x \in S, \ y \in T\}$. Show that $R$ is bounded above and express $\sup R$ in terms of $\sup S$ and $\sup T$.

(c) Let $S, T \subseteq R$ with $S$ bounded above and $T$ bounded below. Put $R = \{s - t \mid s \in S, \ t \in T\}$. Prove that $R$ is bounded above and $\sup R = \sup S - \inf T$.

(d) Let $A \subseteq \mathbb{R}$ be bounded below. Show that $\beta = \inf A \Leftrightarrow \beta$ is a lower bound of $A$ and $\forall \varepsilon > 0$, $\exists \, a \in A$ s.t. $\beta \leq a < \beta + \varepsilon$.

We now look at denseness of $\mathbb{Q}$ in $\mathbb{R}$.

# 03 DENSENESS OF Q IN R

In this section our main goal is to prove a very important result which states that between any two real numbers there is a rational number.

Theorem 03.1. The set $\mathbb{N}$ is not bounded above.

Proof. Assume $\mathbb{N}$ is bounded above. Then by the Completeness Axiom, $\sup \mathbb{N}$ exists. Put $\alpha = \sup \mathbb{N}$. Since $\alpha - 1 < \alpha$, $\alpha - 1$ is not an upper bound for $\mathbb{N}$, so there exists $k \in \mathbb{N}$ such that $\alpha - 1 < k$. This implies that $\alpha < k + 1$. But $k \in \mathbb{N} \Rightarrow k + 1 \in \mathbb{N}$. So $k + 1 \leq \alpha$ since $\alpha$ is an upper bound for $\mathbb{N}$. Thus $\alpha < k + 1 \leq \alpha$, which is absurd. $\square$

We deduce from the theorem above that given any real number $r$, there is a natural number $m$ such that $m > r$. Likewise, given any real number $t$, there is an integer $n$ such that $n < t$. (Show this.)

Corollary 03.2. Given a real number $r$, there exists an integer $k$ such that $r-1 \leq k < r$.

Proof. Find an integer $m$ such that $m < r$; and a natural number $n$ such that $n > r$. Thus $m < r < n$. Notice that, since $m < r$ and $r < n$, in the set $\{m, m + 1, \ldots, n\}$ there is the largest integer $k$ such that $k < r$. So $k + 1 \geq r$ and therefore $r - 1 \leq k < r$. $\square$

Corollary 03.3. Let $A$ be a real number and $\varepsilon > 0$. Then there exists $n \in \mathbb{N}$ such that $n \varepsilon > A$. (Informally: no matter how large $A$ is and how small $\varepsilon$ is (as long as $\varepsilon > 0$) we can add enough $\varepsilon$'s to obtain a result larger than $A$).

Proof. If not, then $n \leq \frac{A}{\varepsilon}$ for every $n \in \mathbb{N}$, contrary to the fact that $\mathbb{N}$ is not bounded above. $\square$





We note in particular that for every $\varepsilon > 0$ there exists $n \in \mathbb{N}$ such that $\frac{1}{n} < \varepsilon$. This, of course, is familiar to you in the form $\lim_{n \to \infty} \frac{1}{n} = 0$.

We are now in a position to state the main result.

Theorem 03.4. Let $x,y\in\mathbb{R}$ with $x<y$. Then there is a rational number $r$ such that $x<r<y$.

Proof. Choose $n \in \mathbb{N}$ such that $\frac{1}{n} < y - x$. Then

$$
x < y - { \frac { 1 } { n } } .
$$

By Corollary 0.3.2 we can find an integer $k$ such that

$$
n y - 1 \leq k < n y , \ \mathrm { i . e . } \ \ y - \frac { 1 } { n } \leq \frac { k } { n } < y .
$$

Combining these results we obtain

$$
x < y - { \frac { 1 } { n } } \leq { \frac { k } { n } } < y
$$

which implies that $x < \frac{k}{n} < y$.

Corollary 03.5. Let $b \in \mathbb{R}$ and $S = \{x \in \mathbb{Q} \mid x < b\}$. Then $\sup S = b$.

Proof. Clearly, $S$ is bounded above and so has a supremum, say $c$. Then $c \leq b$ since $b$ is an upper bound for $S$. If we assume that $c < b$, then there is a rational number $r$ such that $c < r < b$. So $r$ is a member of $S$ that is strictly larger than $\sup S$. That is not possible. So $c \nleq b$, hence $c = b$. $\square$

Now let us go back to the case $S=\{x\in\mathbb{Q}\mid x^{2}<2\}$ mentioned earlier. Note that

$$
x ^{2} < 2 \Leftrightarrow - \sqrt { 2 } < x < \sqrt { 2 } .
$$

So, by the foregoing corollary, we have that $\sup S = \sqrt{2}$.

Cardinality is explored next.





# 04 CARDINALITY

Our treatment of this topic will be rather superficial; the main purpose being to establish that:

(i) Any interval $(a,b)$, with $a<b$, has "as many elements" as $\mathbb{R}$;

(ii) Between any two real numbers there is an irrational number.

By a finite set we mean an empty set or a set that has $n$ elements for some $n \in \mathbb{N}$. Now if $S$ and $T$ are finite sets with $m$ and $n$ elements respectively, then it is clear that there is a one-to-one function $f : S \to T$ mapping $S$ onto $T$ if and only if $m = n$. Generalising to arbitrary sets (including those with infinitely many elements) it is natural to think of two sets as having the same number of elements, provided there is a one-to-one onto function between them.

We caution that this may go against intuition in the sense that a proper subset of a set can have "the same number of elements" as the set. Witness the following example.

Example 04.1. Let $S$ be the set of all even natural numbers. Then $S$ is a proper subset of $\mathbb{N}$. The function $f : \mathbb{N} \to S$ given by $f(n) = 2n$ is one-to-one onto.

Clearly, then, in the case of infinite sets, to say two sets "have the same number of elements" might be problematic. We therefore speak of sets having the same cardinal number (or cardinality), where, in the case of finite sets, the cardinality of a set is simply the number of its elements. We shall not define precisely what a cardinal number is; that is a matter normally discussed in a course on Set Theory.

Definition 04.1. Let $S$ be a set. A symbol, called the cardinal number of $S$, denoted $\text{card}(S)$ or $|S|$, is associated with $S$ in such a way that $\text{card}(X) = \text{card}(Y)$ if and only if there is a one-to-one onto function $f : X \to Y$. If $S$ is a finite set with $m$ elements, we set $\text{card}(S) = m$.

As special numbers we mention card($\mathbb{N}$) which is normally denoted by $\mathbb{N}_0$ (the symbol $\mathbb{N}$ is a Hebrew letter pronounced aleph), and card($\mathbb{R}$) which we denote by $\mathbb{N}$.

Next we define what it means to say one cardinal number is smaller (or smaller than or equal to) another. Once again the motivation comes from finite sets. Note that if $S$ and





$T$ are finite sets with $\operatorname{card}(S) \leq \operatorname{card}(T)$, then there is a one-to-one function $g: S \rightarrow T$. Conversely, if there is a one-to-one function $g: S \rightarrow T$, then $S$ cannot have more elements than $T$, ie $\operatorname{card}(S) \leq \operatorname{card}(T)$.

NOTE: The function $g$ mentioned is only assumed to be one-to-one but not necessarily onto.

Definition 04.2. If $X$ and $Y$ are sets, we say $\operatorname{card}(X)$ is less than or equal to $\operatorname{card}(Y)$, and write $\operatorname{card}(X) \leq \operatorname{card}(Y)$, in case there is a one-to-one function $g : X \to Y$. If

card$(X) \leq$ card$(Y)$, but card$(X) \neq$ card$(Y)$,

we write $card\left(X\right) < card(Y)$.

Activity 04.1. Prove that $\operatorname{card}(X) \leq \operatorname{card}(Y) \Leftrightarrow$ there exists $Z \subseteq Y$ such that $\operatorname{card}(X) = \operatorname{card}(Z)$.

Example 04.2. Let $S$ be a set and $T \subseteq S$. The map $i : T \to S$ given by $i(x) = x$ is one-to-one. Thus $\text{card}(T) \leq \text{card}(S)$. So every subset has cardinality less than or equal to the cardinality of the containing set.

The relation $\leq$ defined for cardinal numbers above is easily seen to be:

reflexive, ie $\alpha \leq \alpha$ for every cardinal number $\alpha$. Indeed if $X$ is a set with $\operatorname{card}(X) = \alpha$, then the map $i : X \to X$ given by $i(x) = x$ is one-to-one.

transitive, ie $\alpha \leq \beta \leq \gamma$ implies $\alpha \leq \gamma$. Take sets $X, Y$ and $Z$ with $\operatorname{card}(X) = \alpha$, $\operatorname{card}(Y) = \beta$ and $\operatorname{card}(Z) = \gamma$. Let $f : X \to Y$ and $g : Y \to Z$ be one-to-one functions. Then $g \circ f : X \to Z$ is one-to-one.

It is true that $\leq$ is also antisymmetric, ie $\alpha \leq \beta$ and $\beta \leq \alpha$ together imply that $\alpha = \beta$. The proof of this is not trivial; and the result is known as the Cantor-Bernstein theorem.

Theorem 04.3. Let $A$ and $B$ be sets with $\operatorname{card}(A) \leq \operatorname{card}(B)$ and $\operatorname{card}(B) \leq \operatorname{card}(A)$. Then $\operatorname{card}(A) = \operatorname{card}(B)$.

Proof. Let us denote set difference by $S\backslash T$; ie $S\backslash T = \{x \in S \mid x \notin T\}$. Now we are given that there is a one-to-one function $f : A \to B$ and a one-to-one function $g : B \to A$. We must show that there is a one-to-one onto function $\phi : A \to B$.

For any $S \subseteq A$ let $K(X)$ denote the set

$$
K \left( X \right) = A \backslash g \left[ B \backslash f \left[ S \right] \right] ,
$$





where $f\left[X\right]=\left\{f\left(x\right)\mid x\in X\right\}$ for $X\subseteq A$. Now note that if $U\subseteq V\subseteq A$ then $K\left(U\right)\subseteq K\left(V\right)$ since $U\subseteq V$ implies $f\left[U\right]\subseteq f\left[V\right]$ which in turn implies $B\backslash f\left[U\right]\supseteq B\backslash f\left[V\right]$. Next let

$$
\mathcal { A } = \{ X \subseteq A \mid X \subseteq K ( X ) \}
$$

and put $C=\bigcup\mathcal{A}$, i.e. $C$ is the union of all sets in $\mathcal{A}$. For any $c\in C$ there exists $X\in\mathcal{A}$ such that $c\in X\subseteq K(X)\subseteq K(C)$. [Note that $K(X)\subseteq K(C)$ since $X\subseteq C$]. Since $c$ is an arbitrary element of $C$ we conclude that $C\subseteq K(C)$; which in turn yields $K(C)\subseteq K(K(C))$. Thus $K(C)\in\mathcal{A}$, and therefore by the definition of $C$ we have $K(C)\subseteq C$. This then shows that $K(C)=C$. The function $g$ is one-to-one; so its restriction $\widetilde{g}$ on $B\backslash K[C]$ is also one-to-one. We claim that $\widetilde{g}$ maps $B\backslash f[C]$ onto $A\backslash C$. To see this let $y\notin C$. Then $y\notin C$, i.e. $y\notin K[C]=A\backslash g[B\backslash f[C]]$. So then it follows that $y\in g[B\backslash f[C]]$, and hence $y=g(x)$ for some $x\in B\backslash f[C]$. Now define $\phi:A\to B$ by

$$
\phi \left( x \right) = \left\{ \begin{array}{ll} { f \left( x \right) , } & { \mathrm { i f }  x \in C } \\{ \tilde { g } ^{- 1} \left( x \right) , } & { \mathrm { i f }  x \in A \backslash C } \end{array} \right.
$$

Then $\phi$ is a one-to-one onto function. That it is one-to-one is clear. To see ontoness, notice that $B=(B\backslash f[C])\cup f[C]$ and $f$ is onto $f[C]$ whilst $\widetilde{g}$ is onto $B\backslash f[C]$. $\square$

In fact it can be shown (we will not prove it — see any book on advanced Set Theory) that any two cardinal numbers are comparable. More precisely we have the following theorem.

Theorem 04.4. Given any two sets $X$ and $Y$ either $\operatorname{card}(X) \leq \operatorname{card}(Y)$ or $\operatorname{card}(Y) \leq \operatorname{card}(X)$.

Definition 04.5. A set $X$ is said to be countably infinite in case $\operatorname{card}(X) = \operatorname{card}(\mathbb{N})$; if it has the same cardinality as the set of natural numbers. A set is said to be countable if it is either finite or countably infinite. A set is uncountable if it is not countable.

Let us examine closer what it means for a set $X$ to be countably infinite. In such a case there is a one-to-one onto function $f : \mathbb{N} \to X$. For each $k \in \mathbb{N}$ let $x_k$ denote $f(k)$. Thus the elements of $X$ are precisely $x_1, x_2, x_3, \ldots$; ie $X = \{x_1, x_2, x_3, \ldots\}$. So then the elements of $X$ can be written out with "labels" $1, 2, \ldots$ by means of which we can "count" all the elements of $X$ without missing any. Of course if $Y$ is a finite set, say with $m$ elements, then the elements of $Y$ can be written out as $y_1, y_2, \ldots, y_m$. Thus, whether a





set is finite or countably infinite, we can "count" its elements; hence the term "countable".

There are sets which are not countable. Before we give examples we first prove a result which tells us that the set of all subsets of any given set $S$ has cardinality strictly bigger than the cardinality of $S$. Recall that the set of all subsets of $S$ is denoted by $\mathcal{P}(S)$.

Theorem 04.6. For every set $S$, $\operatorname{card}(S) < \operatorname{card}(\mathcal{P}(S))$.

Proof. The function $j : S \to \mathcal{P}(S)$ given by $j(x) = \{x\}$ is one-to-one. So $\text{card}(S) \leq \text{card}(\mathcal{P}(S))$. So we must show that $\text{card}(S) \neq \text{card}(\mathcal{P}(S))$. Suppose, by way of contradiction, that there is a one-to-one onto function $g : S \to \mathcal{P}(S)$. Let $A = \{x \in S \mid x \notin g(x)\}$. Then $A \in \mathcal{P}(S)$, so there exists $s \in S$ such that $g(s) = A$ because $g$ is onto. Now either $s \in A$ or $s \notin A$. A contradiction arises as follows: if we suppose that $s \in A$, then by the definition of $A$ we have that $s \notin g(s)$, ie $s \notin A$. On the other hand, if we suppose that $s \notin A$, then we must have $s \in g(s)$, ie $s \in A$. This contradiction proves that there cannot be a one-to-one onto function from $S$ onto $\mathcal{P}(S)$. Thus $\text{card}(S) < \text{card}(\mathcal{P}(S))$. $\square$

Example 04.3. The foregoing result gives $\operatorname{card}(\mathbb{N})<\operatorname{card}(\mathcal{P}(\mathbb{N}))$. Therefore the set of all subsets of $\mathbb{N}$ is not countable.

Example 04.4. The interval $(0,1)=\{x\in\mathbb{R}\mid0<x<1\}$ is uncountable. To prove this we suppose, on the contrary, that $(0,1)$ is countable. Then $(0,1)=\{s_1,s_2,\ldots\}$. We then show that this is impossible by constructing a real number $x\in(0,1)$ which cannot be one of the numbers $s_1,s_2,\ldots$. Write each $s_n$ as an infinite decimal $s_n=0\cdot u_{n1}u_{n2}u_{n3}\ldots$ where each $u_{ni}$ is $0,1,\ldots$, or $9$. (For instance $\frac{1}{3}=0.333\ldots,\frac{2}{5}=0.4000\ldots$). Now define $x$ to be $0\cdot t_1t_2t_3\ldots$ where

$$
t _ { n } = \left\{ \begin{array}{ll} { 3 } & { \mathrm { i f } \; \; u _ { n n } \neq 1 } \\{ 2 } & { \mathrm { i f } \; \; u _ { n n } = 1 } \end{array} \right.
$$

Now notice that $0 < x < 1$ and that for each $n$, $x \neq s_n$ since the decimal expansion of $x$ differs from that of $s_n$ at the $n^{\text{th}}$ decimal place. (A situation like $s_n = 0.19999\ldots$ and $x = 0.2000\ldots$ cannot occur here because each $t_n$ is neither 0 nor 9).

In the next series of results we want to determine the countability or otherwise of the sets $\mathbb{Q}$, $\mathbb{R}$ and $\mathbb{R}\backslash\mathbb{Q}$. We start with $\mathbb{R}$. The following theorem is useful in this regard.

Theorem 04.7. Every subset of a countable set is countable.

Proof. Let $S$ be a countable set and $T \subseteq S$. If $T$ is finite then $T$ is countable. So suppose $T$ is countably infinite, which of course means $S$ is also countably infinite. Write





$S=\{s_{1},s_{2},\ldots\}$. Now define $k:\mathbb{N}\rightarrow\mathbb{N}$ as follows:

$k\left(1\right)$ is the smallest positive integer $m$ such that $s_{m}\in T$. Having defined $k\left(1\right),\ldots,k\left(n-1\right)$. define $k\left(n\right)$ to be the smallest positive integer $m>k\left(n-1\right)$ such that $s_{m}\in T$. (For instance if $T=\left\{s_{7},s_{22},s_{59},\ldots\right\}$ then $k\left(1\right)=7, k\left(2\right)=22, k\left(3\right)=59,\mathrm{\~etc.}$) Now let $\phi:\mathbb{N}\rightarrow S$ be given by $\phi\left(n\right)=s_{n}$. Note that both $\phi$ and $k$ are one-to-one. Therefore the composite function $\phi\circ k:\mathbb{N}\rightarrow T$ is one-to-one onto (check this). This completes the proof. $\square$

We note immediately from the foregoing theorem that if $A$ is an uncountable subset of $B$, then $B$ is also uncountable. Now having shown that $(0,1)$ is uncountable, we deduce that:

Theorem 04.8. $\mathbb{R}$ is uncountable.

Actually we can do better than that. We shall show that for any real numbers $a$ and $b$ with $a < b$, the interval $(a,b)$ has the same cardinality as $\mathbb{R}$. Let $a,b \in \mathbb{R}$ with $a < b$. Define

$$
\phi : ( a , b ) \to ( 0 , 1 )  \mathrm { b y }  \phi ( t ) = \frac { b - t } { b - a } .
$$

One checks easily that $\phi$ is one-to-one onto. So $\operatorname{card}(0,1)=\operatorname{card}(a,b)$. Now define

$$
\rho : \mathbb { R } \rightarrow ( - 1 , 1 )  \mathrm { b y }  \rho \left( t \right) = \frac { t } { 1 + \left| t \right| } .
$$

Again it is not difficult to verify that $\rho$ is one-to-one onto. Consequently we have:

$$
\operatorname { c a r d } \left( \mathbb { R } \right) = \operatorname { c a r d } \left( - 1 , 1 \right) = \operatorname { c a r d } \left( a , b \right) { \mathrm { ~ f o r ~ a l l ~ } } a , b \in \mathbb { R } { \mathrm { ~ w i t h ~ } } a < b .
$$

Now let $I$ denote any of the intervals $[a,b]$, $[a,b)$ or $(a,b]$. Then $I \subseteq \mathbb{R}$; so that $\text{card}(I) \leq \text{card}(a,b)$.

So by Theorem 04.4 we have:

Theorem 04.9. For any real numbers $a$ and $b$ with $a < b$, we have

$$
c a r d ( \mathbb { R } ) = c a r d ( a , b ) = c a r d ( a , b ] = c a r d [ a , b ) = c a r d [ a , b ] .
$$

Next we turn our attention to rational numbers.





Lemma 04.1. Let $A$ be a set and $S$ be a countable set. If there is a one-to-one function $g : A \to S$ mapping $A$ into $S$ (note that we are not assuming $g$ to be onto), then $A$ is countable.

Proof. Note that $f[A]$ is countable since it is a subset of a countable set. Now $f : A \to f[A]$ is one-to-one onto. Thus $A$ is countable. $\square$

Theorem 04.10. The product set $\mathbb{N} \times \mathbb{N}$ is countable.

Proof. Let $f : \mathbb{N} \times \mathbb{N} \to \mathbb{N}$ be given by $f(m,n) = 2^m \cdot 3^n$. Then $f$ is one-to-one as can easily be checked. So in view of Lemma 0.4.1 the result follows. $\square$

Let $X_1, X_2, \ldots$ be nonempty sets. For each $n \in \mathbb{N}$ let $\widetilde{X}_n = \{(x, n) \mid x \in X_n\}$. We therefore have

$$
\begin{array}{rl} { \widetilde { X } _ { 1 } } & { = \ \{ ( x , 1 ) \ | \ x \in X _ { 1 } \} } \\{ \widetilde { X } _ { 2 } } & { = \ \{ ( x , 2 ) \ | \ x \in X _ { 2 } \} , \ \mathrm { e t c . } } \end{array}
$$

Notice that for any $k$, $m \in \mathbb{N}$ with $k \neq m$, $\widetilde{X}_k \cap \widetilde{X}_m = \emptyset$ because the second coordinate of each element of $\widetilde{X}_k$ is different from the second coordinate of any element of $\widetilde{X}_m$. Thus the sets $\widetilde{X}_n$ are mutually disjoint. We claim that $\text{card}(\bigcup X_n) \leq \text{card}\Big(\bigcup \widetilde{X}_n\Big)$. Indeed, for every $z \in \bigcup_{n=1}^{\infty} X_n$, let $i(z)$ be the smallest positive integer such that $z \in X_{i(z)}$. Defining

$$
\beta : \bigcup _ { n = 1 } ^{\infty} X _ { n } \to \bigcup _ { n = 1 } ^{\infty} \widetilde X _ { n } \; \; \mathrm { b y } \; \; \beta \left( z \right) = \left( z , i \left( z \right) \right)
$$

gives a one-to-one function $\beta$; which proves the claim. The sets $\widetilde{X}_n$ are called the disjointification of the sets $X_n$.

Next, let $S_1, S_2, \ldots$ be disjoint sets and for each $n$ let $g_n : S_n \to T_n$ be a function. Define $\overline{g} : \bigcup_{n=1}^{\infty} S_n \to \bigcup_{n=1}^{\infty} T_n$ as follows: If $x \in \bigcup_{n=1}^{\infty} S_n$, then there exists exactly one $k$ such that $x \in S_k$. Then put $\overline{g}(x) = g_k(x)$. Check that $\overline{g}$ is indeed a well-defined function mapping $\bigcup_{n=1}^{\infty} S_n$ into $\bigcup_{n=1}^{\infty} T_n$. Furthermore, if each $g_n$ is one-to-one, then so is $\overline{g}$.

Theorem 04.11. Let $S_1, S_2, \ldots$ be countable sets. Then $\bigcup_{n=1}^{\infty} S_n$ is countable.

Proof. For each fixed $n \in \mathbb{N}$, let $T_n = \{(m,n) \mid m \in \mathbb{N}\}$. Then note that $\bigcup_{n=1}^{\infty} T_n = \mathbb{N} \times \mathbb{N}$. The function $f : T_n \to \mathbb{N}$ given by $f(m,n) = m$ is one-to-one. So $T_n$ is countable for





each $n$. Because $S_n$ is countable for each $n$, each of the sets $\widetilde{S}_n$ in the disjointification of the $S_n$'s is countable. We can thus find a one-to-one function $g_n : \widetilde{S}_n \to T_n$, for every $n \in \mathbb{N}$. Letting $\overline{g}$ be defined as above, we obtain a one-to-one function mapping $\bigcup_{n=1}^{\infty} \widetilde{S}_n$ into $\bigcup_{n=1}^{\infty} T_n = \mathbb{N} \times \mathbb{N}$. Because $\mathbb{N} \times \mathbb{N}$ is countable, we conclude that $\bigcup_{n=1}^{\infty} \widetilde{S}_n$ is countable. But $\text{card}\left(\bigcup_{n=1}^{\infty} S_n\right) \leq \text{card}\left(\bigcup_{n=1}^{\infty} \widetilde{S}_n\right)$, so the result follows. $\square$

If $\Gamma$ is a set and for each $\gamma \in \Gamma$ we have an object $a_{\gamma}$, we say the objects $a_{\gamma}$ ($\gamma \in \Gamma$) are countably many provided $\Gamma$ is countable. In this terminology the foregoing theorem can be stated as:

The union of countably many countable sets is countable.

Now $\mathbb{Z}=\{-n\mid n\in\mathbb{N}\}\cup\{0\}\cup\mathbb{N}$. Since $\{-n\mid n\in\mathbb{N}\}$ is obviously countable, we have expressed $\mathbb{Z}$ as a countable union (i.e. a union of countably many) of countable set. So $\mathbb{Z}$ is countable.

Theorem 04.12. $\mathbb{Q}$ is countable.

Proof. For each $n \in \mathbb{N}$ let $T_n = \left\{\frac{m}{n} \mid m \in \mathbb{Z}\right\}$. The function $f : T_n \to \mathbb{Z}$ given by $f\left(\frac{m}{n}\right) = m$ is one-to-one onto. Since $\mathbb{Z}$ is countable, $T_n$ is countable. But now $\mathbb{Q} = \bigcup_{n=1}^{\infty} T_n$. So it follows from Theorem 04.12 that $\mathbb{Q}$ is countable. $\square$

Corollary 04.13. The set $\mathbb{R}\backslash\mathbb{Q}$ of irrational numbers is not countable.

Proof. If it were, then, in view of $\mathbb{R} = \mathbb{Q} \cup (\mathbb{R} \setminus \mathbb{Q})$, we would have that $\mathbb{R}$ is countable.

Corollary 04.14. Between any two real numbers there is an irrational number.

Proof. Let $a,b\in\mathbb{R}$ with $a<b$. Then $(a,b)$ is not countable since $\operatorname{card}(a,b)=\operatorname{card}(\mathbb{R})$. Now if there were no irrational number between $a$ and $b$ we would have $(a,b)\subseteq\mathbb{Q}$, which would make $(a,b)$ countable. $\square$

Activity 04.2. (a) Let $A_1, A_2, \ldots, A_n$ be countable sets. Prove that the product

$$
A _ { 1 } \times A _ { 2 } \times \ldots \times A _ { n } = \{ ( a _ { 1 } , a _ { 2 } , \ldots , a _ { n } ) \mid a _ { i } \in A _ { i } \}
$$

is countable.

(b) The Axiom of Choice states that: If $\{S_{\alpha} \mid \alpha \in \Lambda\}$ is a collection of nonempty sets, then there exists a set $S$ consisting of exactly one element from each $S_{\alpha}$. Equivalently; there exists a function $f : \Lambda \to \bigcup_{\alpha \in \Lambda} S_{\alpha}$ such that $f(\alpha) \in S_{\alpha}$ for every $\alpha \in \Lambda$. Such a function is called a choice function.





(i) Now let $X$ and $Y$ be sets such that there exists an onto function $g : X \to Y$. Show that $\text{card}(Y) \leq \text{card}(X)$.

(ii) On the other hand, if $Y \neq \emptyset$ and $\text{card}(Y) \leq \text{card}(X)$, show that there is a function mapping $X$ onto $Y$.

(c) Let $S$ be the collection of all sequences whose terms are the integers 0 and 1. Show that $S$ is not countable. (Hint: mimic the proof of Example 04.4).

We next look at Learning Unit 2 with focus on Metric Spaces.





# LEARNING UNIT 2

# METRIC SPACES

# 01 METRIC SPACES

The outcome for this learning unit is to;

Demonstrate the concept of a metric space.

The idea of a metric on a set is an abstraction and generalisation of the geometric concept of distance. On the Euclidean plane, let us write $\rho(x,y)$ to denote the distance from a point $x$ to a point $y$. Then it is intuitively clear that $\rho(x,y) \geq 0$ for all $x$ and $y$ because distance is measured in terms of nonnegative numbers. Also, the distance between $x$ and $y$ is the same as the distance between $y$ and $x$. In terms of $\rho$, this says $\rho(x,y) = \rho(y,x)$. Furthermore, the distance between $x$ and $y$ is zero precisely when $x$ is $y$. Lastly, in any triangle, the length of any side is less than or equal to the sum of the lengths of the other two sides. On the basis of these observations we formulate the following definition.

Definition 01.1. Let $X$ be a nonempty set. A metric on $X$ is a function $d : X \times X \to \mathbb{R}$ that satisfies the following conditions:

$M1$. $d(x,y) \geq 0$ for all $x,y \in X$.

$M2$. $d(x,y) = 0 \Leftrightarrow x = y$.

$M3$. $d(x,y) = d(y,x)$ for all $x,y \in X$.

$M4$. $d(x,y) \leq d(x,z) + d(z,y)$ for all $x,y,z \in X$.

If $d$ is a metric on a set $X$, the pair $(X,d)$ is called a metric space, and $d(x,y)$ the distance from $x$ to $y$.

Property M4 in the above definition is called the triangle inequality. We emphasise that a metric space is simply a set (any nonempty set) together with a metric (which can





be thought of as a "distance function") on the set. The properties that the distance function must satisfy parallel the familiar properties of the usual distance function on $\mathbb{R}$ or $\mathbb{R}^2$.

A point to note is that on any set many metrics can be defined, as the following examples show. Where we only state that a given function is a metric, you must verify that indeed it is a metric.

Example 01.1. Let $X$ be any nonempty set. Define $d : X \times X \to \mathbb{R}$ by

$$
d \left( x , y \right) = \left\{ \begin{array}{ll} { 0 } & { \mathrm { i f }  x = y } \\{ 1 } & { \mathrm { i f }  x \neq y } \end{array} \right. .
$$

Then $d$ is a metric on $X$. M1 through M3 are easily verified. To show M4, let $x,y,z\in X$. If $x=y$, then $d(x,y)=0\leq d(x,z)+d(z,y)$ since each of $d(x,z)$ and $d(z,y)$ is nonnegative. On the other hand, if $x\neq y$, then we cannot have $z=x$ and $z=y$, because that would mean $x=y$. So, say $z\neq x$. Thus:

$$
\begin{array}{rl} { d ( x , z ) + d ( z , y ) } & { = \ 1 + d ( z , y ) } \\& { \geq \ 1 \ \ \mathrm { s i n c e } \ \ d ( z , y ) \geq 0 } \\& { = \ d ( x , y ) . } \end{array}
$$

So the triangle inequality also holds.

The metric given in Example 01.1 is called the discrete metric on $X$.

Example 01.2. The function $d : \mathbb{R} \times \mathbb{R} \to \mathbb{R}$ defined by $d(x,y) = |x-y|$ satisfies M1 through M4. It is called the usual metric on $\mathbb{R}$. In general, let $d : \mathbb{R}^n \times \mathbb{R}^n \to \mathbb{R}$ be defined by

$$
d ( x , y ) = \sqrt { ( x _ { 1 } - y _ { 1 } ) ^{2} + \ldots + ( x _ { n } - y _ { n } ) ^{2} } ,
$$

where $x=(x_{1},\ldots,x_{n})$ and similarly for $y$. Then $d$ is a metric on $\mathbb{R}^{n}$ called the usual or Euclidean metric on $\mathbb{R}^{n}$. Also, if $d:\mathbb{C}\times\mathbb{C}\rightarrow\mathbb{R}$ is defined by $d(z,w)=|z-w|$ then $d$ is a metric on $\mathbb{C}$ called the usual metric on $\mathbb{C}$.

Example 01.3. In this example we give two other metrics on $\mathbb{R}^n$. The square metric on $\mathbb{R}^n$ is the metric $\rho : \mathbb{R}^n \times \mathbb{R}^n \to \mathbb{R}$ given by $\rho(x,y) = \max\{|x_1 - y_1|, |x_2 - y_2|, \ldots, |x_n - y_n|\}$, where, as before, $x = (x_1, x_2, \ldots, x_n)$ and $y = (y_1, y_2, \ldots, y_n)$. The taxicab metric on $\mathbb{R}^n$ is the metric $\sigma$ given by $\sigma(x,y) = |x_1 - y_1| + |x_2 - y_2| + \ldots + |x_n - y_n|$.





Example 01.4. Let $(X,d)$ be a metric space and $S \subseteq X$. Define $d_S : S \times S \to \mathbb{R}$ by $d_S(a,b) = d(a,b)$ for all $a,b \in S$. In other words, $d_S$ is the restriction of $d$ to $S \times S$. Then $d_S$ is a metric on $S$ called the subspace metric. The metric space $(S,d_S)$ is called a subspace of $(X,d)$. This example shows that every nonempty subset of a metric space inherits a metric from the containing metric space. So, for instance, if we say "consider $[0,1)$ with the usual me-tric" what we mean is that equip $[0,1)$ with the metric $d$ for which $d(x,y) = |x-y|$. Henceforth we shall adopt the convention that if no metric is specified on a subset $A$ of a metric space, then we assume $A$ has the subspace metric.

Activity 01.1. (a) Prove that each of the functions claimed to be a metric in the examples above is indeed a metric.

(b) Let $(X,d)$ and $(Y,\rho)$ be metric spaces. Define $\sigma$ by

$$
\sigma ( ( a , u ) , ( b , v ) ) = \operatorname* { m a x } \{ d ( a , b ) , \rho ( u , v ) \} .
$$

Determine if $\sigma$ is a metric on $X \times Y$.

(c) Let $(X,d)$ be a metric space and define

$$
\rho : X \times X \to \mathbb { R } \ \ \mathrm { b y } \ \ \rho ( x , y ) = \frac { d ( x , y ) } { 1 + d ( x , y ) } .
$$

Prove that $(X,\rho)$ is a metric space. (Hint: To prove the triangle inequality, it might help first to show that the function $f(t)=\frac{t}{1+t}$ is increasing for $t\geq0$.)

(d) On $\mathbb{R}$ let $d(x,y)=(x-y)^4$. Show that $d$ is not a metric on $\mathbb{R}$.

(e) For $x,y\in\mathbb{R}$ define

$$
d _ { 1 } ( x , y ) = ( x - y ) ^{2} ,  d _ { 2 } ( x , y ) = | x - 2 y | ,  d _ { 3 } ( x , y ) = | x ^{2} - y ^{2} |  \mathrm { a n d }  d _ { 4 } ( x , y ) = \sqrt { | x - y | } .
$$

Determine, for each of these, whether it is a metric on $\mathbb{R}$ or not.

Next we examine open sets and interior.

# 02 OPEN SETS AND INTERIOR

One of the key notions in the study of metric spaces is that of open sets and their complements which are called closed sets. In this section we define these and explore some of





their basic properties.

Definition 02.1. Let $(X,d)$ be a metric space, $a \in X$ and $r$ be a real number with $r > 0$. The ball with centre $a$ and radius $r$, denoted $B(a,r)$, is the set

$$
B ( a , r ) = \{ x \in X \mid d ( x , a ) < r \} .
$$

Notice that a ball is defined in terms of the metric. Thus if a set $X$ is equipped with more than one metric, we denote the ball with centre $a$ and radius $r$ by $B_d(x,r)$ if the metric we are using is $d$. Indeed it is possible for different metrics $d$ and $\rho$ on a set $X$ to have $B_d(a,r) \neq B_\rho(a,r)$ as we show by means of examples below.

In words, the ball $B(a,r)$ consists of all those elements $x$ of $X$ such that the distance between them and $a$ is less than $r$. The ball $B(a,r)$ is also referred to as the open ball with centre $a$ and radius $r$. The justification for the adjective "open" will be clear when we study open sets in general. The reason we sometimes wish to call a ball an open ball is that at times it is necessary to distinguish it from a closed ball which is defined as follows:

Definition 02.2. Let $(X,d)$ be a metric space, $a \in X$ and $r > 0$. The closed ball with centre $a$ and radius $r$, denoted $\overline{B}(a,r)$, is the set

$$
\overline { { B } } ( a , r ) = \{ x \in X \mid d ( x , a ) \leq r \} .
$$

As before if it is necessary to avoid confusion, we write $\overline{B}_{d}(a,r)$ for the closed ball to indicate that the metric in question is $d$. Also, the adjective "closed" will be justified shortly. Let us emphasise that "ball" without qualification always means "open ball". One sees easily that $B(a,r) \subseteq \overline{B}(a,r)$.

Pictorially, an open ball and a closed ball appear as indicated in the following diagrams.





<div style="display: block; width: 100%"><img src="https://storage.simpletex.cn/view/m008c663f56ef03e19d95c7745aad848f" style="width: 30%; max-width: 30%" /></div> Figure 1.2.3

<div style="display: block; width: 100%"><img src="https://storage.simpletex.cn/view/me102fbec4f9fb8bc36196f255f3a06ec" style="width: 30%; max-width: 30%" /></div> Figure 1.2.4

Informally, as illustrated in Figure 1.2.3, the open ball consists of all the points inside the circle excluding the points on the circumference. The points on the circumference are excluded because the distance between each such point and $a$ is equal to $r$ and not less than $r$. On the other hand, the closed ball, as illustrated in Figure 1.2.4, consists of all the points inside the circle together with the points on the circumference.

As a word of caution, let us mention that diagrams help visualise things, but do not prove anything. Now we give examples of balls in various metric spaces.

Example 02.1. Consider $\mathbb{R}$ with the usual metric. Let $a \in \mathbb{R}$ and $r > 0$. Then

$$
B \left( a , r \right) = \left\{ x \in \mathbb { R } \mid \left| x - a \right| < r \right\} = \left( a - r , \ a + r \right) ,
$$

the open interval with endpoints $a - r$ and $a + r$. On the other hand,

$$
\overline { { B } } ( a , r ) = \left\{ x \in \mathbb { R } \mid \, | x - a | \leq r \right\} = \left[ a - r , \, \, a + r \right] .
$$

Example 02.2. (a) Consider $\mathbb{N}$ with the usual metric (i.e. $\mathbb{N}$ as a subspace of $\mathbb{R}$ with





the usual metric). Then

$$
B \left( 5 , \frac { 3 } { 2 } \right) = \left\{ n \in \mathbb { N } \mid | n - 5 | < \frac { 3 } { 2 } \right\} = \left\{ 4 , 5 , 6 \right\} .
$$

(b) Now consider N with the discrete metric $\rho$. Then

$$
B _ { \rho } \left( 5 , \frac { 3 } { 2 } \right) = \left\{ n \in \mathbb { N } \mid \rho \left( n , 5 \right) < \frac { 3 } { 2 } \right\} = \mathbb { N }
$$

since for each $n \in \mathbb{N}$, $\rho(n,5)=0$ or $1$.

Example 02.3. Consider $\mathbb{R}^2$ with the usual metric. Then for any $(x,y) \in \mathbb{R}^2$ and $\varepsilon > 0$, $B((x,y),\varepsilon)$ is the open disk with centre $(x,y)$ and radius $\varepsilon$. In other words it is the set of all points inside the circle with centre $(x,y)$ and radius $\varepsilon$.

Example 02.4. Consider $[0,1]$ with the usual metric. Then

$$
B \left( \frac { 1 } { 4 } , \frac { 1 } { 2 } \right) = \left\{ x \in [ 0 , 1 ] : \ \left| x - \frac { 1 } { 4 } \right| < \frac { 1 } { 2 } \right\} = \left[ 0 , \frac { 3 } { 4 } \right) .
$$

Notice that

$$
\left[ 0 , \frac { 3 } { 4 } \right) = [ 0 , 1 ] \cap \left( \frac { 1 } { 4 } - \frac { 1 } { 2 } , \ \frac { 1 } { 4 } + \frac { 1 } { 2 } \right) = [ 0 , 1 ] \cap B _ { \mathbb { R } } \left( \frac { 1 } { 4 } , \frac { 1 } { 2 } \right) ,
$$

where by $B_{\mathbb{R}}(a,\varepsilon)$ we mean the ball in $\mathbb{R}$. In general, if $(X,d)$ is a metric space and $S$ a subspace, then for any $x\in S$ and $r>0$, $B_{S}(x,r)=S\cap B_{X}(x,r)$; where the subscript on $B$ indicates the metric space in which the ball is computed. Prove this.

Now we come to the definition of openness.

Definition 02.3. Let $(X,d)$ be a metric space and $S \subseteq X$. Then:

a point $x \in S$ is called an interior point of $S$ if there is a ball $B(x,r)$ such that $B(x,r) \subseteq S$.

the interior of $S$, denoted int$(S)$ or $S^{0}$, is the set of all interior points of $S$.

$S$ is said to be open if each point of $S$ is an interior point of $S$.

Let us reiterate. A subset $S$ of a metric space is open provided for each $x \in S$, there is a ball with centre $x$ which is contained in $S$. Thus a set $T$ is not open provided for some





$t\in T$ there is no ball with centre $t$ which is contained in $T$.

Concerning the empty set, note that because the empty set has no points, it is true that there is no point of the empty set which is not an interior point. Consequently, the empty set is open.

Note that openness of a subset $S$ of a metric space depends on the metric in question. For that reason, if $S$ is an open subset of $(X,d)$ we say $S$ is open in $(X,d)$. As an example of an open set we show that every ball $B(x,\varepsilon)$ is open regardless of the metric.

Theorem 02.4. Let $(X,d)$ be a metric space. Then every ball $B(a,r)$ in $(X,d)$ is open.

Proof. Let $x \in B(a,r)$. We must show that there exists a real number $\varepsilon > 0$ such that $B(x,\varepsilon) \subseteq B(a,r)$. Since $x \in B(a,r), d(x,a) < r$. Put $\varepsilon = r - d(x,a)$ and note that $\varepsilon > 0$. We claim that $B(x,\varepsilon) \subseteq B(a,r)$. To see this let $z \in B(x,\varepsilon)$. Then $d(z,x) < \varepsilon$. Now

$$
\begin{array}{rl} { d ( z , a ) } & { \leq  d ( z , x ) + d ( x , a ) } \\& { <  \varepsilon + d ( x , a ) } \\& { =  r - d ( x , a ) + d ( x , a ) } \\& { =  r . } \end{array}
$$

Thus $d(z,a)<r$; which implies that $z\in B(a,r)$. As $z$ is an arbitrary element of $B(x,\varepsilon)$, it follows that $B(x,\varepsilon)\subseteq B(a,r)$. Therefore $B(a,r)$ is open. $\square$

The foregoing theorem justifies calling balls of the form $B(a,r)$ open. Notice that for any $a,b\in\mathbb{R}$ with $a<b$, the interval $(a,b)=(x-\varepsilon,\ x+\varepsilon)$ with

$$
x = { \frac { a + b } { 2 } } \ \ \mathrm { a n d } \ \ \varepsilon = { \frac { b - a } { 2 } } > 0 .
$$

Thus the interval $(a,b)$ is an open ball in $\mathbb{R}$ with the usual metric. It is precisely for this reason that we have always been taught to call such intervals "open intervals".

Let us observe that the interval $[a,b)$ is not open in $\mathbb{R}$ with the usual metric. Indeed, for any $\varepsilon > 0$, $B(a,\varepsilon) = (a-\varepsilon, a+\varepsilon) \nsubseteq [a,b)$. Thus $[a,b)$ has a point which is not its interior point. Likewise, one shows that each of the intervals $(a,b]$ and $[a,b]$ is not open.

Example 02.5. Let $(X,d)$ be a discrete metric space. For any $x \in X$ and $\varepsilon$ with $0 < \varepsilon \leq 1$ we have $B(x,\varepsilon) = \{x\}$. (Why?) Consequently if $S$ is any subset of $X$, then for each $x \in S$ we have $B\left(x,\frac{1}{2}\right) = \{x\} \subseteq S$. Thus every element of $S$ is an interior point of $S$. Hence $S$ is open.





The above example says in a discrete metric space every subset is open. So, for instance, in $\mathbb{R}$ equipped with the discrete metric, $[0,1)$ is open. Of course in $\mathbb{R}$ with the usual metric $[0,1)$ is not open as observed above.

We showed above that in any metric space the empty set is open. Now let $(X,d)$ be a metric space. For any $x \in X$, $B(x,r) \subseteq X$ for any $r > 0$. Thus each point of $X$ is an interior point of $X$. This shows that $X$ is open in itself.

Example 02.6. We showed above that in $\mathbb{R}$ with the usual metric, the set $[a,b)$ ($a,b \in \mathbb{R}$ with $a < b$) is not open in $\mathbb{R}$. If we equip $[a,b)$ with the subspace metric, then $[a,b)$ is open in itself. By this example we are trying to emphasise that openness of a subset has everything to do with the containing metric space.

The next result tells us that arbitrary unions of open sets are open sets, and finite intersections of open sets are open sets.

Theorem 02.5. Let $(X,d)$ be a metric space. Then

(a) If $\{A_{\alpha} \mid \alpha \in \Gamma\}$ is any collection of open subsets of $X$, then $\bigcup_{\alpha \in \Gamma} A_{\alpha}$ is open in $X$.

(b) If $A_{1}, A_{2}, ..., A_{m}$ are finitely many open subsets of $X$, then $\bigcap_{i=1}^{m} A_{i}$ is open in $X$.

Proof. (a) Let $x \in \bigcup_{\alpha \in \Gamma} A_{\alpha}$. Then there exists $\alpha_0 \in \Gamma$ such that $x \in A_{\alpha_0}$. Since $A_{\alpha_0}$ is open, there is a ball $B(x, r)$ such that $B(x, r) \subseteq A_{\alpha_0}$. But $A_{\alpha_0} \subseteq \bigcup_{\alpha \in \Gamma} A_{\alpha}$, so $B(x, r) \subseteq \bigcup_{\alpha \in \Gamma} A_{\alpha}$. Thus $\bigcup_{\alpha \in \Gamma} A_{\alpha}$ is open.

(b) Let $x \in \bigcap_{i=1}^{m} A_{i}$. Then $x \in A_{i}$ for each $i=1,\ldots,m$. Since each $A_{i}$ is open, there are positive numbers $r_{1},\ldots,r_{m}$ such that $B(x,r_{1}) \subseteq A_{1},\ldots,B(x,r_{m}) \subseteq A_{m}$. Now let

$$
r = \operatorname* { m i n } \{ r _ { 1 } , r _ { 2 } , \ldots , r _ { m } \} ,
$$

i.e. let $r$ be the smallest of the numbers $r_1,\ldots,r_m$. Then $B(x,r) \subseteq B(x,r_i)$ for each $i=1,2,\ldots,m$. In consequence, $B(x,r) \subseteq \bigcap_{i=1}^{m} B(x,r_i) \subseteq \bigcap_{i=1}^{m} A_i$.

The second result in the preceding theorem cannot be extended to an arbitrary intersection. Witness the following example.





Example 02.7. Consider $\mathbb{R}$ with the usual metric. For each $n=1,2,\ldots$ let $A_n=\left(0,1+\frac{1}{n}\right)$. Then each $A_n$ is open in $\mathbb{R}$. But now $\bigcap\limits_{n=1}^{\infty}A_n=(0,1]$ (prove this) which is not open in $\mathbb{R}$.

So far in our discussion, if $X$ is a metric space and $A$ an open subset, we have consistently said $A$ is open in $X$. Henceforth, if there is only one metric on a set $X$ under consideration, and if $A \subseteq X$ is open in $X$ with the metric in question, we shall simply say $A$ is an open subset of $X$; or, briefer still, we shall say $A$ is open. Likewise, when dealing with $\mathbb{R}^n$ (for any $n$), if we say $A \subseteq \mathbb{R}^n$ is open we shall be meaning that $A$ is open in $\mathbb{R}^n$ equipped with the usual metric. In this language, Theorem 02.5 says a union of open sets is open, and a finite intersection of open sets is open.

The next result shows how open subsets of a subspace can be obtained from those of the containing metric space.

Theorem 02.6. Let $(X,d)$ be a metric space and $S \subseteq X$ be equipped with the subspace metric. Then a set $A \subseteq S$ is open in $S$ if and only if $A = S \cap U$ for some set $U \subseteq X$ which is open in $X$.

Proof. (⇒) Assume $A \subseteq S$ is open in $S$. If $A = \emptyset$, then $A = S \cap \emptyset$, and the result follows since $\emptyset$ is open in $X$. If $A \neq \emptyset$, for each $a \in A$ there is a ball $B_S(a, r_a)$ such that $B_S(a, r_a) \subseteq A$. Now $B_S(a, r_a) = S \cap B_X(a, r_a)$. [Verify this.] Define $U \subseteq X$ by

$$
U = \bigcup _ { a \in A } B _ { X } ( a , r _ { a } ) .
$$

Then $U$ is open in $X$ since it is a union of open sets. Now we claim that $S \cap U = A$. To prove the claim, notice that

$$
\begin{array}{rl} { S \cap U } & { = \ S \cap \bigcup _ { a \in A } B _ { X } ( a , r _ { a } ) } \\& { = \ \bigcup _ { a \in A } ( S \cap B _ { X } ( a , r _ { a } ) ) } \\& { = \ \bigcup _ { a \in A } B _ { S } ( a , r _ { a } ) } \\& { = \ A , } \end{array}
$$

the last equality holding because each $B_S(a,r_a) \subseteq A$, so that $\bigcup_{a \in A} B_S(a,r_a) \subseteq A$; and clearly $A \subseteq \bigcup_{a \in A} B_S(a,r_a)$ since for each $x \in A$, $x \in B_S(x,r_x) \subseteq \bigcup_{a \in A} B_S(a,r_a)$. (⇐) Assume $A = S \cap U$ for some $U$ open in $X$. To prove that $A$ is open in $S$, let $a \in A$.





Then $a \in U$. Since $U$ is open in $X$, there exists a ball $B_X(a,r) \subseteq U$. Then

$$
B _ { S } ( a , r ) = B _ { X } ( a , r ) \cap S \subseteq U \cap S = A .
$$

So every point of $A$ is an interior point (relative to the subspace metric) of $A$. This shows that $A$ is open in $S$. $\square$

In the case of $\mathbb{R}$ we have a remarkable result which tells us that every open subset of $\mathbb{R}$ is expressible as a union of countably many disjoint open intervals. Recall that an interval in $\mathbb{R}$ is a subset of the form $(-\infty, \infty)$, $(-\infty, a)$, $(-\infty, a]$, $[a, \infty)$, $(a, \infty)$, $(a, b)$, $(a, b]$, $[a, b]$ and $[a, b]$. Open intervals are precisely the intervals $(-\infty, \infty)$, $(-\infty, a)$, $(a, \infty)$, $(a, b)$.

For purposes of this discussion, if $A \subseteq \mathbb{R}$ is not bounded above we shall put $\sup A = \infty$, and if $B \subseteq \mathbb{R}$ is not bounded below we shall put $\inf B = -\infty$. Given an open subset $S$ of $\mathbb{R}$, call an interval $I$ a component interval of $S$ provided $I \subseteq S$ and for any open interval $J$ with $I \subseteq J \subseteq S$ we have $I = J$. In other words, a component interval of $S$ is an open interval contained in $S$ which is such that it is not a proper subinterval of any other open interval contained in $S$. This does not mean that a component interval of $S$ contains every interval contained in $S$.

Example 02.8. Let $S=(-\infty,0)\cup(1,7)\cup(7,23)$. Then each of $(-\infty,0),(1,7)$ and $(7,23)$ is a component interval of $S$. $(1,23)$ is not a component interval of $S$ (why not?).

Lemma 02.1. Let $S$ be a nonempty open subset of $\mathbb{R}$. Then every point of $S$ belongs to one and only one component interval of $S$.

Proof. Let $x \in S$. Since $S$ is open, there is an open interval (recall that balls in $\mathbb{R}$ are finite intervals of the form $(a,b)$ with $a,b \in \mathbb{R}$, $a < b$) $I$ such that $x \in I \subseteq S$. Let

$$
a = \operatorname* { i n f } \{ c \in \mathbb { R } \mid ( c , x ) \subseteq S \}
$$

and let

$$
b = \operatorname* { s u p } \{ d \in \mathbb { R } \mid ( x , d ) \subseteq S \} .
$$

Put $I=(a,b)$. We claim that $I$ is a component interval of $S$ containing $x$.

(i) $I \subseteq S$: $I = (a, x) \cup \{x\} \cup (x, b)$. Since $x \in S$, it suffices to show that $(a, x) \subseteq S$ and $(x, b) \subseteq S$. We show $(a, x) \subseteq S$ and leave the other verification as an exercise. There are two cases; namely $a = -\infty$ and $a \in \mathbb{R}$. In the former case we have $(r, x) \subseteq S$ for every real number $r < x$. This clearly implies $(-\infty, x) \subseteq S$. In the latter case, for any natural number $n$, $(a + \frac{1}{n}, x) \subseteq S$ for otherwise $\inf\{c \in \mathbb{R} \mid (c, x) \subseteq S\}$ would be





bigger than $a+\frac{1}{n}$, which is false since this infimum is $a$. Thus $\bigcup_{n=1}^{\infty}\left(a+\frac{1}{n},x\right)\subseteq S$.

But $\bigcup_{n=1}^{\infty}\left(a+\frac{1}{n},\ x\right)=(a,x)$.

(ii) Let $J$ be an interval with $I \subseteq J \subseteq C$. We must show that $I = J$. As we have $I \subseteq J$, it suffices to show that $J \subseteq I$. So let $y \in J$. If $y = x$, then $y \in I$. If $y < x$, then there exists $z \in J$ such that $z < y$. This shows that $y \in I$. Similarly we can show (do it) that if $y > x$ then $y \in I$. We deduce therefore that $J = I$.

We have so far shown that $I$ is a component interval of $S$ containing $x$. To be done we still need to show that $I$ is the only such component interval. So let $I'$ be a component interval of $S$ containing $x$. Then $I \cup I'$ is an open interval with $I \subseteq I \cup I'$, $I' \subseteq I \cup I'$ and $I \cup I' \subseteq S$. Therefore by the definition of component interval we have that $I \cup I' = I = I'$. $\square$

Theorem 02.7. Every nonempty open set $S$ in $\mathbb{R}$ is the union of countably many disjoint component intervals of $S$.

Proof. For each $x \in S$ let $I_x$ denote the component interval of $S$ containing $x$. Then clearly $S = \bigcup_{x \in S} I_x$. If two such component intervals, $I_z$ and $I_w$ say, have a point in common, then their union $I_z \cup I_w$ is an open interval contained in $S$ and containing both $I_z$ and $I_w$. So, as argued in the proof of Lemma 02.1, it follows that $I_z = I_w$. This shows that any two distinct component intervals of $S$ are disjoint. $\square$

It now remains to show that the collection of all these component intervals is countable. To this end write the set of rational numbers as $\mathbb{Q} = \{r_1, r_2, r_3, \ldots\}$, which is possible since $\mathbb{Q}$ is countable. Each $I_x$ contains infinitely many rationals $r_n$ (recall Theorem 03.4). Among the rationals $r_n$ contained in $I_x$ there is exactly one with smallest index $k$. Define a function $F : \{I_x \mid x \in S\} \to \mathbb{N}$ by

$$
F ( I _ { x } ) = \operatorname* { m i n } \{ k \in \mathbb { N } \mid r _ { k } \in I _ { x } \} .
$$

Because the intervals $I_x$ ($x \in S$) are mutually disjoint, it follows that $F$ is a one-to-one function. We therefore have that $\{I_x \mid x \in S\}$ is countable. ■

Remark 02.1. (a) The foregoing theorem tells us about the structure of all open sets in $\mathbb{R}$. They are expressible as countable unions of disjoint open intervals.

(b) The expression of an open set $S$ in $\mathbb{R}$ in this manner is unique. In fact if $S$ is a union of disjoint open intervals, then these intervals must be component intervals of $S$. Note that this statement is a consequence of Lemma 02.1.





(c) In particular, if $S$ is an open interval then $S$ is its only component interval. Thus, an open interval in $\mathbb{R}$ cannot be expressed as a union of two nonempty disjoint open sets. Prove this!

Now we turn our attention to interiors of sets. Recall that if $S$ is a subset of a metric space $(X,d)$, then the interior of $S$ is the set of all interior points of $S$. (Definition 02.3.) We will show that int$(S)$ is the largest open set contained in $S$. Recall that in order to show two sets $A$ and $B$ to be equal, one shows that $A \subseteq B$ and $B \subseteq A$.

Theorem 02.8. Let $S$ be a subset of a metric space $(X,d)$. Then

$$
i n t ( S ) = \bigcup \{ U \subseteq S \mid U \ \ i s \ o p e n \ i n \ X \} .
$$

Proof. Let $x \in \text{int}(S)$. Then there exists $r > 0$ such that $B(x,r) \subseteq S$. Since balls $B(x,r)$ are open, it follows that $x \in \bigcup\{U \subseteq S \mid U \text{ is open in } X\}$. We therefore have that

$$
\operatorname { i n t } ( S ) \subseteq \bigcup \{ U \subseteq S \mid U { \mathrm { ~ i s ~ o p e n ~ i n ~ } } X \} .
$$

On the other hand let $z \in \bigcup\{U \subseteq S \mid U \text{ is open in } X\}$. Then there exists an open set $U$ in $X$ such that $z \in U \subseteq S$. Since $U$ is open, there is a ball $B(z, \varepsilon) \subseteq U \subseteq S$. This shows that $z$ is an interior point of $S$; and therefore $z \in \text{int}(S)$. So $\bigcup\{U \subseteq S \mid U \text{ is open in } X\} \subseteq \text{int}(S)$, and equality follows. $\square$

Corollary 02.9. Let $S$ be a subset of a metric space $(X,d)$. Then

(a) $int(S)$ is open.

(b) $int(S)$ is the largest open set of $X$ contained in $S$.

Proof. Exercise.

Theorem 02.10. Let $A$ and $B$ be subsets of a metric space $X$. Then

(a) $int(A \cap B) = int(A) \cap int(B)$

(b) $A \subseteq B \Rightarrow $ $int(A) \subseteq $ $int(B)$

(c) $A$ is open $\Leftrightarrow A = $ $int(A)$





(d) $int(A) \cup int(B) \subseteq int(A \cup B)$

(e) $int(\emptyset)=\emptyset$, $int(X)=X$

(f) $int(int(A))=int(A).$

Proof. We prove (b) and leave the proofs of remaining parts as an exercise. If $A \subseteq B$, then $\text{int}(A) \subseteq A \subseteq B$. So $\text{int}(A)$ is an open set contained in $B$. But $\text{int}(B)$ is the largest open set contained in $B$; therefore $\text{int}(A) \subseteq \text{int}(B)$. $\square$

Remark 02.2. We have deliberately given a proof of Theorem 02.10(b) without reference to points. One can also show this by showing that each point in int(A) lies in int(B).

Example 02.9. We give an example that shows that "$\sqsubseteq$" cannot be replaced by "$=$" in Theorem 02.10(d). Consider $\mathbb{R}$ with the usual metric. Let us compute the interiors of $\mathbb{Q}$, $\mathbb{R}$ and $\mathbb{R}\backslash\mathbb{Q}$. We immediately have $\text{int}(\mathbb{R})=\mathbb{R}$ (why?). Let $q\in\mathbb{Q}$. For any $\varepsilon>0$, $B(q,\varepsilon)=(q-\varepsilon,q+\varepsilon)$ contains an irrational number. So $B(q,\varepsilon)\nsubseteq\mathbb{Q}$. Thus there is no rational number which is an interior point of $\mathbb{Q}$. Similarly, for any irrational $s$ and $\delta>0$, $B(s,\delta)=(s-\delta,s+\delta)$ contains a rational number, and is therefore not contained in $\mathbb{R}\backslash\mathbb{Q}$. Therefore $\text{int}(\mathbb{R}\backslash\mathbb{Q})=\text{int}(\mathbb{Q})=\emptyset$. However $\text{int}(\mathbb{Q}\cup\mathbb{R}\backslash\mathbb{Q})=\text{int}(\mathbb{R})=\mathbb{R}$. So we have sets $A$ and $B$ such that

$$
\operatorname { i n t } ( A \cup B ) \neq \operatorname { i n t } ( A ) \cup \operatorname { i n t } ( B ) .
$$

Example 02.10. Let $a,b$ be real numbers with $a<b$. Then in $\mathbb{R}$,

$$
\operatorname { i n t } ( [ a , b ) ) = \operatorname { i n t } ( ( a , b ] ) = \operatorname { i n t } ( [ a , b ] ) = ( a , b ) .
$$

Also, int((−∞, b)) = (−∞, b), int([a, ∞)) = (a, ∞). Prove these statements.

Activity 02.1. (a) Let $x,y$ be distinct elements of a metric space. Prove that there are disjoint open sets $U$ and $V$ such that $x \in U$ and $y \in V$.

(b) Let $(X,d)$ be a metric space and let $r$ be a real number with $r>0$. Define $\rho: X\times X\to\mathbb{R}$ by $\rho(x,y)=rd(x,y)$.

(i) Prove that $\rho$ is a metric on $X$.

(ii) Show that a subset of $X$ is open in $(X,d)$ if and only if it is open in $(X,\rho)$.

(iii) Does it follow that for each $A \subseteq X$, $\text{int}_d(A) = \text{int}_\rho(A)$?

We next examine closed sets and closures.





# 03 CLOSED SETS AND CLOSURE

Having studied open sets we now pay attention to their complements. A number of results here will be obtainable from their counterparts in the open-sets-section by appealing to De Morgan's laws, namely:

For any set $X$ and collection $\{S_{\alpha} \mid \alpha \in \Gamma\}$ of subsets of $X$, we have

(i) $X\bigcup_{\alpha\in\Gamma}S_{\alpha}=\bigcap_{\alpha\in\Gamma}(X\backslash S_{\alpha})$, and

(ii) $X\bigcap_{\alpha\in\Gamma}S_{\alpha}=\bigcup_{\alpha\in\Gamma}(X\backslash S_{\alpha})$.

Definition 03.1. A subset $S$ of a metric space $(X,d)$ is closed if its complement $X\backslash S$ is open.

Example 03.1. In any metric space $(X,d)$, every closed ball $\overline{B}(x,r)$ is closed. Recall that $\overline{B}(x,r)=\{y\in X\mid d(x,y)\leq r\}$. To prove that $\overline{B}(x,r)$ is closed we must show that $X\backslash\overline{B}(x,r)$ is open. Let $z\in X\backslash\overline{B}(x,r)$. Then $d(z,x)>r$. Put $\delta=d(z,x)-r$ and note that $\delta>0$. We will show that $B(z,\delta)\subseteq X\backslash\overline{B}(x,r)$ which will complete the proof. So let $w\in B(z,\delta)$. Then $d(w,z)<\delta$. Now $d(x,w)+d(w,z)\geq d(x,z)$. Hence $d(x,w)\geq d(x,z)-d(w,z)>d(x,z)-\delta=r$. This shows that $d(w,x)>r$; whence we deduce that $w\notin\overline{B}(x,r)$. Consequently $w\in X\backslash\overline{B}(x,r)$. So every element of $X\backslash\overline{B}(x,r)$ is an interior point. Thus $X\backslash\overline{B}(x,r)$ is open and therefore $\overline{B}(x,r)$ is closed. So, as in the case of the open ball, we are justified to call $\overline{B}(x,r)$ a closed ball.

Example 03.2. Let $a,b\in\mathbb{R}$ with $a<b$. Then each of the intervals $[a,b]$, $(-\infty,b]$ and $[a,\infty)$ is closed. Indeed, $[a,b]=\mathbb{R}\backslash(-\infty,a)\cup(b,\infty)$; $(-\infty,b)=\mathbb{R}\backslash(b,\infty)$ and $[a,\infty)=\mathbb{R}\backslash(-\infty,a)$.

Example 03.3. In a discrete metric space every subset is closed. Why is this so?

Theorem 03.2. Let $(X,d)$ be a metric space and $x_0$ be any element of $X$. Then $\{x_0\}$ is closed.

Proof. Let $z \in X \backslash \{x_0\}$. This means that $z \neq x_0$. So $r = d(z, x_0) > 0$. Since $d(x_0, z)$ is not less than $r$, it follows that $x_0 \notin B(z, r)$. Hence $B(z, r) \subseteq X \backslash \{x_0\}$. So $X \backslash \{x_0\}$ is open, and the theorem is proved. $\square$

The theorem above tells us that singletons (ie sets consisting of a single point) are closed in any metric space. Informally, we say "points are closed" in a metric space. We will see that in fact every finite set is closed.





The following result gives properties of closed sets which are akin to those of open sets given in Theorem 02.5.

Theorem 03.3. Let $X$ be a metric space. Then

(a) $X$ and $\emptyset$ are closed sets.

(b) If $A_1, A_2, \ldots, A_m$ are finitely many closed sets, then $\bigcup_{\alpha \in \Gamma} A_i$ is closed.

(c) If $\{A_\alpha \mid \alpha \in \Gamma\}$ is a collection of closed sets, then $\bigcap_{\alpha \in \Gamma} A_\alpha$ is closed.

Proof. (a) $X = X \backslash \emptyset$ and as $\emptyset$ is open we have that $X$ is closed. Next, $\emptyset = X \backslash X$, and therefore $\emptyset$ is closed since $X$ is open.

(b) and (c) are left as exercises. Apply the De Morgan's law to Theorem 02.5.

Corollary 03.4. In any metric space, every finite subset is closed.

Proof. Let $S$ be a finite subset of a metric space. Say $S = \{s_1, \ldots, s_m\}$. Then

$$
S = \{ s _ { 1 } \} \cup \cdots \cup \{ s _ { 2 } \} ,
$$

a finite union of closed sets (recall that singletons are closed – Theorem 03.2). So by Theorem 03.3(b) we have that $S$ is closed. $\square$

When we were studying open sets we encountered the concept of the interior of a set. We saw that the interior was defined in terms of points in that it is the set of all interior points; and showed it to be expressible in terms of open sets in that it is the largest open subset of any given set. Likewise in the discussion on closed sets we will introduce the concept of closure. This we will define in terms of points and later prove that it is expressible in terms of closed sets.

Definition 03.5. Let $(X,d)$ be a metric space and $x \in X$. By a neighbourhood (to be abbreviated $nbd$) of $x$ we mean an open ball containing $x$ (not necessarily centered at $x$).

For instance in $\mathbb{R}^2$, $B\left((0,0),1\right)$ is a nbd of the point $\left(-\frac{1}{2},\frac{1}{3}\right)$. We caution that in certain books by a nbd of a point is meant any open set (not necessarily a ball) containing the point.

All results stated in terms of neighbourhoods as defined here are true with "nbd" meaning any open set containing the point, and vice versa. With this nomenclature, note (actually prove) that a set is open if and only if it contains a nbd of each of its points.





Definition 03.6. Let $(X,d)$ be a metric space, $S$ be a subset of $X$ and $z \in X$. We say $z$ is an adherent point of $S$ if every $\text{nbd}$ of $z$ contains a point of $S$. We say $z$ is an accumulation point of $S$ if every $\text{nbd}$ of $z$ contains a point of $S$ different from $z$. The closure of $S$, denoted by $\overline{S}$ or $\text{cl}(S)$, is the set of all adherent points of $S$. The derived set of $S$, denoted by $S'$, is the set of all accumulation points of $S$.

Let us pause a bit and digest these concepts. For an adherent point $p$ of a set $A$ we require that every ndb of $p$ must contain a point of $A$. Such a point may be $p$ itself. However, for $p$ to be an accumulation point of $A$, every ndb of $p$ must contain a point of $A$ different from $p$. In other words, every ndb of $p$ must contain a point of $A\backslash\{p\}$. It clearly then follows that every accumulation point of a set $B$ is an adherent point of $B$. In symbols, $B'\subseteq\overline{B}$. Is the converse true? Before answering this let us notice that for any subset $S$ of a metric space, if $z\in S$ then every ndb of $z$ contains a point of $S$ ($z$ itself), and so every point of $S$ is an adherent point of $S$. That is, $S\subseteq\overline{S}$. The example below shows that not every adherent point of a set is an accumulation point of the set.

Example 03.4. Consider $\mathbb{N}$ as a subset of $\mathbb{R}$ with the usual metric. For any $m \in \mathbb{N}$, $m$ is an adherent point of $\mathbb{N}$. Now $B(m, \frac{1}{2}) = \{m\}$ is a $\text{nbd}$ of $m$ which contains no element of $\mathbb{N}$ different from $m$. Thus $m$ is not an accumulation point of $\mathbb{N}$. We have actually shown that $\mathbb{N}' = \emptyset$.

In the discussion preceding Example 03.4, we saw that for any subset $B$ of a metric space, $B' \subseteq \overline{B}$ and $B \subseteq \overline{B}$. Hence $B' \cup B \subseteq \overline{B}$. In fact we have the following result.

Theorem 03.7. Let $S$ be a subset of a metric space. Then $\overline{S} = S \cup S'$.

Proof. We have already observed that $S \cup S' \subseteq \overline{S}$. So it remains to show that $\overline{S} \subseteq S \cup S'$. Let $x \in \overline{S}$. If $x \notin S$, then given a $\text{nbd } N$ of $x$ we have that $N$ contains a point $p$ of $S$ since $x$ is an adherent point of $S$. As $x \notin S$ it follows that $p \neq x$. Thus $N$ contains a point of $S$ different from $x$. Since $N$ is an arbitrary $\text{nbd}$ of $x$, we conclude that every $\text{nbd}$ of $x$ contains a point of $S \setminus \{x\}$. This proves that $x$ is an accumulation point of $S$, i.e. $x \in S'$. All in all we have shown that $\overline{S} \subseteq S \cup S'$. Therefore $\overline{S} = S \cup S'$. $\square$

In words the foregoing result says: (a) the closure of $S$ consists of $S$ together with all the accumulation points of $S$ and (b) $p\in\overline{S}\Leftrightarrow$ every $nbd$ of $p$ has nonempty intersection with $S$. It is important to note that an accumulation point of a set $A$ need not be an element of $A$. As an easy example, note that every $nbd$ of $1$ contains an element of the interval $(0,1)$. Thus $1$ is an accumulation point of $(0,1)$ which does not belong to $(0,1)$. On the other hand every point of $(0,1)$ is an accumulation point of $(0,1)$.





From the definition, if $p$ is an accumulation point of a set $A$, then we are guaranteed that every ndb of $p$ contains some point of $A$ different from $p$. We show below that every ndb of an accumulation point $p$ of a set $A$ contains infinitely many points of $A$.

Theorem 03.8. Let $(X,d)$ be a metric space, $A$ be a subset of $X$ and $p$ be an accumulation point of $A$. Then every $nbd$ of $p$ contains infinitely many points of $A$.

Proof. Suppose, by way of contradiction, that $p$ has a nbd $N$ that contains only finitely many points of $A$. Let $a_1, a_2, \ldots, a_m$ be those points of $N \cap A$ that are different from $p$. Let $r = \min\{d(p, a_1), \, d(p, a_2), \ldots, d(p, a_m)\}$. Then $r > 0$ since $d(p, a_i) > 0$ for each $i = 1, 2, \ldots, m$. Since $p \in N$ and $N$ is open, there exists $\varepsilon > 0$ such that $B(p, \varepsilon) \subseteq N$. Now let $\delta = \min\{r, \varepsilon\}$. Then $\delta > 0$ and $B(p, \delta)$ contains no point of $A\backslash\{p\}$. To see this, note that $B(p, \delta) \subseteq N$, so if it did contain a point of $A\backslash\{p\}$ that point would be $a_k$ for some $k = 1, \ldots, m$. But if $a_k \in B(p, \delta)$, then $d(p, a_k) < \delta \leq r \leq d(p, a_k)$, i.e. $d(p, a_k) < d(p, a_k)$; a contradiction. $\square$

Corollary 03.9. A finite subset of a metric space has no accumulation points.

Proof. This follows immediately from Theorem 03.8.

We saw above that an accumulation point of a set need not belong to the set. In the case of closed sets this cannot happen as the next result shows.

Theorem 03.10. The following statements about a subset $S$ of a metric space $(X,d)$ are equivalent.

(a) $S$ is closed.

(b) $S$ contains all its adherent points.

(c) $S$ contains all is accumulation points.

Proof. (a) $\Rightarrow$ (b): Let $p$ be an adherent point of $S$. Since $S$ is closed, $X\backslash S$ is open. So if $p$ were an element of $X\backslash S$ there would exist $r>0$ such that $B(p,r)\subseteq X\backslash S$. But then that would mean that $B(p,r)$ is a $\text{nbd}$ of $p$ which contains no point of $S$; a contradiction since $p$ is an adherent point of $S$. Thus $p\notin X\backslash S$, i.e. $p\in S$.

(b) $\Rightarrow$ (c): Every accumulation point is an adherent point. So if (b) holds, then $S$ contains all its accumulation points.

(c) $\Rightarrow$ (a): We must show that $X\backslash S$ is open. So let $p\in X\backslash S$. Then $p$ is not an accumulation of point $S$, for if it were then it would belong to $S$ by the hypothesis. So $p$





has a ndb $N$ which contains no point of $S\backslash\{p\}$. This means that $N\cap(S\backslash\{p\})=\emptyset$. Since $p\notin S$ anyway, it follows that $N\cap S=\emptyset$, and therefore $N\subseteq X\backslash S$. So $p$ is an interior point of $X\backslash S$, and hence $X\backslash S$ is open as required. $\square$

Remark 03.1. The statement (a) $\Leftrightarrow$ (c) in the above theorem says a set is closed if and only if it contains all its accumulation points. Now if a set has no accumulation point, some people might have qualms about the statement that "it contains all its accumulation points". This should however not cause us anxiety since (a) $\Leftrightarrow$ (c) of the foregoing theorem can also be written as: $S$ is closed $\Leftrightarrow S' \subseteq S$. Now if $S$ has no accumulation point, then $S' = \emptyset \subseteq S$; so that this case is in fact included in "S contains all its accumulation points". If you are still not comfortable with this, restate (a) $\Leftrightarrow$ (c) as: A subset of a metric space is closed if and only if it has no accumulation points or it contains all its accumulation points if it has any.

Corollary 03.11. Let $A$ be a subset of a metric space $(X,d)$. Then $A$ is closed if and only if $A=\overline{A}$.

Proof. (⇒) Let $A$ be closed. Then $\overline{A} \subseteq A$ by Theorem 03.10. Since $A \subseteq \overline{A}$ for every set $A$, we conclude that $A = \overline{A}$.

(⇐) Let $A=\overline{A}$. We show that $X\backslash A$ is open. Let $p\in X\backslash A=X\backslash\overline{A}$. Then $p\notin\overline{A}=A\cup A'$. Therefore $p$ is neither a point of $A$ nor an accumulation point of $A$. Hence $p$ has a ndb $N$ which does not intersect $A$. Then $N\subseteq X\backslash A$. So $p$ is an interior point of $X\backslash A$, and as $p$ was chosen arbitrarily, we conclude that $X\backslash A$ is open, whence the result follows. $\square$

Theorem 03.12. Let $S$ be a subset of a metric space $(X,d)$. Then

$$
{ \overline { { S } } } = \bigcap \{ F \subseteq X \mid F { \mathrm { ~ ~ i s ~ c l o s e d ~ a n d ~ ~ } } F \supseteq S \} .
$$

Proof. Let $F$ be a closed subset of $X$ with $S \subseteq F$. We want to show that $\overline{S} \subseteq F$. So let $x \in \overline{S}$. Then every ndb of $x$ has nonempty intersection with $S$; and therefore with $F$. This shows that $x \in \overline{F} = F$, since $F$ is closed. We therefore have that $\overline{S} \subseteq F$. As $F$ is an arbitrary closed subset of $X$ that contains $S$, we conclude that $\overline{S} \subseteq \bigcap\{F \subseteq X \mid F \text{ is closed and } F \supseteq S\}$. To show the reverse inclusion let $z \in \bigcap\{F \subseteq X \mid F \text{ is closed and } F \supseteq S\}$. If we assume that $z \notin \overline{S}$, then there is a ndb $N$ of $z$ with $N \cap S = \emptyset$. Thus $S \subseteq X \setminus N$. But now $X \setminus N$ is a closed set containing $S$; therefore $z \in X \setminus N$, which is a contradiction since $z \in N$ as $N$ is a ndb of $z$. So $z \in \overline{S}$, and hence $\bigcap\{F \subseteq X \mid F \text{ is closed and } F \supseteq S\} \subseteq \overline{S}$. This completes the proof. $\square$

Corollary 03.13. The closure of any subset of a metric space is closed.





Proof. Intersections of closed sets are closed.

We state the next result about closure and juxtapose it with its interior counterpart, Theorem 02.10. We deliberately include other results already stated. We shall use the notation $A^{0}$ for int$(A)$.

Theorem 03.14. Let $A$ and $B$ be subsets of a metric space $X$. Then

(a) $\overline{A}$ is closed $\Leftrightarrow A=\overline{A}$

(b) $\overline{(A)}=\overline{A}$

(c) $\overline{\emptyset}=\emptyset$ and $\overline{X}=X$

(d) $A\subseteq B\Rightarrow\overline{A}\subseteq\overline{B}$

(e) $\overline{A\cup B}=\overline{A}\cup\overline{B}$

(f) $\overline{A}$ is the smallest closed set containing $A$

(g) $\overline{A\cap B}\subseteq\overline{A}\cap\overline{B}$

(e) $\overline{A\cap B}\subseteq\overline{A}\cap\overline{B}$

Proof. We give a proof of (e) only and leave the proofs of other statements not proved so far as an exercise. Note that since $A \subseteq \overline{A}$ and $B \subseteq \overline{B}$, we have $A \cup B \subseteq \overline{A} \cup \overline{B}$. But now $\overline{A} \cup \overline{B}$ is a finite union of closed sets, so it is a closed set containing $A \cup B$. Thus, by Theorem 03.12, $\overline{A \cup B} \subseteq \overline{A} \cup \overline{B}$. So it remains to show that $\overline{A} \cup \overline{B} \subseteq \overline{A \cup B}$. Let $x \in \overline{A \cup B}$. Then $x \in \overline{A}$ or $x \in \overline{B}$. Suppose $x \in \overline{A}$. Let $N$ be a $\text{nbd}$ of $x$. Then $N \cap A \neq \emptyset$. Since $A \subseteq A \cup B$, it follows that $N \cap (A \cup B) \neq \emptyset$. Thus every $\text{nbd}$ of $x$ has a nonempty intersection with $A \cup B$, so $x \in \overline{A \cup B}$. Similarly, if $x \in \overline{B}$ we have that $x \in \overline{A \cup B}$. Thus $\overline{A} \cup \overline{B} \subseteq \overline{A \cup B}$, and consequently $\overline{A \cup B} = \overline{A} \cup \overline{B}$. $\square$

Example 03.5. Consider $\mathbb{R}$ with the usual metric. Then $\mathbb{Q}' = \mathbb{R}$ and $(\mathbb{R} \backslash \mathbb{Q}') = \mathbb{R}$. That is, every $x$ in $\mathbb{R}$ is an accumulation point of $\mathbb{Q}$ and also of $\mathbb{R} \backslash \mathbb{Q}$. Verify this. Thus $\overline{\mathbb{Q}} = \mathbb{Q} \cup \mathbb{Q}' = \mathbb{R}$. Similarly, $\overline{\mathbb{R} \backslash \mathbb{Q}} = \mathbb{R}$. So $\overline{\mathbb{Q}} \cap \overline{\mathbb{R} \backslash \mathbb{Q}} = \mathbb{R}$. On the other hand, $\overline{\mathbb{Q} \cap (\mathbb{R} \backslash \mathbb{Q})} = \emptyset$. So "$\subseteq$" in Theorem 03.14 ($g$) and ($g'$) cannot be replaced by "$=$". In $\mathbb{R}$, any interval of the form $(a, b]$ where $a, b \in \mathbb{R}$ with $a < b$ is neither open nor closed. So it is possible for a set to be neither open nor closed. Now in any metric space $X$, each of $\emptyset$ and $X$ is both open and closed. Is it possible for a proper subset (ie one which is neither empty nor the whole set) to be both open and closed? Witness the following example.

Example 03.6. Let $(X,d)$ be any discrete metric space. We saw in Example 02.5 that every subset of $X$ is open. Thus every subset of $X$ is closed (as its complement is open).

Example 03.7. In this example we examine the relationship between the closed ball $\overline{B}(x,r)$ and the closure $\overline{B}(x,r)$ of the open ball $B(x,r)$. If $y\in B(x,r)$, then $d(y,x)<r$; and so $d(y,x)\leq r$, implying that $B(x,r)\subseteq\overline{B}(x,r)$. Now $\overline{B}(x,r)$ is a closed set as was shown in Example 03.1. Because the closure of any set is the smallest closed set containing the set, we conclude that $\overline{B}(x,r)\subseteq\overline{B}(x,r)$.





Example 03.8. The preceding example shows that $\overline{B(x,r)} \subseteq \overline{B}(x,r)$. We now give examples where $\overline{B(x,r)} = \overline{B}(x,r)$ and where $\overline{B(x,r)} \neq \overline{B}(x,r)$. Consider $\mathbb{R}$ with the usual metric. Then $\overline{B(0,1)} = (\overline{-1,1}) = [-1,1]$. Also $\overline{B}(0,1) = [-1,1]$. Now consider $\mathbb{R}$ with the discrete metric. Then $\overline{B(0,1)} = \{\overline{0}\} = \{0\}$. On the other hand $\overline{B}(0,1) = \mathbb{R}$.

Definition 03.15. Let $A$ be a subset of a metric space $(X,d)$. A point $p\in X$ is called a boun-dary point of $A$ in case $p\in\overline{A}\cap\overline{X\setminus A}$. The boundary of $A$, denoted $bd(A)$, is the set of all boundary points of $A$. In other words, $bd(A)=\overline{A}\cap\overline{X\setminus A}$.

It is clear that $x \in \text{bd}(A)$ if and only if every $\text{nbd}$ of $x$ contains a point of $A$ as well as a point of the complement of $A$.

Example 03.9. Let $A$ be the subset of $\mathbb{R}^2$ given by $A = \{(x, y) \in \mathbb{R}^2 \mid x^2 + y^2 > 1\}$. Then $\text{bd}(A) = \{(x, y) \in \mathbb{R}^2 \mid x^2 + y^2 = 1\}$. Verify this.

Example 03.10. In $\mathbb{R}$ with the usual metric, $\mathrm{bd}(\mathbb{Q})=\overline{\mathbb{Q}}\cap\overline{\mathbb{R}\backslash\mathbb{Q}}=\mathbb{R}$. On the other hand, $\mathrm{bd}(\mathbb{N})=\mathbb{N}$.

Example 03.11. Let $A$ be a subset of a metric space which is both open and closed. Therefore its complement is also both open and closed. Now $\text{bd}(A) = \overline{A} \cap \overline{X \setminus A} = A \cap (X \setminus A)$ since $A = \overline{A}$ and $X \setminus A = \overline{X \setminus A}$. Thus $\text{bd}(A) = \emptyset$. In the exercise we ask that you prove that the converse is also true.

Definition 03.16. A subset $A$ of a metric space $(X,d)$ is said to be dense in $X$ (or simply dense) if $\overline{A}=X$. It is nowhere dense if $\operatorname{int}(\overline{A})=\emptyset$.

Example 03.12. The rationals are dense in the reals. That is, $\mathbb{Q}$ as a subset of $\mathbb{R}$ with the usual metric is dense in $\mathbb{R}$. Indeed $\overline{\mathbb{Q}}=\mathbb{R}$.

Theorem 03.17. Let $A$ be a subset of a metric space $(X,d)$. Then $A$ is dense in $X$ if and only if $A$ intersects every nonempty open set.

Proof. (⇒) Let $A$ be dense in $X$ and $U \subseteq X$ be a nonempty open set. We must show that $A \cap U \neq \emptyset$. If $A \cap U$ were empty, then we would have $A \subseteq X \backslash U$. But $X \backslash U$ is closed since $U$ is open. This would mean $\overline{A} \subseteq X \backslash U$. But $\overline{A} = X$ since $A$ is dense, so we would have $X \subseteq X \backslash U$, which is impossible as $U \neq \emptyset$.

(⇐) We show that every $x \in X$ is an element of $\overline{A}$. Let $x \in X$ and $N$ be a nbd of $x$. Then $N$ is a nonempty open set. Therefore $N \cap A \neq \emptyset$, by the hypothesis. We have thus shown that every nbd of $x$ contains a point of $A$. So $x \in \overline{A}$ and therefore $X \subseteq \overline{A} \subseteq X$. $\square$

Activity 03.1. (a) Let $A$ be a subset of a metric space with $\text{bd}(A) = \emptyset$. Show that $A$ is both open and closed.





(b) Let $A=\{(x,y)\in\mathbb{R}^2\mid y\geq0\}$. Find $\mathrm{bd}(A)$.

(c) Let $A$ and $B$ be subsets of a metric space $X$. Prove that $X\backslash(\overline{A}\cup B)=(X\backslash\overline{A})\cap(X\backslash\overline{B})$.

(d) Let $A$ be a subset of a metric space $X$. Prove that:

(i) $A^{0}$, $(X\backslash A)^{0}$ and $\mathrm{bd}(A)$ are pairwise disjoint sets whose union is $X$.

(ii) $\mathrm{bd}(A)$ is closed.

(iii) $\overline{A}=A^{0}\cup\mathrm{bd}(A)$.

(e) Let $A$ be a subset of a metric space $X$. Prove that $A$ is dense in $X$ if and only if $\text{int}(X\backslash A) = \emptyset$.

(f) Let $A$ be a subset of a metric space $X$. Prove that

(i) $\overline{X\backslash A}=X\backslash A^{0}$.

(ii) $(X\backslash A)^{0}=X\backslash\overline{A}$.

(g) Let $(X,d)$ be a metric space, $x \in X$ and $\varepsilon$ and $\delta$ be positive numbers with $\delta < \varepsilon$. Prove that $\overline{B(x,\delta)} \subseteq B(x,\varepsilon)$.

(h) Let $A$ be a subset of $\mathbb{R}$ which is bounded above. Show that $\sup A \in \overline{A}$.

(i) Let $A$ be a subset of a metric space. Prove that:

(i) $A'$ is closed.

(ii) $A$ and $\overline{A}$ have the same accumulation points.

(j) Do $A$ and $A'$ always have the same accumulation points? Prove your assertion.

(k) Let $S$ be a subspace of the metric space $X$. Prove that a subset $T$ of $S$ is closed in $S$ if and only if $T = S \cap K$ for some $K$ which is closed in $X$.

(l) Let $A$ be the subset of $\mathbb{R}$ given by $A = \{\frac{1}{n} - \frac{1}{m} \mid m, n \in \mathbb{N}\}$. Find all the accumulation points of $A$.

(m) Let $A$ be a subset of a metric space. Prove that $\text{int}(\text{bd}(A)) = \emptyset$ if $A$ is open or if $A$ is closed.

(n) Let $U$ be an open subset of $(X, d)$ and $A \subseteq X$. Show that $U \cap A = \emptyset \Rightarrow U \cap \overline{A} = \emptyset$.

We now move on to bounded sets, diameters and distances.





Throughout this section we shall adopt the convention that if $A$ is a nonempty subset of $\mathbb{R}$ which is not bounded above, then we set $\sup A = \infty$.

We define boundedness of a subset of a metric space in such a way that in the case of $\mathbb{R}$ it reduces to boundedness as per Definition 02.3. Recall that $A \subseteq \mathbb{R}$ is bounded if there exist real numbers $c$ and $d$ such that $c \leq x \leq d$ for all $x \in A$. Thus $A$ is bounded if and only if there are real numbers $\alpha$ and $\beta$ such that $\alpha < x < \beta$ for all $x \in A$. In other words $A$ is bounded if and only if $A$ is contained in some ball in $\mathbb{R}$.

Definition 04.1. Let $A$ be a subset of a metric space $(X,d)$. We say $A$ is bounded if $A \subseteq B(x,r)$ for some $r > 0$ and some $x \in X$.

Thus, a bounded subset of a metric space is one which is contained in some ball. Now let $A$ be a bounded subset of a metric space $(X,d)$. Find $x \in X$ and $r > 0$ such that $A \subseteq B(x,r)$. We intend to show that the set $\{d(a,b) \mid a,b \in A\}$ is bounded above. Of course it is bounded below since $0 \leq d(a,b)$ for all $a,b \in A$. Let $a,b \in A$. Then $d(a,b) \leq d(a,x) + d(x,b) \leq r + r = 2r$ since $d(a,x) \leq r$ and $d(x,b) \leq r$, as $a,b \in A \subseteq B(x,r)$. Therefore $2r$ is an upper bound for $\{d(a,b) \mid a,b \in A\}$. Thus, $A$ is bounded if and only if there exists $M > 0$ such that $d(x,y) \leq M$ for all $x,y \in A$.

Definition 04.2. Let $A$ be a subset of a metric space $(X,d)$. If $A$ is bounded, we define the diameter of $A$, denoted $\text{diam}(A)$, by

$$
d i a m ( A ) = \operatorname* { s u p } \{ d ( a , b ) \mid a , b \in A \} .
$$

If $A$ is not bounded we set $\text{diam}(A) = \infty$. We also set $\text{diam}(\emptyset) = 0$.

Example 04.1. Let $(X,d)$ be a metric space, $x \in X$ and $r > 0$. Then $\text{diam}(B(x,r)) \leq 2r$. Similarly, $\text{diam}(\overline{B}(x,r)) \leq 2r$. No doubt you are wondering why we are not saying the diameter of the closed ball with radius $r$ is equal to $2r$. Afterall the closed ball includes its boundary points; the points "on the circumference", so to speak. The flaw in this line of thinking is that you are pushing your geometric intuition about balls too far. Indeed in $\mathbb{R}^n$, $\text{diam}(B(x,r)) = \text{diam}(\overline{B}(x,r)) = 2r$.

However in our old friend, the discrete space, things aren't what they seem to be. Take any set $X$ with at least two elements and equipped with the discrete metric. For any $x \in X$, $\text{diam}(\overline{B}(x, \frac{1}{2})) = \text{diam}(\{x\}) = 0$. Also, $\text{diam}(\overline{B}(x, 1)) = 1$ and $\text{diam}(\overline{B}(x, 2)) = 1$. Note that the last two statements are false if $X$ has only one element.





Definition 04.3. Let $(X,d)$ be a metric space, $A$ and $B$ be nonempty subsets of $X$ and $z \in X$. The distance from $z$ to $A$, denoted $d(z,A)$, is defined by

$$
d ( z , A ) = \operatorname* { i n f } \{ d ( z , a ) \mid a \in A \} .
$$

The distance between $A$ and $B$, denoted $d(A,B)$, is defined by

$$
d ( A , B ) = \operatorname* { i n f } \{ d ( a , b ) \mid a \in A , \ b \in B \} .
$$

So if we wish to compute the distance between $z$ and $A$ we must compute $d(z,a)$ for all $a \in A$ and find the infimum of the set of all these numbers. Similarly for $d(A,B)$.

Example 04.2. In $\mathbb{R}$ with the usual metric, $d(-3,(2,8])=5$. Note that there is no point of $(2,8]$ which is closest to $-3$. On the other hand, $d(\sqrt{2},\mathbb{Q})=0$ since, although $\sqrt{2}\notin\mathbb{Q}$, no matter how small $\varepsilon>0$ is, there is a rational number $q$ such that $d(\sqrt{2},q)<\varepsilon$.

Theorem 04.4. Let $(X,d)$ be a metric space and $A \subseteq X$. For any $z \in X$, $z \in \overline{A}$ if and only if $d(z,A) = 0$.

Proof. (⇒) Suppose $z \in \overline{A}$ and let $\varepsilon > 0$. Then, as every nbd of $z$ contains a point of $A$, there exists $a \in A$ such that $a \in B(z, \varepsilon)$. Thus $d(z, A) < \varepsilon$. So any positive number cannot be a lower bound for $\{d(z, x) \mid x \in A\}$. But of course 0 is a lower bound for this set, therefore it is the greatest lower bound for this set; that is $0 = \inf\{d(z, x) \mid x \in A\} = d(z, A)$.

(⇐) Suppose $d(z,A)=0$. We must show that $z\in\overline{A}$. If we assume that $z\not\in\overline{A}$, then there exists some $\delta>0$ such that $B(z,\delta)\cap A=\emptyset$. This would mean that for each $x\in A$, $x\not\in B(z,\delta)$; that is, $d(z,x)\geq\delta$. Consequently $\delta$ would be a lower bound for $\{d(z,x)\mid x\in A\}$, and hence we would have $d(z,A)\geq\delta>0$, contradicting the hypothesis. $\square$

Theorem 04.5. Let $A$ be a bounded subset of a metric space $(X,d)$. Then $\overline{A}$ is bounded and $\text{diam}(\overline{A}) = \text{diam}(A)$.

Proof. Since $A$ is bounded, there exists $M > 0$ such that $d(x,y) \leq M$ for all $x$ and $y \in A$. We will show that $d(a,b) \leq M + 1$ for all $a,b \in \overline{A}$. Let $a,b \in \overline{A}$. Pick $x,y \in A$ such that $x \in B(a,\frac{1}{2})$ and $y \in B(b,\frac{1}{2})$. Then

$$
\begin{array}{rl} { d ( a , b ) } & { \leq  d ( a , x ) + d ( x , b ) } \\& { \leq  d ( a , x ) + d ( x , y ) + d ( y , b ) } \\& { \leq  \frac { 1 } { 2 } + M + \frac { 1 } { 2 } } \end{array}
$$





$$
= \ M + 1 .
$$

Therefore $\overline{A}$ is bounded.

To show that $\operatorname{diam}(\overline{A})=\operatorname{diam}(A)$, first note that if $B$ is a bounded set and $C \subseteq B$, then $C$ is bounded and $\operatorname{diam}(C) \leq \operatorname{diam}(B)$. Now let $\varepsilon>0$. As before, given $a, b \in \overline{A}$, find $x, y \in A$ such that $d(a, x)<\frac{\varepsilon}{2}$ and $d(b, y)<\frac{\varepsilon}{2}$. Then $d(a, b) \leq \operatorname{diam}(A)+\varepsilon$, arguing as above and noting that $d(x, y) \leq \operatorname{diam}(A)$. We therefore have that $\operatorname{diam}(A)+\varepsilon$ is an upper bound for $\{d(a, b) \mid a, b \in \overline{A}\}$. Hence $\operatorname{diam}(\overline{A}) \leq \operatorname{diam}(A)+\varepsilon$. As this is true for every $\varepsilon>0$, we deduce from Theorem 02.2 that $\operatorname{diam}(\overline{A}) \leq \operatorname{diam}(A)$. But $\operatorname{diam}(A) \leq \operatorname{diam}(\overline{A})$ since $A \subseteq \overline{A}$; so $\operatorname{diam}(\overline{A})=\operatorname{diam}(A)$. $\square$

Activity 04.1. (a) Let $(X,d)$ be a metric space. Prove that a subset $A$ of $X$ is closed if and only if for each $x \in X \setminus A$, $d(x,A) \neq 0$.

(b) Let $A$ and $B$ be nonempty subsets of a metric space $(X,d)$. Show that

$$
d ( A , B ) = \operatorname* { i n f } \{ d ( a , B ) \mid a \in A \} = \operatorname* { i n f } \{ d ( b , A ) \mid b \in B \} .
$$

(c) Give an example of a metric space $(X,d)$ and nonempty subsets $A$ and $B$ of $X$ such that $A \cap B = \emptyset$ but $d(A,B) = 0$.

(d) Let $A$ be a subset of a metric space such that $A \subseteq B(x,r)$ for some $x \in X$ and $r > 0$. Prove that $\text{diam}(A) \leq 2r$.

The Bolzano-Weierstrass Theorem will be looked at next.

# 05 THE BOLZANO-WEIERSTRASS THEOREM

Our goal in this section is to show that every infinite bounded subset of $\mathbb{R}^m$ has an accumulation point. This result does not hold in all metric spaces. Indeed consider $\mathbb{N}$ with the discrete metric. Then $A=\mathbb{N}$ is an infinite subset of $\mathbb{N}$. Since $d(x,y)\leq 1$ for all $x,y\in A$, it follows that $A$ is bounded. Now $A$ has no accumulation point since, for each $n\in\mathbb{N}$, $B(n,1)=\{n\}$ and therefore does not contain a point of $A\backslash\{n\}$.

In order to prove the Bolzano-Weierstrass Theorem for $\mathbb{R}^{m}$ (for the duration of this discussion $\mathbb{R}^{m}$ will have the usual metric), we shall need some preliminary results.

Theorem 05.1. For each $n \in \mathbb{N}$ let $I_n = [a_n, b_n]$, $(a_n < b_n)$ and suppose that $I_1 \supseteq I_2 \supseteq \ldots$; that is, $I_n \supseteq I_{n+1}$ for each $n \in \mathbb{N}$. Then $\bigcap_{n=1}^{\infty} I_n \neq \emptyset$.





Proof. For each $n \in \mathbb{N}$, $I_n \subseteq I_1$; and therefore $a_n \leq b_1$. The set $\{a_n \mid n \in \mathbb{N}\}$ is therefore bounded above. Let $\alpha$ denote its supremum. Thus $a_n \leq \alpha$ for each $n$. If we can show that $\alpha \leq b_n$ for each $n$, then we shall be done since we will then have $\alpha \in \bigcap_{n=1}^{\infty} I_n$. Suppose, by way of contradiction, that there is some $k \in \mathbb{N}$ such that $b_k < \alpha$. Since $\alpha = \sup\{a_n \mid n \in \mathbb{N}\}$ and $b_k$ is strictly smaller than $\alpha$, $b_k$ is not an upper bound for $\{a_n \mid n \in \mathbb{N}\}$. There is therefore some $\ell \in \mathbb{N}$ such that $b_k < a_\ell$. Let $p$ be the larger between $k$ and $\ell$; that is let $p = \max\{k, \ell\}$. Since $a_1 \leq a_2 \leq \ldots$ and $b_1 \geq b_2 \geq \ldots$ we conclude that $b_p \leq b_k < a_\ell \leq a_p$. This means that $b_p < a_p$; a contradiction. Therefore $a_n \leq \alpha \leq b_n$ for each $n \in \mathbb{N}$. $\square$

Remark 05.1. (a) The above result fails for intervals which are not closed. Take for instance $J_n = (0, \frac{1}{n})$, $n \in \mathbb{N}$. Then $J_1 \supseteq J_2 \supseteq J_3 \ldots$, but $\bigcap_{n=1}^{\infty} J_n = \emptyset$.

(b) What the theorem says is that $\bigcap_{n=1}^{\infty} I_{n}$ is not empty. It does not tell us how many elements the intersection contains. In fact if we let $\beta=\inf\{b_{n} \mid n \in \mathbb{N}\}$ then one can show that $[\alpha, \beta] \subseteq \bigcap_{n=1}^{\infty} I_{n}$.

<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>A closed cell in $\mathbb{R}^{m}$ is a set of the form $I=\{(x_{1},\ldots,x_{m})\in\mathbb{R}^{m}\mid a_{i}\leq x_{i}\leq b_{i}\}$ for $i=1,2,\ldots,m$ where $a_{i},b_{i}$ are real numbers with $a_{i}\leq b_{i}$. It is clear that $I=[a_{1},b_{1}]\times\ldots\times[a_{m},b_{m}].$

Corollary 05.2. Let $I_1, I_2, \ldots$ be closed cells in $\mathbb{R}^m$ with $I_1 \supseteq I_2 \supseteq \ldots$. Then there is a point in $\mathbb{R}^m$ which belongs to all the cells.

Proof. For each $k \in \mathbb{N}$ write $I_k = \{(x_1, \ldots, x_m) \mid a_k \leq x_i \leq b_k, \ i = 1, \ldots, m\}$ where $a_k$ and $b_k$ are real numbers with $a_k \leq b_k$ for $i = 1, \ldots, m$. Then note that

$$
\begin{aligned}&[a_{11},b_{11}]\:\supseteq\:[a_{21},b_{21}]\supseteq\ldots\supseteq[a_{n1},b_{n1}]\supseteq\ldots\\&[a_{12},b_{12}]\:\supseteq\:[a_{22},b_{22}]\supseteq\ldots\supseteq[a_{n2},b_{n2}]\supseteq\ldots\\&[a_{1m},b_{1m}]\:\supseteq\:[a_{2m},b_{2m}]\supseteq\ldots\supseteq[a_{nm},b_{nm}]\supseteq\ldots\end{aligned}
$$

By Theorem 05.1 find points $y_1 \in \bigcap_{k=1}^{\infty} [a_{k1}, b_{k1}], \ldots, y_m \in \bigcap_{k=1}^{\infty} [a_{km}, b_{km}]$. Then the point $y = (y_1, \ldots, y_m)$ belongs to all the cells.

Momentarily, for $x=(x_1,x_2,\ldots,x_m)\in\mathbb{R}^m$, let us write $||x||=\sqrt{x_1^2+\ldots+x_m^2}$. Recalling that addition and subtraction in $\mathbb{R}^m$ are defined componentwise; ie $x-y=$





$(x_{1}-y_{1},\ldots,x_{m}-y_{m})$ where $x=(x_{1},\ldots,x_{m})$ and $y=(y_{1},\ldots,y_{m})$, we note that with this notation the usual distance between $x$ and $y$ is $||x-y||$.

Lemma 05.1. Let $x=(x_1,\ldots,x_m)\in\mathbb{R}^m$. Then $|x_i|\leq||x||\leq\sqrt{m}\max\{|x_1|,\ldots,|x_m|\}$ for each $i=1,\ldots,m$.

Proof. Since $||x||^2 = x_1^2 + \ldots + x_m^2$, it is clear that $|x_i| \leq ||x||$ for each $i$. Likewise, if we put $b = \max\{|x_1|, \ldots, |x_n|\}$, then $||x||^2 \leq mb$, whence $||x|| \leq \sqrt{mb}$. $\square$

Theorem 05.3. (Bolzano-Weierstrass Theorem). Every bounded infinite subset of $\mathbb{R}^m$ has an accumulation point.

Proof. Let $B$ be a bounded subset of $\mathbb{R}^m$ that has infinitely many points. Because $B$ is bounded there is a closed cell $I_1$ which contains $B$. We divide $I_1$ into $2^m$ closed subcells by bisecting each of its sides. Since $I_1$ contains infinitely many points of $B$, at least one part obtained in this subdivision will contain infinitely many points of $B$. Let $I_2$ be one such part. Next we divide $I_2$ as we did $I_1$ to obtain a subcell $I_3$ of $I_2$ which contains infinitely many points of $B$. Continuing this process we obtain closed cells $I_1 \supseteq I_2 \supseteq I_3 \supseteq \ldots$. By Corollary 05.2 there is a point $y$ which belongs to all the cells $I_1, I_2, \ldots$. We show that $y$ is an accumulation point of $B$.

First note that if $I_1 = [a_1, b_1] \times \ldots \times [a_m, b_m]$ with $a_i < b_i$ and if we set

$$
\ell ( I _ { 1 } ) = \operatorname* { m a x } \{ b _ { 1 } - a _ { 1 } , \ldots , b _ { m } - a _ { m } \} ,
$$

then $\ell(I_{1}) > 0$, and in fact $\ell(I_{1})$ is the length (or diameter in the language of metric spaces) of the largest side of $I_{1}$. According to the above construction of the cells $I_{n}$, we have

$$
0 < \ell ( I _ { n } ) < \frac { 1 } { 2 ^{n - 1} } \cdot \ell ( I _ { 1 } ) ,
$$

for each $n \in \mathbb{N}$. Let $U$ be a nbd of $y$ and pick $r > 0$ such that $B(y, r) \subseteq U$. Let $k$ be a natural number such that

$$
k > 1 + \log _ { 2 } \frac { 1 } { \sqrt { m \cdot r \cdot \ell ( I _ { 1 } ) } } .
$$

Then

$$
\frac { \sqrt { m } } { 2 ^{k - 1} } \cdot \ell ( I _ { 1 } ) < r .
$$

For such $k$, if $w \in I_k$ then, by Lemma 05.1, we have that

$$
\| y - w \| \leq \sqrt { m } \ell ( I _ { k } ) = \frac { \sqrt { m } } { 2 ^{k - 1} } \ell ( I _ { 1 } ) < r ;
$$





showing that $I_k \subseteq U$. Since $I_k$ contains infinitely many points of $B$, so does $U$. So $U$ does contain a point of $B\backslash\{y\}$. Therefore $y$ is an accumulation point of $B$. $\square$

Activity 05.1. Prove the validity of the statements made in the Remark 05.1.

You have finished Learning Unit 2 for this module. We look at Convergence and Completeness in the next Learning Unit 3.





# LEARNING UNIT 3

# CONVERGENCE AND

#COMPLETENESS

The outcomes for this Learning Unit are:

Demonstrate the concept of convergence of sequences in a metric space.

Demonstrate the concept of completeness of a metric space.

# 01 SEQUENCES AND SUBSEQUENCES

In the theory of metric spaces sequences play a very important role. The aim of this chapter is to study convergence of sequences in metric spaces.

Definition 01.1. Let $X$ be a set (not necessarily a metric space). A sequence in $X$ is a function $f : \mathbb{N} \to X$. For each $n \in \mathbb{N}$ let $x_n$ denote $f(n)$. The elements $x_n$ of $X$ are called the terms of the sequence.

In practice we normally specify a sequence by its terms. We shall thus frequently speak of "a sequence $\{x_n\}$ in $X$" in place of the more tedious "a sequence $f : \mathbb{N} \to X$ in $X$ for which $f(n) = x_n$". It is crucial always to keep in mind the difference between a sequence $\{x_n\}$ and the set $\{x_n \mid n \in \mathbb{N}\}$ whose elements are the terms of the sequence $\{x_n\}$. Also important is that even if terms of a sequence are repeated, when one writes them down, one does not remove the repetition as one would do in the case of the set whose elements are the terms of a sequence. For instance the sequence $\{a_n\}$ in $\mathbb{R}$ for which

$$
a _ { n } = \left\{ \begin{array}{ll} { 1 , } & { \mathrm { i f }  n \mathrm { ~ i s ~ o d d } } \\{ n , } & { \mathrm { i f }  n \mathrm { ~ i s ~ e v e n } } \end{array} \right.
$$





has terms $1,2,1,4,1,6,\ldots$. The set of terms is of course $\{1,2,4,6,\ldots\}$.

Definition 01.2. Let $\{x_n\}$ be a sequence in a set $X$. Let $n_1 < n_2 < \ldots$ be a sequence of natural numbers which is strictly increasing. The sequence $x_{n_1}, x_{n_2}, x_{n_3}, \ldots, x_{n_k}, x_{n_{k+1}}, \ldots$ is called a subsequence of the sequence $\{x_n\}$.

The thrust of the definition of a subsequence $\{x_{n_k}\}$ is that the indices $n_1, n_2, \ldots$ are strictly increasing; that is $n_1 < n_2 < \ldots$.

Example 01.1. Let $\{a_n\}$ be the sequence for which $a_n=1$ if $n$ is odd and $a_n=n$ if $n$ is even. Then $\{a_{2n}\}$ is the subsequence $a_2, a_4, a_6, \ldots$ whose terms are $2, 4, 6, \ldots$; and the subsequence $\{a_{2n+1}\}$ is the subsequence $a_1, a_3, a_5, \ldots$ whose terms are $1, 1, 1, \ldots$.

In terms of the definition of a sequence as a map from $\mathbb{N}$ into a set, note that if $f : \mathbb{N} \to X$ is a sequence and $\phi : \mathbb{N} \to \mathbb{N}$ is a strictly increasing function (ie $\phi(m) < \phi(n)$ for all $m < n$ in $\mathbb{N}$), then $(f \circ \phi)(n) = f(\phi(n)) = x_{\phi(n)}$. Conversely, if $\{x_{n_k}\}$ is a subsequence of the sequence $\{x_n\}$, then there is a function $\phi : \mathbb{N} \to \mathbb{N}$ which is strictly increasing, such that $x_{n_k} = x_{\phi(k)}$ for each $k \in \mathbb{N}$.

An observation which will be useful later is that if $n_1 < n_2 < \ldots$ is a sequence of natural numbers which is strictly increasing, then given any natural number $N$, there exists $k \in \mathbb{N}$ such that $n_\ell > N$ for each $\ell \geq k$.

Definition 01.3. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$, and let $p \in X$. We say the sequence converges to $p$ if for every $\varepsilon > 0$ there exists a natural number $n_0$ such that $d(x_n, a) < \varepsilon$ whenever $n \geq n_0$. In this case we say $p$ is the limit of the sequence. We use the notation $x_n \to p$ or $\lim\limits_{n \to \infty} x_n = p$ or $\lim\limits_{n} x_n = p$ to indicate that the sequence $\{x_n\}$ converges to $p$.

Note that if we say a sequence in a metric space converges, we mean there is a point $p$ in the metric space such that $x_n \to p$.

Example 01.2. Let $\{x_n\}$ be the sequence given by $x_n=\frac{1}{n}$ for each $n\in\mathbb{N}$ in $\mathbb{R}$ with the usual metric. One checks easily that $x_n\to0$. So the sequence converges in $\mathbb{R}$ with limit 0. Now let $(X,d)$ denote the set $\mathbb{R}\backslash\{0\}$ with the usual metric, and let $x_n=\frac{1}{n}$ as before. In this case the sequence does not converge in $(X,d)$ because there is no point of $X$ which is the limit of the sequence.

Theorem 01.4. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$ and suppose $p,q \in X$ are such that $x_n \to p$ and $x_n \to q$. Then $p = q$.





Proof. If not, then $d(p,q) > 0$. Let $r = d(p,q)$. Since $x_n \to p$ and $\frac{r}{2} > 0$, there exists $n_0 \in \mathbb{N}$ such that $d(x_n,p) < \frac{r}{2}$ whenever $n \geq n_0$. Similarly, since $x_n \to q$, there exists $n_1 \in \mathbb{N}$ such that $d(x_n,q) < \frac{r}{2}$ whenever $n \geq n_1$. Now let $k = \max\{n_0, n_1\}$. Then $k \geq n_0$ and $k \geq n_1$. Thus

$$
\begin{array}{rlr} { r = d ( p , q ) } & { \leq } & { d ( p , x _ { k } ) + d ( x _ { k } , q ) } \\& { < } & { \frac { r } { 2 } + \frac { r } { 2 } } \\& { = } & { r } \end{array}
$$

We therefore have $r < r$; which is absurd.

This theorem tells us that in a metric space a sequence cannot converge to more than one point. In other words, limits are unique. That is why in fact in Example 01.2 we could say with certainty that there is no point $p$ in $\mathbb{R}\backslash\{0\}$ such that the sequence given there converges to $p$. If there were such a point then this point $p$ would be different from 0, and as we are using the same metric in $\mathbb{R}\backslash\{0\}$ as in $\mathbb{R}$ we would then have had $x_n \to 0$ and $x_n \to p$ in $\mathbb{R}$, contradicting Theorem 01.4.

Given a set $A \subseteq X$ and a sequence $\{x_n\}$ in $X$, we say $\{x_n\}$ is eventually in $A$ if there is a natural number $n_0$ such that for all $n \geq n_0$ we have $x_n \in A$. By a tail of a sequence $\{x_n\}$ we mean a set of the form $\{x_n \mid n \geq n_0\}$ for some $n_0 \in \mathbb{N}$. For instance each of the sets $\{x_{31}, x_{32}, x_{33}, \ldots\}, \{x_{98}, x_{99}, x_{100}, \ldots\}$ is a tail of the sequence $\{x_n\}$. Note that terms of a subsequence do not necessarily form a tail of a sequence because starting from $x_{n_1}$ to $x_{n_2}$ to $x_{n_3}$, etc. some terms of the sequence may have been left out. A tail starts with $x_{n_0}$ and includes all terms thereafter. Thus, a sequence $\{x_n\}$ is eventually in $A$ if and only if $A$ contains a tail of the sequence.

We now characterise convergence in terms of neighbourhoods.

Theorem 01.5. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$. Then $x_n \rightarrow p$ if and only if for every $n$b $U$ of $p$, $\{x_n\}$ is eventually in $U$. Put differently; a sequence converges to $p$ if and only if every $n$b of $p$ contains a tail of the sequence.

Proof. (⇒) Let $x_n \to p$ and $U$ be a nbd of $p$. Then there exists $\varepsilon > 0$ such that $B(p,\varepsilon) \subseteq U$. Since $x_n \to p$, we can find $n_0 \in \mathbb{N}$ such that $d(x_n,p) < \varepsilon$ for all $n \geq n_0$. This means that $x_n \in B(p;\varepsilon) \subseteq U$ for every $n \geq n_0$. Thus $\{x_n\}$ is eventually in $U$.

$(\Leftarrow)$ We want to show that $x_{n} \rightarrow p$. So let $\varepsilon > 0$. Then $B(p, \varepsilon)$ is a nbd of $p$; therefore $\{x_{n}\}$ is eventually in $B(p, \varepsilon)$. But this means that there is a natural number $n_{0}$ such





that if $n \geq n_0$ then $x_n \in B(p,\varepsilon)$; that is, such that $d(x_n,p) < \varepsilon$ whenever $n \geq n_0$. So $x_n \to p$. $\square$

Theorem 01.6. Let $(X,d)$ be a metric space and $A$ be a nonempty subset of $X$. For any $p \in X$, $p \in \overline{A}$ if and only if there is a sequence $\{x_n\}$ whose terms are points of $A$ such that $x_n \to p$.

Proof. (⇒) Let $p \in \overline{A}$. By Theorem 03.7, every ndb of $p$ contains a point of $A$. For each $n \in \mathbb{N}$ choose a point $x_n$ in $A$ such that $x_n \in B(p, \frac{1}{n})$; ie such that $d(x_n, p) < \frac{1}{n}$. Given any $\varepsilon > 0$, there exist $n_0 \in \mathbb{N}$ such that $n_0 > \frac{1}{\varepsilon}$. Now if $n \geq n_0$, then $d(x_n, p) < \frac{1}{n} \leq \frac{1}{n_0} < \varepsilon$. Thus $x_n \to p$.

(⇐) If $x_{n} \rightarrow p$ where each $x_{n}$ is in $A$; then every ndb of $p$ contains a tail of $\{x_{n}\}$. Thus it contains a point of $A$ and therefore $p \in \overline{A}$. $\square$

We note that it is possible for a sequence which does not converge to have a subsequence that converges. For instance the sequence $1, \frac{1}{2}, 1, \frac{1}{3}, 1, \ldots$ does not converge in $\mathbb{R}$ but each of the subsequences $1, 1, 1, \ldots$ and $\frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \ldots$ converges. The limits of subsequences of a sequence $\{x_n\}$ are called the subsequential limits of $\{x_n\}$. These form a closed set as we will show below. First we prove that if a sequence converges then so does each of its subsequences. Furthermore, if $x_n \rightarrow p$, then each subsequence of $\{x_n\}$ converges to $p$.

Theorem 01.7. A sequence $\{x_n\}$ in a metric space $(X,d)$ converges to $p$ if and only if every subsequence of $\{x_n\}$ converges to $p$.

Proof. (⇐) If every subsequence of $\{x_n\}$ converges to $p$, then $\{x_n\}$ converges to $p$ because every sequence is a subsequence of itself.

(⇒) Let $x_{n} \rightarrow p$ and $\{x_{n_{k}}\}$ be a subsequence of $\{x_{n}\}$. Given $\varepsilon > 0$, find $m \in \mathbb{N}$ such that $d(x_{n}, p) < \varepsilon$ whenever $n \geq m$. Choose $\ell \in \mathbb{N}$ such that $n_{\ell} \geq m$. Then for $k \geq \ell$ we have $n_{k} \geq n_{\ell} \geq m$, and therefore $d(x_{n_{k}}, p) < \varepsilon$. Thus $x_{n_{k}} \rightarrow p$ as $k \rightarrow \infty$. $\square$

Theorem 01.8. The subsequential limits of any sequence in a metric space form a closed set.

Proof. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$ and $E$ be the set of all subsequential limits of $\{x_n\}$. Let $q$ be an accumulation point of $E$. The idea of the proof is to construct a subsequence of $\{x_n\}$ which converges to $q$. So choose $n_1 \in \mathbb{N}$ such that $x_{n_1} \neq q$. (If there is no such $n_1$, then $x_n \rightarrow q$ and therefore, by Theorem 01.7, $E = \{q\}$ which is a





closed set; and hence there is nothing to prove). Put $\delta = d(x_{n_1}, q)$. Then $\delta > 0$. Since $q$ is an accumulation point of $E$, there exists $x \in E$ such that $d(x, q) < \frac{1}{2^2}\delta$. Likewise, since $x \in E$, there exists $n_2 > n_1$ such that $d(x, x_{n_2}) < \frac{1}{2^2}\delta$. Thus

$$
d ( q , x _ { n _ { 2 } } ) \leq d ( q , x ) + d ( x , x _ { n _ { 2 } } ) < \frac { 1 } { 2 } \delta .
$$

Continuing, by induction, suppose $n_1 > n_2 > \ldots > n_{k-1}$ have been chosen as above. Choose $n_k > n_{k-1}$ such that $d(q, x_{n_k}) < 2^{1-k}\delta$. We thus obtain a subsequence $\{x_{n_k}\}$ which converges to $q$. Therefore $q \in E$, and hence $E$ is closed. $\square$

Definition 01.9. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$. A point $y$ of $X$ is a cluster point of $\{x_n\}$ if for every $\varepsilon > 0$ and every $n \in \mathbb{N}$, there exists $m > n$ such that $d(x_m, y) < \varepsilon$.

Note that there is a difference between a cluster point and a limit of a sequence. If $y$ is a cluster point, then given any $\varepsilon > 0$ and any index $k$, we can find an index $\ell > k$ such that $d(x_\ell, y) < \varepsilon$. In the case of $y$ being a limit, given $\varepsilon > 0$ we can find an index $k$ so that for all indices $\ell > k$, $d(x_\ell, y) < \varepsilon$.

Quite clearly, a limit of a sequence is a cluster point, but not conversely. The next result shows that $y$ is a cluster point of $\{x_n\}$ if and only if some subsequence of $\{x_n\}$ converges to $y$. In consequence, "cluster point" is another name for "subsequential limit".

Theorem 01.10. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$. Then a point $y$ of $X$ is a cluster point of $\{x_n\}$ if and only if some subsequence of $\{x_n\}$ converges to $y$.

Proof. (⇒) Let $y$ be a cluster point of $\{x_n\}$. Choose an index $n_1$ such that $d(x_{n_1},y) < 1$. Now suppose indices $n_1 > n_2 > \ldots > n_k$ have been chosen such that $d(x_{n_i},y) < \frac{1}{i}$ for $i = 1,2,\ldots,k$. Then choose an index $n_{k+1} > n_k$ such that $d(x_{n_{k+1}},y) < \frac{1}{k+1}$. We thus have a subsequence $\{x_{n_k}\}$ with $d(x_{n_k},y) < \frac{1}{k}$ for each $k \in \mathbb{N}$. Therefore $\lim_{\frac{1}{\ell}} x_{n_k} = y$.

# $(\Leftarrow)$ Exercise.

Activity 01.1. (a) Let $\{x_n\}$ be a sequence in a metric space $(X,d)$ which converges to $p$. Put $S=\{x_n \mid n \in \mathbb{N}\}$.





Show that

(i) $S$ is a bounded subset of $X$,

(ii) $p$ is an adherent point of $S$.

(b) Let $\{a_{n}\}$ be a sequence of complex numbers, and let $p$ be a complex number. Show that $\lim _{n} a_{n}=p$ if and only if $\lim _{n} Re(a_{n})=Re(p)$ and $\lim _{n} Im(a_{n}=Im(p)$, where $Re(z)$ and $Im(z)$ respectively, denote the real part and the imaginary part of $z$.

(c) Let $\{a_{n}\}$ be a sequence in a metric space $(X, d)$. Show that $a_{n} \rightarrow a \Leftrightarrow \lim _{n} d(a_{n}, a)=0$.

Now that you have mastered this section, we move on to Cauchy sequences and completeness.

# 02 CAUCHY SEQUENCES AND COMPLETENESS

When dealing with sequences it is sometimes helpful to be able to determine that a sequence converges without knowing the point it converges to. In this section we discuss, among other things, a necessary condition for a sequence in a metric space to converge.

Definition 02.1. A sequence $\{x_n\}$ in a metric space $(X,d)$ is called a Cauchy sequence if for every $\varepsilon > 0$ there exists a natural number $n_0$ such that if $m,n \geq n_0$ then $d(x_m,x_n) < \varepsilon$.

Theorem 02.2. Every convergent sequence is a Cauchy sequence.

Proof. Let $\{x_n\}$ be a convergent sequence in a metric space $(X,d)$. Put $p=\lim x_n$. Let $\varepsilon>0$. Since $x_n\to p$ and $\frac{\varepsilon}{2}>0$, there exists an index $n_0$ such that $d(x_k,p)<\frac{\varepsilon}{2}$ whenever $k\geq n_0$. Now for any $m,n\geq n_0$ we have

$$
d ( x _ { m } , x _ { n } ) \leq d ( x _ { m } , p ) + d ( p , x _ { n } ) < \frac { \varepsilon } { 2 } + \frac { \varepsilon } { 2 } = \varepsilon .
$$

The converse of the above result does not hold. That is, there are Cauchy sequences which do not converge.





Example 02.1. Let $X$ be $\mathbb{R}\backslash\{0\}$ with the usual metric. Put $x_n=\frac{1}{n}$ for $n=1,2,\ldots$. Then $\{x_n\}$ is a Cauchy sequence. Indeed, given $\varepsilon>0$, choose $n_0\in\mathbb{N}$ so that $\frac{1}{n_0}<\frac{\varepsilon}{2}$. Then for $m,n\geq n_0$ we have $d(x_m,x_n)=|\frac{1}{m}-\frac{1}{n}|=\frac{1}{m}+\frac{1}{n}<\varepsilon$. The sequence however does not converge in $X$.

There are however metric spaces in which all Cauchy sequences converge.

Definition 02.3. A metric space $(X,d)$ is said to be complete if every Cauchy sequence in $X$ converges to a point of $X$.

Note that "to a point of $X$" in the above definition is a tautology because when we say a sequence converges in a metric space we mean it converges to a point in the space. Complete metric spaces abound as we shall see. Let us agree to say a sequence $\{x_n\}$ is bounded to mean the set $\{x_n \mid n \in \mathbb{N}\}$ of its terms is bounded. Then we have the following result.

Theorem 02.4. Every Cauchy sequence is bounded.

Proof. Let $\{x_n\}$ be a Cauchy sequence in a metric space $(X,d)$. Choose $n_0 \in \mathbb{N}$ such that $d(x_n, x_m) < 1$ for all $m, n \geq n_0$. Thus for $n \geq n_0$ we have $d(x_n, x_{n_0}) < 1$. Put

$$
r = \operatorname* { m a x } \{ d ( x _ { 1 } , x _ { n _ { 0 } } ) , \ldots , d ( x _ { n _ { 0 } - 1 } , x _ { n _ { 0 } } ) \} .
$$

One checks easily that the ball $B(x_{n_0}, r+1)$ contains all the terms of the sequence. So the set $\{x_n \mid n \in \mathbb{N}\}$ is bounded, as required. $\square$

We saw in the previous section that it is possible for a sequence which does not converge to have a convergent subsequence. This phenomenon is not possible with Cauchy sequences.

Theorem 02.5. If a Cauchy sequence has a convergent subsequence then it is itself convergent to the limit of that subsequence.

Proof. Let $\{x_n\}$ be a Cauchy sequence in a metric space $(X,d)$ and let $\{x_{n_k}\}$ be a subsequence of $\{x_n\}$ with $\lim\limits_{k}x_{n_k}=p$, say. Given $\varepsilon>0$ find $n_0\in\mathbb{N}$ such that $d(x_n,x_m)<\frac{\varepsilon}{2}$ whenever $m,n\geq n_0$. Since $x_{n_k}\to p$, we can find $\ell\in\mathbb{N}$ such that $n_\ell>n_0$ and $d(x_{n_\ell},p)<\frac{\varepsilon}{2}$. Then if $n\geq n_0$ we have

$$
d ( x _ { n } , p ) \leq d ( x _ { n } , x _ { n \ell } ) + d ( x _ { n \ell } , p ) < \varepsilon .
$$





Theorem 02.6. Let $\{x_n\}$ be a Cauchy sequence in a metric space $(X,d)$. If the range of the sequence, ie $\{x_n \mid n \in \mathbb{N}\}$, is finite, then $\{x_n\}$ converges.

Proof. Since $\{x_n \mid n \in \mathbb{N}\}$ is finite, there is $x \in X$ such that $x_n = x$ for infinitely many $n \in \mathbb{N}$. If $x$ is the only member of the range, then clearly $x_n \to x$. If the range has other elements, put $\delta = \min\{d(a,b) \mid a \text{ and } b \text{ are in the range of } \{x_n\} \text{ and } a \neq b\}$. Then $\delta > 0$ because it is the minimum of a finite set of positive real numbers. Since $\{x_n\}$ is a Cauchy sequence, there is an index $n_0$ such that $d(x_n, x_m) < \delta$ whenever $m, n \geq n_0$. As $x_n$ and $x_{n_0}$ are in the range of $\{x_n\}$ and $d(x_n, x_{n_0}) < \delta$, we deduce that $x_n = x_{n_0}$ for all $n \geq n_0$. But $x_k = x$ for infinitely many integers $k$; so it follows that $x_m = x$ for all $m \geq n_0$. Thus $x_n \to x$. $\square$

Theorem 02.7. The Euclidean space $\mathbb{R}^m$ is complete for each $m \in \mathbb{N}$. Also, $\mathbb{C}$ with the usual metric is complete.

Proof. Let $\{x_n\}$ be a Cauchy sequence in $\mathbb{R}^m$ and let $S = \{x_n \mid n \in \mathbb{N}\}$ be its range. If $S$ is finite then by Theorem 02.6 we have that $\{x_n\}$ converges. If $S$ is infinite, then, by Theorem 02.4, $S$ is a bounded infinite subset of $\mathbb{R}^m$. So by the Weierstrass-Bolzano Theorem we have that $S$ has an accumulation point, say $p$. But clearly $p$ is then a cluster point of the sequence $\{x_n\}$. Thus, by Theorem 01.10, $\{x_n\}$ has a subsequence that converges to $p$. So by Theorem 02.5 it follows that $x_n \to p$. We leave it as an exercise to show that $\mathbb{C}$ is complete using the fact that $\mathbb{R}$ is complete. $\square$

We saw in Example 02.1 that $\mathbb{R}\backslash\{0\}$, although being a subspace of the complete metric space $\mathbb{R}$, is not complete. In the next result we state a theorem which tells us precisely when a subspace of a complete metric space is complete. First some terminology.

Definition 02.8. Let $(X,d)$ be a metric space and $S$ be a subset of $X$. We say $S$ is complete if the metric space $(S,d_S)$ is complete.

Thus a subset $S$ of a metric space $(X,d)$ is complete if and only if whenever $\{a_n\}$ is a Cauchy sequence of points in $S$, then there exists $p \in S$ such that $a_n \to p$.

Theorem 02.9. Let $(X,d)$ be a complete metric space and $A \subseteq X$. Then $A$ is complete if and only if $A$ is closed.

Proof. (⇒) Let $p \in \overline{A}$. We must show that $p \in A$. By Theorem 01.6 there is a sequence $\{x_n\}$ in $X$ whose terms are points of $A$ and such that $x_n \rightarrow p$. But then $\{x_n\}$ is a Cauchy sequence with terms in $A$. So by the hypothesis there exists $q \in A$ such that $x_n \rightarrow_A q$,





where $\rightarrow_{A}$ means convergence in $(A,d_{A})$. But clearly $x_{n}\rightarrow_{A}q$ implies $x_{n}\rightarrow q$, where the latter convergence is in $(X,d)$. Now the uniqueness of limits (Theorem 01.4) yields $p=q$. So $p\in A$.

(⇐) Let $\{x_{n}\}$ be a Cauchy sequence in $(A,d_{A})$. Then $\{x_{n}\}$ is a Cauchy sequence in $(X,d)$ and therefore converges in $X$. Thus there is a point $p\in X$ such that $x_{n}\to p$. By Theorem 01.6 we have that $p\in\overline{A}$. But $A$ is closed, so $A=\overline{A}$. Therefore $\{x_{n}\}$ converges in $(A,d_{A})$. So $A$ is complete. $\square$

Theorem 02.10. A metric space $(X,d)$ is complete if and only if for every decreasing sequence $F_1 \supseteq F_2 \supseteq \ldots$ of nonempty closed subsets of $X$ with $\lim\limits_{n} \text{diam}(F_n) = 0$, the intersection $\bigcap\limits_{n=1}^{\infty} F_n$ is nonempty.

Proof. (⇒) Let $(X,d)$ be a complete metric space and $\{F_n\}$ be a sequence of closed subsets of $X$ such that

$$
F _ { n + 1 } \subseteq F _ { n } { \mathrm { ~ f o r ~ e a c h ~ } } n { \mathrm { ~ a n d ~ } } \operatorname* { l i m } _ { n } { \mathrm { d i a m } } ( F _ { n } ) = 0 .
$$

For each $n \in \mathbb{N}$ choose a point $x_n \in F_n$. The sequence $\{x_n\}$ of these points is a Cauchy sequence for if $\varepsilon > 0$ is given, then choosing $n_0 \in \mathbb{N}$ such that $\text{diam}(F_{n_0}) < \varepsilon$ we obtain the following: For $n, m \geq n_0$, $x_n$ and $x_m$ are in $F_{n_0}$ since $F_{k+1} \supseteq F_k$ for every $k$. Thus $d(x_n, x_m) \leq \text{diam}(F_{n_0}) < \varepsilon$. Since $(X, d)$ is complete there is a point $p \in X$ such that $x_n \to p$. For each $k \in \mathbb{N}$ the sequence $x_k, x_{k+1}, \ldots$ is a sequence of points of $F_k$ which converges to $p$. Thus $p \in \overline{F}_k = F_k$ since $F_k$ is closed. So $p \in \bigcap_{n=1}^{\infty} F_n$.

(⇐) Let $(X,d)$ be a metric space which satisfies the stated condition. Let $\{x_n\}$ be a Cauchy sequence in $(X,d)$. For each $n \in \mathbb{N}$ put $F_n = \{\overline{x_n}, x_{n+1}, \ldots\}$. Then each $F_n$ is closed, $F_{n+1} \subseteq F_n$ for each $n$ and $\text{diam}(F_n) \to 0$ as $n \to \infty$ (verify each of these assertions, recalling Theorem 04.5, among other results). Thus there is a point $x \in \bigcap_{n+1}^{\infty} F_n$. Check that $x = \lim\limits_{n} x_n$. $\square$

Remark 02.1. Note that, with regard to the above result, $\bigcap_{n=1}^{\infty} F_{n}$ actually contains one point. Indeed if $x \neq y$ were both in the intersection then we could not have $\operatorname{diam}(F_{n}) \rightarrow 0$.

An important property of complete metric spaces is that countable unions of nowhere dense sets have empty interiors. This property is often formulated in a different but equivalent form and is known as the Baire Category Theorem.





Theorem 02.11. (Baire Category Theorem) Let $\{G_n \mid n \in \mathbb{N}\}$ be a collection of dense open subsets of a complete metric space $(X,d)$. Then $\bigcap_{n=1}^{\infty} G_n$ is also dense.

Proof. Put $H=\bigcap_{n=1}^{\infty}G_{n}$. By Theorem 03.17 it suffices to show that $H$ intersects every nonempty open set. So let $x\in X$ and $r>0$. Since $G_{1}$ is dense there exists $y_{1}\in B(x,r)\cap G_{1}$. Because $G_{1}$ is open there exists a real number $\delta$ with $0<\delta<1$ such that

$$
y _ { 1 } \in B ( y _ { 1 } , \delta ) \subseteq G _ { 1 } \cap B ( x , r ) .
$$

Put $r_{1}=\frac{\delta}{2}$ and note that $0<r_{1}<1$ and

$$
\overline { { B ( y _ { 1 } , r _ { 1 } ) } } \subseteq \{ z \in X \mid d ( z , y _ { 1 } ) \leq r _ { 1 } \} \subseteq G _ { 1 } \cap B ( x , r ) .
$$

Now use the same argument, with $B(x,r)$ replaced by $B(y_1,r_1)$, to get a point $y_2$ in $G_2 \cap B(y_1,r_1)$ and a real number $r_2$ such that $0 < r_2 < \frac{1}{2}$ and

$$
\overline { { B ( y _ { 2 } , r _ { 2 } ) } } \subseteq G _ { 2 } \cap B ( y _ { 2 } r _ { 1 } ) .
$$

Proceeding this way we obtain a sequence of point $y_1, y_2 \ldots$ of $X$, and a sequence of positive real numbers $r_1, r_2, \ldots$ such that $0 < r_n < \frac{1}{n}$ and

$$
\overline { { B ( y _ { n + 1 } , r _ { n + 1 } ) } } \subseteq G _ { n + 1 } \cap B ( y _ { n } , r _ { n } ) { \mathrm { ~ f o r ~ e a c h ~ } } n \geq 1 .
$$

We claim that $\{y_n\}$ is a Cauchy sequence. To see this let $\varepsilon > 0$ be given and choose $n_0 \in \mathbb{N}$ such that $\frac{1}{n_0} < \varepsilon$. If $m, n \geq n_0$ (say $m \geq n$), then $B(y_m, r_m) \subseteq B(y_n, r_n)$ and so $y_m \in B(y_n, r_n)$ which implies that

$$
d ( y _ { m } , y _ { n } ) < r _ { n } < \frac { 1 } { n } \leq \frac { 1 } { n _ { 0 } } < \varepsilon .
$$

Since $(X,d)$ is complete, there exists $y \in X$ such that $y_n \to y$. Next we show that $y$ belongs to all the sets $G_1, G_2, \ldots$, which will complete the proof. Let $k \in \mathbb{N}$. For any integer $m \geq k$ we have $y_m \in B(y_k, r_k)$. So the sequence $y_k, y_{k+1}, \ldots$ is a sequence in $B(y_k, r_k)$ that converges to $y$. Thus, by Theorem 01.6, $y \in \overline{B(y_k, r_k)} \subseteq G_k$. So $y \in \bigcap_{n=1}^{\infty} G_n$. $\square$

Remark 02.2. The Baire Category Theorem can be used to prove the rather startling fact that: There is a continuous function $f : [0,1] \to \mathbb{R}$ which is differentiable at no point of $[0,1]$.





Activity 02.1. (a) Let $\{a_n\}$ and $\{b_n\}$ be Cauchy sequences in a metric space $(X,d)$.

For each $n \in \mathbb{N}$ let $s_n = d(a_n, b_n)$. Show that $\{s_n\}$ converges. Hint: Use

$$
d ( a _ { n } , b _ { n } ) \leq d ( a _ { n } , a _ { m } ) + d ( a _ { m } , b _ { m } ) + d ( b _ { m } , b _ { n } )
$$

to show that $|s_{n}-s_{m}|$ is small for large $m$ and $n$.

(b) Let $(X,d)$ be any discrete metric space and let $\{x_n\}$ be a Cauchy sequence in $(X,d)$. Show that there exists $n_0 \in \mathbb{N}$ such that for each $n \geq n_0$, $x_n = x_{n_0}$. Deduce that every discrete metric space is complete.

(c) Let $\{a_{n}\}$ be a sequence of real numbers. Suppose that

$$
| a _ { n } | < 2 \; \; \mathrm { a n d } \; \; | a _ { n + 2 } - a _ { n + 1 } | \leq \frac { 1 } { 8 } | a _ { n + 1 } ^{2} - a _ { n } ^{2} | \; \; \mathrm { f o r ~ a l l } \; \; n \geq 1 .
$$

Prove that $\{a_{n}\}$ converges.

(d) Let $(X,d)$ be a metric space and $A$ be a dense subset of $X$ such that every sequence in $A$ has a limit in $X$. Prove that $(X,d)$ is complete.

(e) Let $(X,d)$ be a metric space. Define $\overline{d}: X \times X \rightarrow \mathbb{R}$ by $\overline{d}(x,y) = \min\{d(x,y), 1\}$. Show that:

(i) $\overline{d}$ is a metric on $X$, and

(ii) $(X,d)$ is complete if and only if $(X,\overline{d})$ is complete

(f) This exercise shows that if the condition $\lim_{n}diam(F_{n})=0$ is dropped in the statement of Theorem 02.10, then the result might be false. For each $n\in\mathbb{N}$ let $F_{n}=[n,\infty)$. Verify that

(i) Each $F_n$ is closed

(ii) $F_{n+1} \supseteq F_n$ for every $n \geq 1$

(iii) $\bigcap_{n=1}^{\infty} F_n = \emptyset$.

We now move on to look at sequences with terms in $\mathbb{R}$.





# 03 SEQUENCES WITH TERMS IN $\mathbb{R}$

Having seen above that $\mathbb{R}$ is complete, it is now possible to conclude that certain sequences converge even if one has no idea what the limit is. This is accomplished by showing a given sequence to be a Cauchy sequence.

Example 03.1. For each $n \in \mathbb{N}$ let $x_n = 1 - \frac{1}{2} + \frac{1}{3} - \ldots + \frac{(-1)^{n-1}}{n}$. We claim that $\{x_n\}$ converges. Of course you know from MAT2613 that $\{x_n\}$ converges because $x_n$ is the $n^{\text{th}}$ partial sum of an alternating series with terms approaching zero. Let us however use the Cauchy condition to establish this. Let $\varepsilon > 0$. Choose $n_0 \in \mathbb{N}$ such that $\frac{1}{n_0} < \varepsilon$. For $m, n \geq n_0$; say $m > n$, we have

$$
| x _ { m } - x _ { n } | = | \frac { 1 } { n + 1 } - \frac { 1 } { n + 2 } + \ldots \pm \frac { 1 } { m } | < \frac { 1 } { n } \ ( \mathrm { w h y } ? )
$$

So $\{x_{n}\}$ is a Cauchy sequence in the complete metric space $\mathbb{R}$, so $\{x_{n}\}$ converges.

Example 03.2. Let $a_n$ be a sequence of real numbers such that $|a_{n+2}-a_{n+1}| \leq \frac{1}{2}|a_{n+1}-a_n|$ for all $n \geq 1$. We show that $\{a_n\}$ converges by showing that it is a Cauchy sequence. For each $n \geq 1$ let $b_n = |a_{n+1}-a_n|$. Then $0 \leq b_{n+1} \leq b_n/2$ and so, by induction, $b_{n+1} \leq b_1/2^n$. So if $m > n$ we have

$$
a _ { m } - a _ { n } = \sum _ { k = n } ^{m - 1} ( a _ { k + 1 } - a _ { k } ) ;
$$

hence

$$
\begin{array}{rl} { | a _ { m } - a _ { n } | } & { \leq \sum _ { k = n } ^{m - 1} b _ { k } } \\& { \leq \ b _ { n } ( 1 + \frac { 1 } { 2 } + \ldots + \frac { 1 } { 2 ^{m - 1 - n} } ) } \\& { < \ 2 b _ { n } } \\& { \leq \ b _ { 1 } \frac { 1 } { 2 ^{n - 1} } } \end{array}
$$

Thus given $\varepsilon > 0$, we can find $n_0 \in \mathbb{N}$ such that if $m, n \geq n_0$ we have $|a_m - a_n| < \varepsilon$.

We now discuss the important notions of limit superior and limit inferior for a sequence of real numbers. By the extended real line we mean the set $\mathbb{R}^* = \mathbb{R} \cup \{-\infty, +\infty\}$, consisting of $\mathbb{R}$ and two symbols $-\infty$ and $+\infty$, satisfying the following properties:

ER1 : $-\infty < x < +\infty$ for all $x \in \mathbb{R}$.





ER2 : $x + (+\infty) = +\infty$ and $x + (-\infty) = -\infty$, for all $x \in \mathbb{R}$.

ER3 : $x - (+\infty) = -\infty$ and $x - (-\infty) = +\infty$, for all $x \in \mathbb{R}$.

ER4 : $x/(+\infty)=x/(-\infty)=0$, for all $x\in\mathbb{R}$.

ER5 : $x \cdot (+\infty) = +\infty$ and $x \cdot (-\infty) = -\infty$, for all $x \in \mathbb{R}$ with $x > 0$.

ER6 : $x \cdot (+\infty) = -\infty$ and $x \cdot (-\infty) = +\infty$, for all $x \in \mathbb{R}$ with $x < 0$.

ER7 : $(+\infty)+(+\infty)=(+\infty)\cdot(+\infty)=(+\infty)\cdot(+\infty)=(-\infty)\cdot(-\infty)=+\infty$, and $(-\infty)+(-\infty)=(+\infty)\cdot(-\infty)=-\infty$.

Note that we do not define

$$
0 \cdot ( \pm \infty ) , + \infty - ( + \infty ) , \frac { \pm \infty } { \pm \infty } , - \infty + ( + \infty ) .
$$

It should be emphasized that the principal reason for introducing the symbols $-\infty$ and $+\infty$ is one of convenience. For instance if a subset $A$ of $\mathbb{R}$ is not bounded above, we write $\sup A = +\infty$ when working within $\mathbb{R}^*$. Similarly, we write $\inf A = -\infty$ if $A$ is a subset of $\mathbb{R}$ which is not bounded below. In this way every nonempty subset of $\mathbb{R}$ has a $\sup$ and an $\inf$ in $\mathbb{R}^*$.

Definition 03.1. Let $\{a_n\}$ be a sequence of real numbers. We say $\{a_n\}$ diverges to $+\infty$, and write $a_n \to +\infty$ or $\lim_{n \to \infty} a_n = +\infty$ or simply $\lim_{n \to \infty} a_n = +\infty$, if for every real number $M > 0$ there exists $n_0 \in \mathbb{N}$ such that $a_n > M$ for all $n \geq n_0$. We say $\{a_n\}$ diverges to $-\infty$, and write $a_n \to -\infty$ or $\lim_{n \to \infty} a_n = -\infty$ or simply $\lim_{n \to \infty} a_n = -\infty$, if for every real number $M < 0$ there exists $n_0 \in \mathbb{N}$ such that $a_n < M$ for all $n \geq n_0$.

Activity 03.1. Show that $\lim_{n} a_{n} = -\infty \Leftrightarrow \lim_{n} (-a_{n}) = +\infty$.

Definition 03.2. Let $\{a_n\}$ be a sequence of real numbers. Let

$$
E = \{ x \in \mathbb { R } ^{*} \mid a _ { n _ { k } } \rightarrow x \; \; \mathrm { f o r } \; s o m e \; s u b s e q u e n c e \; \; \{ a _ { n _ { k } } \} \} .
$$

Note that $E$ contains all subsequential limits of $\{a_n\}$ and possibly $-\infty$ and $+\infty$. Then $\sup E$ (in $\mathbb{R}^*$) is called the limit superior of $\{a_n\}$, and $\inf E$ (in $\mathbb{R}^*$) is called the limit inferior of $\{a_n\}$. The limits superior and inferior of a sequence $\{a_n\}$ are respectively denoted by $\limsup_{n\to\infty}a_n$ and $\liminf_{n\to\infty}a_n$.

Example 03.3. Let $a_{n}=n$ for $n$ odd and $a_{n}=\frac{1}{n+1}$ for $n$ even. Let us compute $\limsup_{n\to\infty}a_{n}$ and $\liminf_{n\to\infty}a_{n}$. Writing out the terms of the sequence yields $1,\frac{1}{3},3,\frac{1}{5},5,\frac{1}{7},7,\frac{1}{9},\ldots$. So





$\{a_{n}\}$ has only two subsequences that "converge" in $\mathbb{R}^{*}$; namely, $\{a_{2n-1}\}$ and $\{a_{2n}\}$ with $a_{2n-1} \rightarrow +\infty$ and $a_{2n} \rightarrow 0$. Therefore $\limsup_{n \rightarrow \infty} a_{n} = +\infty$ and $\liminf_{n \rightarrow \infty} a_{n} = 0$.

In what follows we shall say a sequence is bounded above, bounded below, or bounded according to whether its range has the corresponding property. We leave the proof of the following theorem as an exercise.

Theorem 03.3. Let $\{a_n\}$ be a sequence of real numbers. Then

(a) $\limsup_{n\to\infty}a_n=+\infty\Leftrightarrow\{a_n\}$ is not bounded above.

(b) $\liminf_{n\to\infty}a_n=-\infty\Leftrightarrow\{a_n\}$ is not bounded below.

(c) $\liminf_{n\to\infty}a_n\leq\limsup_{n\to\infty}a_n$.

Let us note the following about sequences of real numbers. If $\{x_n\}$ is a sequence with a finite range, then there is an integer $k \in \mathbb{N}$ such that $x_n = x_k$ for infinitely many indices $n$. Convince yourself that this is true. It should be obvious though, for if the range is $\{x_{m_1}, \ldots, x_{m_p}\}$, say, and for each $m_i$ there were only finitely many integers $n$ with $x_n = x_{m_i}$, then for $n$ large enough we would have $x_n \notin \{x_{m_1}, \ldots, x_{m_p}\}$, a contradiction since $\{x_{m_1}, \ldots, x_{m_p}\}$ is the range of the sequence.

Thus if a sequence (in any metric space) has a finite range then it has a convergent subsequence. [Compare this with Theorem 02.6.] On the other hand, if $\{x_n\}$ is a bounded sequence of real numbers with an infinite range, then, by the Weierstrass-Bolzano Theorem, the sequence has a cluster point, and hence a convergent subsequence. This discussion actually proves that:

Theorem 03.4. Every bounded sequence of real numbers has both the limit superior and the limit inferior.

In fact, as will be apparent later, every sequence of real numbers (whether bounded or not), has both the limit superior and the limit inferior. We now give a characterisation of the limit superior. In the exercises you will give a similar characterisation for the limit inferior.

Theorem 03.5. Let $\{a_n\}$ be a sequence of real numbers which is bounded. Then $\limsup_{n\to\infty}a_n=\alpha$ (where $\alpha\in\mathbb{R}$) if and only if $\alpha$ satisfies the following properties:

(a) For every $\beta > \alpha$, $a_n < \beta$ for all but a finite number of integers $n$. (That is, $\exists n_0 \in N$ such that $n \geq n_0 \Rightarrow a_n < \beta$.)





(b) For every $\gamma < \alpha, a_n > \gamma$ for infinitely many integers $n$. (That is, $\forall m \in N$, $\exists n > m$ such that $a_n > \gamma$.)

Proof. (⇒) Let $E=\{x\in\mathbb{R}\mid a_{n_k}\to x\text{ for some subsequence }\{a_{n_k}\}\}$. Note that, since the sequence is bounded, all subsequential limits are real numbers. Let $s$ be an upper bound for the sequence; ie $a_n\leq s$ for every $n$. Now if (a) were false, then there would exist $\beta>\alpha$ such that $\beta\leq a_n\leq s$ for infinitely many integers $n$. But then by the discussion preceding Theorem 03.5 we would have that $\{a_n\}$ has a subsequential limit in the interval $[\beta,s]$. This would contradict the fact that $\limsup_{n\to\infty}a_n=\sup E\text{ since }\alpha<\beta$. So (a) is true. Next, if (b) were false then there would exist $\gamma<\alpha$ such that $a_n\leq\gamma$ for all but a finite number of integers $n$. The sequence would thus have no subsequential limit bigger than $\gamma$. Thus we would have $\alpha=\sup E\leq\gamma<\alpha$; an absurdity.

(⇐) It is clear from (a) that no number strictly bigger than $\alpha$ can be a subsequential limit of $\{a_n\}$. Therefore $\limsup_{n\to\infty}\alpha$. If we assume that $\limsup_{n\to\infty}<\alpha$, then a contradiction arises as follows: Say $\limsup_{n\to\infty}a_n=\beta$. Then let $r$ be such that $\beta<r<\alpha$. Now in the interval $[r,\alpha]$ there are terms $a_n$ for infinitely many integers $n$ by (b). So $\{a_n\}$ has a subsequential limit in $[r,\alpha]$; ie a subsequential limit $p$ with $\limsup_{n\to\infty}a_n<p$. This is impossible. $\square$

Theorem 03.6. Let $\{a_n\}$ be a sequence of real numbers and put $\limsup_{n\to\infty}a_n=\alpha$. Then there is a subsequence $\{a_{n_k}\}$ such that $a_{n_k}\to\alpha$.

Proof. If $\alpha=+\infty$ then $\{a_{n}\}$ is not bounded above; hence the result follows. If $\alpha=-\infty$ then $\{a_{n}\}$ has no subsequential limit. So, for any real number $M$, $a_{n}\geq M$ for at most a finite number of integers $n$. Thus there is a natural number $n_{0}$ such that $a_{n}<M$ for all $n\geq n_{0}$. So $a_{n}\rightarrow-\infty$.

If $\alpha \in \mathbb{R}$, then $\{a_n\}$ has at least one subsequential limit. Let $E$ be the set of all subsequential limits of $\{a_n\}$. Then $E$ is not empty. But by Theorem 01.8 we have that $E$ is closed, so that $E = \overline{E}$. One checks easily that for any subset $S$ of $\mathbb{R}$ which is bounded above, $\sup S \in \overline{S}$. So $\alpha \in E$, and we are done. $\square$

Theorem 03.7. Let $\{a_n\}$ be a sequence of real numbers. Then we have:

(a) $\liminf_{n\to\infty}=-\limsup_{n\to\infty}(-a_n)$

(b) $\{a_n\}$ converges if and only if $\limsup_{n\to\infty}a_n$ and $\liminf_{n\to\infty}a_n$ are both real numbers and are equal. In that case $\liminf_{n\to\infty}a_n=\liminf_{n\to\infty}a_n=\limsup_{n\to\infty}a_n$.

(c) $a_n\to+\infty$ if and only if $\liminf_{n\to\infty}a_n=\limsup_{n\to\infty}a_n=+\infty$.

(d) $a_n\to-\infty$ if and only if $\limsup_{n\to\infty}a_n=-\infty$.

(e)





Activity 03.2. (a) Formulate (and prove) a characterisation of $\liminf_{n\to\infty}a_n$ which is similar (actually dual) to that of $\limsup_{n\to\infty}a_n$ given in Theorem 03.6.

(b) Let $\{a_n\}$ and $\{b_n\}$ be sequences of real numbers. Suppose there exists $n_0\in\mathbb{N}$ such that $a_n\leq b_n$ for all $n\geq n_0$. Prove that $\liminf_{n\to\infty}a_n\leq\liminf_{n\to\infty}b_n$ and $\limsup_{n\to\infty}a_n\leq\limsup_{n\to\infty}b_n$.

(c) Let $\{a_n\}$ and $\{b_n\}$ be sequences of real numbers that are bounded below. Show that $\limsup_{n\to\infty}(a_n+b_n)\leq\limsup_{n\to\infty}a_n+\limsup_{n\to\infty}b_n$.

(d) Given a sequence $\{a_n\}$ of real numbers which is bounded above, let $u_n=\sup\{a_k\mid k\geq n\}$. Show that:

(i) $\{u_n\}$ is a decreasing sequence of real numbers.

(ii) $\limsup_{n\to\infty}a_n=\limsup_{n\to\infty}u_n$.

(e) Formulate (and prove) a result for $\liminf_{n\to\infty}a_n$ similar to that in (d).

(f) Find $\limsup_{n\to\infty}a_n$ and $\liminf_{n\to\infty}a_n$ if:

(i) $a_n=(-1)^n(1+\frac{1}{n})$,

(ii) $a_n=n^2\sin^2(\frac{n\pi}{2})$,

(iii) $\frac{n}{3}-[\frac{n}{3}]$,

where $[x]$ denotes the greatest integer $\leq x$.

We have come to the end of Learning Unit 3. Before moving on to Learning Unit 4 on Compactness, make sure that you are familiar with the concepts and are able to do the activities correctly.





# LEARNING UNIT 4

# COMPACTNESS

The outcome for this learning unit is;

Demonstrate the concept of a compact metric space.

# 01 COMPACT SETS

Let $(X,d)$ be a metric space and $A \subseteq X$. A collection $\mathcal{C}$ of subsets of $X$ is a $\text{cover}$ of $A$ if $A \subseteq \bigcup \mathcal{C}$. If $\mathcal{C}$ is a cover of $A$ we also say $\mathcal{C}$ covers $A$. Given a cover $\mathcal{C}$ of $A$, we say $\mathcal{D} \subseteq \mathcal{C}$ is a $\text{subcover}$ if $\mathcal{D}$ also covers $A$. An $\text{open}$ $\text{cover}$ of $A$ is a cover $\mathcal{C}$ such that each set in $\mathcal{C}$ is open (in $X$). A $\text{finite}$ $\text{subcover}$ of $\mathcal{C}$ is a subcover which consists of finitely many sets from $\mathcal{C}$.

Definition 01.1. Let $(X,d)$ be a metric space and $K \subseteq X$. We say $K$ is compact if every open cover of $K$ has a finite subcover.

Thus a set which is not compact is one which has an open cover that has no finite subcover.

Example 01.1. Consider $\mathbb{R}$ with the usual metric. The set $(0,1]$ is not compact. To prove this we must produce an open cover of $(0,1]$ which has no finite subcover. Let

$$
c = \left\{ \left( { \frac { 1 } { n } } , 2 \right) \mid n = 1 , 2 , \ldots \right\} .
$$

Then:

(i) $\mathcal{C}$ covers $(0,1]$. To see this let $x \in (0,1]$. Choose $m \in \mathbb{N}$ such that $m > \frac{1}{x}$. Then $\frac{1}{m} < x < 2$, which implies that

$$
x \in \left( \frac { 1 } { m } , 2 \right) \subseteq \bigcup _ { n = 1 } ^{\infty} \left( \frac { 1 } { n } , 2 \right) .
$$





(ii) $\mathcal{C}$ is an open cover since each set in $\mathcal{C}$ is open.

(iii) $\mathcal{C}$ has no finite subcover; for if it had then there would be finitely many natural numbers $n_1, n_2, \ldots, n_k$ such that

$$
( 0 , 1 ] \subseteq \left( \frac { 1 } { n _ { 1 } } , 2 \right) \cup \cdots \cup \left( \frac { 1 } { n _ { k } } , 2 \right) .
$$

Letting $m=\max\{n_{1},\ldots,n_{k}\}$ would yield $(0,1)\subseteq\left(\frac{1}{m},2\right)$, which is false as, for instance, $\frac{1}{m+1}$ is in $(0,1]$ but not in $\left(\frac{1}{m},2\right)$.

Example 01.2. $\mathbb{R}$ is not compact. The open cover $\{(-\infty,n) \mid n \in \mathbb{N}\}$ of $\mathbb{R}$ has no finite subcover.

Example 01.3. In any metric space every finite set is compact. Indeed, let $F$ be a finite subset of a metric space $(X,d)$ and let $\mathcal{C}$ be an open cover of $F$. Say $F=\{x_1,\ldots,x_k\}$. For each $i=1,\ldots,k$ choose $C_i\in\mathcal{C}$ such that $x_i\in C_i$. Then $F\subseteq C_1\cup\cdots\cup C_k$; so that $\{C_1,\ldots,C_k\}$ is a finite subcover.

Example 01.4. Let $(X,d)$ be a discrete metric space. A subset of $X$ is compact if and only if it is finite. The one implication follows from the foregoing example. Conversely, let $K \subseteq X$ be compact. Then $\mathcal{C} = \{\{x\} \mid x \in K\}$ is an open cover of $K$ since in a discrete metric space singletons are open. By compactness $\mathcal{C}$ has a finite subcover, ie there are points $x_1, \ldots, x_m$ such that $K \subseteq \{x_1\} \cup \cdots \cup \{x_m\} = \{x_1, \ldots, x_m\}$. So $K$ is finite.

Notice that we defined compactness for subsets of metric spaces. If $(X,d)$ is a metric space and $X$ (as a subset of $X$) is compact, we say $(X,d)$ is a compact metric space. Thus $(X,d)$ is compact if and only if every open cover of $X$ has a finite subcover. As we saw above, $\mathbb{R}$ is not a compact metric space.

Recall from Activity 02.1(a) that if $x$ and $y$ are distinct points in a metric space $(X,d)$, then there are disjoint open sets $U$ and $V$ such that $x \in U$ and $y \in V$. In fact, for $r = d(x,y) > 0$ the balls $B\left(x,\frac{r}{2}\right)$ and $B\left(y,\frac{r}{2}\right)$ are open and disjoint. So we can say: in a metric space, distinct points can be separated by open sets. We will show below that if $K$ is a compact set and $p$ a point not in $K$, then we can separate $p$ and $K$ by open sets. That is, we can find disjoint open sets $U$ and $V$ such that $p \in U$, $K \subseteq V$. From this result we will be able to deduce that compact sets are closed.

Theorem 01.2. Let $(X,d)$ be a metric space, $K \subseteq X$ be compact and $p \in X \backslash K$. Then there exist disjoint open sets $U$ and $V$ such that $K \subseteq U$ and $p \in V$.





Proof. For each $x \in K$, $x \neq p$. So choose (for each $x \in K$) disjoint open sets $U_x$ and $V_x$ such that $x \in U_x$ and $p \in V_x$. Then $\mathcal{C} = \{U_x \mid x \in K\}$ is an open cover of $K$. Since $K$ is compact there is a finite subcollection $\{U_x, U_x_2, \ldots, U_{x_m}\}$ of $\mathcal{C}$ which covers $K$. Since $U_{x_i} \cap V_{x_i} = \emptyset$ for each $i = 1, 2, \ldots, m$, we have that

$$
U = \bigcup _ { i = 1 } ^{m} U _ { x _ { i } } \; \; \mathrm { a n d } \; \; V = \bigcap _ { i = 1 } ^{m} V _ { x _ { i } }
$$

are disjoint open sets with $K \subseteq U$ and $p \in V$.

Theorem 01.3. Every compact subset of a metric space is closed and bounded.

Proof. Let $K$ be a compact subset of a metric space $(X,d)$. We first show that $K$ is closed. We do this by showing that $X\backslash K$ is open. So let $p\in X\backslash K$. By Theorem 01.2 find disjoint open sets $U$ and $V$ such that $K\subseteq V$ and $p\in U$. Since $U\cap V=\emptyset$, we have that $U\subseteq X\backslash V$. Since $K\subseteq V$, we have that $X\backslash V\subseteq X\backslash K$. Thus $U$ is an open set with $p\in U\subseteq X\backslash K$. This shows that every point of $X\backslash K$ is an interior point; so $X\backslash K$ is open and hence $K$ is closed.

Next, to prove that $K$ is bounded, let $p$ be any point in $K$. The balls $B(p,1), B(p,2), \ldots$ form an open cover of $K$, for if $x \in K$ and $m$ is a natural number with $m > d(p,x)$, then $x \in B(p,m)$. By compactness a finite number of these balls also cover $K$. So $K$ is contained in the one with the largest radius. $\square$

The converse of Theorem 01.3 does not hold. That is, if a subset of a metric space is closed and bounded, it does not follow that it is compact. Take for instance any infinite set with the discrete metric. In such a metric space all subsets are closed and bounded, but the compact ones are the finite ones as we saw above.

Theorem 01.4. Closed subsets of compact metric spaces are compact.

Proof. Let $K$ be a closed subset of a compact metric space $(X,d)$. Let $\mathcal{C}$ be an open cover of $K$. Since $K$ is closed, $X\backslash K$ is open. Since $X=K\cup(X\backslash K)$ and $K\subseteq\bigcup\mathcal{C}$, we have that $\mathcal{C}\cup\{X\backslash K\}$ is an open cover of $X$. Since $X$ is compact, there are finitely many sets $C_1, C_2, \ldots, C_m$ in $\mathcal{C}$ such that

$$
X = C _ { 1 } \cup C _ { 2 } \cup \cdots \cup C _ { m } \cup ( X \backslash K ) .
$$

Since $K \cap (X \backslash K) = \emptyset$, it follows that $K \subseteq C_1 \cup \cdots \cup C_m$.

Theorem 01.5. Let $K$ be a compact subset of a metric space $(X,d)$. Then every infinite subset of $K$ has an accumulation point in $K$.





Proof. Suppose, by way of contradiction, that $T$ is an infinite subset of $K$ and that no point of $K$ is an accumulation point of $T$. Then for each $x \in K$ there is a real number $r_x > 0$ such that the ball $B(x, r_x)$ does not contain a point of $T \backslash \{x\}$. Now $\{B(x, r_x) \mid x \in K\}$ is an open cover of $K$; so by compactness there are points $x_1, \ldots, x_m$ in $K$ such that

$$
K \subseteq B ( x _ { 1 } , r _ { x _ { 1 } } ) \cup \cdots \cup B ( x _ { m } , r _ { x _ { m } } ) .
$$

Thus, also

$$
T \subseteq B ( x _ { 1 } , r _ { x _ { 1 } } ) \cup \cdots \cup B ( x _ { m } , r _ { x _ { m } } ) ;
$$

so that

$$
T = \bigcup _ { i = 1 } ^{m} ( T \cap B ( x _ { i } , r _ { x _ { i } } ) ) \, .
$$

But each of the sets

$$
T \cap B ( x _ { 1 } , r _ { x _ { 1 } } ) , \ldots , T \cap B ( x _ { m } , r _ { x _ { m } } )
$$

is finite (in fact each $T \cap B(x_i, r_{x_i})$ is either empty – if $x_i \notin T$, or only $\{x_i\}$ – if $x_i \in T$); thus $T$ is finite, contradicting the fact that $T$ is infinite. $\square$

Theorem 01.6. Let $\mathcal{A}$ be a collection of compact subsets of a metric space $(X,d)$ such that the intersection of every finite subcollection of $\mathcal{A}$ is nonempty. Then $\bigcap_{\mathcal{A}} \mathcal{A}$ is nonempty.

Proof. Note first that each set in $\mathcal{A}$ is nonempty. Fix $C_0 \in \mathcal{A}$ and put $\mathcal{B} = \{X \setminus A \mid A \in \mathcal{A}\}$. Then each member of $\mathcal{B}$ is open since compact sets are closed. Now assume that no point of $C_0$ belongs to every member of $\mathcal{A}$. So for each $x \in C_0$, there exists $A \in \mathcal{A}$ such that $x \notin A$. Thus $x \in X \setminus A$. This shows that $\mathcal{B}$ covers $C_0$. Since $C_0$ is compact, there are finitely many sets $A_1, A_2, \ldots, A_m$ in $\mathcal{A}$ such that $C_0 \subseteq (X \setminus A_1) \cup \cdots \cup (X \setminus A_m)$. But

$$
( X \backslash A _ { 1 } ) \cup \cdots \cup ( X \backslash A _ { m } ) = X \backslash ( A _ { 1 } \cap \cdots \cap A _ { m } ) .
$$

So we have that $C_0 \cap A_1 \cap \cdots \cap A_m = \emptyset$, which contradicts the hypothesis that the intersection of any finitely many sets in $\mathcal{A}$ is nonempty. $\square$

Corollary 01.7. Let $K_1, K_2, \ldots$ be nonempty compact subsets of a metric space such that $K_1 \supseteq K_2 \supseteq \ldots$. Then $\bigcap_{n=1}^{\infty} K_n$ is nonempty.





Proof. This follows immediately from Theorem 01.6 because if $K_{n_1}, K_{n_2}, \ldots K_{n_p}$ are finitely many sets from the collection $\{K_n\}$, then $K_{n_1} \cap \cdots \cap K_{n_p} = K_m$ where $m = \max\{n_1, \ldots, n_p\}$ and of course $K_m \neq \emptyset$. $\square$

Remark 01.1. The foregoing result should be compared with that in Theorem 02.10.

Activity 01.1. (a) Show that the intersection of an arbitrary collection of compact sets is compact.

(b) Show that the union of a finite number of compact sets is compact.

(c) Let $(X,d)$ be a metric space and $S \subseteq M \subseteq X$. Show that $S$ is compact in $(X,d)$ if and only if it is compact in $(M,d_M)$.

(d) Show that if $K$ is compact and $C$ is closed, then $K \cap C$ is compact.

Characterisations will be examined next.

# 02 CHARACTERISATIONS OF COMPACTNESS

The main goal of this section is to give various characterisations of compactness. Some of these are, in certain instances, easier to use to determine compactness than the definition.

Let us note the following fact which we could also have raised when we were discussing countability. Let $A$ be an infinite set. We argue that $A$ contains a countably infinite subset. To construct such a set, let $x_1$ be any element of $A$. Then $A\backslash\{x_1\}$ is not empty, so we can choose $x_2 \in A\backslash\{x_1\}$. Thus $x_1 \neq x_2$. Now suppose elements $x_1, x_2, \ldots, x_k$ in $A$ which are mutually distinct have been chosen. Then since $A$ is infinite, $A\backslash\{x_1, x_2, \ldots, x_k\}$ is not empty. So we can choose an element $x_{k+1}$ in $A\backslash\{x_1, x_2, \ldots, x_k\}$. Thus, by induction, we have a countably infinite set $\{x_1, x_2, \ldots\} \subseteq A$.

The foregoing discussion also shows that in every infinite set there is a sequence whose range is infinite. We observed earlier that a point $p$ in a metric space is an accumulation point of a set $\{x_1, x_2, \ldots\}$ if and only if the sequence $\{x_n\}$ has a subsequence converging to $p$. To be sure, we did not express this explicitly, but it certainly follows from results pertaining accumulation points of sets and cluster points of sequences. Better yet: prove the claim.

Definition 02.1. Let $(X,d)$ be a metric space. We say:





(a) $(X,d)$ has the Bolzano-Weierstrass property if every infinite subset of $X$ has an accumulation point.

(b) $(X,d)$ is sequentially compact if every sequence in $X$ has a convergent subsequence.

We are going to show that each of the notions defined above is equivalent to compactness.

Theorem 02.2. A metric space is sequentially compact if and only if it has the Bolzano-Weierstrass property.

Proof. $(\Rightarrow)$ This follows from the discussion preceding Definition 02.1.

(⇐) Let $(X,d)$ be a metric space with the Bolzano-Weierstrass property. Let $\{x_n\}$ be a sequence in $X$. If the sequence has a term which is infinitely repeated, then it has a constant subsequence, and this subsequence clearly converges. If no term of the sequence is infinitely repeated, then the set $\{x_n \mid n=1,2,\ldots\}$ is infinite. So by the hypothesis this set has an accumulation point. This accumulation point is a subsequential limit of $\{x_n\}$. □

Note that, in the terminology of this section, Theorem 01.5 says that if $(X,d)$ is a compact metric space, then $(X,d)$ has the Bolzano-Weierstrass property.

An alert student will at this juncture have noticed what, at first glance, might appear to be a discrepancy between the discussion of compactness in Section 01 and that of sequential compactness defined above. In Section 01 we defined (and consistently spoke about) compactness of a subset of a metric space. Here we have defined subsequential compactness of a metric space. Keeping in mind that we are aiming to prove that these concepts are equivalent, and that (in view of Exercise 3.1.8(c)) a subset $S$ of a metric space $(X,d)$ is compact, as a subset of $(X,d)$, if and only if the metric space $(S,d_S)$ is compact, we see that in fact there is no discrepancy in the two discussions. However if you insist on pedantry, you can rewrite Section 02 along the lines of Section 01 by defining sequential compactness and the Bolzano-Weierstrass property for subsets of metric spaces as follows:

Definition 02.3. ' A subset $S$ of a metric space $(X,d)$ is said to:

(a) have the Bolzano-Weierstrass property if every infinite subset of $S$ has an accumulation point which is an element of $S$.

(b) be sequentially compact if every sequence in $(X,d)$ whose terms are elements of $S$ has a subsequence which converges to a point of $S$.





Now that we have "tied loose ends", let us continue with the task at hand; namely, that of proving that "compactness" $\Leftrightarrow$ "sequential compactness" $\Leftrightarrow$ "the Bolzano-Weierstrass property".

So far we have achieved the following:

(i) "sequential compactness" $\Leftrightarrow$ "having the Bolzano-Weierstrass property", and

(ii) "compactness" $\Rightarrow$ "sequential compactness".

We are thus left with showing that compactness is implied by sequential compactness. This we shall do in stages, introducing two important notions in the process; that of the Lebesgue number and that of total boundedness.

Definition 02.4. Let $\mathcal{C}$ be an open cover of a metric space $(X,d)$. A real number $\delta > 0$ is called a Lebesgue number for the cover if every subset of $X$ with diameter less that $\delta$ is contained in one of the open sets in $\mathcal{C}$. That is, for every $A \subseteq X$ with $\text{diam}(A) < \delta$, there exists $C \in \mathcal{C}$ such that $A \subseteq C$.

Theorem 02.5. Let $(X,d)$ be a sequentially compact metric space. Then every open cover of $X$ has a Lebesgue number.

Proof. Let $\mathcal{C}$ be an open cover of $X$. Let us call a subset of $X$ big if it is not contained in any of the sets in $\mathcal{C}$. Notice that if $X$ has no big subsets, then any $r > 0$ is a Lebesgue number for $\mathcal{C}$. So let us assume that $X$ has some big sets. Let

$$
\alpha = \operatorname* { i n f } \{ \operatorname { d i a m } ( B ) \mid B { \mathrm { ~ i s ~ a ~ b i g ~ s u b s e t ~ o f ~ } } X \} .
$$

Then clearly, $0 \leq \alpha \leq +\infty$. Note that if $\alpha = +\infty$, then each big subset of $X$ is unbounded. So for any real number $r > 0$, if $\text{diam}(S) < r$, then $S$ is bounded and hence not big. So $S$ is contained in some member of $\mathcal{C}$. Thus any $r > 0$ is a Lebesgue number for $\mathcal{C}$. So we investigate the case $0 \leq \alpha < +\infty$. If we can show that $\alpha > 0$, then a real number $r$ with $0 < r < \alpha$ will be a Lebesgue number for $\mathcal{C}$ because then any set with diameter less than $r$ is not big. We prove by contradiction that $\alpha > 0$. Suppose, by way of contradiction, that $\alpha = 0$. Since singletons have diameter $0$, we have that every big set has more than one element. Since $\alpha = 0$ we have that for each $n \in \mathbb{N}$, there is a big set $B_n$ such that $0 < \text{diam}(B_n) < \frac{1}{n}$. For each $n = 1, 2, \ldots$, choose a point $x_n \in B_n$. Since $(X, d)$ is sequentially compact, the sequence $\{x_n\}$ has a subsequence $\{x_{n_k}\}$ which converges to some point $x \in X$. Since $\mathcal{C}$ covers $X$, there exists a set $C \in \mathcal{C}$ such that $x \in C$. Since $C$ is open, there exists a real number $\varepsilon > 0$ such that $B(x, \varepsilon) \subseteq C$. Since $x_{n_k} \to x$, we can find $\ell \in \mathbb{N}$ such that $n_\ell > \frac{2}{\varepsilon}$ and such that if





$k\geq\ell$ then $d(x_{n_k},x)<\frac{\varepsilon}{2}$. Now $x_{n_\ell}\in B_{n_\ell}$ and $\text{diam}(B_{n_\ell})<\frac{1}{n_\ell}<\frac{\varepsilon}{2}$; so $B_{n_\ell}\subseteq B(x,\varepsilon)$, for if $z\in B_{n_\ell}$ then $d(z,x)\leq d(z,x_{n_\ell})+d(x_{n_\ell},x)<\frac{\varepsilon}{2}+\frac{\varepsilon}{2}$. But this now implies that $B_{n_\ell}\subseteq C$ since $B(x,\varepsilon)\subseteq C$; which contradicts the fact that $B_{n_\ell}$ is big. $\square$

Definition 02.6. A metric space $(X,d)$ is totally bounded if for every real number $r>0$, the cover $\{B(x,r)\mid x\in X\}$ always has a finite subcover.

What is the relationship between boundedness and total boundedness? We show that the latter implies the former; but not conversely.

Theorem 02.7. Every totally bounded metric space is bounded.

Proof. Let $(X,d)$ be a totally bounded metric space. Then the cover $\{B(x,1) \mid x \in X\}$ has a finite subcover, say, $B(x_1,1),\ldots,B(x_m,1)$. Let $r = \max\{d(x_i,x_j) \mid i,j=1,\ldots,m\}$. Let $x,y \in X$. Then $x \in B(x_i,1)$ and $y \in B(x_j,1)$ for some $i,j \in \{1,\ldots,m\}$. Therefore

$$
d ( x , y ) \leq d ( x , x _ { i } ) + d ( x _ { i } , x _ { j } ) + d ( x _ { j } , y ) < r + 2 .
$$

So $r+2$ is a real number such that $d(x,y) \leq r+2$ for all $x,y$ in $X$.

Example 02.1. Let $X$ be a set of real numbers with the metric $d(x,y)=\min\{|x-y|,1\}$. Then $(X,d)$ is bounded since $d(x,y)\leq 1$ for all $x,y\in X$. We show that the cover $\{B(x,\frac{1}{2})\mid x\in X\}$ has no finite subcover. For any finite set $F\subseteq X$, let $p$ be the largest element of $F$ (recall that $X=\mathbb{R}$). If $q\in F$, then $d(p+1,q)=1$, so that $p+1\notin\bigcup_{x\in F}B(x,\frac{1}{2})$. Hence $X$ is not totally bounded.

Theorem 02.8. Every sequentially compact metric space is totally bounded and complete.

Proof. Let $(X,d)$ be a sequentially compact metric space. To show completeness, let $\{x_n\}$ be a Cauchy sequence in $X$. By sequential compactness, $\{x_n\}$ has a convergent subsequence. Thus, by Theorem 02.5, $\{x_n\}$ converges. Next we show that $(X,d)$ is totally bounded. Suppose this were not the case. Then there is a real number $r>0$ such that the cover $\{B(x,r)\mid x\in X\}$ has no finite subcover. Let $x_1$ be any point of $X$. Since $X\nsubseteq B(x_1,r)$ there is a point $x_2\in X\backslash B(x_1,r)$. Also, $\{B(x_1,r),B(x_2,r)\}$ does not cover $X$, so there is a point $x_3\in X\backslash (B(x_1,r)\cup B(x_2,r))$. Continuing, by induction, we obtain a sequence $\{x_n\}$ in $X$ such that

$$
d ( x _ { i } , x _ { j } ) \geq r { \mathrm { ~ f o r ~ a l l ~ } } i \neq j .
$$

So $\{x_{n}\}$ cannot have a convergent subsequence; contrary to the hypothesis.

We have finally arrived at a stage where we can complete the loop.





Theorem 02.9. Every sequentially compact metric space is compact.

Proof. Let $(X,d)$ be a sequentially compact metric space and let $\mathcal{C}$ be an open cover of $X$. By Theorem 02.5, $\mathcal{C}$ has a Lebesgue number $\delta$. Put $\varepsilon=\frac{\delta}{3}$; and by Theorem 02.8 find points $x_1,x_2,\ldots,x_m$ in $X$ such that

$$
X = B ( x _ { 1 } , \varepsilon ) \cup \cdots \cup B ( x _ { m } , \varepsilon ) .
$$

Now, for each $k=1,2,\ldots,m$ we have $\text{diam}(B(x_k,\varepsilon))\leq 2\varepsilon<\delta$. So by the definition of a Lebesgue number, for each $k=1,\ldots,m$ there is a set $C_k\in\mathcal{C}$ such that $B(x_k,\varepsilon)\subseteq C_k$. Thus $\{C_1,C_2,\ldots,C_m\}$ is a finite subcover of $\mathcal{C}$. Hence $(X,d)$ is compact. $\square$

From Theorem 02.8 we deduce that every compact metric space is totally bounded and complete. The converse is also true.

Theorem 02.10. A metric space is compact if and only if it is totally bounded and complete.

Proof. The one implication has already been observed. We show the converse by proving that if $(X,d)$ is totally bounded and complete then it has the Bolzano-Weierstrass property. Of course if $X$ is a finite set there is nothing to prove. Let $A$ be an infinite subset of $X$. For each $n \in \mathbb{N}$ use total boundedness to find a finite set $F_n \subseteq X$ such that

$$
X = \bigcup _ { x \in F _ { n } } B \left( x , { \frac { 1 } { n } } \right) .
$$

Since $A$ is infinite and the finitely many balls $B(x,1)$ for $x \in F_1$ cover $A_1$, there is a point $x_1 \in F_1$, such that $A \cap B(x_1,1)$ is infinite. Next, since the finitely many balls $B\left(y,\frac{1}{2}\right)$ for $y \in F_2$ cover the infinite set $A \cap B(x_1,1)$, there is a point $x_2 \in F_2$ such that

$$
A \cap B ( x _ { 1 } , 1 ) \cap B \left( x _ { 2 } , \frac { 1 } { 2 } \right)
$$

is infinite. Inductively, we choose $x_n \in F_n$ for all $n \in \mathbb{N}$ such that $A \cap B(x_1,1) \cap \cdots \cap B\left(x_n, \frac{1}{n}\right)$ is infinite for each $n \in \mathbb{N}$. This implies that $d(x_m, x_n) < \frac{1}{m} + \frac{1}{n} < \frac{2}{n}$ for all $m, n \in \mathbb{N}$ with $m > n$ since there is a point $y \in B\left(x_m, \frac{1}{m}\right) \cap B\left(x_n, \frac{1}{n}\right)$. Therefore $\{x_n\}$ is a Cauchy sequence in $(X, d)$ and hence converges to some point $x \in X$. For each $n \in \mathbb{N}$ we have that $d(x_n, x) < \frac{2}{n}$; so

$$
B \left( x _ { n } , { \frac { 1 } { n } } \right) \subseteq B \left( x , { \frac { 3 } { n } } \right) .
$$





So $B\left(x,\frac{3}{n}\right)$ contains infinitely many points of $A$. Since $\frac{3}{n}\rightarrow0$ as $n\rightarrow\infty$, it follows that $x$ is an accumulation point of $A$. $\square$

We now introduce another kind of compactness which is also equivalent to compactness for metric space.

Definition 02.11. A metric space is countably compact if every countable cover has a finite subcover. A subset $S$ of a metric space is countably compact if it is countably compact as a subspace. That is, if every countable open cover of $S$ (by sets open in the containing metric space) has a finite subcover for $S$.

Theorem 02.12. A metric space is compact if and only if it is countably compact.

Proof. If every cover has a finite subcover, then every countable cover has a finite subcover. So compactness clearly implies countable compactness.

Conversely, let $(X,d)$ be a countably compact metric space. We show that $(X,d)$ has the Bolzano-Weierstrass property. Let $A$ be an infinite subset of $X$. Then $A$ contains a countably infinite subset $B=\{x_n\mid n=1,2,\ldots\}$. We may assume that $x_m\neq x_n$ for $m\neq n$. Suppose $B$ has no accumulation point. Then for each $n\in\mathbb{N}$, $C_n=\{x_i\mid i\geq n\}$ is a closed set (why?). For each $n\in\mathbb{N}$, put $D_n=X\backslash C_n$. Note that if $C_{n_1},\ldots,C_{n_k}$ are finitely many of the sets $C_n$, then $C_{n_1}\cap\cdots\cap C_{n_k}\neq\emptyset$ since this intersection is simply $C_m$ for $m=\max\{n_1,n_2,\ldots,n_k\}$. This means that we cannot find finitely many of the sets $D_n$ that cover $X$. So $\{D_n\mid n\in\mathbb{N}\}$ is not a cover of $X$, for if it were it would have a finite subcover. So there is a point $z$ in $X$ such that $z\notin D_n$ for each $n=1,2,\ldots$. Thus $z\in C_n$ for each $n=1,2,\ldots$. As $C_n\subseteq B$ for each $n$, this means that $z=x_k$ for some $k\in\mathbb{N}$. But $x_k\notin C_{k+1}$ since $C_{k+1}=\{x_{k+1},x_{k+2},\ldots\}$. We therefore have a contradiction. So the assumption that $B$ has no accumulation point is false; hence $B$ has an accumulation point. As $B\subseteq A$, it follows that $A$ also has an accumulation point. Therefore $(X,d)$ is compact. $\square$

Remark 02.1. In case you could not work out why each of the sets $C_n$ in the proof above is closed; here is the reason. If $B$ has no accumulation point, then $C_n$ (being a subset of $B$) also has no accumulation point. But we showed in Chapter 1 that a set which has no accumulation point is closed.

Now let us collect all the characterisations of compactness into a single theorem stated for arbitrary subsets of a metric space. All the concepts, but total boundedness, in question (namely: compactness, countable compactness, sequential compactness, having the Bolzano-Weierstrass property and completeness) have been defined for arbitrary subsets of metric spaces. In exactly the same way, if $S$ is a subset of a metric space $(X,d)$, we





say $S$ is totally bounded if the metric space $(S,d_S)$ is totally bounded. This is so if and only if for every $\varepsilon > 0$ there is a finite $T \subseteq X$ (yes, $T$ subset of $X$) such that for each $a \in S$ there exists $t \in T$ with $d(a,t) < \varepsilon$. You will prove this in the exercise below. Our characterisation theorem states that:

Theorem 02.13. Let $S$ be a subset of a metric space. Then the following statements are equivalent:

(a) $S$ is compact.

(b) $S$ is countably compact.

(c) $S$ is sequentially compact.

(d) $S$ has the Bolzano-Weierstrass property.

(e) $S$ is totally bounded and complete.

We have seen when we were studying completeness that the Euclidean space $\mathbb{R}^{m}$ ($m \in \mathbb{N}$) seems to have special properties which are not enjoyed by all metric space. It should therefore come as no surprise that there is a very transparent characterisation of compactness for subsets of $\mathbb{R}^{m}$. By "transparent" we mean "expressible in terms of basic properties".

Let us elaborate. It is no doubt easier to intuit or get a geometric feel of boundedness than that of total boundedness. In other words it is easier to determine boundedness than total boundedness. For instance we can tell immediately that the interval $(-3;22]$, as a subset of $\mathbb{R}$, is bounded. But is it totally bounded?

We showed that in any metric space total boundedness always implies boundedness, but not conversely. In the Euclidean space $\mathbb{R}^m$ it turns out that boundedness is equivalent to total boundedness. Now this is a very nice result because if we want to check whether a subset of $\mathbb{R}^m$ is compact or not we need to determine whether it is bounded and complete. But wait: is completeness of a subset of $\mathbb{R}^m$ easy to check? Indeed. Since $\mathbb{R}^m$ is complete (Theorem 02.7) we know that a subset of $\mathbb{R}^m$ is complete if and only if it is closed (Theorem 02.9). So to check compactness for subsets of $\mathbb{R}^m$ we need only check boundedness and closedness. Nothing could be easier.

Well, let us prove these assertions. Recall that a closed cell in $\mathbb{R}^m$ is a set of the form $I=[a_1,b_1]\times\ldots\times[a_m,b_m]$ where the $a_i$ and $b_i$ are real numbers with $a_i\leq b_i$ for all $i$. By a cube of edge $\ell$ ($\ell>0$) we mean a cell $I$ as above where $b_i-a_i=\ell$ for all $i=1,2,\ldots,m$. A cube in $\mathbb{R}$ is an interval, a cube in $\mathbb{R}^2$ of edge $\ell$ is simply a square with sides each of





length $\ell$. Now convince yourself that in $\mathbb{R}^{m}$, a cube of edge $\ell$ has diameter equal to $\ell\sqrt{m}$. Revisit Lemma 05.1.

Lemma 02.1. Let $S$ be a subset of a metric space $(X,d)$. Then the following conditions are equivalent.

(a) $S$ is totally bounded, ie the metric space $(S,d_s)$ is totally bounded as per Definition 02.6.

(b) For every $\varepsilon > 0$, there exists a finite $T \subseteq X$ such that for each $x \in S$ there is $y \in T$ with $d(x,y) < \varepsilon$.

(c) For every $\varepsilon > 0$, there is a finite cover of $S$ by subsets of $X$ each with diameter less than $\varepsilon$.

(d) For every $\varepsilon > 0$, there is a finite partition of $A$ consisting of sets each of diameter less than $\varepsilon$.

Proof. Activity.

While studying the proof of the next result, it is recommended that you draw a diagram in $\mathbb{R}^2$ to help you visualise the argument.

Theorem 02.14. A subset of $\mathbb{R}^{m}$ is totally bounded if and only if it is bounded.

Proof. Let $B \subseteq \mathbb{R}^m$ be bounded and choose any point $b = (s_1, \ldots, s_m)$ in $B$. Since $B$ is bounded we can find a real number $r > 0$ such that $B \subseteq B(b,r)$. Then, as one checks easily, $B$ is also contained in the cube

$$
C = \left[ s _ { 1 } - r , s _ { 1 } + r \right] \times \cdots \times \left[ s _ { m } - r , s _ { m } + r \right]
$$

with edge $2r$. If each of the intervals $[s_i - r, s_i + r], i = 1, 2, \ldots, m$, is partitioned into $k$ subintervals of equal length, then the various products of all these subintervals (one from each partition) provide a partition of $C$ into $k^m$ subcubes, each of edge $2r/k$, and therefore diameter $2r\sqrt{m}/k$. Thus, given $\varepsilon > 0$, if we choose $k$ so large that $2r\sqrt{m}/k < \varepsilon$, then the partition of $C$ mentioned above provides a finite cover for $B$ satisfying condition (c) of Lemma 02.1. $\square$

Corollary 02.15. (Heine-Borel Theorem) A subset of $\mathbb{R}^m$ is compact if and only if it is closed and bounded.

We end this section by stating, without proof, the following characterisation of total boundedness.

Theorem 02.16. A subset $S$ of a metric space is totally bounded if and only if every infinite sequence in $S$ has a Cauchy subsequence.





Activity 02.1. (a) Prove Lemma 02.1.

(b) Let $A$ be a subset of a metric space $(X,d)$. Suppose $A$ is not compact. Show that there are closed sets $F_1 \supseteq F_2 \supseteq F_3 \supseteq \ldots$ such that $F_k \cap A \neq \emptyset$ for all $k$ and $\left(\bigcap_{k=1}^{\infty} F_k\right) \cap A = \emptyset$.

(c) A collection $\mathcal{A}$ of subsets of a set is said to have the finite intersection property provided that if $\mathcal{B}$ is a finite subcollection of $\mathcal{A}$ then $\bigcap \mathcal{B}$ is nonempty. Prove that a metric space $(X,d)$ is compact if and only if every countable collection of closed subsets of $X$ with the finite intersection property has a nonempty intersection.

(d) A metric space is called separable if it has a countable dense subset. For instance $\mathbb{R}$ is separable since $\mathbb{Q}$ is a countable dense subset of $\mathbb{R}$.

(i) Given an example of a metric space which is not separable.

(ii) Prove that every totally bounded metric space is separable.

(e) Show that a closed subset of a complete metric space is compact if and only if it is totally bounded.

(f) Let $A$ be a subset of a metric space. Show that $A$ is totally bounded if and only if $\overline{A}$ is totally bounded.

We have come to the end of Learning Unit 4. Before moving on to Learning Unit 5 on Connectedness, make sure that you are familiar with the concepts and are able to do the activities correctly.





# LEARNING UNIT 5

# CONNECTEDNESS

The outcome for this Learning Unit is;

Demonstrate the concept of connectedness of a metric space.

# 01 CONNECTED SETS

From an intuitive point of view, a connected metric space (or subset of a metric space) is one which consists of a single piece. The main goal of this section is to make this notion precise.

Definition 01.1. A metric space $(X,d)$ is disconnected if there are two nonempty, disjoint open sets $A,B \subseteq X$ such that $X = A \cup B$. A connected metric space is one which is not disconnected. A subset $S$ of a metric space $(X,d)$ is connected (respectively, disconnected) if the metric space $(S,d_S)$ is connected (respectively, disconnected).

Recall that a subset $A$ of a set $X$ is a proper subset in case $A \neq \emptyset$ and $A \neq X$. Recall also that in any metric space, the (improper) subsets $\emptyset$ and the whole space are both open and closed. The following easy result characterises connectedness in terms of proper subsets that are both open and closed.

Theorem 01.2. A metric space is connected if and only if it has no proper subset which is both open and closed. Equivalently, a metric space is disconnected if and only if it has a proper subset which is both open and closed.

Proof. Let $(X,d)$ be a metric space which has a proper subset $S$, say, which is both open and closed. Put $T=X\backslash S$. Since $S$ is a proper subset of $X,T$ is nonempty. Thus $S$ and $T$ are nonempty, disjoint open subsets of $X$ with $X=S\cup T$. Thus $(X,d)$ is disconnected. Conversely, suppose $(X,d)$ is a disconnected metric space. Find two nonempty, disjoint





open sets $A$ and $B$ such that $X = A \cup B$. Now, since $A \cup B = X$ and $A \cap B = \emptyset$, it follows that $B = X \setminus A$. Because $A$ is open, we have that $B$ is closed. So $B$ is both open and closed. Since $A$ is a proper subset of $X$ and $B = X \setminus A$, we have that $B$ is a proper subset of $X$. Thus $B$ is a proper subset of $X$ which is both open and closed. $\square$

Now let us examine a little closer what it means for a subset of a metric space to be connected (or disconnected, if you please). Recall that if $(X,d)$ is a metric space and $S \subseteq X$, then a subset $A$ of $S$ is open in $S$ if and only if $A = S \cap U$ for some set $U$ which is open in $X$.

Theorem 01.3. Let $(X,d)$ be a metric space and $S \subseteq X$. Then $S$ is disconnected if and only if there are open subsets $U$ and $V$ of $X$ (ie $U$ and $V$ open in $X$) such that $S \subseteq U \cup V$, $S \cap U \neq \emptyset$, $S \cap V \neq \emptyset$ and $S \cap U \cap V = \emptyset$.

Proof. (⇒) Suppose $S$ is disconnected. This means that the metric space $(S,d_S)$ is disconnected. So there are two disjoint, nonempty open subsets $A$ and $B$ (ie $A$ and $B$ open in $S$) of $S$ such that $S = A \cup B$. So by Theorem 02.6, we can find open subsets $U$ and $V$ of $X$ such that $A = S \cap U$ and $B = S \cap V$. It is easy to check that $U$ and $V$ satisfy the properties stated in the theorem.

(⇐) Suppose $S$, $U$ and $V$ are as stated. Put $G = S \cap U$ and $H = S \cap V$. Then clearly, $G$ and $H$ are two nonempty, disjoint open subsets of $S$ with $S = G \cup H$. So $(S, d_S)$ is disconnected. $\square$

Another result which provides a useful criterion for connected subsets of metric spaces is facilitated by the following definition.

Definition 01.4. Let $(X,d)$ be a metric space and let $A$ and $B$ be subsets of $X$. We say $A$ and $B$ are separated in $X$ if $\overline{A} \cap B = \overline{B} \cap A = \emptyset$. If $A$ and $B$ are separated in $X$ and $X = A \cup B$, we say $A$ and $B$ form a separation of $X$.

Theorem 01.5. A metric space is connected if and only if it cannot be expressed as a union of two nonempty sets that are separated in it.

Proof. Let $(X,d)$ be a disconnected metric space. Then there are nonempty, disjoint open sets $U$ and $V$ such that $X=U\cup V$. Then $U$ and $V$ are also closed, so $\overline{U}\cap V=U\cap V=\emptyset$ and $\overline{V}\cap U=V\cap U=\emptyset$. Therefore $U$ and $V$ are separated in $X$. This proves that if a metric space cannot be expressed as a union of two nonempty sets that are separated in it, then it is connected.

Conversely, suppose $(X,d)$ is a metric space such that $X = A \cup B$ for some nonempty





subsets $A$ and $B$ with $\overline{A} \cap B = \overline{B} \cap A = \emptyset$. Since $X = A \cup B$ and $\overline{A} \cap B = \emptyset$, it follows that $\overline{A} \subseteq A$. Hence $A = \overline{A}$, showing that $A$ is closed. Similarly, $B$ is closed. But then from $X = A \cup B$ and $\overline{A} \cap B = A \cap B = \emptyset$, we deduce that $A = X \backslash B$, and therefore $A$ and $B$ are also open. Thus $X$ is not connected. $\square$

It follows from the proof of Theorem 01.5 that if $A$ and $B$ form a separation of a metric space $(X,d)$, then $A$ and $B$ are both open and closed.

Theorem 01.6. Let $A$ be a subset of a metric space $(X,d)$. Then $A$ is connected if and only if it cannot be expressed as the union of two nonempty subsets of $X$ that are separated in $X$. Equivalently, $A$ is disconnected if and only if $A$ can be expressed as the union of two nonempty subsets of $X$ that are separated in $X$.

Proof. (⇐) Let us first note that if $U \subseteq A$, then $\operatorname{cl}_A U$, the closure of $U$ in the metric space $(A, d_A)$ is $\overline{U} \cap A$, where $\overline{U}$ denotes the closure of $U$ in $(X, d)$. That is, $\operatorname{cl}_A U = \overline{U} \cap A$. Prove this.

Now suppose $A = U \cap V$ where $\overline{U} \cap V = \overline{V} \cap U = \emptyset$, and $U$ and $V$ are nonempty. We must show that $A$ is disconnected; that is, we must show that the metric space $(A, d_A)$ is disconnected. Note that $U$ and $V$ are subsets of $A$. Now

$$
\operatorname { c l } _ { A } ( U ) \cap V = ( A \cap \overline { { U } } ) \cap V = A \cap ( \overline { { U } } \cap V ) = \emptyset
$$

since $\overline{U}\cap V$. Similarly, $\mathrm{cl}_{A}(V)\cap U=\emptyset$. So by Theorem 01.5 we have that $A$ is disconnected.

(⇒) Let $A$ be a disconnected subset of $(X,d)$. We must express $A$ as a union of two nonempty subsets of $X$ that are separated in $X$. By Theorem 01.3 there are nonempty, open subsets $U$ and $V$ of $X$ such that

$$
A \subseteq U \cap V , \ A \cap U \neq \emptyset , \ A \cap V \neq \emptyset , { \mathrm { ~ a n d ~ } } A \cap U \cap V = \emptyset .
$$

From $A \subseteq U \cap V$ we deduce that $A = A \cap (U \cap V) = (A \cap U) \cap (A \cap V)$. If we can show that $A \cap U$ and $A \cap V$ are separated in $X$, we shall be done. We claim that $\overline{A \cap U} \cap (A \cap V) = \emptyset$. If not, then there is a point $p$ such that $p \in \overline{A \cap U}$ and $p \in A \cap V$. But $p \in \overline{A \cap U}$ means that every $\text{nbd}$ of $p$ has a nonempty intersection with $A \cap U$. From $p \in A \cap V$ we have that $p \in V$. As $V$ is open, $V$ contains a ball with centre $p$. But this ball is then a $\text{nbd}$ of $p$, and hence has a nonempty intersection with $A \cap U$. So also $V \cap (A \cap U) \neq \emptyset$; which is a contradiction. This proves the claim. Similarly, $\overline{A \cap V} \cap (A \cap U) = \emptyset$. Thus $A \cap U$ and $A \cap V$ are separated in $X$.





Remark 01.1. Note that in proving that $\overline{A\cap U}\cap(A\cap V)=\emptyset$ in the foregoing theorem, we have in a way proved Activity 03.1(n).

The next result shows that if $A$ and $B$ form a separation of a metric space $(X,d)$, then every connected subset of $X$ is contained either in $A$ or in $B$.

Theorem 01.7. Let $A$ and $B$ be a separation of a metric space $(X,d)$. If $H$ is any connected subset of $X$, then $H \subseteq A$ or $H \subseteq B$.

Proof. Since $A$ and $B$ are open in $X$, both $H \cap A$ and $H \cap B$ are open in $(H, d_H)$. If both $H \cap A$ and $H \cap B$ were nonempty, then $H$ would be disconnected. Therefore either $H \cap A = \emptyset$ or $H \cap B = \emptyset$. Thus $H \subseteq A$ or $H \subseteq B$. $\square$

Theorem 01.8. Let $A$ be a connected subset of a metric space $(X,d)$. If $B$ is a subset of $X$ such that $A \subseteq B \subseteq \overline{A}$, then $B$ is connected. So, in particular, closures of connected sets are connected.

Proof. If $B$ is not connected, there are two open subsets $U$ and $V$ of $X$ such that

$$
B \subseteq U \cup V , \ B \cap U \neq \emptyset , \ B \cap V \neq \emptyset { \mathrm { ~ a n d ~ } } B \cap U \cap V = \emptyset .
$$

Since $A$ is connected and $A \subseteq U \cup V$, $A \cap U \cap V = \emptyset$, it follows that $A \cap U = \emptyset$ or $A \cap V = \emptyset$. Say $A \cap U = \emptyset$. Then $A \subseteq V$. Since $U$ is open and $A \cap U = \emptyset$, we have that $\overline{A} \cap U = \emptyset$. [Recall Activity 03.1(n)]. As $B \subseteq \overline{A}$, we then have $B \cap U = \emptyset$, contradicting the fact that $B \cap U \neq \emptyset$. $\square$

We end by showing that connected subsets of $\mathbb{R}$ have a particularly simple structure, namely: they are intervals. Recall that intervals are subsets of $\mathbb{R}$ of the form

$(-\infty,\infty)$, $(-\infty,b)$, $(-\infty,b]$, $(a,\infty)$, $[a,\infty)$, $(a,b)$, $[a,b)$, $(a,b]$, $[a,b]$, where $a,b\in\mathbb{R}$ with $a\leq b$.

We note that the interval $[a,b]$ with $a=b$ is the singleton $\{a\}$. Clearly all singletons (in any metric space) are connected.

Notice (actually, prove) that a subset $S$ of $\mathbb{R}$ is not an interval if and only if there are real numbers $a, b, c$ such that $a < b < c$ and $a, c \in S$, $b \notin S$.

Theorem 01.9. A subset of $\mathbb{R}$ is connected if and only if it is an interval.

Proof. We shall show that a subset of $\mathbb{R}$ is disconnected if and only if it is not an interval. So let $S$ be a subset of $\mathbb{R}$ which is not an interval. Find real numbers $a, b, c$ such that





$a < b < c$, $a, c \in S$ and $b \notin S$. It is easy to check that $S \cap (\infty, b)$ and $S \cap (b, \infty)$ are separated in $\mathbb{R}$ and $S$ equals, their union. So $S$ is disconnected.

Conversely, let $S$ be a disconnected subset of $\mathbb{R}$. Then there are nonempty subsets $A$ and $B$ of $\mathbb{R}$ which are separated in $\mathbb{R}$ and such that $S = A \cup B$. Pick $x \in A$ and $y \in B$. Then $x \neq y$ since $A \cap B = \emptyset$ [separated sets are disjoint]. Then $x < y$ or $y < x$. Say $x < y$. Put $\alpha = \sup(A \cap [x, y])$. Then $\alpha \in \overline{A}$, and therefore $\alpha \notin B$ since $\overline{A} \cap B = \emptyset$. As $x \in A \cap [x, y]$ we have that $x \leq \alpha$. So $x \leq \alpha \leq y$. But $\alpha \neq y$ as $y \in B$, so $x \leq \alpha < y$. Now if $\alpha \notin A$, then $x < \alpha < y$ and $\alpha \in A$, then $\alpha \notin \overline{B}$. Hence there is a real number $z$ such that $\alpha < z < y$ and $z \notin B$. So $x < z < y$ and $z \notin S$. So again we have that $S$ is not an interval. $\square$

Activity 01.1. (a) Give an example of a disconnected set whose closure is connected.

(b) Show that a metric space is connected if and only if every nonempty proper subset has nonempty boundary.

(c) Show that a metric space $(X,d)$ is connected if and only if for every two points in $X$ there is some connected subset of $X$ which contains both the points.

We have come to the end of Learning Unit 5. Before moving on to Learning Unit 6 on Continuity, make sure you are familiar with the concepts and are able to do the activities correctly.





# LEARNING UNIT 6

# CONTINUITY

The outcome of this Learning Unit is to;

Demonstrate the concept of continuity on metric spaces.

# 01 CONTINUOUS FUNCTIONS

Since defining metric spaces, we have thus far studied only properties of metric spaces and subsets of metric spaces. In this chapter we study maps between metric spaces, and also properties of metric spaces that are preserved or reflected by continuous functions.

In elementary calculus you learnt that a function $f : \mathbb{R} \to \mathbb{R}$ is continuous at $x_0 \in \mathbb{R}$ if for every $\varepsilon > 0$ there is a $\delta > 0$ such that

$$
| f ( x ) - f ( x _ { 0 } ) | < \varepsilon { \mathrm { ~ w h e n e v e r } } \ | x - x _ { 0 } | < \delta .
$$

Now recalling that in $\mathbb{R}\left|w-z\right|$ is the distance between $w$ and $z$ it is clear that the notion of continuity can be defined for functions that map metric spaces into metric spaces in such a way that in the case of real-valued functions of a real variable, the definition reduces to the one above.

Definition 01.1. Let $(X,d)$ and $(Y,\rho)$ be metric spaces. A function $f : X \to Y$ is said to be continuous at a point $x_0 \in X$ if for every $\varepsilon > 0$, there exists $\delta > 0$ such that $\rho(f(x), f(x_0)) < \varepsilon$ whenever $d(x, x_0) < \delta$. We say $f$ is continuous on a set $S \subseteq X$ if it is continuous at every point of $S$. In particular, if we simply say $f$ is continuous, we mean it is continuous at every point of its domain $X$.





So a function $f:(X,d)\to(Y,\rho)$ is continuous at $x_0\in X$ if

$$
\forall \varepsilon > 0 \ \exists \delta > 0 \mathrm { ~ s u c h ~ t h a t ~ } d ( x , x _ { 0 } ) < \delta \Rightarrow \rho ( f ( x ) , f ( x _ { 0 } ) ) < \varepsilon ,
$$

that is, if whenever we are given $\varepsilon > 0$ we can find $\delta > 0$ (this $\delta$ depends on $x_0$ and $\varepsilon$) such that for each $x \in X$ with $d(x, x_0) < \delta$, we have that $\rho(f(x), f(x_0)) < \varepsilon$. This is equivalent to: For every $\varepsilon > 0$ there exists $\delta > 0$ such that if $x \in B(x_0, \delta)$ then $f(x) \in B(f(x_0), \varepsilon)$, that is $f[B(x, \delta)] \subseteq B(f(x_0), \varepsilon)$.

Continuity at a point is characterisable in terms of sequences as stated in the following theorem:

Theorem 01.2. Let $(X,d)$ and $(Y,\rho)$ be metric spaces and $f : X \to Y$ be a function. Then $f$ is continuous at $x_0 \in X$ if and only if for every sequence $\{x_n\}$ in $X$ which converges to $x_0$, the sequence $\{f(x_n)\}$ in $Y$ converges to $f(x_0)$.

Proof. (⇒) Let $f$ be continuous at $x_0$ and $\{x_n\}$ be a sequence in $X$ with $x_n \to x_0$. We must show that $f(x_n) \to f(x_0)$. Let $\varepsilon > 0$ be given. Since $f$ is continuous at $x_0$, we can find $\delta > 0$ such that if $x \in X$ with $d(x, x_0) < \delta$, then $\rho(f(x), f(x_0)) < \varepsilon$. Since $x_n \to x_0$ and $\delta > 0$, we can find $n_0 \in \mathbb{N}$ such that $d(x_n, x_0) < \delta$ whenever $n \geq n_0$. Now if $n \geq n_0$ then $d(x_n, x_0) < \delta$, which implies that $\rho(f(x_n), f(x_0)) < \varepsilon$. This proves that $\{f(x_n)\}$ converges to $f(x_0)$ in $(Y, \rho)$.

(⇐) Now let $f$ have the stated property. We must prove that $f$ is continuous at $x_0$. We do it by contradiction. So suppose $f$ is not continuous at $x_0$. Then there exists $\varepsilon > 0$ for which no $\delta > 0$ "works". So for each $k \in \mathbb{N}$ there is at least one point $x_k$ of $X$ for which $\delta = \frac{1}{k}$ "fails". This means that

$$
d ( x _ { k } , x _ { 0 } ) < \frac { 1 } { k } \; \; \mathrm { b u t } \; \; \rho ( f ( x _ { k } ) , f ( x _ { 0 } ) ) \geq \varepsilon .
$$

Now the sequence $\{x_{n}\}$ has the property that $d(x_{n},x_{0})<\frac{1}{n}$ for every $n$; hence $x_{n}\rightarrow x_{0}$. But clearly the sequence $\{f(x_{n})\}$ does not converge to $f(x_{0})$. This violates the hypothesis. $\square$

The foregoing result is helpful in showing that a function is not continuous at some point $p$. All we need do is find a sequence $\{x_n\}$ with $x_n \to p$ but for which $f(x_n) \not\to f(p)$.





The following result characterises continuity in terms of open sets.

Theorem 01.3. Let $(X,d)$ and $(Y,\rho)$ be metric spaces and let $f:X\to Y$ be a function. Then $f$ is continuous if and only if $f^{-1}[G]$ is open in $X$ whenever $G$ is open in $Y$. That is, a function is continuous if and only if pre-images of open sets are open sets.

Proof. (⇒) Let $f$ be continuous and $G \subseteq Y$ be open. We must show that $f^{-1}[G]$ is open. If $f^{-1}[G] = \emptyset$, there is nothing to prove. So assume $f^{-1}[G] \neq \emptyset$. Let $z \in f^{-1}[G]$. Then $f(z) \in G$, and so there exists $\varepsilon > 0$ such that $B(f(z), \varepsilon) \subseteq G$ since $G$ is open. Since $f$ is continuous at $z$, there exists $\delta > 0$ such that $\rho(f(x), f(z)) < \varepsilon$ whenever $x \in X$ with $d(x, z) < \delta$. Thus $f[B(z, \delta)] \subseteq B(f(z), \varepsilon)$, whence we get $B(z, \delta) \subseteq f^{-1}[B(f(z), \varepsilon)] \subseteq f^{-1}[G]$. Therefore $f^{-1}[G]$ is open.

(⇐) Let $f$ have the stated property. We must show that $f$ is continuous. Let $p$ be an arbitrary point of $X$ and $\varepsilon > 0$. The ball $B(f(p),\varepsilon)$ is open in $Y$, so by the hypothesis we have that $f^{-1}[B(f(p),\varepsilon)]$ is open in $X$. Since $f(p) \in B(f(p),\varepsilon)$, we have that $p \in f^{-1}[B(f(p),\varepsilon)]$. So, since $f^{-1}[B(f(p),\varepsilon)]$ is open, there exists $\delta > 0$ such that $B(p,\delta) \subseteq f^{-1}[B(f(p),\varepsilon)]$. Then $f[B(p,\delta)] \subseteq B(f(p),\varepsilon)$; that is if $d(x,p) < \delta$ then $\rho(f(x),f(p)) < \varepsilon$. So $f$ is continuous at $p$, and hence on $X$. $\square$

Corollary 01.4. A function $f : (X,d) \to (Y,\rho)$ is continuous if and only if $f^{-1}[C]$ is closed in $X$ whenever $C$ is closed in $Y$.

Proof. Recall that $f^{-1}[X\backslash C]=Y\backslash f^{-1}[C]$.

Next we show that the composite of continuous functions is continuous.

Theorem 01.5. Let $(X_1,d_1)$, $(X_2,d_2)$ and $(X_3,d_3)$ be metric spaces. Let $f : X_1 \to X_2$ and $g : f[X_1] \to X_3$ be functions. If $f$ is continuous at a point $p \in X_1$ and $g$ is continuous at $f(p)$, then the composite function $g \circ f$ is continuous at $p$.

Proof. Let $\varepsilon > 0$ be given. Since $g$ is continuous at $f(p)$, there exists $\beta > 0$ such that

$$
d _ { 3 } ( g ( y ) , g ( f ( p ) ) ) < \varepsilon \; \; \mathrm { i f } \; \; d _ { 2 } ( y , f ( p ) ) < \beta \; \; \mathrm { a n d } \; \; y \in f [ X _ { 1 } ] .
$$

Since $f$ is continuous at $p$, there exists $\delta > 0$ such that

$$
d _ { 2 } ( f ( x ) , f ( p ) ) < \beta \ \ \mathrm { i f } \ \ d _ { 1 } ( x , p ) < \delta .
$$

It then follows that

$$
d _ { 3 } ( ( g \circ f ) ( x ) , ( g \circ f ) ( p ) ) < \varepsilon
$$





if $d_{1}(x,p) < \delta$. So $g \circ f$ is continuous at $p$.

Notice that continuity of $g \circ f$ follows readily from Theorem 01.3 since, if $f$ and $g$ are continuous on their domains and $G$ is an open set, then

$$
( g \circ f ) ^{- 1} [ G ] = f ^{- 1} [ g ^{- 1} [ G ] ] .
$$

Example 01.1. Let $X$ be any metric space and $Y$ be any discrete metric space. Any function $f: Y \to X$ is continuous. To show this, let $G$ be an open subset of $X$. Then $f^{-1}[G]$ is open in $Y$ since every subset of $Y$ is open. So $f$ is continuous.

Example 01.2. Let $X$ be the reals with the usual metric and $Y$ be the reals with the discrete metric. Let $f: Y \to X$ be given by $f(x) = x$. Then of course, as seen above, $f$ is continuous. Now let $g: X \to Y$ be given by $g(x) = x$. Notice that, as functions from the set $\mathbb{R}$, $g$ is the same function as $f$. But now $g$ is not continuous since, for instance, $\{3\}$ is open in $Y$ but $g^{-1}[\{3\}]$ is not open in $X$. In fact there is no single point of $X$ where $g$ is continuous. Indeed, for any $p \in X$, there is no $\delta > 0$ such that $g[B(p, \delta)] \subseteq B\left(p, \frac{1}{2}\right)$.

By now it should be clear that the discrete metric spaces are a source of all kinds of "bizarre" examples.

Activity 01.1. (a) Let $(X,d)$ be a metric space, and let $f,g:X\to\mathbb{R}$ be continuous functions.

(i) Prove that the function $h : X \to \mathbb{R}$ defined by $h(x) = f(x) + g(x)$ is continuous.

(ii) Prove that the function $h : X \to \mathbb{R}$ defined by $h(x) = f(x) \cdot g(x)$ is continuous.

(iii) Prove that the function $h : X \to \mathbb{R}$ defined by $h(x) = \max\{f(x), g(x)\}$ is continuous.

(iv) Let $A = \{x \in X \mid g(x) = 0\}$. Prove that the function $h : X \backslash A \to \mathbb{R}$ defined by $h(x) = f(x)/g(x)$ is continuous.

(b) Let $(X,d)$ and $(Y,\rho)$ be metric spaces, $f$ and $g$ be continuous functions mapping $X$ into $Y$ and $A$ be a subset of $X$ such that $f(a)=g(a)$ for all $a\in A$. Show that $f(x)=g(x)$ for all $x\in\overline{A}$.

(c) Let $f : \mathbb{R} \to \mathbb{R}$ be a continuous function and define $g : \mathbb{R} \to \mathbb{R}^2$ by $g(x) = (x, f(x))$. Prove that $g$ is continuous.





(d) Let $f:[a,b]\to\mathbb{R}$ be a continuous function and suppose $f(x)=0$ for each $x\in\mathbb{Q}\cap[a,b]$. Show that $f(x)=0$ for all $x\in[a,b]$.

(e) Recall that every rational number $x$ in $[0,1]$ can be written as $x=\frac{m}{n}$ where $m,n\in\mathbb{N}$ and have no common divisor $\neq 1$. Now let $f:[0,1]\to\mathbb{R}$ be defined by

$f(x)=\begin{cases}x,\text{if }x\text{ is irrational}\\\frac{1}{n},\text{if }x=\frac{m}{n},\text{where }m\text{ and }n\text{ have no common divisor }\neq 1.\end{cases}$

Show that $f$ is continuous only at irrational numbers in $[0,1]$.

(f) Let $(X,d)$ and $(Y,\rho)$ be metric spaces. Prove that for a function $f:X\to Y$ the following are equivalent:

(i) $f$ is continuous

(ii) $f(\overline{A}) \subseteq f[A]$ for every $A \subseteq X$

(iii) $f^{-1}[\text{int}(B)] \subseteq \text{int}(f^{-1}[B])$ for every $B \subseteq Y$.

(g) Let $f$ be a function mapping a metric space $(X,d)$ into a metric space $(Y,\rho)$. Prove that $f$ is continuous if and only if $f$ is continuous on every compact subset of $X$. [Hint: show that if $x_n \to p$ in $X$, then $\{p, x_1, x_2, \ldots\}$ is a compact subset of $X$].

Uniform continuity is examined next.

# 02 UNIFORM CONTINUITY

If a function is continuous on a subset $S$ of a metric space, then for each $p \in S$, if $\varepsilon > 0$ is given we can find $\delta > 0$ which depends on $\varepsilon$ and $p$ such that if the distance between a point $x$ of $S$ and $p$ is less than $\delta$, then the distance between $f(x)$ and $f(p)$ is less than $\varepsilon$. In general it is not possible to find a $\delta$ which depends only on $\varepsilon$ that serves equally well for every point of $S$. When this happens, the function is continuous in a special way which is the subject of this section.

Definition 02.1. Let $f : (X, d) \to (Y, \rho)$ be a function between metric spaces. We say $f$ is uniformly continuous on a subset $A$ of $X$ if for every $\varepsilon > 0$ there exists $\delta > 0$ such that if $x$ and $w$ are any two points of $A$ with $d(x, w) < \delta$, then $\rho(f(x), f(w)) < \varepsilon$.

Let us reiterate the difference between continuity and uniform continuity. If a function is continuous on a set $S$, then given $\varepsilon > 0$ and a point $p$ in $S$, there is a $\delta > 0$ that depends





on $\varepsilon$ and $p$ that satisfies the condition of the definition. On the other hand, given $\varepsilon > 0$, there is a $\delta > 0$ that depends only on $\varepsilon$ such that $\delta$ "works" for all points of $S$.

Let us also point out that whereas we can talk of continuity at a point, it is meaningless to ask whether a given function is uniformly continuous at a point. Uniform continuity is a property of a function on a set.

Clearly, every uniformly continuous function is continuous. Below we give an example of a continuous function which fails to be uniformly continuous on some set. As in the case of continuity, if we say a function is uniformly continuous without stating where, we mean it is uniformly continuous on its domain.

Example 02.1. Let $f:(0,1]\to\mathbb{R}$ given by $f(x)=\frac{1}{x}$. Then $f$ is not uniformly continuous (on $(0,1]$). To show this, let $\varepsilon=2$, and suppose we can find $\delta>0$ that satisfies the condition of the definition. We may assume $0<\delta<1$. The reason is that if $\delta'>0$ works, then any $\gamma<\delta'$ will work as well. Now let $x=\delta$ and $w=\frac{\delta}{4}$. Then $x,w\in(0,1]$ and $|x-w|=\frac{3}{4}\delta<\delta$. But now

$$
| f ( x ) - f ( w ) | = \frac { 4 } { \delta } - \frac { 1 } { \delta } = \frac { 3 } { \delta } > 3 .
$$

So for these points, $|f(x) - f(w)| \not\ll \varepsilon$.

This function is however continuous on $(0,1]$. Indeed, let $p \in (0,1]$ and $\varepsilon > 0$ be given. Now choose a real number $r$ such that $0 < p - r < p + r < 1$. For any $x \in (0,1]$ with $|x - p| < r$ we have $-r < x - p < r$, whence $0 < p - r < x$. Now for such $x$ we have

$$
\begin{array}{rl} { | f ( x ) - f ( p ) | } & { = \left| \frac { 1 } { x } - \frac { 1 } { p } \right| } \\& { = \frac { 1 } { x p } \left| x - p \right| } \\& { \leq \frac { 1 } { p ( p - r ) } \left| x - p \right| \; \; \mathrm { s i n c e } \; \; \frac { 1 } { x } < \frac { 1 } { p - r } . } \end{array}
$$

So,

$$
| f ( x ) - f ( p ) | < \varepsilon \; \; \mathrm { i f } \; \; | x - p | < p ( p - r ) \varepsilon .
$$

Thus choosing $\delta = \min\{r, p(p - r)\varepsilon\}$ will ensure that $|x - p| < \delta \Rightarrow |f(x) - f(p)| < \varepsilon$.

Example 02.2. Let $f:[1,\infty)\to\mathbb{R}$ be given by $f(x)=\sqrt{x}$. This function is uniformly





continuous. To see this, observe that for any two points $x,y$ in $[1,\infty)$ we have

$$
\begin{array}{rl} { | f ( x ) - f ( y ) | } & { = \ | \sqrt { x } - \sqrt { y } | } \\& { = \frac { | x - y | } { \sqrt { x } + \sqrt { y } } } \\& { \leq \ \frac { 1 } { 2 } | x - y | , \ \mathrm { s i n c e } \ \sqrt { x } \geq 1 \ \mathrm { a n d } \ \sqrt { y } \geq 1 . } \end{array}
$$

Thus $|f(x)-f(y)|<\varepsilon$ if $\frac{1}{2}|x-y|<\varepsilon$, ie if $|x-y|<2\varepsilon$. Therefore given $\varepsilon>0$, choose $\delta=2\varepsilon$.

We now state a result which is useful in showing a given function not to be uniformly continuous.

Theorem 02.2. A function $f : (X, d) \to (Y, \rho)$ is uniformly continuous if and only if for any pair of sequences $\{a_n\}$, $\{b_n\}$ in $X$,

$$
\operatorname* { l i m } _ { n \to \infty } d ( a _ { n } , b _ { n } ) = 0 \; \Rightarrow \; \operatorname* { l i m } _ { n \to \infty } \rho ( f ( a _ { n } ) , f ( b _ { n } ) ) = 0 .
$$

Proof. (⇒) Let $f$ be uniformly continuous. Suppose, by way of contradiction, that the stated property does not hold. So find two sequences $\{a_n\}$ and $\{b_n\}$ in $X$ such that $\lim\limits_{n\to\infty}d(a_n,b_n)=0$ but $\lim\limits_{n\to\infty}\rho(f(a_n),f(b_n))\neq0$. Now observe that if a sequence $\{x_n\}$ of nonnegative real numbers does not converge to 0 then there exists $\varepsilon>0$ and a subsequence $\{x_{n_k}\}$ such that $x_{n_k}\geq\varepsilon$ for each $k=1,2,\ldots$.

So then there are subsequences $\{a_{n_k}\}$ and $\{b_{n_k}\}$ of $\{a_n\}$ and $\{b_n\}$ respectively such that for some $\varepsilon > 0$

$$
\rho ( f ( a _ { n _ { k } } ) , f ( b _ { n _ { k } } ) ) \geq \varepsilon \; \; \mathrm { f o r ~ e a c h } \; \; k = 1 , 2 , \ldots
$$

Since $\lim_{n\to\infty}d(a_{n},b_{n})=0$, we have that $\lim_{k\to\infty}d(a_{n_{k}},b_{n_{k}})=0$. Now, by uniform continuity, find $\delta>0$ such that for the $\varepsilon$ above we have

$$
\rho ( f ( z ) , f ( w ) ) < \varepsilon
$$

whenever $z,w\in X$ and $d(z,w)<\delta$. Thus, from the fact that $\lim\limits_{k\to\infty}d(a_{n_k},b_{n_k})=0$, we can find $\ell\in\mathbb{N}$ such that

$$
d ( a _ { n _ { \ell } } , b _ { n _ { \ell } } ) < \delta .
$$





So then we get

$$
\rho ( f ( a _ { n _ { \ell } } ) , \, f ( b _ { n _ { \ell } } ) ) < \varepsilon ,
$$

contradicting what we have above.

(⇐) Suppose the “two-sequences” property holds. We must show that $f$ is uniformly continuous. Suppose not. Then there exists $\varepsilon > 0$ such that for every $\delta = \frac{1}{n}$ ($n = 1, 2, \ldots$) there are points $a_n$ and $b_n$ in $X$ with

$$
d ( a _ { n } , b _ { n } ) < \frac { 1 } { n } \ \mathrm { b u t } \ \ \rho ( f ( a _ { n } ) , f ( b _ { n } ) ) \geq \varepsilon .
$$

As $\lim_{n\to\infty}d(a_n,b_n)=0$ and $\lim_{n\to\infty}\rho(f(a_n),f(b_n))\neq0$, we have a contradiction.

Example 02.3. The function $f : \mathbb{R} \to \mathbb{R}$ given by $f(x) = x^2$ is not uniformly continuous. For each $n \in \mathbb{N}$ let $a_n = n$ and $b_n = n + \frac{1}{n}$. Then $\lim\limits_{n \to \infty} |a_n - b_n| = \lim\limits_{n \to \infty} \frac{1}{n} = 0$. However

$$
\begin{array}{rlr} { | f ( a _ { n } ) - f ( b _ { n } ) | } & { = } & { \left| n ^{2} - \left( n + \frac { 1 } { n } \right) ^{2} \right| } \\& { = } & { 2 + \frac { 1 } { n ^{2} } , } \end{array}
$$

which does not tend to 0 and $n \to \infty$. Thus by Theorem 02.2 we have that $f$ is not uniformly continuous.

Activity 02.1. (a) Find an example of a continuous function $f$ and a Cauchy sequence $\{x_n\}$ such that $\{f(x_n)\}$ is not a Cauchy sequence. Now suppose $g:(X,d)\to(Y,\rho)$ is a uniformly continuous function. Show that if $\{x_n\}$ is a Cauchy sequence in $X$, then $\{g(x_n)\}$ is a Cauchy sequence in $Y$.

(b) Recall that if $E$ is a nonempty subset of a metric space $(X,d)$, then the distance from $x$ to $E$, where $x\in X$, is defined by $d(x,E)=\inf\{d(x,z)\mid z\in E\}$. Now let $f:(X,d)\to\mathbb{R}$ be defined by $f(x)=d(x,E)$. Show that $f$ is uniformly continuous. [Hint: $d(x,E)\leq d(x,z)\leq d(x,y)+d(y,z)$, so that $d(x,E)\leq d(x,y)+d(y,E)$ for all $x,y\in X$. Use this to show that $|d(x,E)-d(y,E)|\leq d(x,y)$.]

(c) Let $f:(0,\infty)\to\mathbb{R}$ be given by $f(x)=\frac{1}{x}$. Use Theorem 02.2 to show that $f$ is not uniformly continuous.

(d) Is it true that if a function is uniformly continuous on a set $S$, then it is uniformly continuous on every subset of $S$ that has at least two points?





We next look at continuity and compactness.

# 03 CONTINUITY AND COMPACTNESS

We saw above that continuity on a set does not necessarily imply uniform continuity on that set. If however the set on which a function is continuous is compact, then necessarily the function is uniformly continuous on the set as we prove below.

Theorem 03.1. Let $f : (X,d) \to (Y,\rho)$ be a function mapping one metric space into another. Let $A$ be a compact subset of $X$. If $f$ is continuous on $A$, then $f$ is uniformly continuous on $A$.

Proof. Let $\varepsilon > 0$ be given. By continuity, for each point $a \in A$ there is a real number $r_a > 0$ such that if $x \in A$ and $d(x, a) < r_a$, then $\rho(f(x), f(a)) < \frac{\varepsilon}{2}$. Let us rewrite this in terms of balls. It says

$$
\rho ( f ( x ) , f ( a ) ) < \frac { \varepsilon } { 2 } \; \; \mathrm { w h e n e v e r } \; \; x \in A \cap B ( a , r _ { a } ) .
$$

Now $\mathcal{C}=\left\{B\left(a,\frac{r_{a}}{2}\right)\mid a\in A\right\}$ is an open cover of $A$. So by compactness there are points $a_{1},\ldots,a_{m}$ in $A$ and corresponding positive numbers $r_{1},\ldots,r_{m}$ (with $r_{i}=r_{a_{i}}$) such that

$$
A \subseteq B ( a _ { 1 } , \frac { r _ { 1 } } { 2 } ) \cup \cdots \cup B ( a _ { m } , \frac { r _ { m } } { 2 } ) .
$$

Put $\delta=\min\{\frac{r_{1}}{2},\ldots,\frac{r_{m}}{2}\}$. We shall show that this $\delta$ works. So let $z$ and $w$ be any two points of $A$ with $d(z,w)<\delta$. Then there is some ball $B(a_{k},\frac{r_{k}}{2})$, say, that contains $z$. So $z\in A\cap B(a_{k},\frac{r_{k}}{2})$, and therefore

$$
\rho ( f ( z ) , f ( a _ { k } ) < \frac { \varepsilon } { 2 } .
$$

Now $d(w,a_k) \leq d(w,z) + d(z,a_k) < \delta + \frac{r_k}{2} \leq \frac{r_k}{2} + \frac{r_k}{2} = r_k$. Thus $w \in A \cap B(a_k,r_k)$, and therefore

$$
\rho ( f ( w ) , f ( a _ { k } ) ) < \frac { \varepsilon } { 2 } .
$$

Combining (*) and (**) yields

$$
\rho ( f ( z ) , f ( w ) ) \leq \rho ( f ( z ) , f ( a _ { k } ) ) + \rho ( f ( a _ { k } ) , f ( w ) ) < \varepsilon .
$$





Example 03.1. Let $f : [0, \infty) \to \mathbb{R}$ be given by $f(x) = \sqrt{x}$. Then $f$ is continuous, and therefore continuous on $[0, 1]$. Since $[0, 1]$ is a compact subset of $\mathbb{R}$ (and therefore of $[0, \infty)$), $f$ is uniformly continuous on $[0, 1]$. Try to prove this uniform continuity directly from the definition.

Next we show that the image of a compact set under a continuous function is compact.

Theorem 03.2. Let $f : (X,d) \to (Y,\rho)$ be a function mapping one metric space into another. If $f$ is continuous on a compact subset $K$ of $X$, then the image $f[K]$ of $K$ under $f$ is a compact subset of $Y$.

Proof. We shall show that every sequence in $f[K]$ has a convergent subsequence. The result will then follow by Theorem 02.13. Let $\{y_n\}$ be a sequence in $f[K]$. For each $n$ choose $x_n \in K$ such that $y_n = f(x_n)$. We then have a sequence $\{x_n\}$ in $K$. Since $K$ is compact, there is a subsequence $\{x_{n_k}\}$ of $\{x_n\}$ and a point $x \in K$ such that $x_{n_k} \to x$. Since $f$ is continuous, Theorem 01.2 gives $f(x_{n_k}) \to f(x)$. But now $f(x) \in f[K]$; so the subsequence $\{y_{n_k}\}$ of $\{y_n\}$ converges to a point of $f[K]$. This completes the proof. $\square$

In Example 01.2, the function $f$ is one-to-one onto and continuous, but $f^{-1}$ (called $g$ in that example) is not continuous. As a corollary to Theorem 03.2, we show that if the domain of a one-to-one onto continuous function is compact, then the inverse of the function is also continuous.

Corollary 03.3. Let $(X,d)$ be a compact metric space and $f:(X,d)\to(Y,\rho)$ be a continuous one-to-one function mapping $(X,d)$ onto a metric space $(Y,\rho)$. Then $f^{-1}:(Y,\rho)\to(X,d)$ is continuous.

Proof. We apply Theorem 01.3. Let $U$ be an open subset of $X$. So we must show that $(f^{-1})^{-1}[U]$ is open in $Y$. Note that $(f^{-1})^{-1}[U] = f[U]$. The set $X \backslash U$ is closed in $X$, and therefore compact by Theorem 01.4. Thus by Theorem 03.2 we have that $f[X \backslash U]$ is a compact subset of $Y$, and is therefore closed by Theorem 01.3. Since $f$ is one-to-one and onto, $f[U] = Y \backslash f[X \backslash U]$ (verify this). Thus $f[U]$ is open, as required. $\square$

In the case of real-valued (ie mapping into $\mathbb{R}$) functions we can say more.

Theorem 03.4. Let $f : X \to \mathbb{R}$ be a continuous real-valued function on a compact metric space $X$. Then

(a) $f[X]$ is a closed and bounded subset of $\mathbb{R}$. (b) There exist points $p$ and $q$ in $X$ such that





$$
f ( p ) = \operatorname* { s u p } \{ f ( x ) \mid x \in X \}  a n d  f ( q ) = \operatorname* { i n f } \{ f ( x ) \mid x \in X \} .
$$

Proof. (a) By Corollary 03.3 we have that $f[X]$ is compact. So by the Heine-Borel Theorem (Corollary 02.15) we have that $f[X]$ is closed and bounded.

(b) If $A$ is a bounded subset of $\mathbb{R}$, then $\sup A \in \overline{A}$ and $\inf A \in \overline{A}$, as you should verify. If fact we have used one of these facts earlier. So if $A$ is also closed, then $\inf A \in A$ and $\sup A \in A$. So then, $\inf f[X] \in f[X]$, which means that $f(q) = \inf f[X]$ for some $q \in X$. Similarly for $\sup f[X]$.

Notice that without compactness, the conclusion above does not always hold. Indeed, if $f:[0,1)\to\mathbb{R}$ is the function given by $f(x)=x$, then $\sup\{f(x)\mid x\in[0,1)\}=1$, and there is no point $p\in[0,1)$ such that $f(p)=1$.

Activity 03.1. (a) Prove Theorem 03.2 using the definition.

(b) Let $K \subseteq \mathbb{R}^2$ be compact and put $A = \{x \in \mathbb{R} \mid \text{there exists } y \in \mathbb{R} \text{ such that } (x, y) \in K\}$. Prove that $A$ is compact. [Suggestion: define $f : \mathbb{R}^2 \to \mathbb{R}$ by $f(x, y) = x$. Show $f$ to be continuous and $A = f[K]$.

(c) Find a continuous function $f$ and a compact set $K$ such that $f^{-1}[K]$ is not compact. [Hint: try constant functions.]

(d) Prove that there is no continuous function mapping $[0, 1]$ onto $[0, 1)$.

(e) Let $(X, d)$ be a compact metric space and $f : X \to X$ be a function such that

$$
d ( f ( x ) , f ( y ) ) = d ( x , y ) \; \; \mathrm { f o r ~ a l l } \; \; x , y \in X .
$$

Prove that:

(i) $f$ is continuous. Is $f$ uniformly continuous?

(ii) $f$ is one-to-one.

(iii) $f$ is onto. [Hint: If $w \in X \setminus f[X]$, show that there is a real number $r > 0$ such that $d(w, z) \geq r$ for all $z \in f[X]$. Then use the sequence $w, f(w), f(f(w)), \ldots$ to contradict the compactness of $X$.]

We next look at continuity and connectedness.





# 04 CONTINUITY AND CONNECTEDNESS

We start with some bit of propaganda. That Real Analysis is a beautiful piece of Mathematics is by now clear to you if you have studied and understood the discussion so far, as well as done (or at least attempted) all the exercises. The results that go counter to intuition, and the ingenuity required to prove facts which are "so obviously true" from a heuristic point of view all add up to this beauty.

Take for instance the following example. If $f$ is a continuous function that maps $[a,b]$ into $\mathbb{R}$ and the graph of $f$ lies above the $x$-axis at $a$ and below the $x$-axis at $b$, then surely the graph must cut the $x$-axis at some point because, being the graph of a continuous function, it consists of "one continuous piece". Who can dispute this? To prove it rigorously takes some doing and will, among other things, be the goal of this section.

Theorem 04.1. Let $f : (X,d) \to (Y,\rho)$ be a continuous function mapping one metric space into another. Let $A$ be a connected subset of $X$. Then $f[A]$ is connected.

Proof. Suppose, by way of contradiction, that $f[A]$ is disconnected. Then, by Theorem 4.1.6, $f[A] = G \cup H$ where $G$ and $H$ are nonempty subsets of $Y$ that are separated in $Y$. Put $U = A \cap f^{-1}[G]$ and $V = A \cap f^{-1}[H]$. Then $A = U \cup V$, and neither $U$ nor $V$ is empty. Since $U \subseteq f^{-1}[G]$, it is immediate that $U \subseteq f^{-1}[\overline{G}]$. Since $f$ is continuous and $\overline{G}$ is closed, we deduce from $U \subseteq f^{-1}[\overline{G}]$ that $\overline{U} \subseteq f^{-1}[\overline{G}]$. Consequently $f[\overline{U}] \subseteq \overline{G}$. Now

$$
\begin{array}{rl} { f [ V ] } & { =  f [ A \cap f ^{- 1} [ H ] ] } \\& { =  f [ A ] \cap f [ f ^{- 1} [ H ] ] } \\& { =  ( G \cup H ) \cap f [ f ^{- 1} [ H ] ] } \\& { \subseteq  ( G \cup H ) \cap H  \mathrm { s i n c e }  f [ f ^{- 1} [ H ] ] \subseteq H } \\& { =  H . } \end{array}
$$

Therefore

$$
\begin{array}{rl} { f [ \overline { { U } } \cap V ] } & { = \ f [ \overline { { U } } ] \cap f [ V ] } \\& { \subseteq \ \overline { { G } } \cap H } \\& { = \ \emptyset . } \end{array}
$$

Hence $f[\overline{U} \cap V] = \emptyset$, which implies that $\overline{U} \cap V = \emptyset$. A similar argument shows that $\overline{V} \cap U = \emptyset$. So $U$ and $V$ are separated in $X$. From $f[A] = G \cup H$ we have

$$
A \subseteq f ^{- 1} [ G ] \cup f ^{- 1} [ H ]
$$





which implies that

$$
\begin{array}{rl} { U \cup V } & { = \ ( A \cap f ^{- 1} [ G ] ) \cup ( A \cap f ^{- 1} [ H ] ) } \\& { = \ A \cap ( f ^{- 1} [ G ] \cup f ^{- 1} [ H ] ) } \\& { = \ A . } \end{array}
$$

By Theorem 01.6 this means that $A$ is disconnected. This contradiction completes the proof. $\square$

Theorem 04.2. (Intermediate-value Theorem) Let $f : S \subseteq \mathbb{R} \to \mathbb{R}$ be a function mapping a subset of $\mathbb{R}$ into $\mathbb{R}$. If $[a,b]$ is an interval contained in $S$ and $f$ is continuous on $[a,b]$, then for every real number $c$ between $f(a)$ and $f(b)$, there is a point $p$ in $[a,b]$ such that $f(p) = c$.

Proof. If $f(a) = f(b)$ there is nothing to prove. So suppose $f(a) \neq f(b)$. Then either $f(a) < f(b)$ or $f(b) < f(a)$. Say $f(a) < f(b)$. The other case is similar. We must show that for any $c$ with $f(a) < c < f(b)$, there is a point $p$ in $[a,b]$ such that $f(p) = c$. By Theorem 01.9, $[a,b]$ is connected. So, by Theorem 04.1, the set $\{f(x) \mid a \leq x \leq b\}$ is connected; and is therefore an interval containing $f(a)$ and $f(b)$. If we assume that $c \notin \{f(x) \mid a \leq x \leq b\}$, then this set will be disconnected. Thus $c = f(p)$ for some $p \in [a,b]$. $\square$

Corollary 04.3. Let $f : [a,b] \to \mathbb{R}$ be a continuous function. If $f(a)$ and $f(b)$ have different signs (ie one positive and the other negative), then $f(c) = 0$ for some $c$ with $a < c < b$.

Proof. Say $f(a) < 0$ and $f(b) > 0$. Then $f(a) < 0 < f(b)$. The result then follows immediately from Theorem 04.2. $\square$

This latter result proves what we stated in the second paragraph of the introductory comments.

The Intermediate-value Theorem, in conjunction with Theorem 03.4(b), actually tells us more about images of closed and bounded intervals under real-valued continuous functions.

Let

$f: S \subseteq \mathbb{R} \to \mathbb{R}$ be a function which is continuous on the interval $[a, b] \subseteq S$. Put

$$
\alpha = \operatorname* { i n f } \{ f ( x ) \mid a \leq x \leq b \} \; \; \mathrm { a n d } \; \; \beta = \operatorname* { s u p } \{ f ( x ) \mid a \leq x \leq b \} .
$$

Then $\alpha$ and $\beta$ are real numbers since the set $\{f(x) \mid a \leq x \leq b\}$ is a compact subset of





$\mathbb{R}$ and is therefore bounded (and of course closed). Then clearly we have

$$
\{ f ( x ) \mid a \leq x \leq b \} \subseteq [ \alpha , \beta ] .
$$

But by Theorem 03.4(b), $\alpha, \beta \in \{f(x) \mid a \leq x \leq b\}$ and by the Intermediate-value Theorem every real number between $\alpha$ and $\beta$ is the image of some point in $[a, b]$. So we therefore have

$$
\left[ \alpha , \beta \right] \subseteq \left\{ f ( x ) \mid a \leq x \leq b \right\} .
$$

All in all this shows that the image of the closed and bounded interval $[a,b]$ is the closed and bounded interval $[\alpha,\beta]$.

Let us end by characterising connectedness of arbitrary metric spaces by means of special kinds of continuous function. Let us denote by $\mathbb{D}$ the metric space whose underlying set is $\{0,1\}$ and whose metric is the discrete metric. Recall that every subset of $\mathbb{D}$ is open.

Theorem 04.4. A metric space $(X,d)$ is connected if and only if every continuous function $f : X \to \mathbb{D}$ is constant.

Proof. (⇒) Let $(X,d)$ be connected and $f:X\to\mathbb{D}$ be continuous. We must show that $f$ is constant. Let $A=f^{-1}[\{0\}]$ and $B=f^{-1}[\{1\}]$. Then $A$ and $B$ are open subsets of $X$ with $A\cap B=\emptyset$ and $X=A\cup B$. Since $X$ is connected, we must have $A=\emptyset$ or $B=\emptyset$. Say $A=\emptyset$. Then $X=B$, ie $f(x)=1$ for each $x\in X$, showing that $f$ is a constant function.

(⇐) Let $(X,d)$ be such that every continuous function $f : X \to \mathbb{D}$ is constant. We must show that $X$ is connected. Suppose not. Then there are two nonempty, disjoint open subsets $A$ and $B$ of $X$ such that $X = A \cup B$. Define a function $g : X \to \mathbb{D}$ by

$$
g \left( x \right) = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  x \in A } \\{ 1 , } & { \mathrm { i f }  x \in B . } \end{array} \right.
$$

Since $A \neq \emptyset$ and $B \neq \emptyset$, $g$ is not a constant function. The open subsets of $\mathbb{D}$ are $\emptyset$, $\{0\}$, $\{1\}$ and $\{0,1\}$ whose pre-images under $g$ are $\emptyset$, $A$, $B$ and $X$ respectively. Thus $g$ is continuous. We therefore have a contradiction. $\square$

Activity 04.1. (a) Prove Theorem 04.1 using Theorem 04.4 [Hint: Let $g : f[A] \to \mathbb{D}$ be continuous and define $h : A \to \mathbb{D}$ by $h(x) = g(f(x))$.]





(b) Let $f:[0,1]\to[0,1]$ be a continuous function. Show that there is a point $p\in[0,1]$ such that $f(p)=p$. [Hint: Consider the continuous function $f(x)-x$ and use the Intermediate-value Theorem.]

(c) Let $A,B\subseteq\mathbb{R}$, and suppose $A\times B$ is connected in $\mathbb{R}^2$. Prove that $A$ is connected. [Suggestion: Show first that the map $f:\mathbb{R}^2\to\mathbb{R}$ given by $f(x,y)=x$ is continuous.]

(d) Let $\{K_\alpha\mid\alpha\in\Gamma\}$ be a collection of nonempty connected subsets of a metric space such that $\bigcap_{\alpha\in\Gamma}K_\alpha\neq\emptyset$. Use Theorem 04.4 to show that $\bigcup_{\alpha\in\Gamma}K_\alpha$ is connected.

We will examine contraction mappings next.

# 05 CONTRACTION MAPPINGS

If $X$ is a set (not necessarily a metric space) and $f : X \to X$ is a function mapping $X$ into itself, we say an element $x_0 \in X$ is a fixed point of $f$ in case $f(x_0) = x_0$. In Activity 04.1(b) you proved (did you?) that every continuous function mapping $[0,1]$ into itself has a fixed point. The purpose of this section is to show that certain continuous functions always have fixed points.

Definition 05.1. Let $(X,d)$ be a metric space. A function $f : X \to X$ is called a contraction of $(X,d)$ if there is a real number $\lambda$ with $0 < \lambda < 1$ such that $d(f(x), f(y)) \leq \lambda \, d(x,y)$ for all $x,y \in X$.

It is obvious that every contraction is uniformly continuous. For a function $f : X \to X$ mapping a set $X$ into itself, let us define $f^2, f^3, \ldots, f^n, \ldots$ by $f^2(x) = f(f(x))$, $f^3(x) = f(f^2(x))$, etc. Thus $f^2$ is the composite of $f$ with itself, and so on.

Theorem 05.2. (Banach's Fixed Point Theorem). Let $(X,d)$ be a complete metric space and $T : X \to X$ be a contraction. Then $T$ has a unique fixed point.

Proof. Let $p$ be any point of $X$. We define a sequence $\{x_n\}$ of points of $X$ as follows:

$$
x _ { 0 } = p , \ x _ { 1 } = T ( x _ { 0 } ) , \ x _ { 2 } = T ( x _ { 1 } ) = T ^{2} ( x _ { 0 } ) , \ldots , x _ { n + 1 } = T ( x _ { n } ) = T ^{n + 1} ( x _ { 0 } ) .
$$

We claim that $\{x_n\}$ is a Cauchy sequence. To show this, let $\lambda$, with $0 < \lambda < 1$, be such that $d(T(x), T(y)) \leq \lambda \, d(x, y)$ for all $x, y \in X$. Note that for any $n \in \mathbb{N}$ we have

$$
d ( x _ { n + 1 } , x _ { n } ) \ = \ d ( T ( x _ { n } ) , T ( x _ { n - 1 } ) )
$$





$$
\begin{array}{rl} { \leq } & { \lambda \, d ( x _ { n } , x _ { n - 1 } ) } \\{ = } & { \lambda \, d ( T ( x _ { n - 1 } ) , T ( x _ { n - 2 } ) ) } \\{ \leq } & { \lambda ^{2} d ( x _ { n - 1 } , x _ { n - 2 } ) } \\& { \ldots } \\{ \leq } & { \lambda ^{n} d ( T ( x _ { 0 } ) , x _ { 0 } ) } \\{ = } & { \lambda ^{n} d ( x _ { 1 } , x _ { 0 } ) . } \end{array}
$$

Thus for $m,n\in\mathbb{N}$ with $m>n$, say, we have

$$
\begin{array}{rl} { d ( x _ { m } , x _ { n } ) } & { \leq  d ( x _ { n } , x _ { n + 1 } ) + d ( x _ { n + 1 } , x _ { n + 2 } ) + \cdots + d ( x _ { m - 1 } , x _ { m } ) } \\& { \leq  ( \lambda ^{n} + \lambda ^{n + 1} + \cdots + \lambda ^{m - 1} ) d ( x _ { 1 } , x _ { 0 } ) } \\& { =  \lambda ^{n} ( 1 + \lambda + \cdots + \lambda ^{m - n - 1} ) d ( x _ { 1 } , x _ { 0 } ) } \\& { <  \frac { \lambda ^{n} } { 1 - \lambda } d ( x _ { 1 } , x _ { 0 } ) } \end{array}
$$

since $\sum_{r=0}^{\infty}\lambda^{r}=\frac{1}{1-\lambda}$ as $0<\lambda<1$. Because

$$
\frac { \lambda ^{n} } { 1 - \lambda } d ( x _ { 1 } , x _ { 0 } ) \to 0 \; \; \mathrm { a s } \; \; n \to \infty \; \; ( \mathrm { s i n c e } \; \; 0 < \lambda < 1 ) ,
$$

it follows that given $\varepsilon > 0$ we can find $n_0 \in \mathbb{N}$ such that $\frac{\lambda^{n_0}}{1-\lambda}d(x_1, x_0) < \varepsilon$. Thus if $m, n \geq n_0$ we have $d(x_m, x_n) < \varepsilon$, as required. Since $(X, d)$ is complete there is a point $q \in X$ such that $x_n \to q$. Because $T$ is continuous, $T(q) = T(\lim\limits_{n} x_n) = \lim\limits_{n} x_{n+1} = q$. So $q$ is a fixed point of $T$.

We are left with showing that $q$ is the only fixed point of $T$. To this end, let $z$ be a fixed point of $T$. We must show that $z = q$. Now $T(z) = z$ and $T(q) = q$; so $d(z, q) = d(T(z), T(q)) \leq \lambda \, d(z, q)$. If $d(z, q) \neq 0$ we would get $1 \leq \lambda$, a contradiction. Hence $d(z, q) = 0$, whence $z = q$. $\square$

Example 05.1. We show that the condition $\lambda < 1$ is essential to ensure that a fixed point exists and that it is unique. That is, $\lambda = 1$ will not do.

(a) Let $f : \mathbb{R} \to \mathbb{R}$ be given by $f(x) = x$. Then $|f(x) - f(y)| = |x - y|$ for all $x, y \in \mathbb{R}$. Note that every point of $\mathbb{R}$ is a fixed point of $f$.

(b) Let $g : \mathbb{R} \to \mathbb{R}$ be given by $g(x) = x + 1$. Then $|g(x) - g(y)| = |x - y|$ for all $x, y \in \mathbb{R}$. However, $g$ has no fixed point since there is no $p \in \mathbb{R}$ such that $p = p + 1$.

Example 05.2. Let $T(x)=\frac{1}{2}\left(x+\frac{2}{x}\right)$.





(a) Verify that $T$ maps $[1,\infty)$ into $[1,\infty)$.

(b) Show that $T$ is a contraction on $[1,\infty)$

(c) Find the fixed point of $T$.

# Solution

(a) We must show that if $x \geq 1$, then $T(x) \geq 1$. Note that for any $x \in \mathbb{R}$

$$
\begin{array}{rl} { ( x - 1 ) ^{2} + 1 \geq 0 } & { \Rightarrow  x ^{2} - 2 x + 2 \geq 0 } \\& { \Rightarrow  \frac { x ^{2} - 2 x + 2 } { x } \geq 0 \mathrm { ~ i f ~ } x \geq 1 } \\& { \Rightarrow  \frac { x ^{2} + 2 } { x } - 2 \geq 0 } \\& { \Rightarrow  x + \frac { 2 } { x } \geq 2 } \\& { \Rightarrow  \frac { 1 } { 2 } \left( x + \frac { 2 } { x } \right) \geq 1 . } \end{array}
$$

So indeed for $x \geq 1$ we have $T(x) \geq 1$. How did we know that starting with $(x-1)^2 + 1 \geq 0$ would work? Actually we started with $T(x) \geq 1$ and worked backwards.

(b) By the Mean Value Theorem (from elementary calculus) we have

$$
| T ( x ) - T ( y ) | = | T ^{\prime} ( c ) | | x - y |
$$

where $c$ is some point between $x$ and $y$. Now if $x$ and $y$ are points in $[1,\infty)$ and $c$ is between $x$ and $y$, then

$$
\begin{array}{rl} { | T ^{\prime} ( c ) | } & { = \ \frac { 1 } { 2 } \bigg | 1 - \frac { 2 } { c ^{2} } \bigg | } \\& { \leq \ \frac { 1 } { 2 } } \end{array}
$$

since $|1-\frac{2}{c^2}|\leq1$ for every $c$ in $[1,\infty)$. Thus, if $x,y\in[1,\infty)$ we have

$$
| T ( x ) - T ( y ) | \leq \frac { 1 } { 2 } | x - y | .
$$

So $T$ is a contraction.





(c) To find the fixed point of $T$ we solve the equation

$$
T ( x ) = x , \ \ \mathrm { i e } \ \frac { 1 } { 2 } \left( x + \frac { 2 } { x } \right) = x
$$

to obtain $x=-\sqrt{2}$ or $\sqrt{2}$. Since we want a point in $[1,\infty)$, we conclude that the fixed point of $T$ is $\sqrt{2}$. Note that we know beforehand that $T$ has a fixed point in $[1,\infty)$ since $[1,\infty)$ is a closed subset of a complete metric space $\mathbb{R}$ and is therefore itself complete.

Activity 05.1. (a) Let $(X,d)$ be a complete metric space and $T : X \to X$ be a function such that $T^2$ is a contraction. Show that $T$ has a unique fixed point in $X$.

(b) Let $\alpha$ be a real number with $1 < \alpha < 2$. Put $f(x) = \frac{\alpha + x}{1 + x}$.

(i) Show that $f$ maps $[1,\infty)$ into $[1,\infty)$.

(ii) Show that $f$ is a contraction on $[1,\infty)$ and find its fixed point.

We have come to the end of Learning Unit 6. Before moving on to Learning Unit 7 on Function spaces, make sure you are familiar with all the concepts and are able to do the activities correctly.





# LEARNING UNIT 7

# FUNCTION SPACES

Demonstrate the concept of convergence of function spaces.

As the title suggests, in this chapter we shall be concerned with spaces the elements of which are functions. In the first section we show how a special metric can be defined on a set whose elements are bounded functions. We then explore briefly the completeness of such a space and indicate how a completion of a metric space can be constructed.

In subsequent sections we concentrate on sequences and series of functions.

# 01 SPACES OF BOUNDED FUNCTIONS

Recall that a subset $S$ of a metric space $(X,d)$ is bounded if there is a real number $M$ such that $d(x,y) \leq M$ for all $x,y \in S$. Now let $f : T \to X$ be a function mapping a set $T$ ($T$ does not have to be a metric space) into a metric space $(X,d)$. We shall say $f$ is bounded if the range $f[T]$ is a bounded subset of $X$. If $V$ is a subset of $T$, we also say $f$ is bounded on $V$ if $f[V]$ is bounded.

Definition 01.1. Let $Z$ be a nonempty set and $(X,d)$ be a metric space. We define the set $B(Z,X)$ by

$$
B ( Z , X ) = \{ f : Z \to X \mid f { \mathrm { ~ i s ~ b o u n d e d } } \} .
$$

Thus $B(Z,X)$ is the collection of all bounded functions that map the set $Z$ into the metric space $(X,d)$. We show how a metric, called the supremum metric, is defined on $B(Z,X)$.





Theorem 01.2. Let $Z$ be a nonempty set and $(X,d)$ be a metric space. Define

$$
d _ { \infty } : B ( Z , X ) \times B ( Z , X ) \to \mathbb { R } \ \ b y \ \ d _ { \infty } ( f , g ) = \operatorname* { s u p } \{ d ( f ( z ) , g ( z ) ) \mid z \in Z \} .
$$

Then $d_{\infty}$ is a metric on $B(Z,X)$ called the supremum metric.

Proof. First we must verify that indeed $d_{\infty}$ maps into $\mathbb{R}$; that is, $d_{\infty}(f,g)$ is a real number for each pair $f,g$ of bounded functions mapping $Z$ into $X$. To achieve this it suffices to show that the set

$$
A = \{ d ( f ( z ) , g ( z ) ) \mid z \in Z \}
$$

is bounded above. To this end, let $z_0$ be any point of $Z$. Given any arbitrary point $z$ in $Z$ we have

$$
d ( f ( z ) , g ( z ) ) \leq d ( f ( z ) , f ( z _ { 0 } ) ) + d ( f ( z _ { 0 } ) , g ( z _ { 0 } ) ) + d ( g ( z _ { 0 } ) , g ( z ) ) .
$$

Thus if $M$ and $N$ are real numbers with $d(f(x), f(y)) \leq M$ and $d(g(s), g(t)) \leq N$ for all $x, y, s$ and $t$ in $Z$; then

$$
d ( f ( z ) , g ( z ) ) \leq M + N + d ( f ( z _ { 0 } ) , g ( z _ { 0 } ) )
$$

for all $z \in Z$. Thus $A$ is bounded above.

Now check that $d_{\infty}(f,g)=0$ if and only if $f=g$; and that $d_{\infty}(f,g)\geq0$. Since

$$
d _ { \infty } ( f , g ) = d _ { \infty } ( g , f )
$$

easily, it remains to show that the triangle inequality holds. So let $f,g,h\in B(Z,X)$. For any $z\in Z$ we have

$$
\begin{array}{rlr} { d ( f ( z ) , g ( z ) ) } & { \leq } & { d ( f ( z ) , h ( z ) ) + d ( h ( z ) , g ( z ) ) } \\& { \leq } & { d _ { \infty } ( f , h ) + d _ { \infty } ( h , g ) . } \end{array}
$$

Taking suprema over all $z \in Z$ we obtain

$$
d _ { \infty } ( f , g ) \leq d _ { \infty } ( f , h ) + d _ { \infty } ( h , g ) .
$$

Now we specialise somewhat and look at $B(Z,X)$ where $Z$ is not merely a set, but in fact a metric space. Among bounded functions mapping $Z$ to $X$ are continuous ones. We





shall denote them by $C(Z,X)$; that is

$C(Z,X)=\{f:Z\to X\mid f\text{ is continuous and bounded}\}.$

Just to whet your appetite, in the next chapter we shall consider $C(Z,X)$ where $X$ will either be $\mathbb{R}$ or $\mathbb{C}$. This will allow us to define addition and multiplication on $C(Z,X)$.

Coming back to the discussion at hand, we show that $C(Z,X)$ is a closed subset of $B(Z,X)$, where the latter is endowed with the supremum metric.

Theorem 01.3. Let $(Z,\rho)$ and $(X,d)$ be metric spaces. Then $C(Z,X)$ is a closed subset of $B(Z,X)$.

Proof. Let $f \in B(Z,X)$ be in the closure of $C(Z,X)$. We show that $f \in C(Z,X)$, which will establish the result. Let $z_0$ be an arbitrary element of $Z$. Since $f \in \overline{C(Z,X)}$, given $\varepsilon > 0$, there is a function $g \in C(Z,X)$ such that

$$
d _ { \infty } ( f , g ) < \frac { \varepsilon } { 3 } .
$$

Consequently,

$$
d ( f ( z ) , g ( z ) ) < \frac { \varepsilon } { 3 }
$$

for every $z \in Z$. Since $g$ is continuous at $z_0$, there exists $\delta > 0$ such that

$$
d ( g ( z ) , g ( z _ { 0 } ) ) < \frac { \varepsilon } { 3 } \; \; \mathrm { w h e n e v e r } \; \; \rho ( z , z _ { 0 } ) < \delta .
$$

Thus, if $z$ is an element of $Z$ with $\rho(z,z_0) < \delta$, then

$$
\begin{array}{rl} { d ( f ( z ) , f ( z _ { 0 } ) ) } & { \leq  d ( f ( z ) , g ( z ) ) + d ( g ( z ) , g ( z _ { 0 } ) ) + d ( g ( z _ { 0 } ) , f ( z _ { 0 } ) ) } \\& { <  \frac { \varepsilon } { 3 } + \frac { \varepsilon } { 3 } + \frac { \varepsilon } { 3 } } \\& { =  \varepsilon . } \end{array}
$$

So $f$ is continuous at $z_0$, and hence on $Z$.

Next we show that if $(X,d)$ is a complete metric space, then $B(Z,X)$ is complete with respect to the supremum metric.

Theorem 01.4. Let $Z$ be any nonempty set and $(X,d)$ be a complete metric space. Then $B(Z,X)$ is complete.





Proof. Let $\{f_n\}$ be a Cauchy sequence in $B(Z,X)$. We must show that there is a function in $B(Z,X)$ to which this sequence converges. Let $\varepsilon > 0$ be given. Then there exists $n_0 \in \mathbb{N}$ such that $d_\infty(f_n,f_m) < \varepsilon$ whenever $m,n \geq n_0$. If $z \in Z$, then

$$
d ( f _ { n } ( z ) , f _ { m } ( z ) ) \leq d _ { \infty } ( f _ { n } , f _ { m } ) < \varepsilon
$$

for all $m,n \geq n_0$. This shows that $\{f_n(z)\}$ is a Cauchy sequence in $X$. Since $(X,d)$ is complete, the sequence $\{f_n(z)\}$ converges to some point of $X$ which we denote by $x_z$. As limits are unique, the relation

$$
f : Z \to X \ \ \mathrm { g i v e n ~ b y } \ \ f ( z ) = x _ { z }
$$

defines a function. We thus have a function $f: Z \to X$ such that $\lim\limits_{n} f_n(z) = f(z)$ for all $z \in Z$. We will show that $f \in B(Z, X)$ and that $f_n \to f$ in $B(Z, X)$.

To prove that $f_n \to f$, let $\varepsilon > 0$. Choose $n_0 \in \mathbb{N}$ such that

$$
m , n \geq n _ { 0 } \Rightarrow d _ { \infty } ( f _ { n } , f _ { m } ) < \frac { \varepsilon } { 4 } .
$$

This is possible since $\{f_n\}$ is a Cauchy sequence. Now take $k \geq n_0$ and $z \in Z$. Since $\lim f_n(z) = f(z)$, we can find $m \geq n_0$ such that

$$
d ( f _ { m } ( z ) , f ( z ) ) < \frac { \varepsilon } { 4 } .
$$

We then have

$$
\begin{aligned}d(f_{k}(z),f(z))&\leq d(f_{k}(z),f_{m}(z))+d(f_{m}(z),f(z))\\&\leq d_{\infty}(f_{k},f_{m})+d(f_{m}(z),f(z))\\&<\frac\varepsilon4+\frac\varepsilon4\\&=\frac\varepsilon2\end{aligned}
$$

As $z \in Z$ was chosen arbitrarily we conclude that

$$
d ( f _ { k } ( w ) , f ( w ) ) < \frac { \varepsilon } { 2 } \ \mathrm { f o r ~ a l l } \ w \in Z .
$$

Consequently

$$
d _ { \infty } ( f _ { k } , f ) = \operatorname* { s u p } \{ d ( f _ { k } ( w ) , f ( w ) ) \mid w \in Z \} \leq \frac { \varepsilon } { 2 } < \varepsilon .
$$

It therefore remains to show that $f$ is bounded. With $\varepsilon=1$ in the preceding argument,





choose $k \in \mathbb{N}$ such that

$$
d _ { \infty } ( f _ { k } , f ) < 1 .
$$

Since $f_k$ is bounded, there is a real number $M$ such that

$$
d ( f _ { k } ( s ) , f _ { k } ( t ) ) \leq M \; \; \mathrm { f o r ~ a l l } \; \; s , t \in Z .
$$

Now let $p,q\in Z$. Then

$$
\begin{array}{rl} { d ( f ( p ) , f ( q ) ) } & { \leq  d ( f ( p ) , f _ { k } ( p ) ) + d ( f _ { k } ( p ) , f _ { k } ( q ) ) + d ( f _ { k } ( q ) , f ( q ) ) } \\& { <  1 + M + 1 } \\& { =  M + 2 . } \end{array}
$$

So $f \in B(Z,X)$ and $\{f_n\}$ converges to $f$. So $B(Z,X)$ is complete.

Corollary 01.5. Let $(Z,\rho)$ and $(X,d)$ be metric spaces. The set $C(Z,X)$ of all bounded continuous functions mapping $Z$ to $X$ is complete with respect to the supremum metric.

Proof. Closed subsets of complete metric spaces are complete.

The result in the foregoing corollary will resurface under a different guise in the next chapter.

Let us now turn our attention to the completion. We start with a definition which isolates special kinds of uniformly continuous functions.

Definition 01.6. A function $f : (X,d) \to (Y,\rho)$ is said to be isometric if it preserves distances; that is, if $\rho(f(x), f(w)) = d(x,w)$ for all pairs of points $x, w$ in $X$. An isometric function which is onto is called an isometry. If there is an isometry $f : X \to Y$ we say $(X,d)$ is isometric to $(Y,\rho)$.

One checks easily that an isometric function is uniformly continuous and one-to-one. Thus if $f : (X,d) \to (Y,\rho)$ is an isometry, then it is one-to-one onto. In this case it can be checked easily that $f^{-1}:Y \to X$ is also an isometry. Consequently $X$ is isometric to $Y$ if and only if $Y$ is isometric to $X$. We can thus speak of two metric spaces that are isometric.

Let us examine closer what it means for two metric spaces to be isometric. If $X$ is isometric to $Y$, then the points of these metric spaces can be put into a one-to-one correspondence in such a way that the distances between pairs of corresponding points are the same. The spaces therefore differ only in nature (or names) of the points; and, from the point of view





of them being metric spaces, this is often not important. We can thus think of isometric metric spaces as being identical. Now suppose $f : X \to Y$ is an isometric function which is not necessarily onto. Then $f[X]$ is a (proper) subspace of $Y$, and $f$ viewed as a function $f : X \to f[X]$ is an isometry. Thus $X$ is isometric to a subspace of $Y$. In this case we say $X$ has been imbedded isometrically into $Y$. So, for all intents and purposes, we can think of $X$ as being a subspace of $Y$.

Theorem 01.7. Every metric space can be imbedded isometrically into a complete metric space.

Proof. Let $(X,d)$ be a metric space and, as above, $B(X,\mathbb{R})$ denote the set of all bounded functions mapping $X$ into $\mathbb{R}$. Choose and fix a point $x_0 \in X$. Given $a \in X$, define $T_a : X \to \mathbb{R}$ by

$$
T _ { a } ( x ) = d ( x , a ) - d ( x , x _ { 0 } ) .
$$

We claim that $T_{a}$ is bounded. From the following inequalities

$$
\begin{array}{rlr} { d ( x , a ) } & { \leq } & { d ( x , x _ { 0 } ) + d ( a , x _ { 0 } ) } \\{ d ( x , x _ { 0 } ) } & { \leq } & { d ( x , a ) + d ( a , x _ { 0 } ) } \end{array}
$$

we obtain

$$
- d ( a , x _ { 0 } ) \leq d ( x , a ) - d ( x , x _ { 0 } ) \leq d ( a , x _ { 0 } )
$$

which implies that

$$
| T _ { a } ( x ) | \leq d ( a , x _ { 0 } ) \ \ \mathrm { f o r ~ a l l } \ \ x \in X .
$$

So indeed $T_a$ is bounded. Now define a function $g : X \to B(X, \mathbb{R})$ by

$$
g ( a ) = T _ { a } \ \ \mathrm { f o r ~ e a c h } \ \ a \in X .
$$

We shall be done if we can show that $g$ is isometric because $B(X,\mathbb{R})$ is complete by Theorem 01.4 since $\mathbb{R}$ is complete. So let $a,b$ be any two points in $X$. We must show that

$$
d _ { \infty } ( T _ { a } , T _ { b } ) = d ( a , b ) .
$$





We have

$$
\begin{array}{rl} { d _ { \infty } ( T _ { a } , T _ { b } ) } & { = \ \operatorname* { s u p } \{ | T _ { a } ( x ) - T _ { b } ( x ) \ | \ : x \in X \} } \\& { = \ \operatorname* { s u p } \{ | d ( x , a ) - d ( x , b ) \ | \ : x \in X \} } \end{array}
$$

But now

$$
| d ( x , a ) - d ( x , b ) | \leq d ( a , b )
$$

as can be seen by applying the triangle inequality in the same way we did when showing $T_a$ to be bounded. As a consequence of all this we have

$$
d _ { \infty } ( T _ { a } , T _ { b } ) \leq d ( a , b ) .
$$

If we put $x=a$ in $|d(x,a)-d(x,b)|$ we get $d(a,b)$. This shows that $d(a,b)$ is an element of $\{|d(x,a)-d(x,b)|:x\in X\}$, which is also an upper bound for this set. Hence $d(a,b)$ is the supremum of this set; that is, $d(a,b)=d_{\infty}(T_a,T_b)$ as required. $\square$

Let $(X,d)$ be a metric space and $g:X\to B(X,\mathbb{R})$ be as in the proof of the above theorem. Then $\overline{g[X]}$ is complete being a closed subset of a complete metric space. We call $\overline{g[X]}$ the completion of $(X,d)$. In this course we do not pursue the discussion on completions beyond what we have so far.

Activity 01.1. (a) Show that an isometric function is uniformly continuous and one-to-one.

(b) Let $f : X \to Y$ be an isometry. Show that $f^{-1}$ is also an isometry.

(c) Show that composites of isometries are isometries.

We now move on to pointwise and uniform convergence.

# 02 POINTWISE AND UNIFORM CONVERGENCE

In certain branches of Mathematics (for instance in Complex Analysis) it is often desirable to know when a function defined as a series of functions has certain properties. In Complex Analysis for instance, one of the main results in the study of analytic functions is that a function is analytic if and only if it is locally representable as a power series. In this section we consider, among other things, questions of this nature.





Definition 02.1. Let $A$ be a nonempty set, $(X,d)$ be a metric space and, for each $n \in \mathbb{N}$, $f_n : A \to X$ be a function mapping $A$ to $X$. We say the sequence $\{f_n\}$ converges pointwise to a function $f : A \to X$ if, for each $x \in A$, the sequence $\{f_n(x)\}$ converges to $f(x)$. We then write $f_n \to f$ pointwise on $A$, and say $f$ is the pointwise limit of $\{f_n\}$ on $A$.

So if we have a sequence $\{f_n\}$ of functions and we want to check if $f_n \to f$ pointwise on A, we must check if for each given $a \in A$, $\lim\limits_{n} f_n(a) = f(a)$.

Example 02.1. For each $n \in \mathbb{N}$ let $f_n : \mathbb{R} \to \mathbb{R}$ be defined by

$$
f _ { n } ( x ) = { \frac { x ^{2} + n x } { n } } .
$$

Determine if $\{f_{n}\}$ converges pointwise to some function.

Solution: Let $a \in \mathbb{R}$. Then

$$
\begin{array}{rl} { \operatorname* { l i m } _ { n \to \infty } f _ { n } ( a ) } & { = \operatorname* { l i m } _ { n \to \infty } { \frac { a ^{2} + n a } { n } } } \\& { = \operatorname* { l i m } _ { n \to \infty } \left( a + { \frac { a ^{2} } { n } } \right) } \\& { = a . } \end{array}
$$

Thus if we define $f : \mathbb{R} \to \mathbb{R}$ by $f(x) = x$, we see that $f_n \to f$ pointwise on $\mathbb{R}$.

Example 02.2. For each $n \in \mathbb{N}$ define $f_n : [0,1] \to \mathbb{R}$ by

$$
f _ { n } ( x ) = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  x \geq \frac { 1 } { n } } \\{ - n x + 1 , } & { \mathrm { i f }  0 \leq x \leq \frac { 1 } { n } . } \end{array} \right.
$$

Let us determine if $\{f_n\}$ converges pointwise on $[0,1]$ and if so let us compute the pointwise limit.

Solution: The following diagram might assist to see how we should tackle the problem of computing $\lim_{n\to\infty}f_n(x)$ for a given $x\in[0,1]$.

<div style="display: block; width: 100%"><img src="https://storage.simpletex.cn/view/mbaa47bc55fe22f22cfca84250b2b067a" style="width: 24%; max-width: 24%" /></div>





If $x=0$, then $f_{n}(x)=f_{n}(0)=1$ for each $n$. Thus $f_{n}(0)\rightarrow1$. If $x\neq0$, then for $n_{0}$ large enough we have $f_{n_{0}}(x)=0$. Thus for all $n\geq n_{0}$ we have $f_{n}(x)=0$, and hence $f_{n}(x)\rightarrow0$. So $\{f_{n}\}$ does converge pointwise on $[0,1]$ and the pointwise limit is the function $f:[0,1]\rightarrow\mathbb{R}$ defined by

$$
f ( x ) = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  x \neq 0 } \\{ 1 , } & { \mathrm { i f }  x = 0 . } \end{array} \right.
$$

Notice that in Example 02.2 each function $f_n$ is continuous on $[0,1]$, but the pointwise limit is not continuous on $[0,1]$. Thus pointwise convergence has a "deficiency" from the point of view of preserving continuity. This deficiency is remedied by a stronger notion of convergence which we define next.

Definition 02.2. A sequence $\{f_n\}$ of functions mapping a set $A$ to a metric space $(X,d)$ converges uniformly to a function $f : A \to X$ on $A$ if for every $\varepsilon > 0$ there exists $n_0 \in \mathbb{N}$ such that $n \geq n_0$ implies

$$
d ( f _ { n } ( x ) , f ( x ) ) < \varepsilon \; \; \mathrm { f o r } \; \; e v e r y \; \; x \in A .
$$

In order to see the difference between pointwise and uniform convergence easily, let us restate the definition of pointwise convergence in the $\varepsilon - n_0$ language. A sequence $\{f_n\}$ converges pointwise to $f$ on $A$ if and only if given $\varepsilon > 0$ and given $x \in A$, there exists a natural number $n_0$, depending on $\varepsilon$ and $x$, such that $d(f_n(x), f(x)) < \varepsilon$ if $n \geq n_0$. So, given $\varepsilon$, each point of $A$ has its own $n_0$ that works. In the case of uniform convergence, given $\varepsilon > 0$ we can find $n_0$ that works for all the points of $A$. This is reminiscent of the difference between continuity and uniform continuity. Clearly, uniform convergence implies pointwise convergence.

A basic property of uniform convergence is its connection with continuity as illustrated in the following theorem.

Theorem 02.3. Let $(X,d)$ and $(Y,\rho)$ be metric spaces. Let $\{f_n\}$ be a sequence of functions mapping $X$ to $Y$. If each function $f_n$ is continuous on $A \subseteq X$ and $\{f_n\}$ converges uniformly on $A$ to a function $f : X \to Y$, then $f$ is continuous on $A$.

Proof. We shall show that $f$ is continuous at each point of $A$. So let $p \in A$. Given $\varepsilon > 0$, we can find $n_0 \in \mathbb{N}$ such that if $n \geq n_0$ then

$$
\rho ( f _ { n } ( x ) , f ( x ) ) < \frac { \varepsilon } { 3 }
$$





for every $x \in A$. This is so since $\{f_n\}$ converges uniformly to $f$ on $A$. Now $f_{n_0}$ is continuous at $p$ by the hypothesis. Thus there exists $\delta > 0$ such that if $x \in A$ and $d(x,p) < \delta$, then

$$
\rho ( f _ { n _ { 0 } } ( x ) , f ( p ) ) < \frac { \varepsilon } { 3 } .
$$

Consequently, if $x \in A$ and $d(x,p) < \delta$, then

$$
\begin{array}{rlr} { \rho ( f ( x ) , f ( p ) ) } & { \leq } & { \rho ( f ( x ) , f _ { n _ { 0 } } ( x ) ) + \rho ( f _ { n _ { 0 } } ( x ) , f _ { n _ { 0 } } ( p ) ) + \rho ( f _ { n _ { 0 } } ( p ) , f ( p ) ) } \\& { < } & { \frac { \varepsilon } { 3 } + \frac { \varepsilon } { 3 } + \frac { \varepsilon } { 3 } } \\& { = } & { \varepsilon . } \end{array}
$$

As $p$ is an arbitrary point of $A$, we have that $f$ is continuous on $A$.

Caution: If the pointwise limit of a sequence of continuous functions is continuous, it does not follow that the convergence is uniform. However if the pointwise limit of a sequence of continuous functions is not continuous, then the convergence is certainly not uniform.

Example 02.3. The sequence of functions in Example 02.2 does not converge uniformly because each function in the sequence is continuous but the pointwise limit is not continuous.

Example 02.4. Consider the sequence given in Example 02.1. Clearly $f_n$ is continuous and the pointwise limit $f$ is also continuous. We show that the convergence is not uniform by exhibiting an $\varepsilon > 0$ for which there is no $n_0$ that works. Take $\varepsilon = \frac{1}{2}$. Suppose there does exist $n_0 \in \mathbb{N}$ such that $|f_k(x) - f(x)| < \frac{1}{2}$ for every $k \geq n_0$ and every $x \in \mathbb{R}$. Choosing $k = n_0$ and $x = n_0$ we get

$$
\begin{array}{rl} { | f _ { n _ { 0 } } ( n _ { 0 } ) - f ( n _ { 0 } ) | } & { = \left| \frac { n _ { 0 } ^{2} + n _ { 0 } \cdot n _ { 0 } } { n _ { 0 } } - n _ { 0 } \right| } \\& { = \left| \begin{array}{c} { n _ { 0 } } \\{ n _ { 0 } } \end{array} \right| } \\& { \not \prec \frac { 1 } { 2 } . } \end{array}
$$

Showing that a sequence $\{f_n\}$ does not converge pointwise to a function $f$ is quite easy. Simply produce a point $x_0$ for which $f(x_0) \neq \lim\limits_{n} f_n(x_0)$. On the other hand, showing that a sequence of functions does not converge uniformly involves a little more sweat. The following criterion, which is simply the negation of the statement in the definition, is frequently useful.

Theorem 02.4. A sequence $\{f_n\}$ does not converge uniformly on a set $E$ to $f$ if and only





if for some $\varepsilon_0 > 0$ there are integers $n_1 < n_2 < \ldots$ and points $x_1, x_2, \ldots$ in $E$ such that

$$
d ( f _ { n _ { k } } ( x _ { k } ) , f ( x _ { k } ) ) \geq \varepsilon _ { 0 } \; \; \mathrm { f o r } \; e v e r y \; \; k = 1 , 2 , \ldots
$$

Proof. Activity.

Example 02.5. Define $f_n : (0,1) \to \mathbb{R}$ by $f_n(x) = x^n$. We show that $\{f_n\}$ converges pointwise but not uniformly. Indeed, for any $x$ with $0 < x < 1$ we have $x^n \to 0$ as $n \to \infty$. Thus $f_n \to f$ pointwise where $f(x) = 0$ for all $x \in (0,1)$. Now if the sequence did converge uniformly then it would converge to the pointwise limit. We use Theorem 02.4 to show that this is not the case. For each $k \in \mathbb{N}$ let $n_k = k$ and $x_k = \left(\frac{1}{2}\right)^{\frac{1}{k}}$. Then

$$
| f _ { n _ { k } } ( x _ { k } ) - f ( x _ { k } ) | = \frac { 1 } { 2 } \mathrm { ~ f o r ~ e a c h ~ } k .
$$

Thus $\{f_{n}\}$ does not converge uniformly on $(0,1)$.

If a sequence of functions is such that the co-domain of the functions is a complete metric space, then there is a criterion for uniform convergence which does not require that we know the limit function. In order to prove this let us first note the following fact.

Lemma 02.1. Let $\{x_n\}$ be a sequence in a metric space $(X,d)$ such that $x_n \to p$. Suppose $q$ is a point in $X$ and $r$ is a real number such that for some $n_0 \in \mathbb{N}$, $d(x_n,q) \leq r$ for all $n \geq n_0$. Then $d(p,q) \leq r$.

Proof. The set $U = \{x \in X \mid d(x,q) > r\}$ is open. (Verify this.) If we assume that $d(p,q) > r$, then $p \in U$. Since $U$ is open, $B(p,\delta) \subseteq U$ for some $\delta > 0$. Since $x_n \to p$, there exists an integer $n_1$ such that if $n \geq n_1$ then $d(x_n,p) < \delta$; so that $x_n \in B(p,\delta) \subseteq U$ and hence $d(x_n,q) > r$. Now let $k = \max\{n_0,n_1\}$. Then $k \geq n_0$ and $k \geq n_1$. Thus we have $d(x_k,q) \leq r$ and $d(x_k,q) > r$, which is impossible. So the assumption that $d(p,q) > r$ is untenable; hence $d(p,q) \leq r$. $\square$

Theorem 02.5. (Cauchy Criterion for Uniform Convergence) Let $\{f_n\}$ be a sequence of functions mapping a set $E$ into a complete metric space $(X,d)$. Then the sequence $\{f_n\}$ converges uniformly on $E$ if and only if for every $\varepsilon > 0$ there is a natural number $n_0$ such that whenever $m, n \geq n_0$ then $d(f_n(x), f_m(x)) < \varepsilon$ for all $x \in E$.

Proof. (⇒) Suppose $\{f_n\}$ converges uniformly on $E$, and let $f$ be the limit function. Then, given $\varepsilon > 0$, there exists $n_0 \in \mathbb{N}$ such that if $m, n \geq n_0$ then

$$
d ( f _ { m } ( x ) , f _ { n } ( x ) ) < \frac { \varepsilon } { 2 }
$$





for every $x \in E$. Consequently, if $m, n \geq n_0$ then

$$
\begin{array}{rlr} { d ( f _ { n } ( x ) , f _ { m } ( x ) ) } & { \leq } & { d ( f _ { n } ( x ) , f ( x ) ) + d ( f ( x ) , f _ { m } ( x ) ) } \\& { < } & { \frac { \varepsilon } { 2 } + \frac { \varepsilon } { 2 } } \\& { = } & { \varepsilon , } \end{array}
$$

for every $x \in E$.

(⇐) Suppose the stated condition holds. Given any point $x \in E$, the sequence $\{f_n(x)\}$ is a Cauchy sequence in $(X,d)$ and therefore converges since $(X,d)$ is complete. Define $f : E \to X$ by

$$
f ( x ) = \operatorname* { l i m } _ { n } f _ { n } ( x )
$$

for each $x \in E$. We claim that $\{f_n\}$ converges uniformly on $E$ to $f$. To show this let $\varepsilon > 0$ be given. By the hypothesis we can find $n_0 \in \mathbb{N}$ such that

$$
m , n \geq n _ { 0 } \Rightarrow d ( f _ { m } ( x ) , f _ { n } ( x ) ) < \frac { \varepsilon } { 4 }
$$

for each $x \in E$. We will show that this $n_0$ satisfies the requirements in the definition of uniform convergence. So let $k \geq n_0$ and $p \in E$. We must show that $d(f_k(p), f(p)) < \varepsilon$. Since

$$
f _ { n } ( p ) \rightarrow f ( p ) \; \; \mathrm { a n d } \; \; d ( f _ { m } ( p ) , f _ { n _ { 0 } } ( p ) ) < \frac { \varepsilon } { 4 } \leq \frac { \varepsilon } { 3 }
$$

for each $m \geq n_0$, we deduce from Lemma 02.10 that

$$
d ( f _ { n _ { 0 } } ( p ) , f ( p ) ) \leq \frac { \varepsilon } { 3 } .
$$

Now

$$
\begin{array}{rlr} { d ( f _ { k } ( p ) , f ( p ) ) } & { \leq } & { d ( f _ { k } ( p ) , f _ { n _ { 0 } } ( p ) ) + d ( f _ { n _ { 0 } } ( p ) , f ( p ) ) } \\& { \leq } & { \frac { \varepsilon } { 4 } + \frac { \varepsilon } { 3 } } \\& { < } & { \varepsilon ; } \end{array}
$$

so we are done.

Because $\mathbb{R}$ and $\mathbb{C}$ are complete, the above criterion can be used on functions that map into $\mathbb{R}$ or $\mathbb{C}$.

In the case of bounded functions, we show that uniform convergence coincides with convergence in the supremum metric.





Theorem 02.6. Let $E$ be a nonempty set, $(X,d)$ be a metric space and, for each $n \in \mathbb{N}$, $f_n : E \to X$ be a bounded function mapping $E$ to $X$. Then the sequence $\{f_n\}$ converges uniformly on $E$ if and only if $f_n \to f$ in $B(E,X)$.

Proof. $(\Rightarrow)$ Let $\varepsilon > 0$ be given. By uniform convergence we can find a positive integer $n_0$ such that

$$
n \geq n _ { 0 } \Rightarrow d ( f _ { n } ( x ) , f ( x ) ) < \frac { \varepsilon } { 2 }
$$

for each $x \in E$. Thus, for $n \geq n_0$ we have

$$
\operatorname* { s u p } \{ d ( f _ { n } ( x ) , f ( x ) ) \mid x \in E \} \leq \frac { \varepsilon } { 2 } < \varepsilon ,
$$

that is we have

$$
d _ { \infty } ( f _ { n } , f ) < \varepsilon .
$$

So $f_{n} \rightarrow f$ in $B(E,X)$.

# ( $\leftarrow$ ) Activity.

Let us note that if the functions map into $\mathbb{R}$ (or $\mathbb{C}$) and they are bounded, then putting

$$
M _ { n } = \operatorname* { s u p } \{ | f _ { n } ( x ) - f ( x ) | : \ x \in E \}
$$

we have that $\{f_n\}$ converges uniformly on $E$ to $f$ if and only if $M_n \to 0$ as $n \to \infty$.

Example 02.6. Consider again the sequence of function given in Example 02.1. We saw in Example 02.4 that the sequence does not converge uniformly on $\mathbb{R}$. Now let $M$ be a real number with $M > 0$. We show that the sequence converges uniformly on $[0, M]$. Note that since each $f_n$ is continuous on $[0, M]$ and $[0, M]$ is compact, then each $f_n$ is bounded on $[0, M]$. Now

$$
\begin{array}{rl} { M _ { n } } & { = \operatorname* { s u p } \{ | f _ { n } ( x ) - f ( x ) | : \ 0 \leq x \leq M \} } \\& { = \operatorname* { s u p } \left\{ \frac { x ^{2} } { n } \bigg | \ 0 \leq x \leq M \right\} } \\& { = \ \frac { M ^{2} } { n } \rightarrow 0 \ \mathrm { a s } \ n \rightarrow \infty . } \end{array}
$$

Thus $\{f_{n}\}$ converges uniformly on $[0,M]$.





Example 02.7. Define $f_n:[0,\infty)\to\mathbb{R}$ by $f_n(x)=\frac{x^2}{e^{nx}}$. Let us determine whether $\{f_n\}$ converges uniformly on $[0,\infty)$. For a given $x\in[0,\infty)$, $\lim\limits_{n\to\infty}\frac{x^2}{e^{nx}}=0$. So if $\{f_n\}$ is to converge uniformly, it will converge to the zero function; that is, the function $f:[0,\infty)\to\mathbb{R}$ given by $f(x)=0$ for all $x\geq0$. Let us check if the functions $f_n$ are bounded, so that if they are we may use Theorem 02.6. First we note that $f_n(0)=0$, $f_n(x)\geq0$ for each $x\geq0$ and $f_n(x)\to0$. So the graph of $f_n(x)$ looks like this:

<div style="display: block; width: 100%"><img src="https://storage.simpletex.cn/view/mab39825325f26e1d65d40d9c69e590c6" style="width: 28%; max-width: 28%" /></div>

By elementary Calculus, $f_{n}$ is bounded and attains its maximum value at the point $x_{0}$ for which $f_{n}^{r}(x_{0})=0$. Put

$$
\begin{array}{rlr} { M _ { n } } & { = } & { \operatorname* { s u p } \{ | f _ { n } ( x ) - 0 | : \ x \geq 0 \} } \\& { = } & { \operatorname* { s u p } \{ f _ { n } ( x ) : \ x \geq 0 \} . } \end{array}
$$

To obtain $M_{n}$ we differentiate $f_{n}$ to obtain

$$
\begin{array}{rl} { f _ { n } ^{\prime} ( x ) } & { = \ \frac { x ( 2 - n x ) } { e ^{n x} } } \\& { = \ 0 \ \mathrm { i f f } \ x = 0 \ \mathrm { o r } \ \frac { 2 } { n } . } \end{array}
$$

Now $f_{n}(0)=0$ and $f_{n}\left(\frac{2}{n}\right)=\frac{4e^{-2}}{n^{2}}$.

Therefore $M_{n}=\frac{4e^{-2}}{n^{2}}$, which tends to zero as $n\rightarrow\infty$. Hence $\{f_{n}\}$ converges uniformly on $[0,\infty)$ to 0.

Next we turn our attention to series of functions. Let $\mathbb{F}$ denote either $\mathbb{R}$ or $\mathbb{C}$ without specifying which.

Definition 02.7. Let $E$ be a nonempty set and, for each $n \in \mathbb{N}$, $g_n : E \to \mathbb{F}$ be a function mapping $E$ to $\mathbb{F}$. For $k \in \mathbb{N}$ let $s_k : E \to \mathbb{F}$ be the $k$-th partial sum defined by $s_k(x) = \sum_{i=1}^k g_i(x)$. We say the series $\sum_{n=1}^{\infty} g_n$ converges pointwise on $E$ to a function $g$, and write $\sum_{n=1}^{\infty} g_n = g$ pointwise on $E$, in case the sequence $\{s_n\}$ converges pointwise





to $g$. We say the series $\sum_{n=1}^{\infty} g_{n}$ converges uniformly on $E$ to a function $g$, and write $\sum_{n=1}^{\infty} g_{n} = g$ uniformly on $E$, in case the sequence $\{s_{n}\}$ converges uniformly on $E$ to $g$.

The Cauchy criterion for uniform convergence of sequences of function has an obvious extension to series of functions. We state this result without proof and leave the proof as an exercise.

Theorem 02.8. (Cauchy Criterion for Uniform Convergence of Series) The series $\sum_{n=1}^{\infty} f_{n}$ converges uniformly on $E$ if and only if for every $\varepsilon > 0$ there exists $n_{0} \in \mathbb{N}$ such that $n \geq n_{0}$ implies

$$
\left| \sum _ { k = n + 1 } ^{n + p} f _ { k } ( x ) \right| < \varepsilon
$$

for each $p=1,2,\ldots$ and every $x\in E$.

Proof. Apply Theorem 02.5 to the sequence of partial sums.

Next we prove a useful test for uniform convergence of series of functions.

Theorem 02.9. (Weierstrass M-test) Let $\{f_n\}$ be a sequence of functions mapping a nonempty set $E$ into $\mathbb{F}$. Suppose that for each $n \in \mathbb{N}$ there is a nonnegative real number $M_n$ such that $|f_n(x)| \leq M_n$ for every $x \in E$. If the series $\sum_{n=1}^{\infty} M_n$ converges, then the series $\sum_{n=1}^{\infty} f_n$ converges uniformly on $E$.

Proof. Let $\varepsilon > 0$. By Theorem 02.8 it suffices to find $n_0 \in \mathbb{N}$ such that $n \geq n_0$ implies

$$
\left| \sum _ { k = n } ^{n + p} f _ { k } ( x ) \right| < \varepsilon
$$

for every $x \in E$. Since $\sum M_n$ converges, the sequence $\{b_n\}$ of partial sums

$$
b _ { 1 } = M _ { 1 } , \ldots , \ \ b _ { n } = M _ { 1 } + \ldots + M _ { n } , \ldots ,
$$

converges, and is therefore a Cauchy sequence. So, for the given $\varepsilon > 0$, we can find $n_0 \in \mathbb{N}$ such that if $m, n \geq n_0$ then

$$
| b _ { m } - b _ { n } | < \varepsilon .
$$





Thus if $n \geq n_{0}$ and $p=1,2,\ldots$ we have

$$
| b _ { n } - b _ { n + p } | < \varepsilon .
$$

But now

$$
| b _ { n } - b _ { n + p } | = M _ { n + 1 } + M _ { n + 2 } + \ldots + M _ { n + p } .
$$

So, if $n \geq n_0$ and $x \in E$ we have

$$
\left| \sum _ { k = n + 1 } ^{n + p} f _ { k } ( x ) \right| \leq \sum _ { k = 1 } ^{n + p} M _ { k } < \varepsilon .
$$

The result then follows from Theorem 02.8.

Caution: A common error is that, given a series $\sum f_{n}(x)$, one finds constants $M_{n} \geq 0$ such that $|f_{n}(x)| \leq M_{n}$ for each $x$ but $\sum M_{n}$ diverges, and then incorrectly concludes that the series $\sum f_{n}(x)$ does not converge uniformly. This is false. All the M-test says is that if we can find bounds $M_{n}$ and $\sum M_{n} < \infty$, then we know that $\sum f_{n}(x)$ converges uniformly. The examples below should clarify this further.

Example 02.8. Consider the complex series $\sum_{n=1}^{\infty}\frac{z^{n}}{n^{2}}$ for $z\in\mathbb{C}$ with $|z|\leq1$. Let us check if the series converges. For each $n\in\mathbb{N}$, $|z^{n}|\leq1$ for every $z\in\mathbb{C}$ with $|z|\leq1$. Thus

$$
\left| { \frac { z ^{n} } { n ^{2} } } \right| \leq { \frac { 1 } { n ^{2} } }
$$

for every $z \in \mathbb{C}$ with $|z| \leq 1$. Since $\sum \frac{1}{n^2} < \infty$, the Weierstrass M-test applies. Thus $\sum \frac{\infty}{n^2} \frac{z^n}{n^2}$ converges uniformly on $\{z \in \mathbb{C} : |z| = 1\}$.

Example 02.9. Let us now consider the series $\sum_{n=1}^{\infty} \frac{z^{n-1}}{n}$. The Weierstrass does not apply on $\{z \in \mathbb{C} : |z| = 1\}$. If however $r$ is a real number with $0 < r < 1$ and $D = \{z \in \mathbb{C} : |z| \leq r\}$, then, for each $n \in \mathbb{N}$, we have

$$
\left| { \frac { z ^{n - 1} } { n } } \right| \leq r ^{n - 1}
$$

for every $z \in D$. Now $\sum_{n=1}^{\infty} r^{n-1}$ converges. So $\sum_{n=1}^{\infty} \frac{z^{n-1}}{n}$ converges uniformly on $D$. Incidentally, note that the series $\sum \frac{z^{n-1}}{n}$ consists of derivatives of the terms of the series $\sum \frac{z^{n}}{n}$.





We remark that there are other tests for uniform convergence of series apart from the Weierstrass M-test. We shall however not discuss them.

In closing, we show that a uniformly convergent series of continuous functions defines a continuous function.

Theorem 02.10. Let $(X,d)$ be a metric space and $\{f_n\}$ be a sequence of functions mapping $X$ to $\mathbb{F}$. (Recall: $\mathbb{F}=\mathbb{R}$ or $\mathbb{C}$). Suppose $\sum_{n=1}^{n}f_n=f$ uniformly on $E\subseteq X$. If each $f_n$ is continuous on $E$, then $f$ is continuous on $E$.

Proof. Clearly each partial sum $s_n$ is continuous on $E$. Thus $\{s_n\}$ is a sequence of continuous functions that converges uniformly on $E$ to the function $f$. Therefore by Theorem 02.3 the result follows. $\square$

Example 02.10. Every polynomial is continuous on $\mathbb{C}$. Thus the function $f$ given by $f(x)=\sum_{n=1}^{\infty}\frac{z^{n}}{n^{2}}$ is continuous on $\{z\in\mathbb{C}:|z|\leq1\}$, in view of Example 02.8.

Activity 02.1. (a) For each of the following functions, test whether the given sequences of functions are pointwise convergent and if they are uniformly convergent on the indicated domains.

(i) $f_{n}(x)=\frac{x^{n}}{n+x^{n}}$; $x\geq0$.

(ii) $f_{n}(x)=\frac{e^{-x^{2}/n}}{n}$; $x\in\mathbb{R}$.

(iii) $f_{n}(x)=\left(x-\frac{1}{n}\right)^{2}$; $0\leq x\leq1$.

(iv) $f_{n}(x)=x-x^{n}$; $0\leq x\leq1$.

(v) $f_{n}(x)=n^{3}x^{n}(1-x)$; $0\leq x\leq1$.

(vi) $f_{n}(x)=\frac{x^{2n}}{1+x^{2n}}$; $x\in\mathbb{R}$.

(b) Test the following series for uniform convergence.

(i) $\sum_{n=1}^{\infty} \frac{x^{n}}{n+x^{n}}$ on $[0,\infty)$.

(ii) $\sum_{n=1}^{\infty} a_{n} \cos n x$ on $\mathbb{R}$, given that $\sum a_{n}$ converges absolutely.

(c) Let $(X,d)$ and $(Y,\rho)$ be metric spaces and $\{f_n\}$ be a sequence of functions mapping $X$ to $Y$. Let $E \subseteq X$ and suppose each $f_n$ is continuous on $E$ and that $\{f_n\}$ converges uniformly on $E$ to a function $f$. Let $\{p_n\}$ be a sequence in $E$ and $p$ be a point in $E$ such that $p_n \to p$. Show that $\lim\limits_{n} f_n(p_n) = f(p)$.





(d) Let $\{f_n\}$ be a sequence of functions $f_n : E \to \mathbb{F}$. Suppose $\{f_n\}$ converges uniformly on $E$ to a function $f$. Show that if each function $f_n$ is bounded on $E$, then there is a real number $M > 0$ such that $|f_k(x)| \leq M$ for all $k \in \mathbb{N}$ and all $x \in E$.

(e) Let $\{f_{n}\}$ and $\{g_{n}\}$ be two sequences defined as follows:

$$
\begin{array}{r} { f _ { n } ( x ) = x \left( 1 + \frac { 1 } { n } \right) } \\{ g _ { n } \left( x \right) = \left\{ \begin{array}{ll} { \frac { 1 } { n } , } & { \mathrm { i f }  x = 0 \mathrm { ~ o r ~ } x \mathrm { ~ i s ~ i r r a t i o n a l } } \\{ b + \frac { 1 } { n } , } & { \mathrm { i f }  x \mathrm { ~ i s ~ r a t i o n a l , ~ s a y ~ } x = \frac { a } { b } \mathrm { ~ w i t h ~ } b > 0 } \\& { \mathrm { a n d ~ } a \mathrm { ~ a n d ~ } b \mathrm { ~ h a v i n g ~ n o ~ c o m m o n ~ f a c t o r } . } \end{array} \right. } \end{array}
$$

Let $h_{n}(x)=f_{n}(x)g_{n}(x)$. Show that

(i) both $\{f_{n}\}$ and $\{g_{n}\}$ converge uniformly on every bounded interval.

(ii) $\{h_{n}\}$ does not converge uniformly on any bounded interval.

An elaboration of miscellaneous examples are given next.

# 03 MISCELLANEOUS EXAMPLES

Before we bid this learning unit farewell, we give a few examples covering the scope of the chapter.

Example 03.1. Let $C = \{f : [0,1] \to \mathbb{R} \mid f \text{ is continuous}\}$. Then of course $C \subseteq B([0,1],\mathbb{R})$ since continuous functions on a compact set are bounded. Now let $C_0 = \{f \in C \mid f(x) > 0 \text{ for all } x \in [0,1]\}$. We show that $C_0$ is an open subset of $C([0,1],\mathbb{R})$ in the supremum metric. Let $f \in C_0$. We will produce a ball $B(f,\varepsilon)$ in $B([0,1],\mathbb{R})$ such that $B(f,\varepsilon) \cap C \subseteq C_0$. Since $[0,1]$ is compact and $f$ is continuous on $[0,1]$, $f$ has a minimum value at some point of $[0,1]$. That is, there is a point $p \in [0,1]$ such that

$$
f ( x ) \geq f ( p ) > 0
$$

for all $x \in [0,1]$. Put $\varepsilon = \frac{f(p)}{2}$. Now if $g \in C([0,1],\mathbb{R})$ is such that $d_{\infty}(f,g) < \varepsilon$, then for any $x \in [0,1]$ we have

$$
| f ( x ) - g ( x ) | < \varepsilon = \frac { f ( p ) } { 2 } .
$$





Consequently

$$
- { \frac { f ( p ) } { 2 } } < f ( x ) - g ( x ) < { \frac { f ( p ) } { 2 } }
$$

which implies that

$$
\begin{array}{rl} { g ( x ) } & { \geq  f ( p ) - \frac { f ( p ) } { 2 } } \\& { =  \frac { f ( p ) } { 2 } } \\& { >  0 . } \end{array}
$$

So $g \in C_0$. This shows that $B(f,\varepsilon) \cap C([0,1],\mathbb{R}) \subseteq C$, as required.

Example 03.2. With reference to Example 03.1, regard $C$ as a metric space with metric $d_{\infty}$ given by

$$
d _ { \infty } ( f , g ) = \operatorname* { s u p } \{ | f ( x ) - g ( x ) | : x \in [ 0 , 1 ] \} .
$$

In other words regard $C$ as a subspace of $B([0,1],\mathbb{R})$. Now we show that the closure of

$$
C _ { 0 } = \{ f \in C \mid f ( x ) > 0 \}
$$

in the space $(C,d_{\infty})$ is

$$
D = \{ f \in C \mid f ( x ) \geq 0 \} .
$$

This is how we will do it: First we shall show that $D$ is a closed set in $C$, and secondly we will show that if $f$ is any point in $D$, then there is a sequence $\{f_n\}$ in $C_0$ which converges to $f$. Now why will this prove that $\overline{C_0} = D$? Well, notice that if $g \in C_0$, then $g(x) > 0$ for each $x \in [0,1]$. Hence $g(x) \geq 0$ for each $x \in [0,1]$, implying that $C_0 \subseteq D$. Thus, if $D$ is closed, then $\overline{C_0} \subseteq D$ since the closure of a set is the smallest closed set containing the set. On the other hand, if for each $f \in D$ there is a sequence in $C_0$ converging to $f$, then $D \subseteq \overline{C_0}$.





Now to show that $D$ is closed, we show that $D$ contains all its adherent points. Then let $f$ be an adherent point of $D$. Find a sequence $\{f_n\}$ in $D$ such that $f_n \to f$ (where this convergence is with respect to the supremum metric). Now by Theorem 02.6 we have that $\{f_n\}$ converges to $f$ uniformly on $[0,1]$. Hence $\{f_n\}$ converges to $f$ pointwise on $f$. But $f_n(x) \geq 0$ for each $n$ and each $x \in [0,1]$; so $f(x) \geq 0$ for each $x \in [0,1]$. This is so since a sequence of nonnegative reals cannot converge to a negative number. Thus $f \in D$ as required.

Next let $g \in D$. For each $n \in \mathbb{N}$ define $f_n : [0,1] \to \mathbb{R}$ by

$$
f _ { n } ( x ) = f ( x ) + { \frac { 1 } { n } } .
$$

Then $f_{n} \in C_{0}$ for each $n$ and $\{f_{n}\}$ converges to $g$ uniformly on $[0,1]$. We are therefore done.

Example 03.3. $\mathbb{C}$ is isometric to $\mathbb{R}^2$. Recall that the usual metric on $\mathbb{C}$ is given by $d(z,w)=|z-w|$, where the mod of a complex number $\alpha+i\beta$ is $|\alpha+i\beta|=\sqrt{\alpha^2+\beta^2}$. Also recall that the usual metric on $\mathbb{R}^2$ is given by $\rho((a,b),(c,d))=\sqrt{(a-c)^2+(b-d)^2}$. So we must exhibit an isometry

$$
T : \mathbb { C } \to \mathbb { R } ^{2}
$$

such that $\rho(T(z),T(w))=d(z,w)$ for all $z,w\in\mathbb{C}$. Define $T$ by

$$
T ( z ) = ( \mathrm { R e } ( z ) , \mathrm { I m } ( z ) )
$$

for each $z \in \mathbb{C}$. It is routine to check that $T$ is an isometry. So, as we remarked earlier, the complex plane $\mathbb{C}$ and the Euclidean plane $\mathbb{R}^2$ are, as metric spaces, essentially the same.

Example 03.4. Let $(X,d)$ be a compact metric space and $\{f_n\}$ be a sequence of continuous functions $f_n : X \to \mathbb{R}$ such that:

(a) $f_{n}(x) > 0$ for each $x \in X$ and each $n$.

(b) $f_{n} \to 0$ pointwise on $X$.

(c) $f_{k}(x) \leq f_{\ell}(x)$ for each $x \in X$ and all $k \geq \ell$ (ie given $x \in X$, the sequence $\{f_{n}(x)\}$ decreases).

Then $f_{n} \rightarrow 0$ uniformly on $X$. To prove this let $\varepsilon > 0$ be given. We must produce $n_{0} \in \mathbb{N}$ such that if $n \geq n_{0}$ and $x \in X$, then $|f_{n}(x)| < \varepsilon$. For each $a \in X$, since $f_{n}(a) \rightarrow 0$,





there exists a positive integer $n(a)$ such that $|f_k(a)| < \frac{\varepsilon}{2}$ whenever $k \geq n(a)$. Since $f_m$ is continuous at $a$, there is an open ball centered at $a$, call it $B_{a,m}$, such that

$$
| f _ { m } ( y ) - f _ { m } ( a ) | < \frac { \varepsilon } { 2 }
$$

for all $y \in B_{a,m}$. The balls $B_{a,n(a)}$ (for $a \in X$) form an open cover of $X$. Since $X$ is compact, there are finitely many of these balls, say centered at $x_1, x_2, \ldots, x_\ell$, such that

$$
X = B _ { x _ { 1 } , n ( x _ { 1 } ) } \cup \cdots \cup B _ { x _ { \ell } , n ( x _ { \ell } ) } .
$$

Put $n_0 = \max\{n(x_1), \ldots, n(x_\ell)\}$. Now let $x \in X$ and $k \geq n_0$. Then $x \in B_{x_p,n(x_p)}$ for some $p \in \{1, \ldots, \ell\}$; so that

$$
| f _ { n ( p ) } ( x ) - f _ { n ( p ) } ( x _ { p } ) | < \frac { \varepsilon } { 2 } .
$$

Consequently, using (c) in the hypothesis we obtain

$$
0 \leq f _ { k } ( x ) \leq f _ { n _ { 0 } } ( x ) \leq f _ { n ( p ) } ( x ) = f _ { n ( p ) } ( x _ { p } ) + [ f _ { n ( p ) } ( x ) - f ( x _ { p } ) ] < \frac { \varepsilon } { 2 } + \frac { \varepsilon } { 2 } = \varepsilon .
$$

Therefore $|f_k(x)| < \varepsilon$ for $k \geq n_0$ and $x \in X$. Thus we have uniform convergence.

Example 03.5. In this example we show that if $f_{n} \rightarrow f$ pointwise on $[a,b]$ it does not follow that

$$
\operatorname* { l i m } _ { n \to \infty } \int _ { a } ^{b} f _ { n } ( x ) d x = \int _ { a } ^{b} f ( x ) d x
$$

In other words we may have

$$
\operatorname* { l i m } _ { n } \int _ { a } ^{b} f _ { n } \neq \int _ { a } ^{b} \operatorname* { l i m } _ { n } f _ { n } .
$$

We will see in Learning Unit 8 that in the case of uniform convergence we always have that

$$
\operatorname* { l i m } _ { n } \int _ { a } ^{b} f _ { n } = \int _ { a } ^{b} \operatorname* { l i m } _ { n } f _ { n } .
$$

Define

$$
f _ { n } : [ 0 , 1 ] \to \mathbb { R } \ \ \mathrm { b y } \ \ f _ { n } ( x ) = n ^{2} x ( 1 - x ) ^{n} .
$$





Then $f_{n} \rightarrow 0$ pointwise on $[0,1]$. So if $f$ is the limit function we have

$$
\int _ { a } ^{b} f ( x ) d x = 0 .
$$

But now

$$
\begin{array}{rl} { \int _ { a } ^{b} f _ { n } ( x ) d x } & { = \ n ^{2} \int _ { 0 } ^{1} x ( 1 - x ) ^{n} d x } \\& { = \ n ^{2} \int _ { 0 } ^{1} ( 1 - t ) t ^{n} d t \ \ ( \mathrm { s u b s t i t u t i o n } ) } \\& { = \ n ^{2} \int _ { 0 } ^{1} t ^{n} d t - n ^{2} \int _ { 0 } ^{1} t ^{n + 1} d t } \\& { = \ \frac { n ^{2} } { n + 1 } - \frac { n ^{2} } { n + 2 } } \\& { = \ \frac { n ^{2} } { ( n + 1 ) ( n + 2 ) } . } \end{array}
$$

Therefore

$$
\operatorname* { l i m } _ { n \to \infty } \int _ { 0 } ^{1} f _ { n } ( t ) d x = 1 \neq \int _ { 0 } ^{1} \operatorname* { l i m } _ { n } f _ { n } ( x ) d x .
$$

We have come to the end of Learning Unit 7. Before moving on to Learning Unit 8 on Linear analysis, make sure you are familiar with the concepts and are able to do all the activities correctly.





# LEARNING UNIT 8

# LINEAR ANALYSIS

The outcome for this learning unit is;

Demonstrate the concept of linear analysis.

Informally speaking, Linear Analysis is concerned with studying sets (and maps between these sets) which are endowed with an algebraic structure and a metric. The algebraic structure in question is one which makes the set a vector space, and the metric is one induced by a generalisation of the notion of length of a vector in a vector space.

# 01 BASIC INEQUALITIES

In this section we recall the definition of a vector space and prove some inequalities which will be useful in the sequel. Throughout this chapter, $\mathbb{F}$ will denote either $\mathbb{R}$ or $\mathbb{C}$.

Definition 01.1. A vector space over $\mathbb{F}$ is a quadruple $(V, \mathbb{F}, +, \cdot)$ consisting of a nonempty set $V$ and two operations

: $V \times V \rightarrow V$ (called addition) and $\cdot : \mathbb{F} \times V \rightarrow V$ (called scalar multiplication)

satisfying the following properties:

(1) $x+y=y+x$ for all $x,y\in V$

(2) $x+(y+z)=(x+y)+z$ for all $x,y,z\in V$

(3) there exists a unique element in $V$, denoted by 0 and called the zero element, such that $x+0=x$ for all $x\in V$.





(4) for each $x \in V$ there corresponds a unique element in $V$, called the negative of $x$ and denoted by $-x$, such that $x + (-x) = 0$.

(5) $\alpha\left(x+y\right)=\alpha x+\alpha y$ for all $\alpha\in\mathbb{F}$ and all $x,y\in V$.

(6) $\left(\alpha+\beta\right)x=\alpha x+\beta x$ for all $\alpha,\beta\in\mathbb{F}$ and all $x\in V$.

(7) $\left(\alpha\beta\right)x=\alpha\left(\beta x\right)$ for all $\alpha,\beta\in\mathbb{F}$ and all $x\in V$.

(8) $1\cdot x=x$ for all $x\in X$.

In practice we simply write $V$ for the vector space $(V, \mathbb{F}, +, \cdot)$. We also call elements of $\mathbb{F}$ scalars in this case. A real vector space is a vector space over $\mathbb{R}$, and a complex vector space is a vector space over $\mathbb{C}$. In the context of Mathematical Analysis, vector spaces are also frequently referred to as linear spaces. Elements of a vector space are at times called vectors. So 0 can be referred to as the zero element or the zero vector. We will not distinguish in notation been the scalar 0 and the zero vector. It will however always be clear which zero the symbol 0 denotes.

The first inequality we wish to prove is called the Cauchy-Bunyakowski-Schwarz inequality. We shall refer to it as the CBS inequality. We remark that in a number of books the CBS inequality is also called the Cauchy-Schwarz inequality. We need to prepare some ground in order to be able to state this inequality.

Definition 01.2. Let $V$ be a vector space over $\mathbb{F}$. An inner product on $V$ is a scalar-valued function $\langle\cdot,\cdot\rangle:V\times V\to\mathbb{F}$ such that for all $x,y,z\in V$ and all $\alpha\in\mathbb{F}$:

IP1. $\langle x,x\rangle$ is a real number $\geq 0$.

IP2. $\langle x,x\rangle=0\Leftrightarrow x=0$.

IP3. $\langle x,y\rangle=\langle y,x\rangle$, where the bar denotes the complex conjugate.

IP4. $\langle x+y,z\rangle=\langle x,z\rangle+\langle y,z\rangle$.

IP5. $\langle\alpha x,y\rangle=\alpha\langle x,y\rangle$.

An inner product space is a pair $(V,\langle\cdot,\cdot\rangle)$ where $V$ is a vector space and $\langle\cdot,\cdot\rangle$ an inner product on $V$.

Notice that even if $V$ is a vector space over $\mathbb{C}$, we require that $\langle x, x \rangle$ be a real number which is nonnegative. In general, if $x \neq y$ are vectors in a complex vector space $V$, then $\langle x, y \rangle$ may be a complex number with imaginary part unequal to zero. Also notice that if $V$ is a real vector space, then IP3 says $\langle x, y \rangle = \langle y, x \rangle$.

Observations: Let $V$ be an inner product space. For $x,y,z\in V$ and $\alpha\in\mathbb{F}$ we have:





$$
\begin{array}{rl} & { \mathrm { ( a ) } \ \langle x , y + z \rangle = \overline { { \langle y + z , x \rangle } } = \overline { { \langle y , x \rangle } } + \overline { { \langle z , x \rangle } } = \langle x , y \rangle + \langle x , z \rangle . } \\& { \mathrm { ( b ) } \ \langle x , \alpha y \rangle = \overline { { \langle \alpha y , x \rangle } } = \overline { { \alpha \langle x , y \rangle } } = \overline { { \alpha \langle y , x \rangle } } = \overline { { \alpha } } \langle x , y \rangle . } \end{array}
$$

Theorem 01.3. (Cauchy-Bunyakowski-Schwarz inequality) Let $V$ be an inner product space. Then for all $x,y\in V$

$$
| \langle x , y \rangle | \leq \sqrt { \langle x , x \rangle } \cdot \sqrt { \langle y , y \rangle } .
$$

Proof. If $x=0$ or $y=0$, then the result holds trivially. So assume $x\neq0$ and $y\neq0$. Now for any $\alpha\in\mathbb{F}$ we have

$$
\begin{array}{rl} { 0 } & { \leq } \\& { \langle x - \alpha y , x - \alpha y \rangle } \\& { = \ \langle x , x \rangle - \alpha \langle y , x \rangle - \overline { { \alpha } } \langle x , y \rangle + \alpha \overline { { \alpha } } \langle y , y \rangle } \\& { = \ \langle x , x \rangle - \overline { { \alpha } } \langle x , y \rangle - \alpha [ \langle y , x \rangle - \overline { { \alpha } } \langle y , y \rangle ] . } \end{array}
$$

Choosing $\alpha=\frac{\langle x,y\rangle}{\langle y,y\rangle}$ yields

$$
\begin{array}{rl} { 0 } & { \leq \ \ \langle x , x \rangle - \frac { \langle y , x \rangle \langle x , y \rangle } { \langle y , y \rangle } } \\& { = \ \ \langle x , x \rangle - \frac { \frac { \langle x , y \rangle \langle x , y \rangle } { \langle y , y \rangle } } { \langle y , y \rangle } } \\& { = \ \ \langle x , x \rangle - \frac { | \langle x , y \rangle | ^{2} } { \langle y , y \rangle } , } \end{array}
$$

which implies that

$$
| \langle x , y \rangle | ^{2} \leq \langle x , x \rangle \cdot \langle y , y \rangle ,
$$

whence the result follows.

Our next inequality deals with sequences of scalars. Recall that by a scalar we mean a real or complex number. In order to prove it we shall need the following result.

Lemma 01.1. Let $a, b, p$ and $q$ be real numbers such that $a \geq 0$, $b \geq 0$, $p > 1$ and $\frac{1}{p} + \frac{1}{q} = 1$ (so that $q = \frac{p}{p - 1}$, and hence $q > 1$). Then

$$
a b \leq { \frac { a } { p } } + { \frac { b } { q } } .
$$

Proof. If $a=0$ or $b=0$, then the result holds trivially since then the left-hand side equals





So assume $a > 0$ and $b > 0$. Define a function $f : (0, \infty) \to \mathbb{R}$ by

$$
f ( t ) = \frac { t ^{p} } { p } + \frac { t ^{- q} } { q } .
$$

We show that $f$ has a minimum at $t=1$. Differentiating $f$ we obtain

$$
\begin{array}{rl} & { f ^{p - 1} - t ^{- q - 1} } \\{ = } & { 0 \mathrm { ~ i f f ~ } t = 1 . } \end{array}
$$

Since $f(t) \to \infty$ as $t \to 0^+$ and $f(t) \to \infty$ as $t \to \infty$, it follows that $f$ has a minimum at $t = 1$. Thus, for all $t > 0$, we have

$$
1 = f ( 1 ) \leq f ( t ) .
$$

If we choose $t = a^{1/q}b^{-1/p}$ we obtain

$$
1 \leq \frac { a ^{p / q} b ^{- 1} } { p } + \frac { a ^{- 1} b ^{q / p} } { p }
$$

which implies

$$
a b \leq \frac { a ^{( p / q ) + 1} } { p } + \frac { b ^{( q / p ) + 1} } { q } .
$$

But $(p/q)+1=p$ and $(q/p)+1=q$, so the result follows.

Definition 01.4. Let $p$ be a real number with $p \geq 1$. The sequence space $\ell_p(\mathbb{R})$ is the set of all sequences $\{x_n\}$ of real numbers such that $\sum_{k=1}^{\infty} |x_k|^p < \infty$. The sequence space $\ell_p(\mathbb{C})$ is the set of all sequences $\{z_n\}$ of complex numbers such that $\sum_{k=1}^{\infty} |z_k|^p < \infty$. By $\ell_p$ we shall mean $\ell_p(\mathbb{R})$ or $\ell_p(\mathbb{C})$ without specifying which.

Theorem 01.5. (Hölder's inequality for sequences) Let $p$ and $q$ be real numbers with $p > 1, q > 1$ and $\frac{1}{p} + \frac{1}{q} = 1$. Let $\{x_n\} \in \ell_p$ and $\{y_n\} \in \ell_q$. Then

$$
\sum _ { k = 1 } ^{\infty} | x _ { k } y _ { k } | \leq \left( \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{q} \right) ^{\frac { 1} { q } }
$$

Proof. If $\sum_{k=1}^{\infty}|x_{k}|^{p}=0$ or $\sum_{k=1}^{\infty}|y_{k}|^{q}=0$ the result holds trivially. So assume that

$$
\sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} > 0 \mathrm { ~ a n d ~ } \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{q} > 0 .
$$





Let $i \in \mathbb{N}$, and in the lemma above put

$$
a = \frac { | x _ { i } | } { \left( \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } } \; \; \mathrm { a n d } \; b = \frac { | y _ { i } | } { \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{q} \right) ^{\frac { 1} { q } } }
$$

to obtain

$$
\frac { | x _ { i } | } { \left( \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } } \frac { | y _ { i } | } { \left( \displaystyle \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{q} \right) ^{\frac { 1} { q } } } \leq \frac { 1 } { p } \frac { | x _ { i } | ^{p} } { \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { i } | ^{p} } + \frac { 1 } { q } \frac { | y _ { i } | ^{q} } { \displaystyle \sum _ { k = 1 } ^{\infty} | y _ { i } | ^{q} } .
$$

Now summing over all $i \in \mathbb{N}$ in this latter inequality we get

$$
\frac { \displaystyle \sum _ { i = 1 } ^{\infty} | x _ { i } y _ { i } | } { \displaystyle \left( \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{q} \right) ^{\frac { 1} { q } } } \leq \frac { 1 } { p } + \frac { 1 } { q } = 1 ,
$$

which implies that

$$
\sum _ { i = 1 } ^{\infty} | x _ { i } y _ { i } | = \sum _ { k = 1 } ^{\infty} | x _ { k } y _ { k } | \leq \left( \sum _ { k = 1 } ^{\infty} | x _ { p } | ^{p} \right) ^{\frac { 1} { p } } \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{q} \right) ^{\frac { 1} { q } } .
$$

Next we have the following inequality the proof of which uses Hölder's inequality.

Theorem 01.6. (Minkowski's inequality for sequences) Let $p$ be a real number with $p > 1$. Let $\{x_n\}$ and $\{y_n\}$ be sequences in $\ell_p$. Then

$$
\left( \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \right) \frac { 1 } { p } \leq \left( \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } + \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{p} \right) ^{\frac { 1} { p } } .
$$

Proof. Let $q=\frac{p}{p-1}$. Then we have that $\frac{1}{p}+\frac{1}{q}=1$, so that Hölder's inequality may be used.

Let us note that since $p > 1$, for each $k \in \mathbb{N}$,

$$
| x _ { k } + y _ { k } | ^{p} \leq ( | x _ { k } | + | y _ { k } | ) ^{p} \leq ( 2 \operatorname* { m a x } \{ | x _ { k } | , | y _ { k } | ) ^{p} = 2 ^{p} \operatorname* { m a x } \{ | x _ { k } | ^{p} , | y _ { k } | ^{p} \} \leq 2 ^{p} | x _ { k } | ^{p} + 2 ^{p} | y _ { k } | ^{p} .
$$

Hence $\sum_{k=1}^{\infty}|x_{k}+y_{k}|^{p}<\infty$ if $\{x_{n}\}$ and $\{y_{n}\}$ are in $\ell_{p}$. This shows that the sequence





$\{ |x_{n}+y_{n}|^{p-1}\}$ is in $\ell_{q}$ since

$$
\sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{( p - 1 ) q} = \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} < \infty .
$$

If $\sum_{k=1}^{\infty}|x_{k}+y_{k}|^{p}=0$ the result is immediately true. So assume $\sum_{k=1}^{\infty}|x_{k}+y_{k}|^{p}>0$. Then

$$
\begin{array}{rl} { \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} } & { = \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p - 1} | x _ { k } + y _ { k } | } \\& { \leq \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p - 1} | x _ { k } | + \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p - 1} | y _ { k } | \ \ ( \mathrm { t r i a n g l e ~ i n e q u a l i t y } ) } \\& { \leq \left( \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{( p - 1 ) q} \right) ^{\frac { 1} { q } } \left[ \left( \displaystyle \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } + \left( \displaystyle \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{p} \right) ^{\frac { 1} { p } } \right] } \end{array}
$$

by the Hölder inequality.

Thus

$$
\sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \leq \left( \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \right) ^{\frac { 1} { q } } \left[ \left( \sum _ { k = 1 } ^{\infty} | x _ { p } | ^{p} \right) ^{\frac { 1} { p } } + \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{p} \right) ^{\frac { 1} { p } } \right] .
$$

Dividing both sides by

$$
\left( \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \right) ^{\frac { 1} { q } }
$$

we get

$$
\left( \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \right) ^{1 - \frac { 1} { q } } \leq \left( \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } + \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{p} \right) ^{\frac { 1} { p } } ,
$$

whence the result follows since $1 - \frac{1}{q} = \frac{1}{p}$.

The Hölder and Minkowski inequalities as we have stated apply to infinite sequences. They have the following special finitary versions that we highlight.

Let $n$ be a natural number, $x = (x_1, x_2, \ldots, x_n)$ and $y = (y_1, \ldots, y_n)$ be elements of $\mathbb{F}^n$ (i.e. $\mathbb{R}^n$ or $\mathbb{C}^n$). So $x$ and $y$ are $n$-tuples of real or complex number. Let $\widetilde{x}$ and $\widetilde{y}$ be the sequences $\widetilde{x} = x_1, x_2, \ldots, x_n, 0, 0, \ldots$ and $\widetilde{y} = y_1, y_2, \ldots, y_n, 0, 0, \ldots$. Then $\widetilde{x} \in \ell_2$ and





$\widetilde{y}=\ell_{2}$. Since $2>1$ and $\frac{1}{2}+\frac{1}{2}=1$, Hölder's inequality applied $\widetilde{x}$ and $\widetilde{y}$ gives

$$
\sum _ { k = 1 } ^{n} | x _ { k } y _ { k } | \leq \sqrt { \sum _ { k = 1 } ^{n} | x | _ { k } ^{2} } \cdot \sqrt { \sum _ { k = 1 } ^{n} | y _ { k } | ^{2} } .
$$

On the other hand, the Minkowski's inequality applied to $\widetilde{x}$ and $\widetilde{y}$ yields

$$
\sqrt { \sum _ { k = 1 } ^{n} | x _ { k } + y _ { k } | ^{2} } \leq \sqrt { \sum _ { k = 1 } ^{n} | x _ { k } | ^{2} } + \sqrt { \sum _ { k = 1 } ^{n} | y _ { k } | ^{2} } .
$$

At this juncture we give several examples of vector spaces and spaces which are frequently encountered in Real Analysis.

Example 01.1. Let $n$ be a positive integer, and put

$$
V = \{ x \mid x = ( x _ { 1 } , x _ { 2 } , \ldots , x _ { n } ) ; \ x _ { i } \in \mathbb { F } \} .
$$

Define + and multiplication by scalars pointwise, ie

$$
( x _ { 1 } , \ldots , x _ { n } ) + ( y _ { 1 } , \ldots , y _ { n } ) = ( x _ { 1 } + y _ { 1 } , \ldots , x _ { n } + y _ { n } ) { \mathrm { ~ a n d ~ } } \alpha ( x _ { 1 } , \ldots , x _ { n } ) = ( \alpha x _ { 1 } , \ldots , \alpha x _ { n } ) .
$$

Then $V$ is a vector space provided that if $\mathbb{F}=\mathbb{R}$ then the scalars should be real numbers, whereas if $\mathbb{F}=\mathbb{C}$, the field of scalars could be $\mathbb{R}$ or $\mathbb{C}$. This vector space we denote by $\mathbb{R}^n$ or $\mathbb{C}^n$ (or simply $\mathbb{F}^n$). Now $\mathbb{F}^n$ is also an inner product space where the inner product is defined by

$$
\langle x , y \rangle = \sum _ { k = 1 } ^{n} x _ { i } \overline { { y _ { i } } }
$$

where $x = (x_1, \ldots, x_n)$ and $y = (y_1, \ldots, y_n)$.

Example 01.2. For a real number $p \geq 1$, the sequence space $\ell_p(\mathbb{F})$ is a vector space over $\mathbb{F}$ where addition and scalar multiplication are defined pointwise, ie for $x = \{x_n\}$ and $y = \{y_n\}$ in $\ell_p(\mathbb{F})$, and $\alpha \in \mathbb{F}$,

$$
\begin{array}{rl} { x + y } & { = \ \left\{ x _ { n } + y _ { n } \right\} = x _ { 1 } + y _ { 1 } , x _ { 2 } + y _ { 2 } , \ldots , x _ { n } + y _ { n } , \ldots } \\{ \alpha x } & { = \ \left\{ \alpha x _ { n } \right\} = \alpha x _ { 1 } , \alpha x _ { 2 } , \ldots } \end{array}
$$

Of course we must ascertain that $x+y\in\ell_{p}(\mathbb{F})$ and $\alpha x\in\ell_{p}(\mathbb{F})$ for $x,y\in\ell_{p}(\mathbb{F})$ and $\alpha\in\mathbb{F}$.





If $x,y\in\ell_{p}(\mathbb{F})$, then, by definition, $\left(\sum_{k=1}^{\infty}|x_{p}|^{\frac{1}{p}}<\infty$ and $\left(\sum_{k=1}^{\infty}|y_{k}|^{p}\right)^{\frac{1}{p}}$. So by Minkowski's inequality

$$
\left( \sum _ { k = 1 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \right) ^{\frac { 1} { p } } \leq \left( \sum _ { k = 1 } ^{\infty} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } + \left( \sum _ { k = 1 } ^{\infty} | y _ { k } | ^{p} \right) ^{\frac { 1} { p } } < \infty .
$$

Therefore $x+y\in\ell_{p}(\mathbb{F})$. That $\alpha x\in\ell_{p}(\mathbb{F})$ for all $\alpha\in\mathbb{F}$ and $x\in\ell_{p}(\mathbb{F})$ is easy to check.

Example 01.3. The sequence space $\ell_{\infty}(\mathbb{F})$ is the set of all bounded sequences. Recall that a sequence $\{x_n\}$ is bounded if there is a real number $M > 0$ such that $|x_n| \leq M$ for all $n$. As in the case of $\ell_p$ we frequently write $\ell_{\infty}$ if we do not wish to specify that the terms are complex or real numbers. Now $\ell_{\infty}(\mathbb{F})$ is a vector space over $\mathbb{F}$ where, as before, addition and multiplication are defined pointwise. Verify this.

Example 01.4. The sequence space $\mathbf{C}(\mathbb{F})$ consists of all convergent sequences of reals or complex numbers. It is a vector space over $\mathbb{F}$ where addition and scalar multiplication are defined pointwise.

Example 01.5. Let $X$ be a nonempty set. Then $B(X, \mathbb{F})$, the set of all bounded functions mapping $X$ to $\mathbb{F}$, is a vector space over $\mathbb{F}$ where addition and scalar multiplication are defined as follows:

$$
\begin{array}{rl} { ( f + g ) ( x ) } & { =  f ( x ) + g ( x ) , \ \ f , g \in B ( X , \mathbb { F } ) } \\{ ( \alpha f ) ( x ) } & { = \ \alpha f ( x ) , \ \ \alpha \in \mathbb { F } , \ f \in B ( X , \mathbb { F } ) . } \end{array}
$$

Example 01.6. Let $X$ be a metric space. Then $C(X, \mathbb{F})$, the set of all continuous functions mapping $X$ to $\mathbb{F}$, is a vector space over $\mathbb{F}$ where addition and scalar multiplication are defined as in the case of $B(X, \mathbb{F})$.

Example 01.7. The sequence space $\ell_0(\mathbb{F})$ consists of all sequences $\{x_n\}$ in $\mathbb{F}$ such that $x_i = 0$ for all but finitely many indices $i$. These are sequences with tails consisting of terms each equal to 0. Defining addition and scalar multiplication pointwise makes $\ell_0(\mathbb{F})$ a vector space over $\mathbb{F}$. We now show how an inner product can be defined on $\ell_0(\mathbb{F})$. For any $x, y \in \ell_0(\mathbb{F})$, let

$$
\langle x , y \rangle = \sum _ { k = 1 } ^{\infty} x _ { k } \overline { { y _ { k } } } .
$$





Notice that the sum is in fact finite, so it is well-defined. Check that it defines an inner product on $\ell_0(\mathbb{F})$.

Example 01.8. For $x=\{x_{n}\}$ and $y=\{y_{n}\}$ in $\ell_{2}$, define

$$
\langle x , y \rangle = \sum _ { k = 1 } ^{\infty} x _ { k } \overline { { y _ { k } } } .
$$

Then $\langle\cdot,\cdot\rangle$ so defined is well-defined, ie the series converges; and in fact $\langle\cdot,\cdot\rangle$ is an inner product on $\ell_2$.

We close with the following quotation:

"All analysts spend half their time hunting through the literature for inequalities which they want to use but cannot prove". Harald Bohr

Activity 01.1. (a) In Example 01.2 an astute reader will have noticed that we showed $\ell_{p}$ to be a vector space only for $p > 1$ because we used the Minkowski inequality. Now show that $\ell_{1}$ is a vector space.

(b) Let $V$ be the set of all $n \times n$ matrices with entries in $\mathbb{C}$. For $A = (A_{ij})$ in $V$, let $tr(A) = \sum_{i=1}^{n} A_{ii}$ be the trace of $A$. For $A, B \in V$ define $\langle \cdot, \cdot \rangle$ by

$$
\langle A , B \rangle = t r ( B ^{*} A )
$$

where $B^*$ is the conjugate transpose of the matrix $B$. [Consult a book on Linear Algebra for definitions.] Show that $\langle\cdot,\cdot\rangle$ is an inner product of $V$.

(c) Let $[a,b]$ be a compact interval in $\mathbb{R}$. A function $f:[a,b]\to\mathbb{C}$ is continuous if and only if its real and imaginary parts are continuous real-valued functions, ie if for $f(t)=u(t)+iv(t)$ where $u:[a,b]\to\mathbb{R}$ and $v:[a,b]\to\mathbb{R}$, $u$ and $v$ are continuous. For such a function the integral $\int_a^b f$ is defined by

$$
\int _ { a } ^{b} f = \int _ { a } ^{b} u + i \int _ { a } ^{b} v .
$$

Now let $V$ be the set of all continuous complex-valued functions on $[a,b]$. Define $\langle\cdot,\cdot\rangle$ on $V$ by

$$
\langle f , g \rangle = \int _ { a } ^{b} f ( t ) \overline { { { g ( t ) } } } d t .
$$

Show that $(V,\langle\cdot,\cdot\rangle)$ is an inner product space.





(d) Does $\langle\cdot,\cdot\rangle$ defined on $\mathbb{R}\times\mathbb{R}$ by $\langle x,y\rangle=xy$ define an inner product on $\mathbb{R}$? What about $\langle z,w\rangle=z\overline{w}$ on $\mathbb{C}$?

(e) Let $\langle\cdot,\cdot\rangle$ be an inner product. Show that if $\langle x,y\rangle=\langle x,z\rangle$ for all $x$; then $y=z$.

Normed vector spaces are examined next.

# 02 NORMED VECTOR SPACES

In this section we introduce the "core business" of Linear Analysis, namely, normed vector spaces.

Definition 02.1. Let $V$ be a vector space over $\mathbb{F}$. A norm on $V$ is a real-valued function $||\cdot||: V \to \mathbb{R}$ which satisfies the following properties for all $x, y \in V$ and $\alpha \in \mathbb{F}$:

$N1$. $\|x\| \geq 0$

$N2$. $\|x\| = 0 \Leftrightarrow x = 0$

$N3$. $\|\alpha x\| = |\alpha|\|x\|$

$N4$. $\|x + y\| \leq \|x\| + \|y\|.$

A normed vector space is a pair $(V, \|\cdot\|)$ where $V$ is a vector space and $\|\cdot\|$ is a norm on $V$.

If there is only one norm under consideration on a vector space $V$, we shall say $V$ is a normed vector space; and thus allow notational confusion between the normed vector space $(V, ||\cdot||)$ and the underlying vector space $V$. When we were discussing metric spaces, if we had two metric spaces under consideration we made a point of denoting the metrics by different symbols. In the case of normed vector spaces, if $V$ and $W$ are normed vector spaces we shall use the same symbol $||\cdot||$ to denote the (possibly different) norms on $V$ and $W$.

The property N4 in the definition of a norm is called the triangle inequality for reasons that will be apparent when we consider examples of normed vector spaces. Before proceeding to give examples of normed vector spaces we show how a norm on a vector space induces on a metric.

Theorem 02.2. Let $V$ be a normed vector space. Define a function $d: V \times V \rightarrow \mathbb{R}$ by

$$
d ( x , y ) = | | x - y | |
$$

for all $x,y\in V$. Then $d$ is a metric on $V$.





Proof. We check that $d$ satisfies properties M1 through M4 in Definition 01.1. So let $x,y,z\in V$. Then

(i) $d(x,y)=||x-y||\geq0$.

(ii) $d(x,y)=0\Leftrightarrow||x-y||=0\Leftrightarrow x-y=0\Leftrightarrow x=y$.

(iii) $d(x,y)=||x-y||=||(-1)(y-x)||=|(-1||y-x||)=||y-x||=d(y,x)$.

(iv) $d(x,y)=||x-y||=||(x-z)+(z-y)||\leq||x-z||+||z-y||=d(x,z)+d(z,y)$.

The metric $d$ such as in the theorem above is said to be induced (or generated) by the norm $||\cdot||$. Thus every normed vector space is a metric space where the metric in question is the one induced by the norm. When we have a normed vector space $V$ and we talk about metric-related properties such as open set, continuity, convergence, completeness, etc., these will be with respect to the metric induced by the norm. Take for instance the following definition.

Definition 02.3. A Banach space is a complete normed vector space.

Just to concretise the ideas a bit, let us go through the tedium of explaining what a Banach space is; pretending we were explaining to someone who knows normed vector spaces but not metric spaces. We would first tell them that a sequence $\{x_n\}$ in a normed vector space $V$ converges if there is a vector $x \in V$ such that for every $\varepsilon > 0$ there is a positive integer $n_0$ with the property that $||x_n - x|| < \varepsilon$ whenever $n \geq n_0$. Next we would tell them that a sequence $\{x_n\}$ in $V$ is a Cauchy sequence provided for every $\varepsilon > 0$ there exists $n_0 \in \mathbb{N}$ such that $||x_n - x_m|| < \varepsilon$ for all $m, n \geq n_0$. We would then tell them that a Banach space is a normed vector space in which every Cauchy sequence converges.

In Theorem 02.2 we showed how a norm induces a metric. Now we show how an inner product induces a norm.

Theorem 02.4. Let $\langle\cdot,\cdot\rangle$ be an inner product on a vector space $V$. Define $||\cdot||:V\to\mathbb{R}$ by

$$
| | x | | = \sqrt { \langle x , x \rangle } .
$$

Then $||\cdot||$ is a norm on $V$.





Proof. We check that $||\cdot||$ satisfies N1 through N4. So let $x,y\in V$ and $\alpha\in\mathbb{F}$. Then

(i) $||x||=\sqrt{\langle x,x\rangle}\geq0$ clearly.

(ii) $||x||=0\Leftrightarrow\sqrt{\langle x,x\rangle}=0\Leftrightarrow\langle x,x\rangle=0\Leftrightarrow x=0$.

(iii) $||\alpha x||=\sqrt{\langle\alpha x,\alpha x\rangle}=\sqrt{\alpha\overline{\alpha}\langle x,x\rangle}=\sqrt{|\alpha|^2\langle x,x\rangle}=|\alpha|\sqrt{\langle x,x\rangle}=|\alpha||x||$.

(iv) The triangle inequality is slightly involved. Notice that if $z\in\mathbb{C}$ (or $\mathbb{R}$) then $z+\overline{z}$ $2Re(z)$, where $Re(z)$ denotes the real part of $z$. Now

$$
\begin{array}{rlr} { | | x + y | | ^{2} } & { = } & { \langle x + y , x + y \rangle } \\& { = } & { \langle x , x \rangle + \langle x , y \rangle + \langle y , x \rangle + \langle y , y \rangle } \\& { = } & { \langle x , x \rangle + \langle x , y \rangle + \overline { { \langle x , y \rangle } } + \langle y , y \rangle } \\& { = } & { | | x | | ^{2} + 2 R e \langle x , y \rangle + | | y | | ^{2} } \\& { \leq } & { | | x | | ^{2} + 2 | \langle x , y \rangle | + | | y | | ^{2} } \\& { \leq } & { | | x | | ^{2} + 2 \sqrt { \langle x , x \rangle } \sqrt { \langle y , y \rangle } + | | y | | ^{2} \ \ ( \mathrm { C B S ~ i n e q u a l i t y } ) } \\& { = } & { | | x | | ^{2} + 2 | | x | | | | y | | + | | y | | ^{2} } \\& { = } & { ( | | x | | + | | y | | ) ^{2} . } \end{array}
$$

Taking square roots yields $||x+y|| \leq ||x|| + ||y||$.

As previously, the norm arising from an inner product as per Theorem 02.4 is said to be induced (or generated) by the inner product. Now we give a host of examples.

Example 02.1. Let $V$ be $\mathbb{R}$ or $\mathbb{C}$. For each $x \in V$ define $||\cdot||$ by $||x|| = |x|$. Then $||\cdot||$ is easily checked to be a norm on $V$. Notice that the induced metric (in either case) is the usual metric. Since $\mathbb{R}$ and $\mathbb{C}$ are complete in the usual metric, we have that $V$ is a Banach space.

Example 02.2. Let $n \in \mathbb{N}$ and $V$ be the vector space $\mathbb{F}^n$ on $n$-tuples of real or complex numbers. Let $p$ be a real number with $p \geq 1$. Define $||\cdot||_p$ by

$$
| | x | | _ { p } = \left( \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } }
$$

where $x = (x_1, \ldots, x_n)$. Then $||\cdot||_p$ is a norm on $V$. Let us verify.





(i) For each $k=1,2,\ldots,n$,

$$
| x _ { k } | \geq 0 , \ \mathrm { s o } \ \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} \geq 0 , \ \mathrm { a n d } \ \mathrm { t h e r e f o r e } \ | | x | | _ { p } \geq 0 .
$$

(ii) For any $x \in V$,

$$
\begin{array}{rl} { \| x \| _ { p } = 0 } & { \Leftrightarrow  \left( \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } = 0 } \\& { \Leftrightarrow  \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} = 0 } \\& { \Leftrightarrow  | x _ { k } | ^{p} = 0 \mathrm { ~ f o r ~ a l l ~ } k = 1 , 2 , \ldots , n } \\& { \Leftrightarrow  x _ { k } = 0 \mathrm { ~ f o r ~ a l l ~ } k = 1 , 2 , \ldots , n } \\& { \Leftrightarrow  x = 0 . } \end{array}
$$

(iii) For any $x \in V$ and scalar $\lambda$,

$$
\begin{array}{rl} { | | \lambda x | | _ { p } } & { = \left( \sum _ { k = 1 } ^{n} | \lambda x _ { k } | ^{p} \right) ^{\frac { 1} { p } } } \\& { = \left( | \lambda | ^{p} \sum _ { k = 1 } ^{n} | x _ { k } ) ^{p} \right) ^{\frac { 1} { p } } } \\& { = | \lambda | | | x | | _ { p } . } \end{array}
$$

(iv) For any $x,y\in V$,

$$
\begin{array}{rlr} { | | x + y | | _ { p } } & { = } & { \left( \sum _ { k = 1 } ^{n} | x _ { k } + y _ { k } | ^{p} \right) ^{\frac { 1} { p } } } \\& { \leq } & { \left( \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } + \left( \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } \; \; \; [ \mathrm { A p p l y ~ M i n k o w s k i ' s ~ i n e q u a l i t y } ] } \\& { = } & { | | x | | _ { p } + | | y | | _ { p } } \end{array}
$$

Notice that the special case $p=2$ yields $||x||_2=\sqrt{\sum_{k=1}^n x_k^2}$ on $\mathbb{R}^n$, which induces the usual metric. So again in this case we have a Banach space.

Example 02.3. Let $E$ be a nonempty set and define $\|\cdot\|_{\infty}$ on the vector space $V=$





$B(E,\mathbb{F})$ by

$$
| | f | | _ { \infty } = \operatorname* { s u p } \{ | f ( x ) | : \ x \in E \} .
$$

Then $||\cdot||_{\infty}$ is a norm on $V$ called the supremum norm or simply the $\sup$ norm. We verify only the triangle inequality. Let $f,g\in V$. For any $t\in E$ we have

$$
\begin{array}{rlr} { | ( f + g ) ( t ) | } & { = } & { | f ( t ) + g ( t ) | } \\& { \leq } & { | f ( t ) + g ( t ) | } \\& { \leq } & { | | f | | _ { \infty } + | | g | | _ { \infty } } \end{array}
$$

Since $t$ is an arbitrary element of $E$, we conclude that

$$
\operatorname* { s u p } \{ | ( f + g ) ( t ) | : \ t \in E \} \leq | | f | | _ { \infty } + | | g | | _ { \infty } ,
$$

that is,

$$
\| f + g \| _ { \infty } \leq \| f \| _ { \infty } + \| g \| _ { \infty } .
$$

Whenever we consider the set $B(E,\mathbb{F})$ of bounded real-valued or complex-valued functions as a normed vector space, the norm will always be assumed to be the sup norm.

Theorem 02.5. $B(E,\mathbb{F})$ is a Banach space.

Proof. This is just a special case of Theorem 01.4.

Activity 02.1. (a) Define $||\cdot||_p$ on $\ell_p$ ($p$ real and $p \geq 1$) by

$$
\left\| x \right\| _ { p } = \left( \sum _ { k = 1 } ^{n} | x _ { k } | ^{p} \right) ^{\frac { 1} { p } } .
$$

Show that $||\cdot||$ is a norm on $\ell_{p}$.

(b) Let $X$ be a compact metric space. Deduce from Theorem 02.5 that $C(X,\mathbb{F})$ is a Banach space.

(c) Let $V$ be an inner product space and $||\cdot||$ be the norm induced by the inner product. Why is it true that

$$
| \langle x , y \rangle | \leq | | x | | | y | |
$$

for all $x,y\in V$?





<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>(d) Let $V$ be an inner product and $\| \cdot \|$ be the norm induced by the inner product. Show that $\|x\|=\sup\{|x,y|\colon y\in V \text{ and } \|y\|=1\}$ for all $x\in V$.

(e) Show that the triangle inequality in a normed real vector space is an equality if and only if $y=0$ or $x=\lambda y$ for some $\lambda\geq0$.

(f) Let $V$ be a vector space and $d$ be a metric on $V$ such that

(i) $d(x,y)=d(x+z,y+z)$ for all $x,y,z\in V$, and

(ii) $d(\lambda x,\lambda y)=|\lambda|d(x,y)$ for all $x,y\in V$ and $\lambda\in\mathbb{F}$.

Define $||\cdot||$ by

$$
| | x | | = d ( x , 0 ) .
$$

Show that $||\cdot||$ is a norm on $V$. Next, show that the metric induced by $||\cdot||$ is precisely $d$.

(g) Show that the discrete metric on a vector space cannot be induced by a norm.

(h) Let $V$ be a normed vector space. For any real number $r > 0$ and $x_0 \in V$, show that:

(i) the closure of the open ball $\{x\in V:\ ||x-x_0||<r\}$ is the closed ball $\{x\in V:\ ||x-x_0||\leq r\}$,

(ii) the boundary of the closed ball $\{x\in V:\ ||x-x_0||\leq r\}$ is $\{x\in V:\ ||x-x_0|=r\}$.

Bounded linear operators are examined next.

# 03 BOUNDED LINEAR OPERATORS

Quite often in Mathematics one encounters objects of the form $(X,\tau)$ where $X$ is a set and $\tau$ some relation on $X$. The mappings $f:(X,\tau)\to(Y,\phi)$ between such objects that are then of interest are functions $f:X\to Y$ which connect the relation $\tau$ to the relation $\phi$ in some way.

For instance in groups one is interested in homomorphisms which are functions that preserve the group operation. In metric spaces we were mostly interested in continuous functions $f : (X, d) \to (Y, \rho)$. Such function map points $X$ which are $d$-close to each other to points of $Y$ which are $\rho$-close to each other. In Linear Algebra you learnt about linear





maps between vector spaces. These are maps that preserve vector addition and scalar multiplication.

So what kind of functions between normed vector spaces should be of main interest? Well, as a normed vector space is a vector space to start with, we should like our maps to preserve the vector space structure. Next, as we have a norm on the vector space at hand, our functions should relate the norm of their domain to that of their co-domain in some way.

Definition 03.1. Let $V$ and $W$ be normed vector spaces. A linear operator from $V$ to $W$ is a function $T: V \to W$ such that $T(\alpha x + \beta y) = \alpha T(x) + \beta T(y)$ for all $x, y \in V$ and all scalars $\alpha$ and $\beta$. The set of all linear operators from $V$ to $W$ is denoted by $\mathcal{L}(V, W)$.

If $T \in \mathcal{L}(V,W)$ and $x \in V$, we shall frequently (so that no confusion can arise) write $Tx$ in place of $T(x)$. Now let $V$ and $W$ be normed vector spaces over $\mathbb{F}$. Then $\mathcal{L}(V,W)$ is a vector space over $\mathbb{F}$ with addition and scalar multiplication defined as follows: For $S,T \in \mathcal{L}(V,W)$ and $\alpha \in \mathbb{F}$,

$$
\begin{array}{rcl} { ( S + T ) ( x ) } & { = } & { S x + T x } \\{ ( \alpha T ) ( x ) } & { = } & { \alpha ( T x ) . } \end{array}
$$

The linear operators of main interest are, as stated earlier, the ones that connect in some way the norm of their domain to that of their co-domain. They are defined as follows.

Definition 03.2. Let $V$ and $W$ be normed vector spaces. A linear operator $T: V \to W$ is said to be a bounded linear operator if there is a real number $M > 0$ such that, for all $x \in V$,

$$
| | T x | | \leq M | | x | | .
$$

The set of all bounded linear operators from $V$ to $W$ is denoted by $\mathcal{B}(V,W)$.

Recall (from Linear Algebra) that a subset $S$ of a vector space $V$ is called a subspace if it is a vector space in its own right with respect to addition and scalar multiplication as defined for $V$. One then has that $S$ is a subspace of $V$ if and only if for all $x,y\in S$ and $\alpha\in\mathbb{F}$, $\alpha x+y\in S$.

Let us observe that $\mathcal{B}(V,W)$ is a subspace of $\mathcal{L}(V,W)$. Indeed if $T,S\in\mathcal{B}(V,W)$ and $\alpha$ is a scalar, then there are real numbers $M_1>0$ and $M_2>0$ such that for all $x\in V$,





$||Sx|| \leq M_{1}||x||$ and $||Tx|| \leq M_{2}||x||$. Then

$$
\begin{array}{rl} { | | ( \alpha S + T ) ( x ) | | } & { = \ | | \alpha S x + T x | | } \\& { \leq \ | | \alpha S x | | + | | T x | | } \\& { = \ | \alpha | | | S x | | + | | T x | | } \\& { \leq \ | \alpha | M _ { 1 } | | x | | + M _ { 2 } | | x | | } \\& { = \ ( | \alpha | M _ { 1 } + M _ { 2 } ) | | x | | , } \end{array}
$$

showing that $\mathcal{B}(V,W)$ is a subspace of $\mathcal{L}(V,W)$.

Now let us look at the adjective "bounded" in the context of "bounded linear operator". When we were dealing with functions $f : E \to (X, d)$ mapping a set $E$ into a metric space $(X, d)$, we said such a function is bounded provided $f[E]$, the image of $E$ under $f$, is a bounded subset of $(X, d)$. Recall that a subset $S$ of $(X, d)$ is bounded in case there is a real number $M > 0$ such that $d(x, y) \leq M$ for all $x, y \in S$.

So if we say $T: V \to W$ is a bounded linear operator, do we mean that the image of $V$ under $T$ is a bounded subset of the metric space $W$? In order to answer this (in the negative) let us note that if $X$ is a normed vector space and $S$ is a subset of $X$, then $S$ is a bounded subset of the metric space $X$ if and only if there is a real number $K > 0$ such that $\|x\| \leq K$ for all $x \in S$. To see this let $S$ be bounded and choose $r \in \mathbb{R}$ such that $d(x, y) = \|x - y\| \leq r$ for all $x, y \in S$. Fix any point $x_0 \in S$. Then for every $x \in S$ we have

$$
\begin{array}{rlr} { | | x | | } & { = } & { | | x - x _ { 0 } + x _ { 0 } | | } \\& { \leq } & { | | x - x _ { 0 } | | + | | x _ { 0 } | | } \\& { \leq } & { r + | | x _ { 0 } | | . } \end{array}
$$

So choosing $K=r+||x_0||$ yields the result. Conversely, if $||x||\leq K$ for all $x\in S$, then for any pair $x,y$ of points in $S$ we have

$$
\begin{array}{rlr} { d ( x , y ) } & { = } & { | | x - y | | } \\& { \leq } & { | | x | | + | | y | | } \\& { \leq } & { 2 K ; } \end{array}
$$

which shows $S$ to be bounded.

Theorem 03.3. Let $V$ and $W$ be normed vector spaces and let $T \in \mathcal{L}(V,W)$. If the image of $V$ under $T$ is a bounded subset of the metric space $(W,d)$ where $d$ is the metric





induced by the norm, then $T(x)=0$ for all $x\in V$.

Proof. Suppose not, and pick $x_0 \in V$ such that $T(x_0) \neq 0$. Since $\{T(x) \mid x \in V\}$ is a bounded set, there exists $M > 0$ such that $||T(x)|| \leq M$ for all $x \in V$. Now let $\alpha = (M + 1)/||T(x_0)||$. Then $\alpha x_0$ is a vector in $V$ such that

$$
\begin{array}{rl} { | | T ( \alpha x _ { 0 } ) | | } & { = \ | | \alpha T ( x _ { 0 } ) | | } \\& { = \ | \alpha | | | T ( x _ { 0 } ) | | } \\& { = \ \frac { M + 1 } { | | T ( x _ { 0 } ) | | } \cdot | | T ( x _ { 0 } ) | | } \\& { = \ M + 1 } \\& { > \ M . } \end{array}
$$

This contradiction proves the theorem.

So when dealing with linear operators, by a bounded linear operator we mean a linear operator with the property stated in Definition 03.2. Similarly, $\mathcal{B}(V,W)$ denotes the set of all bounded linear operators from $V$ to $W$ and should not be confused with the set of functions $f:V\to W$ for which $f[V]$ is a bounded subset of $W$ and, of course, denoted by $B(V,W)$.

As some kind of follow-up to Theorem 03.3 we show that if $T:V\to W$ is a bounded linear operator, then for every subset $E$ of $V$ which is bounded, $T[E]=\{Tx\mid x\in E\}$ is a bounded subset of $W$.

Theorem 03.4. Let $V, W$ be normed vector spaces, $T : V \to W$ be a bounded linear operator and $E \subseteq V$ be bounded. Then $T[E] = \{Tx \mid x \in E\}$ is a bounded subset of $W$.

Proof. Choose $M > 0$ such that $||Tx|| \leq M||x||$ for all $x \in V$. This is possible since $T$ is a bounded linear operator. Since $E$ is a bounded set, there exists $K > 0$ such that $||x|| \leq K$ for all $x \in E$. Then, if $x \in E$ we have

$$
| | T x | | \leq M | | x | | \leq M K .
$$

So $T[E]$ is a bounded set.

<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>Particularly, \] \[T:V\to W\] is a bounded linear operator] \[\{||Tx|\|\:x\in V\] \] and \[\|x\;\] \[] is a subset of \[\mathmathbb{R\}\] which is bounded]. Its suprem] \[\] is extremely important; so] \[\] that that is given a] \[\]





Definition 03.5. Let $V, W$ be normed vector spaces and $T: V \to W$ be a bounded linear operator. The operator norm (or simply norm) of $T$, denoted $||T||$, is defined to be

$$
| | T | | = \operatorname* { s u p } \{ | | T x | | : \ x \in V \ a n d \ | | x | | \leq 1 \} .
$$

Because the set $\{||Tx||: x \in V, ||x|| \leq 1\}$ is bounded above, $||T||$ (as defined above) is a real number. Note that for any $z \in V$ we have:

$$
\begin{array}{r} { \bullet  \| z \| < \ 1 \Rightarrow \| T z \| \leq \| T \| } \\{ \bullet  \| z \| = \ 1 \Rightarrow \| T z \| \leq \| T \| . } \end{array}
$$

What if $z \in V$ is arbitrary? First note that if $z = 0$ then $||z|| < 1$, and so that case is covered. Now let $z \in V \setminus \{0\}$. Put $w = \frac{1}{||z||}z$ (we shall frequently write this as $\frac{z}{||z||}$). Then $w \in V$ and $||w|| = 1$; so that $||Tw|| \leq ||T||$. This implies that

$$
\begin{array}{rl} { \| T \| \geq \left\| T \left( \frac { z } { \| z \| } \right) \right\| } & { = \left\| \frac { 1 } { \| z \| } T ( z ) \right\| } \\& { = \frac { 1 } { \| z \| } \| T ( z ) \| . } \end{array}
$$

Consequently, on multiplying, by $||z||$ both sides, we obtain the following result.

Theorem 03.6. Let $V, W$ be normed vector spaces, $T : V \to W$ be a bounded linear operator and $||T||$ be the operator norm of $T$. Then

$$
\| T x \| \leq \| T \| \| x \|  { \mathrm { f o r ~ a l l } }  x \in V .
$$

Let us reflect a bit on this theorem. If $T:V\to W$ is a bounded linear operator we know, by definition, that there is a real number $M$ such that $||Tx||\leq M||x||$ for all $x\in V$. Now the theorem tells us that in fact $||T||$ is one such number. So a natural question is how $||T||$ is related to other such real numbers. We shall show that $||T||$ is the smallest such number.

Theorem 03.7. Let $V, W$ be normed vector spaces and let $T \in \mathcal{B}(V, W)$. Then

$$
\| T \| = \operatorname* { i n f } \{ M \geq 0 : \ | | T x | | \leq M | | x | | \ \ \mathrm { f o r ~ a l l } \ \ x \in V \} .
$$

Proof. Since $||Tx|| \leq ||T||||x||$ for all $x \in V$, if we can show that for any $M$ with $||Tx|| \leq M||x||$ for all $x \in V$ we have $||T|| \leq M$, then the result will follow because then $||T||$ will be a lower bound of a set to which it belongs. So let $M \geq 0$ be such that $||Tx|| \leq M||x||$





for all $x \in V$. If $w \in V$ is such that $\|w\| \leq 1$, then $\|T(w)\| \leq M\|w\| \leq M$. Consequently $M$ is an upper bound for $\{\|T(w)\| : w \in V, \|w\| = 1\}$. Thus $\|T\| \leq M$. $\square$

Now let us justify calling $||T||$ (as defined above) the norm of $T$. The justification should be that $||\cdot||$: $\mathcal{B}(V,W) \to \mathbb{R}$ does indeed define a norm on the vector space $\mathcal{B}(V,W)$.

Theorem 03.8. Let $V$ and $W$ be normed vector spaces. The function $||\cdot||: \mathcal{B}(V,W) \to \mathbb{R}$ given by $||T|| = \sup\{|Tx||: ||x|| \leq 1\}$ is a norm on $\mathcal{B}(V,W)$.

Proof. It is clear that $||T|| \geq 0$ and $||T|| = 0$ if and only if $T$ is the zero map. So let us verify axioms N3 and N4. Let $S, T \in \mathcal{B}(V, W)$ and $\alpha$ be a scalar, then

$$
\begin{array}{rl} { \| \alpha T \| } & { = \ \operatorname* { s u p } \{ \| \alpha T ( x ) \| : \ | | x | | \leq 1 \} = \operatorname* { s u p } \{ | \alpha | \| T x \| : \ | | x | \| \leq 1 \} } \\& { = \ | \alpha | \operatorname* { s u p } \{ \| T x \| : \ | | x | \| \leq 1 \} = | \alpha | \| T \| . } \end{array}
$$

So N3 holds. To show N4 let $x$ be an arbitrary vector in $V$ with $\|x\| \leq 1$. Then

$$
| | ( T + S ) ( x ) | | = | | T x + S x | | \leq | | T x | | + | | S x | | \leq | | T | | + | | S | | .
$$

Thus the real number $||T||+||S||$ is an upper bound for the set $\{||(T+S)(x)||:||x||\leq1\}$. So the supremum of this set is less than or equal to $||T||+||S||$, i.e. $||T+S||\leq||T||+||S||$.

$\square$

Now let $U,V$ and $W$ be normed vector spaces, $T\in\mathcal{B}(U,V)$ and $S\in\mathcal{B}(V,W)$. Then the composite $S\circ T:U\to W$ is a bounded linear transformation as can easily be verified. We show that the norm of a composite is at most the product of the norms of the factors.

Theorem 03.9. Let $U,V$ and $W$ be normed vector spaces, and let $T \in \mathcal{B}(U,V)$, $S \in \mathcal{B}(V,W)$. Then $||S \circ T|| \leq ||S||||T||$.

Proof. Let $x \in U$ be such that $||x|| \leq 1$. Then

$$
\begin{array}{rl} { | | ( S \circ T ) ( x ) | | } & { = \ | | S ( T x ) | | } \\& { \leq \ | | S | | | | T x | | \ \ ( \mathrm { b y ~ T h e o r e m ~ 03 . 6 } ) } \\& { \leq \ | | S | | | | T | | | | x | | \ \ ( \mathrm { T h e o r e m ~ 03 . 6 ~ a g a i n } ) } \\& { \leq \ | | S | | | | T | | \ \ ( \mathrm { s i n c e ~ } | | x | | \leq 1 ) . } \end{array}
$$

So $||S \circ T|| = \sup\{||(S \circ T)(x)|| : ||x|| \leq 1\} \leq ||S||||T||.$

In the introduction to this section we mentioned that maps of interest in normed vector spaces should connect the algebraic structures of the vector spaces and also the metric properties of mapping points that are close together to images that are close together.





This latter property is just an informal way of describing continuity. So we ask: are bounded linear operators continuous? The answer is affirmative.

Theorem 03.10. Let $V$ and $W$ be normed vector spaces and let $T:V\to W$ be a linear operator. Then the following are equivalent:

(a) $T$ is a bounded linear operator.(b) $T$ is continuous.(c) $T$ is continuous at 0.

Proof. (a) $\Rightarrow$ (b): We show continuity by showing continuity at each point. So let $x_0$ be a vector in $V$. Let $\varepsilon > 0$ be given. Since $T$ is a bounded linear operator there exists a real number $M > 0$ such that $||Tx|| \leq M||x||$ for all $x \in V$. Put $\delta = \frac{\varepsilon}{M}$. Now if $x \in V$ and $||x - x_0|| < \delta$, then

$$
| | T x - T x _ { 0 } | | = | | T ( x - x _ { 0 } ) | | \leq M | | x - x _ { 0 } | | < M \delta = \varepsilon .
$$

So $T$ is continuous at $x_{0}$, and hence on $V$.

(b) $\Rightarrow$ (c): Continuity means continuity at every point.

(c) $\Rightarrow$ (a): Given $\varepsilon=1$, choose, by continuity at $0$, $\delta>0$ such that if $||x-0||<\delta$, then $||T(x)-T(0)||<1$. This means that

$$
\| x \| < \delta \Rightarrow \| T x \| < 1 .
$$

Now put $M=\frac{2}{\delta}$. We shall show that $||Tz||\leq M||z||$ for all $z\in V$. If $z=0$, then clearly $||Tz||\leq M||z||$. If $z\neq0$, put $x=\frac{\delta}{2||z||}z$. Then $x$ is a vector in $V$ with $||x||=\frac{\delta}{2}<\delta$. Thus $||Tx||<1$; that is

$$
\begin{array}{rl} { 1 } & { > } \\& { = \frac { \delta } { 2 | | z | | } \bigg | \bigg | } \\& { = \frac { \delta } { 2 | | z | | } | | T z | | . } \end{array}
$$

Consequently

$$
| | T z | | < \frac { 2 } { \delta } | | z | |
$$

and we are done.

There is nothing special about 0 in the preceding result. You will show in the exercises that if a linear operator is continuous at one vector (any one vector) then it is a bounded





linear operator.

In calculating the norm of a bounded linear operator $T: V \to W$ using the definition, we need to compute the supremum of the set $\{||Tx||: ||x|| \leq 1\}$. In our next result we show that in fact the supremum of this set equals the suprema of the sets $\{||Tx||: ||x|| < 1\}$ and $\{||Tx||: ||x|| = 1\}$. First let us recall some facts we know from metric spaces and cast them in the language of norms.

FACT 1: Let $V$ be normed vector space, $\{x_n\}$ be a sequence in $V$ and $x \in V$. Then $x_n \to x \Leftrightarrow \lim_{n \to \infty} ||x_n - x|| = 0$.

FACT 2: If $T \in \mathcal{B}(V,W)$ and $\{x_n\}$ is a sequence in $V$ which converges to $x \in V$, then $T(x_n) \to T(x)$ in $W$ since $T$ is continuous.

FACT 3: If $V$ is a normed vector space, then $|||x||-||y|||\leq||x-y||$ for all $x,y\in V$. Hence if $x_n\to x$ in $V$, then $\lim\limits_{n\to\infty}||x_n||=||x||$.

Theorem 03.11. Let $V$ and $W$ be normed vector spaces and let $T \in \mathcal{B}(V,W)$. Then

$$
\| T \| = \operatorname* { s u p } \{ \| T x \| : \ | | x | | <   1 \} = \operatorname* { s u p } \{ \| T x \| : \ | | x | | = 1 \} .
$$

<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>只修正下面文本中$\......里的LaTeX语法错误，不改动文字、标点，直接返回修正后的文本：

$$
\begin{array}{rlr} { | | x _ { n } - x | | } & { = } & { \left| \left| \left( x - \frac { 1 } { n } x \right) - x \right| \right| } \\& { = } & { \frac { 1 } { n } | | x | | } \\& { = } & { \frac { 1 } { n } \to 0 \mathrm { ~ a s ~ } \ n \to \infty . } \end{array}
$$





So $x_{n} \rightarrow x$ in $V$ and hence $T(x_{n}) \rightarrow T(x)$ in $W$. In consequence,

$$
\operatorname* { l i m } _ { n \to \infty } | | T ( x _ { n } ) | | = | | T x | | .
$$

But

$$
| | x _ { n } | | = \left| \left( 1 - \frac { 1 } { n } \right) x \right| = \left| \left| 1 - \frac { 1 } { n } \right| \right| = 1 - \frac { 1 } { n } < 1 .
$$

Therefore $||T(x_n)|| \leq \alpha$. So $\{||T(x_n)||\}$ is a sequence of real numbers each less than or equal to $\alpha$ and converging to $\alpha$. So their limit is also less than or equal to $\alpha$; that is, $||Tx|| \leq \alpha$, as required.

$\alpha \leq \beta$: To show that $\alpha \leq \beta$ is suffices to show that if $x \in V$ with $||x|| < 1$, then $||Tx|| \leq \beta$. For $x = 0$, this is trivial. So let $x \neq 0$ and $||x|| < 1$. Now $\frac{x}{||x||}$ has norm 1, so $\left||T\left(\frac{x}{||x||}\right)\right|| \leq \beta$. Then

$$
\begin{array}{rcll}&\frac{1}{||x||}||Tx||&\le&\beta\\\Rightarrow&||Tx||&\le&\beta||x||\\\Rightarrow&||Tx||&\le&\beta\text{since}||x||<1.\end{array}
$$

So all in all we have $||T|| \leq \alpha \leq \beta \leq ||T||$, which proves the theorem.

We end by showing that $\mathcal{B}(V,W)$ is a Banach space whenever $W$ is a Banach space.

Theorem 03.12. Let $V$ and $W$ be normed vector spaces. If $W$ is a Banach space, then $\mathcal{B}(V,W)$ is a Banach space.

Proof. Let $\{T_n\}$ be a Cauchy sequence in $\mathcal{B}(V,W)$. So given $\varepsilon > 0$ there exists $n_0 \in \mathbb{N}$ such that

$$
\| T _ { n } - T _ { m } \| < \varepsilon \; \; \mathrm { f o r ~ a l l } \; \; m , n \geq n _ { 0 } .
$$

Thus, if $x \in V \backslash \{0\}$ and $\varepsilon' > 0$ is arbitrary; choosing $k \in \mathbb{N}$ so that $||T_n - T_m|| < \frac{\varepsilon'}{||x||}$ whenever $m, n \geq k$ we obtain

$$
\begin{array}{rlr} { | | T _ { n } ( x ) - T _ { m } ( x ) | | } & { = } & { | | ( T _ { n } - T _ { m } ) ( x ) | | } \\& { \leq } & { | | T _ { n } - T _ { m } | | | | x | | } \\& { \leq } & { \frac { \varepsilon ^{\prime} } { | | x | | } \cdot | | | x | | } \\& { = } & { \varepsilon ^{\prime} . } \end{array}
$$





This shows that $\{T_{n}(x)\}$ is a Cauchy sequence in $W$ for each $x \in V \setminus \{0\}$. Clearly $\{T_{n}(0)\}$ is a Cauchy sequence in $W$ because it is the constant sequence with each term equal to 0. So $\{T_{n}(x)\}$ is a Cauchy sequence in $W$ for each $x \in V$. Since $W$ is a Banach space, $\{T_{n}(x)\}$ converges in $W$, for each $x \in V$. Define $T: V \to W$ by

$$
T ( x ) = \operatorname* { l i m } _ { n } T _ { n } ( x ) .
$$

We check that $T \in \mathcal{B}(V,W)$ and $T_n \rightarrow T$ in $\mathcal{B}(V,W)$.

We first show that $T$ is a linear operator. Let $x,y\in V$ and $\alpha$ be a scalar. Then

$$
\begin{array}{rl} { T ( \alpha x + y ) } & { = \operatorname* { l i m } _ { n } T _ { n } ( \alpha x + y ) } \\& { = \operatorname* { l i m } _ { n } [ \alpha T _ { n } ( x ) + T ( y ) ] } \\& { = \alpha \operatorname* { l i m } _ { n } T _ { n } ( x ) + T ( y ) } \\& { = \alpha T ( x ) + T ( y ) . } \end{array}
$$

Next we show that $T$ is a bounded linear operator. From $|||T_n||-||T_m|||\leq||T_n-T_m||$ we deduce that $\{||T_n||\}$ is a Cauchy sequence of real numbers. So there is a nonnegative real number $M$ such that

$$
\operatorname* { l i m } _ { n \to \infty } | | T _ { n } | | = M .
$$

Now let $x \in V$. Since $T_n(x) \to T(x)$, $||T_n(x)|| \to ||T(x)||$. That is

$$
\begin{array}{rl} { | | T x | | } & { = \operatorname* { l i m } _ { n } | | T _ { n } ( x ) | | } \\& { \leq \operatorname* { l i m } _ { n } | | T _ { n } | | \ | | x | | \ \ ( \mathrm { s i n c e ~ e a c h } \ T _ { n } \in \mathcal { B } ( V , W ) ) } \\& { = \ M | | x | | . } \end{array}
$$

So $T \in \mathcal{B}(V,W)$. We are left with showing that $T_n \to T$ in $\mathcal{B}(V,W)$. So let $\varepsilon > 0$, and $n_0 \in \mathbb{N}$ be such that

$$
| | T _ { m } - T _ { n } | | < \frac { \varepsilon } { 2 }
$$

for all $m,n\geq n_0$. If $v\in V$ with $||x||=1$ and $m,n\geq n_0$, then

$$
\| ( T _ { m } - T _ { n } ) ( x ) \| \leq \| T _ { m } - T _ { n } \| \, \| x \| \leq \| T _ { m } - T _ { n } \| \leq \frac { \varepsilon } { 2 } .
$$

Now hold $m$ fixed and let $n$ approach $\infty$ to obtain

$$
\operatorname* { l i m } _ { n \to \infty } | | T _ { m } ( x ) - T _ { n } ( x ) | | = | | T _ { m } ( x ) - T ( x ) | | .
$$





We therefore have

$$
| | T _ { m } ( x ) - T ( x ) | | < \frac { \varepsilon } { 2 }
$$

for all $m \geq n_0$ and $x \in V$ with $\|x\| = 1$. Consequently

$$
| | T _ { m } - T | | \leq \frac { \varepsilon } { 2 } < \varepsilon
$$

for all $m \geq n_0$. This completes the proof.

We now give some examples.

Example 03.1. Consider the normed vector space $\ell_2$ with the norm $||x||_2 = \left(\sum_{i=1}^{\infty} |x_i|^2\right)^{\frac{1}{2}}$. Define $T : \ell_2 \to \ell_2$ by

$$
T x = T ( x _ { 1 } , x _ { 2 } , \ldots , ) = ( x _ { 2 } , x _ { 3 } , \ldots ) .
$$

That is, if $x \in \ell_2$ is the sequence $x_1, x_2, \ldots$ then its image under $T$ is the sequence $x_2, x_3, \ldots$. It is easy to check that $T$ is a linear operator. Let us show that $T \in \mathcal{B}(\ell_2, \ell_2)$ and compute $||T||$. Let $x = (x_1, x_2, \ldots) \in \ell_2$.

Then

$$
\begin{array}{rlr} { | | T x | | _ { 2 } } & { = } & { | | ( x _ { 2 } , x _ { 3 } , \ldots ) | | _ { 2 } } \\& { = } & { \sqrt { \displaystyle \sum _ { i = 2 } ^{\infty} | x _ { i } | ^{2} } } \\& { \leq } & { \sqrt { \displaystyle \sum _ { i = 1 } ^{\infty} | x _ { i } | ^{2} } } \\& { = } & { | | x | | _ { 2 } } \end{array}
$$

Thus, putting $M=1$, we have $||Tx||_2 \leq M||x||_2$ for all $x \in \ell_2$. This shows that $T$ is a bounded linear operator with $||T|| \leq 1$. Now before evaluating $||T||$, let us consider this general technique:

Suppose $T: V \to W$ is a bounded linear operator and suppose $M$ is a constant such that $||T(z)|| \leq M||z||$ for all $z \in V$ (or for all $z$ with $||z|| \leq 1$); so that $||T|| \leq M$. Now if there is a vector $z_0$ in $V$ with $||z_0|| \leq 1$ and $||T(z_0)|| = M$, then we must have $||T|| = M$; for otherwise a contradiction arises as follows: $M = ||T(z_0)|| \leq ||T|| ||z_0|| \leq ||T|| < M$.





Going back to the problem at hand, we have $||T|| \leq 1$. Let $z = (0,1,0,0,\ldots)$. Then $z \in \ell_2$, $||z|| = 1$ and $||Tz|| = 1$. Hence $||T|| = 1$.

Example 03.2. Let $T : \mathbb{R}^2 \to \mathbb{R}$ be the map $T(x,y) = x + 2y$ for all $(x,y) \in \mathbb{R}^2$. Let the norms under consideration be $||(x,y)|| = \sqrt{x^2 + y^2}$ and $||(w|| = |w|$ for $(x,y) \in \mathbb{R}^2$ and $w \in \mathbb{R}$. It is easy to check that $T$ is a linear operator. Let us show that $T \in \mathcal{B}(\mathbb{R}^2, \mathbb{R})$ and compute $||(T||$. First let us note that

$$
T ( x , y ) = \langle ( x , y ) , ( 1 , 2 ) \rangle
$$

where $\langle\cdot,\cdot\rangle$ is the inner product as per Example 01.8. Thus, by the CBS inequality

$$
\begin{array}{rl} { | | T ( x , y ) | | } & { = \ | \langle ( x , y ) , ( 1 , 2 ) \rangle | } \\& { \leq \ | | ( x , y ) | | \ | | ( 1 , 2 ) | | } \\& { = \ \sqrt { 5 } | | ( x , y ) | | . } \end{array}
$$

Therefore $||T|| \leq \sqrt{5}$. Now the vector $\left(\frac{1}{\sqrt{5}}, \frac{2}{\sqrt{5}}\right) \in \mathbb{R}^{2}$ is such that

$$
\left\| \left( \frac { 1 } { \sqrt { 5 } } , \frac { 2 } { \sqrt { 5 } } \right) \right\| = 1 \; \mathrm { a n d } \; \left\| T \left( \frac { 1 } { \sqrt { 5 } } , \frac { 2 } { \sqrt { 5 } } \right) \right\| = \frac { 5 } { \sqrt { 5 } } = \sqrt { 5 } .
$$

We therefore conclude that $||T||=\sqrt{5}$.

Example 03.3. Let $h \in C[a,b]$, where $C[a,b]$ denotes the normed vector space of all real-valued continuous functions endowed with the $\sup$ norm. Suppose $h(x) \geq 0$ for all $a \leq x \leq b$. Define $T : C[a,b] \to \mathbb{R}$ by

$$
T ( g ) = \int _ { a } ^{b} g ( t ) f ( t ) d t .
$$

Then $T$ is easily checked to be a linear operator. We show that $T$ is a bounded linear operator and compute $||T||$. Now

$$
\begin{array}{rlr} { | T ( g ) | } & { = } & { \left| \int _ { a } ^{b} g ( t ) h ( t ) d t \right| } \\& { \leq } & { \int _ { a } ^{b} | g ( t ) | \ | h ( t ) | \ d t } \\& { \leq } & { \int _ { a } ^{b} | | g | | \cdot h ( t ) d t \ \ ( \mathrm { s i n c e } \ h \geq 0 \ \mathrm { a n d } \ | g ( t ) | \leq | | g | | \ \forall t ) } \\& { = } & { M | | g | | , } \end{array}
$$





where $M=\int_{a}^{b}h(t)dt$. Therefore $T$ is a bounded linear operator and

$$
\| T \| \leq \int _ { a } ^{b} h ( t ) d t .
$$

Now let $f:[a,b]\to\mathbb{R}$ be given by $f(t)=1$ for all $t\in[a,b]$. Then $f\in C[a,b]$ and $||f||=\sup\{|f(t)|:a\leq t\leq b\}=1$. Furthermore

$$
T ( f ) = \int _ { a } ^{b} h ( t ) d t .
$$

We therefore have that

$$
\| T \| = \int _ { a } ^{b} h ( t ) d t .
$$

Activity 03.1. (a) Let $T : \mathbb{R}^2 \to \mathbb{R}$ be given by $T(x,y) = 2x + 3y$ for all $(x,y) \in \mathbb{R}^2$ where $\mathbb{R}^2$ has the norm $||(u,v)|| = \sqrt{u^2 + v^2}$. Show that $T \in \mathcal{B}(\mathbb{R}^2, \mathbb{R})$ and compute $||T||$.

(b) Let $C[a,b]$ be the normed vector space of all continuous function $f:[a,b]\to\mathbb{R}$ with the $\sup$ norm. Let $g\in C[a,b]$ be such that $g(t)\leq0$ for all $t\in[a,b]$. Define $T:C[a,b]\to\mathbb{R}$ by

$$
T ( f ) = \int _ { a } ^{b} f ( t ) g ( t ) d t .
$$

Show that $T$ is a bounded linear operator and find $||T||$.

(c) Let $V, W$ be normed vector spaces and $T \in \mathcal{L}(V, W)$. Show that if there is a vector $x_0 \in V$ such that $T$ is continuous at $x_0$, then $T \in \mathcal{B}(V, W)$.

(d) In the proof of Theorem 03.12, when showing that $T_n \to T$ in $\mathcal{B}(V,W)$, we could have let $U = \{x \in V : \ ||x|| \leq 1\}$ and then noted that $T, T_n \in \mathcal{B}(V,W)$, and then used the fact that $\{T_n\}$ converges uniformly on $U$ to $T$ in order to conclude that $T_n \to T$ in $\mathcal{B}(V,W)$. Show it.

(e) Let $V, W$ be normed vector spaces and $T \in \mathcal{B}(V, W)$. Show that

$$
\| T \| = \operatorname* { s u p } \left\{ \frac { \| T x \| } { \| x \| } : \ x \neq 0 \right\} .
$$

(f) Let $C[a,b]$ be as in (b). Let $x_0$ be a real number with $a < x_0 < b$. Define $T : [a,b] \to \mathbb{R}$ by $T(f) = f(x_0)$ for all $f \in C[a,b]$. Show that $T$ is a bounded linear operator





with $||T||=1$.

(g) Let $T : \ell_2 \to \ell_2$ be given by $T(x_1, x_2, \ldots) = (0, x_1, x_2, \ldots)$. Show that $T \in \mathbb{B}(\ell_2, \ell_2)$ $[\ell_2$ is endowed with the $||\cdot||_2$ norm] and find $||T||$.

We have come to the end of Learning Unit 8. Before moving on to Learning Unit 9 on Riemann-Stieltjes Integral, make sure you are familiar with the concepts and are able to do all the activities.





# LEARNING UNIT 9

# THE RIEMANN-STIELTJES

#INTEGRAL

The outcome of this learning unit is;

Demonstrate the concept of the Riemann-Stieltjes Integral.

From elementary Calculus you are familiar with the geometrical basis of an integral being the area under the curve. Also in the first course on rigorous Analysis (MAT2613) you learnt about the Riemann integral as a concept on which area under a curve was based rather than the other way around.

In this chapter we study a concept which is more general than that of the Riemann integral, and one of which the Riemann integral is a special case.

# 01 THE INTEGRAL

Throughout this section we shall be working with a closed and bounded interval $[a,b]$, and all functions will be real-valued and bounded on $[a,b]$.

By a partition of $[a,b]$ we mean a finite set of points

$$
P = \{ x _ { 0 } , x _ { 1 } , \ldots , x _ { n } \}
$$

such that $a = x_0 < x_1 < \ldots < x_{n-1} < x_n = b$. A partition $Q$ of $[a,b]$ is said to be finer than $P$ (or a refinement of $P$) in case $Q \supseteq P$. The $k^{\text{th}}$ subinterval of a partition $P = \{x_0, x_1, \ldots, x_n\}$ is the interval $[x_{k-1}, x_k]$. Its length $x_k - x_{k-1}$ is denoted by $\triangle x_k$.





If $\alpha:[a,b]\to\mathbb{R}$, we denote $\alpha(x_k)-\alpha(x_{k-1})$ by $\triangle\alpha_k$. By the norm of a partition $P$, denoted $||P||$, we mean the length of the longest subinterval of $P$; that is,

$$
| | P | | = \operatorname* { m a x } \{ \triangle x _ { k } \mid k = 1 , 2 , \ldots , n \} .
$$

Note that if $P, Q$ are partitions of $[a, b]$ and $Q$ is finer than $P$ then $||Q|| \leq ||P||$. Symbolically,

$$
Q \supseteq P \Rightarrow \| Q \| \leq \| P \| .
$$

Thus, refinement of a partition reduces its norm.

Recall that a function $\alpha:[a,b]\to\mathbb{R}$ is said to be increasing on $[a,b]$ if for all $x,y\in[a,b]$, $\alpha(x)\leq\alpha(y)$ whenever $x\leq y$.

Definition 01.1. Let $f : [a,b] \to \mathbb{R}$ be bounded, $\alpha : [a,b] \to \mathbb{R}$ be increasing on $[a,b]$ and $P = \{x_0, x_1, \ldots, x_n\}$ be a partition of $[a,b]$. For each $k = 1, 2, \ldots, n$ let

$$
\begin{array}{rlr} { M _ { k } ( f ) } & { = } & { \operatorname* { s u p } \{ f ( x ) \mid x _ { k - 1 } \leq x \leq x _ { k } \} , \ \mathrm { a n d } } \\{ m _ { k } ( f ) } & { = } & { \operatorname* { i n f } \{ f ( x ) \mid x _ { k - 1 } \leq x \leq x _ { k } \} . } \end{array}
$$

The numbers

$$
U ( P , f , \alpha ) = \sum _ { k = 1 } ^{n} M _ { k } ( f ) \triangle \alpha _ { k }  a n d  L ( P , f , \alpha ) = \sum _ { k = 1 } ^{n} m _ { k } ( f ) \triangle \alpha _ { k }
$$

are called respectively, the upper Stieltjes sum and the lower Stieltjes sum of $f$ with respect to $\alpha$ for the partition $P$.

Note that $m_k(f) \leq M_k(f)$ for each $k$, and $\triangle\alpha_k \geq 0$ since $\alpha$ is increasing on $[a,b]$. Consequently we have $m_k(f)\triangle\alpha_k \leq M_k(f)\triangle\alpha_k$ for each $k$, whence we deduce that

$$
L ( P , f , \alpha ) \leq U ( P , f , \alpha )
$$

for every partition $P$ of $[a,b]$. Since $f$ is bounded there are real numbers $m$ and $M$ such that $m \leq f(x) \leq M$ for all $x \in [a,b]$. Now note that

$$
\begin{array}{rlr} { \displaystyle \sum _ { k = 1 } ^{n} \triangle \alpha _ { k } } & { = } & { \alpha ( x _ { 1 } ) - \alpha ( x _ { 0 } ) + \alpha ( x _ { 2 } ) - \alpha ( x _ { 1 } ) + \cdots + \alpha ( x _ { n } ) - \alpha ( x _ { n - 1 } ) } \\& { = } & { \alpha ( b ) - \alpha ( a ) . } \end{array}
$$





Thus, for any partition $P$ of $[a,b]$, we have

$$
\begin{array}{rl} { \sum _ { k = 1 } ^{n} m \triangle \alpha _ { k } } & { \leq \sum _ { k = 1 } ^{n} m _ { k } \triangle \alpha _ { k } \leq \sum _ { k = 1 } ^{n} M \triangle \alpha _ { k } } \\{ \Rightarrow  m [ \alpha ( b ) - \alpha ( a ) ] } & { \leq  L ( P , f , \alpha ) \leq M [ \alpha ( b ) - \alpha ( a ) ] . } \end{array}
$$

Similarly we have

$$
m [ \alpha ( b ) - \alpha ( a ) ] \leq U ( P , f , \alpha ) \leq M [ \alpha ( b ) - \alpha ( a ) ] .
$$

This shows that the sets

<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>\[\L(P,\alpha)\mid P\ \\text{is a partition of of a partition a partition pérdida[a]\]\\ \\] and \ \\\U(P,\ a partition

are bounded. So, in particular, the supremum of the first set, and the infimum of the second exist and are real numbers.

Definition 01.2. Let $f$ and $\alpha$ be as above. The upper Stieltjes integral of $f$ with respect to $\alpha$ is defined by

$$
\int _ { a } ^{\bar { b} } f d \alpha = \operatorname* { i n f } \{ U ( P , f , \alpha ) \mid P { \mathrm { ~ i s ~ a ~ p a r t i t i o n ~ o f ~ } } [ a , b ] \} .
$$

The lower Stieltjes integral of $f$ with respect to $\alpha$ is defined by

$$
\int _ { \underline { { a } } } ^{b} f d \alpha = \operatorname* { s u p } \{ L ( P , f , \alpha ) \mid P { \mathrm { ~ i s ~ a ~ p a r t i t i o n ~ o f ~ } } [ a , b ] \} .
$$

We say $f$ is Riemann-integrable (or simply integrable) with respect to $\alpha$, and write $f \in \mathcal{R}(\alpha)$, in case the lower and upper Stieltjes integrals are equal. The common value is then denoted by

$$
\int _ { a } ^{b} f d \alpha
$$

and called the Riemann-Stieltjes integral (or simply the Stieltjes integral) of $f$ with respect to $\alpha$ on $[a,b]$. The functions $f$ and $\alpha$ are respectively called the integrand and the integrator.

If we take $\alpha$ to be the function $\alpha(x)=x$, then the lower and upper Stieltjes sums, the





lower and upper Stieltjes integrals and the Riemann-Stieltjes integral are denoted by

$$
L ( P , f ) , \ U ( P , f ) , \ \int _ { a } ^{b} f , \ \int _ { a } ^{\bar { b} } f \ \ \mathrm { a n d } \ \ \int _ { a } ^{b} f .
$$

They are precisely the concepts discussed in the MAT2613 course. Thus a function $f$ is Riemann-integrable on $[a,b]$ if and only if it is Riemann-Stieltjes-integrable on $[a,b]$ with respect to $\alpha$, where $\alpha(x)=x$ for all $x\in[a,b]$.

A word about notation: The integral $\int_{a}^{b}f d \alpha$ is sometimes denoted by $\int_{a}^{b}f(x) d \alpha(x)$. In such a case it should be noted that the variable $x$ contributes nothing to the numerical value of the integral, which depends only on $f, \alpha, a$ and $b$. Thus the variable $x$ is just a "dummy variable" and can be replaced by any other convenient variable.

Definition 01.3. Let $a < b$. If the integral $\int_a^b f d\alpha$ exists, we define

$$
\int _ { b } ^{a} f d \alpha = - \int _ { a } ^{b} f d \alpha .
$$

Also, for any $a \in \mathbb{R}$ we define

$$
\int _ { a } ^{a} f d \alpha = 0 .
$$

Now let us investigate some properties of lower sums, upper sums, lower integrals and upper integrals. Our first result shows that refinement of partition increases lower sums and decreases upper sums. From that we obtain that for any two partitions, the lower sum with respect to the one partition is always less than or equal to the upper sum with respect to the other.

Theorem 01.4. Let $P$ be a partition of $[a,b]$ and $P'$ be a refinement of $P$. Then

$$
L ( P , f , \alpha ) \leq L ( P ^{\prime} , f , \alpha ) \ \ a n d \ \ U ( P ^{\prime} , f , \alpha ) \leq U ( P , f , \alpha ) .
$$

Proof. First suppose $P'$ contains just one more point than $P$. Say this point is $c$ and lies in the $k^{\text{th}}$ subinterval of $P$; so that

$$
x _ { k - 1 } < c < x _ { k } .
$$

Now put

$$
M ^{\prime} = \operatorname* { s u p } \{ f ( x ) \mid x _ { k - 1 } \leq x \leq c \} \ \ \mathrm { a n d } \ \ M ^{\prime \prime} = \operatorname* { s u p } \{ f ( x ) \mid c \leq x \leq x _ { k } \}
$$





and notice that

$$
M ^{\prime} \leq M _ { k } ( f ) \; \; \mathrm { a n d } \; \; M ^{\prime \prime} \leq M _ { k } ( f ) .
$$

Now

$$
\begin{array}{rl} { U ( P ^{\prime} , f , \alpha ) } & { = \sum _ { i = 1 } ^{k - 1} M _ { i } ( f ) \triangle \alpha _ { i } + M ^{\prime} [ \alpha ( c ) - \alpha ( x _ { k - 1 } ) ] + M ^{\prime \prime} [ \alpha ( x _ { k } ) - \alpha ( c ) ] + \sum _ { i = k + 1 } ^{n} M _ { i } ( f ) \triangle \alpha _ { i } } \\& { \leq \sum _ { i = 1 } ^{n} M _ { i } ( f ) \triangle \alpha _ { i } + M _ { k } ( f ) \left[ \alpha ( c ) - \alpha ( x _ { k - 1 } ) \right] + M _ { k } ( f ) [ \alpha ( x _ { k } ) - \alpha ( c ) ] } \\& { = \sum _ { i = 1 } ^{n} M _ { i } ( f ) \triangle \alpha _ { i } + M _ { k } ( f ) [ \alpha ( x _ { k } ) - \alpha ( x _ { k - 1 } ) ] } \\& { = \ U ( P , f , \alpha ) . } \end{array}
$$

If $P'$ has $\ell$ points more than $P$, we simply repeat this argument $\ell$ times. The proof that $L(P,f,\alpha) \leq L(P',f,\alpha)$ is similar; define $m'$ and $m''$ analogously to $M'$ and $M''$ and note that $m_k(f) \leq m'$ and $m_k(f) \leq m''$. $\square$

Corollary 01.5. Let $P$ and $Q$ be any two partitions of $[a,b]$. Then $L(P,f,\alpha) \leq U(Q,f,\alpha)$.

Proof. Put $P' = P \cup Q$ and note that $P'$ refines both $P$ and $Q$. Therefore

$$
L ( P , f , \alpha ) \leq L ( P ^{\prime} , f , \alpha ) \leq U ( P ^{\prime} , f , \alpha ) \leq U ( Q , f , \alpha ) .
$$

We have used the fact we observed earlier that for the same partition $R$ we always have $L(R,f,\alpha) \leq U(R,f,\alpha)$. The corollary tells us that if we start with any partition and then keep refining it, the lower sums increase and the upper sums decrease, but at all times the lower sums stay smaller than or equal to the upper sums. Thus, informally, integrability occurs if in the limit of refining this increasing and decreasing culminates with equality.

Theorem 01.6. $\int_{a}^{b}f d\alpha \leq \overline{\int_{a}^{b}f} d\alpha$.

Proof. Let $P$ be an arbitrary partition of $[a,b]$. For any partition $Q$ of $[a,b]$ we have

$$
L ( Q , f , \alpha ) \leq U ( P , f , \alpha ) .
$$

Therefore the real number $U(P,f,\alpha)$ is an upper bound for the set of all lower sums. It





is therefore greater than or equal to the supremum of this set; that is,

$$
\int _ { \underline { { a } } } ^{\underline { { b} } } f d \alpha \leq \int _ { a } ^{\overline { { b} } } f d \alpha .
$$

We now give a characterisation of integrability which is often useful in practice.

Theorem 01.7. A function $f$ is integrable with respect to $\alpha$ on $[a,b]$ if and only if for every $\varepsilon > 0$ there is a partition $P$ of $[a,b]$ such that $U(P,f,\alpha) - L(P,f,\alpha) < \varepsilon$.

Proof. (⇒) Let $f \in \mathcal{R}(\alpha)$ on $[a,b]$ and let $\varepsilon > 0$ be given. Since

$$
\frac { \varepsilon } { 2 } > 0 \; \; \mathrm { a n d } \; \; \int _ { a } ^{b} f d \alpha = \operatorname* { s u p } \{ L ( P , f , \alpha ) \mid P \mathrm { ~ i s ~ a ~ p a r t i t i o n ~ o f ~ } [ a , b ] \} ,
$$

there exists a partition $Q$ of $[a,b]$ such that

$$
\int _ { a } ^{b} f d \alpha - \frac { \varepsilon } { 2 } < L ( Q , f , \alpha ) .
$$

<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>Likewise, since $\int_{a}^{b}fd\alpha=\inf\{U(P,f,\alpha)\mid P\} \text{ is a partition of } [a,b]\}$, there exists a partition $R$ of $[a,b]$ such that

$$
U ( R , f , \alpha ) < \int _ { a } ^{b} f d \alpha + \frac { \varepsilon } { 2 } .
$$

From the first inequality we have

$$
\int _ { a } ^{b} f d \alpha + \frac { \varepsilon } { 2 } < L ( Q , f , \alpha ) + \varepsilon .
$$

Now let $P=Q\cup R$ and note that $P$ refines both $Q$ and $R$. Therefore

$$
U ( P , f , \alpha ) \leq U ( R , f , \alpha ) < \int _ { a } ^{b} f d \alpha + \frac { \varepsilon } { 2 } < L ( Q , f , \alpha ) + \varepsilon \leq L ( P , f , \alpha ) + \varepsilon ;
$$

whence the result follows.

(⇐) We must show that $f_{\underline{a}}^{b}fd\alpha=\int_{a}^{\overline{b}}fd\alpha$. Let $\varepsilon>0$ and choose a partition $P$ such that $U(P,f,\alpha)-L(P,f,\alpha)<\varepsilon$. Then

$$
L ( P , f , \alpha ) \leq \int _ { \underline { { a } } } ^{b} f d \alpha \leq \int _ { \underline { { a } } } ^{\bar { b} } f d \alpha \leq U ( P , f , \alpha ) ,
$$





which gives

$$
0 \leq \int _ { a } ^{\overline { { b} } } f d \alpha - \int _ { \underline { { a } } } ^{\underline { { b} } } f d \alpha \leq U ( P , f , \alpha ) - L ( P , f , \alpha ) < \varepsilon .
$$

Since this is true for every $\varepsilon > 0$ we must have

$$
\int _ { a } ^{\bar { b} } f d \alpha - \int _ { a } ^{b} f d \alpha = 0 .
$$

Next we show that a continuous function is integrable. But before doing so, let us reiterate what we said earlier. Our integrators $\alpha$ will always be assumed to be increasing; by which we mean $\alpha(x) \leq \alpha(y)$ for all $x,y$ with $x \leq y$. Note in particular that if $\alpha(a) = \alpha(b)$, then $\alpha$ is constant on the interval $[a,b]$. Thus, for any partition $P = \{x_0, \ldots, x_n\}$ of $[a,b]$, $\triangle\alpha_k = 0$. Hence $L(P,f,\alpha) = U(P,f,\alpha) = 0$ for any bounded function $f$ on $[a,b]$. Consequently, for an integrator $\alpha$ which is constant we have $f \in \mathcal{R}(\alpha)$ and $\int_a^b f d\alpha = 0$.

Theorem 01.8. If $f$ is continuous on $[a,b]$, then $f \in \mathcal{R}(\alpha)$.

Proof. If $\alpha$ is constant, there is nothing to prove. So suppose $\alpha$ is not constant, so that $\alpha(b) - \alpha(a) > 0$. Now let $\varepsilon > 0$ be given. Put

$$
\gamma = \frac { \varepsilon } { \alpha ( b ) - \alpha ( a ) } .
$$

Then $\gamma > 0$. Since $f$ is continuous on $[a,b]$ and $[a,b]$ is compact, $f$ is uniformly continuous on $[a,b]$. So there exists $\delta > 0$ such that

$$
| f ( x ) - f ( y ) | < \gamma \; \; \mathrm { w h e n e v e r } \; \; x , y \in [ a , b ] \; \; \mathrm { a n d } \; \; | x - y | < \delta .
$$

Now let $P$ be any partition of $[a,b]$ with $||P|| < \delta$. Say $P = \{x_0, x_1, \ldots, x_n\}$. For any $i = 1, 2, \ldots, n$ we have

$$
\begin{array}{rl} { M _ { i } ( f ) - m _ { i } ( f ) } & { = \ \operatorname* { s u p } \{ f ( z ) - f ( w ) : \ z , w \in [ x _ { i - 1 } , x _ { i } ] \} } \\& { \leq \ \operatorname* { s u p } \{ | f ( z ) - f ( w ) | : \ z , w \in [ x _ { i - 1 } , x _ { i } ] \} } \\& { \leq \ \gamma . } \end{array}
$$

Consequently we have

$$
U ( P , f , \alpha ) - L ( P , f , \alpha ) \ = \ \sum _ { i = 1 } ^{n} [ M _ { i } ( f ) - m _ { i } ( f ) ] \triangle \alpha _ { i }
$$





$$
\begin{array}{rl} { \leq } & { { } \gamma \sum _ { i = 1 } ^{n} \Delta \alpha _ { i } } \\{ = } & { { } \gamma [ \alpha ( b ) - \alpha ( a ) ] } \\{ < } & { { } \varepsilon . } \end{array}
$$

In view of Theorem 01.7, $f \in \mathbb{R}(\alpha)$.

We now want to prove the linear properties of the integral. For this we observe the following fact which facilitates the proofs. Note that if $A \subseteq \mathbb{R}$ is bounded above, then the set $B = \{-a \mid a \in A\}$ is bounded below and $\inf B = -\sup A$. Similarly, if $A$ is bounded below then $B = \{-a \mid a \in A\}$ is bounded above and $\sup B = -\inf A$.

Now let $f$ be bounded on $[a,b]$, $P$ be a partition of $[a,b]$ and $-f$ be the function defined by $(-f)(t)=-f(t)$ for all $t\in[a,b]$. Then $M_k(-f)=-m_k(f)$ and $m_k(-f)=-M_k(f)$ for all $k=1,2,\ldots,n$. A straightforward calculation shows that if $f\in\mathcal{R}(\alpha)$ on $[a,b]$ then $-f\in\mathcal{R}(\alpha)$ on $[a,b]$ and $\int_a^b(-f)d\alpha=-\int_a^bfd\alpha$.

Theorem 01.9. Let $f,g\in\mathcal{R}(\alpha)$ on $[a,b]$ and let $c\in\mathbb{R}$. Then

(a) $f+g\in\mathcal{R}(\alpha)$ on $[a,b]$ and

$$
\int _ { a } ^{b} \left( f + g \right) d \alpha = \int _ { a } ^{b} f d \alpha + \int _ { a } ^{b} g d \alpha .
$$

(b) $cf\in\mathcal{R}\left(\alpha\right)$ on $[a,b]$ and

$$
\int _ { a } ^{b} c f d \alpha = c \int _ { a } ^{b} f d \alpha .
$$

(c) if $f(x) \leq g(x)$ for all $x \in [a, b]$,

$$
\int _ { a } ^{b} f d \alpha \leq \int _ { a } ^{b} g d \alpha .
$$

(d) for any $d$ with $a < d < b$, $f \in R(\alpha)$ on $[a,d]$ and on $[d,b]$ and

$$
\int _ { a } ^{b} f d \alpha = \int _ { a } ^{d} f d \alpha + \int _ { a } ^{b} f d \alpha .
$$





(e) if $|f(x)| \leq M$ for all $x \in [a,b]$,

$$
\left| \int _ { a } ^{b} f d \alpha \right| \leq M \left[ a \left( b \right) - \alpha \left( a \right) \right] .
$$

Proof. We show only (a) and leave the other proofs (which are similar to that of (a)) as an exercise. For brevity denote $f+g$ by $h$. For any partition $P$ of $[a,b]$ we have

$$
\begin{array}{rlr} { L ( P , f , \alpha ) + L ( P , g , \alpha ) } & { \leq } & { L ( P , h , \alpha ) } \\& { \leq } & { U ( P , h , \alpha ) } \\& { \leq } & { U ( P , f , \alpha ) + U ( P , g , \alpha ) . } \end{array}
$$

Let $\varepsilon > 0$ be given. Find partitions $R, Q$ of $[a, b]$, such that

$$
U ( R , f , \alpha ) - L ( R , f , \alpha ) < \frac { \varepsilon } { 2 } \; \; \mathrm { a n d } \; \; U ( Q , g , \alpha ) - L ( Q , g , \alpha ) < \frac { \varepsilon } { 2 } .
$$

Let $P = R \cup Q$. Then the two inequalities above hold with $R$ and $Q$ each replaced by $P$. This then implies that

$$
U ( P , h , \alpha ) - L ( P , h , \alpha ) < \varepsilon ,
$$

and therefore $f + g \in \mathcal{R}(\alpha)$ by Theorem 01.7.

Next, with the partition $P$ as above we have

$$
U ( P , f , \alpha ) < \int _ { a } ^{b} f d \alpha + \frac { \varepsilon } { 2 } \; \; \mathrm { a n d } \; \; U ( P , g , \alpha ) < \int _ { a } ^{b} g d \alpha + \frac { \varepsilon } { 2 }
$$

which implies that

$$
\int _ { a } ^{b} h d \alpha \leq U ( P , h , \alpha ) < \int _ { a } ^{b} f d \alpha + \int _ { a } ^{b} g d \alpha + \varepsilon .
$$

Since this holds for all $\varepsilon > 0$, we have that

$$
\int _ { a } ^{b} h d \alpha \leq \int _ { a } ^{b} f d \alpha + \int _ { a } ^{b} g d \alpha .
$$

Since the inequality in (9.1.1) holds for any two function $f, g \in \mathcal{R}(\alpha)$, it holds for $-f$ and $-g$. Applying it to these two functions we get





$$
\begin{array}{rl} & { \int _ { a } ^{b} [ ( - f ) + ( - g ) ] d \alpha  \leq  \int _ { a } ^{b} ( - f ) d \alpha + \int _ { a } ^{b} ( - g ) d \alpha } \\{ \Rightarrow  } & { \int _ { a } ^{b} [ - ( f + g ) ] d \alpha  \leq  - \int _ { a } ^{b} f d \alpha - \int _ { a } ^{b} g d \alpha } \end{array}
$$

Now

$$
\begin{array}{rlr} { \Rightarrow } & { { } } & { - \int _ { a } ^{b} ( f + g ) d \alpha  \leq  \left( \int _ { a } ^{b} f d \alpha + \int _ { a } ^{b} g d \alpha \right) } \\{ \Rightarrow } & { { } } & { \int _ { a } ^{b} f d \alpha + \int _ { a } ^{b} g d \alpha  \leq  \int _ { a } ^{b} ( f + g ) d \alpha . } \end{array}
$$

Now (9.1.1) and (9.1.2) yield the desired result.

Theorem 01.10. Let $f \in \mathcal{R}(\alpha)$ and $\mathcal{R}(\beta)$ on $[a,b]$ and let $c$ be a real number with $c \geq 0$. Then

Proof. Activity.

Question: Why did we put the restriction $c \geq 0$ in the foregoing theorem?

Theorem 01.11. If $f \in \mathcal{R}(\alpha)$ on $[a,b]$, then $|f| \in \mathcal{R}(\alpha)$ on $[a,b]$ and

$$
\left| \int _ { a } ^{b} f d \alpha \right| \leq \int _ { a } ^{b} | f | d \alpha .
$$

Proof. For any partition $P$ of $[a,b]$ we have

$$
M _ { k } ( | f | ) - m _ { k } ( | f | ) \leq M _ { k } ( f ) - m _ { k } ( f )
$$

since $|f(x)| - |f(y)|| \leq |f(x) - f(y)|$ for all $x, y$. So given $\varepsilon > 0$, find a partition $P$ such that

$$
U ( P , f , \alpha ) - L ( P , f , \alpha ) < \varepsilon .
$$

Then for this partition we have

$$
U ( P , | f | , \alpha ) - L ( P , | f | , \alpha ) < \varepsilon .
$$

Thus $|f| \in \mathcal{R}(\alpha)$. Now note that $-|f| \leq f \leq |f|$, so

$$
- \int _ { a } ^{b} | f | d \alpha \leq \int _ { a } ^{b} f d \alpha \leq \int _ { a } ^{b} | f | d \alpha
$$





by Theorem 01.9(c). Since, for $r \geq 0$ we have $|w| \leq r \Leftrightarrow -r \leq w \leq r$, we conclude that

$$
\left| \int _ { a } ^{b} f d \alpha \right| \leq \int _ { a } ^{b} | f | d \alpha .
$$

Example 01.1. This example shows that $|f| \in \mathcal{R}(\alpha) \not\equiv f \in \mathcal{R}(\alpha)$. Let $\alpha(x) = 2x$ on $[0,1]$. Define $f : [0,1] \to \mathbb{R}$ by

$$
f \left( x \right) = \left\{ \begin{array}{ll} { - 1 } & { \mathrm { i f }  x \mathrm { ~ i s ~ r a t i o n a l } } \\{ 1 } & { \mathrm { i f }  x \mathrm { ~ i s ~ i r r a t i o n a l } . } \end{array} \right.
$$

For any partition $P$ of $[0,1]$,

$$
m _ { k } ( f ) = - 1 \ \ \mathrm { a n d } \ \ M _ { k } ( f ) = 1
$$

since in each subinterval $[x_{k-1},x_k]$ there are rational and irrational numbers. This shows that

$$
\begin{array}{rl} { U ( P , f , \alpha ) - L ( P , f , \alpha ) } & { = \sum _ { k = 1 } ^{n} M _ { k } ( f ) \triangle \alpha _ { k } - \sum _ { k = 1 } ^{n} m _ { k } ( f ) \triangle \alpha _ { k } } \\& { = \sum _ { k = 1 } ^{n} \triangle \alpha _ { k } + \sum _ { k = 1 } ^{n} \triangle \alpha _ { k } } \\& { = \ [ \alpha ( 1 ) - \alpha ( 0 ) ] + [ \alpha ( 1 ) - \alpha ( 0 ) ] } \\& { = \ 4 . } \end{array}
$$

So for $\varepsilon < 4$, there is no partition $P$ such that

$$
U ( P , f , \alpha ) - L ( P , f , \alpha ) < \varepsilon .
$$

Of course $|f| \in \mathcal{R}(\alpha)$ and $\int_{0}^{1} |f| d\alpha = 2$ (verify).

Theorem 01.12. If $f \in \mathcal{R}(\alpha)$ on $[a,b]$, then $f^2 \in \mathcal{R}(\alpha)$ on $[a,b]$.

Proof. For any partition $P$ of $[a,b]$,

$$
M _ { k } ( f ^{2} ) = [ M _ { k } ( | f | ) ] ^{2} \; \; \mathrm { a n d } \; \; m _ { k } ( f ^{2} ) = [ m _ { k } ( | f | ) ] ^{2} .
$$

Therefore

$$
M _ { k } ( f ^{2} ) - m _ { k } ( f ^{2} ) \ = \ [ M _ { k } ( | f | ) + m _ { k } ( | f | ) ] [ M _ { k } ( | f | ) - m _ { k } ( | f | ) ]
$$





$$
\leq \ 2 M [ M _ { k } ( | f | ) - m _ { k } ( | f | ) ]
$$

where $M > 0$ is such that $|f(x)| \leq M$ for all $x \in [a, b]$. So given $\varepsilon > 0$, if $P$ is a partition of $[a, b]$ such that

$$
U ( P , | f | , \alpha ) - L ( P , | f | , \alpha ) < \frac { \varepsilon } { 2 M }
$$

then

$$
U ( P , f ^{2} , \alpha ) - L ( P , f ^{2} , \alpha ) < \varepsilon .
$$

Theorem 01.13. If $f \in \mathcal{R}(\alpha)$ and $g \in \mathcal{R}(\alpha)$ on $[a,b]$, then the product $f \cdot g \in \mathcal{R}(\alpha)$ on $[a,b]$.

Proof. Note that $fg=\frac{1}{2}[(f+g)^2-f^2-g^2]$ and apply earlier results.

In Theorem 01.8 we saw that continuous functions are integrable. Recall that a function

$$
f : [ a , b ] \to \mathbb { R }
$$

is said to be monotonic on $[a,b]$ in case it is either increasing $(x \leq y \Rightarrow f(x) \leq f(y))$ or decreasing $(x \leq y \Rightarrow f(x) \geq f(y))$. Our next result shows that a monotonic function is always integrable with respect to a continuous integrator.

Theorem 01.14. If $f$ is monotonic on $[a,b]$ and $\alpha$ is continuous on $[a,b]$, then $f \in \mathcal{R}(\alpha)$ on $[a,b]$.

Proof. Let $\varepsilon > 0$ be given. Choose a natural number $n$ such that

$$
n > \frac { [ \alpha ( b ) - \alpha ( a ) ] | f ( b ) - f ( a ) | } { \varepsilon } .
$$

We are going to construct a partition $P$ of $[a,b]$ such that

$$
U ( P , f , \alpha ) - L ( P , f , \alpha ) < \varepsilon .
$$

If $\alpha$ is constant, there is nothing to prove. So we may assume $\alpha(a) < \alpha(b)$. Then

$$
\alpha ( a ) < \alpha ( a ) + \frac { 1 } { n } [ \alpha ( b ) - \alpha ( a ) ] < \alpha ( b ) .
$$





Since $\alpha$ is continuous on $[a,b]$ and $[a,b]$ is connected, there is a point $x_1$ such that

$$
a < x _ { 1 } < b \; \; \mathrm { a n d } \; \; \alpha ( x _ { 1 } ) = \alpha ( a ) + \frac { 1 } { n } [ \alpha ( b ) - \alpha a ] .
$$

That is,

$$
x _ { 0 } < x _ { 1 } < x _ { n } \ \ \mathrm { a n d } \ \ \alpha ( x _ { 1 } ) - \alpha ( x _ { 0 } ) = \frac { \alpha ( b ) - \alpha ( a ) } { n } ,
$$

where we have set $a = x_0$ and $b = x_n$. Repeating this process $n$ times, we obtain points $x_0 < x_1 < x_2 < \ldots < x_n$ such that

$$
\alpha ( x _ { k } ) - \alpha ( x _ { k - 1 } ) = \frac { \alpha ( b ) - \alpha ( a ) } { n } \; \; \mathrm { f o r ~ a l l } \; \; k = 1 , 2 , \ldots , n .
$$

Now $f$ is either increasing or decreasing. Say it is decreasing. Then

$$
M _ { k } ( f ) = f ( x _ { k - 1 } ) \; \; \mathrm { a n d } \; \; m _ { k } ( f ) = f ( x _ { k } )
$$

for all $k=1,2,\ldots,n$. Thus, for the partition $P=\{x_0,x_1,\ldots,x_n\}$, we have

$$
\begin{array}{rl} { U ( P , f , \alpha ) - L ( P , f , \alpha ) } & { = \sum _ { k = 1 } ^{n} \triangle \alpha _ { k } \ [ M _ { k } ( f ) - m _ { k } ( f ) ] } \\& { = \frac { \alpha ( \bar { b } ) - \alpha ( a ) } { n } \cdot \sum _ { k = 1 } ^{n} [ f ( x _ { k - 1 } ) - f ( x _ { k } ) ] } \\& { = \frac { \alpha ( b ) - \alpha a } { n } \cdot [ f ( a ) - f ( b ) ] } \\& { = \frac { \alpha ( b ) - \alpha ( a ) } { n } \cdot | f ( b ) - f ( a ) | } \\& { = \ < \varepsilon . } \end{array}
$$

If $f$ is increasing, the proof is similar.

Corollary 01.15. If $f$ is monotonic on $[a,b]$, then the Riemann integral $\int_{a}^{b}f(x)dx$ exists.

Let us take another look at Theorems 01.8 and 01.14. The first ensures integrability of a continuous function with respect to any integrator (which of course should be increasing). The second ensures integrability of any monotonic function (continuous or not) with respect to a continuous integrator. The next result allows the integrand $f$ to be discontinuous at finitely many points but then the integrator must be continuous at those points.

Theorem 01.16. If $f$ is discontinuous at finitely many points of $[a,b]$, and $\alpha$ is continuous at those points; then $f \in \mathcal{R}(\alpha)$.





Proof. Let the points where $f$ is discontinuous be $d_1, d_2, \ldots, d_m$. Let $\varepsilon > 0$ be given. Let $M > 0$ be such that $|f(x)| \leq M$ for all $x \in [a, b]$. By the continuity of $\alpha$ on the set $E = \{d_1, \ldots, d_m\}$, we can find neighbourhoods (recall that in $\mathbb{R}$ a ndb of a point contains an open interval containing the point) $(u_i, v_i)$, $i = 1, 2, \ldots, m$ of $d_i$ such that if $t \in (u_i, v_i)$ then

$$
| \alpha ( t ) - \alpha ( d _ { i } ) | < \frac { \varepsilon } { 2 ^{m + 1} } .
$$

This implies that $\alpha(v_i) - \alpha(u_i) < \frac{\varepsilon}{2^m}$ for each $i$ (verify this). Furthermore, the points $u_i, v_i$ can be chosen such that the intervals $[u_i, v_i]$ are disjoint. Notice that

$$
\sum _ { i = 1 } ^{m} [ \alpha ( v _ { i } ) - \alpha ( u _ { i } ) ] < \varepsilon .
$$

Now let $K \subseteq [a, b]$ be the set

$$
\begin{array}{rl} { K } & { = \ [ a , b ] \backslash \bigcup _ { i = 1 } ^{m} ( u _ { i } , v _ { i } ) } \\& { = \ [ a , u _ { 1 } ] \cup [ v _ { 1 } , u _ { 2 } ] \cup \cdots \cup [ u _ { m } , b ] } \end{array}
$$

where we have assumed $u_{1} < v_{1} < u_{2} < v_{2} < \ldots < u_{m} < v_{m}$; which we may without loss of generality.

Thus $K$ is compact since it is a closed and bounded subset of $\mathbb{R}$. Since $f$ is continuous on $K$, it is uniformly continuous on $K$. So there exists $\delta > 0$ such that

$$
s , t \in K \ \ \mathrm { a n d } \ \ | s - t | < \delta \Rightarrow | f ( s ) - f ( t ) | < \varepsilon .
$$

Now form a partition $P=\{x_0,x_1,\ldots,x_n\}$ as follows: each $u_i$ occurs in $P$ and each $v_i$ occurs in $P$. No point $x$ with $u_i<x<v_i$ occurs in $P$. If $x_{k-1}\notin\{u_1,u_2,\ldots,u_m\}$, then $x_k-x_{k-1}<\delta$.

Now note that $M_{k}(f)-m_{k}(f)\leq 2M$ and $M_{k}(f)-m_{k}(f)\leq \varepsilon$ unless $x_{k-1}\in\{u_{1},u_{2},\ldots,u_{m}\}$. Consequently,

$$
\begin{array}{rl} { U ( P , f , \alpha ) - L ( P , f , \alpha ) } & { \leq \ [ \alpha ( b ) - \alpha ( a ) ] \varepsilon + 2 M \varepsilon } \\& { = \ [ \alpha ( b ) - \alpha ( a ) + 2 M ] \varepsilon . } \end{array}
$$

Since $\varepsilon$ is arbitrary, it follows that $f \in \mathcal{R}(\alpha)$.

In the case of the Riemann integral, we can actually say more. We need the following definition in order to state the result we are alluding to.

Definition 01.17. A set $S \subseteq \mathbb{R}$ is said to be of measure zero if, for every $\varepsilon > 0$,





there are countably many open intervals $(a_1,b_1),(a_2,b_2),\ldots$ such that $S\subseteq\bigcup_k(a_k,b_k)$ and $\sum_k(b_k-a_k)<\varepsilon$.

In the above definition, if the collection of the covering intervals is finite, then the index $k$ runs over a finite set. If the collection is countably infinite, then $k$ goes from 1 to $\infty$.

Lemma 01.1. A countable union of sets of measure zero is a set of measure zero.

Proof. Let $S_1, S_2, \ldots$ be sets of measure zero and let $\varepsilon > 0$ be given. For each $k=1,2,\ldots$ let $S_k$ be covered by countably many intervals the sum of whose lengths is less than $\frac{\varepsilon}{2^k}$. The collection of all these coverings is a countable collection, and the sum of the lengths of all the intervals is less than $\sum_{k=1}^{\infty} \frac{\varepsilon}{2^k} = \varepsilon$. $\square$

Example 01.2. A singleton $\{x\}$ is of measure zero since the interval $\left(x-\frac{\varepsilon}{3},x+\frac{\varepsilon}{3}\right)$ has length $\frac{2\varepsilon}{3}<\varepsilon$. Hence every countable subset of $\mathbb{R}$ is of measure zero. Note that there does exist an uncountable set of measure zero. Also, a subset of a set of measure zero is itself of measure zero.

The proof of the characterisation we wish to state is rather too involved, and we will therefore not provide it. It can however be found, for instance, in T.M. Apostol's Mathematical Analysis.

Theorem 01.18. (Lebesgue's criterion for Riemann-integrability). Let $f:[a,b]\to\mathbb{R}$ be a bounded function and let $D$ denote the set of points in $[a,b]$ where $f$ is discontinuous. Then $f$ is Riemann-integrable on $[a,b]$ if and only if $D$ is of measure zero.

We end this section with the following result which is known as the change of variable technique for integration. Recall that a function $g$ is said to be strictly increasing in case

$$
x < y \Rightarrow g ( x ) < g ( y ) \ \ \mathrm { f o r ~ a l l } \ \ x , y
$$

in the domain of $g$.

Theorem 01.19. (Change of variable) Let $f \in \mathcal{R}(\alpha)$ on $[a,b]$ and $\varphi$ be a strictly increasing function defined on some interval $[c,d]$. Assume that $a = \varphi(c)$ and $b = \varphi(d)$. Define $\beta$ and $g$ on $[c,d]$ by

$$
\beta ( t ) = \alpha ( \varphi ( t ) )  a n d  g ( t ) = f ( \varphi ( t ) ) .
$$





Then $g\in\mathcal{R}(\beta)$ on $[c,d]$ and

$$
\int _ { c } ^{d} g d \beta = \int _ { a } ^{b} f d \alpha ;
$$

that is

$$
\int _ { c } ^{d} f ( g ( x ) ) d [ \alpha ( g ( x ) ) ] = \int _ { g ( c ) } ^{g ( d )} f ( t ) d \alpha ( t ) .
$$

In particular,

$$
\int _ { g ( c ) } ^{g ( d )} f ( t ) d t = \int _ { c } ^{d} f ( g ( x ) ) d [ \alpha g ( x ) ) ] .
$$

Proof. To each partition $P=\{x_0,\ldots,x_n\}$ of $[a,b]$ corresponds a partition $Q=\{y_0,\ldots,y_n\}$ of $[c,d]$ such that $x_i=\varphi(y_i)$. In fact all partitions of $[c,d]$ are of this nature. Since the values taken by $f$ on $[x_{i-1},x_i]$ are exactly the same as those taken by $g$ on $[y_{i-1},y_i]$, we have that

$$
U ( Q , g , \beta ) = U ( P , f , \alpha ) \; \; \mathrm { a n d } \; \; L ( Q , g , \beta ) = L ( P , f , \alpha ) .
$$

Since $f \in \mathcal{R}(\alpha)$ on $[a,b]$, $P$ can be chosen so that both $U(P,f,\alpha)$ and $L(P,f,\alpha)$ are close to $\int_a^b f d\alpha$. More precisely, what we mean is: given $\varepsilon > 0$ we can find a partition $P$ such that

$$
U ( P , f , \alpha ) + \frac { \varepsilon } { 2 } < \int _ { a } ^{b} f d \alpha \; \; \mathrm { a n d } \; \; L ( P , f , \alpha ) - \frac { \varepsilon } { 2 } < \int _ { a } ^{b} f d \alpha .
$$

This then yields

$$
U ( Q , g , \beta ) - L ( Q , g , \beta ) < \varepsilon ,
$$

showing that $g \in \mathcal{R}(\beta)$ on $[c,d]$. The claimed equality of integrals then follows easily. Let us now consider some examples.

Example 01.3. Let $f,\alpha$ and $\beta$ be functions defined on $[0,1]$ by

$$
\begin{array}{rl} { f \left( x \right) } & { = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  0 \leq x < \frac { 1 } { 2 } } \\{ 2 , } & { \mathrm { i f }  \frac { 1 } { 2 } \leq x \leq 1 } \end{array} \right. } \\{ \alpha \left( x \right) } & { = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  0 \leq x < \frac { 1 } { 2 } } \\{ 1 , } & { \mathrm { i f }  \frac { 1 } { 2 } \leq x < 1 } \end{array} \right. } \end{array}
$$





$$
\begin{array}{rl} { \beta \left( x \right) } & { { } = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  0 \leq x \leq \frac { 1 } { 2 } } \\{ 1 , } & { \mathrm { i f }  \frac { 1 } { 2 } < x \leq 1 } \end{array} \right. } \end{array}
$$

Let us determine if $f \in \mathcal{R}(\alpha)$ and $f \in \mathcal{R}(\beta)$ on $[0,1]$, and evaluate the integral where it exists.

Let $P=\{x_0,\ldots,x_n\}$ be a partition of $[0,1]$ such that $\frac{1}{2}\in P$. Say $\frac{1}{2}=x_j$. Now

$$
\begin{array}{rcl} { { M _ { k } ( f ) } } & { { = } } & { { 0 \mathrm { ~ f o r ~ } k = 1 , \ldots , j - 1 . } } \\{ { M _ { k } ( f ) } } & { { = } } & { { 2 \mathrm { ~ f o r ~ } k = j , \ldots , n . } } \\{ { m _ { k } ( f ) } } & { { = } } & { { 0 \mathrm { ~ f o r ~ } k = 1 , \ldots , j . } } \\{ { m _ { k } ( f ) } } & { { = } } & { { 2 \mathrm { ~ f o r ~ } k = j + 1 , \ldots , n . } } \end{array}
$$





$$
\begin{array}{rl} { \triangle \alpha _ { k } } & { = \ 0 \ \ \mathrm { f o r } \ \ k = 1 , \ldots , j - 1 . } \\{ \triangle \alpha _ { j } } & { = \ \alpha ( x _ { j } ) - \alpha ( x _ { j - 1 } ) } \\& { = \ 1 - 0 = 1 . } \\{ \triangle \alpha _ { k } } & { = \ 1 - 1 = 0 \ \ \mathrm { f o r } \ \ k = j + 1 , \ldots , n . } \\{ \triangle \beta _ { k } } & { = \ 0 \ \ \mathrm { f o r } \ \ k = 1 , \ldots , j . } \\{ \triangle \beta _ { j + 1 } } & { = \ 1 - 0 = 1 . } \\{ \triangle \beta _ { k } } & { = \ 1 - 1 = 0 \ \ \mathrm { f o r } \ \ k = j + 2 , \ldots , n . } \end{array}
$$

Thus

$$
U ( P , f , \alpha ) = 2 \; \; \mathrm { a n d } \; \; L ( P , f , \alpha ) = 0 .
$$

So for $\varepsilon < 1$, for instance, there is no partition $Q$ such that $U(Q, f, \alpha) - L(Q, f, \alpha) < \varepsilon$. If there were such a partition $Q$, then, as seen above, $\frac{1}{2}$ would not be in $Q$. Hence taking $P = Q \cup \{\frac{1}{2}\}$ would give a partition finer than $Q$ which would mean

$$
U ( P , f , \alpha ) - L ( P , f , \alpha ) \leq U ( Q , f , \alpha ) - L ( Q , f , \alpha ) < 1 ,
$$

contrary to what we have observed about partitions containing the point $\frac{1}{2}$.

On the other hand we have, for $P$ as before,

$$
\begin{array}{rl} { U ( P , f , \beta ) } & { = \ 2 \triangle \beta _ { j + 1 } , \ \mathrm { s i n c e \ o t h e r \ t e r m s \ v a n i s h } } \\& { = \ 2 , \ \mathrm { a n d } } \\{ L ( P , f , \beta ) } & { = \ 2 \triangle \beta _ { j + 1 } } \\& { = \ 2 . } \end{array}
$$

Then $f \in \mathcal{R}(\beta)$ on $[0,1]$. Since any lower sum is a lower bound for the set of all upper sums, we have

$$
2 \leq \int _ { 0 } ^{\overline { { \mathrm { I} } } } f d \beta = \int _ { 0 } ^{1} f d \beta .
$$

Similarly, since any upper sum is an upper bound for the set of all lower sums, we have

$$
\int _ { 0 } ^{1} f d \beta = \int _ { 0 } ^{1} f d \beta \leq 2 .
$$





Consequently,

$$
\int _ { 0 } ^{1} f d \beta = 2 .
$$

Example 01.4. Let $f$ be a bounded Riemann-integrable function on $[a,b]$. Let

$$
g : [ - M , M ] \to \mathbb { R }
$$

be continuous where $M=\sup\{|f(x)|: a\leq x\leq b\}$. Then $g\circ f$ is Riemann-integrable on $[a,b]$.

<font color="red">【此段建议校对(This paragraph is recommended for proofreading)】</font>To prove this let $D=\{x\in[a,b]\mid f\text{ is not continuous at }x\}$. Since $f$ is Riemann-integrable on $[a,b]$, $D$ is of measure zero. Since $g$ is continuous on the range of $f$, we have that $g\circ f$ is continuous at every point where $f$ is continuous. Consequently the set of points where $g\circ f$ is discontinuous is a subset of $D$, and hence of measure zero. Thus $g\circ f$ is Riemann-integrable on $[a,b]$.

Activity 01.1. (a) Let $f$ be nonnegative on $[a,b]$; that is, $f(x) \geq 0$ for all $x \in [a,b]$. Suppose $f$ is continuous on $[a,b]$ and $\int_{a}^{b} f(x)dx = 0$. Show that $f(x) = 0$ for all $x \in [a,b]$.

(b) Let $\alpha$ be increasing on $[a,b]$, $a \leq x_0 \leq b$ and $\alpha$ be continuous at $x_0$. Let $f : [a,b] \to \mathbb{R}$ given by

$$
f \left( x \right) = \left\{ \begin{array}{ll} { 1 , } & { \mathrm { i f }  x = x _ { 0 } } \\{ 0 , } & { \mathrm { i f }  x \neq x _ { 0 } . } \end{array} \right.
$$

Show that $f \in \mathcal{R}(\alpha)$ on $[a,b]$ and $\int_{a}^{b} f d\alpha = 0$.

(c) Define $\alpha:[0,1]\to\mathbb{R}$ by

$$
\alpha \left( x \right) = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  0 \leq x \leq \frac { 1 } { 2 } } \\{ 1 , } & { \mathrm { i f }  \frac { 1 } { 2 } < x \leq 1 . } \end{array} \right.
$$

Let $f$ be a bounded function on $[0,1]$. Show that $f \in \mathcal{R}(\alpha)$ if and only if $f$ is continuous at $\frac{1}{2}$ from the right [this means: $\lim\limits_{x \to \frac{1}{2}} f(x) = f(\frac{1}{2})$]. In this case, show that $\int_0^1 f d\alpha = f(\frac{1}{2})$.

(d) Let $\alpha$ be an increasing function on $[a,b]$ and suppose $\alpha \in \mathcal{R}(\alpha)$ on $[a,b]$. Show that $\int_{a}^{b} \alpha d\alpha = \frac{1}{2}[\alpha(b)^{2} - \alpha(a)^{2}]$.





# 02 THE FUNDAMENTAL THEOREM OF CALCUL- LUS

In this section we consider the relationship between integration and differentiation. Throughout this section we will deal with the Riemann integral. As before, all functions are assumed to be bounded.

Theorem 02.1. Let $f$ be Riemann-integrable on $[a,b]$. Define $F:[a,b]\to\mathbb{R}$ by

$$
F ( x ) = \int _ { a } ^{x} f ( t ) d t .
$$

Then $F$ is uniformly continuous on $[a,b]$. Furthermore, if $f$ is continuous at a point $x_0 \in [a,b]$, then $F$ is differentiable at $x_0$ with $F'(x_0) = f(x_0)$.

Proof. Pick $M>0$ such that $|f(t)|\leq M$ for all $t\in[a,b]$. Now if $a\leq x<y\leq b$, then

$$
| F ( y ) - F ( x ) | = \left| \int _ { x } ^{y} f ( t ) d ( t ) \right| \leq M | y - x | .
$$

Thus given $\varepsilon > 0$, if we set $\delta = \frac{\varepsilon}{M}$, then we get

$$
| x - y | < \delta \Rightarrow | F ( x ) - F ( y ) | < M \cdot \frac { \varepsilon } { M } = \varepsilon .
$$

This shows that $F$ is uniformly continuous on $[a,b]$. Now suppose $f$ is continuous at $x_0$. Given $\varepsilon > 0$, choose $\delta > 0$ such that

$$
t \in [ a , b ] \ \ \mathrm { a n d } \ \ | t - t _ { 0 } | < \delta \Rightarrow | f ( t ) - f ( x _ { 0 } ) | < \varepsilon .
$$

Thus, if $x_0 - \delta < s \leq x_0 \leq t < x_0 + \delta$ and $a \leq s < t \leq b$, then

$$
\left| \frac { F ( t ) - F ( s ) } { t - s } - f ( x _ { 0 } ) \right| = \left| \frac { 1 } { t - s } \int _ { s } ^{t} [ f ( u ) - f ( x _ { 0 } ) ] d u \right| < \varepsilon .
$$

This proves that

$$
\operatorname* { l i m } _ { h \to 0 } { \frac { F ( x _ { 0 } + h ) - F ( x _ { 0 } ) } { h } } = f ( x _ { 0 } ) .
$$





Theorem 02.2. (Fundamental Theorem of Calculus) If $f$ is Riemann-integrable on $[a,b]$ and there is a differentiable function $F$ on $[a,b]$ such that $F' = f$, then

$$
\int _ { a } ^{b} f ( x ) d x = F ( b ) - F ( a ) .
$$

Proof. Let $\varepsilon > 0$. Pick a partition $P$ of $[a,b]$ such that

$$
U ( P , f ) - L ( P , f ) < \varepsilon .
$$

Now for any $k=1,2,\ldots,n$, let $t_k\in[x_{k-1},x_k]$. Then

$$
m _ { k } ( f ) \leq f ( t _ { k } ) \leq M _ { k } ( f )
$$

which implies that

$$
L ( P , f ) \leq \sum _ { k = 1 } ^{n} f ( t _ { k } ) \triangle x _ { k } \leq U ( P , f )
$$

where $\triangle x_{k}=x_{k}-x_{k-1}$. Since $f$ is integrable we also have

$$
L ( P , f ) \leq \int _ { a } ^{b} f ( x ) d x \leq U ( P , f ) .
$$

Combining (9.2.3) and (9.2.4) yields

$$
\left| \sum _ { k = 1 } ^{n} f ( t _ { k } ) \triangle x _ { k } - \int _ { a } ^{b} f ( x ) d x \right| < \varepsilon .
$$

Now apply the Mean Value Theorem to $F$ on $[x_{k-1},x_k]$ to obtain points $s_k \in [x_{k-1},x_k]$ such that

$$
\begin{array}{rlr} { F ( x _ { k } ) - F ( x _ { k - 1 } ) } & { = } & { F ^{\prime} ( s _ { k } ) ( x _ { k } - x _ { k - 1 } ) } \\& { = } & { f ( s _ { k } ) \triangle x _ { k } . } \end{array}
$$

Summing over all $k$ we get

$$
F ( b ) - F ( a ) = \sum _ { k = 1 } ^{n} f ( s _ { k } ) \triangle x _ { k } .
$$





Since (9.2.5) holds for all points $t_k$ in $[x_{k-1},x_k]$, we have

$$
\left| F ( b ) - F ( a ) - \int _ { a } ^{b} f ( x ) d x \right| < \varepsilon .
$$

Nothing on the left hand side of (9.2.6) depends on $P$; and this inequality holds for all $\varepsilon > 0$. Thus

$$
\int _ { a } ^{b} f ( x ) d x = F ( b ) - F ( a ) .
$$

Example 02.1. Let $f:[0,1]\to\mathbb{R}$ be defined by

$$
\begin{array}{rl} { f \left( x \right) } & { = \left\{ \begin{array}{ll} { 0 , } & { \mathrm { i f }  \mathrm { i s ~ i r r a t i o n a l ~ o r ~ } x = 0 } \\{ \frac { 1 } { q } , } & { \mathrm { i f }  x = \frac { p } { q } \mathrm { ~ w h e r e ~ } p , q \mathrm { ~ a r e ~ i n t e g e r s ~ i n ~ l o w e s t ~ f o r m } . } \end{array} \right. } \end{array}
$$

Define $F:[0,1]\to\mathbb{R}$ by

$$
F ( x ) = \int _ { 0 } ^{x} f ( t ) d t .
$$

Let us show that

(i) $F(x)=0$ for all $x\in[0,1]$.

(ii) $F'$ exists on $[0,1]$, but $F'(x)\neq f(x)$ when $x$ is rational.

# Solution:

(i) We must show that $f$ is integrable on $[0,x]$ for all $x \in [0,1]$ and that the value of the integral is zero. We show integrability by proving that $f$ is continuous at every irrational point. So the set of points where $f$ is discontinuous will be a subset of $\mathbb{Q}$, and hence of measure zero.





So let $\xi$ be an irrational number in $[0,1]$ and $x_{n}=\frac{p_{n}}{q_{n}}$ be rational numbers such that $p_{n}$ and $q_{n}$ have no common factor other than 1 and $\lim_{n\to\infty}x_{n}=\xi$. We claim that the set

$$
S = \{ q _ { n } \mid n \in \mathbb { N } \}
$$

is infinite. If not, then $S=\{q_1,q_2,\ldots,q_k\}$ for some $k\in\mathbb{N}$. But now, for each

$$
i = 1 , 2 , \ldots , k ,
$$

there are at most $q_i$ integers $\ell$ such that $\frac{\ell}{q_i} \in [0,1]$. This means that the sequence $\{\frac{p_n}{q_n}\}$ has only finitely many terms. As each term of the sequence is rational, the sequence can therefore not converge to an irrational number. This contradicts the fact that

$$
\operatorname* { l i m } _ { n \to \infty } x _ { n } = \xi \in \mathbb { R } \backslash \mathbb { Q } .
$$

So, in view of the set $S$ being infinite, it follows that

$$
\operatorname* { l i m } _ { n \to \infty } { \frac { 1 } { q _ { n } } } = 0 .
$$

Consequently, if $\{t_n\}$ is a sequence in $[0,1]$ such that $t_n \to \xi$, then $f(t_n) \to 0 = f(\xi)$. So $f$ is Riemann-integrable on $[0,1]$, and therefore on $[0,x]$ for all $0 \leq x \leq 1$.

Now for any partition $P$ of $[0,x]$, $m_k(f)=0$ since between any two reals there is an irrational number. Thus

$$
\int _ { 0 } ^{x} f ( t ) d t = \int _ { \underline { { 0 } } } ^{x} f ( t ) d t = 0 .
$$

(ii) Let $x \in (0,1)$ and $h$ be sufficiently small so that $0 \leq x + h \leq 1$. Then

$$
\operatorname* { l i m } _ { h \to 0 } { \frac { F ( x + h ) - F ( x ) } { h } } = 0 .
$$

Similarly,

$$
\operatorname* { l i m } _ { h \to 0 ^{+} } { \frac { F ( 0 + h ) - F ( 0 ) } { h } } = 0 = \operatorname* { l i m } _ { h \to 0 ^{-} } { \frac { F ( 1 + h ) - F ( 1 ) } { h } } .
$$

This shows that $F'$ exists on $[0,1]$ and in fact $F'(x)=0$ for all $x\in[0,1]$. So, for $x$ rational, $x\neq0$, we have $F'(x)\neq f(x)$.





Activity 02.1. (a) With reference to the example above, show by some other method that $\int_{0}^{1}f(t)dt=0$.

(b) Why does $F'(x) \neq f(x)$ in Example 02.1 not contradict Theorem 02.1?

(c) The largest integer function is the function $[\cdot,\cdot]:\mathbb{R}\to\mathbb{Z}$ defined by

$[x] = \text{the largest integer less than or equal to } x.$

For instance, $[-3] = -3$, $[3.6] = 3$, $[-5.8] = -6$, etc. Now let $f : [0,2] \to \mathbb{R}$ be given by $f(x) = [x]$. Show that $f$ is integrable on $[0,2]$, but there is no function $F$ such that $F' = f$ on $[0,2]$.

We will examine integration and convergence next.

# 03 INTEGRATION AND CONVERGENCE

We saw in Learning Unit 7 that if $\{f_n\}$ is a sequence of integrable functions that converges pointwise to an integrable function $f$, then the sequence of integrals does not have to converge to the integral of the limit function.

If the convergence is uniform, then the result holds. The proof of this fact is the content of this section.

Theorem 03.1. Let $\alpha$ be increasing on $[a,b]$, and let $\{f_n\}$ be a sequence of functions such that $f_n \in \mathcal{R}(\alpha)$ on $[a,b]$ for each $n$. Assume that $f_n \to f$ uniformly on $[a,b]$ and define $g_n : [a,b] \to \mathbb{R}$ by

$$
g _ { n } ( x ) = \int _ { a } ^{x} f _ { n } d \alpha .
$$

Then we have:

(a) $f \in \mathcal{R}(\alpha)$ and $[a,b]$, and

(b) $g_n \to g$ uniformly on $[a,b]$, where $g(x) = \int_a^x f d\alpha$.

Proof. (a) If $\alpha$ is constant, the result is immediate. So we may assume $\alpha(a) < \alpha(b)$.

Let $\varepsilon > 0$ be given. Choose $n_0 \in \mathbb{N}$ such that

$$
n \geq n _ { 0 } \Rightarrow | f ( x ) - f _ { n } ( x ) | < \frac { \varepsilon } { 3 [ \alpha ( b ) - \alpha ( a ) ] } \; \; \mathrm { f o r ~ a l l } \; \; x \in [ a , b ] .
$$

Then, for any partition $P$ of $[a,b]$, we have

$$
| U ( P , f - f _ { n _ { 0 } } , \alpha ) | \leq \frac { \varepsilon } { 3 } \; \; \mathrm { a n d } \; \; | L ( P , f - f _ { n _ { 0 } } , \alpha ) | \leq \frac { \varepsilon } { 3 } .
$$





Since $f_{n_0} \in \mathcal{R}(\alpha)$ on $[a,b]$, there is a partition $Q$ of $[a,b]$ such that

$$
U ( Q , f _ { n _ { 0 } } , \alpha ) - L ( Q , f _ { n _ { 0 } } , \alpha ) < \frac { \varepsilon } { 3 } .
$$

For this partition $Q$ we have

$$
\begin{array}{rl} { U ( Q , f , \alpha ) - L ( Q , f , \alpha ) } & { \leq \ U ( Q , f - f _ { n _ { 0 } } , \alpha ) - L ( Q , f - f _ { n _ { 0 } } , \alpha ) + U ( Q , f _ { n _ { 0 } } , \alpha ) } \\& {  - L ( Q , f _ { n _ { 0 } } , \alpha ) } \\{ < } & { | U ( Q , f - f _ { n _ { 0 } } , \alpha ) | + | L ( Q , f - f _ { n _ { 0 } } , \alpha ) | + \frac { \varepsilon } { 3 } } \\{ \leq } & { \varepsilon . } \end{array}
$$

So $f \in \mathcal{R}(\alpha)$ on $[a,b]$.

(b) Let $\varepsilon > 0$ be given and choose $n_0 \in \mathbb{N}$ such that

$$
n \geq n _ { 0 } \Rightarrow | f _ { n } ( t ) - f ( t ) | < \frac { \varepsilon } { 2 [ \alpha ( b ) - \alpha ( a ) ] }  \mathrm { f o r ~ a l l }  t \in [ a , b ] .
$$

If $x \in [a, b]$ we have

$$
| g _ { n } ( x ) - g ( x ) | \leq \int _ { a } ^{x} | | f _ { n } - f | | d \alpha \ \mathrm { w h e r e } \ \ | | f _ { n } - f | | = \operatorname* { s u p } \{ | f _ { n } ( t ) - f ( t ) | : a \leq t \leq b \} .
$$

Thus

$$
| g _ { n } ( x ) - g ( x ) | \leq \frac { \varepsilon } { 2 } < \varepsilon \; \; \mathrm { f o r ~ a l l } \; \; x \in [ a , b ] .
$$

This proves (b).

Corollary 03.2. Let $\alpha$ be increasing on $[a,b]$ and $\{f_n\}$ be a sequence of functions such that $f_n \in \mathcal{R}(\alpha)$ for each $n=1,2,\ldots$ on $[a,b]$ and $\sum_{n=1}^{\infty} f_n = f$ uniformly on $[a,b]$. Then we have

Proof. Apply Theorem 03.1 to partial sums.

The preceding result says a uniformly convergent series can be integrated term by term.

Activity 03.1. (a) Prove Corollary 03.2.

(b) Let $f_{n}(x)=nx(1-x^{2})^{n}$ on $[0,1]$. Show, using integration, that $\{f_{n}\}$ does not converge uniformly on $[0,1]$.





We will examine improper integrals next.

# 04 IMPROPER INTEGRALS

In the previous section we have studied integrals of functions that are bounded on compact intervals $[a,b]$. In this section we consider integrals where at least one of these conditions is relaxed.

We shall not discuss improper integrals at any length, save to show how they are defined. By this we are by no means suggesting that these kinds of integrals are not important. It so happens that general integrals (improper or otherwise) are, in our view, best discussed in the context of Measure Theory; a subject matter beyond the scope of this course.

First we define an improper integral over a finite interval. We restrict the discussion to the Riemann integral. Let $f$ be a function which is defined for all $x$ such that $a < x \leq b$. Suppose for each $c$ with $a < c \leq b$ that $f$ is Riemann-integrable over $[c,b]$. If the limit of $\int_{c}^{b} f(x)dx$ as $c$ approaches $a$ from the right exists, we say this limit is the improper integral of $f$ over $[a,b]$ and denote it by $\int_{a}^{b} f$. The improper integral of a function defined on $[a,b)$ is defined analogously.

Next let $f$ be a function mapping $[a,\infty)$ into $\mathbb{R}$. If $f$ is Riemann-integrable on $[a,b]$ for every $b>a$ and the limit

$$
\operatorname* { l i m } _ { b \to \infty } \int _ { a } ^{b} f ( x ) d x
$$

exists, we say this limit is the improper integral of $f$ on $[a,\infty)$ and denote it by $\int_{a}^{\infty}f$. Thus

$$
\int _ { a } ^{\infty} f = \operatorname* { l i m } _ { b \to \infty } \int _ { a } ^{b} f ( x ) d x
$$

if the limit exists. The improper integral $\int_{-\infty}^{a}f$ is defined in a similar way; to wit,

$$
\int _ { - \infty } ^{a} = \operatorname* { l i m } _ { b \to - \infty } \int _ { b } ^{a} f ( x ) d x
$$

if the limit exists. Lastly, let $f$ be defined on the whole of $\mathbb{R}$, and suppose $f$ is Riemann-integrable on $[a,b]$ for all $a,b \in \mathbb{R}$ with $a < b$. If for some $c \in \mathbb{R}$, $\int_{-\infty}^{c} f$ and $\int_{c}^{\infty} f$ both





exist, we define the improper integral

$$
\int _ { - \infty } ^{\infty} f = \int _ { - \infty } ^{c} f + \int _ { c } ^{\infty} f .
$$

It should be noted that if $\int_{-\infty}^{\infty} f$ exists, then its value is also equal to the symmetric limit

$$
\operatorname* { l i m } _ { b \to \infty } \int _ { - b } ^{b} f ( x ) d x .
$$

However, the symmetric limit above might exist even when $\int_{-\infty}^{\infty} f$ does not exist, as the following example shows.

Example 04.1. let $f(x)=x$ on $\mathbb{R}$. Then

$$
\operatorname* { l i m } _ { b \to \infty } \int _ { - b } ^{b} f ( x ) d x = \operatorname* { l i m } _ { b \to \infty } { \frac { 1 } { 2 } } [ b ^{2} - b ^{2} ] = 0 .
$$

On the other hand, for any $a \in \mathbb{R}$, neither $\int_{-\infty}^{a} f$ nor $\int_{a}^{\infty} f$ exists. If the limit $\lim _{b \rightarrow \infty} \int_{-b}^{b} f(x) d x$ exists, it is called the Cauchy principal value of the integral $\int_{-\infty}^{\infty} f$.

Finally, refer back to the Learning Unit 9 outcome which has been placed here for your convenience. Having studied Learning Unit 9, you should be able to;

Demonstrate the concept of the Riemann-Stieltjes Integral.

Remember to check that you have achieved the outcomes for every Learning Unit as you progress through the Study Guide. This final section contained concepts/work that you should know well as you finish studying. We have now completed Learning Unit 9 which is also the final Study Unit.

# IN CONCLUSION:

Looking back you can see that the purpose of this module is for students to have gained sufficient knowledge, skills and competencies;

To have demonstrated the concept of countability of sets.

To have demonstrated the concepts of upper and lower bounds, suprema and infima.

To have demonstrated the concept of a metric space.

To have demonstrated the concept of convergence of sequences in a metric space.





To have demonstrated the concept of completeness of a metric space.

To have demonstrated the concept of a compact metric space.

To have demonstrated the concept of connectedness of a metric space.

To have demonstrated the concept of continuity on metric spaces.

To have demonstrated the concept of convergence of function spaces.

To have demonstrated the concept of linear analysis.

To have demonstrated the concept of the Riemann-Stieltjes Integral.

Final Remark 04.1. Guidelines regarding some of the activities will be provided on myUnisa.

We wish you every success in your studies.

# References:

Stoll, M., 2001, Introduction to Real Analysis. 2nd Ed. Addison-Wesley.

Apostol, T.M., 1974, Mathematical Analysis. 2nd Ed. Addison-Wesley.

Rudin, W., 1976, Principles of Mathematical Analysis. 3rd Ed. McGraw-Hill.

Howie, J.M., 2001, Real Analysis. Springer.

Pugh, C.C., 2001, Real Mathematical Analysis. Springer.
