# Chapter 7 Exam Notes

Topic 7: Intermediate Trigonometry

---

1. Core Concept: Reciprocal & Pythagorean Identities

- Core Concept: **Reciprocal Identities**
    - Key Definition: The three **reciprocal trigonometric functions** are defined as the mathematical reciprocals of the three primary trigonometric functions: $$\csc x = \frac{1}{\sin x}, \quad \sec x = \frac{1}{\cos x}, \quad \cot x = \frac{1}{\tan x} = \frac{\cos x}{\sin x}$$
        - _Detail/Fine Print_: These functions are mathematically undefined at any value of $x$ where their respective denominator function equals zero (e.g., $\csc x$ and $\cot x$ are undefined for $x = k\pi$, and $\sec x$ is undefined for $x = \frac{\pi}{2} + k\pi$).
- Core Concept: **Pythagorean Identities**
    - Key Formula: The three fundamental **Pythagorean identities** derived from the unit circle are: $$\sin^2 \theta + \cos^2 \theta = 1$$ $$1 + \tan^2 \theta = \sec^2 \theta$$ $$1 + \cot^2 \theta = \csc^2 \theta$$
        - _Detail/Fine Print_: These identities are used to transform terms involving squared trigonometric functions into alternative forms to facilitate factoring or cancellation.

---

2. Core Concept: Proving Trigonometric Identities

- Core Concept: **Trigonometric Identity Verification**
    - Key Definition: A **trigonometric identity** is an equation involving trigonometric ratios that remains true for all valid real values of the variables. Proving an identity requires algebraically manipulating only one side of the equation (the LHS or the RHS) until it matches the other side exactly.
        - _Detail/Fine Print_: It is a critical logical error to perform operations across the equals sign (such as cross-multiplying or shifting terms from LHS to RHS) because the equality has not yet been established.
- Core Concept: **Simplification Strategies**
    - Key Method: The three principal strategies for proving identities are:
        1. **Convert to basic functions**: Express all reciprocal functions, tangent, and cotangent in terms of sine and cosine.
        2. **Consolidate fractions**: Find a common denominator to combine separate terms into a single fraction.
        3. **Multiply by the conjugate**: Multiply both the numerator and the denominator of a term by the algebraic conjugate of the denominator (e.g., multiply by $1-\cos x$ when the denominator is $1+\cos x$) to create differences of squares that simplify using Pythagorean identities.
        4. _Detail/Fine Print_: It is always strategically easier to begin the proof with the more complex-looking side of the equation.

---

3. Core Concept: Solving Advanced Trigonometric Equations

- Core Concept: **Quadratic Form Equations**
    - Key Formula: Equations containing squared trigonometric terms are resolved by substituting Pythagorean identities to express the entire equation in terms of a single trigonometric ratio, resulting in a factorisable quadratic form: $$a \cdot f(\theta)^2 + b \cdot f(\theta) + c = 0 \implies (p \cdot f(\theta) + q)(r \cdot f(\theta) + s) = 0$$
        - _Detail/Fine Print_: Because the ranges of sine and cosine are restricted, any solved factor where $|\sin\theta| > 1$ or $|\cos\theta| > 1$ (e.g., $\sin\theta = 1.5$) yields no real solutions and must be formally rejected.
- Core Concept: **Multi-Angle Equations**
    - Key Formula: Equations where the argument contains a coefficient (e.g., $\sin k\theta = C$) must be solved by scaling the domain limits to find all valid roots for the compound argument first: $$\text{If } a \le \theta \le b \implies ka \le k\theta \le kb$$
        - _Detail/Fine Print_: Compressing the period to $\frac{360^\circ}{k}$ means there will be $k$ times as many solutions in the standard interval compared to a single-angle equation.

---

🛠️ Numbered Procedures

Procedure 1: Proving a Trigonometric Identity

1. **Identify the starting side**: Choose the more complex side (usually the Left-Hand Side, LHS).
2. **Apply substitution rules**: Express non-basic functions ($\tan x, \cot x, \sec x, \csc x$) in terms of $\sin x$ and $\cos x$.
3. **Unify fractional terms**: Find the Lowest Common Denominator (LCD) to combine any sum or difference of fractional terms.
4. **Use Pythagorean substitutions**: Replace squared terms using Pythagorean identities (e.g., substitute $1 - \cos^2 x$ with $\sin^2 x$) to reduce the numerator or denominator.
5. **Factorise and simplify**: Factorise algebraic expressions (such as differences of squares or perfect squares) and divide out common binomial or monomial factors.
6. **Verify the target**: Confirm that the simplified expression is identical to the opposite side of the equation.

Procedure 2: Solving Quadratic Trigonometric Equations

