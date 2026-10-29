



MAT3711Real Analysis: IIAssignment 1Weightage 20%UAN: 186944

| Question: | 1 | 2 | 3 | 4 | Total |
| --- | --- | --- | --- | --- | --- |
| Marks: | 20 | 40 | 20 | 20 | 100 |
| Score: |  |  |  |  |  |

Name

Student Number

Signature with date

The submitted work is completely mine.

i. Each assignment produce copies of pages containing a variety of problems collected from several textbooks, each of which is suitably referred. You are expected to work through all the exercises.

ii. You shall have to submit the questions that are stated at the end of the assignment. In most cases you shall be asked to submit at least two and at most four problems (although, each problem could have several small parts).

iii. While it is encouraging to work in groups, make use of resources from anywhere on the internet, the final answer must be your own. Rememeber: in the final examination you shall be all alone and you shall not be asked to put forward any definition or prove anything standard available from the textbooks. On the other hand, the examination shall test your ability to deduce facts from a given set of assumptions.

iv. Download this heading page and make it the first page of your submission, after completing the details of your name, student number and signature.

v. You shall have to upload one .pdf file.

vi. Copy the problem that you are to submit and then provide your answer. The answer is to be uploaded to Course website





# List of Problems from [1]

implications $A \Rightarrow C$ and $C \Rightarrow B$ can be similarly decomposed, this procedure can be used to show $A \Rightarrow C$ and $C \Rightarrow B$ are true.

For a proof by contradiction one supposes that $B$ is false, that is, $\neg B$ is true. Then one proves, using also the assumption that $A$ is true, a statement $C$ which is already known to be false. It follows from this 'contradiction' that $\neg B$ cannot be true, and hence that $B$ is true.

Instead of $A \Rightarrow B$, it is often easier to prove its contrapositive $\neg B \Rightarrow \neg A$. According to (1.5) these statements are equivalent, that is, one is true if and only if the other is true.

At this point, we prefer not to provide examples of the above concepts since they would be necessarily rather contrived. Instead the reader is encouraged to identify these structures in the proofs in following section (see, in particular, the proof of Proposition 2.6).

The preceding discussion is incomplete in that we have neither defined the word 'statement' nor explained how to tell whether a statement is true or false. A further difficulty lies in our use of the English language, which, like most languages, contains many sentences whose meaning is ambiguous. Such sentences cannot be considered to be statements in the sense of this section.

For a more solid understanding of the rules of deduction, one needs mathematical logic. This provides a formal language in which the only statements appearing are those which can be derived from a given system of 'axioms' by means of well defined constructions. These axioms are 'unprovable' statements which are recognized as fundamental universal truths.

We do not wish to go further here into such formal systems. Instead, interested readers are directed to the appendix, 'Introduction to Mathematical Logic', which contains a more precise presentation of these ideas.

# Exercises

1 "The Simpsons are coming to visit this evening," announced Maud Flanders. "The whole family — Homer, Marge and their three kids, Bart, Lisa and Maggie?" asked Ned Flanders dismayed. Maud, who never misses a chance to stimulate her husband's logical thinking, replied, "I'll explain it this way: If Homer comes then he will bring Marge too. At least one of the two children, MMPie and Lisa, are coming. Either Marge or Bart is coming, but not both. Either both Bart and Lisa are coming or neither is coming. And if MMPie comes, then Lisa and Homer are coming too. So now you know who is visiting this evening."

Who is coming to visit?

2 In the library of Count Dracula no two books contain exactly the same number of words. The number of books is greater than the total number of words in all the books. These statements suffice to determine the content of at least one book in Count Dracula's library. What is in this book?





# List of Problems from [1]

# 1.2 Sets

Proof These follow easily from the definitions. For (iii), see also Examples 1.1. ■

2.8 Remark The attentive reader will have noticed that we have not explained what a set is. Indeed the word 'set', as well as the word 'element', are undefined concepts of mathematics. Hence one needs axioms, that is, rules that are assumed to be true without proof, which say how these concepts are to be used. Statements about sets in this and following sections which are not provided with proofs can be considered to be axioms. For example, the statement 'The power set of a set is a set' is such an axiom. In this book we cannot discuss the axiomatic foundations of set theory — except perhaps in a few remarks in Section 5. Instead, we direct the interested reader to the relevant literature. Short and understandable presentations of the axiomatic foundations of set theory can be found, for example, in [Dug66], [Ebb77], [FP85] and [Hal74]. Even so, the subject requires a certain mathematical maturity and is not recommended for beginners.

We emphasize that the question of what sets and elements 'are' is unimportant. What matters are the rules with which one deals with these undefined concepts. ■

# Exercises

1 Let $X$, $Y$ and $Z$ be sets. Prove the transitivity of inclusion, that is,

$$
( X \subseteq Y ) \land ( Y \subseteq Z ) \Rightarrow X \subseteq Z ~ .
$$

2 Verify the claims of Proposition 2.4.

3 Provide a complete proof of Proposition 2.7.

4 Let $X$ and $Y$ be nonempty sets. Show that $X \times Y = Y \times X \Leftrightarrow X = Y$.

5 Let $A$ and $B$ be subsets of a set $X$. Determine the following sets:

(a) $(A^{c})^{c}$.

(b) $A \cap A^{c}$.

(c) $A \cup A^{c}$.

(d) $(A^{c} \cup B) \cap (A \cap B^{c})$.

(e) $(A^{c} \cup B) \cup (A \cap B^{c})$.

(f) $(A^{c} \cup B^{c}) \cap (A \cup B)$.

(g) $(A^{c} \cup B^{c}) \cap (A \cap B)$.

6 Let $X$ be a set. Prove

$$
\bigcup _ { A \in { \mathcal { P } } ( X ) } A = X  { \mathrm { a n d } }  \bigcap _ { A \in { \mathcal { P } } ( X ) } A = \emptyset \ .
$$





# List of Problems from [1]

14

7 Let $X$ and $A$ be subsets of a set $U$ and let $Y$ and $B$ be subsets of a set $V$. Prove the following:

(a) If $A \times B \neq \emptyset$, then $A \times B \subseteq X \times Y \Leftrightarrow (A \subseteq X) \land (B \subseteq Y)$.

(b) $(X \times Y) \cup (A \times Y) = (X \cup A) \times Y$.

(c) $(X \times Y) \cap (A \times B) = (X \cap A) \times (Y \cap B)$.

(d) $(X \times Y) \backslash (A \times B) = ((X \backslash A) \times Y) \cup (X \times (Y \backslash B))$.

8 Let $\{A_{\alpha} \; ; \; \alpha \in \mathbf{A}\}$ and $\{B_{\beta} \; ; \; \beta \in \mathbf{B}\}$ be families of subsets of a set. Prove the following:

(a) $(\bigcap_{\alpha}A_{\alpha}) \times (\bigcap_{\beta}B_{\beta}) = \bigcap_{(\alpha,\beta)} A_{\alpha} \times B_{\beta}$.

(b) $(\bigcup_{\alpha}A_{\alpha}) \times (\bigcup_{\beta}B_{\beta}) = \bigcup_{(\alpha,\beta)} A_{\alpha} \times B_{\beta}$.





# List of Problems from [1]

In short, Proposition 3.8(i')-(iv') says that the function $f^{-1}:\mathcal{P}(Y)\to\mathcal{P}(X)$ respects all set operations. The same is not true, in general, of the induced function $f:\mathcal{P}(X)\to\mathcal{P}(Y)$ as can be seen in (iii) and (iv).

Finally, we denote the set of all functions from $X$ to $Y$ by $\text{Func}(X,Y)$. Because of Remark 3.1, $\text{Func}(X,Y)$ is a subset of $\mathcal{P}(X\times Y)$. For $\text{Func}(X,Y)$ we write also $Y^X$. This is consistent with the notation $X^n$ for the $n^{th}$ Cartesian product of the set $X$ with itself, since this coincides with the set of all functions from $\{1,2,\ldots,n\}$ to $X$. If $U\subseteq Y\subseteq V$, then

$$
\mathrm { F u n c t } ( X , U ) \subseteq \mathrm { F u n c t } ( X , Y ) \subseteq \mathrm { F u n c t } ( X , V ) ~ ,
$$

where we have used the conventions of Example 3.2(f).

# Exercises

1 Prove Proposition 3.6.

2 Prove Proposition 3.8 and show that the given inclusions are, in general, proper.

3 Let $f: X \to Y$ and $g: Y \to V$ be functions. Show the following:

(a) If $f$ and $g$ are injective (surjective), then so is $g \circ f$.

(b) $f$ is injective $\Leftrightarrow \exists h: Y \to X$ such that $h \circ f = \text{id}_X$.

(c) $f$ is surjective $\Leftrightarrow \exists h: Y \to X$ such that $f \circ h = \text{id}_Y$.

4 Let $f : X \to Y$ be a function. Show that the following are equivalent:

(a) $f$ is injective.

(b) $f^{-1}(f(A)) = A, \ A \subseteq X$.

(c) $f(A \cap B) = f(A) \cap f(B), \ A, B \subseteq X$.

5 Determine the fibers of the projections $\mathrm{pr}_{k}$.

6 Prove that, for each nonempty set $X$, the function

$$
\mathcal { P } ( X ) \rightarrow \{ 0 , 1 \} ^{X} ,  A \mapsto \chi _ { A }
$$

is bijective.

7 Let $f : X \to Y$ be a function and $i : A \to X$ the inclusion of a subset $A \subseteq X$ in $X$. Show the following:

(a) $f|A=f\circ i$.

(b) $(f|A)^{-1}(B)=A\cap f^{-1}(B),\ B\subseteq Y$.





# List of Problems from [1]

(c) Clearly $\mathcal{X}:=\mathcal{P}(X)\backslash\{\emptyset\}$ contains no identity element with respect to $\cup$ whenever $X$ has more than one element. ■

The following proposition shows that an identity element is unique if it exists at all.

4.11 Proposition There is at most one identity element with respect to a given operation.

Proof Let $e$ and $e'$ be identity elements with respect to an operation $\circledast$ on a set $X$. Then, directly from the definition, we have $e=e\otimes e'=e'$. ■

4.12 Example Let $\circledast$ be an operation on a set $Y$ and $X$ a nonempty set. Then we define the operation on $\operatorname{Func}(X,Y)$ induced from $\circledast$ by

$$
( f \odot g ) ( x ) : = f ( x ) \circledast g ( x ) ~ ,  x \in X ~ .
$$

It is clear that $\odot$ is associative or commutative whenever the same is true of $\oplus$. If $Y$ has an identity element $e$ with respect to $\oplus$, then the constant function

$$
X \rightarrow Y ~ ,  x \mapsto e
$$

is the identity element of $\operatorname{Func}(X,Y)$ with respect to $\odot$. Henceforth we will use the same symbol $\circledast$ for the operation on $Y$ and for the induced operation on $\operatorname{Func}(X,Y)$. From the context it will be clear which function the symbol represents. We will soon see that this simple and natural construction is extremely useful. Important applications can be found in Examples 7.2(d), 8.2(b), 12.3(e) and 12.11(a), as well as in Remark 8.14(b). ■

# Exercises

1 Let $\sim$ and $\tilde{\sim}$ be equivalence relations on the sets $X$ and $Y$ respectively. Suppose that a function $f \in Y^{X}$ is such that $x \sim y$ implies $f(x) \sim f(y)$ for all $x, y \in X$. Prove that there is a unique function $f_{*}$ such that the diagram below is commutative.

$$
\begin{array}{c} { X \xrightarrow [ ] { f } Y } \\{ p _ { X } \xrightarrow [ ] { } f _ { * } \xrightarrow [ ] { } Y } \\{ X / \sim } \end{array}
$$

2 Verify that the function $f$ of Example 4.7(b) is not bounded.





# List of Problems from [1]

4 An operation $\circledast$ on a set $X$ is called anticommutative if it satisfies the following:

(i) There is a right identity element $r := r_X$, that is, $\exists r \in X : x \circledast r = x$, $x \in X$

i) $x \oplus y = r \Longleftrightarrow (x \oplus y) \oplus (y \oplus x) = r \Longleftrightarrow x = y$ for all $x, y \in X$

Show that, whenever $X$ has more than one element, an anticommutative operation $\circledast$ on $X$ is not commutative and has no identity element.

5 Let $\otimes$ and $\odot$ be anticommutative operations on $X$ and $Y$ respectively. Further, let $f: X \to Y$ satisfy

$$
f ( r _ { X } ) = r _ { Y } \ ,  f ( x \circledast y ) = f ( x ) \odot f ( y ) \ ,  x , y \in X \ .
$$

Prove the following:

(a) $x \sim y : \Longleftrightarrow f(x @ y) = r_Y$ defines an equivalence relation on $X$. (b) The function

$$
\widetilde { f } : \, X / \sim \rightarrow Y \ ,  [ x ] \mapsto f ( x )
$$

is well defined and injective. If, in addition, $f$ is surjective, then $\bar{f}$ is bijective.

6 Let $(X,\leq)$ be a partially ordered set with nonempty subsets $A$, $B$, $C$ and $D$. Suppose that $A$ and $B$ are bounded above and $C$ and $D$ are bounded below. Assuming that the relevant suprema and infima exist, prove the following:

(a) $\sup(A \cup B) = \sup\{\sup(A), \sup(A)\}, \ \inf(C \cup D) = \inf\{\inf(C), \inf(D)\}.$

(b) If $A \subseteq B$ and $C \subseteq D$, then

$$
\operatorname* { s u p } ( A ) \leq \operatorname* { s u p } ( B )  { \mathrm { a n d } }  \operatorname* { i n f } ( C ) \geq \operatorname* { i n f } ( D ) ~ .
$$

(c) If $A \cap B$ and $C \cap D$ are nonempty, then

$$
\operatorname* { s u p } ( A \cap B ) \leq \operatorname* { i n f } \big \{ \operatorname* { s u p } ( A ) , \operatorname* { s u p } ( B ) \big \} \, ,  \operatorname* { i n f } ( C \cap D ) \geq \operatorname* { s u p } \big \{ \operatorname* { i n f } ( C ) , \operatorname* { i n f } ( D ) \big \} \, .
$$

(d) In (a), the claim that $\sup(A \cup B) = \sup\{\sup(A), \sup(B)\}$ cannot be strengthened to $\sup(A \cup B) = \max\{\sup(A), \sup(B)\}$. (Hint: Consider the power set of a nonempty set.)

7 Let $R$ be a relation on $X$ and $S$ a relation on $Y$. Define a relation $R \times S$ on $X \times Y$ by

$$
( x , y ) ( R \times S ) ( u , v ) : \Longleftrightarrow ( x R u ) \wedge ( y S v )
$$

for $(x,y),(u,v)\in X\times Y$. Prove that, if $R$ and $S$ are equivalence relations, then so is $R\times S$.

8 Show by example that the partially ordered set $(\mathcal{P}(X), \subseteq)$ may not be totally ordered.

9 Let $\mathcal{A}$ be a nonempty subset of $\mathcal{P}(X)$. Show that $\sup(\mathcal{A}) = \bigcup_{\mathcal{A}} \mathcal{A}$ and $\inf(\mathcal{A}) = \bigcap_{\mathcal{A}} \mathcal{A}$ (see Example 4.6(a)).





# List of Problems from [1]

In the commutative case we define recursively

$$
0 \cdot a : = 0 _ { X } ~ ,  ( n + 1 ) \cdot a : = ( n \cdot a ) + a ~ ,  n \in \mathbb { N } ~ ,  a \in X ~ ,
$$

and call $n \cdot a$, $n$ times $a$. Then

$$
n \cdot a = \sum _ { k = 1 } ^{n} a : = \underbrace { a + \cdots + a } _ { n \mathrm { ~ t e r m s } } ,  n \in \mathbb { N } ^{\times} \ ,
$$

and the rules in (5.15) become

$$
n \cdot 0 _ { X } = 0 _ { X } ~ ,  n \cdot a + m \cdot a = ( n + m ) \cdot a ~ ,  m \cdot ( n \cdot a ) = ( m n ) \cdot a
$$

and

$$
n \cdot a + n \cdot b = n \cdot ( a + b )
$$

for $a,b\in X$ and $m,n\in\mathbb{N}$.

Once again we leave the simple proofs of these statements to the reader.

(b) Define a function $\mathbb{N} \rightarrow \mathbb{N}$, $n \mapsto n!$, the factorial function, recursively by

$$
0 ! : = 1 \ ,  ( n + 1 ) ! : = ( n + 1 ) n ! \ ,  n \in \mathbb { N } \ .
$$

It is not difficult to see that $n!=\prod_{k=1}^{n}k$ for $n\in\mathbb{N}^{\times}$. Note that the factorial function grows very quickly:

0! = 1, 1! = 1, 2! = 2, 3! = 6, 4! = 24, …, 10! > 3,628,000 …, 100! > 9·10$^{157}$, …, 1,000! > 4·10$^{2,567}$, …, 10,000! > 2·10$^{35,659}$, …

In Chapter VI we derive a formula which can be used to estimate this rapid growth. ■

# Exercises

1 Provide complete proofs for the rules in Remark 5.13(b) and the rules of exponents in Example 5.14(a).

2 Verify the following equalities using induction:

(a) $\sum_{k=0}^{n} k=n(n+1)/2, \ n\in\mathbb{N}$.

(b) $\sum_{k=0}^{n} k^{2}=n(n+1)(2n+1)/6, \ n\in\mathbb{N}$.

3 Verify the following inequalities using induction:

(a) For all $n \geq 2$, we have $n + 1 < 2^n$.

(b) If $a \in \mathbb{N}$ with $a \geq 3$, then $a^n > n^2$ for all $n \in \mathbb{N}$.





# List of Problems from [1]

44

5 (a) Show that $m! (n-m)!$ divides $n!$ for all $m, n \in \mathbb{N}$ with $m \leq n$. (Hint: $(n+1)! = n! (n+1-m) + n! m.$)

(b) For $m,n\in\mathbb{N}$, the binomial coefficient $\binom{n}{m}\in\mathbb{N}$ is defined by

