# Chapter 7 Exam Notes: Theory of Quadratic Equations, Functions & Inequalities

---

Section 1: Sum and Product of Roots (Vieta's Formulas)

- **Symmetric Roots**
    - **Vieta's Formulas**: Proportional relationships that link the roots of a quadratic equation to its numerical coefficients.
        - Key LaTeX formulas: For the general quadratic equation $ax^2 + bx + c = 0$ (where $a \neq 0$) with roots $\alpha$ and $\beta$:
            - Sum of Roots (SOR): $\alpha + \beta = -\frac{b}{a}$
            - Product of Roots (POR): $\alpha\beta = \frac{c}{a}$
        - These formulas apply even if the roots of the quadratic equation are complex numbers or irrational surds.
- Symmetric Algebraic Identities
    - **Symmetric Expressions**: Algebraic expressions of $\alpha$ and $\beta$ that remain unchanged when the variables $\alpha$ and $\beta$ are swapped.
        - Key LaTeX formulas:
            - Sum of Squares: $\alpha^2 + \beta^2 = (\alpha + \beta)^2 - 2\alpha\beta$
            - Sum of Cubes: $\alpha^3 + \beta^3 = (\alpha + \beta)^3 - 3\alpha\beta(\alpha + \beta)$
            - Sum of Fourth Powers: $\alpha^4 + \beta^4 = (\alpha^2 + \beta^2)^2 - 2(\alpha\beta)^2$
            - Difference of Roots Squared: $(\alpha - \beta)^2 = (\alpha + \beta)^2 - 4\alpha\beta$
            - Reciprocal Sum: $\frac{1}{\alpha} + \frac{1}{\beta} = \frac{\alpha + \beta}{\alpha\beta}$
            - Reciprocal Quotient Sum: $\frac{\alpha}{\beta} + \frac{\beta}{\alpha} = \frac{\alpha^2 + \beta^2}{\alpha\beta}$
        - Any symmetric polynomial can be rewritten entirely in terms of the primary components $(\alpha+\beta)$ and $(\alpha\beta)$.

---

Numbered Procedures

Procedural Topic: Forming a New Quadratic Equation with Modified Roots

1. **Extract Original SOR and POR**: Calculate $\alpha + \beta = -\frac{b}{a}$ and $\alpha\beta = \frac{c}{a}$ from the given equation.
2. **Define New Roots**: Let the new roots be $\alpha'$ and $\beta'$ (e.g., $\alpha' = \alpha+2$ and $\beta' = \beta+2$).
3. **Calculate New SOR**: Compute $\alpha' + \beta'$ and express it purely in terms of $(\alpha+\beta)$ and $(\alpha\beta)$ to find its numerical value.
4. **Calculate New POR**: Compute $\alpha'\beta'$ and express it purely in terms of $(\alpha+\beta)$ and $(\alpha\beta)$ to find its numerical value.
5. **Formulate Equation**: Write the new quadratic equation using the template: $$x^2 - (\text{New SOR})x + (\text{New POR}) = 0$$ Multiply out fractional denominators if integer coefficients are required.

---

Worked Examples

Example 1: Forming a New Quadratic Equation

- **Question**: If $\alpha$ and $\beta$ are the roots of the quadratic equation $2x^2 - 3x - 4 = 0$, find the quadratic equation with roots $\alpha+2$ and $\beta+2$.
- **Step-by-Step Reasoning**:
    1. **Find original SOR and POR**: $$\alpha + \beta = -\frac{-3}{2} = \frac{3}{2} \quad \text{and} \quad \alpha\beta = \frac{-4}{2} = -2$$
    2. **Calculate New SOR**: $$\text{New SOR} = (\alpha + 2) + (\beta + 2) = \alpha + \beta + 4 = \frac{3}{2} + 4 = \frac{11}{2}$$
    3. **Calculate New POR**: $$\text{New POR} = (\alpha + 2)(\beta + 2) = \alpha\beta + 2(\alpha + \beta) + 4$$ $$\text{New POR} = -2 + 2\left(\frac{3}{2}\right) + 4 = -2 + 3 + 4 = 5$$
    4. **Form the new equation**: $$x^2 - \left(\frac{11}{2}\right)x + 5 = 0 \implies 2x^2 - 11x + 10 = 0$$

Example 2: Non-Zero Multi-Root Constraints

- **Question**: The roots of the quadratic equation $x^2 - (2k+4)x + (k^2+3k+2) = 0$ are non-zero, and one root is twice the other. Calculate the value of the constant $k$.
- **Step-by-Step Reasoning**:
    1. **Define roots**: Let the roots be $\alpha$ and $2\alpha$.
    2. **Formulate sum of roots**: $$\alpha + 2\alpha = 3\alpha = 2k + 4 \implies \alpha = \frac{2k+4}{3}$$
    3. **Formulate product of roots**: $$\alpha(2\alpha) = 2\alpha^2 = k^2 + 3k + 2$$
    4. **Substitute** $\alpha$ **to eliminate it**: $$2\left(\frac{2k+4}{3}\right)^2 = k^2 + 3k + 2 \implies 2\left(\frac{4k^2 + 16k + 16}{9}\right) = k^2 + 3k + 2$$ $$8k^2 + 32k + 32 = 9(k^2 + 3k + 2) \implies 8k^2 + 32k + 32 = 9k^2 + 27k + 18$$
    5. **Solve the resulting quadratic in** $k$: $$k^2 - 5k - 14 = 0 \implies (k-7)(k+2) = 0 \implies k = 7 \quad \text{or} \quad k = -2$$
    6. **Verify non-zero root constraint**:
        - If $k = -2$, the product constant of the equation is $(-2)^2 + 3(-2) + 2 = 0$, which yields a root of $0$ (Reject).
        - If $k = 7$, the product constant is $7^2 + 3(7) + 2 = 72 \neq 0$ (Accept).
    7. **Final value**: $k = 7$.

---

Section 2: Quadratic Inequalities

- **Quadratic Inequalities**
    - **Quadratic Inequality**: An inequality that can be written in one of the forms $ax^2+bx+c > 0$, $ax^2+bx+c \ge 0$, $ax^2+bx+c < 0$, or $ax^2+bx+c \le 0$, where $a \neq 0$.
        - Unlike quadratic equations, the solutions of quadratic inequalities represent continuous intervals of real numbers.

---

Numbered Procedures

Procedural Topic: Solving a Quadratic Inequality Graphically

1. **Standardise form**: Rearrange all terms to one side so that the quadratic expression is compared to zero (e.g., $ax^2 + bx + c > 0$).
2. **Ensure positive lead coefficient**: If $a < 0$, multiply the entire inequality by $-1$ and **reverse the direction of the inequality sign**.
3. **Factorise**: Find the critical values (the x-intercepts) by factorising the expression into $a(x - x_1)(x - x_2) = 0$ where $x_1 < x_2$.
4. **Sketch Parabola**: Draw a rough, upward-opening ($\cup$-shaped) parabola showing the two horizontal intercepts $x_1$ and $x_2$.
5. **Shade and State Intervals**:
    - For $< 0$ or $\le 0$: Select the region below the x-axis, giving $x_1 < x < x_2$.
    - For $> 0$ or $\ge 0$: Select the regions above the x-axis, giving $x < x_1$ or $x > x_2$.

---

Worked Examples

Example 3: Solving a Quadratic Inequality

- **Question**: Find the range of values of $x$ for which $2x^2 - 4x - 3 > x$.
- **Step-by-Step Reasoning**:
    1. **Rearrange terms**: Subtract $x$ from both sides: $$2x^2 - 5x - 3 > 0$$
    2. **Factorise the quadratic**: $$(2x + 1)(x - 3) > 0$$
    3. **Identify critical values**: $x = -0.5$ and $x = 3$.
    4. **Sketch and apply sign analysis**: Since $a = 2 > 0$, the parabola is $\cup$-shaped. The inequality is strictly positive ($> 0$), so select the intervals outside the roots.
    5. **Final range**: $x < -0.5$ or $x > 3$.

Example 4: Simultaneous Quadratic Inequalities

- **Question**: Find the range of values of $x$ that satisfy both $x^2 + 2x < 0$ and $x^2 - x > 2$.
- **Step-by-Step Reasoning**:
    1. **Solve the first inequality**: $$x^2 + 2x < 0 \implies x(x + 2) < 0 \implies -2 < x < 0$$
    2. **Solve the second inequality**: $$x^2 - x - 2 > 0 \implies (x - 2)(x + 1) > 0 \implies x < -1 \quad \text{or} \quad x > 2$$
    3. **Intersect the solution intervals on a number line**:
        - Interval 1: $(-2, 0)$
        - Interval 2: $(-\infty, -1) \cup (2, \infty)$
        - The overlapping region is strictly between $-2$ and $-1$.
    4. **Combined Range**: $-2 < x < -1$.

---

Section 3: The Discriminant and Nature of Roots

- **The Discriminant**
    - **Discriminant**: The algebraic expression $D = b^2 - 4ac$ calculated from the coefficients of the quadratic equation $ax^2 + bx + c = 0$.
        - The sign of the discriminant determines the geometric relationship between the quadratic function and the horizontal axis.
- Nature of Roots
    - **Real and Distinct Roots**: Occurs when $b^2 - 4ac > 0$ (the curve intersects the x-axis at two distinct coordinate points).
    - **Real and Equal Roots**: Occurs when $b^2 - 4ac = 0$ (the curve touches the x-axis at exactly one point, meaning the x-axis is tangent to the vertex).
    - **No Real Roots**: Occurs when $b^2 - 4ac < 0$ (the curve has no x-intercepts and lies entirely above or entirely below the x-axis).
        - _Fine print_: If an exam states that an equation has **real roots**, you must use the combined inclusive inequality $b^2 - 4ac \ge 0$.
- Always Positive/Always Negative Quadratic Functions
    - **Definite Quadratics**: Quadratic functions that maintain the same positive or negative sign across all real inputs.
        - Key LaTeX formulas:
            - Always Positive: $a > 0$ and $b^2 - 4ac < 0$
            - Always Negative: $a < 0$ and $b^2 - 4ac < 0$

---

Worked Examples

Example 5: Roots showing for All Real Parameters

- **Question**: Show that the solutions of the equation $x^2 + kx = 3 - k$ are real and distinct for all real values of $k$.
- **Step-by-Step Reasoning**:
    1. **Express in standard form**: $$x^2 + kx + (k - 3) = 0$$
    2. **Evaluate the discriminant**: $$D = b^2 - 4ac = k^2 - 4(1)(k - 3) = k^2 - 4k + 12$$
    3. **Complete the square of the discriminant expression**: $$D = (k - 2)^2 - 4 + 12 = (k - 2)^2 + 8$$
    4. **Analyze the minimum value of** $D$: Since a squared term is always non-negative, $(k - 2)^2 \ge 0$ for all real values of $k$.
    5. **Evaluate inequality**: $$D = (k - 2)^2 + 8 \ge 8 > 0$$
    6. **Conclusion**: Since the discriminant $D$ is strictly greater than zero for all real $k$, the quadratic equation is guaranteed to have real and distinct roots.

Example 6: Bounded Optimization with Definite Quadratics

- **Question**: Find the range of values of the parameter $m$ for which the quadratic function $x^2 + 3mx + 9$ is strictly positive for all real values of $x$.
- **Step-by-Step Reasoning**:
    1. **State the positive definite conditions**: The lead coefficient $a$ must be positive, and the discriminant $D$ must be strictly negative.
    2. **Verify the lead coefficient**: $a = 1 > 0$ (satisfied).
    3. **Set up the discriminant inequality**: $$D = b^2 - 4ac < 0 \implies (3m)^2 - 4(1)(9) < 0$$ $$9m^2 - 36 < 0 \implies m^2 - 4 < 0$$
    4. **Solve the inequality**: $$(m - 2)(m + 2) < 0 \implies -2 < m < 2$$
    5. **Final range**: $-2 < m < 2$.

---

Section 4: Intersection of Line and Curve

- **Linear-Quadratic Intersections**
    - **Intersection Discriminant**: The discriminant of the single-variable quadratic equation formed by substituting a linear equation into a non-linear curve.
        - Key LaTeX formulas: For a combined quadratic equation $Ax^2 + Bx + C = 0$:
            - Line cuts curve at two distinct points: $b^2 - 4ac > 0$
            - Line is tangent to the curve: $b^2 - 4ac = 0$
            - Line does not intersect the curve: $b^2 - 4ac < 0$
        - If the line meets the curve, it implies both intersection or tangency, requiring $b^2 - 4ac \ge 0$.

---

Numbered Procedures

Procedural Topic: Determining Intersection Ranges

1. **Isolate Variable in Linear Equation**: Rearrange the linear equation to make either $y$ or $x$ the subject.
2. **Substitute**: Substitute this expression into the curve's non-linear equation to eliminate one variable.
3. **Express as Standard Quadratic**: Expand all terms and simplify to form the standard single-variable quadratic equation: $Ax^2 + Bx + C = 0$.
4. **Apply Discriminant Condition**: Calculate $D = B^2 - 4AC$ and apply the inequality corresponding to the requested intersection relationship (e.g., $<0$ for no intersection).
5. **Solve for the Parameter**: Solve the resulting inequality to find the allowed range of the parameter.

---

Worked Examples

Example 7: Finding Parameter Ranges for Line-Curve Cuts

- **Question**: The curve $x^2 - xy + y^2 = 1$ cuts the straight line $2x - y = k$ at two distinct points. Find the range of values of $k$.
- **Step-by-Step Reasoning**:
    1. **Isolate** $y$ **in the linear equation**: $$y = 2x - k$$
    2. **Substitute into the curve's equation**: $$x^2 - x(2x - k) + (2x - k)^2 = 1$$
    3. **Expand and collect terms**: $$x^2 - 2x^2 + kx + (4x^2 - 4kx + k^2) = 1$$ $$3x^2 - 3kx + (k^2 - 1) = 0$$
    4. **Identify coefficients**: $A = 3$, $B = -3k$, $C = k^2 - 1$.
    5. **Set up the discriminant for two distinct intersection points**: $$B^2 - 4AC > 0 \implies (-3k)^2 - 4(3)(k^2 - 1) > 0$$ $$9k^2 - 12(k^2 - 1) > 0 \implies 9k^2 - 12k^2 + 12 > 0$$ $$-3k^2 + 12 > 0 \implies 3k^2 < 12 \implies k^2 < 4$$
    6. **Solve for** $k$: $$(k - 2)(k + 2) < 0 \implies -2 < k < 2$$

---

⚠️ Common Mistakes on Exams

- **Sign Errors in Vieta's Sum of Roots**: Accidentally writing $\alpha+\beta = \frac{b}{a}$ instead of $-\frac{b}{a}$.
- **Treating Inequalities as Equations during Factorisation**: Attempting to solve $(x-3)(x+1) > 0$ by writing $x > 3$ or $x > -1$, instead of mapping the solution regions on a parabola graph to get the correct intervals.
- **Confusing Real Roots with Real and Distinct Roots**: Using the strict inequality $b^2 - 4ac > 0$ instead of the inclusive inequality $b^2 - 4ac \ge 0$ when an exam question states that the roots are simply "real".
- **Ignoring the Lead Coefficient in Definite Quadratics**: Forgetting to ensure that $a > 0$ when solving for a function that is "always positive" (which can lead to incorrect parameter ranges if $a$ is a variable expression).
- **Failing to Distribute Negative Signs in Substitutions**: When expanding substitutions like $(2x-k)^2$, failing to correctly calculate the middle term, resulting in $4x^2 + k^2$ instead of $4x^2 - 4kx + k^2$.

---

🔗 Cross-References

- **Vieta's Formulas** $\leftrightarrow$ **Simultaneous Equations (Chapter 2)**: Constructing quadratic equations from known root relationships is frequently used to solve simultaneous non-linear equations.
- **Quadratic Inequalities** $\leftrightarrow$ **Linear Inequalities (Chapter 6)**: Solving compound inequalities and finding overlapping solution intervals on a number line builds directly on Chapter 6 techniques.
- **Nature of Roots** $\leftrightarrow$ **Completed Square Form (Chapter 3)**: Completing the square is used both to prove discriminant properties (showing $D > 0$) and to find maximum/minimum points of quadratic functions.