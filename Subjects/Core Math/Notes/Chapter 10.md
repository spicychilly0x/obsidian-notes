# Chapter 10 Exam Notes: Mensuration

---

Section 1: Volume and Surface Area of Pyramids

- **Pyramids**
    - **Pyramid**: A solid in which one of the faces is a polygonal base, and the other triangular faces, known as **lateral faces**, meet at a common vertex called the **apex** opposite the base.
        - **Right Pyramid**: A pyramid where the **apex** is positioned vertically directly above the geometric centre of the base.
    - **Volume of a Pyramid**
        - Key LaTeX formula: $$V_{\text{pyramid}} = \frac{1}{3} \times \text{Base Area} \times H$$
        - The height $H$ represents the vertical perpendicular height from the base to the apex, not the slant height along the triangular faces.
    - **Surface Area of a Pyramid**
        - Key LaTeX formula: $$\text{Total Surface Area} = \text{Base Area} + \text{Area of all lateral faces}$$
        - For a right pyramid with a regular polygon base, all lateral triangular faces are congruent isosceles triangles.

---

Section 2: Volume and Surface Area of Cones

- **Cones**
    - **Cone**: A 3D solid with a circular base and a curved face tapering to a vertex (or **apex**) opposite the base.
        - The perpendicular height $h$ is the vertical distance from the apex to the center of the base. The **slant height** $l$ is the straight-line distance from the apex to any point on the circumference of the base.
    - **Volume of a Cone**
        - Key LaTeX formula: $$V_{\text{cone}} = \frac{1}{3}\pi r^2 h$$
        - A cone’s volume is exactly one-third the volume of a cylinder with an identical radius and height.
    - **Surface Area of a Cone**
        - Key LaTeX formulas:
            - Curved Surface Area (CSA): $\text{CSA} = \pi r l$
            - Total Surface Area (TSA): $\text{TSA} = \pi r^2 + \pi r l$
        - The vertical height $h$, radius $r$, and slant height $l$ always form a right-angled triangle, satisfying: $$l = \sqrt{r^2 + h^2}$$
- **Truncation and Frustums**
    - **Frustum**: The remaining lower portion of a cone (or pyramid) after the top part has been sliced off by a plane parallel to its base.
        - Solving frustum parameters relies on using similar triangles to relate the dimensions of the removed upper cone to the original large cone.

---

Section 3: Volume and Surface Area of Spheres & Hemispheres

- **Spheres**
    - **Sphere**: A 3D solid where all points on the outer surface are at a constant distance, known as the **radius**, from a fixed internal point called the **centre**.
        - A line segment joining two points on the outer surface and passing through the centre is a **diameter**.
    - **Volume of a Sphere**
        - Key LaTeX formula: $$V_{\text{sphere}} = \frac{4}{3}\pi r^3$$
        - Archimedes discovered that a sphere's volume is exactly $\frac{2}{3}$ the volume of a cylinder that fits tightly around it (with radius $r$ and height $2r$).
    - **Surface Area of a Sphere**
        - Key LaTeX formula: $$\text{Surface Area} = 4\pi r^2$$
        - The outer surface area of a sphere of radius $r$ is equivalent to the curved surface area of a cylinder with base radius $r$ and height $2r$.
- **Hemispheres**
    - **Hemisphere**: A solid representing exactly half of a sphere.
        - Key LaTeX formulas:
            - Volume of a Hemisphere: $V = \frac{2}{3}\pi r^3$
            - Curved Surface Area of a Hemisphere: $\text{CSA} = 2\pi r^2$
            - Total Surface Area of a Solid Hemisphere: $\text{TSA} = 3\pi r^2$
        - The total surface area of a solid hemisphere includes both its curved dome surface ($2\pi r^2$) and its flat circular base ($\pi r^2$).

---

Section 4: Composite Solids

