# Chapter 1 Exam Notes

Topic 1: Algebraic Fractions & Equations

1. Core Concept: Simplifying Algebraic Fractions

- Core Concept: **Simplifying algebraic fractions** is the process of reducing a rational algebraic expression to its lowest terms by dividing both the numerator and the denominator by their highest common factors1.
    - Key Formula: The Golden Rule of simplification is complete factorization of both the numerator and the denominator1: $$\frac{A \cdot C}{B \cdot C} = \frac{A}{B} \quad \text{for } B, C \neq 0$$
        - _Detail/Fine Print_: You can only cancel common factors that multiply the entire numerator or denominator; individual terms separated by addition or subtraction must never be cancelled1.
- Core Concept: Difference of Two Squares Factorization
    - Key Formula: Binomials representing a difference of squares must be factorized using the algebraic identity1: $$a^2 - b^2 = (a - b)(a + b)$$
        - _Detail/Fine Print_: This identity applies to higher power indices as well, such as: $$16x^{2n} - 9y^{2n} = (4x^n)^2 - (3y^n)^2 = (4x^n - 3y^n)(4x^n + 3y^n)$$1
- Core Concept: Sign Manipulation of Binomial Factors
    - Key Formula: Reversing the order of subtraction introduces a negative factor3: $$(y - x) = -(x - y)$$
        - _Detail/Fine Print_: Under odd powers, the negative sign is preserved outside the parenthesis, whereas under even powers, the negative sign is eliminated3: $$(y - x)^3 = -(x - y)^3 \quad \text{and} \quad (y - x)^2 = (x - y)^2$$

---

2. Core Concept: Operations on Algebraic Fractions

- Core Concept: Multiplication and Division
    - Key Formula: The product and quotient of algebraic fractions follow the standard rules34: $$\frac{a}{b} \times \frac{c}{d} = \frac{ac}{bd} \quad \text{and} \quad \frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \times \frac{d}{c} = \frac{ad}{bc}$$
        - _Detail/Fine Print_: Always factorize all quadratic and linear expressions fully before executing cross-cancellation13.
- Core Concept: Addition and Subtraction
    - Key Formula: Combining algebraic fractions requires finding a common denominator1: $$\frac{a}{c} \pm \frac{b}{d} = \frac{ad \pm bc}{cd}$$
        - _Detail/Fine Print_: Find the Lowest Common Denominator (LCD) of the fractions to prevent generating high-degree polynomial expressions in the numerator24.
- Core Concept: Complex Fractions
    - Key Formula: A complex fraction (fractions within a fraction) is simplified by first converting both the main numerator and main denominator into single unified fractions5: $$\frac{1 - \frac{1}{y}}{1 - \frac{1}{y^2}} = \frac{\frac{y-1}{y}}{\frac{y^2-1}{y^2}}$$
        - _Detail/Fine Print_: Once converted, apply the division rule by multiplying the numerator fraction by the reciprocal of the denominator fraction5.

---

3. Core Concept: Solving Algebraic Fractional Equations

- Core Concept: Expressions vs. Equations
    - Key Definition: An **algebraic expression** is a mathematical phrase containing variables, numbers, and operations that can only be simplified, whereas an **algebraic equation** contains an equals sign and can be solved to find the specific values of the unknown variable2.
        - _Detail/Fine Print_: Expressions are written without an equals sign (e.g., $x + 3$), whereas equations contain an equals sign (e.g., $x + 3 = 0$)2.
- Core Concept: Clearing Denominators
    - Key Formula: Fractional equations are solved by multiplying all terms by the LCD to eliminate the denominators26: $$\text{If } \frac{P(x)}{Q(x)} = \frac{R(x)}{S(x)} \implies P(x)S(x) = R(x)Q(x)$$
        - _Detail/Fine Print_: Multiplying by variable expressions clears denominators but can introduce extraneous roots6.
- Core Concept: Extraneous Solutions
    - Key Definition: An **extraneous solution** is a root obtained during the algebraic solving process that is invalid because it violates the initial domain restrictions of the equation6.
        - _Detail/Fine Print_: Any root that yields a denominator value of zero in the original equation (e.g., making $Q(x) = 0$ or $S(x) = 0$) must be formally rejected6.

---

🛠️ Numbered Procedure: Solving Algebraic Fractional Equations

1. **Identify domain restrictions**: Set each denominator in the original equation to zero to find values of the variable that are restricted (e.g., if denominator is $y + 1$, then $y \neq -1$)6.
2. **Determine the Lowest Common Denominator (LCD)** of all fractional terms in the equation26.
3. **Clear the denominators**: Multiply every term on both sides of the equation by the LCD to convert it into a polynomial equation26.
4. **Expand and collect like terms**: Rearrange the equation into standard polynomial form (e.g., linear $ax + b = 0$ or quadratic $ax^2 + bx + c = 0$)2.
5. **Solve the polynomial equation** using factorization, completing the square, or the quadratic formula26.
6. **Filter extraneous solutions**: Compare all obtained roots against the initial domain restrictions. Reject any root that makes an original denominator equal to zero6.
7. **State the final valid solution(s)**6.

---

📝 Worked Examples per Question Type

Type 1: Simplifying with Difference of Squares and Power Indices

