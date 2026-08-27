# Chapter 5 Exam Notes: Solutions of a Triangle

Section 1: Trigonometric Ratios of Acute and Obtuse Angles

- **Trigonometric Ratios**
    - **Trigonometric Ratios**: The ratios of the side lengths of a right-angled triangle relative to an acute angle1.
        - Key LaTeX formulas: $$\sin \theta = \frac{\text{opposite}}{\text{hypotenuse}}$$ $$\cos \theta = \frac{\text{adjacent}}{\text{hypotenuse}}$$ $$\tan \theta = \frac{\text{opposite}}{\text{adjacent}}$$
        - Trig ratios represent pure dimensionless numbers and have no physical units of measurement1.
- Trigonometric Ratios of Obtuse Angles
    - **Obtuse Angle Identities**: Algebraic identities relating the trigonometric ratio of an obtuse angle to the ratio of its acute supplement2.
        - Key LaTeX formulas: $$\sin(180^\circ - A) = \sin A$$ $$\cos(180^\circ - A) = -\cos A$$ $$\tan(180^\circ - A) = -\tan A$$
        - The sine of an obtuse angle is positive, whereas the cosine and tangent of an obtuse angle are always negative2.
- Trigonometric Ratios in All Quadrants (CAST)
    - **CAST Diagram**: A coordinate framework showing which trigonometric functions are positive in each of the four quadrants from $0^\circ$ to $360^\circ$3.
        - Quadrant 1 ($0^\circ < \theta < 90^\circ$): **All** functions positive ($\sin \theta > 0, \cos \theta > 0, \tan \theta > 0$)3.
        - Quadrant 2 ($90^\circ < \theta < 180^\circ$): Only **Sine** positive ($\sin \theta > 0$; others negative)3.
        - Quadrant 3 ($180^\circ < \theta < 270^\circ$): Only **Tangent** positive ($\tan \theta > 0$; others negative)3.
        - Quadrant 4 ($270^\circ < \theta < 360^\circ$): Only **Cosine** positive ($\cos \theta > 0$; others negative)3.

---

Section 2: Area of a Triangle

- Area of Non-Right-Angled Triangles
    - **Area of a Triangle**: The measure of the triangular space bounded by any two sides and the sine of their included angle4.
        - Key LaTeX formula: $$\text{Area of } \Delta ABC = \frac{1}{2}ab \sin C = \frac{1}{2}bc \sin A = \frac{1}{2}ac \sin B$$
        - The angle used in the formula must be the included angle located directly between the two given side lengths4.

---

Section 3: The Sine Rule and The Cosine Rule

- **The Sine Rule**
    - **Sine Rule**: A proportional relationship stating that the ratio of a triangle's side length to the sine of its opposite angle is constant across all three sides5.
        - Key LaTeX formulas:
            - To find sides: $\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}$
            - To find angles: $\frac{\sin A}{a} = \frac{\sin B}{b} = \frac{\sin C}{c}$
        - Used when given an angle and its opposite side along with one other side or angle (AAS or SSA cases)5.
- **The Ambiguous Case of the Sine Rule**
    - **Ambiguous Case**: A condition where two distinct triangles can be constructed from the same set of given SSA measurements6.
        - This occurs only if:
            1. The given angle $A$ is **acute** ($A < 90^\circ$)6.
            2. The opposite side $a$ is **shorter** than the adjacent side $b$ ($a < b$)6.
            3. The opposite side is **longer** than the perpendicular height ($a > b \sin A$)6.
        - This results in two possible values for the angle: an acute angle $B_1$ and an obtuse angle $B_2 = 180^\circ - B_1$6.
- **The Cosine Rule**
    - **Cosine Rule**: An algebraic formula relating all three side lengths of a triangle to the cosine of one of its angles7.
        - Key LaTeX formulas:
            - To find sides: $a^2 = b^2 + c^2 - 2bc \cos A$
            - To find angles: $\cos A = \frac{b^2 + c^2 - a^2}{2bc}$
        - Used when given two sides and the included angle (SAS) or all three side lengths (SSS)7. There is never an ambiguous case with the Cosine Rule because the cosine of an angle uniquely identifies it from $0^\circ$ to $180^\circ$7.

---

Section 4: Bearings, Elevation, and Depression

- **Bearings**
    - **Bearing**: An angle representing the direction of travel or position of one point relative to another, measured clockwise from the North direction line8.
        - Key LaTeX formula: $$\text{Bearing of } A \text{ from } B = \text{Bearing of } B \text{ from } A \pm 180^\circ$$
        - Bearings must always be written as three-figure angles (e.g., $045^\circ$, $270^\circ$)8.
