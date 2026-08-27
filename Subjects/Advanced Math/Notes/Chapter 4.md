# Chapter 4 Exam Notes

Topic 4: Relations & Functions

---

1. Core Concept: Functions & Mappings

- Core Concept: **Algebraic Function**
    - Key Definition: A **function** is defined as a relation in which every element in the domain has a unique image in the range (meaning it is either a 1-to-1 or a many-to-1 relation).
        - _Detail/Fine Print_: If an input maps to more than one output (1-to-many), the relation is not a function. You can verify this using the **Vertical Line Test**: if any vertical line $x = a$ intersects the graph more than once, the graph does not represent a function.
- Core Concept: **One-to-One Function**
    - Key Definition: A **one-to-one function** (or **injective function**) is a function in which each element in the range is mapped from exactly one unique element in the domain.
        - _Detail/Fine Print_: To test if a function is one-to-one, apply the **Horizontal Line Test**: if any horizontal line $y = b$ cuts the graph at more than one point, the function is many-to-one (e.g., quadratics $y = ax^2+bx+c$), not one-to-one.
- Core Concept: **Domain and Range Restrictions**
    - Key Definition: The **domain** is the complete set of valid input values ($x$-values) for which the function is defined, while the **range** is the set of all possible output values ($y$-values) yielded by those inputs.
        - _Detail/Fine Print_: You must exclude values from the domain that cause division by zero (such as $x = a$ in $f(x) = \frac{1}{x-a}$) or negative values under an even radical (such as $x < a$ in $f(x) = \sqrt{x-a}$).

---

2. Core Concept: Composite Functions

- Core Concept: **Function Composition**
    - Key Definition: A **composite function** $gf(x)$ (or $g(f(x))$) represents a two-step mapping where the output of the inner function $f(x)$ becomes the direct input for the outer function $g(x)$.
        - _Detail/Fine Print_: Composition is non-commutative, meaning $gf(x) \neq fg(x)$ in general. Additionally, $f^2(x)$ denotes $f(f(x))$, which is entirely different from the square of the function $(f(x))^2$.
- Core Concept: **Existence Condition for Composite Functions**
    - Key Formula: The composite function $gf(x)$ exists if and only if the range of the inner function $f$ is a subset of the domain of the outer function $g$: $$R_f \subseteq D_g$$
        - _Detail/Fine Print_: If the range of the inner function contains any value that lies outside the domain of the outer function, the composite function is undefined for those inputs.

---

3. Core Concept: Inverse Functions

- Core Concept: **Inverse Function Definition**
    - Key Definition: An **inverse function** $f^{-1}(x)$ is a function that reverses the original mapping, sending each output $y$ back to its unique corresponding input $x$.
        - _Detail/Fine Print_: An inverse function $f^{-1}(x)$ exists **if and only if** the original function $f(x)$ is a **one-to-one function**. Many-to-one functions (e.g., quadratics) do not have an inverse unless their domain is restricted (such as restricting $y = x^2$ to $x \ge 0$).
- Core Concept: **Swapping Domains and Ranges**
    - Key Formula: The domain and range of a function and its inverse are swapped: $$D_{f^{-1}} = R_f \quad \text{and} \quad R_{f^{-1}} = D_f$$
        - _Detail/Fine Print_: When sketching the graphs, the graph of $y = f^{-1}(x)$ is the reflection of the graph of $y = f(x)$ across the identity line $y = x$. Any points of intersection between $f(x)$ and $f^{-1}(x)$ must lie on $y = x$.

---

4. Core Concept: Absolute Value Functions

- Core Concept: **Absolute Value (Modulus)**
    - Key Definition: The **absolute value** (or **modulus**) of a real number $x$, denoted by $|x|$, represents its non-negative magnitude: $$|x| = \begin{cases} x, & \text{if } x \ge 0 \\ -x, & \text{if } x < 0 \end{cases}$$
        - _Detail/Fine Print_: The graph of a standard modulus function $y = a|x-h| + k$ forms a V-shape with a sharp turning point (vertex) at $(h, k)$. The range is $y \ge k$ if $a > 0$, and $y \le k$ if $a < 0$.
- Core Concept: **Modulus Inequalities**
    - Key Formula: Modulus inequalities can be solved by converting them to compound inequalities: $$|x| \le a \iff -a \le x \le a$$ $$|x| \ge a \iff x \ge a \quad \text{or} \quad x \le -a$$
        - _Detail/Fine Print_: If $a$ is a variable expression (e.g., $g(x)$), you must verify all solutions because absolute value is strictly non-negative.

---

5. Core Concept: Graph Transformations

