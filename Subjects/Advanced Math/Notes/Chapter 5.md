# Chapter 5 Exam Notes

Topic 5: Exponents & Logarithms

---

1. Core Concept: Definition & Equivalence of Logarithms

- Core Concept: **Logarithmic Equivalence**
    - Key Definition: The **logarithm** of a positive number $y$ to a positive base $a$ (where $a \neq 1$) is the exponent $x$ to which the base must be raised to yield $y$. The logarithmic form is the mathematical equivalent of the index (exponential) form: $$y = a^x \iff \log_a y = x$$
        - _Detail/Fine Print_: For a logarithmic term $\log_a y$ to be mathematically defined, the argument must be strictly positive ($y > 0$) and the base must be strictly positive and not equal to one ($a > 0$ and $a \neq 1$).
- Core Concept: **Common and Natural Logarithms**
    - Key Definition: A **common logarithm** is a logarithm with base 10, conventionally denoted as $\lg x$ or $\log_{10} x$, while a **natural logarithm** is a logarithm with the irrational base $e$ (where $e \approx 2.71828182846$), conventionally denoted as $\ln x$ or $\log_e x$.
        - _Detail/Fine Print_: Basic properties arising directly from these definitions include: $$\log_a a = 1 \quad \text{and} \quad \log_a 1 = 0$$ $$\ln e = 1 \quad \text{and} \quad \ln 1 = 0$$

---

2. Core Concept: Laws and Properties of Logarithms

- Core Concept: **Product & Quotient Laws**
    - Key Formula: For any positive real numbers $x$, $y$, and base $a > 0, a \neq 1$: $$\text{Product Law: } \log_a (xy) = \log_a x + \log_a y$$ $$\text{Quotient Law: } \log_a \left(\frac{x}{y}\right) = \log_a x - \log_a y$$
        - _Detail/Fine Print_: These laws apply only to the product or quotient of arguments. It is a critical error to write $\log_a (x \pm y) = \log_a x \pm \log_a y$ or $\frac{\log_a x}{\log_a y} = \log_a (x - y)$.
- Core Concept: **Power Law**
    - Key Formula: For any positive real number $x$, base $a > 0, a \neq 1$, and real exponent $n$: $$\log_a x^n = n\log_a x$$
        - _Detail/Fine Print_: Note that $\log_a x^n$ is not equivalent to $(\log_a x)^n$. The exponent $n$ in the power law must apply strictly to the argument, not the entire logarithmic term.
- Core Concept: **Change of Base Law**
    - Key Formula: A logarithm of base $b$ can be converted to any new positive base $c$ (where $c \neq 1$) using the identity: $$\log_b a = \frac{\log_c a}{\log_c b}$$
        - _Detail/Fine Print_: A useful corollary of the change of base law is the reciprocal property: $$\log_b a = \frac{1}{\log_a b}$$

---

3. Core Concept: Solving Logarithmic & Exponential Equations

- Core Concept: **Logarithmic Equality Property**
    - Key Formula: For any positive arguments $M$ and $N$ with identical bases: $$\log_a M = \log_a N \iff M = N$$
        - _Detail/Fine Print_: To apply this, all logarithmic terms must first be combined into a single logarithm on each side of the equation. Any solution obtained must be checked against the original equations to filter out extraneous roots.
- Core Concept: **Exponential Equations of the Form** $a^x = b$
    - Key Definition: An **exponential equation** is an equation where the unknown variable lies in the exponent.
        - _Detail/Fine Print_: If bases cannot be easily equated, solve by taking common or natural logarithms of both sides and applying the power law to isolate $x$.
- Core Concept: **Quadratic Substitution in Exponential Equations**
    - Key Formula: Equations of the form $p \cdot a^{2x} + q \cdot a^x + r = 0$ are solved by introducing a dummy variable: $$\text{Let } y = a^x \implies p y^2 + q y + r = 0$$
        - _Detail/Fine Print_: Since exponential functions strictly yield positive values ($a^x > 0$ for all real $x$), any solved value of $y$ that is negative or zero must be rejected.

---

4. Core Concept: Exponential & Logarithmic Graphs

- Core Concept: **Exponential Growth and Decay Graphs**
    - Key Definition: An **exponential graph** of the form $y = A \cdot a^x + C$ is a continuous curve with a horizontal asymptote at $y = C$.
        - _Detail/Fine Print_: If $a > 1$, the graph represents growth; if $0 < a < 1$, it represents decay. The natural exponential graph $y = e^x$ has a domain of $\mathbb{R}$ and a range of $y > 0$, with a $y$-intercept at $(0,1)$.