1. **Unify trigonometric terms**: Use Pythagorean identities to rewrite the equation in terms of a single trigonometric ratio (e.g., converting $2\cos^2 \theta + 5\sin \theta = 5$ entirely to sine).
2. **Set up quadratic form**: Group and rearrange all terms on one side of the equation to equal zero: $ay^2 + by + c = 0$, where $y$ represents the unified trigonometric function.
3. **Factorise the quadratic**: Factorise the trinomial into two linear binomial factors: $(py+q)(ry+s) = 0$.
4. **Filter impossible ratios**: Solve for $y$. Discard any solved values of $y$ that fall outside the mathematical bounds $[-1, 1]$ for sine or cosine.
5. **Find basic reference angles**: For each remaining valid ratio, calculate the positive acute basic angle $\alpha = \sin^{-1}|y|$, $\cos^{-1}|y|$, or $\tan^{-1}|y|$.
6. **Calculate quadrant roots**: Based on the positive or negative sign of the solved ratio, identify the valid quadrants using the CAST diagram and compute all values of $\theta$ within the domain.

---

📝 Worked Examples per Question Type

Type 1: Proving Identities using Basic and Pythagorean substitutions

- **Question**: Prove the identity $\tan^2 x + \cot^2 x + 2 = \csc^2 x \sec^2 x$.
- **Step-by-Step Solution**:
    1. Start with the LHS and group the constant $2$ as $1 + 1$: $$\text{LHS} = (\tan^2 x + 1) + (\cot^2 x + 1)$$
    2. Substitute the Pythagorean identities $1 + \tan^2 x = \sec^2 x$ and $1 + \cot^2 x = \csc^2 x$: $$\text{LHS} = \sec^2 x + \csc^2 x$$
    3. Convert both terms into sines and cosines: $$\text{LHS} = \frac{1}{\cos^2 x} + \frac{1}{\sin^2 x}$$
    4. Combine the fractions using a common denominator $\sin^2 x \cos^2 x$: $$\text{LHS} = \frac{\sin^2 x + \cos^2 x}{\sin^2 x \cos^2 x}$$
    5. Apply the identity $\sin^2 x + \cos^2 x = 1$ in the numerator: $$\text{LHS} = \frac{1}{\sin^2 x \cos^2 x}$$
    6. Convert back to reciprocal functions: $$\text{LHS} = \csc^2 x \sec^2 x = \text{RHS}$$

Type 2: Proving Identities using Trinomial Factoring & Conjugates

- **Question**: Prove the identity $\frac{\sec^2 x + 2\tan x}{1-\tan^2 x} = \frac{\cos x + \sin x}{\cos x - \sin x}$.
- **Step-by-Step Solution**:
    1. Substitute the identity $\sec^2 x = 1 + \tan^2 x$ into the LHS: $$\text{LHS} = \frac{1 + \tan^2 x + 2\tan x}{1 - \tan^2 x}$$
    2. Recognise the numerator as a perfect square trinomial and the denominator as a difference of squares: $$\text{LHS} = \frac{(1 + \tan x)^2}{(1 - \tan x)(1 + \tan x)}$$
    3. Divide out the common binomial factor $(1 + \tan x)$: $$\text{LHS} = \frac{1 + \tan x}{1 - \tan x}$$
    4. Substitute $\tan x = \frac{\sin x}{\cos x}$: $$\text{LHS} = \frac{1 + \frac{\sin x}{\cos x}}{1 - \frac{\sin x}{\cos x}}$$
    5. Multiply both the numerator and denominator by $\cos x$ to clear fractions: $$\text{LHS} = \frac{\cos x + \sin x}{\cos x - \sin x} = \text{RHS}$$

Type 3: Solving Quadratic Equations with Pythagorean Substitutions

- **Question**: Solve $2\cos^2 \theta + 5\sin \theta = 5$ for $0^\circ \le \theta \le 360^\circ$.
- **Step-by-Step Solution**:
    1. Substitute $\cos^2 \theta = 1 - \sin^2 \theta$ to unify the ratios: $$2(1 - \sin^2 \theta) + 5\sin \theta = 5$$
    2. Expand and rearrange the terms into standard quadratic form: $$2 - 2\sin^2 \theta + 5\sin \theta = 5 \implies 2\sin^2 \theta - 5\sin \theta + 3 = 0$$
    3. Factorise the quadratic equation: $$(2\sin \theta - 3)(\sin \theta - 1) = 0 \implies \sin \theta = 1.5 \quad \text{or} \quad \sin \theta = 1$$
    4. Evaluate boundaries:
    5. For $\sin \theta = 1.5$: There are no real solutions (since maximum value is 1). Reject this branch.
    6. For $\sin \theta = 1$: This is a quadrantal value, giving $\theta = 90^\circ$.
    7. State the final valid solution: $$\theta = 90^\circ$$

Type 4: Solving Quadratic Trigonometric Equations with Tangent Formulas