- **Question**: Simplify $\frac{16x^{2n} - 9y^{2n}}{4x^{n+3} - 3x^3y^n}$1.
- **Step-by-Step Solution**:
    1. Factorize the difference of two squares in the numerator1: $$16x^{2n} - 9y^{2n} = (4x^n)^2 - (3y^n)^2 = (4x^n + 3y^n)(4x^n - 3y^n)$$
    2. Factorize the common term $x^3$ from the denominator1: $$4x^{n+3} - 3x^3y^n = x^3(4x^n - 3y^n)$$
    3. Divide out the common binomial factor $(4x^n - 3y^n)$ where $4x^n - 3y^n \neq 0$1: $$\frac{(4x^n + 3y^n)(4x^n - 3y^n)}{x^3(4x^n - 3y^n)} = \frac{4x^n + 3y^n}{x^3}$$

Type 2: Even and Odd Power Sign Manipulation

- **Question**: Simplify $(\frac{1}{x^2-y^2}) \cdot (\frac{y+x}{y-x})^2$3.
- **Step-by-Step Solution**:
    1. Factorize the difference of squares in the first denominator3: $$\frac{1}{(x-y)(x+y)} \cdot \frac{(y+x)^2}{(y-x)^2}$$
    2. Cancel the common term $(x+y)$ from the first denominator and the second numerator3: $$\frac{1}{x-y} \cdot \frac{y+x}{(y-x)^2}$$
    3. Apply the even-power sign rule $(y-x)^2 = (x-y)^2$ to unify the denominators3: $$\frac{y+x}{(x-y)(x-y)^2} = \frac{y+x}{(x-y)^3}$$

Type 3: Division and Multiplication with Sign Reversal

- **Question**: Simplify $\frac{x^2-16}{-x^2+x+2} \div \frac{x+4}{x-2}$3.
- **Step-by-Step Solution**:
    1. Factorize the quadratic numerator and denominator of the first fraction3: $$x^2 - 16 = (x-4)(x+4)$$ $$-x^2 + x + 2 = -(x^2 - x - 2) = -(x-2)(x+1)$$
    2. Invert the divisor and change the division to multiplication3: $$\frac{(x-4)(x+4)}{-(x-2)(x+1)} \times \frac{x-2}{x+4}$$
    3. Cancel the common binomial factors $(x+4)$ and $(x-2)$ where $x \neq -4, 2$3: $$\frac{x-4}{-(x+1)} = \frac{4-x}{x+1}$$

Type 4: Complex Fractions

- **Question**: Simplify $\frac{1 - \frac{1}{y}}{1 - \frac{1}{y^2}}$5.
- **Step-by-Step Solution**:
    1. Express both the numerator and the denominator as single unified fractions5: $$1 - \frac{1}{y} = \frac{y-1}{y}$$ $$1 - \frac{1}{y^2} = \frac{y^2-1}{y^2}$$
    2. Rewrite the division as a multiplication by the reciprocal of the denominator5: $$\frac{y-1}{y} \times \frac{y^2}{y^2-1}$$
    3. Factorize the difference of squares $y^2-1 = (y-1)(y+1)$ and cancel common factors $y$ and $(y-1)$5: $$\frac{y-1}{y} \times \frac{y^2}{(y-1)(y+1)} = \frac{y}{y+1}$$

Type 5: Solving Fractional Equations with Extraneous Solutions

- **Question**: Solve the equation $\frac{6}{y^2-1} = \frac{y-2}{y+1}$6.
- **Step-by-Step Solution**:
    1. Identify domain restrictions: $y \neq \pm 1$6.
    2. Factorize the denominator of the LHS: $$\frac{6}{(y-1)(y+1)} = \frac{y-2}{y+1}$$
    3. Multiply both sides by the LCD $(y-1)(y+1)$ to clear the denominators6: $$6 = (y-2)(y-1)$$
    4. Expand the RHS and rearrange into standard quadratic form6: $$6 = y^2 - 3y + 2 \implies y^2 - 3y - 4 = 0$$
    5. Factorize and solve the quadratic equation6: $$(y-4)(y+1) = 0 \implies y = 4 \quad \text{or} \quad y = -1$$
    6. Check restrictions: Since $y = -1$ is restricted, it must be rejected as an extraneous solution6.
    7. State final valid solution: $y = 4$6.

---

⚠️ Common Mistakes Students Make on Exams

- **Illegal Term Cancellation**: Attempting to cancel terms that are separated by addition or subtraction (e.g., incorrect cancellation of $x$ in $\frac{x+2}{x}$ to get $2$)1. Only factors can be cancelled1.
- **Neglecting Domain Restrictions**: Forgetting to check final solutions against the initial denominator restrictions, leading to the retention of invalid, extraneous solutions (e.g., keeping $y = -1$ in Type 5 above)6.
- **Incorrect Sign Manipulation**: Failing to introduce a negative sign when reversing the subtraction order of a binomial factor under odd powers (e.g., replacing $x-y$ with $y-x$ without multiplying by $-1$)3.
- **Failure to Distribute Negative Sign**: Forgetting to distribute the negative sign to all terms of a numerator when subtracting algebraic fractions2: \[-\frac{x-2}{x+1} = \frac{-x+2}{x+1} \quad \left(\text{NOT } \frac{-x-2}{x+1}\right)\]

---

🔗 Cross-References to Related Concepts

- **Topic 2: Polynomials & Identities**: Long division and factorisation methods for higher-degree polynomial numerators78.
- **Topic 3: Partial Fractions**: The reverse process of algebraic addition, decomposing a complex algebraic fraction into a sum of simpler algebraic fractions9.
- **Topic 4: Rational Functions**: Denominator restrictions define the vertical asymptotes and domain boundaries of rational graphs10.

---

📊 I can generate a practice quiz based on these algebraic fraction skills to help you test your understanding before the exam.