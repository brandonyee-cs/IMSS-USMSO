# **Part V: Thermal Properties**

## **Material Response to Heat and Temperature**

### **Introduction to Part V**

Thermal properties describe how materials respond to changes in temperature and how they interact with heat energy. These properties are critical in countless applications, from designing engines that operate at extreme temperatures and selecting insulating materials for buildings, to processing materials using heat treatments and managing thermal expansion in precision instruments. This part explores key thermal phenomena, including how materials change size with temperature (thermal expansion), how much heat energy they can store (heat capacity), how efficiently they transfer heat (thermal conductivity), and how temperature can induce fundamental changes in their structure (phase transformations). Understanding these properties allows engineers to predict material behavior in thermal environments and select appropriate materials for specific thermal management tasks.

### **5.1 Thermal Expansion and Contraction: Dimensional Changes with Temperature**

Most solid materials expand when heated and contract when cooled. This phenomenon, known as thermal expansion, results from changes in the vibrations of atoms within the material.

#### **5.1.1 Atomic Mechanism of Thermal Expansion**

Recall the interatomic potential energy curve (U vs. r) discussed in Part II. This curve represents the potential energy as a function of the distance between atoms. The minimum of the curve corresponds to the equilibrium separation distance (r₀) at absolute zero temperature. As temperature increases, atoms gain thermal energy and vibrate with larger amplitudes around their equilibrium positions.

Crucially, the potential energy well is **asymmetric**: the repulsion force increases more steeply at distances shorter than r₀ than the attraction force decreases at distances larger than r₀. Because of this asymmetry, as the atoms vibrate with larger amplitudes (higher temperature), their *average* separation distance increases. This increase in the average interatomic distance manifests macroscopically as thermal expansion.

> **Key Concept**: Thermal expansion arises from increased atomic vibrations coupled with the asymmetric nature of the interatomic potential energy well.

#### **5.1.2 Coefficient of Thermal Expansion (α)**

The extent to which a material expands or contracts with temperature change is quantified by the **coefficient of thermal expansion (α)**.

*   **Linear Coefficient of Thermal Expansion (α<0xE2><0x82><0x97> or α)**: Describes the fractional change in length per degree change in temperature for a solid.
    α<0xE2><0x82><0x97> = (ΔL / L₀) / ΔT = (1 / L₀) * (dL / dT)
    Where:
    *   L₀ = Original length at a reference temperature
    *   ΔL = Change in length
    *   ΔT = Change in temperature

    Rearranging gives the practical formula for calculating length change:
    **ΔL = α<0xE2><0x82><0x97> * L₀ * ΔT**

*   **Volume Coefficient of Thermal Expansion (α<0xE1><0xB5><0xA3>)**: Describes the fractional change in volume per degree change in temperature.
    α<0xE1><0xB5><0xA3> = (ΔV / V₀) / ΔT = (1 / V₀) * (dV / dT)
    **ΔV = α<0xE1><0xB5><0xA3> * V₀ * ΔT**

*   **Relationship**: For isotropic materials (properties same in all directions), the volume coefficient is approximately three times the linear coefficient: **α<0xE1><0xB5><0xA3> ≈ 3α<0xE2><0x82><0x97>**.

*   **Units**: The units of α are reciprocal temperature, such as 1/°C, °C⁻¹, 1/K, or K⁻¹. Values are often expressed as ppm/°C (parts per million per degree Celsius, equivalent to 10⁻⁶ °C⁻¹).

#### **5.1.3 Comparison Across Material Classes**

The magnitude of α depends on the strength and symmetry of the atomic bonds:
*   **Polymers**: Generally have the **largest** α values. The weak secondary bonds between polymer chains allow for significant expansion as chain segments gain mobility with temperature.
*   **Metals**: Have **intermediate** α values. Metallic bonds are relatively strong, but the structure allows for expansion.
*   **Ceramics**: Generally have the **lowest** α values. Strong ionic/covalent bonds result in deeper, more symmetric potential energy wells, limiting expansion. Some ceramics (like fused silica) have near-zero expansion over certain temperature ranges.
*   **Composites**: Exhibit α values that depend on the coefficients of the constituent materials and their arrangement.

#### **5.1.4 Practical Implications**

