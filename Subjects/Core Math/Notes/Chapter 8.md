# Chapter 8 Exam Notes: Coordinate Geometry

Section 1: Midpoint, Distance, and Gradient of a Line Segment

- **Line Segment Midpoints**
    - **Midpoint**: The coordinate point that lies exactly halfway between two endpoints of a line segment.
        - Key LaTeX formula: Given points $A(x_1, y_1)$ and $B(x_2, y_2)$: $$\text{Midpoint of } AB = \left(\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2}\right)$$
        - This formula calculates the arithmetic mean of the respective x-coordinates and y-coordinates.
- **Distance Between Two Points**
    - **Distance**: The straight-line length between two coordinate points, derived using Pythagoras' theorem.
        - Key LaTeX formula: Given points $A(x_1, y_1)$ and $B(x_2, y_2)$: $$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$
        - Because the differences are squared, the order of subtraction (e.g., $x_2 - x_1$ versus $x_1 - x_2$) does not affect the final distance.
- **Gradient of a Line Segment**
    - **Gradient**: The measure of the steepness or slope of a line segment, defined as the ratio of vertical change (rise) to horizontal change (run).
        - Key LaTeX formula: Given points $A(x_1, y_1)$ and $B(x_2, y_2)$: $$m = \frac{y_2 - y_1}{x_2 - x_1}$$
        - There are four categories of gradients based on line orientation:
            - Positive gradient: Line rises from left to right (y-coordinate and x-coordinate changes share the same sign).
            - Negative gradient: Line falls from left to right (y-coordinate and x-coordinate changes have opposite signs).
            - Zero gradient ($m = 0$): Horizontal line (where $y_2 - y_1 = 0$).
            - Undefined gradient: Vertical line (where $x_2 - x_1 = 0$, causing division by zero).

---

Section 2: Parallel, Perpendicular, and Collinear Lines

- **Parallel Lines**
    - **Parallel Lines**: Straight lines on the same plane that never intersect and share identical steepness.
        - Key LaTeX formula: For two lines $l_1$ and $l_2$ with gradients $m_1$ and $m_2$: $$l_1 \parallel l_2 \iff m_1 = m_2$$
        - Parallel lines have equal gradients but different y-intercepts.
- **Perpendicular Lines**
    - **Perpendicular Lines**: Straight lines that intersect one another at a right angle ($90^\circ$).
        - Key LaTeX formula: For two lines $l_1$ and $l_2$ with gradients $m_1$ and $m_2$: $$l_1 \perp l_2 \iff m_1 m_2 = -1 \quad \left(\text{or } m_2 = -\frac{1}{m_1}\right)$$
        - The gradient of a perpendicular line is the negative reciprocal of the original line's gradient. This rule holds true for all lines except vertical and horizontal pairs.
- **Collinear Points**
    - **Collinear Points**: Points that lie on the same straight line.
        - Key LaTeX formula: Three points $A$, $B$, and $C$ are collinear if: $$m_{AB} = m_{BC} = m_{AC}$$
        - To formally prove collinearity, you must demonstrate both that the gradients between the points are equal and that the segments share a common point (such as point $B$).

---

Section 3: Equations of Straight Lines and Perpendicular Bisectors

- **Equations of Straight Lines**
    - **Straight-Line Equations**: Algebraic representations defining all coordinate points lying along a specific line.
        - Key LaTeX formulas:
            - Point-slope form: $y - y_1 = m(x - x_1)$
            - Slope-intercept form: $y = mx + c$
        - The point-slope form is highly efficient when given a gradient and any coordinate point, while the slope-intercept form explicitly identifies the vertical intercept $(0, c)$.
- **Perpendicular Bisector**
    - **Perpendicular Bisector**: A line that cuts a line segment into two equal halves at a right angle ($90^\circ$).
        - Key LaTeX formula: If a line bisects segment $AB$ perpendicularly, its gradient is: $$m_{\text{bisector}} = -\frac{1}{m_{AB}}$$
        - The perpendicular bisector must pass directly through the midpoint of the original segment.

