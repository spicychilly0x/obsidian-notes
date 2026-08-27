# Chapter 4 Exam Notes: Indices, Surds and Logarithms

Section 1: Laws of Indices

- **Zero and Negative Indices**
    - **Zero Index**: For any non-zero real base $a \neq 0$, the zero-power of the base is defined as $a^0 = 1$.
        - The base must be strictly non-zero; $0^0$ is undefined and not equal to $1$.
    - **Negative Index**: For any positive base $a > 0$ and rational exponent $p$, a negative exponent denotes a reciprocal: $a^{-p} = \frac{1}{a^p}$.
        - Taking the reciprocal of a fractional base inverts the sign of the exponent: $\left(\frac{a}{b}\right)^{-p} = \left(\frac{b}{a}\right)^p$.
- **Fractional Exponents**
    - **Fractional Index**: Representing radical terms using rational exponents.
        - Key LaTeX formulas:
            - $a^{\frac{1}{p}} = \sqrt[p]{a}$
            - $a^{\frac{q}{p}} = \sqrt[p]{a^q} = (\sqrt[p]{a})^q$
        - The denominator of the exponent represents the root index, and the numerator represents the power to which the base or root is raised.
- **Laws of Indices**
    - **Laws of Indices**: Algebraic rules governing the simplification of exponential terms with the same base or matching exponents.
        - Key LaTeX formulas:
            - Multiplication Law: $a^m \times a^n = a^{m+n}$
            - Division Law: $a^m \div a^n = a^{m-n}$
            - Power of a Power Law: $(a^m)^n = a^{mn}$
            - Power of a Product Law: $(ab)^n = a^n b^n$
            - Power of a Quotient Law: $\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}$
        - These laws hold true for positive bases $a > 0, b > 0$ and rational exponents $m, n$.

---

Section 2: Exponential Equations

- **Solving by Equating Bases**
    - **Exponential Equation**: An equation where the unknown variable resides in the exponent of a base.
        - If the bases on both sides of an equation are equal, their exponents must be equal: if $a^x = a^y$ (for $a \neq -1, 0, 1$), then $x = y$.
- **Solving by Quadratic Substitution**
    - **Quadratic Substitution**: Using a temporary variable $y = a^x$ to convert a multi-term exponential equation into a quadratic equation of the form $Ay^2 + By + C = 0$.
        - Since the exponential function $a^x$ is strictly positive for any real value of $x$, any negative or zero value solved for $y$ (i.e., $y \leq 0$) must be rejected as extraneous.

---

Section 3: Surds & Radical Equations

- **Surds and Radicals**
    - **Surds**: Real, irrational roots of rational numbers that cannot be expressed as exact decimals or fractions.
        - Radicals that simplify to integers (such as $\sqrt{25} = 5$) are rational and are not categorized as surds.
    - **Conjugate Surds**: Pairs of binomial surds of the form $a + b\sqrt{c}$ and $a - b\sqrt{c}$ whose product is always a rational number.
        - Key LaTeX formula:
            - $(a + b\sqrt{c})(a - b\sqrt{c}) = a^2 - b^2 c$
        - Multiplying conjugate pairs utilizes the difference of squares identity to eliminate the irrational radical parts.
- **Rationalising the Denominator**
    - **Rationalising the Denominator**: The algebraic process of removing irrational radical terms from the denominator of a fraction.
        - For a binomial denominator of the form $p \pm \sqrt{q}$, the fraction is scaled by multiplying the numerator and denominator by its conjugate $p \mp \sqrt{q}$.
- **Radical Equations**
    - **Radical Equation**: An equation where the unknown variable is located under a radical (square root) symbol.
        - Squaring both sides of an equation can introduce extraneous roots, making it mandatory to substitute all algebraic solutions back into the original equation to verify their validity.

---

Numbered Procedures

Procedural Topic: Solving Exponential Equations by Base Equating

1. **Express under a Common Base**: Factorize all numerical bases into their prime factors (e.g., convert $9$ to $3^2$, $32$ to $2^5$).
2. **Apply Laws of Indices**: Simplify both sides using the laws of indices until there is a single exponential term on each side: $a^{f(x)} = a^{g(x)}$.
3. **Equate Exponents**: Drop the bases and set the exponents equal to each other: $f(x) = g(x)$.
4. **Solve**: Solve the resulting linear or quadratic equation for $x$.

Procedural Topic: Rationalising Binomial Denominators

1. **Find the Conjugate**: Identify the conjugate of the binomial denominator by reversing the sign between the two terms (e.g., the conjugate of $a + \sqrt{b}$ is $a - \sqrt{b}$).
2. **Multiply Fraction**: Multiply both the numerator and the denominator of the fraction by this conjugate.
3. **Expand Numerator**: Distribute and simplify the numerator terms.
4. **Expand Denominator**: Use the difference of squares identity $(x-y)(x+y) = x^2 - y^2$ to eliminate the radical term in the denominator.
5. **Simplify**: Divide out any common numerical factors to write the final fraction in its simplest form.

