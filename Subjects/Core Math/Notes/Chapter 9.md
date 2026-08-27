# Chapter 9 Exam Notes: Graphs of Functions & Graphical Solutions

---

Section 1: Types of Functions and Their Graphs

- **Cubic Functions**
    - **Cubic Function**: A polynomial function of the third degree, written in the general form $y = ax^3 + bx^2 + cx + d$, where $a, b, c, d$ are real numbers and the lead coefficient $a \neq 0$.
        - The orientation of the curve depends strictly on the sign of the lead coefficient $a$:
            - If $a > 0$, the graph starts at the bottom-left and rises to the top-right (e.g., $y = x^3$ passes through coordinates $(-1, -1)$, $(0,0)$, and $(1,1)$).
            - If $a < 0$, the graph starts at the top-left and falls to the bottom-right (e.g., $y = -x^3$ passes through coordinates $(-1, 1)$, $(0,0)$, and $(1,-1)$).
- **Reciprocal Functions**
    - **Reciprocal Function**: A rectangular hyperbolic function of the form $y = \frac{a}{x}$ or $y = \frac{a}{x^2}$, where $a$ is a non-zero real constant.
        - These functions are undefined at the vertical line $x = 0$, meaning they have no y-intercept.
        - **Asymptote**: A straight line that a curve approaches infinitely closely but never actually touches or intersects. For basic reciprocal curves, the asymptotes are the axes $x = 0$ and $y = 0$.
        - Behavior of $y = \frac{a}{x}$:
            - If $a > 0$, the symmetric curves are located in Quadrants 1 and 3.
            - If $a < 0$, the symmetric curves are located in Quadrants 2 and 4.
        - Behavior of $y = \frac{a}{x^2}$:
            - If $a > 0$, the curves are symmetric about the y-axis and located in Quadrants 1 and 2 (wholly above the x-axis).
            - If $a < 0$, the curves are symmetric about the y-axis and located in Quadrants 3 and 4 (wholly below the x-axis).
- **Exponential Functions**
    - **Exponential Function**: A function in which the variable is the exponent of a positive base, written as $y = a^x$, where the base $a > 0$.
        - The domain is all real numbers, and the curve has a horizontal asymptote along the x-axis ($y = 0$).
        - The y-intercept is always located at coordinate point $(0,1)$ because $a^0 = 1$.
        - Behavior of $y = a^x$:
            - If $a > 1$ (exponential growth, e.g., $y = 2^x$), the curve rises from left to right, approaching $y = 0$ as $x \to -\infty$.
            - If $0 < a < 1$ (exponential decay, e.g., $y = 2^{-x} = \left(\frac{1}{2}\right)^x$), the curve falls from left to right, approaching $y = 0$ as $x \to \infty$.

---

Section 2: Graphical Solutions of Equations

- **Intersections and Roots**
    - **Graphical Solution**: Solving an equation of the form $f(x) = g(x)$ by locating the horizontal positions of the intersection points of the curves $y = f(x)$ and $y = g(x)$.
        - The algebraic solutions of the equation are strictly the **x-coordinates** of the intersection points; the y-coordinates are ignored in the final solution set.

---

Section 3: Gradient of a Curve at a Point

- **Non-Linear Slopes**
    - **Tangent**: A straight line that touches a curve at exactly one point without crossing through it at that point.
        - The gradient of a non-linear curve at a specific point is defined as the gradient of the tangent line drawn to the curve at that point.
        - Because tangents are hand-drawn, gradients obtained graphically are estimates and contain a small margin of error.

---

Numbered Procedures

Procedural Topic: Finding the Straight Line to Draw for Graphical Solutions

1. **State Plotted Curve**: Identify the equation of the curve that is already drawn on your graph, e.g., $y = f(x)$.
2. **Write Target Equation**: Write down the equation you are asked to solve, e.g., $F(x) = 0$.
3. **Algebraically Isolate the Curve Term**: Manipulate the target equation $F(x) = 0$ using addition, subtraction, multiplication, or division to isolate the exact expression $f(x)$ on one side of the equals sign.
4. **Identify the Straight Line**: The resulting expression will be in the form $f(x) = mx + c$. The straight line you must draw on the grid is: $$y = mx + c$$
5. **Find Intersections**: Draw this line on the grid, identify the intersection points with the curve, and read their x-coordinates to state the solutions.

Procedural Topic: Estimating the Gradient of a Curve at a Point Graphically

1. **Locate Point**: Mark the target coordinate point $P(x_0, y_0)$ on the plotted curve.
2. **Draw the Tangent Line**: Use a ruler to draw a straight line that touches the curve only at point $P$, balancing the gaps between the ruler and the curve equally on both sides.
3. **Select Two Reference Coordinates**: Choose two distinct, easy-to-read points on the **tangent line** (e.g., $A(x_1, y_1)$ and $B(x_2, y_2)$). Do not use points from the curve itself unless they lie exactly on the tangent.
4. **Calculate the Gradient**: Substitute the coordinates into the gradient formula: $$m = \frac{y_2 - y_1}{x_2 - x_1}$$