Thermal expansion must be considered in many engineering designs:
*   **Thermal Stresses**: If a material is constrained from expanding or contracting freely, temperature changes can induce significant internal stresses (thermal stresses), potentially leading to buckling or fracture. (σ<0xE1><0xB5><0x8B><0xE2><0x82><0x95><0xE1><0xB5><0x89><0xE1><0xB5><0x93><0xE1><0xB5><0x8D><0xE1><0xB5><0x8B><0xE1><0xB5><0x8F> = E * α * ΔT for full constraint).
*   **Expansion Joints**: Gaps are intentionally left in structures like bridges, sidewalks, and railway tracks to allow room for expansion and prevent stress buildup.
*   **Bimetallic Strips**: Two metals with different α values bonded together will bend when heated or cooled due to differential expansion. Used in thermostats and thermometers.
*   **Dimensional Stability**: In precision instruments or applications involving sealing (like engine components), materials with low or matched thermal expansion are required.
*   **Composite Materials**: Mismatched thermal expansion between the matrix and reinforcement in composites can lead to internal stresses during temperature changes, potentially affecting interface integrity.

> **IMSS Olympiad Note: Thermal Expansion Calculations and Concepts**
> Be prepared to calculate changes in length (ΔL = αL₀ΔT) or volume (ΔV ≈ 3αL₀ΔT) given the coefficient, original dimension, and temperature change. Understand the atomic origin of expansion (asymmetric potential well) and the general ranking of α values for different material classes (Polymers > Metals > Ceramics). Recognize the importance of thermal expansion mismatch in composite materials and the potential for thermal stress generation.

### **5.2 Heat Capacity: Storing Thermal Energy**

Heat capacity relates the amount of heat energy added to a material to its resulting temperature increase. It quantifies a material's ability to store internal energy.

#### **5.2.1 Definition and Units**

*   **Heat Capacity (C)**: The amount of heat energy (Q) required to raise the temperature of a given amount of substance by one degree (ΔT).
    C = Q / ΔT
*   **Specific Heat Capacity (c)**: The heat capacity per unit mass of material. It is an intrinsic material property.
    c = Q / (m * ΔT)
    Where 'm' is the mass.
*   **Molar Heat Capacity (C<0xE2><0x82><0x98>)**: The heat capacity per mole of substance.
    C<0xE2><0x82><0x98> = Q / (n * ΔT)
    Where 'n' is the number of moles.
*   **Units**: Specific heat capacity (c) is typically measured in J/(kg·K) or J/(g·°C). Molar heat capacity (C<0xE2><0x82><0x98>) is in J/(mol·K).

Heat capacity can be measured at constant pressure (c<0xE1><0xB5><0xBD>) or constant volume (c<0xE1><0xB5><0xA3>). For solids and liquids, c<0xE1><0xB5><0xBD> and c<0xE1><0xB5><0xA3> are very similar; c<0xE1><0xB5><0xBD> is usually measured and reported.

#### **5.2.2 Physical Origin**

When heat energy is added to a solid, it increases the internal energy, primarily by increasing the vibrational energy of the atoms within the crystal lattice.
*   **Lattice Vibrations (Phonons)**: The primary mechanism for heat storage in most solids involves increasing the amplitude of atomic vibrations. These vibrations can be modeled as quantized energy packets called phonons.
*   **Electronic Contribution**: In metals, some heat energy can also be absorbed by the free electrons, increasing their kinetic energy. This contribution is usually small compared to the lattice contribution at room temperature but becomes significant at very low temperatures.

#### **5.2.3 Temperature Dependence**

