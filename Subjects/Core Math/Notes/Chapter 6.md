# Chapter 6 Exam Notes: Linear Inequalities

---

Section 1: Properties of Inequalities

- **Inequality Relations**
    - **Law of Trichotomy**: For any two real numbers $a$ and $b$, exactly one of the following relations must hold: $a < b$, $a = b$, or $a > b$.
        - This establishes the ordering of real numbers on a one-dimensional number line.
    - **Transitive Property**: An algebraic property stating that if $a < b$ and $b < c$, then $a < c$ (and conversely, if $a > b$ and $b > c$, then $a > c$).
        - This allows the chaining of multiple inequalities to determine relative scale.
- **Inequality Operations**
    - **Addition and Subtraction of Real Numbers**: If $a < b$, then $a + c < b + c$ and $a - c < b - c$ for any real number $c$.
        - Adding or subtracting any real number preserves the direction of the inequality sign.
    - **Multiplication and Division Properties**: Algebraic rules where multiplying or dividing by a positive number preserves the sign, while multiplying or dividing by a negative number reverses the sign.
        - Key LaTeX formulas:
            - For positive multipliers ($c > 0$): $ac < bc$ and $\frac{a}{c} < \frac{b}{c}$
            - For negative multipliers ($c < 0$): $ac > bc$ and $\frac{a}{c} > \frac{b}{c}$
        - The sign change is mandatory whenever an inequality is scaled by any negative factor.

---

Section 2: Solving Linear Inequalities in One Unknown

- **Linear Inequalities**
    - **Linear Inequality**: A mathematical statement containing inequality symbols and first-degree variable terms.
        - The solution represents an interval of values rather than a discrete set.
    - **Number Line Representation**: Visualizing inequality solution intervals on a coordinate axis.
        - A hollow circle excludes the boundary point (strict inequality: $<$ or $>$), whereas a solid circle includes the boundary point (inclusive inequality: $\le$ or $\ge$).

---

Section 3: Solving Simultaneous Linear Inequalities

- **Simultaneous Linear Inequalities**
    - **Simultaneous Linear Inequalities**: A set of two or more inequalities that must be satisfied by the same variable concurrently.
        - The solution set is the overlapping (intersection) region of all individual solution sets.
    - **Compound Inequality Form**: Expressions of the form $a < x < b$.
        - By mathematical convention, compound inequalities must always be written in ascending order.

---

Section 4: Bounded Optimization & Word Problems

- **Extreme Value Calculations**
    - **Extreme Values**: The maximum or minimum limits of algebraic combinations of bounded independent variables.
        - To maximize $x - y$, select $x_{\text{max}}$ and $y_{\text{min}}$. To minimize $x - y$, select $x_{\text{min}}$ and $y_{\text{max}}$.
    - **Perfect Square Bounded Extremes**: Quadratic limits of bounded intervals.
        - If the variable range includes zero (e.g., $-3 \le x \le 7$), the minimum value of $x^2$ is always $0$.

---

Numbered Procedures

Procedural Topic: Solving a General Linear Inequality

1. **Clear Fractions and Parentheses**: Expand any brackets and multiply all terms by the Lowest Common Denominator (LCD) to eliminate fractional terms.
2. **Isolate Variable Terms**: Group all terms containing the variable on one side and constant terms on the opposite side by adding or subtracting terms.
3. **Divide by Coefficient**: Divide both sides of the inequality by the coefficient of the variable.
    - _Warning_: Reverse the inequality sign (flip $>$ to $<$, etc.) if the coefficient is negative.
4. **Represent Solution**: Write the final interval or plot it on a number line using hollow/solid circles.

Procedural Topic: Solving Simultaneous Linear Inequalities

