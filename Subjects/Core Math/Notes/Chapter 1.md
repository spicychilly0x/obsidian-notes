# Chapter 1 Exam Notes: Factorisation & Simplifying Algebraic Fractions

Section 1: Factorisation of Polynomials

- **Factorisation**1
    - **Factorisation**: The algebraic process of finding the constituent factors of a given number or algebraic expression so that it can be written as a product of simpler terms1.
        - Always check for a Greatest Common Factor (GCF) across all terms as the mandatory first step before applying other factorisation methods1.
- Greatest Common Factor (GCF)1
    - **Greatest Common Factor (GCF)**: The highest common factor shared between all numbers and variable terms of a polynomial expression1.
        - For numerical coefficients, identify the largest integer that divides all coefficients1. For variable factors, select the lowest power of each common variable present across all terms1.
- Factorisation by Regrouping1
    - **Regrouping**: An algebraic method where terms of an expression are rearranged and grouped in pairs or sets that share common factors, allowing a binomial common factor to be factored out1.
        - Terms must be grouped in a way that ensures each individual group yields an identical binomial common factor1.
- Factorisation Using Algebraic Identities2
    - **Algebraic Identities**: Standard algebraic equations representing perfect squares and difference of squares used to factorize quadratic and higher-degree polynomials2.
        - Key LaTeX formulas:
            - Perfect Square Trinomial (Positive): $a^2 + 2ab + b^2 = (a+b)^2$2
            - Perfect Square Trinomial (Negative): $a^2 - 2ab + b^2 = (a-b)^2$2
            - Difference of Two Squares: $a^2 - b^2 = (a-b)(a+b)$2
        - To apply perfect square identities, both the first and last terms of the trinomial must be positive perfect squares2.

---

Numbered Procedures

Procedural Topic: Factorisation by Regrouping1

1. **Group Terms**: Group terms of the expression into pairs or sets containing a common factor1.
2. **Extract GCF from Groups**: Factor out the GCF from each group separately1.
3. **Factor Out Binomial**: Identify and factor out the resulting common binomial factor from the entire expression1.

---

Worked Examples

Example 1: Greatest Common Factor (GCF)1

- **Question**: Factorize $2x^2y^3z^4 - 8xy^5z^2$ completely1.
- **Step-by-Step Reasoning**:
    1. **Identify coefficient GCF**: The GCF of $2$ and $8$ is $2$1.
    2. **Identify variable GCF**:
        - For $x$: the lowest power is $x^1$1.
        - For $y$: the lowest power is $y^3$1.
        - For $z$: the lowest power is $z^2$1.
        - The variable GCF is $xy^3z^2$1.
    3. **Form overall GCF**: $2xy^3z^2$1.
    4. **Divide terms by GCF**:
        - $\frac{2x^2y^3z^4}{2xy^3z^2} = xz^2$1
        - $\frac{-8xy^5z^2}{2xy^3z^2} = -4y^2$1
    5. **Write as product**: $2xy^3z^2(xz^2 - 4y^2)$1.

Example 2: Regrouping1

- **Question**: Factorize $6xz + xy + 2x^2 + 3yz$ completely1.
- **Step-by-Step Reasoning**:
    1. **Rearrange and group terms**: Group terms with common variables: $(6xz + 3yz) + (2x^2 + xy)$1.
    2. **Factor each group**:
        - Factor out $3z$ from the first group: $3z(2x + y)$1.
        - Factor out $x$ from the second group: $x(2x + y)$1.
    3. **Factor out the common binomial**: Combine the factored groups: $(3z + x)(2x + y)$1.

Example 3: Identity-Based Factorisation (Difference of Squares)2

- **Question**: Factorize $18x^2 - 2$ completely2.
- **Step-by-Step Reasoning**:
    1. **Extract numerical GCF**: Factor out the GCF $2$: $2(9x^2 - 1)$2.
    2. **Identify squares**: Recognize $9x^2 = (3x)^2$ and $1 = 1^2$2.
    3. **Apply difference of squares identity**: Use $a^2 - b^2 = (a-b)(a+b)$ where $a = 3x$ and $b = 1$: $2(3x-1)(3x+1)$2.

---

⚠️ Common Mistakes on Exams

- **Losing Solutions by Direct Division**2: Dividing both sides of an equation by a variable (e.g., solving $4x^2 = x$ by dividing by $x$ to get $4x = 1 \implies x = \frac{1}{4}$) is incorrect because it loses the valid solution $x = 0$2. Instead, move terms to one side and factorize: $x(4x-1) = 0 \implies x = 0$ or $x = \frac{1}{4}$2.
- **Incomplete Factorisation**2: Leaving terms partially factored (such as $2(9x^2-1)$) instead of resolving them down to their basic linear components ($2(3x-1)(3x+1)$)2.

---

🔗 Cross-References

- **GCF** $\leftrightarrow$ **Simplifying Algebraic Fractions**: Essential for identifying the common terms that must be factored out and cancelled13.
- **Factorisation of Quadratics** $\leftrightarrow$ **Solving Quadratic Equations**: Factoring expressions forms the basis for finding solutions to quadratic equations in completing the square and quadratic formula topics25.

---

---

Section 2: Simplifying and Operating on Algebraic Fractions

- Simplifying Algebraic Fractions3
    - **Simplifying Algebraic Fractions**: The mathematical process of dividing both the numerator and the denominator of an algebraic fraction by their common factors to reduce it to its lowest terms3.
        - Numerator and denominator terms must be completely factorized into product forms before any cancellation can occur3.