---

Worked Examples

Example 1: Describing Key Features of Graphs

- **Question**: State the asymptotes, quadrants, and intercepts of the function $y = \frac{5}{x}$ and sketch its general shape.
- **Step-by-Step Reasoning**:
    1. **Identify function type**: This is a reciprocal function of the form $y = \frac{a}{x}$ where $a = 5$ (positive).
    2. **State asymptotes**: The curve is undefined at $x = 0$, and as $x \to \pm\infty$, $y \to 0$. The vertical asymptote is $x = 0$ (y-axis) and the horizontal asymptote is $y = 0$ (x-axis).
    3. **Determine quadrants**: Since $a = 5 > 0$, the reciprocal curves lie entirely within Quadrants 1 and 3.
    4. **Identify intercepts**: There are no x-intercepts or y-intercepts.
    5. **Sketch**: Draw two smooth hyperbolic curves asymptotic to the axes in Quadrants 1 and 3.

Example 2: Finding the Straight Line to Solve an Equation Graphically

- **Question**: Given that the curve $y = 2^x - 1$ has been plotted on a grid, find the equation of the straight line that must be drawn to solve the equation $2^x - x = 2$ graphically.
- **Step-by-Step Reasoning**:
    1. **Identify target equation and plotted function**:
        - Target: $2^x - x = 2$
        - Plotted Curve: $y = 2^x - 1$
    2. **Isolate the exponential term**: Rearrange the target equation to isolate $2^x$: $$2^x = x + 2$$
    3. **Formulate the plotted curve's expression**: Subtract $1$ from both sides of the equation to match the curve's formula: $$2^x - 1 = x + 2 - 1$$ $$2^x - 1 = x + 1$$
    4. **Identify the line**: The left-hand side is now equal to the plotted curve $y$. The right-hand side is the equation of the straight line to draw: $$y = x + 1$$

Example 3: Estimating Gradient of a Curve Graphically

- **Question**: Estimate the gradient of the curve $y = x^2 + 1$ at the point where $x = 0.5$.
- **Step-by-Step Reasoning**:
    1. **Locate point on curve**: At $x = 0.5$, the y-coordinate is $y = (0.5)^2 + 1 = 1.25$. Point is $P(0.5, 1.25)$.
    2. **Draw tangent**: Place a ruler at $P(0.5, 1.25)$ and draw a straight tangent line.
    3. **Choose two points on the tangent**: Suppose the drawn tangent passes through the grid intersections at $A(1.5, 2.25)$ and $B(-0.5, 0.25)$.
    4. **Calculate gradient**: $$m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{2.25 - 0.25}{1.5 - (-0.5)} = \frac{2}{2} = 1$$
    5. **State gradient**: The estimated gradient of the curve at $x = 0.5$ is $1$.

---

⚠️ Common Mistakes on Exams

- **Using Curve Points instead of Tangent Points**: Selecting coordinate points from the curve itself rather than coordinates lying directly on the hand-drawn tangent line to calculate the rise-over-run gradient.
- **Incorrect Asymptote Behaviors**: Drawing curves that cross over, touch, or curl away from their asymptotes (e.g., drawing reciprocal graphs that curl away from the axes at their extreme ends).
- **Deriving the Wrong Line due to Sign Errors**: Making algebraic errors when manipulating the target equation to match the plotted curve (e.g., adding instead of subtracting a constant, leading to drawing the wrong line).
- **Including y-coordinates in Graphical Solutions**: Writing the final solutions as coordinate pairs $(x, y)$ instead of stating only the x-coordinates of the intersection points.
- **Drawing Secant Lines instead of Tangents**: Drawing lines that cross through the curve twice at the point of interest instead of touching the curve at exactly one point.

---

🔗 Cross-References

- **Graphical Solutions** $\leftrightarrow$ **Simultaneous Linear & Non-Linear Equations (Chapter 2)**: Solving equations graphically finds the geometric coordinates of intersections, which serves as the visual representation of solving simultaneous equations algebraically.
- **Gradients of Curves** $\leftrightarrow$ **Coordinate Geometry (Chapter 8)**: Finding the slope of a non-linear curve at a point relies on drawing a linear tangent and applying the Chapter 8 straight-line gradient formula $m = \frac{y_2 - y_1}{x_2 - x_1}$.
- **Exponential Graph Constraints** $\leftrightarrow$ **Indices and Exponential Equations (Chapter 4)**: The asymptotic boundary ($y > 0$) and intercepts ($y = 1$ when $x = 0$) of exponential graphs are derived from index laws.