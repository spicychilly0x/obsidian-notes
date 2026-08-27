# Chapter 2 Exam Notes: Simultaneous Linear & Non-Linear Equations

Section 1: Solving Simultaneous Linear Equations in Two Variables

- **Simultaneous Linear Equations**
    - **Simultaneous Linear Equations**: A set of two or more algebraic equations containing the same variables that are satisfied simultaneously by the same set of values1.
        - Geometrically, solving a system of two linear equations in two variables corresponds to finding the coordinates of the point where their straight-line graphs intersect on the Cartesian plane2.
- Algebraic Methods: Elimination and Substitution
    - **Elimination Method**: An algebraic procedure where equations are scaled and added or subtracted to eliminate one variable, leaving a single-variable linear equation1.
        - Always choose the variable with coefficients that can be easily matched by multiplying one or both equations by small integers1.
    - **Substitution Method**: An algebraic procedure where one equation is rearranged to express one variable in terms of the other, which is then substituted into the remaining equation1.
        - This is the most direct method when one of the variables in either equation already has a coefficient of $\pm 1$1.
- System Consistency and Solutions
    - **System Consistency**: The categorization of a linear system based on the number of shared coordinate solutions it possesses23.
        - There are three possible cases for any two linear equations on a plane:
            1. **Unique Solution**: The lines intersect at exactly one point (different gradients)2.
            2. **No Solution**: The lines are parallel (same gradient, different y-intercepts)3.
            3. **Infinitely Many Solutions**: The lines coincide (same gradient, same y-intercept)3.

---

Numbered Procedures

Procedural Topic: Solving Simultaneous Linear Equations (Algebraic)

1. **Select Method**: Inspect coefficients. If any variable has a coefficient of $\pm 1$, use **Substitution**1. If coefficients can be easily matched, use **Elimination**1.
2. **Isolate/Align**:
    - _For Substitution_: Rearrange one equation to express $y$ in terms of $x$ (i.e., $y = mx + c$) or vice versa1.
    - _For Elimination_: Multiply one or both equations by constants so that the coefficients of one variable are equal in magnitude1.
3. **Combine Equations**:
    - _For Substitution_: Replace the isolated variable in the other equation with its equivalent expression1.
    - _For Elimination_: Add the equations if the matched coefficients have opposite signs, or subtract them if they have the same sign1.
4. **Solve and Back-Substitute**: Solve the resulting single-variable equation, then substitute this value back into any original equation to find the second variable1.

---

Worked Examples

Example 1: Solving via Elimination (with Coefficient Alignment)

- **Question**: Solve the simultaneous equations: $$4x + 6y = 9 \quad \text{(1)}$$ $$3x - 2y = 10 \quad \text{(2)}$$
- **Step-by-Step Reasoning**:
    1. **Align coefficients**: Multiply equation (2) by $3$ to match the $y$-coefficient magnitude of equation (1): $$3 \times (3x - 2y = 10) \implies 9x - 6y = 30 \quad \text{(3)}$$
    2. **Eliminate** $y$: Add equation (1) and equation (3) because the coefficients of $y$ ($+6$ and $-6$) have opposite signs: $$(4x + 6y) + (9x - 6y) = 9 + 30 \implies 13x = 39$$
    3. **Solve for** $x$: $$x = \frac{39}{13} = 3$$
    4. **Back-substitute**: Substitute $x = 3$ into equation (1) to find $y$: $$4(3) + 6y = 9 \implies 12 + 6y = 9 \implies 6y = -3 \implies y = -0.5$$
    5. **Final Solution**: $(x, y) = (3, -0.5)$4.

Example 2: Finding Constant Coefficients from a Known Solution

- **Question**: If $(2,3)$ is the solution of the simultaneous equations: $$ax + by = 1$$ $$ay - bx = 8$$ Find the value of $a$ and of $b$5.
- **Step-by-Step Reasoning**:
    1. **Substitute the known coordinates**: Substitute $x = 2$ and $y = 3$ into both equations: $$2a + 3b = 1 \quad \text{(1)}$$ $$3a - 2b = 8 \quad \text{(2)}$$
    2. **Align coefficients**: Multiply equation (1) by $3$ and equation (2) by $2$: $$6a + 9b = 3 \quad \text{(3)}$$ $$6a - 4b = 16 \quad \text{(4)}$$
    3. **Eliminate** $a$: Subtract equation (4) from equation (3): $$(6a + 9b) - (6a - 4b) = 3 - 16 \implies 13b = -13 \implies b = -1$$
    4. **Solve for** $a$: Substitute $b = -1$ into equation (1): $$2a + 3(-1) = 1 \implies 2a - 3 = 1 \implies 2a = 4 \implies a = 2$$
    5. **Final Values**: $a = 2$, $b = -1$5.