- Core Concept: **Logarithmic Graphs**
    - Key Definition: A **logarithmic graph** of the form $y = \log_a(x-h)$ has a vertical asymptote at $x = h$.
        - _Detail/Fine Print_: The natural logarithmic graph $y = \ln x$ is the reflection of $y = e^x$ across the identity line $y = x$, reflecting their relationship as inverse functions. The domain is strictly $x > 0$, the range is $\mathbb{R}$, and the $x$-intercept is $(1,0)$.

---

🛠️ Numbered Procedures

Procedure 1: Solving Logarithmic Equations (Same Base)

1. **Identify domain restrictions**: Set each logarithmic argument to be strictly greater than zero to find the valid range of $x$.
2. **Consolidate logarithmic terms**: Use the product, quotient, and power laws to group all logarithms into a single log on one side (or one on each side).
3. **Convert or equate**:
    - If $\log_a f(x) = \log_a g(x)$, equate the arguments: $f(x) = g(x)$.
    - If $\log_a f(x) = C$, convert to index form: $f(x) = a^C$.
4. **Solve the resulting polynomial equation** for $x$.
5. **Filter extraneous roots**: Compare all solutions against the restrictions in Step 1. Reject any root that makes any original argument non-positive.

Procedure 2: Solving Simultaneous Logarithmic Equations

1. Use the laws of logarithms to expand and simplify each simultaneous equation.
2. Define substitution variables for the logarithmic expressions (e.g., let $u = \log_q x$ and $v = \log_q y$) to obtain a linear system.
3. Solve the linear system for $u$ and $v$ using elimination or substitution.
4. Convert $u$ and $v$ back to $x$ and $y$ using index definitions (e.g., $x = q^u$ and $y = q^v$).
5. Check that the final coordinate pair satisfies all original domain conditions.

---

📝 Worked Examples per Question Type

Type 1: Evaluating Domain Restrictions

- **Question**: Determine the range of values of $x$ for which the expression $\log_x (5 - 4x)$ is mathematically defined.
- **Step-by-Step Solution**:
    1. Identify the condition for the argument of the logarithm to be positive: $$5 - 4x > 0 \implies 4x < 5 \implies x < \frac{5}{4}$$
    2. Identify the conditions for the base $x$ of the logarithm: $$x > 0 \quad \text{and} \quad x \neq 1$$
    3. Intersect all conditions: $$0 < x < \frac{5}{4} \quad \text{where } x \neq 1$$
    4. Express the final defined domain: $$x \in \left(0, 1\right) \cup \left(1, 1.25\right)$$

Type 2: Change of Base Simplification

- **Question**: Solve the equation $\log_8 27 + \log_2(x+1) = 2\log_2(x-5)$.
- **Step-by-Step Solution**:
    1. Determine domain restrictions: $x+1 > 0 \implies x > -1$ and $x-5 > 0 \implies x > 5$. Thus, the combined domain restriction is $x > 5$.
    2. Simplify $\log_8 27$ by converting it to base 2: $$\log_8 27 = \frac{\log_2 27}{\log_2 8} = \frac{\log_2 3^3}{3} = \frac{3\log_2 3}{3} = \log_2 3$$
    3. Substitute back and combine using the Product Law on the LHS and the Power Law on the RHS: $$\log_2 3 + \log_2(x+1) = \log_2 (x-5)^2$$ $$\log_2 [3(x+1)] = \log_2 (x-5)^2$$
    4. Equate the arguments of the logarithms: $$3(x+1) = (x-5)^2$$ $$3x + 3 = x^2 - 10x + 25$$ $$x^2 - 13x + 22 = 0$$
    5. Factorise and solve the quadratic: $$(x-11)(x-2) = 0 \implies x = 11 \quad \text{or} \quad x = 2$$
    6. Filter solutions: Since $x = 2$ is less than our domain restriction of $x > 5$, it must be rejected as an extraneous root.
    7. Final valid solution: $x = 11$.

Type 3: Solving Simultaneous Logarithmic Systems

