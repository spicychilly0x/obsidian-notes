Chapter 6 Exam Notes

Topic 6: Basic Trigonometry

---

1. Core Concept: Right-Angled Triangles & Complementary Angles

- Core Concept: **Trigonometric Ratios of Acute Angles**
    - Key Definition: For a right-angled triangle with acute angle $\theta$, adjacent side $a$, opposite side $b$, and hypotenuse $c$, the three fundamental ratios are defined as: $$\sin \theta = \frac{\text{Opposite}}{\text{Hypotenuse}} = \frac{b}{c}$$ $$\cos \theta = \frac{\text{Adjacent}}{\text{Hypotenuse}} = \frac{a}{c}$$ $$\tan \theta = \frac{\text{Opposite}}{\text{Adjacent}} = \frac{b}{a}$$
        - _Detail/Fine Print_: Tangent is also mathematically equivalent to the ratio of sine to cosine: $$\tan \theta = \frac{\sin \theta}{\cos \theta}$$
- Core Concept: **Trigonometric Ratios of Complementary Angles**
    - Key Definition: Two angles are **complementary angles** if their sum is exactly $90^\circ$ (or $\frac{\pi}{2}$ radians). Using right-triangle properties, complementary relationships are: $$\sin(90^\circ - \theta) = \cos \theta$$ $$\cos(90^\circ - \theta) = \sin \theta$$ $$\tan(90^\circ - \theta) = \frac{1}{\tan \theta}$$
        - _Detail/Fine Print_: These rules allow trigonometric terms with co-functions to be swapped directly during algebraic simplifications.
- Core Concept: **Special Angles**
    - Key Formula: Exact geometric values for angles $30^\circ$ ($\frac{\pi}{6}$), $45^\circ$ ($\frac{\pi}{4}$), and $60^\circ$ ($\frac{\pi}{3}$) are: $$\sin(30^\circ) = \frac{1}{2}, \quad \cos(30^\circ) = \frac{\sqrt{3}}{2}, \quad \tan(30^\circ) = \frac{1}{\sqrt{3}}$$ $$\sin(45^\circ) = \frac{1}{\sqrt{2}}, \quad \cos(45^\circ) = \frac{1}{\sqrt{2}}, \quad \tan(45^\circ) = 1$$ $$\sin(60^\circ) = \frac{\sqrt{3}}{2}, \quad \cos(60^\circ) = \frac{1}{2}, \quad \tan(60^\circ) = \sqrt{3}$$
        - _Detail/Fine Print_: These values are derived from a bisected equilateral triangle of side length 2 and a right-angled isosceles triangle of side length 1.

---

2. Core Concept: General Angles & The CAST Quadrant System

- Core Concept: **General Angles & The CAST Diagram**
    - Key Definition: General angles are plotted on coordinate axes split into four quadrants in an anticlockwise direction, where the sign of each trigonometric ratio is determined by the **CAST diagram**: $$\text{Quadrant 1 } (0^\circ \text{ to } 90^\circ): \text{ All ratios (S, C, T) are positive}$$ $$\text{Quadrant 2 } (90^\circ \text{ to } 180^\circ): \text{ Only Sine is positive}$$ $$\text{Quadrant 3 } (180^\circ \text{ to } 270^\circ): \text{ Only Tangent is positive}$$ $$\text{Quadrant 4 } (270^\circ \text{ to } 360^\circ): \text{ Only Cosine is positive}$$
        - _Detail/Fine Print_: Angles measured in the clockwise direction from the positive $x$-axis are defined as negative angles.
- Core Concept: **Basic Angle (Reference Angle)**
    - Key Definition: A **basic angle** $\alpha$ is the positive acute angle ($0 < \alpha < 90^\circ$) formed between the terminal ray of the angle $\theta$ and the horizontal $x$-axis.
        - _Detail/Fine Print_: For any quadrant angle, its trigonometric value is equal to the trigonometric value of its basic angle, prefixed with the appropriate positive or negative sign according to its quadrant.