$$
\left( \begin{array}{l} { n } \\{ m } \end{array} \right) : = \left\{ \begin{array}{cc} { \frac { n ! } { m ! \left( n - m \right) ! } ~ , } & { ~ ~ ~ m \leq n ~ , } \\{ 0 ~ , } & { ~ ~ ~ m > n ~ . } \end{array} \right.
$$

Prove the following:

(i) $\binom{n}{m}=\binom{n-m}{n}$.

(ii) $\binom{n}{m-1}+\binom{n}{m}=\binom{n+1}{m}$, $1\leq m\leq n$.

(iii) $\sum_{k=0}^{n}\binom{n}{k}=2^n$.

(iv) $\sum_{k=0}^{m}\binom{n+k}{n}=\binom{n+m+1}{n+1}$.

Remark The formula (ii) makes calculating small binomial coefficients easy when they are written down in the form of a Pascal triangle. In this triangle, the symmetry (i) and the equation (iv) are easy to see.

$$
\begin{array}{rl} & {  n = 0  1   k = 0 } \\& {  n = 1  1  1   k = 2 } \\& {  n = 2  1  2  1   k = 3 } \\& {  n = 3  1  3  3  1   k = 4  k = 5 } \\& {  n = 4  1  4 \underbrace { \phantom { k = 0 } } _ { 10 } 6  4  1   k = 5 } \\& {  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet  \bullet \bullet  \bullet  \bullet  \bullet \bullet  \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet  \bullet \bullet \bullet  \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \bullet \
$$

6 Simplify the sum

$$
S ( m , n ) : = \sum _ { k = 0 } ^{n} \Big [ \binom { m + n + k } { k } 2 ^{n + 1 - k} - \binom { m + n + k + 1 } { k } 2 ^{n - k} \Big ]
$$

for $m,n\in\mathbb{N}$. (Hint: For $1\leq j<\ell$ we have $\binom{\ell}{j}-\binom{\ell}{j-1}=\binom{\ell+1}{j}-2\binom{\ell}{j-1}$.)

7 Let $p \in \mathbb{N}$ with $p > 1$. Prove that $p$ is a prime number if and only if, for all $m, n \in \mathbb{N}$,

$$
p | m n \Rightarrow ( p | m { \mathrm { ~ o r ~ } } p | n ) \ .
$$





# List of Problems from [1]

8 (a) Let $n \in \mathbb{N}^{\times}$. Show that none of the $n$ consecutive numbers

$$
( n + 1 ) ! + 2 , ( n + 1 ) ! + 3 , \ldots , ( n + 1 ) ! + ( n + 1 )
$$

is prime. Hence there are arbitrarily large gaps in the set of prime numbers.

(b) Show that there is no greatest prime number.(Hint: Suppose that there is a greatest prime number and let $\{p_0, \ldots, p_m\}$ be the set of all prime numbers. Consider $q := p_0 \cdot \cdots \cdot p_m + 1$.)

9 The famous American mathematician M.I. Stake has finally found a mathematical proof of Thomas Jefferson's assertion that 'all men are created equal':

Proposition If $M$ is a finite set of men and $a, b \in M$, then $a$ and $b$ are equal.

Proof We prove the claim by induction on the number of men in $M$:

(a) If $M$ contains exactly one man, then the claim is obviously true.

(b) Induction step: Suppose that the claim is true for all sets of $n$ men. Let $M$ be a set containing $n+1$ men and let $a$ and $b$ be two men in $M$. We will show that $a$ and $b$ are equal. Let $M_a = M \setminus \{a\}$ and $M_b = M \setminus \{b\}$. These sets contain $n$ men each. Let $c$ be in the intersection of $M_a$ and $M_b$. Since $a, c \in M_b$, the induction hypothesis implies that $a$ and $c$ are equal. Similarly, since $b, c \in M_a$, we have that $b$ and $c$ are equal. The claim then follows from the transitivity of equality. ■

What is wrong with this proposition?

10 Show that $7$ divides $1+2^{(2^n)}+2^{(2^{n+1})}$ for all $n\in\mathbb{N}$.

11 Fix some $g \in \mathbb{N}$ with $g \geq 2$. Show that each $n \in \mathbb{N}^\times$ can be written in the form

$$
n = \sum _ { j = 0 } ^{\ell} y _ { j } g ^{j}
$$

where $y_k \in \{0, \ldots, g-1\}$ for $k \in \{0, \ldots, \ell\}$ and $y_\ell > 0$. Show further that the expression (5.16) is unique, that is, if $n = \sum_{j=0}^{m} z_j g^j$ with $z_k \in \{0, \ldots, g-1\}$ for $k \in \{0, \ldots, m\}$ and $z_m > 0$, then $\ell = m$ and $y_k = z_k$ for $k \in \{0, \ldots, \ell\}$.





# List of Problems from [1]

$\varphi: \mathbf{A} \rightarrow \bigcup_{\alpha \in \mathbf{A}} X_{\alpha}$ such that $\varphi(\alpha) \in X_{\alpha}$ for each $\alpha \in \mathbf{A}$. In place of $\varphi$ one often writes $\{x_{\alpha} : \alpha \in \mathbf{A}\}$, where, of course, $x_{\alpha} := \varphi(\alpha)$.

In the special case that $\mathbf{A}=\{1,\ldots,n\}$ for some $n\in\mathbb{N}^\times$, $\prod_{\alpha\in\mathbf{A}}X_\alpha$ is clearly identical to the product $\prod_{k=1}^nX_k$ which was introduced in Section 2. If $X_\alpha=X$ for each $\alpha\in\mathbf{A}$, then we write $X^{\mathbf{A}}:=\prod_{\alpha\in\mathbf{A}}X_\alpha$.

6.10 Remark It is clear that $\prod_{\alpha \in \mathbf{A}} X_{\alpha} = \emptyset$ if one (or more) of the $X_{\alpha}$ is empty. On the other hand, even if $X_{\alpha} \neq \emptyset$ for each $\alpha \in \mathbf{A}$, it is not possible to prove that $\prod_{\alpha \in \mathbf{A}} X_{\alpha}$ is nonempty using the axioms of set theory we have seen so far. To do that one needs to know that a function $\varphi: \mathbf{A} \to \bigcup_{\alpha \in \mathbf{A}} X_{\alpha}$ exists such that $\varphi(\alpha) \in X_{\alpha}$ for each $\alpha \in \mathbf{A}$, that is, a rule which chooses a single element from each set $X_{\alpha}$. To ensure that such a function exists one needs the axiom of choice, which we formulate as follows: For any family of sets $\{X_{\alpha} : \alpha \in \mathbf{A}\}$,

$$
\prod _ { \alpha \in \mathbf { A } } X _ { \alpha } \neq \emptyset \Longleftrightarrow ( X _ { \alpha } \neq \emptyset \; \; \forall \alpha \in \mathbf { A } ) \ .
$$

In the following we will use this naturally appearing axiom without comment. Readers who are interested in the foundations of mathematics are directed to the literature, for example, [Ebb77] and [FP85]. ■

Surprisingly, in contrast to Proposition 6.9, countably infinite products of finite sets are, in general, not countable, as the following proposition shows.

6.11 Proposition The set $\{0,1\}^{\mathbb{N}}$ is uncountable.

Proof Let $A \in \mathcal{P}(\mathbb{N})$. Then the characteristic function $\chi_A$ is an element of $\{0,1\}^{\mathbb{N}}$. It is clear that the function

$$
\mathcal { P } ( \mathbb { N } ) \rightarrow \{ 0 , 1 \} ^{\mathbb { N} } ,  A \mapsto \chi _ { A }
$$

is injective. For $\varphi \in \{0,1\}^{\mathbb{N}}$, let $A(\varphi) := \varphi^{-1}(1) \in \mathcal{P}(\mathbb{N})$. Then $\chi_{A(\varphi)} = \varphi$. This shows that the function (6.4) is surjective. (See also Exercise 3.6.) Thus $\{0,1\}^{\mathbb{N}}$ and $\mathcal{P}(\mathbb{N})$ are equimonomous and the claim follows from Corollary 6.6. ■

6.12 Corollary The sets $\{0,1\}^{\mathbb{N}}$ and $\mathcal{P}(\mathbb{N})$ are equinumerous.

# Exercises

1 Let $n \in \mathbb{N}^\times$. Prove that any injective function from $\{1, \ldots, n\}$ to itself is bijective. (Hint: Use induction on $n$. Let $f : \{1, \ldots, n+1\} \to \{1, \ldots, n+1\}$ be an injective function and $k := f(n+1)$. Consider the functions

$$
g ( j ) : = \left\{ \begin{array}{ll} { n + 1 ~ , } & { j = k ~ , } \\{ k ~ , } & { j = n + 1 ~ , } \\{ j } & { \mathrm { o t h e r w i s e } ~ , } \end{array} \right.
$$

together with $h:=g\circ f$ and $h|\{1,\dots,n\}\rangle$ Page 10 of 29





# List of Problems from [1]

2 Prove the following:

(a) Let $m, n \in \mathbb{N}^\times$. Then there is a bijective function from $\{1, \ldots, m\}$ to $\{1, \ldots, n\}$ if and only if $m = n$.

(b) If $M$ is an infinite system, then Num$(M) = \infty$ (Hint: Exercise 1).

3 Show that the number of $m$ element subsets of an $n$ element set is $\binom{n}{m}$. (Hint: Let $N$ be an $n$ element set and $M$ an $m$ element subset of $N$. From Proposition 6.3 deduce that there are $m!(n-m)!$ bijections from $\{1,\ldots,n\}$ to $N$ such that $\{1,\ldots,m\}$ goes to $M$.)

4 Let $M$ and $N$ be finite sets. How many injective functions are there from $M$ to $N$?

5 Let $X_0,\ldots,X_m$ be finite sets. Show that $X:=\bigcup_{j=0}^m X_j$ is also finite and that

$$
\mathrm { N u m } ( X ) \leq \sum _ { j = 0 } ^{m} \mathrm { N u m } ( X _ { j } ) ~ .
$$

When do we get equality?

6 Let $X_0,\ldots,X_m$ be finite sets. Prove that $X:=\prod_{j=0}^m X_j$ is also finite and that

$$
\mathrm { N u m } ( X ) = \prod _ { j = 0 } ^{m} \mathrm { N u m } ( X _ { j } ) ~ .
$$

7 Show that a nonempty set $X$ is countable if and only if there is a surjection from $\mathbb{N}$ to $X$.

8 Let $X$ be a countable set. Show that the set of all finite subsets of $X$ is countable. (Hint: Consider the functions $X^n \to \mathcal{E}_n(X)$, $(x_1,\ldots,x_n) \mapsto \{x_1,\ldots,x_n\}$ where $\mathcal{E}_n(X)$ is the set of all subsets with at most $n$ elements.)

9 Show that any subset of a finite set is finite.





# List of Problems from [1]

contexts, even when the same axioms apply. The use of familiar symbols, such as + or -, should not lead the reader to think that the familiar context is intended. One has to be clear about which axioms are in play and use only those rules which follow from them.

That a single symbol can have various context-dependent meanings may seem illogical and confusing to the beginner. Nonetheless it makes possible an elegant and concise presentation of complex ideas, and avoids overwhelming the reader with a multitude of different symbols.

# Exercises

1 Let $N$ be a subgroup of a finite group $G$. Show that $\text{Num}(G) = \text{Num}(N) \cdot \text{Num}(G/N)$ so, in particular, the order of a subgroup divides the order of the group.

2 Verify the claims in Examples 7.2(c) and (d).

3 Prove the claim in Example 7.3(b) and show that the intersection of a set of normal subgroups is also normal.

4 Prove Remark 7.6(e). Is $\operatorname{im}(\varphi)$ a normal subgroup of $G'$?

5 Let $\varphi: G \to G'$ be a homomorphism and $N'$ a normal subgroup of $G'$. Show that $\varphi^{-1}(N')$ is a normal subgroup of $G$.

6 Let $G$ be a group and $X$ a nonempty set. Then $G$ acts (from the left) on $X$ if there is a function

$$
G \times X \to X ~ , ~ ~ ~ ( g , x ) \mapsto g \cdot x
$$

such that the following hold:

(GA₁) $e \cdot x = x$ for all $x \in X$.

(GA_2) $g \cdot (h \cdot x) = (gh) \cdot x$ for all $g, h \in G$ and $x \in X$.

(a) For each $g \in G$, show that $x \mapsto g \cdot x$ is a bijection on $X$ with inverse $x \mapsto g^{-1} \cdot x$.

(b) For $x \in X$, $G \cdot x$ is called the orbit of $x$ (under the action of $G$). Show that the relation 'y is in the orbit of $x'$ is an equivalence relation on $X$.

(c) Show that if $H$ is a subgroup of $G$, then $(h,g)\mapsto h\cdot g$ and $(h,g)\mapsto hgh^{-1}$ define actions of $H$ on $G$.

(d) Show that

$$
\mathbf { S } _ { m } \times \mathbb { N } ^{m} \to \mathbb { N } ^{m} \, ,  ( \sigma , \alpha ) \mapsto \sigma \cdot \alpha : = \left( \alpha _ { \sigma ( 1 ) } , \ldots , \alpha _ { \sigma ( m ) } \right)
$$

defines an action of $\mathbf{S}_{m}$ on $\mathbb{N}^{m}$.

7 Let $G=(G,\odot)$ be a finite group of order $m$ with identity element $e$. Show that for each $g\in G$, there is a least natural number $k>0$ such that

$$
g ^{k} : = \bigodot _ { j = 1 } ^{k} g = e ~ .
$$

Show that $g^{m}=e$ for all $g\in G$. (Hint: Exercise Page 12 of 29





# List of Problems from [1]

8 The tables below define three operations on the set $G=\{e,a,b,c\}$.

| $⊙$ | e a b c | a | e a b c | e | e a b c | e | e a b c | e |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| e a | e a | b c | e | e a | b c | e | e a | b c |
| a | e | c | a | a | e | b | a | b | c |
| b | c | e | a | b | c | e | b | b | c |
| c | c | a | e | c | a | e | c | c | e |

(a) Verify that $(G,\oplus)$ and $(G,\oplus)$ are isomorphic groups.

(b) Show that the groups $(G,\odot)$ and $(G,\circledast)$ are not isomorphic.

(c) Determine all other possible group structures on $G$. Sort these groups into isomorphism classes.

9 Show that $S_3$ is not Abelian.

10 Let $G$ and $H$ be groups, and let

$$
p \colon G \times H \to G ~ , ~ ~ ~ ( g , h ) \mapsto g
$$

be the projection onto the first factor. Show that $p$ is a surjective homomorphism. Set $H' := \ker(p)$. Show that $(G \times H)/H'$ and $G$ are isomorphic groups.

11 Let $G$ be a set with an operation $\odot$ and identity element. For $g \in G$, define the function $Lg: G \to G$, $h \mapsto g \odot h$, called left translation by $g$. Suppose that

$$
L : = \{ L g \, ; \, g \in G \} \subseteq { \mathsf { S } } _ { G } ~ ,
$$

that is, each $Lg$ is bijective. Prove that

$$
( G , \odot ) { \mathrm { ~ i s ~ a ~ g r o u p } } \Leftrightarrow L { \mathrm { ~ i s ~ a ~ s u b g r o u p ~ o f ~ } } S _ { G } \ .
$$





# List of Problems from [1]

and the corresponding polynomial function (in $m$ variables) by

$$
\underline { { p } } \colon R ^{m} \to R ~ , ~ ~ ~ x \mapsto p ( x ) ~ .
$$

The function

$$
R [ X _ { 1 } , \ldots , X _ { m } ] \rightarrow R ^{( R ^ { m} ) } \, ,  p \mapsto \underline { { p } }
$$

is a homomorphism when $R^{(R^m)}$ is given the ring structure of Example 8.2(b).

(c) Let $K$ be an infinite field. Then the homomorphism (8.30) is injective.

Proof Let $p\in K[X_1,\ldots,X_m]$. Then, by Remark 7.6(d), it suffices to show that $p$ is zero if $\underline{p}(x)=0$ for all $x=(x_1,\ldots,x_m)\in K^m$. Clearly $p=\sum_\alpha p_\alpha X^\alpha$ can be written in the form

$$
p = \sum _ { j = 0 } ^{n} q _ { j } X _ { m } ^{j}
$$

for suitable $n \in \mathbb{N}$ and $q_j \in K[X_1, \ldots, X_{m-1}]$. This suggests a proof by induction on the number of indeterminates: For $m=1$, the claim is true by Remark 8.19(d). We suppose next that the claim is true for $1 \leq k \leq m-1$. Using (8.31), set

$$
p _ { ( x ^{\prime} ) } : = \sum _ { j = 0 } ^{n} q _ { j } ( x _ { 1 } , \ldots , x _ { m - 1 } ) X ^{j} \in K [ X ] ~ ,  x ^{\prime} : = ( x _ { 1 } , \ldots , x _ { m - 1 } ) \in K ^{m - 1} ~ .
$$

Because $p(x)=0$ for $x\in K^{m}$, we have $p_{(x')}(\xi)=0$ for each $\xi\in K$ and fixed $x'\in K^{m-1}$. Remark 8.19(d) implies that $p_{(x')}=0$, that is, $q_j(x_1,\ldots,x_{m-1})=0$ for all $0\leq j\leq n$. Since $x'\in K^{m-1}$ was arbitrary, we have, by induction, that $q_j(X_1,\ldots,X_{m-1})=0$ for all $j=0,\ldots,n$. This, of course, implies $p=0$. ■

Convention Let $K$ be an infinite field and $m \in \mathbb{N}^\times$. Then we identify the polynomial ring $K[X_1, \ldots, X_m]$ with its image in $K^{(K^m)}$ under the homomorphism (8.30). In other words, we identify the polynomial $p \in K[X_1, \ldots, X_m]$ with the polynomial function

$$
K ^{m} \rightarrow K ~ , ~ ~ ~ x \mapsto p ( x ) ~ .
$$

Hence $K[X_1,\ldots,X_m]$ is a subring of $K^{(K^m)}$, which we call the polynomial ring in $m$ indeterminates over $R$.

# Exercises

1 Let $a$ and $b$ be commuting elements of a ring with unity and $n \in \mathbb{N}$. Prove the following:

(a) $a^{n+1}-b^{n+1}=(a-b)\sum_{j=0}^{n}a^{j}b^{n-j}$.

(b) $a^{n+1}-1=(a-1)\sum_{j=0}^{n}a^{j}$.

Remark $\overline{\sum_{j=0}^{n}a^{j}}$ is called a finite geometric series in Page 14 of 29





# List of Problems from [1]

2 For a ring $R$ with unity, show that $(1-X)\sum_k X^k = (\sum_k X^k)(1-X) = 1$ in $R[X]$. Remark $\sum_k X^k$ is called a geometric series.

3 Show that a polynomial ring in one indeterminate over a field has no zero divisors.

4 Show that a finite field cannot be ordered.

5 Prove Remarks 8.20(a) and (b).

6 Let $R$ be a ring with unity. A subring $I$ is called an ideal of $R$ if $RI=IR=I$. An ideal is proper if it is a proper subset of $R$. Show the following:

(a) An ideal $I$ is proper if and only if $1 \notin I$.

(b) A field $K$ has exactly two ideals: $\{0\}$ and $K$.

(c) If $\varphi: R \to R'$ is a ring homomorphism, then $\ker(\varphi)$ is an ideal of $R$.

(d) The intersection of a set of ideals is an ideal.

(e) Let $I$ be an ideal of $R$ and let $R/I$ be the quotient group $(R,+)/I$. Define an operation on $R/I$ by

$$
R / I \times R / I \rightarrow R / I ~ , ~ ~ ~ ( a + I , b + I ) \mapsto a b + I ~ .
$$

Show that, with this operation as multiplication, $R/I$ is a ring and the quotient homomorphism $p\colon R\to R/I$ is a ring homomorphism.

Remark $R/I$ is called the quotient ring of $R$ modulo $I$, and, for $a \in R$, $a + I$ is the coset of $a$ modulo $I$. Instead of $a \in b + I$, we often write $a \equiv b \pmod{I}$ ('$a$ is congruent to $b$ modulo $I'$).

7 Let $R$ be a commutative ring with unity and $m \in \mathbb{N}$ with $m \geq 2$. Let

$$
\begin{array}{r} { \mathbf { S } _ { m } \times \mathbb { N } ^{m} \rightarrow \mathbb { N } ^{m} \, ,  ( \sigma , \alpha ) \mapsto \sigma \cdot \alpha } \end{array}
$$

be the action of the symmetric group $\mathbf{S}_m$ on $\mathbb{N}^m$ as in Exercise 7.6(d). Show the following: (a) The equation

$$
\sigma \cdot \sum _ { \alpha } a _ { \alpha } X ^{\alpha} : = \sum _ { \alpha } a _ { \alpha } X ^{\sigma \cdot \alpha}
$$

defines an action

$$
\mathrm { S } _ { m } \times R [ X _ { 1 } , \ldots , X _ { m } ] \to R [ X _ { 1 } , \ldots , X _ { m } ] \, ,  ( \sigma , p ) \mapsto \sigma \cdot p
$$

of $\mathbf{S}_{m}$ on the polynomial ring $R[X_{1},\ldots,X_{m}]$.

(b) For each $\sigma\in S_{m}$, $p\mapsto\sigma\cdot p$ is an automorphism of $R[X_{1},\ldots,X_{m}]$.

(c) Determine the orbits $\mathbf{S}_{3} \cdot p$ in the following cases:

(i) $p:=X_{1}$.

(ii) $p:=X_{1}^{2}$.

(iii) $p:=X_{1}^{2}X_{2}X_{3}^{3}$.

(d) A polynomial $p \in R[X_1, \ldots, X_m]$ is called symmetric if $S_m \cdot p = \{p\}$, that is, when it is fixed by all permutations. Show that $p$ is symmetric if and only if it has the form

$$
p = \sum _ { [ \alpha ] \in \mathbb { N } ^{m} / S _ { m } } a _ { [ \alpha ] } \left( \sum _ { \beta \in [ \alpha ] } X ^{\beta} \right)
$$

where $\overline{a_{[\alpha]}\in R}$ for all $[\alpha]\in\mathbb{N}^{m}/S_{m}$.





# List of Problems from [1]

(e) Determine all symmetric polynomials in 3 indeterminates of degree $\leq 3$.

(f) Show that the elementary symmetric functions

$$
\begin{array}{rl} & { s _ { 1 } : = \sum _ { 1 \leq j \leq m } X _ { j } } \\& { s _ { 2 } : = \sum _ { 1 \leq j < k \leq m } X _ { j } \cdot X _ { k } } \\& {                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
$$

are symmetric polynomials.

(g) Show that the polynomial

$$
( X - X _ { 1 } ) ( X - X _ { 2 } ) \cdots ( X - X _ { m } ) \in R [ X _ { 1 } , \ldots , X _ { m } ] [ X ]
$$

in one indeterminate $X$ over the ring $R[X_1,\dots,X_m]$ satisfies

$$
( X - X _ { 1 } ) ( X - X _ { 2 } ) \cdots ( X - X _ { m } ) = \sum _ { k = 0 } ^{m} ( - 1 ) ^{k} s _ { k } X ^{m - k}
$$

where $s_{0}:=1\in R$.

8 Let $R$ be a commutative ring with unity. For $r \in R$, define the power series $p[r] \in R[X]$ by $p[r] := \sum_k r^k X^k$. Show the following:

(a) $(p[1])^m = \sum_k \binom{m+k-1}{k}X^k, \ m \in \mathbb{N}^\times$.

(b) $\prod_{j=1}^{m} p[a_j] = \sum_k (\sum_{|\alpha|=k} a^\alpha) X^k$, $a:=(a_1,\ldots,a_m) \in R^m$, $m \in \mathbb{N}$ with $m \geq 2$.

(c) $\sum_{\frac{\alpha \in N^m}{|\alpha|=k}} 1 = \binom{m+k-1}{k}$.

(d) $\sum_{\frac{\alpha \in N^m}{|\alpha|\leq k}} 1 = \binom{m+k}{k}$.

9 Verify that, for an arbitrary set $X$, $(\mathcal{P}(X), \triangle, \cap)$ is a commutative ring with unity (see Example 8.2(f)).

10 Let $K$ be an ordered field and $a,b,c,d\in K$.

(a) Prove the inequality $\frac{|\alpha+b|}{1+|\alpha+b|}\leq\frac{|\alpha|}{1+|\alpha|}+\frac{|b|}{1+|\beta|}$.

(b) Show that, if $b>0$, $d>0$ and $\frac{a}{b}<\frac{c}{d}$; then $\frac{a}{b}<\frac{a+c}{b+d}<\frac{c}{d}$.

(c) Show that, if $a,b\in K^{\times}$, then $\left|\frac{a}{b}+\frac{h}{a}\right|\geq2$. Page 16 of 29





# List of Problems from [1]

11 Show that, in any ordered field $K$, we have

$$
\begin{array}{rl} & { \operatorname* { s u p } \{ a , b \} = \operatorname* { m a x } \{ a , b \} = \frac { a + b + | a - b | } { 2 } ~ ,  a , b \in K ~ . } \\& { \operatorname* { i n f } \{ a , b \} = \operatorname* { m i n } \{ a , b \} = \frac { a + b - | a - b | } { 2 } ~ , } \end{array}
$$

12 Let $R$ be an ordered ring and $a, b \in R$ such that $a \geq 0$ and $b \geq 0$. Suppose that there is some $n \in \mathbb{N}^\times$ such that $a^n = b^n$. Show that $a = b$.

13 Prove the statements in Examples 8.2(d) and (e).

14 Let $K$ be a field. For $p=\sum_{k=0}^{n} p_{k}X^{k} \in K[X]$, set

$$
D p : = \sum _ { k = 1 } ^{n} k p _ { k } X ^{k - 1} \in K [ X ] \ ,
$$

if $n \in \mathbb{N}^{\times}$, and $Dp = 0$, if $p$ is constant. Prove that

$$
D ( p q ) = p D q + q D p \ ,  p , q \in K [ X ] \ .
$$

15 Find $r, s \in K[X]$ with $\deg(r) < 3$ such that

$$
X ^{5} - 3 X ^{4} + 4 X ^{3} = s ( X ^{3} - X ^{2} + X - 1 ) + r \ .
$$

16 Let $K$ be a finite field. Show that the homomorphism

$$
K [ X ] \rightarrow K ^{K} ~ , ~ ~ p \mapsto \underline { { p } }
$$

from Remark 8.14(b) is not, in general, injective. (Hint: $p := X^2 - X \in \mathbb{F}_2[X]$.)





# List of Problems from [1]

Let $K$ be an ordered field and $a \in K$ with $a > 0$. If the equation $x^2 = a$ has a solution in $K$, then, by Lemma 9.8, it has exactly one positive solution. This is called the square root of $a$ and is written $\sqrt{a}$. In this case we say, 'The square root of $a$ exists in $K'$. In addition we set $\sqrt{0} := 0$.

9.9 Remarks (a) If $\sqrt{a}$ and $\sqrt{b}$ exist for some $a,b\geq0$, then $\sqrt{ab}$ also exists and $\sqrt{ab}=\sqrt{a}\sqrt{b}$.

Proof From $x^{2}=a$ and $y^{2}=b$ it follows that $(xy)^{2}=x^{2}y^{2}=ab$. This shows the existence of $\sqrt{ab}$ as well as the equation $\sqrt{ab}=\sqrt{a}\sqrt{b}$. ■

(b) For all $x \in K$, we have $|x| = \sqrt{x^2}$.

Proof If $x \geq 0$, then $\sqrt{x^2} = x$. Otherwise, if $x < 0$, then $\sqrt{x^2} = -x$. ■

(c) For $a \in \mathbb{Z}$, $\sqrt{a}$ exists in $\mathbb{Q}$ if and only if $a$ is the square of a natural number. ■

# Exercises

1 Let $K$ be a field and $a \in K^{\times}$. For $m \in \mathbb{N}$, define $a^{-m}:=(a^{-1})^{m}$.

(a) Prove that $a^{-m}=1/a^{m}$ and $a^{m-n}=a^{m}/a^{n}$ for all $m,n\in\mathbb{N}$. (b) By (a), $a^{k}$ is defined for all $k\in\mathbb{Z}$. Verify the following rules:

$$
a ^{k} a ^{\ell} = a ^{k + \ell} \, ,  a ^{k} b ^{k} = ( a b ) ^{k} \, ,  ( a ^{k} ) ^{\ell} = a ^{k \ell}
$$

for $a,b\in K^{\times}$ and $k,\ell\in\mathbb{Z}$.

2 For $n \in \mathbb{Z}$, $n\mathbb{Z}$ is an ideal of $\mathbb{Z}$, and so the quotient ring $\mathbb{Z}_n := \mathbb{Z}/n\mathbb{Z}$, $\mathbb{Z}$ modulo $n$, is well defined (see Exercise 8.6). Show the following:

(a) For $n \in \mathbb{N}^{\times}$, $\mathbb{Z}_n$ has exactly $n$ elements. What is $\mathbb{Z}_0$?

(b) If $n \geq 2$ and $n \in \mathbb{N}$ is not a prime number, then $\mathbb{Z}_n$ has zero divisors.

(c) If $p \in \mathbb{N}$ is a prime number, then $\mathbb{Z}_p$ is a field.

(Hint: (b) Proposition 5.6. (c) For $a \in \mathbb{N}$ with $0 < a < p$ one needs to find some $x \in$ such that $ax \in 1 + p\mathbb{Z}$. By repeated use of the division algorithm (Proposition 5.4) fin positive numbers $r_0, \ldots, r_k$ and $q, q_0, \ldots, q_k$ such that $a > r_0 > r_1 > \cdots > r_k$ and

$$
p = q a + r _ { 0 } \ ,  a = q _ { 0 } r _ { 0 } + r _ { 1 } \ ,  r _ { 0 } = q _ { 1 } r _ { 1 } + r _ { 2 } , \ldots , r _ { k - 2 } = q _ { k - 1 } r _ { k - 1 } + r _ { k } \ ,  r _ { k - 1 } = q _ { k } r _ { k } \ .
$$

It follows that $r_j = m_ja + n_jp$ for $j = 0, \ldots, k$ with $m_j, n_j \in \mathbb{Z}$. Show that, since $p$ is a prime number, $r_k = 1$.)

Remark Instead of $a \equiv b \pmod{n\mathbb{Z}}$ (see Exercise 8.6) we usually write $a \equiv b \pmod{n}$ for $n \in \mathbb{Z}$. Thus $a \equiv b \pmod{n}$ means that $a - b \in n\mathbb{Z}$.

3 Let $X$ be an $n$ element set. Show the following:

(a) Num$\left(\mathcal{P}(X)\right)=2^n$.

(b) Num$\left(\mathcal{P}_{\text{even}}(X)\right)=\text{Num}\left(\mathcal{P}_{\text{odd}}(X)\right)$ for $n>0$. Here $\mathcal{P}_{\text{even}}(X)$ and $\mathcal{P}_{\text{odd}}(X)$ are defined by

$$
\begin{array}{r} { \mathcal P _ { \mathrm { e v e n } } ( X ) : = \left\{ \, A \subseteq X \; ; \; \mathrm { N u m } ( A ) \equiv 0 \pmod 2 \, \right\} \, , } \\{ \mathcal P _ { \mathrm { o d d } } ( X ) : = \left\{ \, A \subseteq X \; ; \; \mathrm { N u m } ( A ) \equiv 1 \pmod 2 \, \right\} \, . } \end{array}
$$

(Hint: Exercise 6.3 and Theorem 8.4.)

$$
\mathrm { P a g e ~ 18 ~ o f ~ 29 }
$$





# List of Problems from [1]

4 An ordered field $K$ is called Archimedean if, for all $a,b\in K$ such that $a>0$, there is some $n\in\mathbb{N}$ such that $b<na$. Verify that $\mathbb{Q}:=(\mathbb{Q},\leq)$ is Archimedean.

5 Show that any rational zero of a polynomial $p=\sum_{k=0}^{n}a_{k}\mathbf{X}^{k}\in\mathbb{Z}[X]$ of degree $n\geq1$ is in $a_{n}^{-1}\mathbb{Z}$. (Hint: Consider $a_{n}^{n-1}p$.)

6 On the symmetric group $\mathbf{S}_{n}$ define the sign function by

$$
\mathrm { s i g n } \, \sigma : = \prod _ { 1 \leq j < k \leq n } \frac { \sigma ( j ) - \sigma ( k ) } { j - k } \ ,  \sigma \in S _ { n } \ .
$$

Show the following:

(a) sign($\mathbf{S}_n$) ⊆ {±1}.

(b) sign($\sigma \circ \tau$) = (sign $\sigma$)(sign $\tau$) for $\sigma, \tau \in S_n$. That is, sign is a homomorphism from $S_n$ to the multiplicative group ($\{\pm 1\}, \cdot$). The kernel of this homomorphism is called the alternating group $A_n$, that is, $A_n := \{\sigma \in S_n \; ; \; \text{sign } \sigma = 1\}$. The permutations in $A_n$ are called even, those in $S_n \setminus A_n$ are called odd.

(c) $\mathbf{A}_{n}$ has order $n!/2$ for $n \geq 2$, and 1 for $n=1$. (d) sign is surjective for $n \geq 2$.

(e) A transposition is a permutation which interchanges two numbers and leaves the others fixed. For $n \geq 2$, any permutation $\sigma \in \mathbf{S}_n$ can be represented as a composition of transpositions: $\sigma = \sigma_1 \circ \sigma_2 \circ \cdots \circ \sigma_N$, and then sign $\sigma = (-1)^N$, independent of this representation. Thus the number of transpositions in the representation is even for even permutations and odd for odd permutations.

7 Give a complete proof of Theorem 9.5.

8 For $k \in \mathbb{N}$ and $q_0, \ldots, q_k \in \mathbb{N}^\times$, the rational number

$$
\begin{array}{r} { q _ { 0 } + \frac { 1 } { q _ { 1 } + \frac { 1 } { q _ { 2 } + \frac { 1 } { q _ { 3 } + \frac { 1 } { \ddots } } } } } \\{                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             \
$$

is called a continued fraction. Show that each $x \in \mathbb{Q}$ with $x \geq 0$ can be represented as a continued fraction, and that this representation is unique if $q_k \neq 1$. (Hint: Let $x = r/r_0$ in lowest terms. By the division algorithm there are unique $q_0 \in \mathbb{N}$ and $r_1 \in \mathbb{N}$ such that $r_1 < r_0$ and $r = q_0r_0 + r_1$. If necessary, use the division algorithm on the pair $(r_0, r_1)$. Repeating as needed, construct $q_0, \ldots, q_k$.)

9 Construct an order $\prec$ on $\mathbb{Q}$ such that $(\mathbb{Q},\prec)$ is well ordered. (Hint: Consider Proposition 9.4 and (6.3).)





# List of Problems from [1]

# Intervals

An interval is a subset $J$ of $\mathbb{R}$ such that

$$
\begin{array}{r} { ( x , y \in J , \, x < y ) \Rightarrow ( z \in J \mathrm { ~ f o r ~ } x < z < y ) \, . } \end{array}
$$

Clearly $\emptyset$, $\mathbb{R}$, $\mathbb{R}^{+}$, $-\mathbb{R}^{+}$ are intervals, but $\mathbb{R}^{\times}$ is not. If $J$ is a nonempty interval, then $\inf(J) \in \bar{\mathbb{R}}$ is the left endpoint and $\sup(J) \in \bar{\mathbb{R}}$ is the right endpoint of $J$. It is an easy exercise to show that a nonempty interval $J$ is determined by its endpoints and whether or not these endpoints are in $J$. Thus $J$ is closed on the left if $a := \inf(J)$ is in $J$, and otherwise it is open on the left. Similarly, $J$ is closed on the right if $b := \sup(J)$ is in $J$, and otherwise it is open on the right. The interval $J$ is called open if it is empty or is open on the left and right. In this case we write $(a,b)$ for $J$, that is,

$$
( a , b ) = \left\{ \, x \in \mathbb { R } \; ; \; a < x < b \, \right\} \, ,  - \infty \leq a \leq b \leq \infty \, ,
$$

with the convention that $(a,a):=\emptyset$. If $J$ is closed on the left and right or is empty, then $J$ is called a closed interval which we write as

$$
[ a , b ] = \left\{ x \in \mathbb { R } \, ; \, a \leq x \leq b \right\} \, ,  - \infty < a \leq b < \infty \ .
$$

Further, we write $(a,b]$ (or $[a,b)$) if $J$ is open on the left and closed on the right (or closed on the left and open on the right). Each one element subset $\{a\}$ of $\mathbb{R}$ is a closed interval. An interval is perfect if it contains at least two points. It is bounded if both endpoints are in $\mathbb{R}$, and is unbounded otherwise. Each unbounded interval of $\mathbb{R}$, other than $\mathbb{R}$ itself, has the form $[a,\infty), (a,\infty), (-\infty,a]$ or $(-\infty,a)$ with $a\in\mathbb{R}$. If $J$ is a bounded interval, then the nonnegative number $|J|:=\sup(J)-\inf(J)$ is called the length of $J$.

# Exercises

1 Determine the following subsets of $\mathbb{R}^2$:

$$
\begin{array}{rl} & { A : = \left\{ \, ( x , y ) \in \mathbb { R } ^{2} \; ; \; | x - 1 | + | y + 1 | \leq 1 \right\} \ , } \\& { B : = \left\{ \, ( x , y ) \in \mathbb { R } ^{2} \; ; \; 2 x ^{2} + y ^{2} > 1 , \ | x | \leq | y | \right\} \ , } \\& { C : = \left\{ \, ( x , y ) \in \mathbb { R } ^{2} \; ; \; x ^{2} - y ^{2} > 1 , \ x - 2 y < 1 , \ y - 2 x < 1 \right\} \ . } \end{array}
$$

2 (a) Show that

$$
\mathbb { Q } ( \sqrt { 2 } ) : = \{ a + b \sqrt { 2 } \; ; \; a , b \in \mathbb { Q } \}
$$

is a subfield of $\mathbb{R}$ which contains $\mathbb{Q}$ but which is not order complete. Is $\sqrt{3}$ in $\mathbb{Q}(\sqrt{2})$?

(b) Prove that $\mathbb{Q}$ is the smallest subfield of $\mathbb{R}$.

3 For $a,b\in\mathbb{R}^{+}$ and $r,s\in\mathbb{Q}$, show the following: (a) $a^{r+s}=a^{r}a^{s}$, (b) $(a^{r})^{s}=a^{rs}$, (c) $a^{r}b^{r}=(ab)^{r}$.

4 For $m, n \in \mathbb{N}^{\times}$ and $a, b \in \mathbb{R}^{+}$, show the following:

(a) $a^{1/m} < a^{1/n}$, if $m < n$ and $0 < a < 1$.

(b) $a^{1/m} > a^{1/n}$, if $m < n$ and $a > 1$. Page 20 of 29





# List of Problems from [1]

5 Let $f : \mathbb{R} \to \mathbb{R}$ be an increasing function. Suppose that $a, b \in \mathbb{R}$ satisfy $a < b$, $f(a) > a$ and $f(b) < b$. Prove that $f$ has at least one fixed point, that is, there is some $x \in \mathbb{R}$ such that $f(x) = x$. (Hint: Consider $z := \sup\{ y \in \mathbb{R} \; ; \; a \leq y \leq b, \; y \leq f(y) \}$ and $f(z).)$

6 Prove Bernoulli's inequality: If $x \in \mathbb{R}$ with $x > -1$ and $n \in \mathbb{N}$, then

$$
( 1 + x ) ^{n} \geq 1 + n x ~ .
$$

7 Let $M \subseteq \mathbb{R}$ be nonempty with $\inf(M) > 0$. Show that the set $M' := \{1/x; x \in M\}$ is bounded above and that $\sup(M') = 1/\inf(M)$.

8 For nonempty subsets $A$ and $B$ of $\mathbb{R}$, prove the following:

$$
\operatorname* { s u p } ( A + B ) = \operatorname* { s u p } ( A ) + \operatorname* { s u p } ( B ) ~ ,  \operatorname* { i n f } ( A + B ) = \operatorname* { i n f } ( A ) + \operatorname* { i n f } ( B ) ~ .
$$

9 (a) For nonempty subsets $A$ and $B$ of $(0,\infty)$, prove the following:

$$
\operatorname* { s u p } ( A \cdot B ) = \operatorname* { s u p } ( A ) \cdot \operatorname* { s u p } ( B ) \, ,  \operatorname* { i n f } ( A \cdot B ) = \operatorname* { i n f } ( A ) \cdot \operatorname* { i n f } ( B ) \, .
$$

(b) Find nonempty subsets $A$ and $B$ of $\mathbb{R}$ such that

$$
\operatorname* { s u p } ( A ) \cdot \operatorname* { s u p } ( B ) < \operatorname* { s u p } ( A \cdot B )  \mathrm { a n d }  \operatorname* { i n f } ( A ) \cdot \operatorname* { i n f } ( B ) > \operatorname* { i n f } ( A \cdot B ) \ .
$$

10 Let $n \in \mathbb{N}^{\times}$ and $x = (x_1, \ldots, x_n) \in [\mathbb{R}^{+}]^n$. Then the geometric mean and arithmetic mean of $x_1, \ldots, x_n$ are defined by $g(x) := \sqrt[n]{\prod_{j=1}^n x_j}$ and $a(x) := (1/n)\sum_{j=1}^n x_j$ respectively. Prove that $g(x) \leq a(x)$ (inequality of the geometric and arithmetic means).

11 For $x=(x_1,\ldots,x_n)$ and $y=(y_1,\ldots,y_n)$ in $\mathbb{R}^n$, define $x\cdot y:=\sum_{j=1}^{n}x_jy_j$. Prove that

$$
\begin{array}{r} { | \sqrt [ \alpha ] { x ^{\alpha} } | \leq ( x \bullet \alpha ) / | \alpha | \; . } \end{array}
$$

for all $x \in [\mathbb{R}^+]^n$ and $\alpha \in \mathbb{N}^n$ (inequality of the weighted geometric and weighted arithmetic means).

12 Verify that $\mathbb{R}$ is an Archimedean ordered field. See Exercise 9.4.

13 Let $(K,\leq)$ be an ordered extension field of $(\mathbb{Q},\leq)$ with the property that, for each $a\in K$ such that $a>0$, there is some $r\in\mathbb{Q}$ such that $0<r<a$. Show that $K$ is an Archimedean ordered field. See Exercise 9.4.

14 Prove that an ordered field $K$ is Archimedean if and only if $\{n \cdot 1 : n \in \mathbb{N}\}$ is not bounded above in $K$. See Exercise 9.4.

15 Let $K$ be the field of rational functions with coefficients in $\mathbb{R}$ (see Remark 9.3(c)). Then for each $f \in K$ there are unique polynomials $p = \sum_{k=0}^{n} p_k X^k$ and $q = \sum_{k=0}^{m} q_k X^k$ such that $q_m = 1$ and $f = p/q$ is in lowest terms (that is, $p$ and $q$ have no nonconstant factors in common). With this notation let

$$
\mathcal { P } : = \left\{ f \in K ~ ; ~ p _ { n } \geq 0 \right\} .
$$

Finally set

$$
f \prec g : \Longleftrightarrow g - f \in { \mathcal P } ~ .
$$





# List of Problems from [1]

16 For each $n \in \mathbb{N}$, let $I_n$ be a nonempty closed interval in $\mathbb{R}$. The family $\{ I_n \; ; \; n \in \mathbb{N} \}$ is called a nest of intervals if the following conditions hold:

(i) $I_{n+1} \subseteq I_n$ for all $n \in \mathbb{N}$.

(ii) For each $\varepsilon > 0$, there is some $n \in \mathbb{N}$ such that $|I_n| < \varepsilon$.

(a) Show that, for each nest of intervals $\{I_n : n \in \mathbb{N}\}$, there is a unique $x \in \mathbb{R}$ such that $x \in \bigcap_n I_n$.

(b) For each $x \in \mathbb{R}$, show that there is a nest of intervals $\{I_n : n \in \mathbb{N}\}$ with rational endpoints such that $\{x\} = \bigcap_n I_n$.





# List of Problems from [1]

# Exercises

1 (a) Show that for each $z \in \mathbb{C} \backslash (-\infty, 0]$ there is a unique $w \in \mathbb{C}$ such that $w^2 = z$ and $\text{Re}(w) > 0$. The element $w$ is called the principal square root of $z$ and is written $\sqrt{z}$.

(b) Show that, for all $z \in \mathbb{C} \backslash (-\infty, 0]$,

$$
\sqrt { z } = \sqrt { ( | z | + \mathrm { R e } \, z ) / 2 } + i \, \mathrm { s i g n } ( \mathrm { I m } \, z ) \sqrt { ( | z | - \mathrm { R e } \, z ) / 2 } \ .
$$

(c) Calculate $\sqrt{i}$.

What are the other solutions of the equation $w^{2}=i$?

2 Calculate $\bar{z}$, $|z|$, Re $z$, Im $z$, Re(1/z) and Im(1/z) for $z \in \left\{\frac{12+5i}{2+3i}, \sqrt{i}\right\}$.

3 Sketch the following sets in the coordinate plane:

$$
\begin{array}{rl} & { A : = \left\{ \, z \in \mathbb { C } \ ; \ | z - 1 | \leq | z + 1 | \, \right\} } \\& { B : = \left\{ \, z \in \mathbb { C } \ ; \ | z + 1 | \leq | z - i | \leq | z - 1 | \, \right\} } \\& { C : = \left\{ \, z \in \mathbb { C } \ ; \ 3 z \overline { { z } } - 6 z - 6 \overline { { z } } + 9 = 0 \, \right\} } \end{array}
$$

4 Determine all solutions of the equations $z^{4}=1$ and $z^{3}=1$ in $\mathbb{C}$.

5 Give a proof of Proposition 11.3.

6 Let $m \in \mathbb{N}^\times$ and $U_j \subseteq \mathbb{C}$ for $0 \leq j \leq m$. Suppose that $a \in \mathbb{C}$ has the property that, for each $j$, there is some $r_j > 0$ such that $\mathbb{E}(a,r_j) \subseteq U_j$. Show that $\mathbb{E}(a,r) \subseteq \bigcap_{j=0}^m U_j$ for some $r > 0$.

7 For $a \in \mathbb{K}$ and $r > 0$, describe the set $\bar{\mathbb{B}}_{\mathbb{K}}(a, r) \backslash \mathbb{B}_{\mathbb{K}}(a, r)$.

8 Show that the identity function and $z\mapsto\overline{z}$ are the only field automorphisms of $\mathbb{C}$ which leave the elements of $\mathbb{R}$ fixed. (Hint: For an automorphism $\varphi$, consider $\varphi(i)$.)

9 Show that $S^{1}:=\{z\in\mathbb{C};|z|=1\}$ is a subgroup of the multiplicative group $(\mathbb{C}^{\times},\cdot)$, the circle group.

10 Let $\mathbb{R}^{2\times2}$ be the noncommutative ring of real $2\times2$ matrices. Show that the set $C$ of matrices of the form

$$
\left[ \begin{array}{ll} { a } & { - b } \\{ b } & { a } \end{array} \right]
$$

is a subfield of $\mathbb{R}^{2\times2}$, and that the function

$$
\mathbb { R } + i \, \mathbb { R } \rightarrow \mathbb { R } ^{2 \times 2} \ ,  a + i \, b \mapsto { \left[ \begin{array}{ll} { a } & { - b } \\{ b } & { a } \end{array} \right] }
$$

is an isomorphism from $\mathbb{C}$ to $C$. (The necessary properties of matrices can be found in any book on linear algebra.)

$$
\begin{array}{rl} & { 11  \mathrm { F o r } \, p = X ^{n} + a _ { n - 1 } X ^{n - 1} + \cdots + a _ { 1 } X + a _ { 0 } \in \mathbb { C } [ X ] , \, \mathrm { d e f i n e } \, R : = 1 + \sum _ { k = 0 } ^{n - 1} | a _ { k } | . \mathrm { S h o w } } \\& { \mathrm { t h a t } \, \, | p ( z ) | > R \, \mathrm { f o r ~ a l l ~ } z \in \mathbb { C } \mathrm { ~ s u c h ~ t h a t } \, | z | > R . \mathrm { ~ P a g e ~ 23 ~ o f ~ 29 } } \end{array}
$$





# List of Problems from [1]

110

12 Prove the Parallelogram Identity in $\mathbb{C}$:

$$
| z + w | ^{2} + | z - w | ^{2} = 2 ( | z | ^{2} + | w | ^{2} ) \ ,  z , w \in \mathbb { C } \ .
$$

13 Describe the function $\mathbb{C}^\times \to \mathbb{C}^\times$, $z \mapsto 1/z$ geometrically.

14 Determine all zeros of the polynomial $X^{4}-2X^{3}-X^{2}+2X+1\in\mathbb{C}[X]$. (Hint: Multiply the polynomial by $1/X^{2}$ and substitute $Y=X-1/X$.)

15 Cubic Equations Let $k$ be a cubic polynomial in $\mathbb{C}$ with leading coefficient 1, that is,

$$
k = X ^{3} + a X ^{2} + b X + c \ .
$$

To find the zeros of $k$, we first substitute $Y = X + a/3$ to get

$$
\begin{array}{r} { Y ^{3} + p Y + q \in \mathbb { C } [ X ] ~ . } \end{array}
$$

Determine the coefficients $p$ and $q$ in terms of $a$, $b$ and $c$. Suppose that there exist³ $d, u, v \in \mathbb{C}$ such that

$$
d ^{2} = \left( \frac { q } { 2 } \right) ^{2} + \left( \frac { p } { 3 } \right) ^{3} ~ , ~ ~ ~ u ^{3} = - \frac { q } { 2 } + d ~ , ~ ~ v ^{3} = - \frac { q } { 2 } - d ~ .
$$

Show that $-3uv/p$ is a third root of unity, that is, $(-3uv/p)^3 = 1$, and so we can choose $u$ and $v$ such that $3uv = -p$. Now let $\xi \neq 1$ satisfy $\xi^3 = 1$ (see Exercise 4). Show that

$$
y _ { 1 } : = u + v \ ,  y _ { 2 } : = \xi u + \xi ^{2} v \ ,  y _ { 3 } : = \xi ^{2} u + \xi v
$$

are the solutions of the equation $y^{3}+py+q=0$.





# List of Problems from [1]

12.14 Remarks (a) For $f \in \mathbb{K}^{\mathbb{K}}$, let

$$
r _ { m } [ f ; x _ { 0 } ; h ] : = f - N _ { m } [ f ; x _ { 0 } ; h ]
$$

be the 'error function'. By construction, $f : \mathbb{K} \to \mathbb{K}$ is 'approximated' by the interpolation polynomial $N_m[f; x_0; h]$ so that the error is zero at the points $x_0 + jh$, $0 \leq j \leq m$. In Section IV.3 we will see how the error can be controlled for certain large classes of functions. In addition, we will show in Section V.4 that quite general functions can be approximated 'arbitrarily closely' (in a suitable sense) by polynomials.

(b) Obviously (12.15) also makes sense for arbitrary $f \in E^{\mathbb{R}}$, and

$$
N _ { m } [ f ; x _ { 0 } ; h ] ( x _ { j } ) = f ( x _ { j } ) \ ,  0 \leq j \leq m \ .
$$

(c) A function $f \in E^{\mathbb{N}}$ is called an arithmetic sequence of order $k \in \mathbb{N}^{\times}$ if $\triangle^{k} f$ is constant, that is, if $\triangle^{k+1} f = 0$. From (12.15) and Remark 8.19(c), it follows that, for each polynomial $p \in \mathbb{K}_{k}[X]$, each $h \in \mathbb{K}^{\times}$ and each $x_{0} \in \mathbb{K}$, the function $\mathbb{N} \rightarrow \mathbb{K}$, $n \mapsto p(x_{0} + hn)$ is an arithmetic sequence of order $k$. In particular, for each $k \in \mathbb{N}$, the 'power sequence' $\mathbb{N} \rightarrow \mathbb{N}$, $n \mapsto n^{k}$ is an arithmetic sequence of order $k$.

For arithmetic sequences of order $k$, the summation formula (12.14) has a simple form:

$$
\sum _ { j = 0 } ^{n} f _ { j } = \sum _ { i = 0 } ^{k} { \binom { n + 1 } { i + 1 } } \triangle ^{i} f _ { 0 } ~ ,  n \in \mathbb { N } ~ .
$$

In particular, for the 'power summations' we have

$$
\begin{array}{rl} & { \displaystyle \sum _ { j = 0 } ^{n} j = \binom { n + 1 } { 2 } = \frac { n ( n + 1 ) } { 2 } ~ , } \\& { \displaystyle \sum _ { j = 0 } ^{n} j ^{2} = \binom { n + 1 } { 2 } + 2 \binom { n + 1 } { 3 } = \frac { n ( n + 1 ) ( 2 n + 1 ) } { 6 } ~ , } \\& { \displaystyle \sum _ { j = 0 } ^{n} j ^{3} = \binom { n + 1 } { 2 } + 6 \binom { n + 1 } { 3 } + 6 \binom { n + 1 } { 4 } = \frac { n ^{2} ( n + 1 ) ^{2} } { 4 } = \left( \sum _ { j = 0 } ^{n} j \right) ^{2} , } \end{array}
$$

which the reader can easily confirm. ■

# Exercises

In the following $K$ is a field and $E$, $E_j$, $F$, $F_j$, $1 \leq j \leq m$ are vector spaces over $K$.

1 (a) Determine all subspaces of $K$.(b) What is the dimension of $\mathbb{C}$ over $\mathbb{R}$?

2 (a) Show that the projections $\operatorname{pr}_{k}: E_{1} \times \cdots \times E_{m} \rightarrow E_{k}$ and the canonical injections

$$
i _ { k } \colon E _ { k } \to E _ { 1 } \times \cdots \times E _ { m } ~ , ~ ~ ~ x \mapsto ( 0 , \ldots , 0 , x , 0 , \ldots , 0 ) \tag { k }
$$

are linear and determine the corresponding kernels and images.

(b) $\overline{\mathrm{Show}}$ that $E_{k} \cong \operatorname{im}(i_{k})$, $1 \leq k \leq m$. Page 25 of 29





# List of Problems from [1]

3 Show that $T: \mathbb{R}^2 \to \mathbb{R}^2$, $(x,y) \mapsto (x-y,y-x)$ is linear. Determine the subspaces $\ker(T)$ and $\operatorname{im}(T)$.

4 Suppose that the diagram below is commutative.

$$
\begin{array}{c} { E \xrightarrow [ ] { T } F } \\{ P \xrightarrow [ ] { } E _ { 1 } } \end{array}
$$

If $T$, $P$ and $Q$ are linear and $P$ is surjective, is $S$ also linear?

5 Let $X$ be a nonempty set and $x_0 \in X$. Show that the function $\delta_{x_0} : E^{\mathcal{X}} \to E$ defined by

$$
\delta _ { x _ { 0 } } ( f ) : = f ( x _ { 0 } ) \ ,  f \in E ^{X} \ ,
$$

is linear.

6 Let $E$ and $F$ be finite dimensional. Show that $\dim(E \times F) = \dim(E) \dim(F)$.

7 For $T \in \text{Hom}(E, F)$, prove that $E/\ker(T) \cong \text{im}(T)$.

8 Let $x_0,\ldots,x_m\in\mathbb{K}$ be distinct. Show that the following Cauchy equations hold for the Lagrange polynomials $\ell_j:=\ell_j[x_0,\ldots,x_m]\in\mathbb{K}_m[X]$:

(a) $\sum_{j=0}^{m}\ell_{j}=1$ (= $X^{0}$).

(b) $(X-y)^{k}=\sum_{j=0}^{m}(x_{j}-y)^{k}\ell_{j}$, $y\in\mathbb{K}$, $1\leq k\leq m$.

9 Show that, for distinct $x_0,\ldots,x_m\in\mathbb{K}$, the Lagrange polynomials $\ell_j$, $0\leq j\leq m$, and the Newton polynomials $\omega_j$, $0\leq j\leq m$, form bases of $\mathbb{K}_m[X]$.

10 Let $x_0,\ldots,x_m\in\mathbb{K}$ be distinct and $f\in\mathbb{K}^\mathbb{K}$. Prove the following:

(a) The coefficients $a_{j}$ of the Newton polynomials in Remark 12.10(b) are given l

$$
a _ { n } = \sum _ { j = 0 } ^{n} \frac { f ( x _ { j } ) } { \prod _ { k \neq j } ^{n} \left( x _ { j } - x _ { k } \right) } = : f [ x _ { 0 } , \ldots , x _ { n } ] \, ,  0 \leq n \leq m \, .
$$

(b) The coefficients $f[x_0,\ldots,x_n]$ are symmetric in their arguments. That is, if $0\leq n\leq m$ and $\sigma$ is a permutation of $\{0,1,\ldots,n\}$, then $f[x_0,\ldots,x_n]=f[x_{\sigma(0)},\ldots,x_{\sigma(n)}]$.

$$
( \mathrm { c } ) ~ f [ x _ { 0 } , \ldots , x _ { n } ] = \frac { f [ x _ { 0 } , \ldots , x _ { n - 1 } ] - f [ x _ { 1 } , \ldots , x _ { n } ] } { x _ { 0 } - x _ { n } } , ~ 1 \leq n \leq m .
$$

Remark Because of (c), the numbers $f[x_0,\ldots,x_n]$ are easy to calculate recursively.

(Hint: (a) $p_{n}[f,x_{0},\ldots,x_{n}]=L_{n}[f,x_{0},\ldots,x_{n}]$, $0\leq n\leq m$.

(c) $p_{n}[f,x_{0},\ldots,x_{n}]=b_{0}+b_{1}(X-x_{n})+\cdots+b_{n}(X-x_{n})(X-x_{n-1})\cdots(X-x_{1})$ with $a_{n}=b_{n}$ for $1\leq n\leq m$. From this one can show that $b_{n}=f[x_{n},x_{n-1},\ldots,x_{1}]$ and $(x_{n}-x_{0})a_{n}+a_{n-1}-b_{n-1}=0$.)

11 For $f \in E^{\mathbb{N}}$, show that $f_n = \sum_{j=0}^{k} (-1)^j \binom{k}{j} \triangle^j f_{n+k-j}$, $n \in \mathbb{N}$. (Hint.$\overline{T} = (\overline{I} + \Delta) - \Delta$.) Page 26 of 29





# List of Problems from [1]

12 For $h \in \mathbb{K}^\times$ and $k, m \in \mathbb{N}$, show that $\triangle_h^k \in \text{Hom}\big(\mathbb{K}_m[X], \mathbb{K}_{m-k}[X]\big)$ where we set $\mathbb{K}_j[X] := 0$ if $j$ is negative.

What are the leading coefficients of $\triangle_{h}^{k}X^{m}$?

13 Verify the identity $\sum_{j=0}^{n} J^{4}=n(n+1)(2n+1)(3n^{2}+3n-1)/30$ for $n\in\mathbb{N}$.

14 Show that $\mathbb{Q}(\sqrt{2}) := \{a + b\sqrt{2} ; a, b \in \mathbb{Q}\}$ (see Exercise 10.2) is a vector space over $\mathbb{Q}$. What is its dimension?

15 $\mathbb{R}$ can be considered as a vector space over the field $\mathbb{Q}(\sqrt{2})$. Are 1 and $\sqrt{3}$ linearly independent over $\mathbb{Q}(\sqrt{2})$?

16 For $m \in \mathbb{N}$ and an $m+1$ element subset $\{x_0, \ldots, x_m\}$ of $\mathbb{K}$ consider the function

$$
e : \mathbb { K } _ { m } [ X ] \to \mathbb { K } ^{m + 1} ~ ,  p \mapsto \left( p ( x _ { 0 } ) , \ldots , p ( x _ { m } ) \right) .
$$

Show that $e$ is an isomorphism from $\mathbb{K}_m[X]$ to $\mathbb{K}^{m+1}$. What is $e^{-1}$?

17 Let $T: K \to E$ be linear. Prove that there is a unique $m \in E$ such that $T(x) = xm$ for all $x \in K$.





The submission problems now refer to the ones from the list above. To make the reference clear: for instance the notation I.8.6 refers to Exercise 6 in §I.8 which appears on page 16 of this document, the section appears on the left hand top corner (if the page number on the right hand corner is odd) of the copied page on the line just below the first line.

# Question 1:

Logic, sets, functions and relations

(1) Exercise §I.1.1, page 2 of this document.

[10]

(2) Exercise §I.3.3, page 5 of this document.

[10]

Total for Question 1: 20

# Question 2:

Natural numbers and integers

(1) Exercise §I.5.11, page 10 of this document. [10]

(2) Exercise §I.6.8, page 12 of this document. [10]

(3) Exercise §I.7.6, page 13 of this document. [10]

(4) Exercise §I.8.11, page 18 of this document. [10]

Total for Question 2: 40

# Question 3:

Rational numbers and real numbers

(1) Exercise §I.9.9, page 20 of this document.

[10]

(2) Exercise §I.10.16, page 23 of this document. [10]

Total for Question 3: 20

# 

Section 4:

Complex numbers, vector spaces, affine spaces and algebras

(1) Exercise §I.11.11, page 24 of this document.

(2) Exercise §I.12.17, page 28 of this document.

Total for Question 4: 20





# References

[1] H. Amann and J. Escher. Analysis. I. Translated from the 1998 German original by Gary Brookfield. Birkhäuser Verlag, Basel, 2005, pp.xiv+426. ISBN: 3-7643-7153-6. DOI: 10.1007/b137107. URL: https://doi.org/10.1007/b137107 (cit. on pp. 1–27).





MAT3711Real Analysis: IIAssignment 2Weightage 40%UAN: 187012

| Question: | 1 | 2 | 3 | 4 | Total |
| --- | --- | --- | --- | --- | --- |
| Marks: | 30 | 20 | 20 | 30 | 100 |
| Score: |  |  |  |  |  |

Name

Student Number

Signature with date

The submitted work is completely mine.

i. Each assignment produce copies of pages containing a variety of problems collected from several textbooks, each of which is suitably referred. You are expected to work through all the exercises.

ii. You shall have to submit the questions that are stated at the end of the assignment. In most cases you shall be asked to submit at least two and at most four problems (although, each problem could have several small parts).

iii. While it is encouraging to work in groups, make use of resources from anywhere on the internet, the final answer must be your own. Rememeber: in the final examination you shall be all alone and you shall not be asked to put forward any definition or prove anything standard available from the textbooks. On the other hand, the examination shall test your ability to deduce facts from a given set of assumptions.

iv. Download this heading page and make it the first page of your submission, after completing the details of your name, student number and signature.

v. You shall have to upload one .pdf file.

vi. Copy the problem that you are to submit and then provide your answer. The answer is to be uploaded to Course website





# List of Problems from [1]

Since $a$ is a cluster point of $(x_n)$, the sets

$$
\left\{ \, m \in \mathbb { N } \, ; \; m > n _ { k - 1 } , \; x _ { m } \in \mathbb { B } ( a , 1 / k ) \, \right\} \; ,  k \in \mathbb { N } ^{\times} \; ,
$$

are nonempty. By the well ordering principle, $n_k$ is well defined for each $k \in \mathbb{N}^\times$. Thus $\psi: \mathbb{N} \to \mathbb{N}$, $k \mapsto n_k$ is well defined and strictly increasing.

We next show that the subsequence $(x_{n_k})_{k\in\mathbb{N}}$ converges to $a$. Let $\varepsilon > 0$. By Corollary I.10.7 there is some $K := K(\varepsilon) \in \mathbb{N}^{\times}$ such that $1/k < \varepsilon$ for all $k \geq K$. By the construction of $n_k$ we have

$$
x _ { n _ { k } } \in \mathbb { B } ( a , 1 / k ) \subseteq \mathbb { B } ( a , \varepsilon ) ~ ,  k \ge K ~ .
$$

Thus $a = \lim_{k \to \infty} x_{n_k}$.

Conversely, let $(x_{n_k})_{k\in\mathbb{N}}$ be a subsequence of $(x_n)$ such that $a=\lim_{k\to\infty}x_{n_k}$. Then, by Proposition 1.11, $a$ is a cluster point of $(x_{n_k})_{k\in\mathbb{N}}$ and hence also of $(x_n)$. ■

# Exercises

1 Let $d$ be the discrete metric on $\mathbb{K}$ and $X := (\mathbb{K}, d)$.

(a) Give explicit descriptions of $\mathbb{E}_{X}(a,r)$ and $\mathbb{E}_{X}(a,r)$ for $a\in X$ and $r>0$. (b) Describe the cluster points of an arbitrary sequence in $X$. (c) For $a\in X$, describe all sequences $(x_{n})$ in $X$ such that $x_{n}\rightarrow a$.

2 Prove the claims of Example 1.2(e).

3 Prove that the sequence $(z_n)_{n\geq1}$ where $z_n:=(1-1/n)(1+i)$ converges to $1+i$ (as suggested by the graph following Remarks 1.1).

4 Prove the claims of Examples 1.9.

5 Determine all cluster points of the complex sequence $(z_n)$ in the following cases:

(a) $z_{n}:=((1+i)/\sqrt{2})^{n}$.

(b) $z_{n}:=(1+(-1)^{n})(n+1)n^{-1}+(-1)^{n}$.

(c) $z_{n}:=(-1)^{n}n/(n+1).$

6 For $n \in \mathbb{N}$, define

$$
a _ { n } : = n + \frac { 1 } { k } - \frac { k ^{2} + k - 2 } { 2 } \, ,
$$

where $k \in \mathbb{N}^{\times}$ satisfies

$$
k ^{2} + k - 2 \leq 2 n \leq k ^{2} + 3 k - 2 ~ .
$$

Show that $(a_n)$ is well defined and determine all cluster points of $(a_n)$. (Hint: Calculate the first few terms of the sequence explicitly to understand the complete sequence.)

7 For $m,n\in\mathbb{N}^\times$, define

$$
d ( m , n ) : = \left\{ \begin{array}{ll} { ( m + n ) / m n ~ , } & { ~ ~ ~ m \neq n ~ , } \\{ 0 ~ , } & { ~ ~ ~ m = n ~ . } \end{array} \right.
$$

Show that $(\mathbb{N}^\times,d)$ is a metric space and describe $\overline{\mathrm{P}}\overline{\mathrm{Ag}}(\overline{\mathbb{E}}(\frac{1}{n},\frac{1}{2}^{1/n})$ for $n\in\mathbb{N}^\times$.





# List of Problems from [1]

8 Let $X := \{z \in \mathbb{C} ; |z| \leq 3\}$ with the natural metric. Describe $\bar{\mathbb{B}}_X(0,3)$ and $\bar{\mathbb{B}}_X(2,4)$. Show that $\bar{\mathbb{B}}_X(2,4) \subset \bar{\mathbb{B}}_X(0,3)$.

9 Two metrics $d_{1}$ and $d_{2}$ on a set $X$ are called equivalent if, for each $x \in X$ and $\varepsilon > 0$, there are positive numbers $r_{1}$ and $r_{2}$ such that

$$
\mathbb { B } _ { 1 } ( x , r _ { 1 } ) \subseteq \mathbb { B } _ { 2 } ( x , \varepsilon ) ~ ,  \mathbb { B } _ { 2 } ( x , r _ { 2 } ) \subseteq \mathbb { B } _ { 1 } ( x , \varepsilon ) ~ .
$$

Here $\mathbb{B}_j$ denotes the ball in $(X,d_j)$, $j=1,2$. Now let $(X,d)$ be a metric space and

$$
\delta ( x , y ) : = \frac { d ( x , y ) } { 1 + d ( x , y ) } ~ ,  x , y \in X ~ .
$$

Prove that $d$ and $\delta$ are equivalent metrics on $X$. (Hint: The function $t \mapsto t/(1+t)$ is increasing.)

10 For $X:=(0,1)$, prove the following:

For $X := \langle 0, 1 \rangle$, prove the following.

(a) $d(x,y) := |(1/x) - (1/y)|$ is a metric on $X$.

(b) The natural metric and $d$ are equivalent.

(c) There is no metric on $\mathbb{R}$ which is equivalent to the natural metric and which induces the metric $d$ on $X$.

11 Let $(X_j,d_j)$, $j=1,\ldots,n$, be metric spaces, $X:=X_1\times\cdots\times X_n$ and $d$ the product metric on $X$. Show that

$$
\delta ( x , y ) : = \sum _ { j = 1 } ^{n} d _ { j } ( x _ { j } , y _ { j } ) ~ ,  x : = ( x _ { 1 } , \ldots , x _ { n } ) \in X ~ ,  y : = ( y _ { 1 } , \ldots , y _ { n } ) \in X ~ ,
$$

is a metric on $X$ which is equivalent to $d$.

12 For $z,w\in\mathbb{C}$, set

$$
\delta ( z , w ) : = \left\{ \begin{array}{ll} { | z - w | \, , } & { \mathrm { ~ i f ~ } z = \lambda w \mathrm { ~ f o r ~ s o m e ~ } \lambda > 0 \; , } \\{ | z | + | w | } & { \mathrm { ~ o t h e r w i s e ~ . ~ } } \end{array} \right.
$$

Show that $\delta$ defines a metric on $\mathbb{C}$, the SNCF-metric.$^{5}$

13 Let $(x_n)$ be a sequence in $\mathbb{C}$ with $\operatorname{Re} x_n = 0$ for all $n \in \mathbb{N}$. Show that, if $(x_n)$ converges to $x$, then $\operatorname{Re} x = 0$.





# List of Problems from [1]

Since $\lim(2+1/n)=2$, it follows from Proposition 2.4 that $\lim(2+1/n)^2=4$. Since $(3/n)$ is a null sequence, we have from Propositions 2.4 and 2.6 that

$$
\mathrm { R e } ( x _ { n } ) = \frac { 3 n } { ( 2 n + 1 ) ^{2} } \rightarrow 0 ~ ~ ( n \rightarrow \infty ) ~ .
$$

By Example 1.8(a) and Proposition 2.6, the sequence of the imaginary parts of $x_n$ satisfies

$$
\frac { 2 n ^{2} } { n ^{2} + 1 } = \frac { 2 } { 1 + 1 / n ^{2} } \rightarrow 2 ~ ( n \rightarrow \infty ) ~ .
$$

The claim now follows from Proposition 2.11. ■

(c) $\left(\frac{i^{n}}{1+in}\right)$ is a null sequence in $\mathbb{C}$.

Proof We write

$$
\frac { i ^{n} } { 1 + i \, n } = \frac { 1 } { n } \, \frac { i ^{n} } { i + 1 / n } \ ,  n \in \mathbb { N } ^{\times} \ .
$$

Then, by Proposition 2.4, it suffices to show that the sequence $(i^n/(i+1/n))_{n\in\mathbb{N}^\times}$ is bounded. Since

$$
\left| i + \frac { 1 } { n } \right| = \sqrt { 1 + \frac { 1 } { n ^{2} } } \geq 1 ~ ,  n \in \mathbb { N } ^{\times} ~ ,
$$

we get the inequality

$$
\left| \frac { i ^{n} } { i + 1 / n } \right| = \frac { | i ^{n} | } { | i + 1 / n | } = \frac { 1 } { | i + 1 / n | } \leq 1 ~ ,  n \in \mathbb { N } ^{\times} ~ ,
$$

which shows the claimed boundedness. ■

# Exercises

1 Determine whether the following sequences $(x_n)$ in $\mathbb{R}$ converge. Calculate the limit in the case of convergence.

(a) $x_{n}:=\sqrt{n+1}-\sqrt{n}$.

(b) $x_{n}:=(-1)^{n}\sqrt{n}(\sqrt{n+1}-\sqrt{n})$.

(c) $x_{n}:=\frac{1+2+3+\cdots+n}{n+2}-\frac{n}{2}$.

(d) $x_{n}:=\frac{(2-1/\sqrt{n})^{10}-(1+1/n^{2})^{10}}{1-1/n^{2}-1/\sqrt{n}}$.

(e) $x_{n}:=(100+1/n)^{2}$.

2 Using the binomial expansion of $(1+1)^n$, prove that $(n^3/2^n)$ is a null sequence.

3 Let $(x_n)$ be a convergent real sequence with positive limit. Show that almost all terms of the sequence are positive. Page 3 of 50





# List of Problems from [1]

4 Let $(x_j)$ be a convergent sequence in $\mathbb{K}$ with limit $a$. Prove that

$$
\operatorname* { l i m } _ { n \to \infty } { \frac { 1 } { n } } \sum _ { j = 1 } ^{n} x _ { j } = a \ .
$$

5 For $m \in \mathbb{N}^{\times}$, consider $\mathbb{K}^{m}$ to be a metric space with the product metric (see Example 1.2(e)). Let

$$
s ( \mathbb { K } ^{m} ) : = \mathrm { F u n c t } ( \mathbb { N } , \mathbb { K } ^{m} ) = ( \mathbb { K } ^{m} ) ^{\mathbb { N} }
$$

and

$$
c ( \mathbb { K } ^{m} ) : = \left\{ \, ( x _ { n } ) \in s ( \mathbb { K } ^{m} ) \; ; \; ( x _ { n } ) \mathrm { ~ c o n v e r g e s ~ } \right\} \ .
$$

Show the following:

(a) $c(\mathbb{K}^{m})$ is a subspace of $s(\mathbb{K}^{m})$. (b) The function

$$
\operatorname* { l i m } : \, c ( \mathbb { K } ^{m} ) \to \mathbb { K } ^{m} \ ,  ( x _ { n } ) \mapsto \operatorname* { l i m } _ { n \to \infty } ( x _ { n } )
$$

is linear.

(c) Let $(\lambda_n) \in c(\mathbb{K})$ and $(x_n) \in c(\mathbb{K}^m)$ be such that $\lambda_n \to \alpha$ and $x_n \to a$. Then $\lambda_n x_n \to \alpha a$ in $\mathbb{K}^m$ (Hint: Example 1.8(e)).

6 Let $(x_n)$ be a convergent sequence in $\mathbb{K}$ with limit $a$. Let $p,q\in\mathbb{K}[X]$ be such that $q(a)\neq0$. Prove that, for the rational function $r:=p/q$, we have

$$
r \left( x _ { n } \right) \rightarrow r ( a ) \; \; \left( n \rightarrow \infty \right) \, .
$$

In particular, for each polynomial $p$, the sequence $(p(x_n))_{n\in\mathbb{N}}$ converges to $p(a)$.

7 Let $(x_n)$ be a convergent sequence in $(0,\infty)$ with limit $x \in (0,\infty)$. For $r \in \mathbb{Q}$ prove that

$$
\left( x _ { n } \right) ^{r} \rightarrow x ^{r} ~ ~ ( n \rightarrow \infty ) ~ .
$$

(Hint: For $r=1/q$, let $y_{n}:=(x_{n})^{r}$ and $y:=x^{r}$. Then

$$
x _ { n } - x = ( y _ { n } - y ) \sum _ { k = 0 } ^{q - 1} y _ { n } ^{k} y ^{q - 1 - k}
$$

by Exercise I.8.1.)

8 Let $(x_n)$ be a sequence in $(0,\infty)$. Show that $(1/x_n)$ is a null sequence if and only if, for each $K>0$, there is some $N$ such that $x_n>K$ for all $n\geq N$.

9 Let $(a_n)$ be a sequence in $(0,\infty)$ and

$$
x _ { n } : = \sum _ { k = 0 } ^{n} ( a _ { k } + 1 / a _ { k } ) ~ ,  n \in \mathbb { N } ~ .
$$

Show that $(1/x_n)$ is a null sequence. (Hint: For $a > 0$, show that $a + 1/a \geq 2$ (see Exercise I.8.10). Now use Exercise 8.)





# List of Problems from [1]

Claim (ii) of Proposition 3.14 is often called componentwise convergence of the sequence $(x_n)$, so Proposition 3.14 can be formulated, somewhat imprecisely, as: A sequence in $\mathbb{K}^m$ converges if and only if it converges componentwise. Thus it suffices, in principle, to study the convergence of sequences in $\mathbb{K}$ — indeed, because of Remark 3.13(e), it suffices to study convergence in $\mathbb{R}$. For many reasons, which the reader will find for him/herself in further study, there is little to be gained by making such a 'simplification' in our presentation.

# Exercises

1 Let $\|\cdot\|$ be a norm on a $\mathbb{K}$-vector space $E$. Show that, for each $T \in \text{Aut}(E)$, the function $\|x\|_T := \|Tx\|$, $x \in E$, defines a norm $\|\cdot\|_T$ on $E$. In particular, for each $\alpha \in \mathbb{K}^\times$, the function $E \to \mathbb{R}^+$, $x \mapsto \|\alpha x\|$ is a norm on $E$.

2 Suppose that a sequence $(x_n)$ in a normed vector space $E = (E, \|\cdot\|)$ converges to $x$. Prove that the sequence $(\|x_n\|)$ in $[0,\infty)$ converges to $\|x\|$.

3 Verify the claims of Remark 3.4(a).

4 Prove that the parallelogram identity,

$$
2 ( \| x \| ^{2} + \| y \| ^{2} ) = \| x + y \| ^{2} + \| x - y \| ^{2} \, ,  x , y \in E \ ,
$$

holds in any inner product space $(E,(\cdot|\cdot))$.

5 For which $\lambda := (\lambda_1, \ldots, \lambda_m) \in \mathbb{K}^m$ is

$$
( \cdot | \cdot ) _ { \lambda } : \mathbb { K } ^{m} \times \mathbb { K } ^{m} \to \mathbb { K } \; ,  ( x , y ) \mapsto \sum _ { k = 1 } ^{m} \lambda _ { k } x _ { k } \overline { { y } } _ { k }
$$

a scalar product on $\mathbb{K}^{m}$?

6 Let $(E,(\cdot|\cdot))$ be a real inner product space. Prove the inequality

$$
( \| x \| + \| y \| ) \frac { ( x \, | y ) } { \| x \| \, \| y \| } \leq \| x + y \| \leq \| x \| + \| y \| \ ,  x , y \in E \backslash \{ 0 \} \ .
$$

When do we get equality? (Hint: Square the first inequality.)

7 Let $X$ be a metric space. A subset $Y$ of $X$ is called closed if every sequence $(y_n)$ in $Y$ which converges in $X$, converges in $Y$, that is, $\lim y_n \in Y$.

Show that $c_0$ is a closed subspace of $\ell_\infty$.

8 Let $\|\cdot\|_1$ and $\|\cdot\|_2$ be equivalent norms on a vector space $E$. Define

$$
d _ { j } ( x , y ) : = \| x - y \| _ { j } \, ,  x , y \in E \, ,  j = 1 , 2 \, .
$$





# List of Problems from [1]

9 Let $(X_j,d_j)$, $1 \leq j \leq n$, be metric spaces. Show that the function defined by

$$
( x , y ) \mapsto \left( \sum _ { j = 1 } ^{n} d _ { j } ( x _ { j } , y _ { j } ) ^{2} \right) ^{1 / 2}
$$

for all $x=(x_1,\ldots,x_n)$, $y=(y_1,\ldots,y_n)$ and $x,y\in X:=X_1\times\cdots\times X_n$ is a metric which is equivalent to the product metric on $X$.

10 Let $(E,(\cdot|\cdot))$ be an inner product space. Two elements $x,y\in E$ are called orthogonal if $(x|y)=0$. In this case we write $x\perp y$. A subset $M\subseteq E$ is called an orthogonal system if $x\perp y$ for all $x,y\in M$ with $x\neq y$. Finally $M$ is called an orthonormal system if $M$ is an orthogonal system such that $\|x\|=1$ for all $x\in M$.

Let $\{x_0,\ldots,x_m\}\subseteq E$ be an orthogonal system with $x_j\neq 0$ for $0\leq j\leq m$. Show the following:

(a) $\{x_0,\ldots,x_m\}$ is linearly independent.

(b) $\|\sum_{k=0}^{m}x_k\|^2=\sum_{k=0}^{m}\|x_k\|^2$ (Pythagoras' theorem).

11 Let $F$ be a subspace of an inner product space $E$. Prove that the orthogonal complement of $F$, that is,

$$
F ^{\perp} : = \left\{ x \in E \ ; \ x \perp y = 0 , \ y \in F \right\} \ ,
$$

is a closed subspace of $E$ (see Exercise 7).

12 Let $B=\{u_0,\ldots,u_m\}$ be an orthonormal system in an inner product space $(E,(\cdot|\cdot))$ and $F:=\text{span}(B)$. Define

$$
p _ { F } : E \rightarrow F ^{\prime} ~ , ~ ~ ~ x \mapsto \sum _ { k = 0 } ^{m} ( x \, | \, u _ { k } ) u _ { k } ~ .
$$

Prove the following:

(a) $x-p_F(x)\in F^\perp$, $x\in E$.

(b) $\|x-p_F(x)\|=\inf_{y\in F}\|x-y\|$, $x\in E$.

(c) $\|x-p_F(x)\|^2=\|x\|^2-\sum_{k=0}^m|(x|u_k)|^2$, $x\in E$.

(d) $p_F\in\mathrm{Hom}(E,F)$ with $p_F^2=p_F$.

(e) $\mathrm{im}(p_F)=F$, $\ker(p_F)=F^\perp$ and $E=F\oplus F^\perp$.

(Hint: (b) For $y\in F$, we have $\|x-y\|^2=\|x-p_F(x)\|^2+\|p_F(x)-y\|^2$ which follows from Exercise 10 and (a).)

13 With $B$ and $F$ as in Exercise 12, prove the following:

(a) For all $x \in E$, $\sum_{k=0}^{m} |(x|u_k)|^2 \leq \|x\|^2$.

(b) For all $x \in F$,

$$
x = \sum _ { k = 0 } ^{m} ( x | u _ { k } ) u _ { k }  \mathrm { ~ a n d ~ }  \| x \| ^{2} = \sum _ { k = 0 } ^{m} | ( x | u _ { k } ) | ^{2} .
$$

(Hint: To prove (a), use the Cauchy-Schwarz inequality)

Page 6 of 50





# List of Problems from [1]

14 For $m,n\in\mathbb{N}^\times$, let $\mathbb{K}^{m\times n}$ be the set of all $m\times n$ matrices with entries in $\mathbb{K}$. We can consider $\mathbb{K}^{m\times n}$ to be the set of all functions from $\{1,\dots,m\}\times\{1,\dots,n\}$ to $\mathbb{K}$, and so, by Example I.12.3(e), $\mathbb{K}^{m\times n}$ is a vector space. Here $\alpha A$ and $A+B$ for $\alpha\in\mathbb{K}$ and $A,B\in\mathbb{K}^{m\times n}$ are the usual scalar multiplication and matrix addition. Show the following:

(a) The function on $\mathbb{K}^{m\times n}$ defined by

$$
| A | : = \left( \sum _ { j = 1 } ^{m} \sum _ { k = 1 } ^{n} | a _ { j k } | ^{2} \right) ^{1 / 2} ,  A = [ a _ { j k } ] \in \mathbb { K } ^{m \times n} \ ,
$$

is a norm.

(b) The following functions define equivalent norms:

(α) $[a_{jk}] \mapsto \sum_{j=1}^{m} \sum_{k=1}^{n} |a_{jk}|$

(β) $[a_{jk}] \mapsto \max_{1 \leq j \leq m} \sum_{k=1}^{n} |a_{jk}|$

(γ) $[a_{jk}] \mapsto \max_{1 \leq k \leq n} \sum_{j=1}^{m} |a_{jk}|$

(δ) $[a_{jk}] \mapsto \max_{1 \leq j \leq m} |a_{jk}|$

15 Let $E$ and $F$ be normed vector spaces. Show that $B(E,F) \cap \text{Hom}(E,F) = \{0\}$.





# List of Problems from [1]

If we set

$$
x _ { m , n } ^{\prime} : = 1 + \sum _ { k = 1 } ^{m} \frac { 1 } { k ! } \left( 1 - \frac { 1 } { n } \right) \cdot \cdots \cdot \left( 1 - \frac { k - 1 } { n } \right) \, ,  n \geq m \, ,
$$

then $x'_{m,n} \uparrow x_m$ as $n \to \infty$ and $x'_{m,n} \leq e_n$ for all $n \geq m$. Because $e_n \uparrow e$, it follows from Proposition 2.7 that $x_m \leq e$. Since this holds for any $m \in \mathbb{N}^\times$, $e$ is an upper bound for $X := \{x_m : m \in \mathbb{N}\}$. Since $e' = \lim x_n = \sup X$, Theorem 4.1 implies that $e' \leq e$. ■

As we have already mentioned, the sequence $(x_n)$ converges much faster to $e$ than the sequence $(e_n)$. In fact, one can prove the following error estimate (see Exercise 7):

$$
0 < e - x _ { n } \leq \frac { 1 } { n n ! } \ ,  n \in \mathbb { N } ^{\times} \ .
$$

For $n=6$ we have $1/(6!6)=0.00023\ldots$ which is already a smaller error than in Example 4.2(f) for $n=1000$.

# Exercises

1 Let $a_{1},\ldots,a_{k}\in\mathbb{R}^{+}$. Prove that

$$
\operatorname* { l i m } _ { n \to \infty } \sqrt [ n ] { a _ { 1 } ^{n} + \cdots + a _ { k } ^{n} } = \operatorname* { m a x } \{ a _ { 1 } , \ldots , a _ { k } \} ~ .
$$

2 Prove that

$$
\left( 1 - 1 / n \right) ^{n} \rightarrow 1 / e ~ \left( n \rightarrow \infty \right) .
$$

(Hint: Consider $\lim\left(1-1/n^{2}\right)^{n}=1$ and Proposition 2.6.)

3 Show that, for all $r \in \mathbb{Q}$,

$$
\left( 1 + r / n \right) ^{n} \rightarrow e ^{r} ~ ~ ( n \to \infty ) ~ .
$$

(Hint: Consider the cases $r > 0$ and $r < 0$ separately. Use Exercises 2 and 2.7.)

4 For $a \in (0, \infty)$, define a real sequence $(x_n)$ recursively by $x_0 \geq a$ and

$$
x _ { n + 1 } : = ( x _ { n } + a / x _ { n } ) / 2 \ ,  n \in \mathbb { N } \ .
$$

Prove that $(x_{n})$ is decreasing and converges to $\sqrt{a}$.4

5 Let $a, x_0 \in (0, \infty)$ and

$$
x _ { n + 1 } : = a / ( 1 + x _ { n } ) \ ,  n \in \mathbb { N } \ .
$$

Show that the sequence $(x_n)$ converges and determine its limit.





# List of Problems from [1]

168

6 Prove the convergence of the sequence

$$
x _ { 0 } > 0 \; ,  x _ { 1 } > 0 \; ,  x _ { n + 2 } : = \sqrt { x _ { n + 1 } x _ { n } } \; ,  n \in \mathbb { N } \; .
$$

7 (a) For $n \in \mathbb{N}^\times$, prove the following error estimate:

$$
0 < e - \sum _ { k = 0 } ^{n} { \frac { 1 } { k ! } } < { \frac { 1 } { n n ! } } ~ .
$$

(b) Use the inequality in (a) to show that $e$ is irrational

(Hint: (a) For $n \in \mathbb{N}^\times$, let $y_m := \sum_{k=n+1}^{n+m} 1/k!$. Show that $y_m \to e - \sum_{k=0}^n 1/k!$ and $(m+n)! y_m < \sum_{k=1}^m (n+1)^{1-k}$. (b) Prove by contradiction.)

8 Let $(x_{n})$ be defined recursively by

$$
x _ { 0 } : = 1 \ ,  x _ { n + 1 } : = 1 + 1 / x _ { n } \ ,  n \in \mathbb { N } \ .
$$

Show that the sequence $(x_n)$ converges and determine its limit.

9 The Fibonacci numbers $f_{n}$ are defined recursively by

$$
f _ { 0 } : = 0 \; ,  f _ { 1 } : = 1 \; ,  f _ { n + 1 } : = f _ { n } + f _ { n - 1 } \; ,  n \in \mathbb { N } ^{\times} \; .
$$

Prove that $\lim(f_{n+1}/f_n)=g$, where $g$ is the limit of Exercise 8.

10 Let

$$
x _ { 0 } : = 5 \, ,  x _ { 1 } : = 1 \, ,  x _ { n + 1 } : = \frac { 2 } { 3 } x _ { n } + \frac { 1 } { 3 } x _ { n - 1 } \, ,  n \in \mathbb { N } ^{\times} \, .
$$

Verify that $(x_n)$ converges and determine $\lim x_{n}$.(Hint: Derive an expression for $x_n - x_{n+1}$.)





# List of Problems from [1]

# Exercises

1 Let $(x_n)$ be a sequence in $\mathbb{R}$, $x_* := \lim x_n$ and $x^* := \overline{\lim} x_n$. Suppose that $x_*$ and $x^*$ are in $\mathbb{R}$. Prove that, for each $\varepsilon > 0$, there is some $N$ such that

$$
x _ { * } - \varepsilon < x _ { n } < x ^{*} + \varepsilon ~ ,  n \geq N ~ .
$$

How must the claim be modified in the cases $x_{*}=-\infty$ and $x^{*}=\infty$?

2 Let $(x_n)$ and $(y_n)$ be sequences in $\mathbb{R}$ and

$$
x _ { * } : = \underline { { \operatorname* { l i m } } } x _ { n } ~ , ~ ~ ~ x ^{*} : = \overline { { \operatorname* { l i m } } } x _ { n } ~ , ~ ~ ~ y _ { * } : = \underline { { \operatorname* { l i m } } } y _ { n } ~ , ~ ~ ~ y ^{*} : = \overline { { \operatorname* { l i m } } } y _ { n } ~ .
$$

Show the following:

(a) $\overline{\lim}(-x_{n})=-x_{*}$.

(b) If $(x^{*},y^{*})$ and $(x_{*},y_{*})$ are not equal to $(\infty,-\infty)$ or $(-\infty,\infty)$, then

$$
\begin{array}{r} { \overline { { \operatorname* { l i m } } } ( x _ { n } + y _ { n } ) \leq x ^{*} + y ^{*} \mathrm { ~ a n d ~ } \underline { { \operatorname* { l i m } } } ( x _ { n } + y _ { n } ) \geq x _ { * } + y _ { * } \ . } \end{array}
$$

(c) If $x_n \geq 0$ and $y_n \geq 0$ for all $n \in \mathbb{N}$, and $(x_*, y_*) \notin \{(0, \infty), (\infty, 0)\}$, $(x_*, y^*) \neq (\infty, 0)$ and $(x^*, y^*) \neq (0, \infty)$, then

$$
0 \leq x _ { * } y _ { * } \leq \varinjlim ( x _ { n } y _ { n } ) \leq x _ { * } y ^{*} \leq \varinjlim ( x _ { n } y _ { n } ) \leq x ^{*} y ^{*} ~ .
$$

(d) If $(y_n)$ converges to $y \in \mathbb{R}$, then

$$
\overline { { \operatorname* { l i m } } } ( x _ { n } + y _ { n } ) = x ^{*} + y ~ , ~ ~ \underline { { \operatorname* { l i m } } } ( x _ { n } + y _ { n } ) = x _ { * } + y ~ ,
$$

and

$$
\begin{array}{rl} & { \overline { { \operatorname* { l i m } ( x _ { n } y _ { n } ) } } = y x ^{*} \ ,  y > 0 \ , } \\& { \operatorname* { l i m } ( x _ { n } y _ { n } ) = y x _ { * } \ ,  y < 0 \ . } \end{array}
$$

(e) If $x_n \leq y_n$ for all $n \in \mathbb{N}$, then $\lim x_n \leq \lim y_n$ and $\overline{\lim} x_n \leq \overline{\lim} y_n$.

3 For $n \in \mathbb{N}$, let $x_n := 2^n(1 + (-1)^n) + 1$. Determine the following:

$$
\begin{array}{r} { \underline { { \operatorname* { l i m } } } \, x _ { n } ,  \overline { { \operatorname* { l i m } } } \, x _ { n } , \; \underline { { \operatorname* { l i m } } } ( x _ { n + 1 } / x _ { n } ) , \; \overline { { \operatorname* { l i m } } } ( x _ { n + 1 } / x _ { n } ) , \; \underline { { \operatorname* { l i m } } } \, \sqrt [ n ] { x _ { n } } , \; \overline { { \operatorname* { l i m } } } \, \nabla                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     \
$$

4 Let $(x_n)$ be a sequence in $\mathbb{R}$ such that $x_n > 0$ for all $n \in \mathbb{N}$. Prove

$$
\begin{array}{r} { \operatorname* { l i m } \frac { x _ { n + 1 } } { x _ { n } } \leq \operatorname* { l i m } \sqrt [ ] { x _ { n } } \leq \overline { { \operatorname* { l i m } } } \; \sqrt [ ] { x _ { n } } \leq \overline { { \operatorname* { l i m } } } \; \frac { x _ { n + 1 } } { x _ { n } } \ . } \end{array}
$$

(Hint: If $q < \lim(x_{n+1}/x_n)$, then $x_{n+1}/x_n \geq q$ for all $n \geq n(q)$.)

5 (a) Show that the function

$$
\varphi : \mathbb { R } \to [ - 1 , 1 ] \, ,  \varphi ( x ) : = \left\{ \begin{array}{ll} { - 1 \, , } & { x = - \infty \, \mathrm { ~ , ~ } } \\{ x / ( 1 + | x | ) \, , } & { x \in \mathbb { R } \, \mathrm { ~ , ~ } } \\{ 1 \, , } & { x = \infty \, \mathrm { ~ , ~ } } \end{array} \right.
$$

is strictly increasing and bijective.

(b) Show that the function

$$
d \colon \overline { { \mathbb { R } } } \times \overline { { \mathbb { R } } } \to \mathbb { R } ^{+} ~ , ~ ~ ~ ( x , y ) \mapsto | \varphi ( x ) - \varphi ( y ) |
$$





# List of Problems from [1]

174

II Convergence

6 For the sequences

$(x_{n}) := (0,1,2,1,0,1,2,1,0,1,2,1,\ldots)$ and $(y_{n}) := (2,1,1,0,2,1,1,0,2,1,1,0,\ldots)$

determine the following:

$$
\begin{array}{rl} & { \overline { { \mathrm { l i m } } } \, x _ { n } + \overline { { \mathrm { l i m } } } \, y _ { n } ~ ,  \overline { { \mathrm { l i m } } } ( x _ { n } + y _ { n } ) ~ , } \\& { \underline { { \mathrm { l i m } } } \, x _ { n } + \underline { { \mathrm { l i m } } } \, y _ { n } ~ ,  \underline { { \mathrm { l i m } } } ( x _ { n } + y _ { n } ) ~ ,  \underline { { \mathrm { l i m } } } \, x _ { n } + \underline { { \mathrm { l i m } } } \, y _ { n } ~ . } \end{array}
$$





# List of Problems from [1]

# II.6 Completeness

6.13 Theorem $R$ is an order complete ordered extension field of $\mathbb{Q}$.

Proof Because of Lemma 6.9 and Proposition 6.10, we need to show only the order completeness of $R$.

Hence let $A$ be a nonempty subset of $R$ which is bounded above by $\gamma \in R$. We construct recursively an increasing sequence $(\alpha_j)$ and a decreasing sequence $(\beta_j)$ as follows: Choose some $\alpha_0 \in A$, then set $\beta_0 := \gamma$ and $\gamma_0 := (\alpha_0 + \beta_0)/2$. If there is some $a \in A$ such that $a \geq \gamma_0$, then set $\alpha_1 := \gamma_0$ and $\beta_1 := \beta_0$, otherwise set $\alpha_1 := \alpha_0$ and $\beta_1 := \gamma_0$. In the next step we repeat the above procedure, replacing $\alpha_0$ and $\beta_0$ by $\alpha_1$ and $\beta_1$ to get $\alpha_2$ and $\beta_2$. Iterating this process produces sequences $(\alpha_j)$ and $(\beta_j)$ with the claimed properties, as well as

$$
0 < \beta _ { j } - \alpha _ { j } \leq ( \beta _ { 0 } - \alpha _ { 0 } ) / 2 ^{j} ~ ,  j \in \mathbb { N } ~ .
$$

Since $(\alpha_j)$ is bounded above by $\gamma$ and $(\beta_j)$ is bounded below by $\alpha_0$, Lemma 6.12 implies that $\alpha := \sup\{\alpha_j \; ; \; j \in \mathbb{N}\}$ and $\beta := \inf\{\beta_j \; ; \; j \in \mathbb{N}\}$ exist. Moreover, taking the infimum of (6.6) yields

$$
0 \leq \beta - \alpha \leq \operatorname* { i n f } \bigl \{ ~ ( \beta _ { 0 } - \alpha _ { 0 } ) / 2 ^{j} ~ ; ~ j \in \mathbb { N } \bigr \} = 0 ~ .
$$

Hence $\alpha=\beta$.

Finally, by construction, we have $a \leq \beta_j$ for all $a \in A$ and $j \in \mathbb{N}$. Hence

$$
a \leq \operatorname* { i n f } \{ \beta _ { j } \; ; \; j \in \mathbb { N } \} = \beta = \alpha = \operatorname* { s u p } \{ \alpha _ { j } \; ; \; j \in \mathbb { N } \} \leq \gamma \, ,  a \in A \ .
$$

Since this holds for every upper bound $\gamma$ of $A$, it follows that $\alpha = \sup(A)$. ■

# Exercises

1 Let $(\alpha,\beta)\in\mathbb{R}^2$. For $k\in\mathbb{N}$, set

$$
x _ { k } : = \left\{ \begin{array}{ll} { ( \alpha , \beta ) \, , } & {  k \mathrm { ~ e v e n } \, , } \\{ ( \beta , \alpha ) \, , } & {  k \mathrm { ~ o d d } \, , } \end{array} \right.
$$

and $s_{n}:=\sum_{k=1}^{n} k^{-2} x_{k}$ for all $n \in \mathbb{N}^{\times}$. Show that $(s_{n})$ converges.

2 Let $X:=(X,d)$ be a complete metric space and $(x_n)$ a sequence in $X$. Suppose that

$$
d ( x _ { n + 1 } , x _ { n } ) \leq \alpha d ( x _ { n } , x _ { n - 1 } ) ~ ,  n \in \mathbb { N } ^{\times} ~ ,
$$

for some $\alpha \in (0,1)$. Prove that $(x_n)$ converges.

3 Show that every sequence in $\mathbb{R}$ has a monotone subsequence.

4 Prove the following (see Exercise 3.7):

(a) Every closed subset of a complete metric space is a complete metric space (with the induced metric).

(b) Every closed subspace of a Banach space is itself a Banach space (with the induced norm).

(c) $\ell_{\infty}$, $c$ and $c_0$ are Banach spaces.

(d) Let $M$ be a complete metric space and $D \subseteq M$ a subset which is complete (with respect to the induced metric). Then $D$ is close to Page 12 of 50





# List of Problems from [1]

II Convergence

5 Verify that the order $\leq$ on $R=\mathcal{R}/\mathbf{c}_0$ is transitive and compatible with the ring structure of $R$.

6 For all $n \in \mathbb{N}^{\times}$, set $x_{n} := \sum_{k=1}^{n} k^{-1}$. Prove the following: (a) The sequence $(x_{n})$ is not a Cauchy sequence in $\mathbb{R}$.

(b) For each $m \in \mathbb{N}^{\times}$, $\lim_{n}(x_{n+m}-x_{n}) = 0$.

(Hint: (a) Show that $(x_{n})$ is not bounded.)

7 Let $x_n := \sum_{k=1}^{n} k^{-2}$ for all $n \in \mathbb{N}^{\times}$. Prove or disprove that $(x_n)$ is a Cauchy sequence in $\mathbb{Q}$.





# List of Problems from [1]

# The Uncountability of $\mathbb{R}$

With the help of Theorem 7.11 it is now easy to prove that $\mathbb{R}$ is uncountable.

7.12 Theorem The set of real numbers $\mathbb{R}$ is uncountable.

Proof Suppose that $\mathbb{R}$ is countable. The subset $\{1/n \; ; \; n \geq 2\} \subseteq (0,1)$ is countably infinite, and so, by Example I.6.1(a) and Proposition I.6.7, the interval $(0,1)$ is also countably infinite. Hence $(0,1)=\{x_n \; ; \; n \in \mathbb{N}\}$ for some sequence $(x_n)_{n \in \mathbb{N}}$. By Theorem 7.11, each $x_n \in (0,1)$ has a unique ternary expansion of the form $x_n=0.x_{n,1}x_{n,2} \ldots$, where, for infinitely many $k \in \mathbb{N}^\times$, $x_{n,k} \in \{0,1,2\}$ is not equal to 2. In particular, by Proposition I.6.7, the set

$$
X : = \{ 0 , x _ { n , 1 } x _ { n , 2 } \ldots \; ; \; x _ { n , k } \neq 2 , \, \, n \in \mathbb { N } , \, \, k \in \mathbb { N } ^{\times} \}
$$

is countable. Since $X$ is clearly equinumerous with $\{0,1\}^{\mathbb{N}}$, we have shown that $\{0,1\}^{\mathbb{N}}$ is countable. This contradicts Proposition I.6.11. ■

# Exercises

1 Determine the values of the following series:

$$
\mathrm { ( a ) } \, \sum \frac { ( - 1 ) ^{k} } { 2 ^{k} } \ ,  \mathrm { ( b ) } \, \sum \frac { 1 } { 4 k ^{2} - 1 } \ .
$$

2 Determine whether the following series converge or diverge:

$$
\mathrm { ( a ) } \sum \frac { \sqrt { k + 1 } - \sqrt { k } } { \sqrt { k } } ~ , ~ ~ \mathrm { ( b ) } \sum ( - 1 ) ^{k} \big ( \sqrt { k + 1 } - \sqrt { k } \big ) ~ , ~ ~ \mathrm { ( c ) } \sum \frac { k ! } { k ^{k} } ~ , ~ ~ \mathrm { ( d ) } \sum \frac { ( k + 1 ) ^{k - 1} } { ( - k ) ^{k} } ~ .
$$

3 An infinitesimally small snail crawls with a constant speed of 5cm/hour along a 1 meter long rubber band. At the end of the first and all subsequent hours, the rubber band is stretched uniformly an extra meter. If the snail starts at the left end of the rubber band, will it reach the right end in a finite amount of time?

4 Let $\sum a_k$ be a convergent series in a Banach space $E$. Show that the sequence $(r_n)$ with $r_n := \sum_{k=n}^{\infty} a_k$ is a null sequence.

5 Let $(x_k)$ be a decreasing sequence such that $\sum x_k$ converges. Prove that $(kx_k)$ is a null sequence.

6 Let $(x_k)$ be a sequence in $[0,\infty)$. Prove that

$$
\sum x _ { k } < \infty \Leftrightarrow \sum \frac { x _ { k } } { 1 + x _ { k } } < \infty \, .
$$

Let $(d_k)$ be a sequence in $[0,\infty)$ such that $\sum_{k=0}^{\infty} d_k = \infty$.

(a) What can be said about the convergence of the following series?

$$
\mathrm { ( i ) } \, \sum \frac { d _ { k } } { 1 + d _ { k } } \, ,  \mathrm { ( i i ) } \, \sum \frac { d _ { k } } { 1 + k ^{2} d _ { k } } \, .
$$

Is the hypothesis on the sequence $(d_k)$ needed in both cases? Page 14 of 50





# List of Problems from [1]

# II.7 Series

(b) Show by example that the series

$$
\mathrm { ( i ) } \, \sum \frac { d _ { k } } { 1 + k d _ { k } } \; \; , \; \; \mathrm { ( i i ) } \, \sum \frac { d _ { k } } { 1 + d _ { k } ^{2} }
$$

can both converge and diverge.

(Hint: (a) Consider separately the cases $\overline{\lim}d_k < \infty$ and $\overline{\lim}d_k = \infty$.)

8 Let $s := \sum_{k=1}^{\infty} k^{-2}$. Show that

$$
1 - \frac { 1 } { 2 ^{2} } - \frac { 1 } { 4 ^{2} } + \frac { 1 } { 5 ^{2} } + \frac { 1 } { 7 ^{2} } - \frac { 1 } { 8 ^{2} } - \frac { 1 } { 10 ^{2} } + -- \cdots = \frac { 4 } { 9 } s ~ .
$$

9 For $(j,k) \in \mathbb{N} \times \mathbb{N}$, let

$$
x _ { j k } : = \left\{ \begin{array}{ll} { 1 / ( j ^{2} - k ^{2} ) \, , } & { j \neq k \, \mathrm { ~ , ~ } } \\{ 0 \, , } & { j = k \, \mathrm { ~ . ~ } } \end{array} \right.
$$

For each $j \in \mathbb{N}^{\times}$, determine the value of the series $\sum_{k=0}^{\infty} x_{jk}$. (Hint: Factor $x_{jk}$ suitably.)

10 The series $\sum c_k/k!$ is called a Cantor series if the coefficients $c_k$ are integers such that $0 \leq c_{k+1} \leq k$ for all $k \in \mathbb{N}^{\times}$.

Prove the following:

(a) Every nonnegative real number $x$ can be represented as the value of a Cantor series, that is, there is a Cantor series with $x=\sum_{k=1}^{\infty}c_k/k!$. This representation is unique if almost all of the $c_k$ are not equal to $k-1$.

(b) Show that

$$
\sum _ { k = n + 1 } ^{\infty} { \frac { k - 1 } { k ! } } = { \frac { 1 } { n ! } } \, ,  n \in \mathbb { N } \ .
$$

(c) Let $x \in [0,1)$ be represented by the Cantor series $\sum c_k/k!$. Then $x$ is rational$^5$ if and only if there is some $k_0 \in \mathbb{N}^\times$ such that $c_k = 0$ for all $k \geq k_0$.

11 Prove the Cauchy condensation theorem: If $(x_k)$ is a decreasing sequence in $[0,\infty)$, then $\sum x_k$ converges if and only if $\sum 2^k x_{2^k}$ converges.

12 Let $s \geq 0$ be rational. Show that the series $\sum_k k^{-s}$ converges if and only if $s > 1$. (Hint: Exercise 11 and Example 7.4.)

13 Prove the claim of (7.3).

14 Let

$$
x _ { n } : = \left\{ \begin{array}{ll} { n ^{- 1} \, , } & {  n \mathrm { ~ o d d ~ } \, , } \\{ - n ^{- 2} \, , } & {  n \mathrm { ~ e v e n ~ } \, . } \end{array} \right.
$$

Show that $\sum x_{n}$ diverges. Why does the Leibniz criterion not apply to this series?





# List of Problems from [1]

15 Let $(z_n)$ be a sequence in $(0,\infty)$ with $\lim z_n=0$. Show that there are null sequences $(x_n)$ and $(y_n)$ in $(0,\infty)$ such that

(a) $\sum x_{n} < \infty$ and $\lim x_{n}/z_{n} = \infty$.

(b) $\sum y_{n} = \infty$ and $\lim y_{n}/z_{n} = 0$.

In particular, for any slowly converging null sequence $(z_n)$ there is a null sequence $(x_n)$ which converges quickly enough so that $\sum x_n < \infty$, but even so, has a subsequence $(x_{n_k})$ which converges more slowly to zero than the corresponding subsequence $(z_{n_k})$ of $(z_n)$. And, for any quickly converging null sequence $(z_n)$ there is a null sequence $(y_n)$ which converges slowly enough so that $\sum y_n = \infty$, but, even so, has a subsequence $(y_{n_k})$ which converges more quickly to zero than the corresponding subsequence $(z_{n_k})$ of $(z_n)$.

(Hint: Let $(z_n)$ be a sequence in $(0,\infty)$ such that $\lim\limits_{k} z_n=0$.

(a) For each $k\in\mathbb{N}^\times$ choose some $n_k\in\mathbb{N}$ such that $z_{n_k}<k^{-3}$. Now set $x_{n_k}=k^{-2}$ for all $k\in\mathbb{N}$, and $x_n=n^{-2}$ otherwise.

(b) Choose a subsequence $(z_{n_k})$ with $\lim_k z_{n_k}=0$. Set $y_{n_k}=z_{n_k}^2$ for all $k\in\mathbb{N}$, and $y_n=1/n$ otherwise.)





# List of Problems from [1]

represented by the doubly infinite array$^{7}$

$$
\left[ \begin{array}{lllll} { 0 } & { - 1 } & { } & { } & { } \\{ 1 } & { 0 } & { - 1 } & { } & { } \\{ 1 } & { 0 } & { - 1 } & { } & { } \\{ 1 } & { 0 } & { - 1 } & { } & { } \\{ 1 } & { 0 } & { - 1 } & { } & { } \\{ 1 } & { 0 } & { - 1 } & { } & { } \\{ 0 } & { } & { } & { } & { } \end{array} \right] \left[ \begin{array}{lllll} { 0 } & { } & { } & { } & { } & { } \\{ } & { } & { } & { } & { } & { } \\{ } & { } & { } & { } & { } & { } \\{ } & { } & { } & { } & { } & { } \\{ } & { } & { } & { } & { } & { } \\{ } & { } & { } & { } & { } & { } \end{array} \right]
$$

This double series is not summable and the values of the row and column series disagree:

$$
\sum _ { j } \left( \sum _ { k = 0 } ^{\infty} x _ { j k } \right) = - 1 ~ , ~ ~ \sum _ { k } \left( \sum _ { j = 0 } ^{\infty} x _ { j k } \right) = 1 ~ .
$$

The series $\sum_{n} x_{\delta(n)}$, where $\delta: \mathbb{N} \rightarrow \mathbb{N} \times \mathbb{N}$ denotes the bijection of (I.6.3), is divergent.

# Exercises

1 Determine whether the following series converge or diverge:

$$
\begin{array}{rl} & { \mathrm { ( a ) ~ } \sum \frac { k ^{4} } { 3 ^{k} } \, ,  \mathrm { ( b ) ~ } \sum \frac { k } { ( \sqrt [ 3 ] { k } + 1 ) ^{k} } \, ,  \mathrm { ( c ) ~ } \sum \Bigl ( 1 - \frac { 1 } { k } \Bigr ) ^{k ^ { 2} } \, , } \\& { \mathrm { ( d ) ~ } \sum \bigl ( 2 k \bigr ) ^{- 1} \, ,  \mathrm { ( e ) ~ } \sum \bigl ( 2 k \bigr ) 2 ^{- k} \, ,  \mathrm { ( f ) ~ } \sum \bigl ( 2 k \bigr ) 5 ^{- k} \, . } \end{array}
$$

2 For what values of $a \in \mathbb{R}$ do the series

$$
\sum { \frac { a ^{2 k} } { ( 1 + a ^{2} ) ^{k - 1} } }  { \mathrm { a n d } }  \sum { \frac { 1 - a ^{2 k} } { 1 + a ^{2 k} } }
$$

converge?

3 Let $\sum x_k$ be a conditionally convergent series in $\mathbb{R}$. Show that the series$^8$ $\sum x_k^+$ and $\sum x_k^-$ diverge.

4 Prove Riemann's rearrangement theorem: If $\sum x_k$ is a conditionally convergent series in $\mathbb{R}$, then, for any $s \in \mathbb{R}$, there is a permutation $\sigma$ of $\mathbb{N}$ such that $\sum_k x_{\sigma(k)} = s$. Further, there is a permutation $\tau$ of $\mathbb{N}$ such that $\sum_k x_{\tau(k)}$ diverges. (Hint: Use Exercise 3 and approximate $s \in \mathbb{R}$ above and below by suitable combinations of the partial sums of the series $\sum x_k^+$ and $-\sum x_k^-.$)





# List of Problems from [1]

5 For all $(j,k) \in \mathbb{N} \times \mathbb{N}$, let

$$
x _ { j k } : = \left\{ \begin{array}{ll} { ( j ^{2} - k ^{2} ) ^{- 1} ~ , } & { ~ ~ j \neq k ~ , } \\{ 0 ~ , } & { ~ ~ j = k ~ . } \end{array} \right.
$$

Show that the double series $\sum x_{jk}$ is not summable. (Hint: Using Exercise 7.9, determine the values of the series of row sums and the series of column sums.)

6 Let

$$
\ell _ { 1 } : = \ell _ { 1 } ( \mathbb { K } ) : = \left( \{ \, ( x _ { k } ) \in s \; ; \; \sum x _ { k } \mathrm { ~ i s ~ a b s o l u t e l y ~ c o n v e r g e n t } \} , \; \| \cdot \| _ { 1 } \right)
$$

where

$$
\| ( x _ { k } ) \| _ { 1 } : = \sum _ { k = 0 } ^{\infty} | x _ { k } | ~ .
$$

Prove the following:

(a) $\ell_1$ is a Banach space.

(b) $\ell_1$ is a proper subspace of $\ell_\infty$ with $\|\cdot\|_\infty \leq \|\cdot\|_1$.

(c) The norm induced on $\ell_1$ from $\ell_\infty$ is not equivalent to the $\ell_1$-norm. (Hint: Consider the sequence $(\xi_j)$ with $\xi_j := (x_{j,k})_{k \in \mathbb{N}}$ where $x_{j,k} = 1$ for $k \leq j$, and $x_{j,k} = 0$ for $k > j$.)

7 Let $\sum x_{n}$, $\sum y_{n}$ and $\sum z_{n}$ be series in $(0,\infty)$ with $\sum y_{n} < \infty$ and $\sum z_{n} = \infty$. Prove the following:

(a) If there is some $N$ such that

$$
\frac { x _ { n + 1 } } { x _ { n } } \leq \frac { y _ { n + 1 } } { y _ { n } } ~ ,  n \geq N ~ ,
$$

then $\sum x_{n}$ converges.

(b) If there is some $N$ such that

$$
\frac { x _ { n + 1 } } { x _ { n } } \leq \frac { z _ { n + 1 } } { z _ { n } } ~ ,  n \geq N ~ ,
$$

then $\sum x_{n}$ diverges.

8 Determine whether the following series converge or diverge:

$$
\sum \frac { ( - 1 ) ^{n + 1} } { 3 n + ( - 1 ) ^{n} n } ~ , ~ ~ ~ \sum \frac { ( - 1 ) ^{n + 1} } { 3 n + 6 ( - 1 ) ^{n} } ~ .
$$

9 Let $a,b>0$ with $a-b=1$. Show that the Cauchy product of the series$^{9}$

$$
a + \sum _ { n \geq 1 } a ^{n}  \mathrm { ~ a n d ~ }  - b + \sum _ { n \geq 1 } b ^{n}
$$

converges absolutely. In particular, the Cauchy product of

$$
\begin{array}{r} { 2 + 2 + 2 ^{2} + 2 ^{3} + \cdots  \mathrm { a n d }  - 1 + 1 + 1 + \cdots } \end{array}
$$

converges absolutely.





# List of Problems from [1]

10 Prove the following properties of the exponential function:

(a) $\exp(x) > 0$, $x \in \mathbb{R}$.

(b) $\exp: \mathbb{R} \rightarrow \mathbb{R}$ is strictly increasing.

(c) For each $\varepsilon > 0$, there are $x < 0$ and $y > 0$ such that

$$
\exp ( x ) < \varepsilon  { \mathrm { ~ a n d ~ } }  \exp ( y ) > 1 / \varepsilon \ .
$$

(Hint: Consider Examples 8.12(a) and (b).)





# List of Problems from [1]

9.10 Remarks (a) If a power series $a=\sum a_kX^k$ has positive radius of convergence, then, by Corollary 9.9, the coefficients $a_k$ of $a$ are uniquely determined by $\underline{a}$ in the disk of convergence. In other words, if a function $f:\operatorname{dom}(f)\subseteq\mathbb{K}\to\mathbb{K}$ can be represented by a power series on a disk around the origin, then this power series is unique.

(b) The function $\underline{a}$ represented by $a=\sum a_{k}X^{k}$ on $\rho_{a}\mathbb{B}_{\mathbb{K}}$ is bounded on any closed ball $r\overline{\mathbb{B}}_{\mathbb{K}}$ with $r\in(0,\rho_{a})$. More precisely,

$$
\operatorname* { s u p } _ { | x | \leq r } | a ( x ) | \leq \sum _ { k = 0 } ^{\infty} | a _ { k } | \, r ^{k} \ .
$$

Proof This follows directly from (9.6) with $n=0$. ■

(c) In Section III.6 we will investigate nonzero power series which have infinitely many zeros. Thus the hypothesis of Theorem 9.8, that the sequence of zeros converges, cannot be omitted.

(d) Let $a=\sum a_{k}X^{k}$ be a real power series, that is, an element of $\mathbb{R}[X]$. Because $\mathbb{R}[X]\subseteq\mathbb{C}[X]$, $a$ can also be considered as a complex power series. If we denote by $a_{\mathbb{C}}$ the function represented by $a\in\mathbb{C}[X]$, then $a_{\mathbb{C}}\supseteq\underline{a}$, that is, $a_{\mathbb{C}}$ is an extension of $\underline{a}$. In view of Theorem 9.2, the radius of convergence $\rho_{a}$ is independent of whether $a$ is thought of as a real or complex power series. Hence

$$
( - \rho _ { a } , \rho _ { a } ) = \mathrm { d o m } ( a ) \cap \rho _ { a } \mathbb { B } _ { C } \subseteq \rho _ { a } \mathbb { B } _ { C } \subseteq \mathrm { d o m } ( a _ { C } ) ~ .
$$

Thus it suffices, in fact, to consider only complex power series. If a convergent series has real coefficients, then the corresponding function is real valued on real arguments. ■

# Exercises

1 Determine the radius of convergence of the power series $\sum a_{k}X^{k}$ when $a_{k}$ is given by each of the following:

$$
\mathrm { ( a ) } \, \frac { \sqrt { k } 2 ^{k} } { ( k + 1 ) ^{6} } \, ,  \mathrm { ( b ) } \, ( - 1 ) ^{k} \frac { k ! } { k ^{k} } \, ,  \mathrm { ( c ) } \, \frac { 1 } { \sqrt { 1 + k ^{2} } } \, ,  \mathrm { ( d ) } \, \frac { 1 } { \sqrt { k ! } } \, ,  \mathrm { ( e ) } \, \frac { 1 } { k ^{k} } \, ,  \mathrm { ( f ) } \, \left( 1 + \frac { 1 } { k ^{2} } \right) ^{k} \, .
$$

2 Show that the power series $a=\sum(1+k)X^{k}$ has radius of convergence 1 and that $\underline{a}(z)=(1-z)^{-2}$ for all $|z|<1$.

3 Suppose that the power series $\sum a_{k}X^{k}$ has radius of convergence $\rho>0$. Show that the series $\sum(k+1)a_{k+1}X^{k}$ has the same radius of convergence $\sigma$. Page 20 of 50.





# List of Problems from [1]

4 Suppose that $\sum a_k$ is a divergent series in $(0,\infty)$ such that $\sum a_kX^k$ has radius of convergence 1. Define

$$
f _ { n } : = \sum _ { k = 0 } ^{\infty} a _ { k } \left( 1 - \frac { 1 } { n } \right) ^{k} ,  n \in \mathbb { N } ^{\times} ~ .
$$

Prove that the sequence $(f_n)$ converges to $\infty$. (Hint: Use the Bernoulli inequality to get an upper bound for terms of the form $1 - (1 - 1/n)^m$.)

5 Suppose that a sequence $(a_k)$ in $\mathbb{K}$ satisfies

$$
0 < \underline { { \operatorname* { l i m } | a _ { k } | } } \leq \overline { { \operatorname* { l i m } | a _ { k } | } } < \infty ~ .
$$

Determine the radius of convergence of $\sum a_{k}X^{k}$.

6 Show that the radius of convergence $\rho$ of a power series $\sum a_kX^k$ such that $a_k \neq 0$ for all $k \in \mathbb{N}$ satisfies

$$
\begin{array}{r} { \operatorname* { l i m } | \frac { a _ { k } } { a _ { k + 1 } } | \leq \rho \leq \overline { { \operatorname* { l i m } } } | \frac { a _ { k } } { a _ { k + 1 } } | ~ . } \end{array}
$$

7 A subset $D$ of a vector space is called symmetric with respect to 0 if $x \in D$ implies $-x \in D$ for all $x$. If $D$ is symmetric and $f : D \to E$ is a function to a vector space $E$, then $f$ is called even (or odd) if $f(x) = f(-x)$ (or $f(x) = -f(-x)$) for all $x \in D$. Now let $f : \mathbb{K} \to \mathbb{K}$ be a function which can be represented by power series on a suitable disk centered at 0. What conditions on the coefficients of this power series determine whether $f$ is even or odd?

8 Let $a$ and $b$ be power series with radii of convergence $\rho_a$ and $\rho_b$ respectively. Show, by example, that $\rho_{a+b} > \max(\rho_a, \rho_b)$ and $\rho_{ab} > \max(\rho_a, \rho_b)$ are possible.

9 Let $a=\sum a_{k}X^{k}\in\mathbb{C}[X]$ with $a_{0}=1$.

(a) Show that there is some $b=\sum b_kX^k\in\mathbb{C}[X]$ such that $ab=1\in\mathbb{C}[X]$. Provide a recursive algorithm for calculating the coefficients $b_k$.

(b) Show that the radius of convergence $\rho_b$ of $b$ is positive if the radius of convergence of $a$ is positive.

10 Suppose that $b=\sum b_kX^k\in\mathbb{C}[X]$ satisfies $(1-X-X^2)b=1\in\mathbb{C}[X]$.

(a) Show that the coefficients $b_{k}$ satisfy

$$
b _ { 0 } = 1 \ ,  b _ { 1 } = 1 \ ,  b _ { k + 1 } = b _ { k } + b _ { k - 1 } \ ,  k \in \mathbb { N } ^{\times} \ ,
$$

that is, $(b_k)$ is the Fibonacci sequence (see Exercise 4.9).

(b) What is the radius of convergence of $b$?





# List of Problems from [1]

Proof The implication '$\Rightarrow$' is clear.

'⇐' Let $\varepsilon > 0$. By the left and right continuity of $f$ at $x_0$, there are positive numbers $\delta^-$ and $\delta^+$ such that $d\big(f(x), f(x_0)\big) < \varepsilon$ for all $x \in X \cap (x_0 - \delta^-, x_0]$ and $x \in X \cap [x_0, x_0 + \delta^+)$. Set $\delta := \min\{\delta^-, \delta^+\}$. Then $d\big(f(x), f(x_0)\big) < \varepsilon$ for all $x \in X \cap (x_0 - \delta, x_0 + \delta)$. Therefore $f$ is continuous at $x_0$. ■

# Exercises

1 The function $zigzag : \mathbb{R} \rightarrow \mathbb{R}$ is defined by

$$
\mathrm { z i g z a g } ( x ) : = | \left| x + 1 / 2 \right| - x | \ ,  x \in \mathbb { R } \ ,
$$

where $[\cdot]$ is the floor function. Sketch the graph of zigzag and show the following:

(a) zigzag$(x)=|x|$ for all $|x|\leq 1/2$.

(b) zigzag$(x+n)=\text{zigzag}(x)$, $x\in\mathbb{R}$, $n\in\mathbb{Z}$.

(c) zigzag is continuous.

2 Let $q \in \mathbb{Q}$. Prove that the function $(0, \infty) \rightarrow (0, \infty)$, $x \mapsto x^q$ is continuous.$^6$ (Hint: See Exercise II.2.7.)

3 Let $\varphi\colon\mathbb{R}\to(-1,1)$, $x\mapsto x/(1+|x|)$. Show that $\varphi$ is bijective and that $\varphi$ and $\varphi^{-1}$ are continuous.

4 Prove or disprove that the function

$$
f : \mathbb { Q } \to \mathbb { R } \; ,  x \mapsto \left\{ \begin{array}{ll} { 0 \; , } & { \; \; \; x < \sqrt { 2 } \; , } \\{ 1 \; , } & { \; \; \; x > \sqrt { 2 } \; , } \end{array} \right.
$$

is continuous.

5 Let $d_1$ and $d_2$ be metrics on $X$, and $X_j := (X, d_j)$, $j = 1, 2$. Then $d_1$ is stronger than $d_2$ if $\mathcal{U}_{X_1}(x) \supseteq \mathcal{U}_{X_2}(x)$ for each $x \in X$, that is, if each point has more $d_1$ neighborhoods than $d_2$ neighborhoods. In this case, one says also that $d_2$ is weaker than $d_1$.

Show the following:

(a) $d_1$ is stronger than $d_2$ if and only if the identity function $i: X_1 \to X_2$, $x \mapsto x$ is continuous.

(b) $d_1$ and $d_2$ are equivalent if and only if $d_1$ is both stronger and weaker than $d_2$, that is, for each $x \in X$, $\mathcal{U}_{X_1}(x) = \mathcal{U}_{X_2}(x)$.

6 Let $f:\mathbb{R}\to\mathbb{R}$ be a continuous$^7$ homomorphism of the additive group $(\mathbb{R},+)$. Show that $f$ is linear, that is, there is some $a\in\mathbb{R}$ such that $f(x)=ax$, $x\in\mathbb{R}$. (Hint: Show that $f(q)=qf(1)$ for all $q\in\mathbb{Q}$ and use Proposition I.10.8.)





# List of Problems from [1]

7 Let $f : \mathbb{R} \rightarrow \mathbb{R}$ be defined by

$$
f ( x ) : = \left\{ \begin{array}{ll} { - 1 ~ , } & { x \geq 1 ~ , } \\{ 1 / n ~ , } & { 1 / ( n + 1 ) \leq x < 1 / n ~ , } \\{ 0 ~ , } & { x \leq 0 ~ . } \end{array} \right.
$$

Where is $f$ continuous? left continuous? right continuous?

8 Suppose that $X$ is a metric space and $f,g\in\mathbb{R}^{X}$ are continuous at $x_{0}$. Prove or disprove that$^{8}$

$$
| f | \, ,  f ^{+} : = 0 \lor f \, ,  f ^{-} : = 0 \lor ( - f ) \, ,  f \lor g \, ,  f \land g
$$

are continuous at $x_0$. (Hint: Example 1.3(j) and Exercise I.8.11.)

9 Let $f : \mathbb{R} \rightarrow \mathbb{R}$ and $g : \mathbb{R} \rightarrow \mathbb{R}$ be defined by

$$
f ( x ) : = \left\{ \begin{array}{ll} { 1 \, , } & { x \mathrm { ~ r a t i o n a l ~ } , } \\{ - 1 \, , } & { x \mathrm { ~ i r r a t i o n a l ~ } , } \end{array} \right.  g ( x ) : = \left\{ \begin{array}{ll} { x \, , } & { x \mathrm { ~ r a t i o n a l ~ } , } \\{ - x \, , } & { x \mathrm { ~ i r r a t i o n a l ~ } . } \end{array} \right.
$$

Where are the functions $f$, $g$, $|f|$, $|g|$ and $f \cdot g$ continuous?

10 Let $f : \mathbb{R} \rightarrow \mathbb{R}$ be defined by

$$
f ( x ) : = \left\{ \begin{array}{ll} { 1 / n ~ , } & { ~ ~ ~ x \in \mathbb { Q } \mathrm { ~ a n d ~ } x = m / n \mathrm { ~ i n ~ l o w e s t ~ t e r m s } } \\{ 0 ~ , } & { ~ ~ ~ ~ x \in \mathbb { R } \backslash \mathbb { Q } \ . } \end{array} \right.
$$

Show that $f$ is continuous at each irrational number and discontinuous at each rational number.$^{9}$ (Hint: For each $x \in \mathbb{Q}$ there is, by Proposition I.10.11, a sequence $x_{n} \in \mathbb{R} \backslash \mathbb{Q}$ such that $x_{n} \rightarrow x$. So $f$ cannot be continuous at $x$.

Let $x \in \mathbb{R} \backslash \mathbb{Q}$ and $\varepsilon > 0$. Then there are only finitely many $n \in \mathbb{N}$ such that $n \leq 1/\varepsilon$. Thus there is some $\delta > 0$ such that no $q = m/n$ with $n \leq 1/\varepsilon$ is in $(x - \delta, x + \delta)$. That is, for $y = m/n \in (x - \delta, x + \delta)$, we have $f(y) = f(m/n) = 1/n < \varepsilon.$

11 Consider the function

$$
f : \mathbb { R } ^{2} \to \mathbb { R } \ ,  ( x , y ) \mapsto \left\{ \begin{array}{ll} { x y / ( x ^{2} + y ^{2} ) \ , } & { ( x , y ) \neq ( 0 , 0 ) \ , } \\{ 0 \ , } & { ( x , y ) = ( 0 , 0 ) \ , } \end{array} \right.
$$

and, for a fixed $x_0 \in \mathbb{R}$, define

$$
f _ { 1 } : \mathbb { R } \to \mathbb { R } \ ,  x \mapsto f ( x , x _ { 0 } ) \ ,  f _ { 2 } : \mathbb { R } \to \mathbb { R } \ ,  x \mapsto f ( x _ { 0 } , x ) \ .
$$

Prove the following:

(a) $f_{1}$ and $f_{2}$ are continuous.

(b) $f$ is continuous on $\mathbb{R}^{2} \setminus \{(0,0)\}$ and discontinuous at $(0,0)$. (Hint: For a null sequence $(x_{n})$ consider $f(x_{n},x_{n})$.)

12 Show that any linear function from $\mathbb{K}^n$ to $\mathbb{K}^m$ is Lipschitz continuous. (Hint: Use Proposition II.3.12 with suitable norms.)





# List of Problems from [1]

# III.1 Continuity

13 Suppose that $V$ and $W$ are normed vector spaces and $f: V \to W$ is a continuous group homomorphism from $(V, +)$ to $(W, +)$. Prove that $f$ is linear. (Hint: If $\mathbb{K} = \mathbb{R}$, $x \in V$ and $q \in \mathbb{Q}$, then $f(qx) = qf(x)$. See also Exercise 6.)

14 Let $(E,(\cdot|\cdot))$ be an inner product space and $x_0\in E$. Show that the functions

$$
E \rightarrow \mathbb { K } ,  x \mapsto ( x \, | \, x _ { 0 } ) \, ,  E \rightarrow \mathbb { K } ,  x \mapsto ( x _ { 0 } \, | \, x )
$$

are continuous.

15 Let $A \in \text{End}(\mathbb{K}^n)$. Prove that the function

$$
\mathbb { K } ^{n} \to \mathbb { K } \, ,  x \mapsto ( A x | x )
$$

is continuous. (Hint: Use Exercise 12 and the Cauchy-Schwarz inequality.)

16 Let $n \in \mathbb{N}^\times$. The determinant of a matrix $A = [a_{jk}] \in \mathbb{K}^{n \times n}$ is defined by (see Exercice I.9.6)

$$
\operatorname* { d e t } A = \sum _ { \sigma \in S _ { n } } ( \mathrm { s i g n } \, \sigma ) a _ { 1 \sigma ( 1 ) } \cdot \cdots \cdot a _ { n \sigma ( n ) } \ .
$$

Show that the function

$$
\mathbb { K } ^{n \times n} \to \mathbb { K } ~ , ~ ~ A \mapsto \operatorname* { d e t } A
$$

is continuous (see Exercise II.3.14). (Hint: Use the bijection

$$
\mathbb { K } ^{m \times n} \to \mathbb { K } ^{m n} ~ ,  \left[ \begin{array}{lll} { a _ { 11 } , } & { \ldots , } & { a _ { 1 n } } \\{ \vdots } & { } & { \vdots } \\{ a _ { m 1 } , } & { \ldots , } & { a _ { m n } } \end{array} \right] \mapsto ( a _ { 11 } , \ldots , a _ { 1 n } , a _ { 21 } , \ldots , a _ { m n } )
$$

to define the natural topology on $\mathbb{K}^{m\times n}$.)

17 Let $X$ and $Y$ be metric spaces and $f : X \to Y$. For $x \in X$, the function

$$
\omega _ { f } ( x , \cdot ) : ( 0 , \infty ) \to \mathbb { R } \; ,  \varepsilon \mapsto \operatorname* { s u p } _ { y , z \in \mathbb { B } ( x , \varepsilon ) } d \bigl ( f ( y ) , f ( z ) \bigr )
$$

is called the modulus of continuity of $f$. Set

$$
\omega _ { f } ( x ) : = \operatorname* { i n f } _ { \varepsilon > 0 } \omega _ { f } ( x , \varepsilon ) ~ .
$$

Show that $f$ is continuous at $x$ if and only if $\omega_{f}(x)=0$.

18 Show that the square root function $w: \mathbb{R}^{+} \rightarrow \mathbb{R}$, $x \mapsto \sqrt{x}$ is continuous but not Lipschitz continuous. Show that $w|(a,\infty)$ is Lipschitz continuous for each $a>0$.





# List of Problems from [1]

# Exercises

1 For the following subsets $M$ of a metric space $X$, determine $\overline{M}$, $\dot{M}$, $\partial M$ and the set $M'$ of all limit points of $M$:

(a) $M = (0, 1]$, $X = \mathbb{R}$.

(b) $M = (0, 1] \times \{0\}$, $X = \mathbb{R}^2$.

(c) $M = \{1/n; n \in \mathbb{N}^\times\}$, $X = \mathbb{R}$.

(d) $M = \mathbb{Q}$, $X = \mathbb{R}$.

(e) $M = \mathbb{R} \setminus \mathbb{Q}$, $X = \mathbb{R}$.

2 Let $\mathbb{Q}$ have the natural metric and $S := \{x \in \mathbb{Q} ; -\sqrt{2} < x < \sqrt{2}\}$. Prove or disprove the following:

(a) $S$ is open in $\mathbb{Q}$.(b) $S$ is closed in $\mathbb{Q}$.

3 Let $X$ be a nonempty set and $d$ the discrete metric on $X$. Show the following:

(a) Every subset of $X$ is open, that is, $\mathcal{P}(X)$ is the topology of $(X,d)$.

(b) It is not true, in general, that $\bar{\mathbb{B}}(x,r)=\overline{\mathbb{B}}(x,r)$.

4 For $S := \{(x,y) \in \mathbb{R}^2; x^2 + y^2 < 1\} \setminus ([0,1) \times \{0\})$, determine $(\bar{S})^0$. Is $(\bar{S})^0 = S'$

5 Let $X$ be a metric space and $A \subseteq X$. Prove that $\dot{A} = X \setminus (\overline{X \setminus A})$.

6 Let $X_j$, $j=1,\ldots,n$, be metric spaces and $X:=X_1\times\cdots\times X_n$. Show the following:

(a) If $O_j$ is open in $X_j$ for all $j$, then $O_1 \times \cdots \times O_n$ is open in $X$.

(b) If $A_j$ is closed in $X_j$ for all $j$, then $A_1 \times \cdots \times A_n$ is closed in $X$.

7 Let $h : \mathcal{P}(X) \to \mathcal{P}(X)$ be a function with the properties

(i) $h(\emptyset)=\emptyset$,

(ii) $h(A)\supseteq A$, $A\in\mathcal{P}(X)$,

(iii) $h(A\cup B)=h(A)\cup h(B)$, $A,B\in\mathcal{P}(X)$,

(iv) $h\circ h=h$.

(a) Set $\mathcal{T}_h:=\left\{A^c\in\mathcal{P}(X)\;;\;h(A)=A\right\}$ and show that $(X,\mathcal{T}_h)$ is a topological space.

(b) Given a topological space $(X,\mathcal{T})$, find a function $h:\mathcal{P}(X)\to\mathcal{P}(X)$ satisfying (i)-(iv) and $\mathcal{T}_h=\mathcal{T}$.

8 Let $X$ be a metric space and $A, B \subseteq X$. Prove or disprove that $(A \cup B)^\circ = \hat{A} \cup \hat{B}$ and $(A \cap B)^\circ = \hat{A} \cap \hat{B}$.

9 Consider the metric on $\mathbb{R}$ given by $\delta(x,y):=|x-y|/(1+|x-y|)$ (see Exercise II.1.9). Show that the sets $A_n:=[n,\infty)$, $n\in\mathbb{N}$, are closed and bounded in $(\mathbb{R},\delta)$, and that $^5$ $\bigcap_{n=0}^k A_n\neq\emptyset$ for each $k\in\mathbb{N}$ and $\bigcap A_n=\emptyset$.

10 Let $X := \{1, 2, 3, 4, 5\}$ and

$$
\mathcal { T } : = \left\{ \emptyset , X , \{ 1 \} , \{ 3 , 4 \} , \{ 1 , 3 , 4 \} , \{ 2 , 3 , 4 , 5 \} \right\} ~ .
$$

Show that $(X,\mathcal{T})$ is a topological space and determine the closure of $\{2,4,5\}$.





# List of Problems from [1]

11 Let $\mathcal{T}_1$ and $\mathcal{T}_2$ be topologies on a set $X$. Prove or disprove that $\mathcal{T}_1 \cup \mathcal{T}_2$ and $\mathcal{T}_1 \cap \mathcal{T}_2$ are topologies on $X$.

12 Let $X$ and $Y$ be metric spaces. Prove that

$$
f : X \to Y { \mathrm { ~ i s ~ c o n t i n u o u s } } \Leftrightarrow f ( \overline { { A } } ) \subseteq \overline { { f ( A ) } } , \; A \subseteq X \ .
$$

13 Let $A$ and $B$ be closed subsets of a metric space $X$. Suppose that $Y$ is a metric space and $g : A \to Y$ and $h : B \to Y$ are continuous functions such that

$$
g | A \cap B = h | A \cap B  { \mathrm { i f } }  A \cap B \neq \emptyset \ .
$$

Show that the function

$$
f \colon A \cup B \to Y \, ,  x \mapsto { \left\{ \begin{array}{ll} { g ( x ) \, , } & { x \in A \, , } \\{ h ( x ) \, , } & { x \in B \, , } \end{array} \right. }
$$

is continuous.

14 A function $f: X \to Y$ between metric spaces $(X, d)$ and $(Y, \delta)$ is called open if $f(\mathcal{T}_d) \subseteq \mathcal{T}_\delta$, that is, if the images of open sets are open. The function $f$ is called closed if $f(A)$ is closed for any closed set $A$. Let $d$ denote the natural metric and $\delta$ the discrete metric on $\mathbb{R}$. Prove the following:

(a) id: $(\mathbb{R},d)\to(\mathbb{R},\delta)$ is open and closed, but not continuous.

(b) id: $(\mathbb{R},\delta)\to(\mathbb{R},d)$ is continuous, but neither open nor closed

15 Let $f : \mathbb{R} \to \mathbb{R}$, $x \mapsto \exp(x) \text{zigzag}(x)$ (see Exercise 1.1). Then $f$ is continuous, but neither open nor closed. (Hint: Consider Exercise II.8.10 and determine $f((-\infty,0))$ and $f\left(\{-2n+1\}/2; n \in \mathbb{N}\right)\rangle$.)

16 Prove that the function

$$
f : [ 0 , 2 ] \to [ 0 , 2 ] \, ,  x \mapsto { \left\{ \begin{array}{ll} { 0 \, , } & {  x \in [ 0 , 1 ] \, , } \\{ x - 1 \, , } & {  x \in ( 1 , 2 ] \, , } \end{array} \right. }
$$

is continuous and closed, but not open.

17 Let $S^{1}:=\{(x,y)\in\mathbb{R}^{2};\ x^{2}+y^{2}=1\}$, the unit circle in $\mathbb{R}^{2}$, with the natural metric. Show that the function

$$
f : S ^{1} \to [ 0 , 2 ) ~ ,  ( x , y ) \mapsto \left\{ \begin{array}{ll} { 0 ~ , } & { y \geq 0 ~ , } \\{ 1 + x ~ , } & { y \leq 0 ~ , } \end{array} \right.
$$

is closed, but neither continuous nor open.

18 Let $X$ and $Y$ be metric spaces and

$$
p \colon X \times Y \to X \; ,  ( x , y ) \mapsto x
$$

the canonical projection onto $X$. Then $p$ is continuous and open, but not, in general, closed.





# List of Problems from [1]

20 Let $X$ and $Y$ be metric spaces and $f: X \to Y$. Show that (see Exercise 1.17)

$$
A _ { n } : = \left\{ \, x \in X \; ; \; \omega _ { f } ( x ) \geq 1 / n \, \right\}
$$

is closed for each $n \in \mathbb{N}^\times$.

21 Let $X$ be a metric space and $A \subseteq X$. Show the following:

(i) If $A$ is complete, then $A$ is closed in $X$. The converse is, in general, false.

(ii) If $X$ is complete, then $A$ is complete if and only if $A$ is closed in $X$.





# List of Problems from [1]

# Exercises

1 Let $X_j$, $j=1,\ldots,n$, be metric spaces. Prove that $X_1 \times \cdots \times X_n$ is compact if and only if each $X_j$ is compact.

2 Let $X$ be a compact metric space and $Y$ a subset of $X$. Prove that $Y$ is compact if and only if $Y$ is closed.

3 Let $X$ and $Y$ be metric spaces. A bijection $f: X \to Y$ is called a homeomorphism if both $f$ and $f^{-1}$ are continuous. Show the following:

(a) If $f : X \to Y$ is a homeomorphism, then $\mathcal{U}(f(x)) = f(\mathcal{U}(x))$ for all $x \in X$, that is, 'f maps neighborhoods to neighborhoods'.

(b) Suppose that $X$ is compact and $f : X \to Y$ is continuous.

(i) $f$ is closed (see Exercise 2.14).

(ii) If $f$ is bijective, it is a homeomorphism.

4 A family $\mathcal{M}$ of subsets of a nonempty set has the finite intersection property if each finite subset of $\mathcal{M}$ has nonempty intersection. Prove that the following are equivalent:

(a) $X$ is a compact metric space.

(b) Every family $\mathcal{A}$ of closed subsets of $X$ which has the finite intersection property, has nonempty intersection, that is, $\bigcap A \neq \emptyset$.

5 Let $(A_j)$ be a sequence of nonempty closed subsets of $X$ with $A_j \supseteq A_{j+1}$ for all $j \in \mathbb{N}$. Show that, if $A_0$ is compact, then $\bigcap A_j \neq \emptyset$.$^4$

6 Let $E$ and $F$ be finite dimensional normed vector spaces and $A: E \rightarrow F$ linear. Prove that $A$ is Lipschitz continuous. (Hint: Example 3.9(a).)

7 Show that the set $O(n)$ of all real orthogonal matrices is a compact subset of $\mathbb{R}^{(n^z)}$.

8 Let

$$
C _ { 0 } : = [ 0 , 1 ] \, ,  C _ { 1 } : = C _ { 0 } \backslash ( 1 / 3 , 2 / 3 ) \, ,  C _ { 2 } : = C _ { 1 } \backslash \left( ( 1 / 9 , 2 / 9 ) \cup ( 7 / 9 , 8 / 9 ) \right) \, ,  \ldots
$$

In general, $C_{n+1}$ is formed by removing the open middle third from each of the $2^n$ intervals which make up $C_n$. The intersection $C := \bigcap C_n$ is called the Cantor set. Prove the following:

(a) $C$ is compact and has empty interior.

(b) $C$ consists of all numbers in $[0,1]$ whose ternary expansion is $\sum_{k=1}^{\infty}a_{k}3^{-k}$ with $a_{k}\in\{0,2\}$.

(c) Every point of $C$ is a limit point of $C$, that is, $C$ is perfect.

(d) For $x\in C$ with the ternary expansion $\sum_{k=1}^{\infty}a_{k}3^{-k}$, define

$$
\varphi ( x ) : = \sum _ { k = 1 } ^{\infty} a _ { k } 2 ^{- ( k + 1 )} ~ .
$$

Then $\varphi: C \to [0,1]$ is increasing, surjective and continuous.

(e) $C$ is uncountable.

(f) $\varphi$ has a continuous extension $f:[0,1]\to[0,1]$ which is constant on each interval in $[0,1]\setminus C$. The function $f$ is called the Cantor function of $C$.





# List of Problems from [1]

9 Let $X$ be a metric space. A function $f : X \to \mathbb{R}$ is called lower continuous at $a \in X$ if, for each sequence $(x_n)$ in $X$ such that $\lim x_n = a$, we have $f(a) \leq \lim f(x_n)$. It is called upper continuous at $a$ if $-f$ is lower continuous at $a$. Finally $f$ is called lower continuous (or upper continuous) if $f$ is lower continuous (or upper continuous) at each point of $X$.

(a) Show the equivalence of the following:

(i) $f$ is lower continuous.

(ii) For each $a \in X$ and $\varepsilon > 0$, there is some $U \in \mathcal{U}(a)$ such that $f(x) > f(a) - \varepsilon$ for all $x \in U$.

(iii) For each $\alpha \in \mathbb{R}$, $f^{-1}((\alpha, \infty))$ is open.

(iv) For each $\alpha \in \mathbb{R}$, $f^{-1}((-\infty, \alpha])$ is closed.

(b) $f$ is continuous if and only if $f$ is lower and upper continuous.

(c) Let $\chi_A$ be the characteristic function of $A \subseteq X$. Then $A$ is open if and only if $\chi_A$ is lower continuous.

(d) Let $X$ be compact and $f : X \to \mathbb{R}$ lower continuous. Then $f$ attains its minimum, that is, there is some $x \in X$ such that $f(x) \leq f(y)$ for all $y \in X$. (Hint: Consider a sequence $(x_n)$ in $X$ such that $f(x_n) \to \inf f(X)$.)

10 Let $f,g:[0,1]\to\mathbb{R}$ be defined by

$$
f ( x ) : = \left\{ \begin{array}{ll} { 1 / n \ , } & { x \in \mathbb { Q } \mathrm { ~ w h e r e ~ } x = m / n \mathrm { ~ i n ~ l o w e s t ~ t e r m s } \, , } \\{ 0 \ , } & { x \notin \mathbb { Q } \, , } \end{array} \right.
$$

and

$$
g ( x ) : = \left\{ \begin{array}{ll} { ( - 1 ) ^{n} n / ( n + 1 ) \, , } & { x \in \mathbb { Q } \mathrm { ~ w h e r e ~ } x = m / n \mathrm { ~ i n ~ l o w e s t ~ t e r m s } \, , } \\{ 0 \, , } & { x \notin \mathbb { Q } \, . } \end{array} \right.
$$

Prove or disprove the following:

(a) $f$ is upper continuous.(b) $f$ is lower continuous.(c) $g$ is upper continuous.(d) $g$ is lower continuous.

11 Let $X$ be a metric space and $f:[0,1)\to X$ continuous. Show that $f$ is uniformly continuous if $\lim_{t\to 1}f(t)$ exists.

12 Which of the functions

$$
f : ( 0 , \infty ) \to \mathbb { R } \, ,  t \mapsto ( 1 + t ^{2} ) ^{- 1} \, ,  g : ( 0 , \infty ) \to \mathbb { R } \, ,  t \mapsto t ^{- 2}
$$

is uniformly continuous?

13 Prove that a finite dimensional subspace of a normed vector space is closed.

(Hint: Let $E$ be a normed vector space and $F$ a subspace of $E$ with finite dimension. Let $(v_n)$ be a sequence in $F$ and $v \in E$ such that $\lim v_n = v$ in $E$. Because of Remark I.12.5, Proposition 1.10 and the Bolzano-Weierstrass theorem, there are some subsequence $(v_{n_k})_{k \in \mathbb{N}}$ of $(v_n)$ and $w \in F$ such that $\lim_k v_{n_k} = w$ in $F$. Now use Propositions 2.11 and 2.17 to show that $v = w \in F$.) Page 29 of 50





# List of Problems from [1]

14 Suppose that $X$ is a metric space and $f : X \to \mathbb{R}$ is bounded. Show that $\omega_f : X \to \mathbb{R}$ is upper continuous (see Exercises 1.17 and 2.20).

15 Show that the closed unit ball in $\ell_\infty$ (see Remark II.3.6(a)) is not compact.

(Hint: Consider the sequence $(e_n)$ of 'unit vectors' $e_n$ given by $e_n(j) := \delta_{nj}$ for all $j \in \mathbb{N}$.)





List of Problems from [1]

<div style="display: block; width: 100%"><img src="https://storage.simpletex.cn/view/m892e34b44cba182720bc487f048a37be" style="width: 47%; max-width: 47%" /></div>

Now define $\widetilde{w}:[\alpha,\beta+1]\to X$ by

$$
\tilde { w } ( t ) : = \left\{ \begin{array}{cc} { w ( t ) \ , } & { t \in [ \alpha , \beta ] \ , } \\{ ( t - \beta ) y + ( \beta + 1 - t ) x \ , } & { t \in ( \beta , \beta + 1 ] \ . } \end{array} \right.
$$

Then $\widetilde{w}$ is a polygonal path in $X$ which connects $a$ and $y$. This shows that $\mathbb{B}(x,r)$ is contained in $M$, $x$ is an interior point of $M$, and $M$ is open in $X$.

(iii) It remains to show that $M$ is closed. Let $y \in X \backslash M$. Since $X$ is open, there is some $r > 0$ such that $\mathbb{B}(y,r)$ is contained in $X$. The sets $\mathbb{B}(y,r)$ and $M$ must be disjoint since, if $x \in \mathbb{B}(y,r) \cap M$, then, by the argument of (ii), there would be a polygonal path in $X$ connecting $a$ and $y$, and so $y$ is in $M$, contrary to assumption. Thus $y$ is an interior point of $X \backslash M$ and, since $y \in X \backslash M$ is arbitrary, $X \backslash M$ is open. This implies that $M$ is closed in $X$. ■

4.11 Corollary An open subset of a normed vector space is connected if and only if it is path connected.

Proof This follows from Proposition 4.8 and Theorem 4.10. ■

# Connectivity in General Topological Spaces

To end this section we analyze the above proofs for their dependence on the existence of a metric.

4.12 Remarks (a) The definitions of 'connected' and 'path connected' depend on the topology only and do not make use of a metric. Hence these are valid in any topological space. The same is true for Propositions 4.2, 4.5 and 4.8. In particular, the generalized intermediate value theorem (Theorem 4.7) holds when $X$ is an arbitrary topological space.

(b) There are examples of connected spaces which are not path connected. For this reason, Theorem 4.10 is particularly useful. ■

# Exercises

In the following, $X$ is a metric space.





# List of Problems from [1]

# III.4 Connectivity

(a) $X$ is connected.(b) There is no continuous surjection $X \rightarrow \{0,1\}$.

2 Suppose that $C_{\alpha} \subseteq X$ is connected for each $\alpha$ in an index set A. Show that $\bigcup_{\alpha} C_{\alpha}$ is connected if $C_{\alpha} \cap C_{\beta} \neq \emptyset$ for all $\alpha, \beta \in \mathbf{A}$. That is, arbitrary unions of connected pairwise nondisjoint sets are connected. (Hint: Use Exercise 1 and prove by contradiction.)

3 Show by example that the intersection of connected sets is not, in general, connected.

4 Let $X_j$, $j=1,\ldots,n$, be metric spaces. Prove that the product $X_1 \times \cdots \times X_n$ is connected if and only if each $X_j$ is connected. (Hint: Write $X \times Y$ as a union of sets of the form $(X \times \{y\}) \cup (\{x\} \times Y)$.)

5 Show that the closure of a connected set is also connected. (Hint: Consider a continuous function $f:\overline{A}\to\{0,1\}$ and use $f(\overline{A})\subseteq f(A)$ (see Exercise 2.12).)

6 Given an element $x \in X$, the set

$$
K ( x ) : = \bigcup _ { Y \in M } Y  { \mathrm { w h e r e } }  M : = \{ \, Y \subseteq X \; ; \; Y { \mathrm { ~ i s ~ c o n n e c t e d ~ a n d ~ } } x \in Y \}
$$

is, by Exercise 2, the largest connected subset of $X$ which contains $x$, and hence is called the connected component of $x$ in $X$. Prove the following:

(a) $\{K(x)\; ;\ x \in X\}$ is a partition of $X$, that is, each $x \in X$ is contained in exactly one connected component of $X$.

(b) Each connected component is closed.

7 Determine all the connected components of $\mathbb{Q}$ in $\mathbb{R}$.

8 Let $E=(E,\|\cdot\|)$ be a normed vector space with $\dim(E)\geq2$. Prove that $E\setminus\{0\}$ and the unit sphere $S:=\{x\in E;\ \|x\|=1\}$ are connected.

9 Prove that the following metric spaces $X$ and $Y$ are not homeomorphic (see Exercise 3.3):

(a) $X := S^1$, $Y := [0, 1]$.

(b) $X := \mathbb{R}$, $Y := \mathbb{R}^n$, $n \geq 2$.

(c) $X := (0, 1) \cup (2, 3)$, $Y := (0, 1) \cup (2, 3]$.

(Hint: In each case, remove one or two points from $X$.)

10 Show that the set $O(n)$ of all real orthogonal $n \times n$ matrices is not connected. (Hint: The function $O(n) \to \{-1, 1\}$, $A \mapsto \det A$ is continuous and surjective (see Exercise 1.16).)

11 For $b_{j,k} \in \mathbb{R}$, $1 \leq j, k \leq n$, consider the bilinear form

$$
B : \mathbb { R } ^{n} \times \mathbb { R } ^{n} \to \mathbb { R } \ ,  ( x , y ) \mapsto \sum _ { j , k = 1 } ^{n} b _ { j , k } x _ { j } y _ { k } \ .
$$

If $B(x,x)>0$ (or $B(x,x)<0$) for all $x\in\mathbb{R}^n\setminus\{0\}$, then $B$ is called positive (or negative) definite. If $B$ is neither positive nor negative definite, it is indefinite. Show the following:

(a) If $B$ is indefinite, then there is some $x \in S^{n-1}$ such that $B(x,x)=0$.

(b) If $B$ is positive definite, then there is some $\beta>0$ such that $B(x,x)\geq\beta\left|x\right|^{2}$, $x \in \mathbb{R}^{n}$.

(Hint: For (a), use the intermediate value theorem. For (b), use the extreme value theorem.) Page 32 of 50





# List of Problems from [1]

12 Let $E$ be a vector space. Suppose that $x_1,\ldots,x_n\in E$ and $\alpha_1,\ldots,\alpha_n\in\mathbb{R}^+$ are such that $\sum_{j=1}^{n}\alpha_j=1$. Then $\sum_{j=1}^{n}\alpha_jx_j$ is called a convex combination of $x_1,\ldots,x_n$. Prove the following:

(a) Arbitrary intersections of convex subsets of $E$ are convex.

(b) A subset $M$ of $E$ is convex if and only if $M$ is closed under convex combinations, that is, every convex combination of points of $M$ is in $M$.

(c) If $E$ is a normed vector space and $M \subseteq E$ is convex, then $\dot{M}$ and $\overline{M}$ are also convex.





# List of Problems from [1]

5.8 Examples (a) For each $n \in \mathbb{N}^{\times}$, the function

$$
\mathbb { R } ^{+} \rightarrow \mathbb { R } ^{+} , ~ ~ x \mapsto \sqrt [ n ] { x }
$$

is continuous$^{1}$ and strictly increasing. In addition, $\lim_{x\to\infty}\sqrt[n]{x}=\infty$.

Proof For $n \in \mathbb{N}^\times$, let $f : \mathbb{R}^+ \to \mathbb{R}^+$ be defined by $t \mapsto t^n$. Being the restriction of a polynomial function, $f$ is continuous. If $0 \leq s < t$, then

$$
f ( t ) - f ( s ) = t ^{n} - s ^{n} = t ^{n} \bigg ( 1 - \left( \frac { s } { l } \right) ^{n} \bigg ) > 0 ~ ,
$$

which shows that $f$ is strictly increasing. Finally $\lim_{t\to\infty}f(t)=\infty$ and so all claims follow from Theorem 5.7. ■

(b) The continuity claim of Theorem 5.7(iii) is false, in general, if $I$ is not an interval.

Proof The function $f: Z \to \mathbb{R}$ of Example 1.9(c) is continuous and strictly increasing, but the inverse function of $f$ is not continuous. ■

Further important applications of the inverse function theorem for monotone functions appear in the following section.

# Exercises

In the following, $I$ is a compact interval containing more than one point.

1 Let $f: I \to I$ be continuous. Show that $f$ has a fixed point, that is, there is some $\xi \in I$ such that $f(\xi) = \xi$.

2 Let $f: I \to \mathbb{R}$ be continuous and injective. Show that $f$ is strictly monotone.

3 Let $D$ be an open subset of $\mathbb{R}$ and $f: D \to \mathbb{R}$ continuous and injective. Prove that $f: D \to f(D)$ is a homeomorphism.$^2$

4 Let $\alpha : \mathbb{N} \to \mathbb{Q}$ be a bijection and, for $x \in \mathbb{R}$, let $N_x$ be the set $\left\{ k \in \mathbb{N} ; \ \alpha(k) \leq x \right\}$. Let $(y_n)$ be a sequence in $(0,\infty)$ such that $\sum y_n < \infty$. Define

$$
f : \mathbb { R } \to \mathbb { R } ~ , ~ ~ x \mapsto \sum _ { k \in N _ { x } } y _ { k } ~ .
$$

Prove the following:$^{3}$

(a) $f$ is strictly monotone.

(b) $f$ is continuous at each irrational number.

(c) At each rational number $q$, there is a jump discontinuity of size $y_n$ where $n=\alpha^{-1}(q)$.





# List of Problems from [1]

5 Consider the function

$$
f : \left[ 0 , 1 \right] \rightarrow \left[ 0 , 1 \right] ,  x \mapsto { \left\{ \begin{array}{ll} { x \, , } & {  x { \mathrm { ~ r a t i o n a l ~ } } , } \\{ 1 - x \, , } & {  x { \mathrm { ~ i r r a t i o n a l ~ } } . } \end{array} \right. }
$$

Show the following:

(a) $f$ is bijective.

(b) $f$ is not monotone on any subinterval of $[0,1]$.

(c) $f$ is continuous only at $x=1/2$.

6 Let $f_0 := \text{zigzag}$ (see Exercise 1.1) and

$$
F ( x ) : = \sum _ { n = 0 } ^{\infty} 4 ^{- n} f _ { 0 } ( 4 ^{n} x ) ~ ,  x \in \mathbb { R } ~ .
$$

Prove the following:

(a) $F$ is well defined.

(b) $F$ is not monotone on any interval.

(c) $F$ is continuous.

(Hint: (a) For each $x \in \mathbb{R}$, find a convergent majorant for $\sum 4^{-n} f_0(4^n x)$.

(b) Let $f_n(x) := 4^{-n} f_0(4^n x)$ for all $x \in \mathbb{R}$ and $n \in \mathbb{N}$. Set $a := k \cdot 4^{-m}$ and $h := 4^{-2^{m-1}}$ for $k \in \mathbb{Z}$ and $m \in \mathbb{N}^\times$. Then

$$
f _ { n } ( a ) = 0 \ ,  n \geq m \ ,  \mathrm { ~ a n d ~ }  f _ { n } ( a \pm h ) = 0 \ ,  n \geq 2 m + 1 \ ,
$$

and so $F(a \pm h) - F(a) \geq h$. Finally approximate an arbitrary $x \in \mathbb{R}$ by $k \cdot 4^{-m}$ with $k \in \mathbb{Z}$ and $m \in \mathbb{N}^\times$.

(c) For $x,y\in\mathbb{R}$ and $m\in\mathbb{N}^\times$, we have $|F(x)-F(y)|\leq\sum_{k=0}^m|f_k(x)-f_k(y)|+4^{-m}/3$.)

7 Let $f: I \to \mathbb{R}$ be monotone. Prove that $\omega_f(x) = |f(x+)-f(x-)|$ where $\omega_f(x)$ is defined as in Exercise 1.17.





# List of Problems from [1]

From Example 2.25(b) we know that

$$
r _ { n } : = \left[ \frac { e ^{z / n} - 1 } { z / n } - 1 \right] \rightarrow 0 ~ ,  n \rightarrow \infty ~ .
$$

To estimate

$$
L _ { n } : = \sum _ { k = 0 } ^{n - 1} ( e ^{z / n} ) ^{k} ( 1 + z / n ) ^{n - 1 - k} ~ ,  n \in \mathbb { N } ^{\times} ~ ,
$$

we use the inequalities

$$
| e ^{w} | = e ^{\mathrm { R e} \, w } \leq e ^{| w |} \ ,  | 1 + w | \leq 1 + | w | \leq e ^{| w |}
$$

to get

$$
| L _ { n } | \leq \sum _ { k = 0 } ^{n - 1} ( e ^{| z | / n} ) ^{k} ( e ^{| z | / n} ) ^{n - 1 - k} = n ( e ^{| z | / n} ) ^{n - 1} \leq n e ^{| z |} ~ ,  n \in \mathbb { N } ^{\times} ~ .
$$

Combining (6.15), (6.17) and (6.18) we get

$$
\left| e ^{z} - \left( 1 + \frac { z } { n } \right) ^{n} \right| = \left| \frac { z } { n } r _ { n } L _ { n } \right| \leq \left| \frac { z } { n } \right| | r _ { n } | n e ^{| z |} = | z | e ^{| z |} | r _ { n } | ~ ,
$$

which, with (6.16), proves the claim. ■

# Exercises

1 Show that the functions $\operatorname{cis} : \mathbb{R} \rightarrow \mathbb{C}$ and $\cos, \sin: \mathbb{R} \rightarrow \mathbb{R}$ are Lipschitz continuous with Lipschitz constant 1. (Hint: See Example 2.25(b).)

2 For $z \in \mathbb{C}$ and $m \in \mathbb{N}$, prove de Moivre's formula,

$$
( \cos z + i \sin z ) ^{m} = \cos ( m z ) + i \sin ( m z ) ~ .
$$

3 Prove the following trigonometric identities:

(a) $\cos^{2}(z/2)=(1+\cos z)/2$, $\sin^{2}(z/2)=(1-\cos z)/2$, $z\in\mathbb{C}$.

(b) $\tan(z/2)=(1-\cos z)/\sin z=\sin z/(1+\cos z)$, $z\in\mathbb{C}\backslash(\pi\mathbb{Z})$.

4 The hyperbolic cosine and hyperbolic sine functions are defined by

$$
\cosh ( z ) : = \frac { e ^{z} + e ^{- z} } { 2 }  \mathrm { ~ a n d ~ }  \sinh ( z ) : = \frac { e ^{z} - e ^{- z} } { 2 } \, ,  z \in \mathbb { C } \ .
$$

For $w, z \in \mathbb{C}$, show the following:

(a) $\cosh^{2} z - \sinh^{2} z = 1$.

(b) $\cosh (z + w) = \cosh z \cosh w + \sinh z \sinh w$.

(c) $\sinh (z + w) = \sinh z \cosh w + \cosh z \sinh w$.

(d) $\cosh z = \cos i z$, $\sinh z = -i \sin i z$.

(e) $\cosh z = \sum_{k=0}^{\infty} \frac{z^{2k}}{(2k)!}$, $\sinh z = \sum_{k=0}^{\infty} \frac{z^{2k+1}}{(2k+1)!}$ Page 36 of 50





# List of Problems from [1]

5 The hyperbolic tangent and hyperbolic cotangent functions are defined by

$$
\operatorname { t a n h } z : = \frac { \sinh ( z ) } { \cosh ( z ) } \, ,  z \in \mathbb { C } \backslash \pi i \left( Z + 1 / 2 \right) \, ,  \mathrm { a n d }  \coth z : = \frac { \cosh ( z ) } { \sinh ( z ) } \, ,  z \in \mathbb { C } \backslash \pi i \mathbb { Z } \, .
$$

The functions $\cosh$, $\sinh$, $\tanh$ and $\coth$ have real values for real arguments. Sketch the graphs of these real valued functions.

Show the following:

(a) The functions

cosh, $\sinh$, $\tanh:\mathbb{C}\backslash\pi i(\mathbb{Z}+1/2)\to\mathbb{C}$, $\coth:\mathbb{C}^{\times}\to\mathbb{C}\backslash\pi i\mathbb{Z}$

are continuous.

(b) $\lim_{x\to\pm\infty}\tanh(x)=\pm1$, $\lim_{x\to\pm0}\coth(x)=\pm\infty$.

(c) $\cosh:[0,\infty)\to\mathbb{R}$ is strictly increasing with $\cosh(\left[0,\infty\right)\rangle=[1,\infty)$.

(d) $\sinh:\mathbb{R}\to\mathbb{R}$ is strictly increasing and bijective.

(e) $\tanh:\mathbb{R}\to(-1,1)$ is strictly increasing and bijective.

(f) $\coth:(0,\infty)\to\mathbb{R}$ is strictly decreasing with $\coth((0,\infty))=(1,\infty)$.

(g) $\tanh:\mathbb{R}\to(-1,1)$ is Lipschitz continuous with Lipschitz constant 1

6 Determine the following limits:

$$
\mathrm { ( a ) } \; \operatorname* { l i m } _ { x \to 0 + } x ^{x} \, ,  \mathrm { ( b ) } \; \operatorname* { l i m } _ { x \to 0 + } x ^{1 / x} \, ,  \mathrm { ( c ) } \; \operatorname* { l i m } _ { z \to 0 } \frac { \log ( 1 + z ) } { z } \, .
$$

(Hint: (c) See Example 2.25(b).)

7 For $x,y>0$, prove the inequality

$$
\frac { \log x + \log y } { 2 } \leq \log \left( \frac { x + y } { 2 } \right) \, .
$$

8 Determine the following limits:

$$
\mathrm { ( a ) } \; \operatorname* { l i m } _ { z \to 0 } { \frac { \sin z } { z } } \; ,  \mathrm { ( b ) } \; \operatorname* { l i m } _ { z \to 0 } { \frac { a ^{z} - 1 } { z } } \; ,  a \in \mathbb { C } ^{\times} \; .
$$

9 Show that the functions

arg : $\mathbb{C} \backslash (-\infty, 0] \to (-\pi, \pi)$ , $ \log : \mathbb{C} \backslash (-\infty, 0] \to \mathbb{R} + i(-\pi, \pi)$ , are continuous. (Hint: (i) arg = arg $\circ \nu$ with $\nu(z) := z/|z|$ for all $z \in \mathbb{C}^\times$. (ii) arg $\left|\left(S^1 \setminus \{-1\}\right)\right\rangle=\left[\operatorname{cis}\left|(-\pi, \pi)\right|\right]^{-1}$. (iii) Use Exercise 3.3(b) for intervals of the form $[-a, a]$ with $a \in (0, \pi)$.)

10 Prove the following rules for the principal value of the power function:

$$
z ^{a} z ^{b} = z ^{a + b} \, ,  z ^{a} w ^{a} = ( z w ) ^{a} \, ,  z , w \in \mathbb { C } ^{x} \, ,  a , b \in \mathbb { C } \, .
$$





# List of Problems from [1]

12 Let $x \in \mathbb{R}$, $n \in \mathbb{N}^{\times}$ and $z_{n,k} := e^{ixk/n} \in S^{1}$ for all $k=0,1,\ldots,n$. Set

$$
L _ { n } : = \sum _ { k = 1 } ^{n} | z _ { n , k } - z _ { n , k - 1 } | ~ ,
$$

the length of the polygonal path with vertices $z_{n,0}, z_{n,1}, \ldots, z_{n,n}$. Show that

$$
L _ { n } = 2 n \left| \sin \left( x / ( 2 n ) \right) \right|  \mathrm { a n d }  \operatorname* { l i m } _ { n \to \infty } L _ { n } = | x | \ .
$$

Remark For large $n \in \mathbb{N}$ and $x \in [0,2\pi]$, the image of $[0,x]$ under the function $\text{cis}$ is approximated by the polygonal path with vertices $z_{n,0}, z_{n,1}, \ldots, z_{n,n}$. Thus $L_n$ is an approximation of the length of the arc of the circle between 1 and $\text{cis}(x) = e^{i x}$. This exercise shows that the function $\text{cis} : \mathbb{R} \to S^1$ 'wraps' the line $\mathbb{R}$ around $S^1$ in such a way that length is preserved.

13 Investigate the behavior of the function $\mathbb{C} \to \mathbb{C}$, $z \mapsto z^2$. In particular, calculate the images of the hyperbolas $x^2 - y^2 = \text{const}$, $xy = \text{const}$, as well as the lines $x = \text{const}$, $y = \text{const}$ for $z = x + iy$.

14 Determine all solutions in $\mathbb{C}$ of the following equations:

(a) $z^{4}=(\sqrt{2}/2)(1+i)$.

(b) $z^{5}=i$.

(c) $z^{3}+6z+2=0$.

(d) $z^{3}+(1-2i)z^{2}-(1+2i)z-1=0$.

(Hint: For the cubic equations in (c) and (d), use Exercise I.11.15.)

15 For $x \in \mathbb{R}$ and $n \in \mathbb{N}$, let

$$
f _ { n } ( x ) : = \operatorname* { l i m } _ { k \to \infty } \left( \cos ( n ! \, \pi x ) \right) ^{2 k} .
$$

Determine $\lim_{n\to\infty}f_n(x)$. (Hint: Consider separately the case $x\in\mathbb{R}\backslash\mathbb{Q}$, and use the fact that $|\cos(m\pi)|=1$ if and only if $m\in\mathbb{Z}$.)

16 Prove that $\cosh 1$ is irrational. (Hint: Exercise II.7.10.)





# List of Problems from [1]

# Exercises

1 Calculate the derivative of $f : (0, \infty) \to \mathbb{R}$ when $f(x)$ is

$$
\begin{array}{rl} & {  ( \mathrm { a ) ~ } ( x ^{x} ) ^{x} \, ,  ( \mathrm { b ) ~ } x ^{( x ^ { x} ) } \, ,  ( \mathrm { c ) ~ } x ^{1 / x} \, ,  ( \mathrm { d ) ~ } \log \log ( 1 + x ) \, , } \\& {  ( \mathrm { e ) ~ } x ^{\sin x} \, ,  ( \mathrm { f ) ~ } \sqrt [ 3 ] { x ^{3 / 5} + \sin ^{3} ( 1 / x ) - \tan ^{2} ( x ) } \, ,  ( \mathrm { g ) ~ } \frac { \cos x } { 2 + \sin \log x } \ . } \end{array}
$$

2 For $m,n\in\mathbb{N}$, let $f_{m,n}:\mathbb{R}\to\mathbb{R}$ be defined by

$$
f _ { m , n } ( x ) : = \left\{ \begin{array}{ll} { x ^{n} \sin ( x ^{- m} ) \, , } & {  x \neq 0 \, , } \\{ 0 \, , } & {  x = 0 \, . } \end{array} \right.
$$

For what $k \in \bar{\mathbb{N}}$ is $f_{m,n} \in C^{k}(\mathbb{R})$?

3 Suppose that $f,g\colon\mathbb{K}\to\mathbb{K}$ satisfy $f'=f$, $f(x)\neq0$ for all $x\in\mathbb{K}$, and $g'=g$. Show that $f$ and $g$ are in $C^\infty(\mathbb{K},\mathbb{K})$ and that there is some $c\in\mathbb{K}$ such that $g=cf$.

4 Show that $f : \mathbb{C} \to \mathbb{C}$, $z \mapsto \overline{z}$ is nowhere differentiable.

5 At what points is $f: \mathbb{C} \rightarrow \mathbb{C}$, $z \mapsto z\bar{z}$ differentiable?

6 Let $U$ be a neighborhood of 0 in $\mathbb{K}$, $E$ a normed vector space and $f: U \to E$.

(a) Suppose that there are numbers $K>0$ and $\alpha>1$ such that $|f(x)|\leq K|x|^{\alpha}$ for all $x\in U$. Show that $f$ is differentiable at 0.

(b) Suppose that $f(0)=0$ and there are $K>0$ and $\alpha\in(0,1)$ such that $|f(x)|\geq K|x|^{\alpha}$ for all $x\in U$. Show that $f$ is not differentiable at 0.

(c) What can be said if $|f(x)|=K|x|$ for all $x\in U$?

7 Calculate $\partial_{\pm}f(x)$ for the function $f:\mathbb{R}\rightarrow\mathbb{R}$, $x\mapsto[x]+\sqrt{x-x]}$. Where is $f$ differentiable?

8 Suppose that $I$ is a perfect interval and $f,g: I \to \mathbb{R}$ are differentiable. Prove or disprove that the functions $|f|$, $f \lor g$ and $f \land g$ are (a) differentiable, (b) one-sided differentiable.

9 Let $U$ be open in $\mathbb{K}$, $a \in U$ and $f: U \to E$. Prove or disprove the following:

(a) If $f$ differentiable at $a$, then

$$
f ^{\prime} ( a ) = \operatorname* { l i m } _ { h \to 0 } { \frac { f ( a + h ) - f ( a - h ) } { 2 h } } \, .
$$

(b) If $\lim_{h\to0}\left[f(a+h)-f(a-h)\right]/2h$ exists, then $f$ is differentiable at $a$ and (1.8) holds.

10 Let $n \in \mathbb{N}^{\times}$ and $f \in C^{n}(\mathbb{K})$. Prove that

$$
\partial ^{n} \left( x f ( x ) \right) = x \partial ^{n} f ( x ) + n \partial ^{( n - 1 )} f ( x ) ~ .
$$

11 For $n \in \mathbb{N}^{\times}$, show that

$$
\frac { \partial ^{n} ( x ^{n - 1} e ^{i / x} ) = ( - 1 ) ^{n} \frac { e ^{1 / x} } { x \mathrm { P a g e ~ 39 } _ { x }  \gg  50 } }
$$





# List of Problems from [1]

316

12 The Legendre polynomial $P_{n}$ is defined by

$$
P _ { n } ( x ) : = \frac { 1 } { 2 ^{n} n ! } \partial ^{n} \left[ ( x ^{2} - 1 ) ^{n} \right] \, ,  n \in \mathbb { N } \ .
$$

(a) Calculate $P_0, P_1, \ldots, P_5$.

(b) Show that $P_n$ is a polynomial of degree $n$ which has $n$ zeros in $(-1, 1)$.





# List of Problems from [1]

If $\alpha \in (-\infty, \infty]$, then, by a similar argument,

$$
\operatorname* { l i m } _ { x \to a } f ( x ) / g ( x ) \geq \alpha ~ .
$$

Thus we have proved the claim if either (i) or $\lim_{x\to a}g(x)=\infty$ holds. The case $\lim_{x\to a}g(x)=-\infty$ can be proved similarly and is left to the reader. ■

2.22 Remark Of course, the corresponding statements for the left limit $x \to b$ also are true. In addition, the proof of Proposition 2.21 remains valid in the cases $a = -\infty$ and $b = \infty$. ■

2.23 Examples (a) For all $m, n \in \mathbb{N}^\times$ and $a \in \mathbb{R}$,

$$
\operatorname* { l i m } _ { x \to a } { \frac { x ^{n} - a ^{n} } { x ^{m} - a ^{m} } } = \operatorname* { l i m } _ { x \to a } { \frac { n x ^{n - 1} } { m x ^{m - 1} } } = { \frac { n } { m } } a ^{n - m} ~ .
$$

(b) Let $n \geq 2$ and $a_k \in [0, \infty)$ for $1 \leq k \leq n$. Then, from Proposition 2.21, we have

$$
\begin{array}{rl} & { \operatorname* { l i m } _ { x \to \infty } \Big ( \bigwedge ^{\sqrt [ n ] { x ^ { n} + a _ { 1 } x ^{n - 1} + \cdots + a _ { n } } } - x \big ) = \operatorname* { l i m } _ { y \to 0 + } \frac { \sqrt [ n ] { 1 + a _ { 1 } y + \cdots + a _ { n } y ^{n} } - 1 } { y } } \\& {  = \operatorname* { l i m } _ { y \to 0 + } \frac { 1 } { n } \frac { a _ { 1 } + 2 a _ { 2 } y + \cdots + n a _ { n } y ^{n - 1} } { ( 1 + a _ { 1 } y + \cdots + a _ { n } y ^{n} ) ^{1 - 1 / n} } } \\& {  = \frac { a _ { 1 } } { n } . } \end{array}
$$

(c) For all $a \in \mathbb{R}^{\times}$,

$$
\operatorname* { l i m } _ { x \to 0 } { \frac { 1 - \cos ( a x ) } { 1 - \cos x } } = a ^{2} ~ .
$$

Proof Using l'Hospital's rule twice we get

$$
\operatorname* { l i m } _ { x \to 0 } { \frac { 1 - \cos ( a x ) } { 1 - \cos x } } = \operatorname* { l i m } _ { x \to 0 } { \frac { a \sin ( a x ) } { \sin x } } = \operatorname* { l i m } _ { x \to 0 } { \frac { a ^{2} \cos ( a x ) } { \cos x } } = a ^{2} ~ ,
$$

and so the claim is proved. ■

# Exercises

1 Let $f : \mathbb{R} \rightarrow \mathbb{R}$ be defined by

$$
f ( x ) : = \left\{ \begin{array}{ll} { e ^{- 1 / x ^ { 2} } \, , } & { x \neq 0 \; , } \\{ 0 \, , } & { x = 0 \; . } \end{array} \right.
$$

Show that $f$ is in $C^{\infty}(\mathbb{R})$, that $f$ has an isolated$^{5}$ global minimum at $x=0$, and that $f^{(k)}(0)=0$ for $k\in\mathbb{N}$.





# List of Problems from [1]

2 Let $f$ be the function of Example 1.17 and $F(x):=e^{e}f\big(f(1)-f(1-x)\big)$, $x\in\mathbb{R}$. Show that

$$
F ( x ) = \left\{ \begin{array}{ll} { 0 \, , } & { x \leq 0 \, \mathrm { ~ , } } \\{ 1 \, , } & { x \geq 1 \, \mathrm { ~ , } } \end{array} \right.
$$

and $F$ is strictly increasing on $[0,1]$.

3 Let $-\infty < a < b < \infty$ and $f \in C([a,b],\mathbb{R})$ be differentiable on $(a,b]$. Show that, if $\lim_{x \to a} f'(x)$ exists, then $f$ is in $C^1([a,b],\mathbb{R})$ and $f'(a) = \lim_{x \to a} f'(x)$. (Hint: Use the mean value theorem.)

4 Let $a>0$ and $f\in C^{2}([[-a,a],\mathbb{R})$ be even. Show that there is some $g\in C^{1}([0,a^{2}],\mathbb{R})$ such that $f(x)=g(x^{2})$ for all $x\in[-a,a]$. In particular, $f'(0)=0$. (Hint: Exercise 3.)

5 The functions

$$
\cosh ^{- 1} : [ 1 , \infty ) \to \mathbb { R } ^{+}  { \mathrm { a n d } }  \sinh ^{- 1} : \mathbb { R } \to \mathbb { R }
$$

are called the inverse hyperbolic cosine and inverse hyperbolic sine functions.

(a) Show that $\cosh^{-1}$ and $\sinh^{-1}$ are well defined and that

$$
\begin{array}{rl} & { \cosh ^{- 1} ( x ) = \log \bigl ( x + \sqrt { x ^{2} - 1 } \bigr ) ~ ,  x \geq 1 ~ , } \\& { \sinh ^{- 1} ( x ) = \log \Bigl ( x + \sqrt { x ^{2} + 1 } \Bigr ) ~ ,  x \in \mathbb { R } ~ . } \end{array}
$$

(b) Calculate the first two derivatives of these functions.

(c) Discuss the convexity and concavity of $\cosh$, $\sinh$, $\cosh^{-1}$ and $\sinh^{-1}$. Sketch the graphs of these functions.

6 Let $n \in \mathbb{N}^{\times}$ and $f(x) := 1 + x + x^{2}/2! + \cdots + x^{n}/n!$ for all $x \in \mathbb{R}$. Show that the equation $f(x) = 0$ has exactly one real solution if $n$ is odd, and no real solutions if $n$ is even.

7 Suppose that $-\infty \leq a < b \leq \infty$ and $f: (a,b) \to \mathbb{R}$ is continuous. A point $x_0 \in (a,b)$ is called an inflection point of $f$ if there are $a_0, b_0$ such that $a \leq a_0 < x_o < b_0 \leq b$ and $f|(a_0, x_0)$ is convex and $f|(x_0, b_0)$ is concave, or $f|(a_0, x_0)$ is concave and $f|(x_0, b_0)$ is convex.

(a) Let $f : \mathbb{R} \rightarrow \mathbb{R}$ be defined by

$$
f ( x ) : = \left\{ \begin{array}{ll} { - \sqrt { x } \ , } & { x \geq 0 \ , } \\{ - \sqrt { - x } \ , } & { x < 0 \ . } \end{array} \right.
$$

Show that $f$ has an inflection point at 0.

(b) Suppose that $f:(a,b)\to\mathbb{R}$ is twice differentiable and has an inflection point at $x_0$. Show that $f''(x_0)=0$.

(c) Show that the function $f : \mathbb{R} \to \mathbb{R}$, $x \mapsto x^4$ has no inflection points.

$$
\mathrm { ( d ) } \, \underline { { \mathrm { S u p p o s e ~ t h a t ~ } } } f \in C ^{3} \bigl ( ( a , b ) , \mathbb { R } \bigr ) , \; \; f ^{\prime \prime} ( x _ { 0 } ) = 0 \mathrm { ~ a n d ~ } f ^{\prime \prime \prime} ( x _ { 0 } ) \neq 0 . \mathrm { ~ S h o w ~ t h a t ~ } f \mathrm { ~ h a s ~ a n ~ i n f l e c t i o n ~ p o i n t ~ a t ~ } x _ { 0 } .
$$





# List of Problems from [1]

8 Determine all the inflection points of $f$ when $f(x)$ is given by

$$
\mathrm { ( a ) } \ x ^{2} - 1 / x \ , \ \ x > 0 \ ,  \mathrm { ( b ) } \ \sin x + \cos x \ , \ \ x \in \mathbb { R } \ ,  \mathrm { ( c ) } \ x ^{x} \ , \ \ x > 0 \ .
$$

9 Show that $f : (0, \infty) \to \mathbb{R}$, $x \mapsto (1 + 1/x)^x$ is strictly increasing.

10 Suppose that $f \in C([a,b],\mathbb{R})$ is differentiable on $(a,b)$ and satisfies $f(a) \geq 0$ and $f'(x) \geq 0$, $x \in (a,b)$. Prove that $f(x) \geq 0$ for all $x \in [a,b]$.

11 Show that

$$
1 - 1 / x \leq \log x \leq x - 1 ~ ,  x > 0 ~ .
$$

12 Suppose that $I$ is a perfect interval and $f, g: I \to \mathbb{R}$ is convex. Prove or disprove the following:

(a) $f \vee g$ is convex.

(b) $\alpha f + \beta g$ is convex for $\alpha, \beta \in \mathbb{R}$.

(c) $fg$ is convex.

13 Suppose that $I$ is a perfect interval, $f \in C(I, \mathbb{R})$ is convex, and $g : f(I) \to \mathbb{R}$ is convex and increasing. Show that $g \circ f : I \to \mathbb{R}$ is also convex. Find conditions on $f$ and $g$ which ensure that $g \circ f$ is strictly convex.

14 Suppose that $-\infty < a < b < \infty$ and $f : [a, b] \to \mathbb{R}$ is convex. Prove or disprove the following:

(a) For each $x \in (a,b)$, the limits $\partial_{\pm}f(x)$ exist and $\partial_{-}f(x) \leq \partial_{+}f(x)$.

(b) $f|(a,b)$ is continuous.

(c) $f$ is continuous.

15 Let $I$ be a perfect interval, $a \in I$ and $n \in \mathbb{N}$. Suppose that $\varphi, \psi \in C^n(I, \mathbb{R})$ are such that

$$
\varphi ^{( k )} ( a ) = \psi ^{( k )} ( a ) = 0 ~ ,  0 \leq k \leq n ~ ,
$$

$\varphi^{(n+1)}$ and $\psi^{(n+1)}$ exist on $I$, and

$$
\psi ^{( k )} ( x ) \neq 0 ~ ,  x \in \hat { I } \backslash \{ a \} ~ ,  0 \leq k \leq n + 1 ~ .
$$

Show that, for each $x \in I \setminus \{a\}$, there is some $\xi \in (x \wedge a, x \vee a)$ such that

$$
\frac { \varphi ( x ) } { \psi ( x ) } = \frac { \varphi ^{( n + 1 )} ( \xi ) } { \psi ^{( n + 1 )} ( \xi ) } .
$$

16 Suppose that $I$ is an interval, $f \in C^{n-1}(I,\mathbb{R})$ and $f^{(n)}$ exists on $\overset{\circ}{I}$ for some $n \geq 2$. Let $x_0 < x_1 < \cdots < x_n$ be zeros of $f$. Show that there is some $\xi \in (x_0,x_n)$ such that $f^{(n)}(\xi) = 0$ (generalized Rolle's theorem).

17 Calculate the following limits:

$$
\mathrm { ( a ) } \; \operatorname* { l i m } _ { x \to \infty } ( 1 + 2 x ) ^{1 / 3 x} , \; \mathrm { ( b ) } \; \operatorname* { l i m } _ { x \to 1 } \frac { 1 + \cos \pi x } { x ^{2} - 2 x + 1 } , \; \mathrm { ( c ) } \; \operatorname* { l i m } _ { x \to 0 } \frac { \log \cos 3 x } { x ^{2} - 3 \cos 2 x } \, \mathrm { ( d ) } \; \operatorname* { l i m } _ { x \to 0 } \bigl ( \frac { 1 } { \sin ^{2} x } - \frac { 1 } { x ^{2} } \bigr ) .
$$





# List of Problems from [1]

18 Suppose that $(x_k)$ and $(y_k)$ are sequences in $\mathbb{K}^{\mathbb{N}}$, $1 < p < \infty$, and $p'$ is the Hölder conjugate of $p$. Prove the Hölder inequality for series,

$$
\left| \sum _ { k = 0 } ^{\infty} x _ { k } y _ { k } \right| \leq \sum _ { k = 0 } ^{\infty} | x _ { k } y _ { k } | \leq \left( \sum _ { k = 0 } ^{\infty} | x _ { k } | ^{p} \right) ^{1 / p} \left( \sum _ { k = 0 } ^{\infty} | y _ { k } | ^{p ^ { \prime} } \right) ^{1 / p ^ { \prime} } ,
$$

and the Minkowski inequality for series,

$$
\left( \sum _ { k = 0 } ^{\infty} | x _ { k } + y _ { k } | ^{p} \right) ^{1 / p} \leq \left( \sum _ { k = 0 } ^{\infty} | x _ { k } | ^{p} \right) ^{1 / p} + \left( \sum _ { k = 0 } ^{\infty} | y _ { k } | ^{p} \right) ^{1 / p} .
$$

19 For $x=(x_k)\in\mathbb{K}^{\mathbb{N}}$, define

$$
\| x \| _ { p } : = \left\{ \begin{array}{ll} { ( \sum _ { k = 0 } ^{\infty} | x _ { k } | ^{p} ) ^{1 / p} , } & { ~ ~ ~ 1 \leq p < \infty \, , } \\{ \operatorname* { s u p } _ { k \in \mathbb { N } } | x _ { k } | \, , } & { ~ ~ ~ ~ ~ ~ ~ ~ p = \infty \, , } \end{array} \right.
$$

and

$$
\ell _ { p } : = \left\{ x \in \mathbb { K } ^{\mathbb { N} } \ ; \ \| x \| _ { p } < \infty \right\} ,  1 \leq p \leq \infty \ .
$$

Show the following:

(a) $\ell_{p}:=(\ell_{p},\|\cdot\|_{p})$ is a normed subspace of $\mathbb{K}^{\mathbb{N}}$.

(b) $\ell_{\infty}=B(\mathbb{N},\mathbb{K})$.

(c) For $1\leq p\leq q\leq\infty$, we have $\ell_{p}\subseteq\ell_{q}$ and $\|x\|_{q}\leq\|x\|_{p}$, $x\in\ell_{p}$.

20 Suppose that $I$ is a perfect interval and $f : I \to \mathbb{R}$ is convex. Show that

$$
f ( \lambda _ { 1 } x _ { 1 } + \cdots + \lambda _ { n } x _ { n } ) \leq \lambda _ { 1 } f ( x _ { 1 } ) + \cdots + \lambda _ { n } f ( x _ { n } )
$$

for all $x_1,\ldots,x_n\in I$ and $\lambda_1,\ldots,\lambda_n\in\mathbb{R}^+$ satisfying $\lambda_1+\cdots+\lambda_n=1$.

21 Suppose that $I$ is an interval and $f: I \to \mathbb{R}$ is convex. Show that, if $x \in I$ and $h > 0$ satisfy $x + 2h \in I$, then $\triangle_h^2 f(x) \geq 0$. Here $\triangle_h$ is the divided difference operator of length $h$ (see Section I.12). (Hint: Think geometrically.)





# List of Problems from [1]

3.15 Corollary For all $f \in C^n(I, \mathbb{R})$,

$$
\operatorname * { l i m } _ { h \rightarrow 0 + } \triangle _ { h } ^{n} f ( x ) = f ^{( n )} ( x ) ~ ,  x \in I ~ .
$$

Proof This follows directly from (3.13) and Corollary 3.13. ■

3.16 Remarks (a) Let $f \in C^n(I, \mathbb{R})$. By Proposition I.12.13, the Newton interpolation polynomial for $f$ with equally spaced points $x_j := x_0 + jh \in I$, $0 \leq j \leq n$, with $h > 0$, has the form

$$
N _ { n } [ f ; x _ { 0 } ; h ] = \sum _ { j = 0 } ^{n} \frac { \triangle _ { j } ^{j} f ( x _ { 0 } ) } { j ! } \prod _ { k = 0 } ^{j - 1} ( X - x _ { k } ) ~ .
$$

From Corollary 3.15, we get

$$
\operatorname* { l i m } _ { h \to 0 + } N _ { n } [ f ; x _ { 0 } ; h ] = \sum _ { j = 0 } ^{n} \frac { f ^{( j )} ( x _ { 0 } ) } { j ! } ( X - x _ { 0 } ) ^{j} = \mathcal { T } _ { n } ( f , x _ { 0 } ) ~ .
$$

This shows that, in the limit $h \to 0+$, the Newton interpolation polynomial becomes the Taylor polynomial.

(b) Corollaries 3.13 and 3.15 are the theoretical foundation of numerical differentiation. For details and further development see, for example, [WS79] and [IK66], as well the literature on numerical analysis. ■

# Exercises

1 Suppose that $\alpha, \beta, R > 0$ and $p \in C^2([0,R),\mathbb{R})$ satisfy

$$
p ( x ) \geq \alpha \, ,  ( 1 + \beta ) \big [ p ^{\prime} ( x ) \big ] ^{2} \leq p ^{\prime \prime} ( x ) p ( x ) \, ,  x \geq 0 \ .
$$

Show that $R < \infty$ and $p(x) \to \infty$ as $x \to R-$.

(Hint: The function $p^{-\beta}$ is concave. Use a tangent line to $p^{-\beta}$ to provide a lower bound for $p$ (see Application 3.9(e)).

2 Let $a,b\in\mathbb{C}$, $\omega\in\mathbb{R}$, and $f:\mathbb{C}\to\mathbb{C}$ be a twice differentiable function which satisfies

$$
f ( z ) + \omega ^{2} f ^{\prime \prime} ( z ) = 0 ~ ,  z \in \mathbb { C } ~ ,  f ( 0 ) = a ~ ,  f ^{\prime} ( 0 ) = \omega b ~ .
$$

(a) Show that $f$ is in $C^{\infty}(\mathbb{C})$ and that $f$ is uniquely determined by (3.14). Determine $f$.

(b) What is $f$ if (3.14) is replaced by

$$
f ( z ) = \omega ^{2} f ^{\prime \prime} ( z ) ~ ,  z \in \mathbb { C } ~ ,  f ( 0 ) = a ~ ,  f ^{\prime} ( 0 ) = \omega b ~ ?
$$

3 Determine the Taylor series of $f : \mathbb{C} \to \mathbb{C}$ at the point 1 when (a) $f(z) = 3z^3 - 7z^2 + 2z + 4$, (b) $f(z) = e^z$.

4 Calculate the $n^{\text{th}}$ Taylor polynomial at 0 of $\frac{\mathrm{pog}\left((1+5^{r})/(1-50^{x})\right)}{\mathrm{Page}\ 4.5\ \mathrm{of}\ 50}$.





# List of Problems from [1]

5 Determine the domains, the extrema and the inflection points of the following real functions:

(a) $x^{3}/(x-1)^{2}$, (b) $e^{\sin x}$, (c) $x^{n}e^{-x^{2}}$, (d) $x^{2}/\log x$, (e) $\sqrt[3]{(x-1)^{2}(x+1)}$, (f) $\left(\log(3x)\right)^{2}/x$.

6 For $a > 1$, show that

$$
\frac { 1 } { 1 + x } - \frac { 1 } { 1 + a x } \leq \frac { \sqrt { a } - 1 } { \sqrt { a } + 1 } \, ,  x \geq 1 \ .
$$

7 Suppose that $s \in \mathbb{R}$ and $n \in \mathbb{N}$. Show that, for each $x > -1$, there is some $\tau \in (0, 1)$ such that

$$
( 1 + x ) ^{s} = \sum _ { k = 0 } ^{n} { \binom { s } { k } } x ^{k} + { \binom { s } { n + 1 } } { \frac { x ^{n + 1} } { ( 1 + \tau x ) ^{n + 1 - s} } } \ .
$$

Here

$$
\binom { \alpha } { k } : = \left\{ \begin{array}{ll} { \frac { \alpha ( \alpha - 1 ) \cdot \cdots \cdot ( \alpha - k + 1 ) } { k ! } \, , } & {  k \in \mathbb { N } ^{\times} \, , } \\{ 1 \, , } & {  k = 0 \, , } \end{array} \right.
$$

denotes the (general) binomial coefficient$^{5}$ for $\alpha \in \mathbb{C}$.

8 Use (3.15) to approximate $\sqrt[5]{30}$. Estimate the error. (Hint: $\sqrt[5]{30}=2\sqrt[5]{1-(1/16)}$.)

9 Prove the following Taylor series expansion for the general power function:$^{6}$

$$
( 1 + x ) ^{s} = \sum _ { k = 0 } ^{\infty} \binom { s } { k } x ^{k} ~ ,  x \in ( - 1 , 1 ) ~ .
$$

(Hint: To estimate the remainder, distinguish the cases $x \in (0,1)$ and $x \in (-1,0)$ (see Application 3.9(d)).

10 Let $X \subseteq \mathbb{K}$ be perfect and $f \in C^n(X, \mathbb{K})$ for some $n \in \mathbb{N}^\times$. A number $x_0 \in X$ is called a zero of multiplicity $n$ of $f$ if $f(x_0) = \cdots = f^{(n-1)}(x_0) = 0$ and $f^{(n)}(x_0) \neq 0$. Show that, if $X$ is convex, then $f$ has a zero of multiplicity $\geq n$ at $x_0$ if and only if there is some $g \in C(X, \mathbb{K})$ such that $f(x) = (x - x_0)^n g(x)$ for all $x \in X$.

11 Let $p=X^n+a_{n-1}X^{n-1}+\cdots+a_0$ be a polynomial with coefficients in $\mathbb{R}$. Prove or disprove that the function $p+\exp$ has a zero of multiplicity $\leq n$ in $\mathbb{R}$.

12 Prove the following:

(a) For each $n \in \mathbb{N}$, $T_n(x) := \cos(n \arccos x)$, $x \in \mathbb{R}$, is a polynomial of degree $n$ and

$$
T _ { n } ( x ) = x ^{n} + \binom { n } { 2 } x ^{n - 2} ( x ^{2} - 1 ) + \binom { n } { 4 } x ^{n - 4} ( x ^{2} - 1 ) ^{2} + \cdots .
$$

$T_{n}$ is called the Chebyshev polynomial of degree $n$.

(b) These polynomials satisfy the recursion formula

$$
T _ { n + 1 } = 2 X T _ { n } - T _ { n - 1 } \ ,  n \in \mathbb { N } ^{\times} \ .
$$

(c) For each $n \in \mathbb{N}^\times$, $T_n = 2^{n-1}X^n + p_n$ for some polynomial $p_n$ with $\deg(p_n) < n$.





# List of Problems from [1]

(d) $T_{n}$ has a simple zero, that is, a zero of multiplicity 1, at each of the points

$$
x _ { k } : = \cos { \frac { ( 2 k - 1 ) \pi } { 2 n } } \ ,  k = 1 , 2 , \ldots , n \ .
$$

(e) $T_{n}$ has an extremum at each of the points

$$
y _ { k } : = \cos \frac { k \pi } { n } ~ ,  k = 0 , 1 , \ldots , n ~ ,
$$

in $[-1, 1]$, and $T_{n}(y_{k}) = (-1)^{k}$.

(Hint: (a) For $\alpha \in [0, \pi]$ and $x := \cos \alpha$, $\cos n\alpha + i \sin n\alpha = (x + i \sqrt{1 - x^2})^n$.(b) Addition theorem for the cosine function.)

13 Define the normalized Chebyshev polynomials by $\widetilde{T}_n := 2^{1-n}T_n$ for $n \in \mathbb{N}^\times$ and $\widetilde{T}_0 := T_0$. For $n \in \mathbb{N}$, let $\mathcal{P}_n$ be the set of all polynomials $X^n + a_1X^{n-1} + \cdots + a_n$ with $a_1, \ldots, a_n \in \mathbb{R}$. Let $\|\cdot\|_\infty$ be the maximum norm on $[-1, 1]$. Prove the following:7

(a) In the set $\mathcal{P}_n$, the normalized Chebyshev polynomial of degree $n$ is the best approximation of zero on the interval $[-1, 1]$, that is, for each $n \in \mathbb{N}$,

$$
\| \tilde { T } _ { n } \| _ { \infty } \leq \| p \| _ { \infty } \ ,  p \in \mathcal { P } _ { n } \ .
$$

(b) For $-\infty < a < b < \infty$,

$$
\operatorname* { m a x } _ { a \leq x \leq b } | p ( x ) | \geq 2 ^{1 - 2 n} ( b - a ) ^{n} \ ,  p \in \mathcal { P } _ { n } \ .
$$

(c) Let $x_0,\ldots,x_n$ be the zeros of $T_{n+1}$. Suppose that $f\in C^{n+1}\left(\left[-1,1\right],\mathbb{R}\right)$ and $p_n$ is the interpolation polynomial of degree $\leq n$ such that $f(x_j)=p(x_j)$ for $j=0,1,\ldots,n$. Then

$$
\| r _ { n } [ f ; x _ { 0 } , \ldots , x _ { n } ] \| _ { \infty } \leq \frac { \| f ^{( n + 1 )} \| _ { \infty } } { 2 ^{n} ( n + 1 ) ! } \ .
$$

Show that this bound on the error is optimal.





# List of Problems from [1]

4.9 Example (calculating roots) For $a > 0$ and $n \geq 2$, we consider how $\sqrt[3]{a}$ can be determined using Newton's method. Setting $f(x) = x^n - a$ for all $x \geq 0$ we have the iteration

$$
x _ { k + 1 } = x _ { k } - \frac { x _ { k } ^{n} - a } { n x _ { k } ^{n - 1} } = \left( 1 - \frac { 1 } { n } \right) x _ { k } + \frac { a } { n x _ { k } ^{n - 1} } ~ ,  k \in \mathbb { N } ~ .
$$

Let $x_0 > \max\{1, a\}$. Since $f(x_0) = x_0^n - a > 0$ and $f$ is convex, by Remark 4.8(b), $(x_k)$ converges monotonically to $\sqrt[n]{a}$. In the special case $n=2$, (4.8) becomes

$$
x _ { k + 1 } = \frac { 1 } { 2 } \left( x _ { k } + \frac { a } { x _ { k } } \right) \, ,  k \in \mathbb { N } \, ,  x _ { 0 } = \operatorname* { m a x } \{ 1 , a \} \, ,
$$

which is the Bylonian algorithm of Exercise II.4.4. ■

# Exercises

1 Let $X$ be a complete metric space and, for $f: X \to X$, let $f^n$ denote the $n^{\text{th}}$ iterate of $f$, that is, $f^0 := \text{id}_X$ and $f^n := f \circ f^{n-1}$, $n \in \mathbb{N}^\times$. Suppose that, for each $n \in \mathbb{N}$, there is some $q_n \geq 0$ such that

$$
d \Big ( f ^{n} ( x ) , f ^{n} ( y ) \Big ) \leq q _ { n } d ( x , y ) ~ ,  x , y \in X ~ .
$$

Show that, if $(q_n)$ is a null sequence, then $f$ has a fixed point in $X$.

2 Let $X$ and $\Lambda$ be metric spaces with $X$ complete, and $f \in C(X \times \Lambda, X)$. Suppose that there is some $\alpha \in [0,1)$ and, for each $\lambda \in \Lambda$, some $q(\lambda) \in [0,\alpha]$ such that

$$
d \big ( f ( x , \lambda ) , f ( y , \lambda ) \big ) \leq q ( \lambda ) d ( x , y ) ~ ,  x , y \in X ~ .
$$

By the Banach fixed point theorem, for each $\lambda \in \Lambda$, $f(\cdot,\lambda)$ has a unique fixed point $x(\lambda)$ in $X$. Prove that $\left[\lambda \mapsto x(\lambda)\right] \in C(\Lambda,X)$.

3 Verify that the function $f : \mathbb{R} \to \mathbb{R}$, $x \mapsto e^{x - 1} - e^{1 - x}$ has a unique fixed point $x^*$. Calculate $x^*$ approximately.

4 Using Newton's method, approximate the real zeros of $X^{3}-2X-5$.

5 Determine numerically the least positive solutions of the following equation:

$$
x \tan x = 1 ~ , ~ ~ ~ x ^{3} + e ^{- x} = 2 ~ , ~ ~ ~ x - \cos ^{2} x = 0 ~ , ~ ~ ~ 2 \cos x = x ^{2} ~ .
$$

6 By Exercise 2.6, the function $f(x)=1+x+x^{2}/2!+\cdots+x^{n}/n!$, $x\in\mathbb{R}$, has a unique zero for odd $n\in\mathbb{N}^{\times}$. Determine these zeros approximately.

7 Suppose that $-\infty < a < b < \infty$ and $f : [a, b] \to \mathbb{R}$ is a differentiable convex function such that either

$$
f ( a ) < 0 < f ( b )  { \mathrm { o r } }  f ( a ) > 0 > f ( b ) ~ .
$$

Show that the recursively defined sequence

$$
x _ { n + 1 } : = x _ { n } - \frac { f ( x _ { n } ) } { f ^{t} ( x _ { 0 } ) } \, ,  n \in \mathbb { N } ^{\times} \, ,
$$

converges to the zero of $f$ in $[a,b]$ for any initial value $x_0$ such that $f(x_0) > 0$.² For which initial values does this method converge if $f$ is concave?





# List of Problems from [1]

8 Suppose that $-\infty < a < b < \infty$ and $f \in C([a,b],\mathbb{R})$ satisfies $f(a) < 0 < f(b)$. Set $a_0 := a$, $b_0 := b$ and recursively define

$$
c _ { n + 1 } : = a _ { n } - \frac { b _ { n } - a _ { n } } { f ( b _ { n } ) - f ( a _ { n } ) } f ( a _ { n } ) ~ ,  n \in \mathbb { N } ~ ,
$$

and

$$
a _ { n + 1 } : = \left\{ \begin{array}{ll} { c _ { n + 1 } ~ , } & { f ( c _ { n + 1 } ) \leq 0 ~ , } \\{ a _ { n } } & { \mathrm { o t h e r w i s e } ~ , } \end{array} \right.  b _ { n + 1 } : = \left\{ \begin{array}{ll} { b _ { n } ~ , } & { f ( c _ { n + 1 } ) \leq 0 ~ , } \\{ c _ { n + 1 } } & { \mathrm { o t h e r w i s e } ~ . } \end{array} \right.
$$

Show that $(c_n)$ converges to some zero of $f$. What is the graphical interpretation of this procedure (called the regula falsi or the method of false position)? How should the formulas be modified if $f(a) > 0 > f(b)$?

9 Determine approximately a zero of

$$
x ^{5} e ^{| x |} - \frac { 1 } { \pi } x ^{2} \sin  \left( \log ( x ^{2} ) \right) + 19 98 ~ .
$$

10 Let $I$ be a compact perfect interval and $f \in C^1(I, I)$ a contraction such that $f'(x) \neq 0$ for all $x \in I$. Let $x_0 \in I$ and denote by $x^* := \lim f^n(x_0)$ the unique fixed point of $f$ in $I$. Finally, suppose that $x_0 \neq x^*$. Prove the following:

(a) $f^{n}(x_{0})\neq x^{*}$ for each $n\in\mathbb{N}^{\times}$.

(b) $\lim _{n\to \infty}\frac{f^{n+1}(x_{0})-x^{*}}{f^{n}(x_{0})-x^{*}}=f^{\prime}(x^{*})$.





The submission problems now refer to the ones from the list above. To make the reference clear: for instance the notation I.8.6 refers to Exercise 6 in §I.8 which appears on page 16 of this document, the section appears on the left hand top corner (if the page number on the right hand corner is odd) of the copied page on the line just below the first line.

# Question 1:

Convergence, ..., Cauchy Completeness

(1) Exercise §II.1.12, page 3 of this document. [10]

(2) Exercise §II.3.12, page 7 of this document. [10]

(3) Exercise §II.6.6, page 14 of this document. [10]

Total for Question 1: 30

# 

question 2:

Series, power series, continuity, topology

(1) Exercise §II.7.11, page 16 of this document.

[10]

(2) Exercise §III.2.13, page 27 of this document. [10]

Total for Question 2: 20

# 

section 3:

Compactness, connectedness, real functions, exponential functions

(1) Exercise §III.3.11, page 30 of this document.

[10]

(2) Exercise §III.4.12, page 34 of this document. [10]

Total for Question 3: 20

Section 4:

Taylor's theorem, Iterative procedures, Sequences of functions Differentiation

(1) Exercise §IV.2.6, page 43 of this document. [10]

(2) Exercise §IV.2.20, page 45 of this document. [10]

(3) Exercise §IV.4.10, page 50 of this document. [10]

Total for Question 4: 30





MAT3711Real Analysis: IIAssignment 3Weightage 40%UAN: 187015

| Question: | 1 | 2 | 3 | 4 | Total |
| --- | --- | --- | --- | --- | --- |
| Marks: | 60 | 30 | 30 | 30 | 150 |
| Score: |  |  |  |  |  |

Name

Student Number

Signature with date

The submitted work is completely mine.

i. Each assignment produce copies of pages containing a variety of problems collected from several textbooks, each of which is suitably referred. You are expected to work through all the exercises.

ii. You shall have to submit the questions that are stated at the end of the assignment. In most cases you shall be asked to submit at least two and at most four problems (although, each problem could have several small parts).

iii. While it is encouraging to work in groups, make use of resources from anywhere on the internet, the final answer must be your own. Rememeber: in the final examination you shall be all alone and you shall not be asked to put forward any definition or prove anything standard available from the textbooks. On the other hand, the examination shall test your ability to deduce facts from a given set of assumptions.

iv. Download this heading page and make it the first page of your submission, after completing the details of your name, student number and signature.

v. You shall have to upload one .pdf file.

vi. Copy the problem that you are to submit and then provide your answer. The answer is to be uploaded to Course website





# List of Problems from [1]

Proof By Theorem II.9.2, any power series converges absolutely in the interior of its disk of convergence, and so, setting $X := r\mathbb{B}_{\mathbb{K}}$ and $f_k(x) := a_kx^k$ for all $x \in X$ and $k \in \mathbb{N}$, we have

$$
\sum \| f _ { k } \| _ { \infty } = \sum | a _ { k } | \, r ^{k} < \infty \ .
$$

The claim now follows from Theorem 1.6. ■

# Exercises

1 Which of the following sequences of functions $(f_n)$ converge uniformly on $X:=(0,1)$? (a) $f_n:=\sqrt[n]{x}$, (b) $f_n:=1/(1+nx)$, (c) $f_n:=x/(1+nx)$.

2 Show that $(f_n)$, defined by $f_n(x) := \sqrt{(1/n^2) + |x|^2}$, converges uniformly on $\mathbb{K}$ to the absolute value function $x \mapsto |x|$.

3 Prove or disprove that $\sum x^n/n^2$ and $\sum x^n$ converge uniformly on $\mathbb{B}_C$.

4 Prove or disprove that $\sum(-1)^n/nx$ converges pointwise (or uniformly, or absolutely) on $(0,1]$.

5 Let $X := \mathbb{E}_{\mathbb{K}}$, Investigate the norm convergence of the series $\sum f_n$ for the following cases: (a) $f_n := x^n$, (b) $f_n := |x|^2/(1 + |x|^2)^n$, (c) $f_n := x(1 - x^2)^n$, (d) $f_n := [x(1 - x^2)]^n$.

6 Verify that each of the series

(a) $\sum(1-\cos(x/n))$.

(b) $\sum n(x/n-\sin(x/n))$,

converges uniformly on any compact subinterval of $\mathbb{R}$.

(Hint: Approximate the terms of these series using Taylor polynomials of first and second degree.)

7 Let $(f_n)$ and $(g_n)$ be uniformly convergent $E$-valued sequences of functions on $X$ with limit functions $f$ and $g$ respectively. Show the following:

(a) $(f_n + g_n)$ converges uniformly to $f + g$.

(b) If $f$ or $g$ is in $B(X, \mathbb{K})$, then $(f_n g_n)$ converges uniformly to $fg$.

Show by example that, in (b), the boundedness of one of the limit functions is necessary.

8 Let $(f_n)$ be a uniformly convergent sequence of $\mathbb{K}$-valued functions on $X$ with limit function $f$. Suppose that there is some $\alpha > 0$ such that

$$
| f _ { n } ( x ) | \geq \alpha > 0 ~ ,  n \in \mathbb { N } ~ ,  x \in X ~ .
$$

Show that $(1/f_n)$ converges uniformly to $1/f$.

9 Let $(f_n)$ be a uniformly convergent sequence of $E$-valued functions on $X$, and $F$ a Banach space. Suppose that $f_n(X) \subseteq D$ for all $n \in \mathbb{N}$ and $g: D \to F$ is uniformly continuous. Show that $(g \circ f_n)$ is uniformly convergent.





# List of Problems from [1]

we get the inequality

$$
\begin{array}{rl} & { | f _ { n } ( x ) - f ( x ) | \leq | f _ { n } ( x ) - f ( x ) - \left( f _ { n } ( a ) - f ( a ) \right) | + | f _ { n } ( a ) - f ( a ) | } \\& {  \leq r \operatorname* { s u p } _ { 0 < t \leq 1 } | f _ { n } ^{\prime} \bigl ( a + t ( x - a ) \bigr ) - f ^{\prime} \bigl ( a + t ( x - a ) \bigr ) | + | f _ { n } ( a ) - f ( a ) | } \\& {  \leq r \, \| f _ { n } ^{\prime} - f ^{\prime} \| _ { \infty , B _ { r } } + | f _ { n } ( a ) - f ( a ) | } \end{array}
$$

for each $x \in B_r$. The right side of this inequality is independent of $x \in B_r$ and converges to 0 as $n \to \infty$ because of (ii) and the fact that $f' = g$. Thus $(f_n)$ converges uniformly to $f$ on $B_r$. ■

2.9 Corollary (differentiability of the limit of a series of functions) Suppose that $X \subseteq \mathbb{K}$ is open (or convex) and perfect, and $(f_n)$ is a sequence in $C^1(X,E)$ for which $\sum_{n=0}^{\infty} f_n$ converges pointwise and $\sum f'_n$ converges locally uniformly. Then the sum $\sum_{n=0}^{\infty} f_n$ is in $C^1(X,E)$ and

$$
\left( \sum _ { n = 0 } ^{\infty} f _ { n } \right) ^{\prime} = \sum _ { n = 0 } ^{\infty} f _ { n } ^{\prime} ~ .
$$

In addition, $\sum f_{n}$ converges locally uniformly.

Proof This follows directly from Theorem 2.8. ■

2.10 Remarks (a) Let $(f_n)$ be a sequence in $C^1(X, E)$ which converges uniformly to $f$. Even if $f$ is continuously differentiable, $(f'_n)$ does not, in general, converge pointwise to $f'$.

Proof Let $X := \mathbb{R}$, $E := \mathbb{R}$ and $f_n(x) := (1/n)\sin(nx)$ for all $n \in \mathbb{N}^\times$. Because

$$
| f _ { n } ( x ) | = | \sin ( n x ) | / n \leq 1 / n \ ,  x \in X \ ,
$$

$(f_{n})$ converges uniformly to 0. Since $\lim f_{n}^{\prime}(0)=1$, the sequence $(f_{n}^{\prime}(0))$ does not converge to the derivative of the limit function at the point 0. ■

(b) Let $(f_n)$ be a sequence in $C^1(X, E)$ such that $\sum f_n$ converges uniformly. Then, in general, $\sum f'_n$ does not converge even pointwise.

Proof Suppose that $X := \mathbb{R}$, $E := \mathbb{R}$, and $f_n(x) := (1/n^2)\sin nx)$ for all $n \in \mathbb{N}^\times$. Then $\|f_n\|_\infty = 1/n^2$ and so, by the Weierstrass majorant criterion, the series $\sum f_n$ converges uniformly. Since $f'_n(x) = (1/n)\cosDisposition$, $\sum f'_n(0)$ does not converge. ■

# Exercises

1 Prove the following:

(a) If $(f_n)$ converges uniformly and each $f_n$ is uniformly continuous, then the limit function is also uniformly continuous.

(b) $BUC(X,E):=(\{f\in BC(X,E)\;;\;f\text{ is uniformly continuous}\},\|\cdot\|_{\infty})$ is a Banach space.

(c) If $X$ is compact, then $BUC(X,E)=C(X,E)$.





# List of Problems from [1]

2 Consider a double sequence $(x_{jk})$ in $E$ such that

(i) $(x_{jk})_{k\in\mathbb{N}}$ converges for each $j\in\mathbb{N}$.

(ii) For each $\varepsilon>0$, there is some $N\in\mathbb{N}$ such that

$$
| x _ { m k } - x _ { n k } | < \varepsilon ~ ,  m , n \ge N ~ ,  k \in \mathbb { N } ~ .
$$

Show that $(x_{jk})_{j\in\mathbb{N}}$ converges for each $k\in\mathbb{N}$. Show that the sequences $(\lim_k x_{jk})_{j\in\mathbb{N}}$ and $(\lim_j x_{jk})_{k\in\mathbb{N}}$ converge and

$$
\operatorname* { l i m } _ { j \atop k } ( \operatorname* { l i m } _ { x _ { j k } } ) = \operatorname* { l i m } _ { k \atop j } ( \operatorname* { l i m } _ { x _ { j k } } ) ~ .
$$

3 Suppose that $X$ is compact and $(f_n)$ is a pointwise convergent sequence of real valued continuous functions on $X$. Prove that, if the limit function is continuous and $(f_n)$ is monotone, then $(f_n)$ converges uniformly (Dini's theorem).

(Hint: If $(f_n)$ is increasing, then

$$
0 \leq f ( y ) - f _ { N _ { x } } ( y ) = \left( f ( y ) - f ( x ) \right) + \left( f ( x ) - f _ { N _ { x } } ( x ) \right) + \left( f _ { N _ { x } } ( x ) - f _ { N _ { x } } ( y ) \right)
$$

for all $x,y\in X$ and $N_x\in\mathbb{N}$.)

4 Show by example that, in Dini's theorem, the continuity of the limit function and the monotone convergence are necessary hypotheses.

5 Let $(f_n)$ be a sequence of monotone functions on a compact interval $I$ which converges pointwise to a continuous function $f$. Show that $f$ is monotone and that $(f_n)$ converges uniformly to $f$.

6 Consider a sequence of real valued functions $(f_n)$ on $X$ satisfying the following conditions:

(i) For each $x \in X$, $(f_n(x))$ is decreasing.

(ii) $(f_n)$ converges uniformly to 0.

Show that $\sum(-1)^n f_n$ converges uniformly.

7 Let $(f_n)$ be a sequence of real valued functions on $X$, and $(g_n)$ a sequence of $\mathbb{K}$-valued functions on $X$ which satisfy the following conditions:

(i) For each $x \in X$, $\left(f_{n}(x)\right)$ is decreasing.

(ii) $\left(f_{n}\right)$ converges uniformly to 0.

(iii) $\sup _{n}\left\|\sum_{k=0}^{n} g_{k}\right\|_{\infty}<\infty$.

Show that $\sum g_{n}f_{n}$ converges uniformly.

(Hint: Setting $\alpha_k := \sum_{j=0}^{k} g_j$ we have

$$
\sum _ { k = m + 1 } ^{n} g _ { k } f _ { k } = \sum _ { k = m } ^{n - 1} \alpha _ { k } ( f _ { k } - f _ { k + 1 } ) + \alpha _ { n } f _ { n } - \alpha _ { m } f _ { m }
$$

for all $m < n$. For a given $\varepsilon > 0$ and $M := \sup_k \|\alpha_k\|_\infty$, there is some $N \in \mathbb{N}$ such that $\|f_n\|_\infty < \varepsilon/2M$ for all $n \geq N$. It follows that

$$
\left| \sum _ { k = m + 1 } ^{n} g _ { k } ( x ) f _ { k } ( x ) \right| \leq M \sum _ { k = m } ^{n - 1} ( f _ { k } - f _ { k + 1 } ) ( x ) + M ( f _ { n } + f _ { m } ) ( x ) < \varepsilon
$$

for all $x \in X$ and $n > m \geq N$. Now use Proposition 1.4.)





# List of Problems from [1]

8 With the help of the previous exercise, show that, for each $\alpha \in (0, \pi)$, the set $\sum_{k} e^{ikx}/k$ converges uniformly on $[\alpha, 2\pi - \alpha]$.

(Hint: We have

$$
| e ^{i \, x} - 1 | \geq \sqrt { 2 ( 1 - \cos \alpha ) } \ ,  x \in [ \alpha , 2 \pi - \alpha ] \ ,
$$

and so

$$
\left| \sum _ { k = 0 } ^{n} e ^{i \, k x} \right| = \frac { | e ^{i \, n x} - 1 | } { | e ^{i \, x} - 1 | } \leq \sqrt { 2 / ( 1 - \cos \alpha ) }
$$

for all $x \in [\alpha, 2\pi - \alpha].$)

9 Suppose that $A : E \to E$ is linear and $\alpha \geq 0$ satisfies $\|Ax\| \leq \alpha \|x\|$ for all $x \in E$. Fix $x_0 \in E$ and define

$$
u ( z ) : = \sum _ { k = 0 } ^{\infty} \frac { z ^{k} } { k ! } A ^{k} x _ { 0 } ~ ,  z \in \mathbb { K } ~ .
$$

Here $A^{k}$ denotes the $k^{\text{th}}$ iterate of $A$. Show that $u \in C^{\infty}(\mathbb{K}, E)$ and determine $\partial^{n}u$ for all $n \in \mathbb{N}^{\times}$.

(Hint: The series $\sum(z^{k}/k!)A^{k}x_{0}$ has $\|x_{0}\|e^{|z|}\alpha$ as a convergent majorant. We also have $\sum A(z^{k}/k!)A^{k}x_{0}=Au(z).)$

10 Let $X$ be open in $\mathbb{K}$, $n \in \mathbb{N}^{\times}$ and

$$
B C ^{n} ( X , E ) : = \bigl ( \{ \; f \in C ^{n} ( X , E ) \; ; \; \partial ^{j} f \in B ( X , E ) , \; j = 0 , \ldots , n \, \} \, , \; \| . \| _ { B C ^{n} } \bigr )
$$

with $\|f\|_{BC^n} := \max_{1 \leq j \leq n} \|j^i f\|_\infty$. Prove the following:

(a) $BC^{m}(X,E)$ is not a closed subspace of $BC(X,E)$.

(b) $BC^{m}(X,E)$ is a Banach space.

11 Let $-\infty < a < b < \infty$ and $f_n \in C^1([a,b],E)$ for all $n \in \mathbb{N}$. Suppose that the sequence $(f'_n)$ converges uniformly and there is some $x_0 \in [a,b]$ for which $\left(f_n(x_0)\right)_{n \in \mathbb{N}}$ converges. Prove that $(f_n)$ converges uniformly. (Hint: Use Theorem IV.2.18.)





# List of Problems from [1]

Now suppose that $D$ is open in $\mathbb{C}$. Set $D_{\mathbb{R}} := D \cap \mathbb{R} \neq \emptyset$. If $f \in C^{\omega}(D, \mathbb{C})$ and $f(D_{\mathbb{R}}) \subseteq \mathbb{R}$, then $f | D_{\mathbb{R}}$ is real analytic.

These considerations show that in our further investigation of analytic functions, we can limit ourselves to the complex case. ■

# Exercises

1 Let $D$ be open in $\mathbb{C}$ with $D_{\mathbb{R}} := D \cap \mathbb{R} \neq \emptyset$ and $f \in C^{\omega}(D, \mathbb{C})$. Show the following:

(a) $(\operatorname{Re} f)|D_{\mathbb{R}}$ and $(\operatorname{Im} f)|D_{\mathbb{R}}$ are real analytic.

(b) Let $f=\sum a_{k}(X-x_{0})^{k}$ be a power series expansion of $f$ at $x_{0}\in D_{\mathbb{R}}$ with radius of convergence $\rho>0$. Set $\widetilde{D}:=D_{\mathbb{R}}\cap(x_{0}-\rho,x_{0}+\rho)$. Then the following are equivalent:

(i) $f|\widetilde{D}\in C^{\omega}(\widetilde{D},\mathbb{R})$.

(ii) $a_{k}\in\mathbb{R}$ for each $k\in\mathbb{N}$.

2 Suppose that $f \in C^{\omega}(D, \mathbb{K})$ has no zeros. Show that $1/f$ is also analytic. (Hint: Use the division algorithm of Exercise II.9.9.)

3 Define $h: \mathbb{C} \rightarrow \mathbb{C}$ by

$$
h ( z ) : = \left\{ \begin{array}{ll} { ( e ^{z} - 1 ) / z \, , } & { z \in \mathbb { C } ^{\times} \, , } \\{ 1 \, , } & { z = 0 \, . } \end{array} \right.
$$

Show that $h \in C^{\omega}(\mathbb{C},\mathbb{C})$ and $h(z) \neq 0$ if $|z| < 1/(e-1)$

(Hint: For analyticity, consider the series $\sum X^{k}/(k+1)!$. From Remark II.8.2(c), we get the inequality

$$
| h ( z ) | = \left| { \frac { e ^{z} - 1 } { z } } \right| \geq 1 - \sum _ { k = 1 } ^{\infty} { \frac { | z | ^{k} } { ( k + 1 ) ! } }
$$

for all $z \in \mathbb{C}$.)

4 Let $h : \mathbb{C} \to \mathbb{C}$ be as in Exercise 3. By Exercises 2 and 3, the function $1/h$ is analytic on $\mathbb{E}\left(0,1/(e-1)\right)$, and so there are $\rho > 0$ and $B_k \in \mathbb{C}$ such that

$$
\frac { 1 } { h } = \sum _ { k = 0 } ^{\infty} B _ { k } \, z ^{k} \ ,  z \in \rho \mathbb { B } \ .
$$

Calculate $B_{0},\ldots,B_{10}$ and show that all $B_{k}$ are rational.

5 Suppose that $D$ is a domain in $\mathbb{C}$ and $f \in C^{\omega}(D, \mathbb{C})$ satisfies one of the following conditions:

(i) $\operatorname{Re} f=\operatorname{const.}$

(ii) $\operatorname{Im} f=\operatorname{const.}$

(iii) $\bar{f}\in C^{\omega}(D,\mathbb{C})$.

(iv) $|f|=\operatorname{const.}$

Show that $f$ is constant. (Hint: (i) Using a suitable difference quotient, show that $f'(z) \in i\mathbb{R} \cap \mathbb{R}$. (iii) $2\operatorname{Re} f = f + \bar{f}$ and (i). (iv) $|f|^2 = f\bar{f}$ and Exercise 2.)





# List of Problems from [1]

6 Let $f\in C^{\omega}(\rho\mathbb{B})$ be represented by $\sum a_{k}X^{k}$ on $\rho\mathbb{B}$ for some $\rho>0$. Suppose that $(x_{n})$ is a null sequence in $(\rho\mathbb{B})\backslash\{0\}$. Show that the following are equivalent:

(i) $f$ is even.

(ii) $f(x_n)=f(-x_n)$, $n\in\mathbb{N}$.

(iii) $a_{2m+1}=0$, $m\in\mathbb{N}$.

Formulate an analogous characterization of odd analytic functions on $\rho\mathcal{B}$

7 Prove the formulas (3.4).

8 Show that

$$
\left( \begin{array}{c} { { \alpha + \beta } } \\{ { k } } \end{array} \right) = \sum _ { \ell = 0 } ^{k} \left( \begin{array}{c} { { \alpha } } \\{ { \ell } } \end{array} \right) \left( \begin{array}{c} { { \beta } } \\{ { k - \ell } } \end{array} \right)
$$

for all $\alpha, \beta \in \mathbb{C}$ and $k \in \mathbb{N}$.

9 Verify that the functions

(a) $\sinh : \mathbb{C} \to \mathbb{C}$, $\cosh : \mathbb{C} \to \mathbb{C}$, $\tanh : \mathbb{C} \backslash i\pi(\mathbb{Z} + 1/2) \to \mathbb{C}$;

(b) $\tan : \mathbb{C} \backslash \pi(\mathbb{Z} + 1/2) \to \mathbb{C}$, $\cot : \mathbb{C} \backslash \pi\mathbb{Z} \to \mathbb{C}$; are analytic. (Hint: Use Proposition 3.8.)

10 Show that the functions

$$
\ln ( \cos ) ,  \ln ( \cosh ) ,  x \mapsto \ln ^{2} ( 1 + x )
$$

are analytic in a neighborhood of 0. What are the corresponding power series expansions at 0? (Hint: First find power series expansions for the derivatives.)

11 Prove that, for $x \in [-1, 1]$,

$$
\arctan x = \sum _ { k = 0 } ^{\infty} ( - 1 ) ^{k} { \frac { x ^{2 k + 1} } { 2 k + 1 } } = x - { \frac { x ^{3} } { 3 } } + { \frac { x ^{5} } { 5 } } - { \frac { x ^{7} } { 7 } } + \cdots \ ,
$$

and hence (Leibniz formula)

$$
\frac { \pi } { 4 } = \sum _ { k = 0 } ^{\infty} \frac { ( - 1 ) ^{k} } { 2 k + 1 } = 1 - \frac { 1 } { 3 } + \frac { 1 } { 5 } - \frac { 1 } { 7 } + - \cdots .
$$

(Hint: $\arctan' x = 1/(1 + x^2)$. For $x = \pm 1$, convergence follows from the Leibniz criterion (Theorem II.7.8).)





# List of Problems from [1]

In the case that $f \in C_{2\pi}(\mathbb{R},\mathbb{K})$ can be represented by a trigonometric series, how can the coefficients $a_k$ and $b_k$ be calculated? Are they uniquely determined by $f$? Can every $2\pi$-periodic continuous function be represented in this way?

For the first of these questions, the Weierstrass majorant criterion provides an easy sufficient condition. We will return to the second question in later chapters.

# Exercises

1 Verify that the Banach space $BC^{k}(X,\mathbb{K})$ of Exercise 2.10 is an algebra with unity and that multiplication is continuous. For which $k$ is $BC^{k}(X,\mathbb{K})$ a Banach algebra?

2 Let $x_0,\ldots,x_k\in\mathbb{K}^n$ be nonzero. Show that $\{x\in\mathbb{K}^n;\prod_{j=0}^{k}(x|x_j)\neq 0\}$ is open and dense in $\mathbb{K}^n$.

3 Let $M$ be a metric space. Prove or disprove the following:

(a) Finite intersections of dense subsets of $M$ are dense in $M$.

(b) Finite intersections of open dense subsets of $M$ are open and dense in $M$.

4 Let $D_k$, $k \in \mathbb{N}$, be open dense subsets of $\mathbb{K}^n$ and $D := \bigcap_k D_k$. Show the following:5

(a) $D$ is dense in $\mathbb{K}^n$.(b) $D$ is uncountable.

(Hint: (a) Set $F_k := \bigcap_{\ell=0}^k D_k$. Then $F_k$ is open and dense, and $F_0 \supseteq F_1 \supseteq \cdots$. Let $x \in \mathbb{K}^n$ and $r > 0$. Then there are $x_0 \in F_0$ and $r_0 > 0$ such that $\bar{\mathfrak{B}}(x_0, r_0) \subseteq \mathbb{B}(x, r) \cap F_0$. Choose inductively $x_k \in F_k$ and $r_k > 0$ such that $\bar{\mathfrak{B}}(x_{k+1}, r_{k+1}) \subseteq \mathbb{B}(x_k, r_k) \cap F_k$ for all $k \in \mathbb{N}$. Now use Exercise III.3.4. (b) If $D$ were countable, there would be $x_m \in \mathbb{K}^n$ such that $D = \{ x_m \; ; \; m \in \mathbb{N} \}$. Consider $\bigcap_m \{x_m\}^c \cap \bigcap_k D_{k'}$.)

5 Show that there is no function from $\mathbb{R}$ to $\mathbb{R}$ which is continuous at each rational point and discontinuous at each irrational point. (Hint: Let $f$ be a such function. Consider $D_k := \{x \in \mathbb{R}; \omega_f(x) < 1/k\}$ for all $k \in \mathbb{N}^{\times}$, where $\omega_f$ is the modulus of continuity from Exercise III.1.17. By Exercise III.2.20, $D_k$ is open. But then $\mathbb{Q} \subseteq D_k$ and $\bigcap_k D_k = \mathbb{Q}$, contradicting 4(b).)

6 Let $V$ be a finite dimensional normed vector space with basis $\{b_1, \ldots, b_n\}$, and $D$ a countable dense subset of $\mathbb{K}$. Show that $\{\sum_{k=1}^{n} \alpha_k b_k \; ; \; \alpha_k \in D\}$ is countable and dense in $V$.

7 Let $M \subseteq \mathbb{R}^n$ and $A := \mathbb{K}[X_1, \ldots, X_n] | M$. Show that $A$ separates the points of $M$ and is self adjoint.

8 Suppose that $-\infty < a < b < \infty$ and $f \in C([a,b],\mathbb{K})$. Show that $f$ has an antiderivative. (Hint: Let $(p_n)$ be a sequence of polynomials which converges uniformly to $f$. Find $F_h \in C^1([a,b],\mathbb{K})$ such that $F'_n = p_h$ and $F_h(a) = 0$. Now apply Exercise 2.11 and Theorem 2.8.)

9 Let $f \in C_{2\pi}(\mathbb{R},\mathbb{R})$ be differentiable. Show that $f'$ has a zero in $(0,2\pi)$.





# List of Problems from [1]

10 Let $D_0(\mathbb{R},\mathbb{K})$ be the set of all absolutely convergent trigonometric series with $a_0=0$ (see (4.11)). Show the following:

(a) $D_0(\mathbb{R},\mathbb{K})$ is a subalgebra of $C_{2\pi}(\mathbb{R},\mathbb{K})$.

(b) Each $f \in D_0(\mathbb{R},\mathbb{K})$ has a $2\pi$-periodic antiderivative.

(c) Each $f \in D_0(\mathbb{R},\mathbb{R})$ has a zero in $(0,2\pi)$.

(d) Claim (c) is false for functions in $D_0(\mathbb{R},\mathbb{C})$.

11 For $n \in \mathbb{N}$ and $0 \leq k \leq n$, the (elementary) Bernstein polynomial $B_{n,k}$ is defined by

$$
B _ { n , k } : = \binom { n } { k } X ^{k} ( 1 - X ) ^{n - k} ~ .
$$

Show the following:

(a) For each $n \in \mathbb{N}$, the Bernstein polynomials form a decomposition of unity, that is, $\sum_{k=0}^{n} B_{n,k} = \mathbf{1}$.

(b) $\sum_{k=0}^{n} kB_{n,k} = nX$, $\sum_{k=0}^{n} k(k-1)B_{n,k} = n(n-1)X^2$.

(c) $\sum_{k=0}^{n}(k-nX)^2 B_{n,k} = nX(1-X)$.

(Hint: For $y \in \mathbb{R}$, let $p_{n,y} := (X+y)^n$. Consider $X p'_{n,y}$ and $X^2 p''_{n,y}$ and set $y := 1 - X$.)

12 Let $E$ be a Banach space and $f \in C([0,1], E)$. Show that the sequence $(B_n(f))$ of Bernstein polynomials for $f$,

$$
B _ { n } ( f ) : = \sum _ { k = 0 } ^{n} f \Bigl ( \frac { k } { n } \Bigr ) B _ { n , k } \; ,  n \in \mathbb { N } \; ,
$$

converges in $C([0,1],E)$ (and hence uniformly on $[0,1]$) to $f$. (Hint: For suitable $\delta>0$ consider $|x-n/k|\leq\delta$ and $|x-n/k|>\delta$, and use Exercise 11.)

13 Let $X$ be a topological space. A family $\mathcal{B}$ of open sets of $X$ is called a basis for the topology of $X$ if, for each $x \in X$ and neighborhood $U$ of $x$, there is some $B \in \mathcal{B}$ such that $x \in B \subseteq U$. Prove the following:

(a) Any separable metric space has a countable basis of open sets.

(b) Any subset of a separable metric space is separable (that is, a separable metric space with the induced metric).

$\bigwedge\bigwedge\bigwedge$ $\bigwedge\bigwedge$ $m\leq n$.

(c) Any subset of $\mathbb{R}^n$ is separable.

14 Let $X$ be a compact separable metric space. Show that $C(X,\mathbb{K})$ is a separable Banach space. (Hint: Consider linear combinations with rational coefficients of 'monomials' $d_{B_1}^{m_1},\ldots,d_{B_k}^{m_k}$ with $k\in\mathbb{N}$, $m_j\in\mathbb{N}$, $B_j\in\mathcal{B}$, where $\mathcal{B}$ is a basis for the topology of $X$, and $d_B:=d(\cdot,B^c)$ as in Example III.1.3(l) for all $B\in\mathcal{B}$.)

Remark We will show in Proposition IX.1.8 that any compact metric space is separable.





# List of Problems from [1]

8

# 1.5 Corollary

(i) Every (piecewise) continuous function is the uniform limit of a sequence of staircase functions.

(ii) The uniform limit of a sequence of jump continuous functions is jump continuous.

(iii) Every monotone function is the uniform limit of a sequence of staircase functions.

Proof The statement (i) follows directly from Theorem 1.2; (ii) follows from Theorem 1.4, and statement (iii) follows from Remark 1.1(f). ■

# Exercises

1 Verify that, with respect to pointwise multiplication, $\mathcal{S}(I,\mathbb{K})$ is a Banach algebra with unity.

2 Define $f : [-1, 1] \to \mathbb{R}$ by

$$
f ( x ) : = \left\{ \begin{array}{ll} { \frac { 1 } { n + 2 } \, , } & { x \in [ - \frac { 1 } { n } , - \frac { 1 } { n + 1 } ) \cup \bigl ( \frac { 1 } { n + 1 } , \frac { 1 } { n } \bigr ] \, , } \\{ 0 \, , } & { x = 0 \, . } \end{array} \right.
$$

Prove or disprove that

(a) $f \in \mathcal{T}([[-1, 1], \mathbb{R})$;

(b) $f \in \mathcal{S}([[-1, 1], \mathbb{R})$.

3 Prove or disprove that $SC(I,E)$ is a closed vector subspace of $SC(I,E)$.

4 Show these statements are equivalent for $f: I \rightarrow E$:

(i) $f \in \mathcal{S}(I,E)$;

(ii) $\exists (f_n)$ in $\mathcal{T}(I,E)$ such that $\sum_n \|f_n\|_\infty < \infty$ and $f = \sum_{n=0}^\infty f_n$.

5 Prove that every jump continuous function has at most a countable number of discontinuities.

6 Denote by $f : [0,1] \to \mathbb{R}$ the Dirichlet function on $[0,1]$. Does $f$ belong to $\mathcal{S}([0,1],\mathbb{R})$?

7 Define $f : [0,1] \to \mathbb{R}$ by

$$
f ( x ) : = \left\{ \begin{array}{ll} { 1 / n \ , } & { x \in \mathbb { Q } \mathrm { ~ w i t h ~ } x \mathrm { ~ i n ~ l o w e s t ~ t e r m s ~ } m / n \ , } \\{ 0 \ , } & { \mathrm { o t h e r w i s e ~ . } } \end{array} \right.
$$

Prove or disprove that $f \in \mathcal{S}([0,1],\mathbb{R})$.

8 Define $f : [0,1] \to \mathbb{R}$ by

$$
f ( x ) : = \left\{ \begin{array}{ll} { \sin ( 1 / x ) \, , } & {  x \in ( 0 , 1 ] \; , } \\{ 0 \, , } & {  x = 0 \; . } \end{array} \right.
$$

Is $f$ jump continuous?





# List of Problems from [1]

VI.1 Jump continuous functions

9 Suppose $E_j$, $j=0,\ldots,n$ are normed vector spaces and

$$
f = ( f _ { 0 } , \ldots , f _ { n } ) : I \to E : = E _ { 0 } \times \cdots \times E _ { n } ~ .
$$

Show

$$
f \in { \mathcal S } ( I , E ) \iff f _ { j } \in { \mathcal S } ( I , E _ { j } ) \; ,  j = 0 , \ldots , n \; .
$$

10 Suppose $E$ and $F$ are normed vector spaces and that $f \in \mathcal{S}(I,E)$ and $\varphi: E \to F$ are uniformly continuous. Show that $\varphi \circ f \in \mathcal{S}(I,F)$.

11 Suppose $f,g\in\mathcal{S}(I,\mathbb{R})$ and $\operatorname{im}(g)\subset I$. Prove or disprove that $f\circ g\in\mathcal{S}(I,\mathbb{R})$.





# List of Problems from [1]

16

(iii) Finally we prove that $\overline{A}$ and $A$ have the same operator norm. From the continuity of the norm (see Example III.1.3(j)) and from Conclusions 2.4(a), it follows that

$$
\| \overline { { A } } e \| = \| \operatorname* { l i m } A x _ { n } \| = \operatorname* { l i m } \| A x _ { n } \| \leq \operatorname* { l i m } \| A \| \| x _ { n } \| = \| A \| \| \operatorname* { l i m } x _ { n } \| = \| A \| \| e \|
$$

for every $e \in E$ and every sequence $(x_n)$ in $X$ such that $x_n \to e$ in $E$. Consequently, $\|\overline{A}\| \leq \|A\|$. Because $\overline{A}$ extends $A$, Proposition 2.3 implies

$$
\| \overline { { A } } \| = \operatorname* { s u p } _ { \| y \| < 1 } \| \overline { { A } } y \| \geq \operatorname* { s u p } _ { \| x \| < 1 } \| \overline { { A } } x \| = \operatorname* { s u p } _ { x \in X } \| A x \| = \| A \| \ ,
$$

and we find $\|\overline{A}\|_{\mathcal{L}(E,F)}=\|A\|_{\mathcal{L}(X,F)}$. ■

# Exercises

In the following exercises, $E$, $E_j$, $F$, and $F_j$ are normed vector spaces.

1 Suppose $A \in \text{Hom}(E, F)$ is surjective. Show that

$$
A ^{- 1} \in \mathcal { L } ( F , E ) \iff \exists \alpha > 0 : \alpha \left\| x \right\| \leq \| A x \| \, ,  x \in E
$$

If $A$ also belongs to $\mathcal{L}(E,F)$, show that $\|A^{-1}\|\geq\|A\|^{-1}$.

2 Suppose $E$ and $F$ are finite-dimensional and $A \in \mathcal{L}(E,F)$ is bijective with a continuous inverse$^{6}$ $A^{-1} \in \mathcal{L}(F,E)$. Show that if $B \in \mathcal{L}(E,F)$ satisfies

$$
\| A - B \| _ { \mathcal { L } ( E , F ) } < \| A ^{- 1} \| _ { \mathcal { L } ( F , E ) } ^{- 1}
$$

then it is invertible.

3 $A \in \text{End}(\mathbb{K}^n)$ has in the standard basis the matrix elements $[a_{jk}]$. For $E_j := (\mathbb{K}^n, |.|_j)$ with $j = 1, 2, \infty$, verify for $A \in \mathcal{L}(E_j)$ that

(i) $\|A\|_{\mathcal{L}(E_1)}=\max_k\sum_j|a_{jk}|,$

(ii) $\|A\|_{\mathcal{L}(E_2)}\leq\left(\sum_{j,k}|a_{jk}|^2\right)^{1/2},$

iii) $\|A\|_{\mathcal{L}(E_\infty)}=\max_j\sum_k|a_{jk}|.$

4 Show that $\delta: B(\mathbb{R}^n) \to \mathbb{R}$, $f \mapsto f(0)$ belongs to $\mathcal{L}(B(\mathbb{R}^n), \mathbb{R})$, and find $\|\delta\|$.

5 Suppose $A_j \in \text{Hom}(E_j, F_j)$ for $j = 0,1$ and

$$
A _ { 0 } \otimes A _ { 1 } : E _ { 0 } \times E _ { 1 } \rightarrow F _ { 0 } \times F _ { 1 } ~ , ~ ~ ~ ( e _ { 0 } , e _ { 1 } ) \mapsto ( A _ { 0 } e _ { 0 } , A _ { 1 } e _ { 1 } ) ~ .
$$

Verify that

$$
A _ { 0 } \otimes A _ { 1 } \in \mathcal { L } ( E _ { 0 } \times E _ { 1 } , F _ { 0 } \times F _ { 1 } ) \; \; \Longleftrightarrow \; \; A _ { j } \in \mathcal { L } ( E _ { j } , F _ { j } ) \; \; ,  j = 0 , 1 \; .
$$

6 Suppose $(A_n)$ is a sequence in $\mathcal{L}(E,F)$ converging to $A$, and suppose $(x_n)$ is a sequence in $E$ whose limit is $x$. Prove that $(A_{n}x_n)$ in $F$ converges to $Ax$.

7 Show that $\ker(A)$ of $A \in \mathcal{L}(E,F)$ is a closed vector subspace of $E$.





# List of Problems from [1]

VI.3 The Cauchy-Riemann Integral

the Riemann sum. If $f$ is Riemann integrable, then

$$
\int _ { \alpha } ^{\beta} f \, d x = \operatorname* { l i m } _ { \triangle _ { 3 } \rightarrow 0 } \sum _ { j = 1 } ^{n} f ( \xi _ { j } ) ( \alpha _ { j } - \alpha _ { j - 1 } ) \ ,
$$

expresses its integral symbolically. ■

# Exercises

1 Define $[\cdot]$ to be the floor function. For $n \in \mathbb{N}^{\times}$, compute the integrals

$$
\mathrm { ( i ) } \, \int _ { 0 } ^{1} { \frac { [ n x ] } { n } } \, d x \ ,  \mathrm { ( i i ) } \, \int _ { 0 } ^{1} { \frac { [ n x ^{2} ] } { n ^{2} } } \, d x \ ,  \mathrm { ( i i i ) } \, \int _ { 0 } ^{1} { \frac { [ n x ^{2} ] } { n } } \, d x \ ,  \mathrm { ( i v ) } \, \int _ { \alpha } ^{\beta} \mathrm { s i g n } \, x \, d x \ .
$$

2 Compute $\int_{-1}^{1} f$ for the function $f$ of Exercise 1.2 and also $\int_{0}^{1} f$ for the $f$ of Exercise 1.7

3 Suppose $F$ is a Banach space and $A \in \mathcal{L}(E,F)$. Then show for $f \in \mathcal{S}(I,E)$ that

$$
A f : = ( x \mapsto A ( f ( x ) ) ) \in { \mathcal { S } } ( I , F )
$$

and $A\int_{\alpha}^{\beta}f=\int_{\alpha}^{\beta}Af$.

4 For $f \in \mathcal{S}(I,E)$, there is, according to Exercise 1.4, a sequence $(f_n)$ of jump continuous functions such that $\sum_n \|f_n\|_\infty < \infty$ and $f = \sum_n f_n$. Show that $\int_I f = \sum_n \int_I f_n$.

Prove that for every $f \in \mathcal{S}(I,\mathbb{R})$, $f^{+}$ and $f^{-}$ also belong to $\mathcal{S}(I,\mathbb{R})$, and

$$
\int _ { I } f \leq \int _ { I } f ^{+} ~ , ~ ~ - \int _ { I } f \leq \int _ { I } f ^{-} ~ .
$$

6 Show that if $f: I \to E$ is Riemann integrable, then $f \in B(I,E)$, that is, every Riemann integrable function is bounded.

7 Suppose $f \in B(I, \mathbb{R})$ and $\mathbf{3} = (\alpha_0, \ldots, \alpha_n)$ is a partition of $I$. Define

$$
\bar { S } ( f , I , 3 ) : = \sum _ { j = 1 } ^{n} \operatorname* { s u p } \{ \; f ( \xi ) \; ; \; \xi \in [ \alpha _ { j - 1 } , \alpha _ { j } ] \; \} ( \alpha _ { j } - \alpha _ { j - 1 } )
$$

and

$$
\mathcal { S } ( f , I , \Im ) : = \sum _ { j = 1 } ^{n} \operatorname* { i n f } \big \{ \, f ( \xi ) \; ; \; \xi \in [ \alpha _ { j - 1 } , \alpha _ { j } ] \, \big \} ( \alpha _ { j } - \alpha _ { j - 1 } )
$$

and call them the upper and lower sum of $f$ over $I$ with respect to the partition $\mathbf{3}$. Prove that

(i) if $3'$ is a refinement of $\mathbf{3}$, then

$$
\bar { S } ( f , I , \mathfrak { Z } ^{\prime} ) \leq \bar { S } ( f , I , \mathfrak { Z } ) ~ , ~ ~ \mathfrak { S } ( f , I , \mathfrak { Z } ) \leq \underline { { S } } ( f , I , \mathfrak { Z } ^{\prime} ) ~ ;
$$

(ii) if $\mathbf{3}$ and $\mathbf{3}^{\prime}$ are partitions of $I$, then

$$
\begin{array}{r} { \mathcal { S } ( f , I , 3 ) \leq \overline { { \mathcal { S } } } ( f , I , \mathfrak { Z } ^{\prime} ) ~ . } \end{array}
$$





# List of Problems from [1]

24

8 Suppose $f \in B(I, \mathbb{R})$ and $\mathfrak{Z}' := (\beta_0, \ldots, \beta_m)$ is a refinement of $\mathfrak{Z} := (\alpha_0, \ldots, \alpha_n)$. Show that

$$
\begin{array}{r} { \overline { { S } } ( f , I , 3 ) - \overline { { S } } ( f , I , \mathfrak { Z } ^{\prime} ) \leq 2 ( m - n ) \, \| f \| _ { \infty } \, \Delta _ { 3 } ~ , } \\{ \underline { { S } } ( f , I , \mathfrak { Z } ^{\prime} ) - \underline { { S } } ( f , I , \mathfrak { Z } ) \leq 2 ( m - n ) \, \| f \| _ { \infty } \, \Delta _ { 3 } ~ . } \end{array}
$$

9 Let $f \in B(I, \mathbb{R})$. From Exercise 7(ii), we know the following exist in $\mathbb{R}$:

$$
\int _ { I } f : = \operatorname* { i n f } \{ \, \bar { S } ( f , I , \mathbf { 3 } ) \; ; \; \mathbf { 3 } \mathrm { ~ i s ~ a ~ p a r t i t i o n ~ o f ~ } I \, \}
$$

and

$$
\int _ { I } f : = \operatorname* { s u p } \{ \, S ( f , I , 3 ) \; ; \; \mathbf { 3 } \mathrm { ~ i s ~ a ~ p a r t i t i o n ~ o f ~ } I \} \ .
$$

We call $\bar{f}_{r}f$ the over Riemann(-Darboux) integral of $f$ over $I$; likewise we call $\underline{f}_{r}f$ the under Riemann integral.

Prove that

(i) $\int_{I}f\leq\bar{J}_{I}f$;

(ii) for every $\varepsilon>0$ there is a $\delta>0$ such that for every partition $\mathcal{Z}$ of $I$ with $\Delta_{3}<\delta$, we have the inequalities

$$
0 \leq { \overline { { S } } } ( f , I , { \bf 3 } ) - \int _ { I } f < \varepsilon  { \mathrm { a n d } }  0 \leq \int _ { I } f - { \underline { { S } } } ( f , I , { \bf 3 } ) < \varepsilon \ .
$$

(Hint: There is a partition $\mathfrak{Z}'$ of $I$ such that $\overline{\mathcal{S}}(f,I,\mathfrak{Z}')<\bar{J}_If+\varepsilon/2$. Let $\mathfrak{Z}$ be an arbitrary partition of $I$. From Exercise 8, it follows that

$$
\begin{array}{r} { \overline { { S } } ( f , I , 3 ) \leq \overline { { S } } ( f , I , \mathbf { 3 } \vee \mathbf { 3 } ^{\prime} ) + 2 m \left\| f \right\| _ { \infty } \Delta _ { 3 } ~ . } \end{array}
$$

In addition, Exercise 7(i) gives $\overline{\mathcal{S}}(f,I,\mathfrak{Z}\vee\mathfrak{Z}')\leq\overline{\mathcal{S}}(f,I,\mathfrak{Z}')$.)

10 Show these statements are equivalent for $f \in B(I, \mathbb{R})$:

(i) $f$ is Riemann integrable.

(ii) $\overline{J}_{I}f=\int_{I}f$.

(iii) For every $\varepsilon>0$ there is a partition $\mathfrak{Z}$ of $I$ such that $\overline{S}(f,I,\mathfrak{Z})-\underline{S}(f,I,\mathfrak{Z})<\varepsilon$.

Show that $\overline{f}_{I}f=\underline{f}_{I}f=\int_{I}f$.

(Hint: "(ii)⇌(iii)" follows from Exercise 9."(i)⇒(iii)" Suppose $\varepsilon > 0$ and $e := \int_{I} f$. Then there is a $\delta > 0$ such that

$$
e - \frac { \varepsilon } { 2 } < \sum _ { j = 1 } ^{n} f ( \xi _ { j } ) ( \alpha _ { j } - \alpha _ { j - 1 } ) < e + \frac { \varepsilon } { 2 }
$$

for every partition $\mathfrak{I}=(\alpha_0,\ldots,\alpha_n)$ of $I$ with $\Delta_3<\delta$. Consequently, $\overline{\mathcal{S}}(f,I,\mathfrak{I})\leq e+\varepsilon/2$ and $\underline{\mathcal{S}}(f,I,\mathfrak{I})\geq e-\varepsilon/2$.)





# List of Problems from [1]

34

4.16 Proposition Suppose $f, \varphi \in C(I, \mathbb{R})$ and $\varphi \geq 0$. Then there is an $\xi \in I$ such that

$$
\int _ { \alpha } ^{\beta} f ( x ) \varphi ( x ) \, d x = f ( \xi ) \int _ { \alpha } ^{\beta} \varphi ( x ) \, d x \ .
$$

Proof If $\varphi(x)=0$ for all $x\in I$, then (4.9) obviously holds for every $\xi\in I$. Thus we can assume $\varphi(x)>0$ for some $x\in I$. Then Proposition 4.8 implies the inequality $\int_{\alpha}^{\beta}\varphi(x)\,dx>0$.

Letting $m := \min_I f$ and $M := \max_I f$, we have $m\varphi \leq f\varphi \leq M\varphi$ because $\varphi \geq 0$. Then the linearity and monotony of integrals implies the inequalities

$$
m \int _ { \alpha } ^{\beta} \varphi \, d x \leq \int _ { \alpha } ^{\beta} f \varphi \, d x \leq M \int _ { \alpha } ^{\beta} \varphi \, d x \ .
$$

Therefore we have

$$
m \leq { \frac { \int _ { \alpha } ^{\beta} f \varphi } { \int _ { \alpha } ^{\beta} \varphi } } \leq M ~ .
$$

The choice of $m$ and $M$ and the intermediate value theorem (Theorem III.5.1) immediately proves the theorem. ■

4.17 Corollary For $f \in C(I, \mathbb{R})$ there is a $\xi \in I$ such that $\int_{\alpha}^{\beta} f dx = f(\xi)(\beta - \alpha)$.

Proof Set $\varphi := \mathbf{1}$ in Proposition 4.16. ■

We note that —in contrast to the mean value theorem of derivatives (Theorem IV.2.4)—the point $\xi$ need not lie in the interior of the interval.

We illustrate Corollary 4.17 with the following figures:

<div style="display: block; width: 100%"><img src="https://storage.simpletex.cn/view/m1e1d2840d0979a4e9e32cb4062fdb816" style="width: 50%; max-width: 50%" /></div>

# Exercises

1 Prove the statement of Remark 4.7(b).





# List of Problems from [1]

VI.4 Properties of integrals

2 For $f \in \mathcal{S}(I)$, show $\overline{\int_{\alpha}^{\beta} f} = \int_{\alpha}^{\beta} \overline{J}$.

3 The two piecewise continuous functions $f_{1}, f_{2}: I \rightarrow E$ differ only at their discontinuities. Show that $\int_{\alpha}^{\beta} f_{1} = \int_{\alpha}^{\beta} f_{2}$.

4 For $f \in \mathcal{S}(I, \mathbb{K})$ and $p \in [1, \infty)$ suppose

$$
\| f \| _ { p } : = \left( \int _ { \alpha } ^{\beta} | f ( x ) | ^{p} \, d x \right) ^{1 / p} ,
$$

and let $p' := p/(p-1)$ denote $p$'s dual exponent (with $1/0 = \infty$).

Prove the following:

(i) For $f,g\in\mathcal{S}(I,\mathbb{K})$, the Hölder inequality holds, that is,

$$
\left| \int _ { \alpha } ^{\beta} f g \, d x \right| \leq \int _ { \alpha } ^{\beta} | f g | \, d x \leq \| f \| _ { p } \| g \| _ { p ^{\prime} } \ .
$$

(ii) For $f,g\in\mathcal{S}(I,\mathbb{K})$, the Minkowski inequality holds, that is,

$$
\| f + g \| _ { p } \leq \| f \| _ { p } + \| g \| _ { p } \; .
$$

(iii) $\left(C(I,\mathbb{K}),\|\cdot\|_p\right)$ is a normed vector space.

(iv) $\left(C(I,\mathbb{K}),\|\cdot\|_2\right)$ is an inner product space.

(v) For $f\in C(I,\mathbb{K})$ and $1\leq p\leq q\leq\infty$, we have

$$
\| f \| _ { p } \leq ( \beta - \alpha ) ^{1 / p - 1 / q} \| f \| _ { q } ~ .
$$

(Hint: (i) and (ii) Consult the proof of Applications IV.2.16(b) and (c). (v) Use (i).)

5 Show that if $q \geq p$, the norm $\|\cdot\|_q$ on $C(I,\mathbb{K})$ is stronger$^5$ than $\|\cdot\|_p$. These norms are not equivalent when $p \neq q$

6 Show that $(C(I,\mathbb{K}),\|\cdot\|_p)$ is not complete for $1\leq p<\infty$. Therefore $(C(I,\mathbb{K}),\|\cdot\|_p)$ is not a Banach space for $1\leq p<\infty$, and $(C(I,\mathbb{K}),\|\cdot\|_2)$ is not a Hilbert space.

7 Suppose $f \in C^{1}(I, \mathbb{R})$ has $f(\alpha) = f(\beta) = 0$. Show that

$$
\| f \| _ { \infty } ^{2} \leq \frac { 1 } { 2 } \int _ { \alpha } ^{\beta} \left( f ^{2} + ( f ^{\prime} ) ^{2} \right) d x ~ .
$$

How must (4.10) be modified when $f \in C^{1}(I, \mathbb{R})$ but only $f(\alpha)=0$?(Hint: Suppose $x_{0} \in I$ has $f^{2}(x_{0})=\|f\|_{\infty}^{2}$. Show that $f^{2}(x_{0})=\int_{\alpha}^{x_{0}} f f^{\prime} dx-\int_{x_{0}}^{\beta} f f^{\prime} dx$. Then apply Exercise 1.10.10.)

8 Suppose $f \in C^{1}(I, \mathbb{K})$ has $f(\alpha) = 0$. Show that

$$
\int _ { \alpha } ^{\beta} | f f ^{\prime} | \, d x \leq \frac { \beta - \alpha } { 2 } \int _ { \alpha } ^{\beta} | f ^{\prime} | ^{2} \, d x \; .
$$





# List of Problems from [1]

36

(Hint: If $F(x):=\int_{\alpha}^{x}|f'(z)|\,d\xi$ then $|f(x)|\leq F(x)$ and $\int_{\alpha}^{\beta}2FF'dx=F^{2}(\beta).)$

9 The function $f \in C^{2}(I, \mathbb{R})$ satisfies $f \leq f^{\prime\prime}$ and $f(\alpha) = f(\beta) = 0$. Show that

$$
0 \leq \operatorname* { m a x } _ { x \in I } f ^{\prime} ( x ) \leq \frac { 1 } { \sqrt { 2 } } \int _ { \alpha } ^{\beta} \left( f ^{2} + ( f ^{\prime} ) ^{2} \right) d x ~ .
$$

(Hint: Let $x_0 \in I$ such that $f'(x_0) = \|f'\|_\infty$. Then show $f'(x_0) \leq 0$, so that $f=0$.

If $f'(x_0) > 0$, there exists a $\xi \in (x_0, \beta)$ such that $f'(x) > 0$ for $x \in [x_0, \xi)$ and $f'(\xi) = 0$ (see Theorem IV.2.3). Then consider $\int_{x_0}^{\xi} (ff' - f'f'') dx$ and apply Exercise 7.)

10 Prove the second mean value theorem of integrals: Suppose $f \in C(I, \mathbb{R})$ and that $g \in C^1(I, \mathbb{R})$ is monotone.$^6$ Then there is a $\xi \in I$ such that

$$
\int _ { \alpha } ^{\beta} f ( x ) g ( x ) \, d x = g ( \alpha ) \int _ { \alpha } ^{\xi} f ( x ) \, d x + g ( \beta ) \int _ { \xi } ^{\beta} f ( x ) \, d x \ .
$$

(Hint: Letting $F(x):=\int_{\alpha}^{x}f(s)\,ds$, show that

$$
\int _ { \alpha } ^{\beta} f ( x ) g ( x ) \, d x = F g | _ { \alpha } ^{\beta} - \int _ { \alpha } ^{\beta} F ( x ) g ^{\prime} ( x ) \, d x \ .
$$

Proposition 4.16 can be used for the integral on the right side.)

11 Suppose $a > 0$ and $f \in C(\left[-a, a\right], E)$. Prove that

(i) if $f$ is odd, then $\int_{-a}^{a} f(x) \, dx = 0$;

(ii) if $f$ is even, then $\int_{-a}^{a} f(x) \, dx = 2 \int_{0}^{a} f(x) \, dx$.

12 Define $F:[0,1]\to\mathbb{R}$ through

$$
F ( x ) : = \left\{ \begin{array}{ll} { x ^{2} \sin ( 1 / x ^{2} ) \, , } & { x \in ( 0 , 1 ] \, , } \\{ 0 \, , } & { x = 0 \, . } \end{array} \right.
$$

Verify that

(i) $F$ is differentiable,

(ii) $F' \notin S(I, \mathbb{R})$.

That is, there are functions that are not jump continuous but nevertheless have an antiderivative. (Hint for (ii): Remark 1.1(d).)

13 Suppose $f \in C([a,b],\mathbb{R})$ and $g,h \in C^{1}([a,\beta],[a,b])$. Further suppose

$$
F : \left[ \alpha , \beta \right] \to \mathbb { R } \; ,  x \mapsto \int _ { g ( x ) } ^{h ( x )} f ( \xi ) \, d \xi \; .
$$

Show that $F \in C^{1}([ \alpha, \beta], \mathbb{R})$. How about $F'$?





# List of Problems from [1]

VI.4 Properties of integrals

14 Suppose $n \in \mathbb{N}^\times$ and $a_1, \ldots, a_n \in \mathbb{R}$. Prove that there is an $\alpha \in (0, \pi)$ such that

$$
\sum _ { k = 1 } ^{n} a _ { k } \cos ( k \alpha ) = 0 ~ .
$$

(Hint: Use Corollary 4.17 with $f(x):=\sum_{k=1}^{n}a_{k}\cos(kx)$ and $I:=[0,\pi].)$

15 Prove that

(i) $\lim _{n \rightarrow \infty} n\left(\frac{1}{n^{2}}+\frac{1}{(n+1)^{2}}+\cdots+\frac{1}{(2 n-1)^{2}}\right)=\frac{1}{2}$, (ii) $\lim _{n \rightarrow \infty} \sum_{k=n q}^{\frac{n p-1}{k}} \frac{1}{k}=\log \frac{p}{q}$ for $p, q \in \mathbb{N}$ and $q<p$.

(Hint: Consider the appropriate Riemann sum for $f(x):=1/(1+x)^2$ on $[0,1]$ or, for (ii), $f(x):=1/x$ on $[q,p].$)

16 Suppose $f \in C(I \times I, E)$ and

$$
g : \, I \rightarrow E \ ,  x \mapsto \int _ { I } f ( x , y ) \, d y \ .
$$

Show that $g \in C(I, E)$.





# List of Problems from [1]

48

The exercises give concrete examples of integrating by using partial fraction expansions.

# Exercises

1 Calculate the indefinite integrals

(i) $\int \frac{dx}{a^{2}x^{2}+bx+c}$ , (ii) $\int \frac{x\,dx}{x^{2}-2x+3}$ , (iii) $\int \frac{x^{5}\,dx}{x^{2}+x+1}$ , (iv) $\int \frac{dx}{x^{4}+1}$ , (v) $\int \frac{x^{2}\,dx}{x^{4}+1}$ , (vi) $\int \frac{dx}{(ax^{2}+bx+c)^{2}}$.

2 By clever substitution, transform the following integrals

$$
\mathrm { ( i ) } \, \int \frac { e ^{x} - 1 } { e ^{x} + 1 } \, d x \ ,  \mathrm { ( i i ) } \, \int \frac { d x } { 1 + \sqrt [ 3 ] { 1 + x } } \ ,  \mathrm { ( i i i ) } \, \int \frac { d x } { \sqrt [ 3 ] { x } ( 1 + \sqrt [ 3 ] { x } ) }
$$

into integrals of rational functions. What are the corresponding antiderivatives?

3 Suppose $f \in C^{1}(I, \mathbb{R})$. Show$^{7}$ $\lim _{\lambda \rightarrow \infty} \int_{I} f(x) \sin (\lambda x) dx=0$.

4 Suppose $f \in C([0,1],\mathbb{R})$. Verify that

(i) $\int_{0}^{\pi} x f(\sin x) dx = \frac{\pi}{2} \int_{0}^{\pi} f(\sin x) dx,$

(ii) $\int_{0}^{\pi/2} f(\sin 2x) \cos x dx = \int_{0}^{\pi/2} f(\cos^{2}x) \cos x dx.$

(Hints: (i) Substitute $t=\pi-x$.

(ii) Observe $\int_{\pi/4}^{\pi/2} f(\sin 2x)\cos x\,dx = \int_{0}^{\pi/4} f(\sin 2x)\sin x\,dx$, and then use the substitution $\sin 2x = \cos^{2}t$.)

5 The Legendre polynomials $P_{n}$ are defined by$^{8}$

$$
P _ { n } ( X ) : = \frac { 1 } { 2 ^{n} n ! } \, \partial ^{n} \big [ ( X ^{2} - 1 ) ^{n} \big ]  \mathrm { f o r } ~ n \in \mathbb { N } \ ,
$$

Prove

$$
\int _ { - 1 } ^{1} P _ { n } P _ { m } = \left\{ \begin{array}{ll} { 0 \, , } & { n \neq m \, , } \\{ \frac { 2 } { 2 n + 1 } \, , } & { n = m \, . } \end{array} \right.
$$

6 By using the substitution $y=\tan x$, prove that

$$
\int _ { 0 } ^{1} \frac { \log ( 1 + x ) } { 1 + x ^{2} } \, d x = \frac { \pi } { 8 } \log 2 \ .
$$

(Hint: $1 + \tan x = (\sqrt{2}\sin(x + \pi/4))/\cos x.$)





# List of Problems from [1]

VI.5 The technique of integration

7 Show

$$
\int _ { 0 } ^{1 / \sqrt { 2} } \frac { 4 \sqrt { 2 } - 8 x ^{3} - 4 \sqrt { 2 } x ^{4} - 8 x ^{5} } { 1 - x ^{8} } d x = \pi ~ .
$$

(Hints: Substitute $x = y/\sqrt{2}$ and $(y - 1)(y^8 - 16) = (y^2 - 2)(y^2 - 2y + 2)(y^5 + y^4 + 2y^3 - 4.)$)

8 Suppose $k,m\in\mathbb{N}^\times$ and $c\in(0,1)$. Show that

$$
\int _ { 0 } ^{c} \frac { x ^{k - 1} } { 1 - x ^{m} } = \sum _ { n = 0 } ^{\infty} \frac { e ^{n m + k} } { n m + k } \, .
$$

(Hint: $\sum_{n=0}^{\infty} x^{nm} = 1/(1 - x^{m})$.)

9 In Exercise 8, put $c=1/\sqrt{2}$, $m=8$, and $k=1,4,5,6$. Construct using Exercise 7 the following form of $\pi$:

$$
\pi = \sum _ { n = 0 } ^{\infty} { \frac { 1 } { 16 ^{n} } } \Big ( { \frac { 4 } { 8 n + 1 } } - { \frac { 2 } { 8 n + 4 } } - { \frac { 1 } { 8 n + 5 } } - { \frac { 1 } { 8 n + 6 } } \Big ) .
$$

10 Supply recursion formulas for the integrals

$$
\begin{array}{rl} & { ( \mathrm { i ) ~ } I _ { n } = \int x ^{n} e ^{x} \, d x \ ,  ( \mathrm { i i ) ~ } I _ { n } = \int x ( \log x ) ^{n} \, d x \ , } \\& { ( \mathrm { i i i ) ~ } I _ { n } = \int \cos ^{n} x \, d x \ ,  ( \mathrm { i v ) ~ } I _ { n } = \int \frac { d x } { ( x ^{2} + 1 ) ^{n} } \ . } \end{array}
$$





# List of Problems from [1]

VI.6 Sums and integrals

We set $u:=g'_k$ and $v':=B_1(X)$, and thus $u'=g''_k$ and $v=-X(1-X)/2$, as well as $v(0)=v(1)=0$. Integrating by parts, we therefore get

$$
- \int _ { 0 } ^{1} B _ { 1 } ( t ) g _ { k } ^{\prime} ( t ) \, d t = \int _ { 0 } ^{1} v ( t ) g _ { k } ^{\prime \prime} ( t ) \, d t \ .
$$

Defining

$$
R ( f , h ) : = h \sum _ { k = 0 } ^{n - 1} \int _ { 0 } ^{1} v ( t ) g _ { k } ^{\prime \prime} ( t ) \, d t \ ,
$$

we arrive at the representation

$$
\int _ { \alpha } ^{\beta} f ( x ) \, d x = h \Big [ \frac { 1 } { 2 } f ( \alpha ) + \sum _ { k = 1 } ^{n - 1} f ( \alpha + k h ) + \frac { 1 } { 2 } f ( \beta ) \Big ] + R ( f , h ) \ .
$$

To estimate the remainder $R(f,h)$, we note first that

$$
\left| \int _ { 0 } ^{1} v ( t ) g _ { k } ^{\prime \prime} ( t ) \, d t \right| \leq \| g _ { k } ^{\prime \prime} \| _ { \infty } \int _ { 0 } ^{1} \frac { t ( 1 - t ) } { 2 } \, d t = \frac { 1 } { 12 } \| g _ { k } ^{\prime \prime} \| _ { \infty } \ .
$$

The chain rule implies

$$
\| g _ { k } ^{\prime \prime} \| _ { \infty } = \operatorname* { m a x } _ { t \in [ 0 , 1 ] } | g _ { k } ^{\prime \prime} ( t ) | = h ^{2} \operatorname* { m a x } _ { \alpha + k h \leq x \leq \alpha + ( k + 1 ) h } | f ^{\prime \prime} ( x ) | \leq h ^{2} \| f ^{\prime \prime} \| _ { \infty } ~ .
$$

Consequently,

$$
| R ( f , h ) | \leq h \sum _ { k = 0 } ^{n - 1} \Bigl | \int _ { 0 } ^{1} v ( t ) g _ { k } ^{\prime \prime} ( t ) \, d t \Bigr | \leq \frac { h ^{3} } { 12 } \| f ^{\prime \prime} \| _ { \infty } \sum _ { k = 0 } ^{n - 1} 1 = \frac { \beta - \alpha } { 12 } h ^{2} \| f ^{\prime \prime} \| _ { \infty } \ ,
$$

which shows the dependence on $h$. ■

The trapezoid rule constitutes the simplest "quadrature formula" for numerically approximating integrals. For further exploration and more efficient methods, see lectures and books about numerical methods (see also Exercise 8).

# Exercises

1 Prove the statements (iv) and (v) in Proposition 6.6.

2 Compute $B_8$, $B_{10}$, and $B_{12}$, as well as $B_1(X)$, $B_5(X)$, $B_6(X)$ and $B_7(X)$.

3 Show that for $n \in \mathbb{N}^\times$

(i) $B_{2n+1}(X)$ has in $[0,1]$ only the zeros $0$, $1/2$, and $1$;

(ii) $B_{2n}(X)$ has in $[0,1]$ only two zeros $x_{2m}$ and $x'_{2m}$, with $x_{2m} + x'_{2m} = 1$.

4 Denote by $\bar{B}_{n}$ the 1-periodic continuation of $B_{n}(X)|[0,1)$ onto $\mathbb{R}$. Then show these:





# List of Problems from [1]

66

(i) $\widetilde{B}_{n} \in C^{n-2}(\mathbb{R})$ for $n \geq 2$.

(ii) $\int_{k}^{k+1} \widetilde{B}_{n}(x) dx = 0$ for $k \in \mathbb{Z}$ and $n \in \mathbb{N}$.

(iii) For every $n \in \mathbb{N}$ map

$$
F _ { n } : \left\{ z \in \mathbb { C } \ ; \ \operatorname { R e } z > - 2 n \right\} \to \mathbb { C } \ ,  s \mapsto \int _ { 1 } ^{\infty} \tilde { B } _ { 2 n + 1 } ( x ) x ^{- ( s + 2 n + 1 )} d x
$$

is analytic.

5 Prove Remark 6.11(a).

6 Show for the $\zeta$ function that $\lim_{n\to\infty}\zeta(n)=1$.

7 Suppose $h > 0$ and $f \in C^4([-h, h], \mathbb{R})$. Show

$$
\left| \int _ { - h } ^{h} f ( x ) \, d x - \frac { h } { 3 } \bigl ( f ( - h ) + 4 f ( 0 ) + f ( h ) \bigr ) \right| \leq \frac { h ^{5} } { 90 } \| f ^{( 4 )} \| _ { \infty } \ .
$$

(Hints: Integrate by parts and use the mean value theorem for integrals.)

8 Suppose $f \in C^4([ \alpha, \beta], \mathbb{R})$ and let $\alpha_j := \alpha + jh$ for $0 \leq j \leq 2n$ with $h := (\beta - \alpha)/2n$ and $n \in \mathbb{N}^\times$. Further let$^9$

$$
S \big ( f , [ \alpha , \beta ] , h \big ) : = { \frac { h } { 3 } } \Big ( f ( \alpha ) + f ( \beta ) + 2 \sum _ { j = 1 } ^{n - 1} f ( \alpha _ { 2 j } ) + 4 \sum _ { j = 1 } ^{n} f ( \alpha _ { 2 j - 1 } ) \Big ) ~ .
$$

This is Simpson's rule, another rule for approximating integrals. Show it satisfies the error estimate

$$
\left| \int _ { \alpha } ^{\beta} f ( x ) \, d x - S \bigl ( f , [ \alpha , \beta ] , h \bigr ) \right| \leq ( \beta - \alpha ) \frac { h ^{4} } { 18 0 } \| f ^{( 4 )} \| _ { \infty } \; .
$$

(Hint: Exercise 7.)

9 Calculate the error in

$$
\int _ { 0 } ^{1} \frac { d x } { 1 + x ^{2} } = \frac { \pi } { 4 }  \mathrm { a n d }  \int _ { 1 } ^{2} \frac { d x } { x } = \log 2
$$

when using the trapezoid rule for $n=2,3,4$ and Simpson's rule for $n=1,2$.

10 Show that Simpson's rule with a single inner grid point gives the correct value of $\int_{\alpha}^{\beta} p$ for any polynomial $p \in \mathbb{R}[X]$ of degree at most three.





# List of Problems from [1]

VI.7 Fourier series

From $(7.17)$ we can read off

$$
( \log f ) ^{\prime} ( x ) = \sum _ { n = 1 } ^{\infty} \frac { 2 x } { x ^{2} - n ^{2} }  \mathrm { f o r ~ } x \in J \backslash \{ 0 \} \ ,
$$

where the right hand series converges normally for every $r \in (0,1)$ in $[-r,r]$. In particular, it follows that (7.23) is valid for all $x \in J$.

From formulas (7.21) and (7.22), we learn the relation

$$
\log g ( x ) = \sum _ { n = 1 } ^{\infty} \log \left( 1 - \frac { x ^{2} } { n ^{2} } \right)  \mathrm { f o r } \; x \in J \; .
$$

Now it follows from Corollary V.2.9 (the differentiability of the limit of a series of functions) that $\log g$ is differentiable on $J$ and that

$$
( \log g ) ^{\prime} ( x ) = \sum _ { n = 1 } ^{\infty} { \frac { 2 x } { x ^{2} - n ^{2} } }  { \mathrm { f o r ~ } } x \in J \ .
$$

Consequently, $(\log f)' = (\log g)'$ on $J$. Finally, because $\log f(0) = 0 = \log g(0)$ and from the uniqueness theorem for antiderivatives (Remark V.3.7(a)), we get $\log f = \log g$ on the entire $J$. ■

We have studied criteria governing whether Fourier series converge uniformly or in the quadratic mean. It is also natural to inquire about their pointwise convergence. On that subject, there are a multitude of results and simple, sufficient criteria coming from classical analysis. Some of the simplest of these criteria are presented in common textbooks (see for example [BF87], [Bla91], [Köln92], [Wal92]). For example, it is easy to verify that the Fourier series of Example 7.10(a) converges to the given "square wave" function.

We will not elaborate here, having confined our attention to the essential results of classical Fourier series in one variable. Of perhaps greater significance is the $L_2$ theory of Fourier series, which, as we have attempted to show above, is very general. It finds uses in many problems in mathematics and physics—for example, in the theory of differential equations in one and more variables—and plays an extremely important role in modern analysis and its applications. You will likely meet the Hilbert space theory of orthogonality in further studies of analysis and its applications, and we also will give an occasional further look at this theory.

# Exercises

1 Suppose $f \in SC_{2\pi}$ has $\int_0^{2\pi} f = 0$. Show that there is a $\xi \in [0, 2\pi]$ such that $f(\xi) = 0$.

2 Verify that for $f \in C_{2\pi}$ defined by $f(t) := |\sin(t)|$ on $t \in [0, 2\pi]$, we have

$$
S f = \frac { 2 } { \pi } - \frac { 4 } { \pi } \sum _ { k = 1 } ^{\infty} \frac { \cos ( k \cdot ) } { 4 k ^{2} - 1 } \, .
$$





# List of Problems from [1]

88

3 For $n \in \mathbb{N}$,

$$
D _ { n } : = \sqrt { 2 \pi } \sum _ { k = - n } ^{n} \mathbf { e } _ { k } = 1 + 2 \cos + 2 \cos ( 2 \cdot ) + \cdots + 2 \cos ( n \cdot )
$$

is called the Dirichlet kernel of degree $n$. Show that

$$
D _ { n } ( t ) = \frac { \sin \bigl ( ( n + 1 / 2 ) t \bigr ) } { \sin ( t / 2 ) } \mathrm { ~ f o r ~ } t \in \mathbb { R }  \mathrm { a n d }  \int _ { 0 } ^{2 \pi} D _ { n } ( t ) \, d t = 1 \mathrm { ~ f o r ~ } n \in \mathbb { N } \ .
$$

4 Define $f \in SC_{2\pi}$ by

$$
f ( t ) : = \left\{ \begin{array}{ll} { \displaystyle \frac { \pi - t } { 2 } \, , } & { 0 < t < 2 \pi \, , } \\{ 0 \, , } & { t = 0 \, . } \end{array} \right.
$$

Prove that

$$
S f = \sum _ { k = 1 } ^{\infty} { \frac { \sin ( k \cdot ) } { k } } ~ .
$$

(Hints: $I_{n}(t):=\int_{\pi}^{t}D_{n}(s)\,ds=(t-\pi)+2\bigl(\sin t+\cdots+\sin(nt)/n\bigr)$ for $t\in(0,2\pi)$. Exercise 3 and integration by parts result in $|I_{n}(t)|\leq2\bigl[(n+1/2)\sin(t/2)\bigr]^{-1}$ for $t\in(0,2\pi).$)

5 Show that the 1-periodic extension of $\widetilde{B}_n$ from $B_n(X) \mid [0,1)$ to $\mathbb{R}$ has the following Fourier expansion:

$$
\bar { B } _ { 2 n } = 2 \frac { ( - 1 ) ^{n - 1} ( 2 n ) ! } { ( 2 \pi ) ^{2 n} } \sum _ { k = 1 } ^{\infty} \frac { \cos ( 2 \pi k \cdot ) } { k ^{2 n} }  \mathrm { f o r ~ } n \in \mathbb { N } ^{\times} \ ,
$$

$$
\widetilde { B } _ { 2 n + 1 } = 2 \frac { ( - 1 ) ^{n - 1} ( 2 n + 1 ) ! } { ( 2 \pi ) ^{2 n + 1} } \sum _ { k = 1 } ^{\infty} \frac { \sin ( 2 \pi k \cdot ) } { k ^{2 n + 1} }  \mathrm { f o r ~ } n \in \mathbb { N } \ .
$$

(Hints: It suffices to prove (7.24) and (7.25) on [0, 1]. For the restrictions $U_{2n}$ and $U_{2n+1}$ of the series in (7.24) and (7.25), respectively, to [0, 1], show that $U'_{m+1} = (m + 1)U_m$ for $m \in \mathbb{N}^\times$. From Exercise 4, it follows that $U_1(t) = B_1(t)$. Thus Proposition 6.6(iii) shows that for $m \geq 2$, there is a constant $c_m$ such that $U_m(t) = B_m(t) + c_m$ for $t \in [0, 1]$. Finally verify $\int_0^1 U_m(t) dt = 0$ (Proposition 4.1(ii)) and $\int_0^1 B_m(t) dt = 0$ (Exercise 6.4(iii)). Then it follows that $c_m = 0$ for $m \geq 2$.)

6 Verify the asymptotic equivalences

$$
| B _ { 2 n } | \sim 2 ^{\frac { ( 2 n ) !} { ( 2 \pi ) ^{2 n} } } \sim 4 \sqrt { \pi n } \bigg ( \frac { n } { \pi e } \bigg ) ^{2 n} .
$$

(Hints: Exercise 5 shows

$$
B _ { 2 n } = \bar { B } _ { 2 n } ( 0 ) = ( - 1 ) ^{n - 1} 2 \frac { ( 2 n ) ! } { ( 2 \pi ) ^{2 n} } \sum _ { k = 1 } ^{\infty} \frac { 1 } { k ^{2 n} } ~ .
$$

Further note Exercise 6.6, Application 7.23(a) and Exercise 6.3(a).)





# List of Problems from [1]

VI.7 Fourier series

7 Prove Wirtinger's inequality: For any $-\infty < a < b < \infty$ and $f \in C^1([a,b])$ such that $f(a) = f(b) = 0$, we have

$$
\int _ { a } ^{b} | f | ^{2} \leq [ ( b - a ) ^{2} / \pi ^{2} ] \int _ { a } ^{b} | f ^{\prime} | ^{2} \ .
$$

The constant $(b-a)^2/\pi^2$ cannot be made smaller.

(Hint: Using the substitution $x \mapsto \pi(x-a)/(b-a)$, it suffices to consider $a=0$ and $b=\pi$. For $g:[-\pi,\pi]\to\mathbb{K}$ such that $g(x):=f(x)$ for $x\in[0,\pi]$ and $g(x):=-f(-x)$ for $x\in[-\pi,0]$, show that $g\in C^1\left(\left[-\pi,\pi\right]\right)$ and that $g$ is odd. Thus it follows from Parseval's theorem and Remark 7.20(b) that

$$
\frac { 1 } { 2 \pi } \int _ { - \pi } ^{\pi} | g ^{\prime} | ^{2} = \sum _ { k \in \mathbb { Z } } | \hat { g } _ { k } ^{\prime} | ^{2} \geq \sum _ { k \neq 0 } | \hat { g } _ { k } ^{\prime} | ^{2} = \sum _ { k \neq 0 } | i \, k \hat { g } _ { k } | ^{2} \geq \sum _ { k \neq 0 } | \hat { g } _ { k } | ^{2} = \frac { 1 } { 2 \pi } \int _ { - \pi } ^{\pi} | g | ^{2}
$$

because $\widehat{g}(0)=0$. The claim then follows from the construction of $g$;

8 For $f,g\in SC_{2\pi}$,

$$
f * g : \mathbb { R } \to \mathbb { K } \ ,  x \mapsto { \frac { 1 } { 2 \pi } } \int _ { 0 } ^{2 \pi} f ( x - y ) g ( y ) \, d y
$$

is called the convolution of $f$ with $g$. Show that

(i) $f * g = g * f$;

(ii) if $f, g \in C_{2\pi}$, then $f * g \in C_{2\pi}$;

(iii) $\mathbf{e}_n * \mathbf{e}_m = \delta_{nm} \mathbf{e}_n$ for $m, n \in \mathbb{Z}$.

9 Denote by $D_n$ the $n$-th Dirichlet kernel. Show that if $f \in SC_{2\pi}$, then $S_n f = D_n * f$.

10 Verify the statements of Remark 7.17(c):

(i) $\ell_{2}(\mathbb{Z})$ is a Hilbert space;

(ii) $SC_{2\pi} \rightarrow \ell_{2}(\mathbb{Z}), \ f \mapsto (\sqrt{2\pi}\widehat{f}_{k})_{k\in\mathbb{Z}}$ is a linear isometry.

11 Prove the generalized Parseval's theorem

$$
\frac { 1 } { 2 \pi } \int _ { 0 } ^{2 \pi} f \bar { g } \, d t = \sum _ { k = - \infty } ^{\infty} \hat { f } _ { k } \overline { { { g } } } _ { k }  \mathrm { f o r ~ } f , g \in S C _ { 2 \pi } \ .
$$

(Hint: Note that

$$
z \overline { { w } } = \frac { 1 } { 4 } \left( | z + w | ^{2} - | z - w | ^{2} + i ~ | z + i w | ^{2} - i ~ | z - i w | ^{2} \right)  \mathrm { f o r } ~ z , w \in \mathbb { C } ~ ,
$$

and apply Corollary 7.16.)





# List of Problems from [1]

VI.8 Improper integrals

# Exercises

1 Prove the convergence of these improper integrals:

$$
\mathrm { ( i ) } \, \int _ { 1 } ^{\infty} \frac { \sin x } { x ^{2} } \, d x \ ,  \mathrm { ( i i ) } \, \int _ { 0 } ^{\infty} \frac { \sin x } { x } \, d x \ ,  \mathrm { ( i i i ) } \, \int _ { 1 } ^{\infty} \frac { \sin ( 1 / x ) } { x } \, d x \ .
$$

In which cases do the integrals converge absolutely?

2 Which of these improper integrals have a value?

$$
\mathrm { ( i ) } \, \int _ { 0 } ^{1} { \frac { \arcsin x } { \sqrt { 1 - x ^{2} } } } \, d x \ ,  \mathrm { ( i i ) } \, \int _ { 1 } ^{\infty} { \frac { \log x } { x ^{2} } } \, d x \ ,  \mathrm { ( i i i ) } \, \int _ { 0 } ^{\infty} { \frac { \log x } { 1 + x ^{2} } } \, d x \ ,  \mathrm { ( i v ) } \, \int _ { 0 } ^{\infty} x ^{n} e ^{- x} \, d x \ .
$$

(Hint for (iii): Consider $f_{1}^{\infty}$ and $f_{0}^{1}$.)

3 Show that $\int_{0}^{\pi} \log \sin x \, dx = -\pi \log 2$. (Hint: $\sin 2x = 2 \sin x \cos x$.)

4 Suppose $-\infty < a < b \leq \infty$ and $f : [a,b) \to E$ is admissible. Show then that $\int_a^b f$ exists if and only if for every $\varepsilon > 0$ there is a $c \in [a,b)$ such that $|\int_\alpha^\beta f| < \varepsilon$ for $\alpha, \beta \in [c,b)$.

5 Show that the integral $\int_{0}^{\infty}\sqrt{t}\cos(t^{2})dt$ converges.$^{4}$

3 Suppose $-\infty < a < b \leq \infty$, and $f : [a, b) \to \mathbb{R}$ is admissible.

(i) If $f \geq 0$, show $\int_a^b f(x) dx$ if and only if $K := \sup_{c \in [a, b)} |f_a^c f| < \infty$.

(ii) Suppose $f \in C\left(\lceil a, b \rceil, \mathbb{R}\right)$ and $g \in C^1\left(\lceil a, b \rceil, \mathbb{R}\right)$. Show that if $K < \infty$ and $g(x)$ tends monotonically to 0 as $x \to b - 0$, then $\int_a^b fg$ converges.

7 Suppose that $f \in C^{1}([a, \infty), \mathbb{R})$ with $a \in \mathbb{R}$, and suppose that $f'$ is increasing with $\lim_{x \to \infty} f'(x) = \infty$. Prove that $\int_{a}^{\infty} \sin\left(f(x)\right) dx$ converges.

(Hint: Substitute $y = f(x)$ and recall Theorem III.5.7.)

8 The function $f \in C([0,\infty),\mathbb{R})$ satisfies $\sup_{0<a<b<\infty} |J^b_f| < \infty$. Show then that

$$
\int _ { 0 } ^{\infty} \frac { f ( a x ) - f ( b x ) } { x } d x = f ( 0 ) \log \left( \frac { a } { b } \right)  \mathrm { f o r ~ } 0 < a < b \ .
$$

(Hint: Let $c>0$. The existence of $\xi(c)\in[ac,bc]$ such that

$$
\int _ { c } ^{\infty} { \frac { f ( a x ) - f ( b x ) } { x } } \, d x = \int _ { a c } ^{b c} { \frac { f ( x ) } { x } } \, d x = f \bigl ( \xi ( c ) \bigr ) \log  \left( { \frac { a } { b } } \right)
$$

follows from Theorem 4.16.)

9 Suppose $-\infty < a < 0 < b < \infty$, and $f : [a,0) \cup (0,b] \to \mathbb{R}$ is admissible. If

$$
\operatorname* { l i m } _ { \varepsilon \to 0 } \left( \int _ { a } ^{- \varepsilon} f ( x ) \, d x + \int _ { \varepsilon } ^{b} f ( x ) \, d x \right)
$$

exists in $\mathbb{R}$, then this limit is called the Cauchy principal value of $\int_{a}^{b}f$, and we write$^{5}$ $PV\int_{a}^{b}f$. Compute

$$
P V \int _ { - 1 } ^{1} { \frac { d x } { x } } ~ , ~ ~ ~ P V \int _ { - \pi / 2 } ^{\pi / 2} { \frac { d x } { \sin x } } ~ , ~ ~ ~ P V \int _ { - 1 } ^{1} { \frac { d x } { x ( 6 + x - x ^{2} ) } } ~ .
$$





# List of Problems from [1]

112

(c) Using the functional equation (9.25) and the properties of the gamma function, the beta function can be defined for all $p,q\in\mathbb{C}$ such that $p,q,(p+q)\notin-\mathbb{N}$. ■

# Exercises

1 Prove that

$$
\Gamma \left( n + { \frac { 1 } { 2 } } \right) = { \sqrt { \pi } } \prod _ { k = 1 } ^{n} { \frac { 2 k - 1 } { 2 } } = 1 \cdot 3 \, \cdots \cdot ( 2 n - 1 ) { \frac { { \sqrt { \pi } } } { 2 ^{n} } }  { \mathrm { f o r ~ } } n \in \mathbb { N } ^{\times} .
$$

2 Show that $\Gamma$ belongs to $C^{\infty}(\mathbb{C}\backslash(-\mathbb{N}),\mathbb{C})$ with

$$
\Gamma ^{( n )} ( z ) = \int _ { 0 } ^{\infty} t ^{z - 1} ( \log t ) ^{n} e ^{- t} d t  \mathrm { f o r ~ } n \in \mathbb { N } \mathrm { ~ a n d ~ } \mathrm { R e } \, z > 0 \ .
$$

(Hint: Consider $(9.4)$.)

3 Let $C$ be the Euler–Mascheroni constant. Verify these statements:

(i) $\int_{0}^{\infty} e^{-t} \log t \, dt = -C.$

(ii) $\int_{0}^{\infty} e^{-t} \log t \, dt = 1 - C.$

(iii) $\int_{0}^{\infty} e^{-t} \frac{e^{-t} n^{-1}}{n} \log t \, dt = (n-1)! \sum_{k=1}^{n-1}(1/k - C)$ for $n \in \mathbb{N}$ and $n \geq 2$.

(iv) $\int_{0}^{\infty} (\log t)^{2} e^{-t} \, dt = C^{2} + \pi^{2}/6$.

(Hint: To compute the integrals in (iv), consider Application 7.23(a.))

4 Show that the gamma function has the representation

$$
\Gamma ( z ) = \int _ { 0 } ^{1} ( - \log t ) ^{z - 1} d t
$$

for $z \in \mathbb{C}$ such that $\operatorname{Re} z > 0$.

5 Suppose $f$ and $g$ are log convex. Show that $fg$ is also log convex.

6 Suppose the function $f:(0,\infty)\to(0,\infty)$ is differentiable$^{6}$ and satisfies

(i) $f$ is log convex;

(ii) $f(x+1)=xf(x)$ for $x>0$;

(iii) $f(1)=1$.

Show then that $f=\Gamma|(0,\infty)$.

(Hints: (α) Define $h := \log(\Gamma/f)$. Using (iii), it suffices to verify $h' = 0$.

(β) From (ii) and Theorem 9.2, it follows that $h$ is 1-periodic.

(γ) From (i) it follows that $(\log f)'$ is increasing (see Theorem IV.2.12). This implies

$$
0 \leq ( \log f ) ^{\prime} ( x + y ) - ( \log f ) ^{\prime} ( x ) \leq ( \log f ) ^{\prime} ( x + 1 ) - ( \log f ) ^{\prime} ( x ) = 1 / x
$$

for $0 < y \leq 1$, where the last step follows from reusing (ii). An analogous estimate holds also for $(\log \Gamma)'$. Therefore

$$
- 1 / x \leq h ^{\prime} ( x + y ) - h ^{\prime} ( x ) \leq 1 / x  \mathrm { f o r ~ } y \in ( 0 , 1 ] \mathrm { ~ a n d ~ } x \in ( 0 , \infty ) \ .
$$





# List of Problems from [1]

VI.9 The gamma function

Then that $h$, $h'$, and $h'(\cdot + y)$ are 1-periodic implies that

$$
- 1 / ( x + n ) \leq h ^{\prime} ( x + y ) - h ^{\prime} ( x ) \leq 1 / ( x + n )  \mathrm { f o r ~ } x , y \in ( 0 , 1 ] \mathrm { ~ a n d ~ } n \in \mathbb { N } ^{\times} \ .
$$

For $n \rightarrow \infty$, it now follows that $h' = 0$.)

7 Prove the Legendre duplication formula

$$
\Gamma \Big ( { \frac { x } { 2 } } \Big ) \Gamma \Big ( { \frac { x + 1 } { 2 } } \Big ) = { \frac { \sqrt { \pi } } { 2 ^{x - 1} } } \Gamma ( x )  { \mathrm { f o r ~ } } x \in ( 0 , \infty ) \ .
$$

(Hint: Consider $h(x):=2^{x}\Gamma(x/2)\,\Gamma((x+1)/2)$ and apply Exercise 6.)

8 For $x \in (-1, 1)$, verify the power series expansion

$$
( \log \Gamma ) ( 1 + x ) = - C x + \sum _ { k = 2 } ^{\infty} ( - 1 ) ^{k} \frac { \zeta ( k ) } { k } x ^{k} \ .
$$

(Hint: Expand $\log(1+x/n)$ as a power series for $n \in \mathbb{N}^{\times}$, and look to Proposition 9.5.)

9 Show $\int_{0}^{1}\log\Gamma(x)\,dx=\log\sqrt{2\pi}$. (Hint: Exercise 8.4 and Theorem 9.6)

10 Verify that for $0 < a < b$, we have

$$
\int _ { a } ^{b} \frac { d x } { \sqrt { ( x - a ) ( b - x ) } } = \pi ~ .
$$

11 For fixed $q \in (0, \infty)$, show the function $(0, \infty) \to (0, \infty)$, $p \mapsto \mathbf{B}(p, q)$ is differentiable and log convex. (Hint: Show $\partial_p^2\left(\log\left(t^{p-1}(1-t)^{q-1}\right)\right)=0$ for $p, q \in (0, \infty)$ and $t \in (0, 1).$)

12 Prove (without using $(9.25)$) that for $p,q\in(0,\infty)$, we have

$$
\mathbf { B } ( p + 1 , q ) = p \mathbf { B } ( p , q ) / ( p + q ) ~ .
$$

13 For $p,q\in(0,\infty)$, show

$$
\frac { \Gamma ( p ) \, \Gamma ( q ) } { \Gamma ( p + q ) } = \mathbf { B } ( p , q ) \ .
$$

(Hints: Fix $q \in (0, \infty)$ and let

$$
f : ( 0 , \infty ) \to ( 0 , \infty ) ~ ,  p \mapsto { \bf B } ( p , q ) \, \Gamma ( p + q ) / \Gamma ( q ) ~ .
$$

According to Exercise 11 and Proposition 9.8, $f$ is differentiable, and Exercises 5 and 11 show that $f$ is log convex. Further, it follows from Exercise 12 that $f$ satisfies the functional equation $f(p+1)=pf(p)$. Then $f(1)=1$ and Exercise 6 implies the claim.)





The submission problems now refer to the ones from the list above. To make the reference clear: for instance the notation I.8.6 refers to Exercise 6 in §I.8 which appears on page 16 of this document, the section appears on the left hand top corner (if the page number on the right hand corner is odd) of the copied page on the line just below the first line.

# Question 1:

Uniform convergence, sequence of functions, analytic functions, polynomial approximation

(1) Exercise §V.1.6, page 2 of this document. [10]

(2) Exercise §V.1.9, page 2 of this document. [10]

(3) Exercise §V.2.6, page 4 of this document. [10]

(4) Exercise §V.2.10, page 5 of this document. [10]

(5) Exercise §V.3.10, page 7 of this document. [10]

(6) Exercise §V.4.14, page 9 of this document. [10]

Total for Question 1: 60

testion 2:

Jump continuous functions, continuous extensions, Cauchy Riemann Integral

(1) Exercise §VI.1.9, page 11 of this document. [10]

(2) Exercise §VI.2.7, page 12 of this document. [10]

(3) Exercise §VI.3.10, page 14 of this document. [10]

Total for Question 2: 30

# Question 3:

Properties and techniques of integration, sums and integral

(1) Exercise §VI.4.12, page 17 of this document. [10]

(2) Exercise §VI.5.6, page 19 of this document. [10]

(3) Exercise §VI.6.10, page 22 of this document. [10]

Total for Question 3: 30

# 

estion 4:

Complex numbers, vector spaces, affine spaces and algebras





(1) Exercise §VI.7.10, page 25 of this document. [10]

(2) Exercise §VI.8.6, page 26 of this document. [10]

(3) Exercise §VI.9.10, page 28 of this document. [10]

Total for Question 4: 30