- **Question**: Solve the simultaneous equations: $$\log_q(xy) = 3 \quad \text{and} \quad \log_q(x^2 y^3) = 4$$
- **Step-by-Step Solution**:
    1. Apply the product and power laws to expand both equations: $$\log_q x + \log_q y = 3 \quad \text{(Equation 1)}$$ $$2\log_q x + 3\log_q y = 4 \quad \text{(Equation 2)}$$
    2. Substitute variables to simplify (let $u = \log_q x$ and $v = \log_q y$): $$u + v = 3$$ $$2u + 3v = 4$$
    3. Multiply the first equation by 2 and subtract it from the second equation: $$2u + 2v = 6$$ $$(2u + 3v) - (2u + 2v) = 4 - 6 \implies v = -2$$
    4. Solve for $u$ using the first equation: $$u + (-2) = 3 \implies u = 5$$
    5. Convert the substitution variables back to $x$ and $y$ using index form: $$\log_q x = 5 \implies x = q^5$$ $$\log_q y = -2 \implies y = q^{-2}$$
    6. State the final valid coordinate pairs: $(x, y) = (q^5, q^{-2})$.

Type 4: Quadratic Substitution of Exponential Equations

- **Question**: Solve the equation $2^{2x} - 2^{x+3} + 7 = 0$.
- **Step-by-Step Solution**:
    1. Rewrite the exponential terms to isolate the base power $2^x$: $$(2^x)^2 - (2^3)(2^x) + 7 = 0$$ $$(2^x)^2 - 8(2^x) + 7 = 0$$
    2. Substitute $y = 2^x$ to form a quadratic equation: $$y^2 - 8y + 7 = 0$$
    3. Factorise and solve for $y$: $$(y-7)(y-1) = 0 \implies y = 7 \quad \text{or} \quad y = 1$$
    4. Convert back to solve for $x$:
        - Case 1: $2^x = 7 \implies x = \frac{\ln 7}{\ln 2} \approx 2.81$
        - Case 2: $2^x = 1 \implies x = 0$
    5. Verify conditions: Both values of $y$ are positive ($y > 0$), so both solutions are valid.

Type 5: Graph Sketching with Modulus Transformations

- **Question**: Sketch the graph of $y = |e^{-x} - 3|$. State its $y$-intercept and the equation of its asymptote.
- **Step-by-Step Solution**:
    1. Sketch the inner function $f(x) = e^{-x} - 3$:
        - This is a natural exponential decay curve shifted downwards by 3 units.
        - The horizontal asymptote of the inner curve is $y = -3$.
        - The $y$-intercept is $(0, 1 - 3) = (0, -2)$.
        - The $x$-intercept is found by setting $e^{-x} - 3 = 0 \implies x = -\ln 3 \approx -1.10$.
    2. Apply the absolute value modulus transformation (reflecting all negative $y$-values across the $x$-axis):
        - The horizontal asymptote $y = -3$ reflects to become $y = 3$.
        - The $y$-intercept $(0, -2)$ reflects to become $(0, 2)$.
        - The portion of the curve to the right of the $x$-intercept $x = -\ln 3$ (which was below the $x$-axis) is reflected upwards.
    3. Identify final graph features:
        - **Asymptote**: $y = 3$
        - $y$**-intercept**: $(0,2)$
        - **Domain**: $\mathbb{R}$, **Range**: $y \ge 0$.

---

⚠️ Common Mistakes Students Make on Exams

- **Illegal Algebraic Distribution of Logarithms**: Mistakenly expanding a sum or difference of arguments as if logarithms distribute linearly (e.g., writing $\log(a-b)$ as $\log a - \log b$). Remember that there is no law of logarithms for the subtraction of arguments.
- **Confusion of Power Laws**: Evaluating $(\log_a x)^n$ as $n\log_a x$. The exponent must belong strictly to the argument inside the logarithm, not the outer power of the expression.
- **Failing to Reject Extraneous Roots**: Failing to test solved roots against original conditions. For example, keeping $x = 1$ in Type 2, which would violate the constraint that logarithmic arguments must be strictly positive.
- **Retaining Negative Outputs of Substitution**: Forgetting that exponential functions strictly yield positive values, and incorrectly trying to solve equations like $e^x = -5$.
- **Incorrect Modulus Asymptote Reflection**: Applying a modulus transformation to an exponential graph but forgetting to reflect its horizontal asymptote (e.g., sketching $y = |e^x - 2|$ but keeping the asymptote at $y = -2$ instead of reflecting it to $y = 2$).

---

🔗 Cross-References to Related Concepts

- **Topic 4 (Inverse Functions)**: Natural exponential and logarithmic functions are inverse reflections of each other across the line $y = x$. Domain and range boundaries swap perfectly: $D_{\ln} = R_{\exp} = (0,\infty)$.
- **Topic 1 (Algebraic Simultaneous Equations)**: Solving complex logarithmic simultaneous equations relies directly on solving systems of linear equations.
- **Topic 3 (Partial Fractions)**: Resolving rational asymptotes parallels vertical domain restrictions on logarithmic axes.