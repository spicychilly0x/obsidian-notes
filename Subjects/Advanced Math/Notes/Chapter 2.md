# Chapter 2 Exam Notes

Topic 2: Polynomials & Identities

---

1. Core Concept: Polynomial Degrees & Basic Operations

- Core Concept: **Polynomials in one variable**
    - Key Definition: A **polynomial** is an algebraic expression of the form: $$P(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0$$ where $a_n, a_{n-1}, \dots, a_0$ are real-number constants representing coefficients, and the powers of the variable $x$ are non-negative integers.
        - _Detail/Fine Print_: The **degree of a polynomial** is defined as the highest power $n$ of the variable $x$ with a non-zero coefficient. Fractional or negative exponents (such as $x^{-2}$ or $\sqrt{x}$) disqualify an expression from being a polynomial.
- Core Concept: **Resultant degree of arithmetic operations**
    - Key Formula: When performing arithmetic on two polynomials, $P(x)$ of degree $p$ and $Q(x)$ of degree $q$: $$\text{Degree of } [P(x) \cdot Q(x)] = p + q$$ $$\text{Degree of } [P(x) \pm Q(x)] \le \max(p, q)$$
        - _Detail/Fine Print_: The degree of a constant polynomial (e.g., $P(x) = 3$) is $0$. The degree of the zero polynomial $P(x) = 0$ is undefined.

---

2. Core Concept: Polynomial Division

- Core Concept: **Polynomial division algorithm**
    - Key Formula: Any polynomial dividend $P(x)$ divided by a divisor $D(x)$ can be uniquely expressed as: $$P(x) = Q(x)D(x) + R(x)$$ where $Q(x)$ is the quotient and $R(x)$ is the remainder.
        - _Detail/Fine Print_: The degree of the remainder $R(x)$ is strictly less than the degree of the divisor $D(x)$. If dividing by a linear divisor $(ax+b)$, the remainder must be a constant. If dividing by a quadratic divisor $(ax^2+bx+c)$, the remainder is at most linear $(px+q)$.
- Core Concept: **Synthetic division limitations**
    - Key Definition: **Synthetic division** is a shorthand method of polynomial division that uses only coefficients to divide a polynomial by a linear divisor.
        - _Detail/Fine Print_: This method is applicable **ONLY** when the divisor is of the linear form $ax + b$ or $ax - b$. For non-linear divisors (such as quadratic divisors), polynomial long division must be used instead.

---

3. Core Concept: Polynomial Identities

- Core Concept: **Identities vs. Equations**
    - Key Definition: An **identity** is a mathematical relation containing variables that remains true for all possible real values of those variables, denoted by the symbol $\equiv$, whereas a standard equation is only satisfied for specific fixed values of $x$.
        - _Detail/Fine Print_: Because an identity holds for all values of $x$, the coefficients of corresponding powers of $x$ on both sides of the identity must be identical.
- Core Concept: **Determining coefficients of identities**
    - Key Method: Unknown coefficients in an identity are found using either:
        1. **Substitution method**: Substituting strategically chosen values of $x$ (often roots of linear terms) to isolate and solve for individual constants.
        2. **Comparing coefficients method**: Expanding and grouping terms on both sides, then equating coefficients of identical powers of $x$.
        3. _Detail/Fine Print_: Substitution is highly efficient for factors in the form $(x-k)$, while comparing coefficients is preferred when there are no obvious roots to substitute.

---

4. Core Concept: Remainder and Factor Theorems

- Core Concept: **Remainder Theorem**
    - Key Formula: If a polynomial $f(x)$ is divided by a linear divisor $ax - b$, the remainder $R$ is given by: $$R = f\left(\frac{b}{a}\right)$$
        - _Detail/Fine Print_: If the divisor is simply $x - c$, the remainder is $f(c)$. This theorem only evaluates the remainder directly; it does not provide the quotient polynomial $Q(x)$.
- Core Concept: **Factor Theorem**
    - Key Definition: The **Factor Theorem** states that a linear expression $(ax - b)$ is a factor of a polynomial $f(x)$ if and only if the remainder of the division is zero: $$f\left(\frac{b}{a}\right) = 0$$
        - _Detail/Fine Print_: Conversely, if $f(c) = 0$, then $(x - c)$ is a factor of $f(x)$. This property is the primary tool used to discover linear factors of higher-degree polynomials by testing integer factors of the constant term.

---

5. Core Concept: Solving Cubic Equations

- Core Concept: **Cubic Equations**
    - Key Definition: A **cubic equation** is a polynomial equation of degree three, written in the general form: $$ax^3 + bx^2 + cx + d = 0 \quad \text{where } a \neq 0$$
        - _Detail/Fine Print_: A cubic equation always has at least one real root and can have up to a maximum of three real roots.
- Core Concept: **Sum and Difference of Cubes Factorisation**
    - Key Formula: Binomial cubic expressions are factorised using the algebraic identities: $$a^3 + b^3 \equiv (a+b)(a^2 - ab + b^2)$$ $$a^3 - b^3 \equiv (a-b)(a^2 + ab + b^2)$$
        - _Detail/Fine Print_: The quadratic factor $(a^2 \mp ab + b^2)$ has a negative discriminant, which means it has no real roots and cannot be factorised further over real numbers.

---

🛠️ Numbered Procedures

Procedure 1: Polynomial Long Division

1. **Arrange terms**: Write both the dividend $P(x)$ and the divisor $D(x)$ in descending order of their exponents.
2. **Insert placeholders**: Insert placeholder terms with a coefficient of $0$ for any missing powers of $x$ (e.g., write $x^3 - 2x + 1$ as $x^3 + 0x^2 - 2x + 1$).
3. **Divide lead terms**: Divide the term with the highest power in the dividend by the highest power term of the divisor. Write this result as the first term of the quotient.
4. **Multiply**: Multiply the entire divisor by the new quotient term, and write the product beneath the dividend, aligning like terms.
5. **Subtract**: Subtract this product from the dividend to obtain a new, lower-degree remainder polynomial.
6. **Repeat**: Repeat steps 3–5 using the remainder polynomial as the new dividend.
7. **Terminate**: Stop the division when the degree of the remainder polynomial is strictly less than the degree of the divisor.

Procedure 2: Synthetic Division (for linear divisor $x - c$)

1. **Setup grid**: Write the value of $c$ on the far left. In a horizontal row on the right, write the coefficients of the dividend polynomial in descending order (including $0$ for any missing powers).
2. **Bring down**: Bring the first coefficient straight down to the bottom row.
3. **Multiply and place**: Multiply the value of $c$ by the number in the bottom row, and place this product in the next column's middle row.
4. **Add**: Add the numbers in the top and middle rows of that column, writing the sum in the bottom row.
5. **Iterate**: Repeat steps 3 and 4 for all remaining columns.
6. **Read results**: The final number in the bottom row is the remainder $R$. The preceding numbers in the bottom row represent the coefficients of the quotient polynomial $Q(x)$, which has a degree exactly one less than the dividend.

Procedure 3: Solving a Cubic Equation $ax^3 + bx^2 + cx + d = 0$

1. **Find a root by trial**: Test integer factors of the constant term $d$ in the polynomial $f(x) = ax^3 + bx^2 + cx + d$ until finding a value $k$ such that $f(k) = 0$.
2. **Identify linear factor**: By the Factor Theorem, write down the linear factor as $(x - k)$.
3. **Perform division**: Divide the cubic polynomial by $(x - k)$ using polynomial long division or synthetic division to find the quadratic quotient $px^2 + qx + r$.
4. **Form quadratic equation**: Set the quadratic quotient to zero: $px^2 + qx + r = 0$.
5. **Solve the quadratic equation**: Solve for the remaining roots using quadratic factorisation, completing the square, or the quadratic formula: $$x = \frac{-q \pm \sqrt{q^2 - 4pr}}{2p}$$
6. **State all roots**: List all valid real roots of the cubic equation.

---

📝 Worked Examples

Type 1: Polynomial Division (Long Division & Synthetic)

- **Question**: Divide $5x^3 + 11x^2 - 5x + 1$ by $x+2$ using synthetic division, and express the result in the form $P(x) = Q(x)D(x) + R$.
- **Step-by-Step Solution**:
    1. Identify $c$ from the divisor $x + 2 = x - (-2) \implies c = -2$.
    2. Set up the synthetic division grid with coefficients $[5, 11, -5, 1]$: $$\begin{array}{r|rccc} -2 & 5 & 11 & -5 & 1 \\ & & -10 & -2 & 14 \\ \hline & 5 & 1 & -7 & \mathbf{15} \end{array}$$
    3. Read the bottom row:
        - The quotient coefficients are $[5, 1, -7]$, which correspond to the polynomial $Q(x) = 5x^2 + x - 7$.
        - The remainder is $R = 15$.
    4. Write the final division identity: $$5x^3 + 11x^2 - 5x + 1 = (5x^2 + x - 7)(x+2) + 15$$

Type 2: Solving Unknowns in Polynomial Identities

- **Question**: Given that $3x^2 - 3x + 9 \equiv A(x-3)^2 + B(x-3) + C$ for all values of $x$, find the value of the constants $A$, $B$, and $C$.
- **Step-by-Step Solution**:
    1. Substitute $x = 3$ to eliminate the $A$ and $B$ terms: $$3(3)^2 - 3(3) + 9 = A(3-3)^2 + B(3-3) + C$$ $$27 - 9 + 9 = C \implies C = 27$$
    2. Substitute $x = 0$ and use $C = 27$: $$3(0)^2 - 3(0) + 9 = A(0-3)^2 + B(0-3) + 27$$ $$9 = 9A - 3B + 27 \implies 9A - 3B = -18 \implies 3A - B = -6 \quad \text{(Equation 1)}$$
    3. Compare the coefficients of $x^2$ on both sides:
        - LHS coefficient of $x^2$ is $3$.
        - RHS coefficient of $x^2$ is $A$ (from expanding $A(x^2 - 6x + 9)$).
        - Therefore, $A = 3$.
    4. Substitute $A = 3$ into Equation 1 to find $B$: $$3(3) - B = -6 \implies 9 - B = -6 \implies B = 15$$
    5. State the final solved constants: $A = 3$, $B = 15$, $C = 27$.

Type 3: Remainder Theorem with Simultaneous Equations

- **Question**: The polynomial $P(x) = 27x^3 + ax^2 + bx - 8$ leaves a remainder of $7$ when divided by $x+1$, and a remainder of $2$ when divided by $3x-2$. Find the value of $a$ and of $b$.
- **Step-by-Step Solution**:
    1. Apply the Remainder Theorem for the divisor $x + 1$ where $R = P(-1) = 7$: $$27(-1)^3 + a(-1)^2 + b(-1) - 8 = 7$$ $$-27 + a - b - 8 = 7 \implies a - b = 42 \implies b = a - 42 \quad \text{(Equation 1)}$$
    2. Apply the Remainder Theorem for the divisor $3x - 2$ where $R = P(\frac{2}{3}) = 2$: $$27\left(\frac{2}{3}\right)^3 + a\left(\frac{2}{3}\right)^2 + b\left(\frac{2}{3}\right) - 8 = 2$$ $$27\left(\frac{8}{27}\right) + \frac{4}{9}a + \frac{2}{3}b - 8 = 2$$ $$8 + \frac{4}{9}a + \frac{2}{3}b - 8 = 2 \implies \frac{4}{9}a + \frac{2}{3}b = 2$$
    3. Multiply by $9$ to clear fractions and simplify: $$4a + 6b = 18 \implies 2a + 3b = 9 \quad \text{(Equation 2)}$$
    4. Substitute Equation 1 into Equation 2: $$2a + 3(a - 42) = 9 \implies 2a + 3a - 126 = 9$$ $$5a = 135 \implies a = 27$$
    5. Calculate $b$ using Equation 1: $$b = 27 - 42 = -15$$
    6. State the final constants: $a = 27$, $b = -15$.

Type 4: Factor Theorem & Factoring Cubic Polynomials Completely

- **Question**: Given that $3x^3 - 17x - 10$ has a factor of $x+2$, factorise the polynomial completely.
- **Step-by-Step Solution**:
    1. Set up synthetic division to divide $3x^3 - 17x - 10$ by $x+2$ (using $c = -2$ and placeholder $0$ for the missing $x^2$ term): $$\begin{array}{r|rccc} -2 & 3 & 0 & -17 & -10 \\ & & -6 & 12 & 10 \\ \hline & 3 & -6 & -5 & \mathbf{0} \end{array}$$
    2. Write down the resulting factorised form: $$3x^3 - 17x - 10 = (x+2)(3x^2 - 6x - 5)$$
    3. Analyze the quadratic factor $3x^2 - 6x - 5$ to see if it factorises further over rational numbers: $$\text{Discriminant } D = (-6)^2 - 4(3)(-5) = 36 + 60 = 96$$
        - Since $96$ is not a perfect square, $3x^2 - 6x - 5$ cannot be factorised further using rational coefficients.
    4. State the final, completely factored expression: $$(x+2)(3x^2 - 6x - 5)$$

Type 5: Solving Cubic Equations

- **Question**: Solve the equation $3x^3 + 5x^2 - 3x - 2 = 0$, leaving your answers in exact surd form.
- **Step-by-Step Solution**:
    1. Let $f(x) = 3x^3 + 5x^2 - 3x - 2$. Find an initial integer root by testing factors of $-2$ (i.e., $\pm 1, \pm 2$):
        - Try $x = -2$: $$f(-2) = 3(-2)^3 + 5(-2)^2 - 3(-2) - 2 = 3(-8) + 5(4) + 6 - 2 = -24 + 20 + 6 - 2 = 0$$
        - Since $f(-2) = 0$, $x = -2$ is a root, and $(x+2)$ is a linear factor.
    2. Divide the cubic polynomial by $(x+2)$ using synthetic division to find the quadratic quotient: $$\begin{array}{r|rccc} -2 & 3 & 5 & -3 & -2 \\ & & -6 & 2 & 2 \\ \hline & 3 & -1 & -1 & \mathbf{0} \end{array}$$
        - The quadratic quotient is $3x^2 - x - 1$.
    3. Set the quadratic factor to zero and solve using the quadratic formula: $$3x^2 - x - 1 = 0$$ $$x = \frac{-(-1) \pm \sqrt{(-1)^2 - 4(3)(-1)}}{2(3)} = \frac{1 \pm \sqrt{1 + 12}}{6} = \frac{1 \pm \sqrt{13}}{6}$$
    4. List the complete set of exact real roots: $$x = -2, \quad x = \frac{1 + \sqrt{13}}{6}, \quad x = \frac{1 - \sqrt{13}}{6}$$

---

⚠️ Common Mistakes Students Make on Exams

- **Missing Zero Placeholders**: Forgetting to write terms with a zero coefficient (such as $0x^2$) when setting up long division or synthetic division. This shifts the columns and produces an incorrect quotient and remainder.
- **Incorrect Sign Subtraction**: Making sign errors when subtracting negative terms during long division steps (e.g., calculating $-5x^2 - (-8x^2)$ as $-13x^2$ instead of $3x^2$).
- **Applying Synthetic Division to Quadratic Divisors**: Attempting to use synthetic division when dividing by quadratic expressions (e.g., $x^2 - 4$). Synthetic division is strictly limited to linear divisors.
- **Sign Errors in Remainder Theorem Substitution**: Substituting $x = -c$ instead of $x = c$ when the linear divisor is $(x - c)$. For example, substituting $x = -3$ instead of $x = 3$ for the divisor $(x - 3)$.
- **Treating Identities like Equations**: Attempting to solve an identity for a specific value of $x$ rather than equating coefficients or substituting multiple test values to find unknown constants.

---

🔗 Cross-References to Related Concepts

- **Topic 1: Algebraic Fractions**: Polynomial division is used to convert improper algebraic fractions into a proper form. Factoring cubic polynomials completely is essential for finding the lowest common denominator of algebraic fractions.
- **Topic 3: Partial Fractions**: Improper rational expressions must be divided using polynomial long division before they can be decomposed into partial fractions.
- **Topic 4: Functions & Graphs**: The roots of a polynomial equation represent the x-intercepts of its corresponding graph. Denominator restrictions in rational functions define the location of vertical asymptotes.