- Core Concept: **Supplementary Angle Identities**
    - Key Formula: Supplementary angles sum to $180^\circ$ (or $\pi$ radians), satisfying the following rules: $$\sin(180^\circ - \theta) = \sin \theta$$ $$\cos(180^\circ - \theta) = -\cos \theta$$ $$\tan(180^\circ - \theta) = -\tan \theta$$
        - _Detail/Fine Print_: The sine of supplementary angles is identical in magnitude and sign because sine is positive in both Quadrants 1 and 2.
- Core Concept: **Negative Angle Identities**
    - Key Formula: Rotating in the clockwise negative direction yields the identities: $$\sin(-\theta) = -\sin \theta$$ $$\cos(-\theta) = \cos \theta$$ $$\tan(-\theta) = -\tan \theta$$
        - _Detail/Fine Print_: Cosine is an even function (the negative sign inside the argument is eliminated), whereas sine and tangent are odd functions (the negative sign is factored out).

---

3. Core Concept: Inverse Functions & Principal Values

- Core Concept: **Principal Values**
    - Key Definition: The **principal value** is the unique angle falling within the restricted range of an inverse trigonometric relation: $$\text{For } \sin^{-1} x: \quad -\frac{\pi}{2} \le \theta \le \frac{\pi}{2} \quad (-90^\circ \le \theta \le 90^\circ)$$ $$\text{For } \cos^{-1} x: \quad 0 \le \theta \le \pi \quad (0^\circ \le \theta \le 180^\circ)$$ $$\text{For } \tan^{-1} x: \quad -\frac{\pi}{2} < \theta < \frac{\pi}{2} \quad (-90^\circ < \theta < 90^\circ)$$
        - _Detail/Fine Print_: Scientific calculators are programmed to output _only_ the principal value when evaluating inverse trigonometric functions.

---

🛠️ Procedure: Solving Simple Trigonometric Equations

1. **Isolate the trigonometric term**: Rearrange the equation into the form $\sin\theta = k$, $\cos\theta = k$, or $\tan\theta = k$.
2. **Identify possible quadrants**: Look at the sign of $k$ and use the CAST diagram to determine the two quadrants where solutions lie.
3. **Calculate the basic angle** $\alpha$: Use a calculator to find the positive acute angle $\alpha = \sin^{-1}|k|$, $\cos^{-1}|k|$, or $\tan^{-1}|k|$. (Always input $|k|$ as a positive value to ensure $\alpha$ is acute).
4. **Determine solutions within the domain**: Formulate $\theta$ based on the identified quadrants:
    - **Quadrant 1**: $\theta = \alpha$
    - **Quadrant 2**: $\theta = 180^\circ - \alpha$ or $\pi - \alpha$
    - **Quadrant 3**: $\theta = 180^\circ + \alpha$ or $\pi + \alpha$
    - **Quadrant 4**: $\theta = 360^\circ - \alpha$ or $2\pi - \alpha$
5. **Adjust for coterminal angles**: If the domain lies outside $[0, 360^\circ]$ (or $[0, 2\pi]$), add or subtract complete periods ($360^\circ$ or $2\pi$) to pull solutions into the specified range.

---

4. Core Concept: Trigonometric Graphs & Transformations

- Core Concept: **Trigonometric Graph Properties**
    - Key Definition:
        - **Amplitude**: The maximum displacement from the central equilibrium axis (calculated as half the difference between maximum and minimum values).
        - **Period**: The width of the smallest interval of the independent variable over which the curve fully repeats itself.
        - **Axis of Curve**: The horizontal line $y = c$ passing directly through the vertical middle of the curve.
        - _Detail/Fine Print_: Tangent graphs have no amplitude since they increase and decrease infinitely toward vertical asymptotes.
- Core Concept: **Transformations of Sinusoidal Curves**
    - Key Formula: For the transformed equations $y = a\sin bx + c$ and $y = a\cos bx + c$: $$\text{Amplitude} = |a|$$ $$\text{Period } (T) = \frac{360^\circ}{b} \quad \text{or} \quad \frac{2\pi}{b}$$ $$\text{Equation of Axis} \implies y = c$$
        - _Detail/Fine Print_: The term $a$ acts as a vertical stretch factor, $b$ acts as a horizontal stretch factor of $\frac{1}{b}$, and $c$ acts as a vertical translation.