- Multiplication and Division of Algebraic Fractions3
    - **Fraction Multiplication/Division**: Arithmetic operations on algebraic fractions; division is executed by multiplying the first fraction by the reciprocal of the second3.
        - Key LaTeX formulas:
            - Multiplication: $\frac{A}{B} \times \frac{C}{D} = \frac{AC}{BD}$3
            - Division: $\frac{A}{B} \div \frac{C}{D} = \frac{A}{B} \times \frac{D}{C} = \frac{AD}{BC}$3
        - Cancel common terms across any numerator and denominator prior to executing final polynomial expansion to keep calculations simpler3.
- Addition and Subtraction of Algebraic Fractions3
    - **Fraction Addition/Subtraction**: Combining algebraic fractions over a single unified denominator3.
        - Key LaTeX formulas:
            - With Common Denominators: $\frac{A}{C} \pm \frac{B}{C} = \frac{A \pm B}{C}$3
            - With Different Denominators: $\frac{A}{B} \pm \frac{C}{D} = \frac{AD \pm BC}{BD}$3
        - Denominators must be fully factorized first to accurately identify the lowest common denominator (LCD)3.

---

Numbered Procedures

Procedural Topic: Operating on Algebraic Fractions34

1. **Fully Factorize**: Factorize all numerators and denominators completely using GCF, regrouping, or standard identities3.
2. **Determine the LCD**: Identify the lowest common denominator among all fractions3.
3. **Scale Numerators**: Multiply the numerator of each fraction by the factors missing from its original denominator to convert them to the LCD3.
4. **Combine and Expand**: Add or subtract the numerators over the common denominator, expanding and collecting like terms3.
5. **Simplify to Lowest Terms**: Factorize the resulting combined numerator and cancel any common factors with the denominator3.

---

Worked Examples

Example 4: Fraction Simplification with Regrouping2

- **Question**: Simplify $\frac{2a - 8ab}{2a + 1 - 8ab - 4b}$ completely2.
- **Step-by-Step Reasoning**:
    1. **Factorize the numerator**: Extract the GCF $2a$: $2a(1-4b)$2.
    2. **Factorize the denominator**: Group terms to find common factors:
        - $(2a - 8ab) + (1 - 4b) = 2a(1 - 4b) + 1(1 - 4b)$2
        - Combine terms: $(2a + 1)(1 - 4b)$2.
    3. **Substitute and cancel**: Substitute both factored forms and cancel the common factor $(1-4b)$2: $$\frac{2a(1-4b)}{(2a+1)(1-4b)} = \frac{2a}{2a+1} \quad$$2

Example 5: Multiplication and Division of Algebraic Fractions3

- **Question**: Simplify $\frac{x^2 - 2x - 3}{2x} \times \frac{x^2}{x^2 - 1}$ completely3.
- **Step-by-Step Reasoning**:
    1. **Factorize algebraic terms**:
        - Quadratic numerator: $x^2 - 2x - 3 = (x-3)(x+1)$3
        - Difference of squares denominator: $x^2 - 1 = (x-1)(x+1)$3
    2. **Express as a single product**: $$\frac{(x-3)(x+1)}{2x} \times \frac{x^2}{(x-1)(x+1)} \quad$$3
    3. **Cancel common terms**:
        - Cancel $(x+1)$ from the numerator and denominator3.
        - Cancel $x$ from $2x$ and $x^2$3.
    4. **Write final simplified form**: $$\frac{x(x-3)}{2(x-1)} = \frac{x^2 - 3x}{2x - 2} \quad$$3

Example 6: Addition/Subtraction with Sign-Adjusted Denominators4

- **Question**: Express $\frac{5}{2a-b} - \frac{3}{2b-4a}$ as a single fraction in its simplest form4.
- **Step-by-Step Reasoning**:
    1. **Analyze the denominators**: Factorize the second denominator to match the first: $2b - 4a = -2(2a - b)$4.
    2. **Adjust the negative sign**: Change the operation from subtraction to addition4: $$\frac{5}{2a-b} - \frac{3}{-2(2a-b)} = \frac{5}{2a-b} + \frac{3}{2(2a-b)} \quad$$4
    3. **Establish LCD**: The LCD is $2(2a-b)$4.
    4. **Convert fractions to LCD**: Multiply the first fraction by $\frac{2}{2}$4: $$\frac{10}{2(2a-b)} + \frac{3}{2(2a-b)} \quad$$4
    5. **Add numerators**: Combine over the common denominator4: $$\frac{10 + 3}{2(2a-b)} = \frac{13}{2(2a-b)} \quad$$4

---

⚠️ Common Mistakes on Exams

- **Cancelling Terms Separated by Addition/Subtraction**23: Attempting to cancel individual terms within a sum or difference (e.g., trying to cancel $2a$ directly in $\frac{2a-8ab}{2a+1-8ab-4b}$ before factorising) is algebraically invalid23. Only fully factored terms can be cancelled3.
- **Failure to Distribute Negative Signs**4: When subtracting algebraic fractions, failing to distribute the negative sign to all terms in the second fraction's numerator when combining them over a common denominator (e.g., in $\frac{2(2x+1) - 1 - (2x+1)^2}{(2x+1)^2}$, forgetting to apply the negative to all terms in the expansion of $(2x+1)^2 = 4x^2 + 4x + 1$)4.
- **Incorrect Sign Transformations**4: Misidentifying negative factor pairs (e.g., writing $2b - 4a = 2(2a-b)$ instead of $-2(2a-b)$), leading to incorrect operators4.

---

🔗 Cross-References

- **Difference of Squares** $\leftrightarrow$ **Simplifying Fractions**: Many addition, subtraction, multiplication, and division problems rely on $a^2-b^2 = (a-b)(a+b)$ to factorize quadratic terms in fractional denominators2more_horiz.
- **Algebraic Fractions** $\leftrightarrow$ **Quadratic Equations**: Fractional equations are typically solved by finding the LCD and multiplying across, which reduces them to quadratic equations solved in later chapters45.