Procedural Topic: Solving Radical Equations

1. **Isolate the Radical**: Rearrange the equation to isolate the radical term on one side.
2. **Square Both Sides**: Square both sides of the equation to eliminate the square root sign.
3. **Solve the Polynomial**: Rearrange the resulting equation into a standard quadratic form $ax^2 + bx + c = 0$ and solve for $x$.
4. **Check for Extraneous Solutions**: Substitute each solved value back into the _original_ equation. Reject any value that does not satisfy it.

---

Worked Examples

Example 1: Laws of Indices (Divisibility Proof)

- **Question**: Show that the expression $7^{n+1} + 7^{n+2} + 7^{n+3}$ is divisible by $399$ for all positive integers $n$.
- **Step-by-Step Reasoning**:
    1. **Split exponents**: Use the multiplication law $a^{m+n} = a^m \times a^n$ to expand the terms: $$7^n \times 7^1 + 7^n \times 7^2 + 7^n \times 7^3$$
    2. **Factor out** $7^n$: $$7^n(7^1 + 7^2 + 7^3)$$
    3. **Evaluate the sum in brackets**: $$7^n(7 + 49 + 343) = 7^n(399)$$
    4. **Conclude divisibility**: Since the expression simplifies to $399 \times 7^n$ and $7^n$ is an integer for any positive integer $n$, $399$ is a factor of the expression, proving it is divisible by $399$.

Example 2: Laws of Indices (Finding Value of Product Power)

- **Question**: Given that $2^{3x-4} \times 9^{x+1} = 2^x$, find the value of $6^x$.
- **Step-by-Step Reasoning**:
    1. **Expand the index terms**: $$2^{3x} \times 2^{-4} \times 9^x \times 9^1 = 2^x$$
    2. **Group** $x$ **terms on one side**: Divide both sides by $2^x$ and rearrange constants: $$\frac{2^{3x} \times 9^x}{2^x} = \frac{2^4}{9}$$
    3. **Simplify exponential terms**: $$2^{2x} \times 9^x = \frac{16}{9} \implies 4^x \times 9^x = \frac{16}{9}$$
    4. **Apply product of power law**: $$(4 \times 9)^x = \frac{16}{9} \implies 36^x = \frac{16}{9}$$
    5. **Solve for** $6^x$: Recognize that $36^x = (6^x)^2$: $$(6^x)^2 = \frac{16}{9} \implies 6^x = \sqrt{\frac{16}{9}} = \frac{4}{3} \quad (6^x > 0)$$

Example 3: Exponential Equation (Quadratic Substitution)

- **Question**: Solve the equation $2^x - 3 = \frac{4}{2^x}$ for $x$.
- **Step-by-Step Reasoning**:
    1. **Apply substitution**: Let $y = 2^x$. Substitute this into the equation: $$y - 3 = \frac{4}{y}$$
    2. **Eliminate the fraction**: Multiply all terms by $y$: $$y^2 - 3y = 4 \implies y^2 - 3y - 4 = 0$$
    3. **Factorize the quadratic**: Solve for $y$: $$(y-4)(y+1) = 0 \implies y = 4 \quad \text{or} \quad y = -1$$
    4. **Apply exponential constraints**: Since $2^x > 0$ for all real $x$, reject the negative solution $y = -1$.
    5. **Solve for** $x$: Solve $2^x = 4$: $$2^x = 2^2 \implies x = 2$$

Example 4: Exponential Boundary Constraints

- **Question**: Find the value of $a$ such that $3^{2x+1} = a(3^x) - 3$ is satisfied by exactly one value of $x$.
- **Step-by-Step Reasoning**:
    1. **Rearrange into quadratic form**: $$3(3^{2x}) - a(3^x) + 3 = 0$$
    2. **Substitute**: Let $y = 3^x$ (where $y > 0$): $$3y^2 - ay + 3 = 0$$
    3. **Apply discriminant condition**: For the quadratic to have equal roots: $$b^2 - 4ac = 0 \implies a^2 - 4(3)(3) = 0 \implies a^2 = 36 \implies a = \pm 6$$
    4. **Test solutions**:
        - If $a = 6 \implies 3(y-1)^2 = 0 \implies y = 1 \implies 3^x = 1 \implies x = 0$ (one valid solution).
        - If $a = -6 \implies 3(y+1)^2 = 0 \implies y = -1 \implies 3^x = -1$ (no real solution, since $3^x > 0$).
    5. **Conclusion**: The only accepted value is $a = 6$.

Example 5: Rationalising and Coefficient Comparison