- Core Concept: **Translations**
    - Key Formula: Horizontal and vertical shifts are represented as: $$y = f(x) \pm b \implies \text{Vertical translation up/down by } b \text{ units}$$ \[y = f(x \pm a) \implies \text{Horizontal translation left/right by } a \text{ units}]
        - _Detail/Fine Print_: Note the sign difference in horizontal shifts: $f(x+a)$ translates the graph to the **left** by $a$ units, whereas $f(x-a)$ translates it to the **right** by $a$ units.
- Core Concept: **Reflections**
    - Key Formula: Reflections across coordinate axes are represented as: $$y = -f(x) \implies \text{Reflection in the } x\text{-axis}$$ $$y = f(-x) \implies \text{Reflection in the } y\text{-axis}$$
        - _Detail/Fine Print_: A reflection in the $x$-axis negates all $y$-coordinates, while a reflection in the $y$-axis negates all $x$-coordinates.
- Core Concept: **Stretching**
    - Key Formula: Stretching or compressing along coordinate axes are represented as: $$y = p \cdot f(x) \implies \text{Vertical stretch by factor of } p \text{ parallel to the } y\text{-axis}$$ $$y = f(kx) \implies \text{Horizontal stretch by factor of } \frac{1}{k} \text{ parallel to the } x\text{-axis}$$
        - _Detail/Fine Print_: For horizontal stretching, if $k > 1$, the graph is **compressed** horizontally by a scale factor of $\frac{1}{k}$. If $0 < k < 1$, the graph is stretched horizontally.

---

🛠️ Numbered Procedures

Procedure 1: Finding an Algebraic Inverse Function $f^{-1}(x)$

1. Set the function equal to $y$: $y = f(x)$.
2. Rearrange the equation to make $x$ the subject of the formula (i.e., express $x$ in terms of $y$).
3. Replace the variable $x$ with $f^{-1}(x)$ and replace all instances of $y$ with $x$.
4. State any domain restrictions on $f^{-1}(x)$, remembering that $D_{f^{-1}} = R_f$.

Procedure 2: Solving Modulus Equations $|f(x)| = g(x)$

1. Split the equation into two separate cases: $f(x) = g(x)$ and $f(x) = -g(x)$.
2. Solve both equations independently to find potential values of $x$.
3. **CRITICAL STEP**: Substitute all potential values back into the original equation $|f(x)| = g(x)$.
4. Reject any extraneous solutions (especially those where the output $g(x)$ would be negative, which violates the non-negative property of the modulus).
5. State the final valid solutions.

---

📝 Worked Examples per Question Type

Type 1: Finding Domain Restrictions (Excluded Values)

- **Question**: State the values of $x$ that must be excluded from the domain of the function $h(x) = \frac{5}{x^2 + x - 6}$.
- **Step-by-Step Solution**:
    1. Identify the restriction: The denominator of a fraction cannot equal zero. Set the denominator to zero: $$x^2 + x - 6 = 0$$
    2. Factorise the quadratic expression: $$(x+3)(x-2) = 0$$
    3. Solve for $x$: $$x = -3 \quad \text{or} \quad x = 2$$
    4. State the excluded values: The values of $x$ that must be excluded from the domain are $x = -3$ and $x = 2$.

Type 2: Finding Expressions for Composite Functions

- **Question**: Given $f(x) = 1 + 2x$ and $g(x) = \frac{x}{x-1}$ where $x \neq 1$, find the expression for the composite function $gf(x)$ and state its domain restriction.
- **Step-by-Step Solution**:
    1. Write the composite function expression: $$gf(x) = g(f(x))$$
    2. Substitute the expression for $f(x)$ into $g$: $$gf(x) = g(1+2x) = \frac{1+2x}{(1+2x) - 1}$$
    3. Simplify the denominator: $$gf(x) = \frac{1+2x}{2x}$$
    4. Identify domain restrictions: The denominator cannot be zero, so $2x \neq 0 \implies x \neq 0$. Additionally, from the inner function, $x$ has no restrictions. Thus, the restriction is $x \neq 0$.

Type 3: Repeated Composite Functions (Self-Composition)

- **Question**: Given $f(x) = \frac{2x}{x-1}$ where $x \neq 1$, find the expression for $f^2(x)$.
- **Step-by-Step Solution**:
    1. Write out the composition: $$f^2(x) = f(f(x)) = f\left(\frac{2x}{x-1}\right)$$
    2. Substitute $f(x)$ back into the function: $$f^2(x) = \frac{2\left(\frac{2x}{x-1}\right)}{\left(\frac{2x}{x-1}\right) - 1}$$
    3. Clear the fractions by multiplying the numerator and denominator by $(x-1)$: $$f^2(x) = \frac{4x}{2x - (x-1)} = \frac{4x}{x+1}$$
    4. State restrictions: $x \neq \pm 1$ (from the inner domain restriction $x \neq 1$ and the final denominator restriction $x \neq -1$).