- **Question**: Solve $2\tan\theta + 3 = \sec^2\theta$ for $0^\circ \le \theta \le 360^\circ$.
- **Step-by-Step Solution**:
    1. Substitute $\sec^2 \theta = 1 + \tan^2 \theta$ to unify ratios: $$2\tan\theta + 3 = 1 + \tan^2\theta \implies \tan^2\theta - 2\tan\theta - 2 = 0$$
    2. Use the quadratic formula to solve for $\tan \theta$: $$\tan \theta = \frac{-(-2) \pm \sqrt{(-2)^2 - 4(1)(-2)}}{2(1)} = 1 \pm \sqrt{3}$$
    3. Set up two independent cases:
        - **Case A**: $\tan \theta = 1 + \sqrt{3} \approx 2.732$ (Positive in Quadrants 1 and 3)
            - Calculate basic angle: $\alpha = \tan^{-1}(2.732) \approx 69.9^\circ$.
            - Solutions: $\theta = 69.9^\circ$ or $\theta = 180^\circ + 69.9^\circ = 249.9^\circ$.
        - **Case B**: $\tan \theta = 1 - \sqrt{3} \approx -0.732$ (Negative in Quadrants 2 and 4)
            - Calculate basic angle: $\alpha = \tan^{-1}(|-0.732|) \approx 36.2^\circ$.
            - Solutions: $\theta = 180^\circ - 36.2^\circ = 143.8^\circ$ or $\theta = 360^\circ - 36.2^\circ = 323.8^\circ$.
    4. Combine all solutions: $$\theta = 69.9^\circ, \quad 143.8^\circ, \quad 249.9^\circ, \quad 323.8^\circ$$

Type 5: "Hence" Proving and Multi-Angle Solving Questions

- **Question**: (i) Prove the identity $\sec \theta \csc \theta - \cot \theta = \tan \theta$. (ii) Hence, find all angles between $0^\circ$ and $360^\circ$ for which $\sec 2x \csc 2x - \cot 2x = 1$.
- **Step-by-Step Solution**:
    1. Prove part (i) by simplifying the LHS: $$\text{LHS} = \frac{1}{\cos \theta \sin \theta} - \frac{\cos \theta}{\sin \theta} = \frac{1 - \cos^2 \theta}{\sin \theta \cos \theta} = \frac{\sin^2 \theta}{\sin \theta \cos \theta} = \tan \theta = \text{RHS}$$
    2. Use this identity to substitute and simplify the equation in part (ii): $$\tan 2x = 1$$
    3. Scale the domain for $2x$: $$0^\circ \le x \le 360^\circ \implies 0^\circ \le 2x \le 720^\circ$$
    4. Calculate the basic reference angle: $$\alpha = \tan^{-1}(1) = 45^\circ$$
    5. Find all values of $2x$ where tangent is positive (Quadrants 1 and 3) up to $720^\circ$:
        - Q1: $2x = 45^\circ$ and $2x = 360^\circ + 45^\circ = 405^\circ$
        - Q3: $2x = 180^\circ + 45^\circ = 225^\circ$ and $2x = 540^\circ + 45^\circ = 585^\circ$
    6. Divide each multiple angle solution by $2$ to solve for $x$: $$x = 22.5^\circ, \quad 112.5^\circ, \quad 202.5^\circ, \quad 292.5^\circ$$

---

⚠️ Common Mistakes Students Make on Exams

- **Illegal Cross-Boundary Proofs**: Treating proving equations like standard algebraic equations by multiplying or moving terms across the equals sign. Always manipulate the sides independently.
- **Failing to Reject Impossible Solutions**: Stating angle roots for invalid quadratics (e.g., writing solutions for $\sin \theta = 1.5$ instead of rejecting it).
- **Missing Solutions from Multi-Angle Domain Scaling**: Neglecting to scale the domain bounds when working with multi-angle terms like $2x$, leading to half of the valid solutions being completely omitted from the final answer list.
- **Incorrect Identity Sign Conversions**: Mixing up signs when substituting Pythagorean identities (e.g., substituting $\tan^2 \theta$ with $1 - \sec^2 \theta$ instead of $\sec^2 \theta - 1$).
- **Calculator Quadrant Errors**: Relying on negative arguments when calculating basic angles on the calculator (e.g., finding $\sin^{-1}(-0.5) = -30^\circ$ instead of using absolute values to find acute angle $\alpha = 30^\circ$ first).

---

🔗 Cross-References to Related Concepts

- **Topic 6 (Basic Trigonometry)**: Applying supplementary identities, finding basic acute reference angles, and executing the CAST quadrant diagram rules are essential prerequisites for solving all trigonometric equations.
- **Topic 1 (Algebraic Fractions)**: Combining trigonometric fractions over lowest common denominators and multiplying by conjugates utilize the basic rules of algebraic rational fractions.
- **Topic 2 (Polynomial Division & Identities)**: Finding unknown constants by equating coefficients of polynomial identities mirrors the structural process used to verify complex trigonometric identities.