- **Composite Solids**
    - **Composite Solid**: A solid object constructed by combining two or more simple 3D geometric shapes.
        - The volume of a composite solid is the sum of the volumes of its constituent parts.
        - The total surface area of a composite solid is the sum of the **outer exposed surfaces** only; any shared internal boundaries must be excluded.

---

Numbered Procedures

Procedural Topic: Solving a Cone Frustum

1. **Identify Similar Triangles**: Establish the linear scale factor of the original large cone and the removed small cone using the ratio of their radii: $$k = \frac{r_{\text{small}}}{R_{\text{large}}}$$
2. **Calculate Missing Heights**: Relate the vertical heights using the scale factor: $$h_{\text{small}} = k \times H_{\text{large}} \quad \text{and} \quad H_{\text{frustum}} = H_{\text{large}} - h_{\text{small}}$$
3. **Compute Volume of Frustum**: Calculate the difference between the volumes of the two cones: $$V_{\text{frustum}} = \frac{1}{3}\pi R_{\text{large}}^2 H_{\text{large}} - \frac{1}{3}\pi r_{\text{small}}^2 h_{\text{small}}$$
4. **Compute Curved Surface Area of Frustum**: Calculate the difference between the curved surface areas using their respective slant heights: $$\text{CSA}_{\text{frustum}} = \pi R_{\text{large}} L_{\text{large}} - \pi r_{\text{small}} l_{\text{small}}$$

---

Worked Examples

Example 1: Oblique Base Pyramid Volume (using Right-Angled Trig)

- **Question**: A pyramid $OABC$ has a horizontal right-angled triangular base $ABC$ with $\angle ACB = 90^\circ$, $AC = 4\text{ cm}$, and $\angle CAB = 30^\circ$. The vertical edge $OC$ has a height of $10\text{ cm}$. Calculate the volume of the pyramid to 1 decimal place (use $\tan 30^\circ = 0.577$).
- **Step-by-Step Reasoning**:
    1. **Find the base length** $BC$: Use the tangent ratio in right-angled $\Delta ABC$: $$\tan 30^\circ = \frac{BC}{AC} \implies BC = 4 \times \tan 30^\circ = 4(0.577) = 2.308\text{ cm}$$
    2. **Calculate the base area (Area of** $\Delta ABC$**)**: $$\text{Base Area} = \frac{1}{2} \times \text{base} \times \text{height} = \frac{1}{2} \times AC \times BC = \frac{1}{2} \times 4 \times 2.308 = 4.616\text{ cm}^2$$
    3. **Apply the pyramid volume formula**: $$V = \frac{1}{3} \times \text{Base Area} \times H = \frac{1}{3} \times 4.616 \times 10 \approx 15.4\text{ cm}^3$$

Example 2: Frustum with a Drilled Cylindrical Hole

- **Question**: A solid right circular cone of base radius $9\text{ cm}$ and height $12\text{ cm}$ is sliced parallel to its base to form a smaller upper cone of radius $3\text{ cm}$ and a lower frustum. A cylindrical hole of radius $3\text{ cm}$ is drilled vertically through the center of the frustum. Find the remaining volume of the frustum in terms of $\pi$.
- **Step-by-Step Reasoning**:
    1. **Calculate the total volume of the large cone**: $$V_{\text{large}} = \frac{1}{3}\pi R^2 H = \frac{1}{3}\pi (9^2)(12) = 324\pi\text{ cm}^3$$
    2. **Determine the height of the smaller upper cone using similar triangles**: $$\frac{r_{\text{small}}}{R_{\text{large}}} = \frac{3}{9} = \frac{1}{3} \implies h_{\text{small}} = \frac{1}{3} \times 12 = 4\text{ cm}$$
    3. **Calculate the volume of the small cone**: $$V_{\text{small}} = \frac{1}{3}\pi r^2 h = \frac{1}{3}\pi (3^2)(4) = 12\pi\text{ cm}^3$$
    4. **Calculate the volume of the solid frustum**: $$V_{\text{frustum}} = V_{\text{large}} - V_{\text{small}} = 324\pi - 12\pi = 312\pi\text{ cm}^3$$
    5. **Find the volume of the drilled cylinder**: The cylinder height matches the frustum height ($12 - 4 = 8\text{ cm}$), and its radius is $3\text{ cm}$. $$V_{\text{cylinder}} = \pi r^2 h = \pi (3^2)(8) = 72\pi\text{ cm}^3$$
    6. **Subtract the cylinder volume from the frustum volume**: $$V_{\text{remaining}} = 312\pi - 72\pi = 240\pi\text{ cm}^3$$