- Core Concept: **Tangent Graphs**
    - Key Formula: For $y = a\tan bx + c$, the period is: $$\text{Period } (T) = \frac{180^\circ}{b} \quad \text{or} \quad \frac{\pi}{b}$$
        - _Detail/Fine Print_: Vertical asymptotes occur where the argument $bx$ is an odd multiple of $90^\circ$ (or $\frac{\pi}{2}$).

---

📝 Worked Examples per Question Type

Type 1: Evaluating Complementary and Ratios of Triangle Ratios

- **Question**: Given that $\sin A = \frac{4}{5}$ and $A$ is an acute angle, evaluate without a calculator: (i) $\tan A$, (ii) $\tan(90^\circ-A)$, and (iii) $\cos(90^\circ-A) + 3\sin A$.
- **Step-by-Step Solution**:
    1. Sketch a right-angled triangle with acute angle $A$. Since $\sin A = \frac{\text{Opp}}{\text{Hyp}} = \frac{4}{5}$, set the opposite side to 4 and the hypotenuse to 5.
    2. Use Pythagoras' Theorem to solve for the adjacent side: $$\text{Adjacent} = \sqrt{5^2 - 4^2} = \sqrt{9} = 3$$
    3. Evaluate the parts:
        - (i) $\tan A = \frac{\text{Opp}}{\text{Adj}} = \frac{4}{3}$
        - (ii) Apply the complementary identity: $\tan(90^\circ-A) = \frac{1}{\tan A} = \frac{3}{4}$
        - (iii) Apply the complementary identity $\cos(90^\circ-A) = \sin A$: $$\cos(90^\circ-A) + 3\sin A = \sin A + 3\sin A = 4\sin A = 4\left(\frac{4}{5}\right) = \frac{16}{5} = 3\frac{1}{5}$$

Type 2: Quadrant Determination & Evaluating Sign Ratios

- **Question**: Given that $\sin\theta = -\frac{2}{3}$ and $\tan\theta < 0$, find in exact form: (i) $\cos\theta$, and (ii) $\tan\theta$.
- **Step-by-Step Solution**:
    1. Determine the quadrant of $\theta$:
        - $\sin\theta < 0 \implies$ Quadrant 3 or Quadrant 4.
        - $\tan\theta < 0 \implies$ Quadrant 2 or Quadrant 4.
        - Therefore, $\theta$ must lie in **Quadrant 4**.
    2. Find the adjacent side length of the reference triangle. The basic angle $\alpha$ satisfies $\sin\alpha = \frac{2}{3}$ (Opposite = 2, Hypotenuse = 3): $$\text{Adjacent} = \sqrt{3^2 - 2^2} = \sqrt{5}$$
    3. Apply Quadrant 4 signs (where Cosine is positive and Tangent is negative):
        - (i) \(\cos\theta = +\frac{\text{Adj}}{\text{Hyp}} = \frac{\sqrt{5}}{3}\]
        - (ii) \(\tan\theta = -\frac{\text{Opp}}{\text{Adj}} = -\frac{2}{\sqrt{5}} = -\frac{2\sqrt{5}}{5}\]

Type 3: Composite Principal Values

- **Question**: Find the exact value of $\tan^{-1}(-\sqrt{3}) - \sin^{-1}\left(-\frac{1}{\sqrt{2}}\right)$ in radians.
- **Step-by-Step Solution**:
    1. Find the principal value of the first term, restricted to $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$: $$\tan^{-1}(-\sqrt{3}) = -\frac{\pi}{3}$$
    2. Find the principal value of the second term, restricted to $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$: $$\sin^{-1}\left(-\frac{1}{\sqrt{2}}\right) = -\frac{\pi}{4}$$
    3. Compute the final difference: \[-\frac{\pi}{3} - \left(-\frac{\pi}{4}\right) = -\frac{\pi}{3} + \frac{\pi}{4} = \frac{-4\pi + 3\pi}{12} = -\frac{\pi}{12}\]