---

Section 2: Solving Simultaneous Linear & Non-Linear Equations

- **Linear and Non-Linear Systems**
    - **Linear and Non-Linear System**: A system containing one linear equation (representing a straight line) and one non-linear equation (representing a curve, such as a quadratic circle or hyperbola)67.
        - Unlike purely linear systems, these can yield up to two distinct coordinate solutions, which correspond to the points where the line cuts or touches the curve67.
- Reciprocal Variable Simultaneous Equations
    - **Reciprocal Systems**: Simultaneous equations where variables appear in the denominators8.
        - These can be solved efficiently by treating the reciprocal terms (e.g., $\frac{1}{x}$ and $\frac{1}{y}$) as single variables during elimination, rather than cross-multiplying immediately8.

---

Numbered Procedures

Procedural Topic: Solving Linear & Non-Linear Systems

1. **Rearrange the Linear Equation**: Express one variable in terms of the other using the linear equation (never use the non-linear equation for this step)6.
2. **Substitute into the Non-Linear Equation**: Replace that variable in the non-linear equation with your new expression to form a single-variable quadratic equation6.
3. **Solve the Quadratic Equation**: Expand, collect like terms, and solve the quadratic equation using factorisation, completing the square, or the quadratic formula69.
4. **Find the Paired Coordinates**: Substitute the resulting values back into the _rearranged linear equation_ from Step 1 to calculate the corresponding values for the second variable6.
5. **Check Constraints**: Ensure none of your solutions violate denominator or real-world constraints (e.g., lengths must be positive)810.

---

Worked Examples

Example 3: Solving a Linear & Quadratic System

- **Question**: Solve the simultaneous equations: $$3x + y = 1 \quad \text{(1)}$$ $$x^2 + y^2 = 5 \quad \text{(2)}$$
- **Step-by-Step Reasoning**:
    1. **Rearrange linear equation**: Make $y$ the subject of equation (1): $$y = 1 - 3x \quad \text{(3)}$$
    2. **Substitute into non-linear equation**: Substitute (3) into equation (2): $$x^2 + (1 - 3x)^2 = 5$$
    3. **Expand and simplify**: $$x^2 + (1 - 6x + 9x^2) = 5$$ $$10x^2 - 6x - 4 = 0$$
    4. **Factorize**: Divide by $2$ to simplify: $$5x^2 - 3x - 2 = 0 \implies (5x + 2)(x - 1) = 0$$ $$x = -\frac{2}{5} \quad \text{or} \quad x = 1$$
    5. **Find paired** $y$**-values**: Substitute both $x$-values into equation (3):
        - If $x = 1 \implies y = 1 - 3(1) = -2$
        - If $x = -0.4 \implies y = 1 - 3(-0.4) = 2.2$
    6. **Final Coordinate Pairs**: $(1, -2)$ or $(-0.4, 2.2)$6.

Example 4: Reciprocal Variable Elimination

- **Question**: Solve the simultaneous equations: $$\frac{1}{x} + \frac{2}{y} = 3 \quad \text{(1)}$$ $$\frac{4}{x} - \frac{3}{y} = 2 \quad \text{(2)}$$
- **Step-by-Step Reasoning**:
    1. **Match coefficients of reciprocal terms**: Multiply equation (1) by $4$: $$\frac{4}{x} + \frac{8}{y} = 12 \quad \text{(3)}$$
    2. **Eliminate the** $\frac{4}{x}$ **term**: Subtract equation (2) from equation (3): $$\left(\frac{4}{x} + \frac{8}{y}\right) - \left(\frac{4}{x} - \frac{3}{y}\right) = 12 - 2 \implies \frac{11}{y} = 10$$
    3. **Solve for** $y$: $$y = \frac{11}{10} = 1.1$$
    4. **Solve for** $x$: Substitute $y = 1.1$ back into equation (1): $$\frac{1}{x} + \frac{2}{1.1} = 3 \implies \frac{1}{x} + \frac{20}{11} = 3 \implies \frac{1}{x} = 3 - \frac{20}{11} \implies \frac{1}{x} = \frac{13}{11}$$ $$x = \frac{11}{13}$$
    5. **Final Coordinate Pair**: $\left(\frac{11}{13}, 1.1\right)$8.

---

Section 3: Word Problems & Real-World Modeling

- Mathematical Modeling
    - **Mathematical Modeling**: The translation of real-world geometric, physical, or financial constraints into a system of simultaneous equations10more_horiz.
        - Always write down explicit variables representing physical quantities (e.g., let $x = \text{length}$, $y = \text{width}$) and construct relationships based on geometric formulas like Pythagoras' theorem, area, or perimeter10more_horiz.