Example 3: Solid Hemisphere with a Hemispherical Hole

- **Question**: A solid hemisphere of diameter $10\text{ cm}$ has a concentric hemispherical hole of diameter $5\text{ cm}$ carved out of its flat top surface. Find the total surface area of this solid in terms of $\pi$.
- **Step-by-Step Reasoning**:
    1. **Determine the outer radius** $R$ **and inner radius** $r$: $$R = 5\text{ cm} \quad \text{and} \quad r = 2.5\text{ cm}$$
    2. **Calculate the curved surface area of the outer hemisphere**: $$\text{CSA}_{\text{outer}} = 2\pi R^2 = 2\pi (5^2) = 50\pi\text{ cm}^2$$
    3. **Calculate the curved surface area of the inner hemispherical hole**: $$\text{CSA}_{\text{inner}} = 2\pi r^2 = 2\pi (2.5^2) = 12.5\pi\text{ cm}^2$$
    4. **Calculate the area of the top flat ring (annulus)**: $$\text{Area}_{\text{flat}} = \pi R^2 - \pi r^2 = \pi (5^2) - \pi (2.5^2) = 25\pi - 6.25\pi = 18.75\pi\text{ cm}^2$$
    5. **Sum all surface components to find the total area**: $$\text{TSA} = \text{CSA}_{\text{outer}} + \text{CSA}_{\text{inner}} + \text{Area}_{\text{flat}} = 50\pi + 12.5\pi + 18.75\pi = 81.25\pi\text{ cm}^2$$

---

⚠️ Common Mistakes on Exams

- **Confusing Slant Height and Perpendicular Height**: Using slant height $l$ instead of vertical height $h$ in cone or pyramid volume formulas, or using vertical height $h$ instead of slant height $l$ for curved surface areas.
- **Including Shared Internal Boundaries in Surface Area**: Adding the flat circular interface area when calculating the total surface area of a composite solid (e.g., adding $\pi r^2$ for both the cylinder top and cone base when they are joined together).
- **Omitting the Flat Surface of Hemispheres**: Assuming the total surface area of a solid hemisphere is only $2\pi r^2$ (curved part) while forgetting the flat base area ($\pi r^2$), which makes the true total surface area $3\pi r^2$.
- **Failing to Halve Diameters**: Substituting diameter values directly into formulas instead of converting them to radii.
- **Inverting Ratios in Similar-Triangle Scaling**: Applying linear scale factors incorrectly when scaling heights of truncated parts (e.g., assuming the frustum height scaled directly by the radius ratio instead of finding the small cone height first).

---

🔗 Cross-References

- **Heights and Radii Right-Triangles** $\leftrightarrow$ **Pythagoras' Theorem (Chapter 5)**: Finding missing slant heights, vertical heights, or radii of cones and right pyramids relies on setting up right-angled triangles and applying Pythagoras' theorem.
- **Oblique Base Areas** $\leftrightarrow$ **Solutions of a Triangle (Chapter 5)**: Pyramids with non-standard triangular bases use Chapter 5 trigonometric ratios (like $\frac{1}{2}ab\sin C$ or right-angled trigonometry) to calculate base areas before finding volume.
- **Scale Factors** $\leftrightarrow$ **Similar Triangles**: Truncation calculations for frustums of cones and pyramids rely on similar triangle ratios to scale heights and areas.