- **Angles of Elevation and Depression**
    - **Angle of Elevation**: The upward angle measured from the horizontal plane to the line of sight of an object above the observer9.
    - **Angle of Depression**: The downward angle measured from the horizontal plane to the line of sight of an object below the observer9.
        - Both angles are measured strictly from the **horizontal line**, meaning the angle of elevation from $B$ to $A$ is equal to the angle of depression from $A$ to $B$9.

---

Section 5: 3-D Trigonometry

- **3-D Trigonometry**
    - **3-D Trigonometric Problems**: Solving geometric lengths and angles in three dimensions by identifying 2D plane triangles embedded within the 3D structure10.
        - Angles are found by identifying the orthogonal projection of a line onto a flat face to establish a right-angled triangle10.

---

Numbered Procedures

Procedural Topic: Identifying and Solving the Ambiguous Case of the Sine Rule

1. **Check Ambiguity Conditions**: Given $a$, $b$, and $A$, verify if $A < 90^\circ$, $a < b$, and $a > b \sin A$6.
2. **Solve for Acute Angle** $B_1$: Apply the Sine Rule: $$B_1 = \sin^{-1}\left(\frac{b \sin A}{a}\right)$$
3. **Find Obtuse Angle** $B_2$: Calculate the supplement of the acute angle: $$B_2 = 180^\circ - B_1$$
4. **Solve Both Triangles**: Calculate the remaining angle $C$ and side $c$ for both independent coordinate sets:
    - **Triangle 1**: $C_1 = 180^\circ - A - B_1$
    - **Triangle 2**: $C_2 = 180^\circ - A - B_2$

Procedural Topic: Calculating Reverse Bearings

1. **Identify Base Angle**: Let the bearing of $B$ from $A$ be $\theta$8.
2. **Determine Shift Direction**:
    - If $\theta < 180^\circ$, add $180^\circ$ to the bearing8.
    - If $\theta \ge 180^\circ$, subtract $180^\circ$ from the bearing8.
3. **State Bearing**: Write the resulting angle as a three-figure bearing.

Procedural Topic: Finding the Angle between a Line and a Plane in 3D

1. **Drop Perpendicular**: From the top point of the line, drop a perpendicular line to meet the plane at its foot10.
2. **Draw Projection Line**: Connect the foot of the perpendicular to the point where the original line intersects the plane10.
3. **Calculate Angle**: Use basic right-angled trigonometric ratios in the resulting vertical right-angled triangle to find the angle between the original line and the projection line10.

---

Worked Examples

Example 1: Obtuse Angle Trigonometric Translation

- **Question**: Given that $\cos 45.5^\circ = q$, express $\cos 134.5^\circ$ in terms of $q$2.
- **Step-by-Step Reasoning**:
    1. **Analyze the angle supplement**: Recognize that $134.5^\circ = 180^\circ - 45.5^\circ$.
    2. **Apply the obtuse cosine identity**: Use $\cos(180^\circ - A) = -\cos A$.
    3. **Substitute** $q$: $$\cos 134.5^\circ = \cos(180^\circ - 45.5^\circ) = -\cos 45.5^\circ = -q$$

Example 2: Area of a Non-Right-Angled Triangle

- **Question**: Calculate the area of a triangle with sides $8.5\text{ cm}$ and $5\text{ cm}$, and an included obtuse angle of $111^\circ$4.
- **Step-by-Step Reasoning**:
    1. **Identify sides and included angle**: $a = 8.5$, $b = 5$, $C = 111^\circ$.
    2. **Apply the Area Formula**: $$\text{Area} = \frac{1}{2}ab \sin C = \frac{1}{2}(8.5)(5)\sin 111^\circ$$
    3. **Calculate**: $$\text{Area} \approx 21.25 \times 0.93358 \approx 19.8\text{ cm}^2 \quad \text{(to 3 s.f.)}$$

Example 3: Sine Rule with the Ambiguous Case

- **Question**: In $\Delta ABC$, $AB = 8\text{ cm}$, $AC = 5\text{ cm}$, and $\angle ABC = 30^\circ$. Find the possible values of $\angle ACB$6.
- **Step-by-Step Reasoning**:
    1. **Verify ambiguity condition**: Given angle $B = 30^\circ$ (acute), adjacent side $c = 8$, and opposite side $b = 5$. Since $5 < 8$ and $5 > 8\sin 30^\circ = 4$, two triangles exist.
    2. **Calculate the acute angle option** $C_1$: $$\frac{\sin C_1}{8} = \frac{\sin 30^\circ}{5} \implies \sin C_1 = \frac{8 \times 0.5}{5} = 0.8$$ $$C_1 = \sin^{-1}(0.8) \approx 53.1^\circ$$
    3. **Calculate the obtuse angle option** $C_2$: $$C_2 = 180^\circ - 53.1^\circ = 126.9^\circ$$
    4. **Final values**: $\angle ACB$ is $53.1^\circ$ or $126.9^\circ$.

Example 4: The Cosine Rule

