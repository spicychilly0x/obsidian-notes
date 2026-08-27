# Chapter 3 Exam Notes

Topic 3: Partial Fractions

1. Core Concept: Proper vs. Improper Fractions

- Core Concept: **Proper algebraic fraction**
    - Key Definition: A **proper algebraic fraction** is a rational expression $\frac{P(x)}{Q(x)}$ where the degree of the numerator polynomial $P(x)$ is strictly less than the degree of the denominator polynomial $Q(x)$.
        - _Detail/Fine Print_: If the degree of the numerator is greater than or equal to the degree of the denominator, the fraction is an **improper algebraic fraction** and cannot be decomposed directly.
- Core Concept: **Improper fraction conversion**
    - Key Formula: Improper fractions must be divided using polynomial long division to express them as the sum of a polynomial quotient and a proper fraction before decomposing: $$\frac{P(x)}{Q(x)} = Q_{\text{quotient}}(x) + \frac{R(x)}{Q(x)}$$
        - _Detail/Fine Print_: In this converted form, the remainder polynomial $R(x)$ will satisfy the condition $\text{deg } R(x) < \text{deg } Q(x)$, making the fractional term proper.

---

2. Core Concept: Partial Fraction Decomposition Cases

- Core Concept: **Case I — Distinct Linear Factors**
    - Key Formula: For a proper fraction whose denominator consists of distinct linear factors, the template is: $$\frac{px+q}{(ax+b)(cx+d)} = \frac{A}{ax+b} + \frac{B}{cx+d}$$
        - _Detail/Fine Print_: Each unique linear factor in the denominator contributes exactly one partial fraction with a constant numerator.
- Core Concept: **Case II — Repeated Linear Factors**
    - Key Formula: For a denominator with a repeated linear factor $(ax+b)^2$, the decomposition template is: $$\frac{px^2+qx+r}{(ax+b)^2(cx+d)} = \frac{A}{ax+b} + \frac{B}{(ax+b)^2} + \frac{C}{cx+d}$$
        - _Detail/Fine Print_: A repeated factor of power $n$ requires setting up $n$ individual partial fractions with denominators increasing in power from $1$ up to $n$.
- Core Concept: **Case III — Non-Factorisable Quadratic Factors**
    - Key Formula: For a denominator with a quadratic factor $(ax^2+bx+c)$ that cannot be factorised over real numbers, the template is: $$\frac{px^2+qx+r}{(dx+e)(ax^2+bx+c)} = \frac{A}{dx+e} + \frac{Bx+C}{ax^2+bx+c}$$
        - _Detail/Fine Print_: The numerator above a non-factorisable quadratic factor of degree 2 must be assumed to be a linear expression of the form $Bx+C$ (degree 1).

---

3. Core Concept: Rational Function Asymptotes

- Core Concept: **Vertical asymptotes**
    - Key Definition: A **vertical asymptote** is a vertical line $x = k$ that the rational curve approaches but never crosses, found by setting the fully-simplified denominator of the function to zero.
        - _Detail/Fine Print_: Any value of $x$ that makes the denominator zero (and does not cancel with a factor in the numerator) defines a vertical asymptote.
- Core Concept: **Horizontal asymptotes**
    - Key Formula: The horizontal line $y = L$ that the curve approaches as $x \to \pm\infty$ is determined by comparing the polynomial degrees: $$\text{If } \text{deg } P(x) < \text{deg } Q(x) \implies y = 0$$ $$\text{If } \text{deg } P(x) = \text{deg } Q(x) \implies y = \frac{a_n}{b_n}$$
        - _Detail/Fine Print_: If $\text{deg } P(x) > \text{deg } Q(x)$, no horizontal asymptote exists; instead, the graph possesses an oblique or curvilinear asymptote.

---

🛠️ Numbered Procedure: Expressing an Algebraic Fraction as Partial Fractions

1. **Identify proper or improper status**: Compare the degrees of the numerator $P(x)$ and denominator $Q(x)$. If improper, use polynomial long division to rewrite the fraction as $Q_{\text{quotient}}(x) + \frac{R(x)}{Q(x)}$.
2. **Factorise the denominator**: Completely factorise $Q(x)$ into linear and non-factorisable quadratic factors.
3. **Set up the template**: Write the proper fraction portion as a sum of partial fractions with unknown constants (e.g., $A, B, C$) based on Case I, II, or III rules.
4. **Form a polynomial identity**: Multiply both sides of the template by the common denominator $Q(x)$ to clear all fractions.
5. **Solve for unknown constants**: Use the **substitution method** (substituting roots of linear terms) or the **comparing coefficients method** (expanding and equating coefficients of identical powers of $x$), or a hybrid of both.
6. **State the final decomposition**: Substitute the solved values of the constants back into the template.

---

📝 Worked Examples per Question Type

Type 1: Distinct Linear Factors (Case I)

- **Question**: Express $\frac{16x-28}{(x-1)(x+3)}$ as partial fractions.
- **Step-by-Step Solution**:
    1. Set up the template for distinct linear factors: $$\frac{16x-28}{(x-1)(x+3)} = \frac{A}{x-1} + \frac{B}{x+3}$$
    2. Multiply by the LCD $(x-1)(x+3)$ to clear fractions: $$16x - 28 = A(x+3) + B(x-1)$$
    3. Substitute $x = 1$ to eliminate $B$: $$16(1) - 28 = A(1+3) \implies -12 = 4A \implies A = -3$$
    4. Substitute $x = -3$ to eliminate $A$: $$16(-3) - 28 = B(-3-1) \implies -76 = -4B \implies B = 19$$
    5. Write the final proper decomposition: $$\frac{16x-28}{(x-1)(x+3)} = -\frac{3}{x-1} + \frac{19}{x+3}$$

