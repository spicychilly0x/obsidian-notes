# Chapter 3 Exam Notes: Solutions to Quadratic Equations

---

Section 1: Solving Quadratic Equations by Completing the Square

- **Quadratic Equations**
    - **Quadratic Equation**: An equation that can be written in the form $ax^2 + bx + c = 0$, where $a$, $b$, and $c$ are real numbers and a =/ 0 .
        - To solve a quadratic equation means to find the values of the unknown variable, which are called the **roots** (or solutions) of the equation1.
- **Completing the Square**
    - **Completing the Square**: An algebraic process of adding a constant term to a quadratic expression of the form $x^2 + bx$ so that it becomes a perfect square trinomial1.
        - Key LaTeX formula: $$x^2 + bx + \left(\frac{b}{2}\right)^2 = \left(x + \frac{b}{2}\right)^2$$
        - The constant term that must be added is always the square of half the coefficient of $x$ (i.e., $\left(\frac{b}{2}\right)^2$)1.

---

Numbered Procedures

Procedural Topic: Solving $ax^2 + bx + c = 0$ by Completing the Square

1. **Check Lead Coefficient**: Verify if the coefficient of $x^2$ (the value $a$) is equal to $1$2.
    - If $a \neq 1$, divide every term in the equation by $a$ to obtain $x^2 + \frac{b}{a}x + \frac{c}{a} = 0$2.
2. **Isolate Constant Term**: Move the constant term to the Right-Hand Side (RHS) of the equation: $x^2 + \frac{b}{a}x = -\frac{c}{a}$2.
3. **Add Perfect Square Constant**: Add the square of half the $x$-coefficient, $\left(\frac{b}{2a}\right)^2$, to both sides of the equation2.
4. **Factor and Solve**: Express the Left-Hand Side (LHS) as a perfect square: $\left(x + \frac{b}{2a}\right)^2 = -\frac{c}{a} + \left(\frac{b}{2a}\right)^2$2. Take the square root on both sides (incorporating a $\pm$ sign) and isolate $x$ to find the roots2.

---

Worked Examples

Example 1: Solving $2x^2 - 3x - 7 = 0$ (Lead Coefficient $a \neq 1$)

- **Question**: Solve $2x^2 - 3x - 7 = 0$ completely using completing the square, giving answers to 2 decimal places2.
- **Step-by-Step Reasoning**:
    1. **Divide by the coefficient of** $x^2$: $$x^2 - \frac{3}{2}x - \frac{7}{2} = 0$$
    2. **Move the constant to the RHS**: $$x^2 - \frac{3}{2}x = \frac{7}{2}$$
    3. **Add** $\left(\frac{b}{2}\right)^2$ **to both sides**: Here, $b = -\frac{3}{2}$, so $\frac{b}{2} = -\frac{3}{4}$. Add $\left(-\frac{3}{4}\right)^2 = \frac{9}{16}$: $$x^2 - \frac{3}{2}x + \frac{9}{16} = \frac{7}{2} + \frac{9}{16}$$
    4. **Simplify and factorize**: $$\left(x - \frac{3}{4}\right)^2 = \frac{56}{16} + \frac{9}{16} = \frac{65}{16}$$
    5. **Take the square root of both sides**: $$x - \frac{3}{4} = \pm\sqrt{\frac{65}{16}} = \pm\frac{\sqrt{65}}{4}$$ $$x = \frac{3 \pm \sqrt{65}}{4}$$
    6. **Calculate decimal values**:
        - $x \approx 2.77$ (to 2 d.p.)
        - $x \approx -1.27$ (to 2 d.p.)

---

Section 2: Quadratic Formula & Fractional Equations

- **The Quadratic Formula**
    - **The Quadratic Formula**: A general formula derived by completing the square that provides the algebraic solutions of any quadratic equation in the form $ax^2 + bx + c = 0$3.
        - Key LaTeX formula: $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
        - The constant $a$ cannot be equal to $0$3.
- **The Discriminant and Nature of Roots**
    - **Discriminant**: The expression $b^2 - 4ac$ located under the square root symbol of the quadratic formula, which dictates the number and type of solutions3.
        - **Two Real and Distinct Roots**: Occurs when $b^2 - 4ac > 0$ (the curve has two distinct x-intercepts)3.
        - **One Real and Equal Root**: Occurs when $b^2 - 4ac = 0$ (the curve is tangent to the x-axis)3.
        - **No Real Roots**: Occurs when $b^2 - 4ac < 0$ (the curve has no points of intersection with the x-axis)3.
- **Fractional Equations**
    - **Fractional Equation**: An algebraic equation containing the unknown variable in the denominator of one or more of its fractional terms3.
        - Fractional equations are solved by multiplying all terms by the Lowest Common Denominator (LCD) to clear fractions and reduce the expression to a standard quadratic equation3.

---

Numbered Procedures