---

Section 4: Coordinate Area and the Shoelace Formula

- **The Shoelace Formula**
    - **Shoelace Formula**: An algebraic algorithm used to find the area of any non-intersecting polygon given the coordinates of its vertices.
        - Key LaTeX formula: For a triangle with vertices $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$: $$\text{Area} = \frac{1}{2} \left| \begin{matrix} x_1 & x_2 & x_3 & x_1 \\ y_1 & y_2 & y_3 & y_1 \end{matrix} \right| = \frac{1}{2} |(x_1 y_2 + x_2 y_3 + x_3 y_1) - (x_2 y_1 + x_3 y_2 + x_1 y_3)|$$ For a quadrilateral with vertices $A$, $B$, $C$, and $D$: $$\text{Area} = \frac{1}{2} \left| \begin{matrix} x_1 & x_2 & x_3 & x_4 & x_1 \\ y_1 & y_2 & y_3 & y_4 & y_1 \end{matrix} \right|$$
        - The vertices must be listed in an **anticlockwise direction** around the polygon to ensure the calculated term inside the modulus is positive. The first coordinate pair must always be repeated at the end of the array to close the shape.

---

Section 5: Coordinate Properties of Geometric Shapes

- **Geometric Shapes in Coordinate Systems**
    - **Parallelogram**: A quadrilateral with two pairs of parallel sides.
        - Key property: The diagonals of a parallelogram bisect each other, meaning the midpoint of diagonal $AC$ is identical to the midpoint of diagonal $BD$.
    - **Rhombus**: A parallelogram with four equal sides.
        - Key property: The diagonals are perpendicular bisectors of each other (they cross at a right angle at their shared midpoint).
    - **Kite**: A quadrilateral with two pairs of equal adjacent sides.
        - Key property: The diagonals intersect at a right angle, and one diagonal is bisected by the other.

---

Numbered Procedures

Procedural Topic: Finding the Equation of a Perpendicular Bisector

1. **Calculate Midpoint**: Use the endpoints $A(x_1, y_1)$ and $B(x_2, y_2)$ to find the segment's midpoint: $M = \left(\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2}\right)$.
2. **Calculate Original Gradient**: Determine the gradient of segment $AB$: $m_{AB} = \frac{y_2 - y_1}{x_2 - x_1}$.
3. **Determine Perpendicular Gradient**: Find the negative reciprocal gradient: $m_{\perp} = -\frac{1}{m_{AB}}$.
4. **Formulate Equation**: Substitute the perpendicular gradient $m_{\perp}$ and the midpoint coordinates $M$ into the point-slope formula: $y - y_M = m_{\perp}(x - x_M)$. Rearrange to standard form.

Procedural Topic: Finding the Fourth Vertex of a Parallelogram

1. **Identify Diagonals**: In a parallelogram $ABCD$, identifying letters in cyclic order means $AC$ and $BD$ are the diagonals.
2. **Calculate Known Midpoint**: Use the coordinates of the known diagonal (e.g., $A$ and $C$) to calculate its midpoint: $M_{AC} = \left(\frac{x_A + x_C}{2}, \frac{y_A + y_C}{2}\right)$.
3. **Equate Midpoints**: Set the midpoint of the second diagonal equal to the calculated midpoint: $M_{BD} = M_{AC}$.
4. **Solve for the Missing Coordinates**: Set up and solve the coordinate equations for the missing vertex $D(x_D, y_D)$: $$\frac{x_B + x_D}{2} = x_M \quad \text{and} \quad \frac{y_B + y_D}{2} = y_M$$

Procedural Topic: Calculating Polygon Area using the Shoelace Formula

1. **Sketch Shape**: Sketch the vertices roughly on a coordinate plane to verify their relative locations.
2. **Order Vertices**: Select a starting vertex and list the coordinates sequentially in an **anticlockwise direction**.
3. **Set Up Array**: Write the x-coordinates in the top row and the y-coordinates in the bottom row of a matrix array, repeating the starting coordinate pair at the end of the columns.
4. **Cross-Multiply and Sum**:
    - Sum the diagonal products from top-left to bottom-right: $D = x_1 y_2 + x_2 y_3 + \dots + x_n y_1$.
    - Sum the diagonal products from bottom-left to top-right: $U = y_1 x_2 + y_2 x_3 + \dots + y_n x_1$.