---

Worked Examples

Example 5: Geometric Area and Perimeter Constraints

- **Question**: A rectangular piece of land with an area of $216 \text{ m}^2$ is enclosed by $60 \text{ m}$ of fencing. Calculate its dimensions11.
- **Step-by-Step Reasoning**:
    1. **Define variables**: Let the length be $x \text{ m}$ and the width be $y \text{ m}$11.
    2. **Formulate equations**:
        - Area constraint: $xy = 216 \quad \text{(1)}$
        - Perimeter constraint: $2x + 2y = 60 \implies x + y = 30 \implies x = 30 - y \quad \text{(2)}$11
    3. **Substitute and solve**: Substitute (2) into (1): $$(30 - y)y = 216 \implies 30y - y^2 = 216 \implies y^2 - 30y + 216 = 0$$
    4. **Factorize**: $$(y - 12)(y - 18) = 0 \implies y = 12 \quad \text{or} \quad y = 18$$
    5. **Determine dimensions**:
        - If $y = 12 \implies x = 30 - 12 = 18$
        - If $y = 18 \implies x = 30 - 18 = 12$
    6. **Final Answer**: The dimensions of the piece of land are $12 \text{ m} \times 18 \text{ m}$11.

Example 6: Modeling with Pythagoras' Theorem

- **Question**: A right-angled triangle has sides of length $(3x - 1) \text{ cm}$, $3x \text{ cm}$, and a hypotenuse of $(y + 1) \text{ cm}$. Given that the perimeter of the triangle is $70 \text{ cm}$, find the values of $x$ and $y$10.
- **Step-by-Step Reasoning**:
    1. **Formulate the linear perimeter equation**: $$(3x - 1) + 3x + (y + 1) = 70 \implies 6x + y = 70 \implies y = 70 - 6x \quad \text{(1)}$$
    2. **Formulate the non-linear Pythagoras equation**: $$(3x - 1)^2 + (3x)^2 = (y + 1)^2 \quad \text{(2)}$$
    3. **Substitute linear into non-linear**: Substitute (1) into (2), replacing $(y+1)$ with $(71 - 6x)$: $$(3x - 1)^2 + 9x^2 = (71 - 6x)^2$$
    4. **Expand and compile quadratic form**: $$(9x^2 - 6x + 1) + 9x^2 = 5041 - 852x + 36x^2$$ $$18x^2 - 6x + 1 = 36x^2 - 852x + 5041 \implies 18x^2 - 846x + 5040 = 0$$
    5. **Solve the quadratic**: Divide by $18$: $$x^2 - 47x + 280 = 0 \implies (x - 40)(x - 7) = 0 \implies x = 40 \quad \text{or} \quad x = 7$$
    6. **Evaluate and pair solutions**:
        - If $x = 40 \implies y = 70 - 6(40) = -170$ (Reject, as length $y+1 = -169$ cannot be negative)10.
        - If $x = 7 \implies y = 70 - 6(7) = 28$ (Accept, as all side lengths are positive)10.
    7. **Final Values**: $x = 7$, $y = 28$10.

---

⚠️ Common Mistakes on Exams

- **Failing to Distribute Binomial Squares**: When expanding substitutions like $(1-3x)^2$, writing $1 + 9x^2$ instead of $1 - 6x + 9x^2$6.
- **Incorrect Solution Pairing**: Listing final solutions as separate disconnected lists (e.g., "$x = 1, 9$ and $y = 1, 7$") instead of explicit coordinate pairs7. This causes errors when matched incorrectly.
- **Omitted Side-Length Constraint Verification**: Forgetting to reject negative values of $x$ or $y$ when they represent physical dimensions like perimeter or area, where negative lengths are impossible10.
- **Substituting into the Non-Linear Equation**: Back-substituting solved variable values into the quadratic/non-linear equation rather than the rearranged linear equation, which introduces redundant algebraic steps and dangerous extraneous solutions6.

---

🔗 Cross-References

- **Simultaneous Linear-Quadratic Systems** $\leftrightarrow$ **Quadratic Formula (Chapter 3)**: Solving non-linear simultaneous systems typically reduces to a single-variable quadratic equation solved via the quadratic formula613.
- **Simultaneous Solutions** $\leftrightarrow$ **Coordinate Geometry (Chapter 8)**: The coordinate solutions obtained algebraically are equivalent to the geometric points where graphs intersect on a coordinate plane2more_horiz.
- **Measurement Word Problems** $\leftrightarrow$ **Mensuration (Chapter 10)**: Real-world modeling constraints rely on solid and plane figure volume, surface area, and perimeter formulas10more_horiz.