Procedural Topic: Solving Fractional Equations

1. **Identify Denominators & LCD**: Determine the denominators of all fractional terms and find their LCD3.
2. **Clear Fractions**: Multiply both sides of the entire equation by the LCD to eliminate all denominators3.
3. **Expand and Group**: Expand all brackets, gather terms on one side of the equation, and combine like terms3.
4. **Solve standard quadratic**: Form the general quadratic equation $ax^2 + bx + c = 0$ and solve using factorisation, completing the square, or the quadratic formula3.
5. **Exclusion check**: Check your roots against the original denominators; reject any solved value that causes division by zero, as it is an extraneous solution3.

---

Worked Examples

Example 2: Solving Fractional Equations

- **Question**: Solve the equation $\frac{2}{x-3} + \frac{1}{x+1} = 5$ completely, giving your answers correct to 2 decimal places3.
- **Step-by-Step Reasoning**:
    1. **Clear denominators**: Multiply the entire equation by the LCD, which is $(x-3)(x+1)$3: $$2(x+1) + 1(x-3) = 5(x-3)(x+1)$$
    2. **Expand both sides**: $$2x + 2 + x - 3 = 5(x^2 - 2x - 3)$$ $$3x - 1 = 5x^2 - 10x - 15$$
    3. **Rearrange into general form**: $$5x^2 - 13x - 14 = 0$$
    4. **Apply the Quadratic Formula**: Here, $a = 5$, $b = -13$, $c = -14$3: $$x = \frac{-(-13) \pm \sqrt{(-13)^2 - 4(5)(-14)}}{2(5)}$$ $$x = \frac{13 \pm \sqrt{169 + 280}}{10} = \frac{13 \pm \sqrt{449}}{10}$$
    5. **Compute final solutions**:
        - $x = \frac{13 + 21.1896}{10} \approx 3.42$ (to 2 d.p.)
        - $x = \frac{13 - 21.1896}{10} \approx -0.82$ (to 2 d.p.)
    6. **Verify constraints**: Neither $3.42$ nor $-0.82$ make the original denominators $(x-3)$ or $(x+1)$ equal to zero. Both solutions are valid.

---

Section 3: Graphs & Properties of Quadratic Functions

- **Quadratic Graphs (Parabolas)**
    - **Parabola**: A smooth, symmetrical U-shaped or $\cap$-shaped curve representing a quadratic function4.
        - If the coefficient $a > 0$, the parabola is U-shaped and features a **minimum point**5. If $a < 0$, the parabola is $\cap$-shaped and features a **maximum point**5.
- **Completed Square Form**
    - **Completed Square Form**: A quadratic function written in the form $y = a(x-h)^2 + k$, which explicitly identifies the vertex of the curve5.
        - Key LaTeX formula: $$y = a(x-h)^2 + k$$
        - The vertex or **turning point** of the parabola is located at coordinates $(h, k)$, and the vertical line of symmetry is the line $x = h$5.
- **Alternative Quadratic Forms**
    - **Factorised Form**: A quadratic function written in terms of its horizontal intercepts as $y = a(x-b)(x-c)$5.
        - The curve intersects the x-axis at x-intercept points $x = b$ and $x = c$, and its vertical axis of symmetry is located exactly halfway between them: $x = \frac{b+c}{2}$5.
    - **General Form**: A quadratic function written as $y = ax^2 + bx + c$5.
        - The vertical axis of symmetry is located at $x = -\frac{b}{2a}$5.

---

Numbered Procedures

Procedural Topic: Sketching a Parabola from Completed Square Form $y = a(x-h)^2+k$

1. **Analyze Orientation**: Check the sign of $a$5. If $a > 0$, it is a minimum curve ($\cup$); if $a < 0$, it is a maximum curve ($\cap$)5.
2. **Locate Turning Point**: Identify the coordinates of the turning point $(h, k)$ directly from the function terms5.
3. **Calculate y-intercept**: Substitute $x = 0$ into the equation to calculate the y-intercept: $y_{\text{int}} = ah^2 + k$5.
4. **Find x-intercepts (if any)**: Set $y = 0$ and solve for $x$ to locate x-intercepts5.
5. **Plot & Label**: Draw a smooth, symmetrical parabola passing through the calculated intercepts and turning point. Clearly label the axes, turning point, and axis of symmetry5.

---

Worked Examples

Example 3: Sketching a Parabola from Completed Square Form