Heat capacity is generally not constant but increases with temperature, especially at low temperatures.
*   **Low Temperatures**: c<0xE1><0xB5><0xA3> approaches zero as T approaches 0 K (Third Law of Thermodynamics). It increases rapidly, often proportional to T³, due to the quantization of lattice vibrations.
*   **High Temperatures**: c<0xE1><0xB5><0xA3> tends to level off at a relatively constant value. For many simple crystalline solids, this value approaches approximately **3R** per mole (where R is the ideal gas constant, ≈ 8.314 J/(mol·K)), a result known as the **Dulong-Petit law**. This corresponds to each atom having 3 vibrational degrees of freedom, each contributing kT of energy on average (k is Boltzmann's constant).

#### **5.2.4 Significance**

*   **Heating/Cooling Rates**: Materials with high heat capacity require more energy to heat up and release more energy when cooling down (they change temperature more slowly). Water has a notably high specific heat capacity.
*   **Thermal Energy Storage**: Materials with high heat capacity can store significant amounts of thermal energy.
*   **Thermal Analysis**: Techniques like Differential Scanning Calorimetry (DSC) measure heat capacity changes to identify phase transitions (like melting or glass transition) which involve absorption or release of heat.

> **IMSS Olympiad Note: Understanding Heat Capacity**
> Know the definition of specific heat capacity (c) and its units. Understand that it represents the energy needed to change temperature. Recognize that heat absorption primarily increases atomic vibrational energy (phonons) in solids. While complex calculations are less common, understand the concept and its role in thermal energy storage and temperature changes.

### **5.3 Heat Transfer and Thermal Conductivity: Moving Heat Through Materials**

Heat transfer is the movement of thermal energy from a hotter region to a colder region. There are three primary modes: conduction, convection, and radiation. In solid materials, **conduction** is typically the dominant mode.

#### **5.3.1 Modes of Heat Transfer (Brief Overview)**

*   **Conduction**: Heat transfer through direct contact, via collisions between adjacent atoms, molecules, or electrons, without bulk movement of the material. Dominant in solids.
*   **Convection**: Heat transfer via the movement of fluids (liquids or gases). Hotter fluid moves, carrying thermal energy with it. Occurs naturally (buoyancy-driven) or forced (by pumps/fans).
*   **Radiation**: Heat transfer via electromagnetic waves (primarily infrared) emitted by objects due to their temperature. Does not require a medium; can occur through vacuum.

#### **5.3.2 Heat Conduction and Fourier's Law**

Heat conduction in solids is governed by **Fourier's Law of Heat Conduction**. For steady-state, one-dimensional conduction:

q = -k * (dT / dx)

Where:
*   **q** = Heat flux (rate of heat transfer per unit area), W/m²
*   **k** = **Thermal Conductivity** of the material (a material property), W/(m·K)
*   **dT/dx** = Temperature gradient (rate of change of temperature with distance), K/m or °C/m

The negative sign indicates that heat flows from higher temperature to lower temperature (down the temperature gradient).

#### **5.3.3 Thermal Conductivity (k)**

*   **Definition**: Thermal conductivity (k) is a measure of a material's ability to conduct heat. High 'k' means efficient heat conduction (a thermal conductor); low 'k' means poor heat conduction (a thermal insulator).
*   **Mechanisms**: Heat is conducted in solids by two primary mechanisms:
    1.  **Lattice Vibrations (Phonons)**: Vibrating atoms transfer energy to adjacent atoms through the lattice. This is the primary mechanism in electrically insulating materials (ceramics, polymers).
    2.  **Electron Transport**: In metals, the free (delocalized) valence electrons can move rapidly through the lattice, carrying kinetic energy from hotter to colder regions. This is a very efficient mechanism.

#### **5.3.4 Comparison Across Material Classes**

The dominant conduction mechanism leads to significant differences in thermal conductivity:
*   **Metals**: Generally have the **highest** k values because the electron transport mechanism is highly effective. Good electrical conductors are usually good thermal conductors (Wiedemann-Franz Law relates the two).
*   **Ceramics**: Have **intermediate to low** k values. Heat transfer is primarily by phonons. Strong bonding can lead to efficient phonon transfer in some crystalline ceramics (e.g., AlN, SiC, BeO have relatively high k), but porosity and complex structures often limit conductivity. Glasses have particularly low k due to their amorphous structure scattering phonons effectively.
*   **Polymers**: Generally have the **lowest** k values. Heat transfer is by inefficient vibration and rotation of chain molecules. Amorphous structure and weak inter-chain forces hinder heat flow. Polymers are excellent thermal insulators.
*   **Composites**: Conductivity depends on the constituents and structure. Adding conductive fillers can increase k; adding insulating fillers or porosity decreases k.

#### **5.3.5 Factors Affecting Thermal Conductivity**

*   **Temperature**:
    *   *Metals*: k generally decreases slightly with increasing temperature (more lattice scattering impedes electrons).
    *   *Ceramics/Glasses*: k generally decreases with increasing temperature at moderate/high T (phonon-phonon scattering increases). At very low T, k increases from zero.
    *   *Polymers*: k may increase slightly with temperature above Tg as chain mobility increases.
*   **Structure**: Crystalline materials generally conduct heat better than amorphous materials (less phonon scattering).
*   **Defects/Impurities**: Point defects, dislocations, grain boundaries scatter both phonons and electrons, reducing k.
*   **Porosity**: Pores contain trapped gas (usually a poor conductor) and disrupt heat flow paths, significantly reducing the effective thermal conductivity of solids (e.g., insulating foams, refractory bricks).

> **IMSS Olympiad Note: Thermal Conductivity and Conduction**
> Understand Fourier's Law (q = -k * dT/dx) and the definition of thermal conductivity (k). Know the relative ranking of 'k' for material classes (Metals > Ceramics > Polymers) and the underlying reasons (electron transport vs. phonons). Recognize factors like porosity and crystallinity significantly impact conductivity. Be prepared for simple calculations using Fourier's Law or comparing conductivities.

### **5.4 Phase Transformations and Temperature Effects: Structural Changes**

Temperature changes can induce fundamental changes in the structure and phase of a material. A **phase** is a region within a material that is homogenous in structure and composition. A **phase transformation** occurs when a material changes from one phase to another, usually involving an abrupt change in properties.

#### **5.4.1 Key Temperature-Driven Transformations**

*   **Melting/Freezing (Solidification)**:
    *   **Transition**: Solid ↔ Liquid
    *   **Temperature**: Occurs at a distinct **Melting Point (Tm)** for crystalline materials.
    *   **Energy**: Involves absorption (melting) or release (freezing) of **Latent Heat of Fusion**. Volume change also occurs.
    *   **Mechanism**: Atoms gain enough thermal energy to overcome the fixed lattice forces and move more freely in the disordered liquid state.
*   **Boiling/Condensation**:
    *   **Transition**: Liquid ↔ Gas (Vapor)
    *   **Temperature**: Occurs at a distinct **Boiling Point (Tb)** (at a given pressure).
    *   **Energy**: Involves absorption (boiling) or release (condensation) of **Latent Heat of Vaporization**. Large volume change occurs.
    *   **Mechanism**: Molecules gain enough energy to overcome intermolecular forces and escape into the gaseous phase.
*   **Sublimation**:
    *   **Transition**: Solid → Gas (Directly)
    *   **Example**: Dry ice (solid CO₂) turning into CO₂ gas.
*   **Glass Transition**:
    *   **Transition**: Amorphous Solid (Glass) ↔ Supercooled/Rubbery Liquid
    *   **Temperature**: Occurs over a temperature range characterized by the **Glass Transition Temperature (Tg)**.
    *   **Characteristics**: Not a true first-order phase transition (no latent heat). Involves a change in slope for properties like volume or heat capacity vs. temperature. Represents onset of large-scale molecular/segmental motion in amorphous materials.
*   **Allotropic / Polymorphic Transformations**:
    *   **Transition**: Solid Phase₁ ↔ Solid Phase₂
    *   **Definition**: The ability of a solid material to exist in more than one crystal structure form is called **polymorphism** (for compounds) or **allotropy** (for elements). The transformation from one solid structure to another is driven by changes in temperature and/or pressure.
    *   **Mechanism**: Involves rearrangement of atoms into a different crystalline lattice. Often involves changes in density and other properties.
    *   **Examples**:
        *   **Iron (Fe)**: BCC (α-ferrite, < 912°C) → FCC (γ-austenite, 912-1394°C) → BCC (δ-ferrite, 1394-1538°C). These transformations are fundamental to the heat treatment of steels.
        *   **Carbon (C)**: Diamond (tetrahedral covalent network) and Graphite (layered hexagonal structure) are allotropes. Tin (Sn) exhibits a transformation from metallic white tin to brittle gray tin at low temperatures ("tin pest"). Zirconia (ZrO₂) undergoes phase transformations important for its use as a ceramic.
    *   **Significance**: These transformations are crucial for materials processing (e.g., heat treating steel relies on the α↔γ transformation) and can affect material stability and properties at different temperatures.

#### **5.4.2 Phase Diagrams**

Phase diagrams are graphical maps that show which phases are stable under different conditions of temperature, pressure, and composition. They are essential tools for understanding and predicting phase transformations, particularly in alloys. (Phase diagrams will be covered in more detail in Part VIII).

> **IMSS Olympiad Note: Understanding Phase Changes**
> Recognize the key temperature-driven transformations: melting (Tm), boiling (Tb), glass transition (Tg), and allotropic/polymorphic changes. Understand the difference between the sharp transition at Tm for crystalline materials and the gradual softening at Tg for amorphous materials. Be aware of important examples like the allotropy of iron, which is central to steel processing and properties.