- **Question**: Find the values of the real numbers $a$ and $b$ such that $(a + \sqrt{3})(5 - 2\sqrt{27}) = b - 7\sqrt{3}$.
- **Step-by-Step Reasoning**:
    1. **Simplify surds**: Recognize $\sqrt{27} = 3\sqrt{3}$: $$(a + \sqrt{3})(5 - 6\sqrt{3})$$
    2. **Expand brackets**: $$5a - 6a\sqrt{3} + 5\sqrt{3} - 6(3) = (5a - 18) + (5 - 6a)\sqrt{3}$$
    3. **Equate coefficients**: $$(5a - 18) + (5 - 6a)\sqrt{3} = b - 7\sqrt{3}$$
        - Irrational parts: $5 - 6a = -7 \implies 6a = 12 \implies a = 2$
        - Rational parts: $b = 5a - 18 \implies b = 5(2) - 18 = -8$

Example 6: Cuboid Mensuration with Conjugate Division

- **Question**: A cuboid has a square base of side $(1 + \sqrt{5})$ m and a volume of $(\sqrt{5} + 2)(2\sqrt{5} - 1)$ m$^3$. Find the height of the cuboid in the form $p + q\sqrt{5}$ where $p$ and $q$ are rational numbers.
- **Step-by-Step Reasoning**:
    1. **Calculate base area**: $$\text{Base Area} = (1 + \sqrt{5})^2 = 1 + 2\sqrt{5} + 5 = 6 + 2\sqrt{5}$$
    2. **Simplify volume**: $$\text{Volume} = (\sqrt{5} + 2)(2\sqrt{5} - 1) = 10 - \sqrt{5} + 4\sqrt{5} - 2 = 8 + 3\sqrt{5}$$
    3. **Set up height division**: $$\text{Height} = \frac{8 + 3\sqrt{5}}{6 + 2\sqrt{5}}$$
    4. **Rationalise denominator using conjugate**: $$\text{Height} = \frac{(8 + 3\sqrt{5})(6 - 2\sqrt{5})}{(6 + 2\sqrt{5})(6 - 2\sqrt{5})} = \frac{48 - 16\sqrt{5} + 18\sqrt{5} - 30}{36 - 20} = \frac{18 + 2\sqrt{5}}{16} = \frac{9 + \sqrt{5}}{8} = \frac{9}{8} + \frac{1}{8}\sqrt{5}$$

Example 7: Radical Equation with Extraneous Solutions

- **Question**: Solve the equation $\sqrt{x+5} + x = 1$.
- **Step-by-Step Reasoning**:
    1. **Isolate radical**: $$\sqrt{x+5} = 1 - x$$
    2. **Square both sides**: $$x + 5 = (1 - x)^2$$
    3. **Expand and form quadratic**: $$x + 5 = 1 - 2x + x^2 \implies x^2 - 3x - 4 = 0$$
    4. **Factorize**: $$(x - 4)(x + 1) = 0 \implies x = 4 \quad \text{or} \quad x = -1$$
    5. **Verify solutions in original equation**:
        - If $x = 4$: $\text{LHS} = \sqrt{4+5} + 4 = 7 \neq 1$ (Reject $x = 2$).
        - If $x = -1$: $\text{LHS} = \sqrt{-1+5} + (-1) = 2 - 1 = 1 = \text{RHS}$ (Accept $x = -1$).

---

⚠️ Common Mistakes on Exams

- **Distributing Exponents and Radicals Over Addition/Subtraction**: Incorrectly assuming $a^m + b^n = (a+b)^{m+n}$ or $\sqrt{a \pm b} = \sqrt{a} \pm \sqrt{b}$. Exponent and radical rules apply strictly to products and quotients, never to sums or differences.
- **Tower Power Simplification Errors**: Evaluating $(a^m)^n$ as $a^{(m^n)}$ instead of multiplying the powers to get $a^{mn}$.
- **Retaining Extraneous Substitution Roots**: Keeping negative or zero roots for exponential substitution variables (e.g., attempting to solve $2^x = -1$ after solving a quadratic substitution where $y = -1$).
- **Misinterpreting "Exactly One Solution" in Substitution Quadratics**: Forgetting that an exponential quadratic $Ay^2 + By + C = 0$ can yield exactly one solution for $x$ even when the discriminant is positive, if one of the resolved roots for $y$ is negative (which must be rejected).
- **Neglecting Extraneous Root Checks on Radical Equations**: Leaving incorrect algebraic solutions on exam sheets because of a failure to test both roots in the original equation.

---

🔗 Cross-References

- **Indices** $\leftrightarrow$ **Simultaneous Linear and Non-Linear Equations (Chapter 2)**: Some non-linear simultaneous equations require converting exponential systems into linear coordinate equations before running substitution or elimination.
- **Exponential Quadratics** $\leftrightarrow$ **Quadratic Formula and Discriminant (Chapter 3)**: Multi-term exponential equations are transformed into Chapter 3 quadratics via substitution, and their roots must be checked against real-root constraints.
- **Conjugate Surds** $\leftrightarrow$ **Algebraic Identities (Chapter 1)**: Rationalising binomial denominators uses the difference of squares identity $(x-y)(x+y) = x^2 - y^2$ to clear irrational radical parts.