Type 4: Algebraically Finding Inverse Functions

- **Question**: Find the inverse function $f^{-1}(x)$ for $f(x) = \frac{2x+3}{x-1}$ where $x \neq 1$.
- **Step-by-Step Solution**:
    1. Let $y = \frac{2x+3}{x-1}$.
    2. Multiply both sides by $(x-1)$ to isolate $x$: $$y(x-1) = 2x + 3 \implies xy - y = 2x + 3$$
    3. Move all terms containing $x$ to one side and other terms to the opposite side: $$xy - 2x = y + 3$$
    4. Factorise $x$ on the left-hand side: $$x(y-2) = y + 3$$
    5. Divide to solve for $x$: $$x = \frac{y+3}{y-2}$$
    6. Express the final inverse function by replacing $x$ with $f^{-1}(x)$ and $y$ with $x$: $$f^{-1}(x) = \frac{x+3}{x-2} \quad \text{where } x \neq 2$$

Type 5: Solving Modulus Equations with Extraneous Solutions

- **Question**: Solve the equation $|x+1| = 2x - 3$.
- **Step-by-Step Solution**:
    1. Split the equation into two cases:
        - **Case 1**: $x + 1 = 2x - 3 \implies x = 4$
        - **Case 2**: $x + 1 = -(2x - 3) \implies x + 1 = -2x + 3 \implies 3x = 2 \implies x = \frac{2}{3}$
    2. Verify solutions in the original equation:
        - For $x = 4$: $$\text{LHS} = |4+1| = 5, \quad \text{RHS} = 2(4)-3 = 5 \quad (\text{Valid})$$
        - For $x = \frac{2}{3}$: $$\text{LHS} = \left|\frac{2}{3}+1\right| = \frac{5}{3}, \quad \text{RHS} = 2\left(\frac{2}{3}\right)-3 = -\frac{5}{3}$$ Since $\frac{5}{3} \neq -\frac{5}{3}$, this root is extraneous.
    3. Reject $x = \frac{2}{3}$. The only valid solution is $x = 4$.

Type 6: Applying Graph Transformations in Sequence

- **Question**: The graph of $y = 2x^2 + 4x + 7$ undergoes a horizontal translation of 2 units in the positive $x$-direction, followed by a vertical translation of 1 unit in the negative $y$-direction. Find the equation of the transformed graph in standard form.
- **Step-by-Step Solution**:
    1. First, apply the horizontal translation of $+2$ units by replacing all instances of $x$ with $(x-2)$: $$y_1 = 2(x-2)^2 + 4(x-2) + 7$$
    2. Next, apply the vertical translation of $-1$ unit by subtracting 1 from the entire expression: $$y_2 = 2(x-2)^2 + 4(x-2) + 7 - 1$$
    3. Expand the terms: $$y_2 = 2(x^2 - 4x + 4) + 4x - 8 + 6$$ $$y_2 = 2x^2 - 8x + 8 + 4x - 2$$
    4. Combine like terms to express the final equation: $$y_2 = 2x^2 - 4x + 6$$

---

⚠️ Common Mistakes Students Make on Exams

- **Forgetting to Check for Extraneous Solutions**: Neglecting to plug solved roots back into modulus equations. Roots that make the non-modulus side negative must be rejected.
- **Assuming Composite Commutativity**: Mistakenly assuming that $gf(x) = fg(x)$ or writing $f^2(x)$ as $(f(x))^2$ instead of $f(f(x))$.
- **Horizontal Translation Sign Error**: Translating to the right by adding to $x$ (e.g., writing $f(x+a)$ instead of $f(x-a)$). Remember that $f(x-a)$ moves the graph in the positive $x$-direction.
- **Attempting to Invert Many-to-One Functions**: Finding an algebraic inverse formula for a quadratic or modulus function without restricting its domain. Inverses are only valid for strictly one-to-one functions.

---

🔗 Cross-References to Related Concepts

- **Topic 1: Algebraic Fractions**: The algebraic manipulations used to find composite and inverse formulas rely directly on simplifying algebraic fractions.
- **Topic 3: Rational Functions**: Denominator restrictions in domains correspond directly to vertical asymptotes of rational functions.
- **Topic 5: Logarithmic & Exponential Graphs**: Exponential functions $y = e^x$ and natural logarithmic functions $y = \ln x$ are inverses of each other, reflecting perfectly across the line $y = x$.