- **Question**: Express $y = 14 - 3x - x^2$ in completed square form, identify the coordinates of its turning point, and state whether it is a maximum or minimum6.
- **Step-by-Step Reasoning**:
    1. **Rearrange terms**: $$y = -x^2 - 3x + 14$$
    2. **Factor out the negative sign from the variable terms**: $$y = -\left(x^2 + 3x\right) + 14$$
    3. **Complete the square inside the bracket**: Half of $3$ is $1.5$, so add and subtract $1.5^2 = 2.25$6: $$y = -\left[\left(x + \frac{3}{2}\right)^2 - \frac{9}{4}\right] + 14$$
    4. **Distribute the negative sign and simplify**: $$y = -\left(x + 1.5\right)^2 + 2.25 + 14$$ $$y = 16.25 - \left(x + 1.5\right)^2$$
    5. **Identify curve properties**:
        - Since the coefficient of the squared term is negative ($a = -1$), the parabola has a **maximum value**6.
        - The maximum value is $16.25$ and occurs at $x = -1.5$6.
        - The coordinates of the turning point are $(-1.5, 16.25)$6.

---

Section 4: Real-World Modeling with Quadratic Functions

- **Quadratic Modeling**
    - **Quadratic Modeling**: Representing real-world phenomena (e.g., projectile trajectories, structural arches, and financial profit margins) using quadratic functions7.
        - Real-world boundaries dictate that some mathematical solutions must be rejected (for example, negative values when calculating physical lengths, widths, or times)7.

---

Worked Examples

Example 4: Bridge Arch Architectural Model

- **Question**: A curved arch that supports a bridge can be modeled by a quadratic function. The arch is $120\text{ m}$ wide at its base and $50\text{ m}$ high in the middle7.
    - (i) Write a quadratic function in the form $y = a(x-p)(x-q)$ representing the arch7.
    - (ii) Find the height of the arch at a point $10\text{ m}$ horizontally from its starting point7.
- **Step-by-Step Reasoning**:
    1. **Identify intercepts**: If the starting point is at the origin $(0,0)$, then the base ends at $120\text{ m}$. The x-intercepts are $p = 0$ and $q = 120$7. $$y = ax(x-120)$$
    2. **Identify the vertex**: The peak height of $50\text{ m}$ is reached in the middle, at $x = \frac{120}{2} = 60\text{ m}$. This gives vertex coordinates of $(60, 50)$7.
    3. **Solve for constant** $a$: Substitute $(60, 50)$ into the function7: $$50 = a(60)(60 - 120)$$ $$50 = a(60)(-60) \implies 50 = -3600a$$ $$a = -\frac{50}{3600} = -\frac{1}{72}$$ The function is: $y = -\frac{1}{72}x(x-120)$7.
    4. **Find the height at** $x = 10\text{ m}$: Substitute $x = 10$ into the model7: $$y = -\frac{1}{72}(10)(10 - 120)$$ $$y = -\frac{10(-110)}{72} = \frac{1100}{72} = 15\frac{5}{18}\text{ m} \approx 15.28\text{ m}$$

---

⚠️ Common Mistakes on Exams

- **Sign errors inside perfect square brackets**: Mistakenly writing $\left(x - \frac{b}{2}\right)^2$ instead of $\left(x + \frac{b}{2}\right)^2$ when the $x$-coefficient $b$ is positive8.
- **Incomplete division in the Quadratic Formula**: Writing $x = -b \pm \frac{\sqrt{b^2 - 4ac}}{2a}$ instead of dividing the entire expression by $2a$ (i.e., $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$)8.
- **Neglecting the constant term during fraction clearance**: In fractional equations, multiplying only the fractions by the LCD while forgetting to multiply the integer constants (e.g., multiplying only the terms on the LHS of $\frac{2}{x-3} + \frac{1}{x+1} = 5$ and leaving the RHS as $5$ instead of $5(x-3)(x+1)$)3.
- **Sign inversion in Completed Square Form turning points**: Stating that the turning point of $y = a(x-h)^2 + k$ is $(-h, k)$ instead of $(h, k)$ (e.g., interpreting $y = (x+3)^2 - 1$ as having turning point $(3, -1)$ rather than $(-3, -1)$)5.
- **Failing to test and reject extraneous solutions**: Forgetting to check if your solved roots make any of the original denominators in a fractional equation equal to zero (which makes the terms undefined and requires the root to be rejected)3.

---

🔗 Cross-References

- **Discriminant (Chapter 3)** $\leftrightarrow$ **Quadratic Inequalities (Chapter 7)**: The discriminant condition $b^2 - 4ac < 0$ helps determine whether quadratic functions are "always positive" or "always negative" in quadratic inequalities.
- **Roots of Quadratic Equations (Chapter 3)** $\leftrightarrow$ **Linear & Non-Linear Simultaneous Equations (Chapter 2)**: Substituting linear equations into quadratic non-linear curves yields single-variable quadratic equations, where the solutions (roots) represent the geometric coordinates of their intersection points.
- **Completing the Square (Chapter 3)** $\leftrightarrow$ **Algebraic Identities (Chapter 1)**: Completing the square relies directly on utilizing the perfect square identities $(a \pm b)^2 = a^2 \pm 2ab + b^2$ in reverse order to transform quadratic expressions into vertex form.