1. **Solve Separately**: Solve each inequality independently to obtain individual solution intervals.
2. **Align on Number Line**: Sketch a single number line and draw both solution intervals above it, using proper hollow/solid circles.
3. **Identify Overlap**: Locate the region where the horizontal lines of the individual intervals overlap.
4. **Write Combined Interval**: Express the overlapping region as a compound inequality in ascending order (e.g., $a < x < b$). If no overlap exists, state "no real solution".

---

Worked Examples

Example 1: Solving a Linear Inequality with Negative Division

- **Question**: Solve the inequality $2 - (3x + 5) \ge 6(7 + 2x)$ and represent the solution on a number line.
- **Step-by-Step Reasoning**:
    1. **Expand brackets**: $$2 - 3x - 5 \ge 42 + 12x$$
    2. **Combine like terms on each side**: $$-3x - 3 \ge 42 + 12x$$
    3. **Isolate variables**: Subtract $12x$ and add $3$ to both sides: $$-15x \ge 45$$
    4. **Divide by negative coefficient and reverse sign**: Divide by $-15$ and flip the inequality sign from $\ge$ to $\le$: $$x \le -3$$
    5. **Graph representation**: Draw a solid circle at $-3$ on the number line with an arrow pointing to the left.

Example 2: Simultaneous Linear Inequalities

- **Question**: Find the integer values of $x$ for which $2x + 1 < 11$ and $4x - 3 \ge -7$.
- **Step-by-Step Reasoning**:
    1. **Solve first inequality**: $$2x + 1 < 11 \implies 2x < 10 \implies x < 5$$
    2. **Solve second inequality**: $$4x - 3 \ge -7 \implies 4x \ge -4 \implies x \ge -1$$
    3. **Combine to find overlapping region**: $$-1 \le x < 5$$
    4. **List integer values**: Select all integers starting from $-1$ up to (but excluding) $5$: $$x \in \{-1, 0, 1, 2, 3, 4\}$$

Example 3: Compound Split Inequality

- **Question**: Solve the linear inequalities: $3x - 5 < x + 3 \le 3x + 8$, listing the integer values of $x$.
- **Step-by-Step Reasoning**:
    1. **Split the compound inequality**: $$3x - 5 < x + 3 \quad \text{AND} \quad x + 3 \le 3x + 8$$
    2. **Solve the first part**: $$3x - 5 < x + 3 \implies 2x < 8 \implies x < 4$$
    3. **Solve the second part**: $$x + 3 \le 3x + 8 \implies -5 \le 2x \implies x \ge -2.5$$
    4. **Find overlap**: $$-2.5 \le x < 4$$
    5. **Extract integer values**: $$x \in \{-2, -1, 0, 1, 2, 3\}$$

Example 4: Extreme Values of Bounded Variables

- **Question**: Given that $x$ and $y$ are integers such that $-3 \le x \le 7$ and $-5 \le y \le -1$, find:
    - (i) the largest possible value of $2x - y$,
    - (ii) the smallest possible value of $x^2 + y^2$.
- **Step-by-Step Reasoning**:
    1. **Part (i) - Maximising a difference**:
        - To maximize $2x - y$, use the maximum value of $x$ and the minimum value of $y$.
        - From the bounds: $x_{\text{max}} = 7$ and $y_{\text{min}} = -5$.
        - Largest value $= 2(7) - (-5) = 14 + 5 = 19$.
    2. **Part (ii) - Minimising a sum of squares**:
        - To minimize $x^2 + y^2$, find the smallest possible values of $x^2$ and $y^2$.
        - Since the range $[-3, 7]$ contains $0$, the absolute minimum of $x^2$ occurs when $x = 0$, giving $x^2_{\text{min}} = 0^2 = 0$.
        - Since the range $[-5, -1]$ contains only negative numbers, the minimum of $y^2$ occurs at the boundary closest to zero ($y = -1$), giving $y^2_{\text{min}} = (-1)^2 = 1$.
        - Smallest value $= 0 + 1 = 1$.

Example 5: Quad-Coordinate Problem (Quadrant Constraint)