Type 2: Repeated Linear Factors (Case II)

- **Question**: Express $\frac{2x+3}{(x-4)^2}$ as partial fractions.
- **Step-by-Step Solution**:
    1. Set up the template with ascending powers of the repeated factor: $$\frac{2x+3}{(x-4)^2} = \frac{A}{x-4} + \frac{B}{(x-4)^2}$$
    2. Multiply by $(x-4)^2$ to form the identity: $$2x + 3 = A(x-4) + B$$
    3. Substitute $x = 4$ to find $B$: $$2(4) + 3 = B \implies B = 11$$
    4. Substitute $x = 0$ and $B = 11$ to find $A$: $$2(0) + 3 = A(0-4) + 11 \implies 3 = -4A + 11 \implies -8 = -4A \implies A = 2$$
    5. State the final decomposition: $$\frac{2x+3}{(x-4)^2} = \frac{2}{x-4} + \frac{11}{(x-4)^2}$$

Type 3: Non-Factorisable Quadratic Factors (Case III)

- **Question**: Express $\frac{17x^2+23x+10}{(3x+4)(x^2+3x+7)}$ as partial fractions.
- **Step-by-Step Solution**:
    1. Set up the template with a linear numerator over the quadratic factor: $$\frac{17x^2+23x+10}{(3x+4)(x^2+3x+7)} = \frac{A}{3x+4} + \frac{Bx+C}{x^2+3x+7}$$
    2. Multiply both sides by the denominator to form the identity: $$17x^2+23x+10 = A(x^2+3x+7) + (Bx+C)(3x+4)$$
    3. Substitute $x = -\frac{4}{3}$ to isolate $A$: $$17\left(-\frac{4}{3}\right)^2 + 23\left(-\frac{4}{3}\right) + 10 = A\left(\left(-\frac{4}{3}\right)^2 + 3\left(-\frac{4}{3}\right) + 7\right)$$ $$\frac{272}{9} - \frac{276}{9} + \frac{90}{9} = A\left(\frac{16}{9} - \frac{36}{9} + \frac{63}{9}\right) \implies \frac{86}{9} = A\left(\frac{43}{9}\right) \implies A = 2$$
    4. Compare the coefficients of $x^2$ to find $B$: $$17 = A + 3B \implies 17 = 2 + 3B \implies 15 = 3B \implies B = 5$$
    5. Compare the constant terms to find $C$: $$10 = 7A + 4C \implies 10 = 7(2) + 4C \implies 10 = 14 + 4C \implies -4 = 4C \implies C = -1$$
    6. State the final decomposition: $$\frac{17x^2+23x+10}{(3x+4)(x^2+3x+7)} = \frac{2}{3x+4} + \frac{5x-1}{x^2+3x+7}$$

Type 4: Improper Rational Expressions (Long Division First)

- **Question**: Express $\frac{4x^3+10x+4}{2x^2+x}$ as partial fractions.
- **Step-by-Step Solution**:
    1. Divide the cubic numerator by the quadratic denominator using long division: $$\frac{4x^3+10x+4}{2x^2+x} = 2x - 1 + \frac{11x+4}{2x^2+x}$$
    2. Factorise the denominator of the proper remainder fraction: $$2x^2 + x = x(2x+1)$$
    3. Set up the Case I template for the remainder fraction: $$\frac{11x+4}{x(2x+1)} = \frac{A}{x} + \frac{B}{2x+1}$$
    4. Form the polynomial identity: $$11x + 4 = A(2x+1) + Bx$$
    5. Substitute $x = 0$ to isolate $A$: $$11(0) + 4 = A(2(0)+1) \implies A = 4$$
    6. Substitute $x = -\frac{1}{2}$ to isolate $B$: $$11\left(-\frac{1}{2}\right) + 4 = B\left(-\frac{1}{2}\right) \implies -\frac{3}{2} = -\frac{1}{2}B \implies B = 3$$
    7. Combine the quotient from step 1 with the decomposed terms: $$\frac{4x^3+10x+4}{2x^2+x} = 2x - 1 + \frac{4}{x} + \frac{3}{2x+1}$$

---

⚠️ Common Mistakes Students Make on Exams

- **Decomposing Improper Fractions Directly**: Forgetting to check if the polynomial degree of the numerator is equal to or greater than the denominator before setting up partial fraction templates. Long division must be performed first.
- **Incorrect Case III Numerator Setup**: Placing a simple constant $B$ instead of a linear expression $Bx + C$ in the numerator of a partial fraction with a non-factorisable quadratic denominator.
- **Omitting Descending Powers in Case II**: Forgetting to set up separate partial fractions for each power of a repeated factor (e.g., decomposing $\frac{1}{(x-2)^2}$ as just $\frac{A}{x-2}$ or just $\frac{B}{(x-2)^2}$ instead of $\frac{A}{x-2} + \frac{B}{(x-2)^2}$).
- **Long Division Sign and Placeholder Errors**: Forgetting to write missing power terms as $0x^k$ during the division setup, or making sign mistakes during subtraction.

---

🔗 Cross-References to Related Concepts

- **Topic 1: Algebraic Fractions**: Algebraic fraction addition is the inverse operation of partial fraction decomposition.
- **Topic 2: Polynomials & Identities**: Polynomial long division is a key prerequisite to simplify improper rational functions before decomposition.
- **Topic 4: Graphs & Asymptotes**: Denominator roots from partial fractions correspond to vertical asymptotes on rational graphs.