5. **Calculate Final Area**: Apply the formula: $\text{Area} = \frac{1}{2} |D - U|$.

---

Worked Examples

Example 1: Multi-Step Algebraic Distance Solving

- **Question**: Given the points $A(a, a+1)$, $B(-6, -3)$, and $C(5, -1)$, find the possible values of $a$ if the length of $AB$ is twice the length of $AC$.
- **Step-by-Step Reasoning**:
    1. **Formulate distance square expressions**: $$AB^2 = (a - (-6))^2 + (a + 1 - (-3))^2 = (a+6)^2 + (a+4)^2$$ $$AB^2 = (a^2 + 12a + 36) + (a^2 + 8a + 16) = 2a^2 + 20a + 52$$ $$AC^2 = (a - 5)^2 + (a + 1 - (-1))^2 = (a-5)^2 + (a+2)^2$$ $$AC^2 = (a^2 - 10a + 25) + (a^2 + 4a + 4) = 2a^2 - 6a + 29$$
    2. **Set up the relationship**: Since $AB = 2AC \implies AB^2 = 4AC^2$.
    3. **Substitute and expand**: $$2a^2 + 20a + 52 = 4(2a^2 - 6a + 29)$$ $$2a^2 + 20a + 52 = 8a^2 - 24a + 116$$
    4. **Compile standard quadratic**: $$6a^2 - 44a + 64 = 0 \implies 3a^2 - 22a + 32 = 0$$
    5. **Factorize and solve**: $$(3a - 16)(a - 2) = 0 \implies a = 2 \quad \text{or} \quad a = \frac{16}{3}$$

Example 2: Collinear Points coordinate Solve

- **Question**: If the points $P(-1, -1)$, $Q(0, 2)$, and $R(2, k)$ lie on a straight line, find the value of $k$.
- **Step-by-Step Reasoning**:
    1. **Calculate gradient** $m_{PQ}$: $$m_{PQ} = \frac{2 - (-1)}{0 - (-1)} = \frac{3}{1} = 3$$
    2. **Calculate gradient** $m_{QR}$: $$m_{QR} = \frac{k - 2}{2 - 0} = \frac{k - 2}{2}$$
    3. **Equate gradients**: Since the points are collinear, they lie on the same straight line, so $m_{PQ} = m_{QR}$: $$3 = \frac{k - 2}{2} \implies 6 = k - 2 \implies k = 8$$

Example 3: Finding the Perpendicular Bisector

- **Question**: Find the equation of the perpendicular bisector of the line joining the points $(1, 1)$ and $(2, 4)$.
- **Step-by-Step Reasoning**:
    1. **Find the midpoint** $M$: $$M = \left(\frac{1+2}{2}, \frac{1+4}{2}\right) = (1.5, 2.5)$$
    2. **Find the original line's gradient** $m$: $$m = \frac{4-1}{2-1} = 3$$
    3. **Calculate perpendicular gradient** $m_{\perp}$: $$m_{\perp} = -\frac{1}{m} = -\frac{1}{3}$$
    4. **Write the equation**: Use point-slope form with $M(1.5, 2.5)$ and $m_{\perp} = -\frac{1}{3}$: $$y - 2.5 = -\frac{1}{3}(x - 1.5) \implies y - 2.5 = -\frac{1}{3}x + 0.5$$ $$y = -\frac{1}{3}x + 3 \implies 3y + x = 9$$

Example 4: Solving Parallelogram Vertices