Type 4: Factorisable Equations & Quadrant Procedures

- **Question**: Solve $4\sin x\cos x - \cos x = 0$ for the domain $0^\circ \le x \le 360^\circ$.
- **Step-by-Step Solution**:
    1. Factorise the common trigonometric term $\cos x$: $$\cos x(4\sin x - 1) = 0$$
    2. Split into two independent cases:
        - **Case 1**: $\cos x = 0$
            - From basic quadrantal values, the solutions are: $$x = 90^\circ, \quad x = 270^\circ$$
        - **Case 2**: $4\sin x - 1 = 0 \implies \sin x = 0.25$
            - Identify quadrants: $\sin x > 0 \implies$ Quadrants 1 and 2.
            - Calculate basic angle: $\alpha = \sin^{-1}(0.25) \approx 14.48^\circ$.
            - Determine solutions:
                - Q1: $x = \alpha \approx 14.5^\circ$
                - Q2: $x = 180^\circ - 14.48^\circ \approx 165.5^\circ$
    3. Combine all solutions within the domain: $$x = 14.5^\circ, \quad 90^\circ, \quad 165.5^\circ, \quad 270^\circ$$

Type 5: Graph Sketching and Amplitude/Period Parameters

- **Question**: Sketch the graph of $y = 4 - 3\sin \theta$ for $0^\circ \le \theta \le 360^\circ$. State the amplitude, period, and equation of the axis of the curve.
- **Step-by-Step Solution**:
    1. Identify parameters from the transformation equation $y = -3\sin\theta + 4$:
        - **Amplitude**: $|a| = |-3| = 3$
        - **Period**: $\frac{360^\circ}{b} = \frac{360^\circ}{1} = 360^\circ$
        - **Axis of Curve**: $y = c \implies y = 4$
    2. Determine critical plotting coordinates (Max/Min boundaries):
        - Maximum value $= c + |a| = 4 + 3 = 7$
        - Minimum value $= c - |a| = 4 - 3 = 1$
    3. Sketching details:
        - Because of the negative sign in $-3\sin\theta$, the sine curve is reflected across the horizontal axis of the curve $y = 4$ (starts at midline (0,4), goes _down_ to minimum (90,1), back to midline (180,4), up to maximum (270,7), and terminates at midline (360,4)).

---

⚠️ Common Mistakes Students Make on Exams

- **Quadrant Errors with Calculator Input**: Finding the basic angle using a negative value directly in the calculator (e.g., calculating $\sin^{-1}(-0.5) = -30^\circ$ and using that as $\alpha$ instead of the absolute value $\alpha = 30^\circ$). Always calculate with absolute positive values to find the basic acute angle first.
- **Missing Alternate Quadrant Solutions**: Only writing down a single root (typically Quadrant 1) from the calculator and failing to find the secondary quadrant solution (e.g., writing only $x = 30^\circ$ for $\sin x = 0.5$ and forgetting $x = 150^\circ$).
- **Inventing Tangent Amplitudes**: Stating that a tangent curve has an amplitude because it has a coefficient $a$ (e.g., writing that $y = 3\tan x$ has an "amplitude of 3"). Tangent has no amplitude.
- **Misinterpreting Negative Angles in Domains**: Failing to adjust positive basic angles when domains include negative ranges (e.g., failing to calculate coterminal values like $-150^\circ$ and $-30^\circ$ when solving $\sin x = -0.5$ in the domain $[-360^\circ, 180^\circ]$).

---

🔗 Cross-References to Related Concepts

- **Topic 4 (Relations & Functions)**: Trigonometric domains must be restricted to their principal intervals to convert many-to-one trigonometric curves into one-to-one functions, making them invertible.
- **Topic 7 (Intermediate Trigonometry & Identities)**: Pythagorean, reciprocal, and quotient identities build directly on these basic acute triangle ratios to simplify complex expressions and prove proofs.