- **Question**: In $\Delta ABC$, $AB = 4\text{ cm}$, $BC = 3\text{ cm}$, and $\angle ABC = 80^\circ$. Find $AC$7.
- **Step-by-Step Reasoning**:
    1. **Identify SAS configuration**: Given $a = 3$, $c = 4$, $B = 80^\circ$.
    2. **Apply Cosine Rule**: $$b^2 = a^2 + c^2 - 2ac \cos B$$ $$b^2 = 3^2 + 4^2 - 2(3)(4)\cos 80^\circ$$
    3. **Compute**: $$b^2 = 9 + 16 - 24(0.17365) \implies b^2 \approx 25 - 4.1676 = 20.832$$ $$b = \sqrt{20.832} \approx 4.56\text{ cm} \quad \text{(to 3 s.f.)}$$

Example 5: Reverse Bearings Navigation

- **Question**: The bearing of point $P$ from point $Q$ is $065^\circ$. Find the bearing of $Q$ from $P$8.
- **Step-by-Step Reasoning**:
    1. **Check bearing threshold**: Since $65^\circ < 180^\circ$, use the addition rule.
    2. **Apply addition**: $$\text{Bearing} = 65^\circ + 180^\circ = 245^\circ$$
    3. **Final value**: The bearing is $245^\circ$.

Example 6: Angles of Elevation and Depression

- **Question**: From the top of a cliff $72\text{ m}$ high, the angle of depression of a ship is $32^\circ$. Find the horizontal distance from the base of the cliff to the ship9.
- **Step-by-Step Reasoning**:
    1. **Identify alternate angles**: The angle of depression of $32^\circ$ from the cliff-top is equal to the angle of elevation of $32^\circ$ from the ship to the cliff-top.
    2. **Set up the tangent ratio**: $$\tan 32^\circ = \frac{\text{height}}{\text{distance}} = \frac{72}{d}$$
    3. **Solve for** $d$: $$d = \frac{72}{\tan 32^\circ} = \frac{72}{0.62487} \approx 115\text{ m} \quad \text{(to 3 s.f.)}$$

Example 7: 3-D Cuboid Properties

- **Question**: A cuboid has a horizontal rectangular base $ABC$ with $AB = 4\text{ cm}$ and $BC = 3\text{ cm}$. The vertical height of the cuboid is $CD = 12\text{ cm}$. Find $AD$ and the angle $\angle CAD$10.
- **Step-by-Step Reasoning**:
    1. **Find horizontal base diagonal** $AC$: Use Pythagoras' theorem in base $\Delta ABC$: $$AC = \sqrt{4^2 + 3^2} = 5\text{ cm}$$
    2. **Find slant height** $AD$: Use Pythagoras' theorem in vertical right-angled $\Delta ACD$: $$AD = \sqrt{AC^2 + CD^2} = \sqrt{5^2 + 12^2} = 13\text{ cm}$$
    3. **Find the angle** $\angle CAD$: Use tangent in $\Delta ACD$: $$\tan \angle CAD = \frac{CD}{AC} = \frac{12}{5} = 2.4$$ $$\angle CAD = \tan^{-1}(2.4) \approx 67.4^\circ$$

---

⚠️ Common Mistakes on Exams

- **Failing to Check for the Ambiguous Case**: Blindly applying the Sine Rule to calculate angles in SSA setups without evaluating if a second obtuse angle supplement can be formed6.
- **Measuring Bearings Counter-Clockwise**: Reading angles from the West line or measuring counter-clockwise instead of measuring clockwise starting from the North line8.
- **Measuring Elevation/Depression Angles from the Vertical**: Confusing the angle of depression with the vertical angle between the observer's mast/cliff and the line of sight (always measure depression down from the horizontal)9.
- **Incorrect Sign on Obtuse Conversions**: Writing $\sin(180^\circ - A) = -\sin A$ by incorrectly applying the negative sign from cosine and tangent conversions2.
- **Applying Right-Angled Trig on Oblique Triangles**: Attempting to use standard SohCahToa ratios directly on non-right-angled triangles instead of using the Sine or Cosine rules5.

---

🔗 Cross-References

- **Obtuse Angles** $\leftrightarrow$ **Sine Rule (Section 3)**: Oblique triangles solved using the Sine Rule often yield obtuse angle results that must be converted using supplement identities26.
- **Cosine Rule** $\leftrightarrow$ **Pythagoras' Theorem (Section 1)**: The Cosine Rule formula $a^2 = b^2+c^2-2bc\cos A$ simplifies exactly to Pythagoras' theorem when $A = 90^\circ$ (since $\cos 90^\circ = 0$)17.
- **Bearings** $\leftrightarrow$ **Parallel Lines**: Calculating reverse bearings relies directly on parallel line properties (alternate interior angles and co-interior angles summing to $180^\circ$)8.