- **Question**: Three of the vertices of a parallelogram $ABCD$ are $A(2,1)$, $B(7,8)$, and $C(4,3)$. Find the coordinates of vertex $D$.
- **Step-by-Step Reasoning**:
    1. **Determine midpoint of diagonal** $AC$: $$M_{AC} = \left(\frac{2+4}{2}, \frac{1+3}{2}\right) = (3, 2)$$
    2. **Equate to midpoint of diagonal** $BD$: Let $D$ have coordinates $(x, y)$. $$M_{BD} = \left(\frac{7+x}{2}, \frac{8+y}{2}\right) = (3, 2)$$
    3. **Solve for x**: $$\frac{7+x}{2} = 3 \implies 7+x = 6 \implies x = -1$$
    4. **Solve for y**: $$\frac{8+y}{2} = 2 \implies 8+y = 4 \implies y = -4$$
    5. **Final Coordinate**: $D(-1, -4)$.

Example 5: Shoelace Area of a Triangle

- **Question**: Find the area of the triangle with vertices $A(5, 6)$, $B(0, -4)$, and $C(16, 8)$.
- **Step-by-Step Reasoning**:
    1. **Arrange coordinates anticlockwise**: Plotting these points reveals their layout: $B(0, -4)$ is lower-left, $C(16, 8)$ is far right, and $A(5, 6)$ is upper-middle. The anticlockwise sequence is $B(0, -4) \to C(16, 8) \to A(5, 6) \to B(0, -4)$.
    2. **Set up Shoelace matrix**: $$\text{Area} = \frac{1}{2} \left| \begin{matrix} 0 & 16 & 5 & 0 \\ -4 & 8 & 6 & -4 \end{matrix} \right|$$
    3. **Multiply diagonally downwards**: $$D = (0 \times 8) + (16 \times 6) + (5 \times -4) = 0 + 96 - 20 = 76$$
    4. **Multiply diagonally upwards**: $$U = (-4 \times 16) + (8 \times 5) + (6 \times 0) = -64 + 40 + 0 = -24$$
    5. **Calculate absolute difference**: $$\text{Area} = \frac{1}{2} |D - U| = \frac{1}{2} |76 - (-24)| = \frac{1}{2} |100| = 50\text{ units}^2$$

---

⚠️ Common Mistakes on Exams

- **Shoelace Formula Orientation Errors**: Listing coordinates in a clockwise direction during Shoelace calculations, which leads to a negative area term. Always sketch the figure first and follow an anticlockwise path.
- **Midpoint/Gradient Sign Confusions**: Subtracting coordinates instead of adding them in the midpoint formula (e.g., writing $\frac{x_2-x_1}{2}$), or conversely adding coordinates in the gradient formula.
- **Failing to State Shared Point in Collinearity Proofs**: Showing that gradients are equal (e.g., $m_{AB} = m_{BC}$) but forgetting to explicitly write that they share a common point (such as $B$), which is required to prove they lie on the same line and are not merely parallel.
- **Incorrect Substitution in Perpendicular Equations**: Finding the perpendicular gradient correctly but accidentally substituting the coordinates of one of the segment's endpoints into the final equation instead of the midpoint coordinates.
- **Wrong Diagonal Pairings in Parallelograms**: Assuming that any two vertices form a diagonal, rather than following the cyclic order of the naming lettering (in parallelogram $ABCD$, $AC$ and $BD$ are always the diagonals; $AB$ is a side).

---

🔗 Cross-References

- **Equations of Lines** $\leftrightarrow$ **Simultaneous Linear Equations (Chapter 2)**: Finding the coordinate point where two straight lines intersect on a plane is achieved algebraically by solving their linear equations simultaneously.
- **Straight Line Gradients** $\leftrightarrow$ **Functions and Graphs (Chapter 9)**: Straight lines have a constant, uniform gradient, whereas non-linear curves have varying gradients that must be approximated using tangents at specific points.
- **Coordinate Area** $\leftrightarrow$ **Solutions of a Triangle (Chapter 5)**: The Shoelace formula calculates areas of triangles mapped onto Cartesian coordinates, whereas Chapter 5 utilizes trigonometric ratios (such as $\frac{1}{2}ab\sin C$) when given lengths and angles.