- **Question**: In a Cartesian plane, $P\left(\frac{k-3}{2}, \frac{1-2k}{3}\right)$ is a point located in the third quadrant. Find the range of values of the constant $k$.
- **Step-by-Step Reasoning**:
    1. **Define Quadrant constraints**: In the third quadrant, both the x-coordinate and y-coordinate must be strictly negative (less than 0).
    2. **Formulate x-coordinate inequality**: $$\frac{k-3}{2} < 0 \implies k - 3 < 0 \implies k < 3$$
    3. **Formulate y-coordinate inequality**: $$\frac{1-2k}{3} < 0 \implies 1 - 2k < 0 \implies 2k > 1 \implies k > 0.5$$
    4. **Find common range**: Intersect $k < 3$ and $k > 0.5$: $$0.5 < k < 3$$

Example 6: Real-World Word Problem Modeling

- **Question**: Daniel answered $3n$ questions in a competition. Correct answers score 3 marks, incorrect answers lose 1 mark, and unanswered questions score 0. Daniel answered $2n+5$ questions correctly and answered all of his $3n$ questions. If his score was between 45 and 55 marks (exclusive), find the integer value of $n$.
- **Step-by-Step Reasoning**:
    1. **Define correct and incorrect quantities**:
        - Correct answers $= 2n+5$.
        - Incorrect answers $= 3n - (2n+5) = n-5$.
    2. **Formulate total score expression**: $$\text{Score} = 3(2n + 5) - 1(n - 5) = 6n + 15 - n + 5 = 5n + 20$$
    3. **Set up compound inequality**: $$45 < 5n + 20 < 55$$
    4. **Solve for** $n$:
        - Subtract 20: $25 < 5n < 35$
        - Divide by 5: $5 < n < 7$
    5. **Find integer value**: Since $n$ must be an integer (as the number of questions $3n$ is discrete), the only possible value is $n = 6$.

---

⚠️ Common Mistakes on Exams

- **Forgetting to Reverse the Inequality Sign**: Failing to flip the inequality sign when multiplying or dividing both sides by a negative number (e.g., keeping $-2x < 6$ as $x < -3$ instead of reversing it to $x > -3$).
- **Squaring Bounded Ranges Incorrectly**: Assuming that if $-3 \le x \le 7$, then $9 \le x^2 \le 49$. The actual range for $x^2$ is $0 \le x^2 \le 49$ since $x = 0$ is within the interval.
- **Incorrect Extreme Value Pairings**: Selecting the maximum boundaries of both variables when calculating the minimum of a difference (e.g., using $x_{\text{max}} - y_{\text{max}}$ to find the minimum of $x-y$, instead of $x_{\text{min}} - y_{\text{max}}$).
- **Omitting Strict Inequalities in Quadrant Boundaries**: Using $\le$ instead of strict $<$ when dealing with points on quadrants (points on the axes where $x=0$ or $y=0$ do not belong to any quadrant).
- **Failing to Check Integer Discreteness**: Giving final answers to word problems as decimal ranges (e.g., leaving $5 < n < 7$ as the answer instead of stating the unique integer $n = 6$).

---

🔗 Cross-References

- **Quadrants and Coordinate Inequalities** $\leftrightarrow$ **Coordinate Geometry (Chapter 8)**: Finding coordinate regions (such as quadrant positions) using simultaneous inequalities is a prerequisite for mapping linear lines and geometric regions on a Cartesian grid.
- **Properties of Inequalities** $\leftrightarrow$ **Quadratic Inequalities (Chapter 7)**: Solving quadratic inequalities relies directly on factoring quadratic expressions and applying linear sign tests to define valid solution intervals.
- **Word Problems** $\leftrightarrow$ **Mensuration (Chapter 10)**: Real-world modeling optimization problems (such as finding the limits of volume, area, or lengths) use linear inequalities combined with geometric mensuration formulas.