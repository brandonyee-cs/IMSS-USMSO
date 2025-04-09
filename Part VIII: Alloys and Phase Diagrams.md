# **Part VIII: Alloys and Phase Diagrams**

## **Understanding Material Mixtures**

### **Introduction to Part VIII**

Pure metals often lack the specific combination of properties required for demanding engineering applications. By intentionally mixing two or more elements, at least one of which is a metal, we create **alloys**, which frequently exhibit significantly enhanced properties compared to their constituent elements. Steel (iron-carbon alloy), brass (copper-zinc alloy), and aluminum alloys are prime examples that form the backbone of modern engineering.

Understanding the behavior of alloys requires knowing how different elements interact and arrange themselves at the atomic level when mixed. This often involves the formation of different **phases** – distinct, physically homogeneous regions within the material. **Phase diagrams** are powerful graphical tools that map the stable phases present in a material system as a function of temperature, composition, and sometimes pressure. They are indispensable for predicting the microstructure that forms during solidification or heat treatment and, consequently, for controlling the final properties of alloys. This part introduces the fundamental concepts of solutions and phases in alloys and focuses on the interpretation and application of binary phase diagrams, particularly the common eutectic type.

### **8.1 Solutions and Phases in Alloys: Defining the Mixture**

When elements are mixed to form an alloy, they can interact in various ways, leading to different structures and phases.

#### **8.1.1 Basic Definitions**

*   **Alloy**: A metallic substance composed of two or more elements, typically created by melting the components together. The primary component is usually a metal.
*   **System**: Refers to a specific body of material under consideration (e.g., the lead-tin alloy system) or a series of possible alloys consisting of the same components without regard to alloy composition (e.g., the iron-carbon system).
*   **Component**: The pure metals and/or nonmetals from which an alloy is composed (e.g., Copper and Zinc are the components of brass).
*   **Solvent**: In an alloy or solution, the component present in the greatest amount (often called the host atoms).
*   **Solute**: The component(s) present in minor concentrations.

#### **8.1.2 Solid Solutions**

Often, when a solute element is added to a solvent metal, the solute atoms dissolve within the host structure to form a **solid solution**. This means the solute atoms are randomly dispersed within the solvent's crystal lattice, creating a single, homogeneous solid phase whose composition can vary within limits. The crystal structure of the solvent is maintained. There are two main types:

*   **Substitutional Solid Solution**: Solute atoms *replace* solvent atoms on the crystal lattice sites.
    *   **Formation Factors (Hume-Rothery Rules)**: Extensive substitutional solubility typically occurs when the solute and solvent atoms have:
        1.  **Similar Atomic Radii**: Difference should ideally be < 15%. Significant differences cause lattice strain.
        2.  **Same Crystal Structure**: Metals with the same structure (e.g., FCC) dissolve more readily.
        3.  **Similar Electronegativity**: Large differences favor compound formation rather than solid solutions.
        4.  **Similar Valence**: Metals with the same valence are more likely to form extensive solid solutions.
    *   **Example**: Copper (FCC) and Nickel (FCC) have similar radii, electronegativity, and valence, and exhibit complete substitutional solubility across the entire composition range. Brass (Zinc solute in Copper solvent) has limited substitutional solubility.
*   **Interstitial Solid Solution**: Solute atoms are small enough to fit into the *interstitial spaces* (voids) between the solvent atoms in the lattice.
    *   **Formation Factors**: Requires the solute atom's radius to be significantly smaller than the solvent atom's radius (typically H, C, N, O as solutes in metals).
    *   **Solubility Limit**: Interstitial solubility is always limited because the interstitial sites are small, and introducing too many interstitial atoms causes significant lattice distortion.
    *   **Example**: Carbon (small atom) dissolves interstitially in Iron (larger atom) to form steel. The maximum solubility is limited (e.g., ~2.14 wt% C in FCC iron).

> **Key Concept**: Solid solutions are homogeneous mixtures at the atomic level within a single crystal structure. Their formation depends on factors like size, structure, and chemical similarity (Hume-Rothery rules for substitutional).

#### **8.1.3 Phases and Phase Equilibria**

*   **Phase**: A portion of a system that has uniform physical and chemical characteristics. It is structurally homogeneous and has a distinct boundary separating it from other phases. Examples include solid phases (like α-iron, γ-iron), liquid phase, gas phase. A single-phase system is homogeneous; systems with two or more phases are heterogeneous or mixtures.
*   **Phase Equilibrium**: A state where the phase characteristics of a system remain constant over time. Under equilibrium conditions, the **free energy** of the system is at a minimum for the given combination of temperature, pressure, and composition. While true equilibrium is often not fully achieved in practical situations (cooling rates can be too fast), equilibrium phase diagrams represent the stable state the system tends towards.
*   **Metastable State**: A non-equilibrium state that may persist indefinitely but has a higher free energy than the equilibrium state. A small input of energy might cause it to transform to the more stable state. Many useful materials exist in metastable states achieved through controlled processing (e.g., hardened steels).

#### **8.1.4 Intermediate Phases / Intermetallic Compounds**

In addition to solid solutions based on the host crystal structure, alloys can also form **intermediate phases** or **intermetallic compounds**. These are distinct solid phases with:
*   **Different Crystal Structure**: Their crystal structure is different from that of the pure components.
*   **Specific Stoichiometry**: Often occur at or near specific atomic ratios between the components (e.g., Mg₂Pb, Cu₃Al). They may exist over a narrow range of compositions or as a line compound with fixed stoichiometry.
*   **Bonding**: Can range from metallic to ionic or covalent in character.
*   **Properties**: Often hard and brittle compared to the constituent metals or solid solutions.

Intermediate phases appear as distinct regions on the phase diagram.

#### **8.1.5 Gibbs Phase Rule**

The **Gibbs Phase Rule** relates the number of phases present in a system at equilibrium to the number of degrees of freedom (variables like temperature, pressure, composition that can be changed independently without changing the number of phases). For systems where pressure is constant (common in materials science applications, often atmospheric pressure):

**P + F = C + 1**

Where:
*   **P**: Number of phases present at equilibrium.
*   **F**: Number of **degrees of freedom** (independent variables).
*   **C**: Number of **components** in the system (distinct chemical species).

*   **Interpretation**: This rule helps understand the conditions under which different numbers of phases can coexist. For a binary alloy (C=2):
    *   If one phase is present (P=1), then F = 2 + 1 - 1 = 2. Both temperature and composition can be varied independently within the single-phase region.
    *   If two phases coexist (P=2), then F = 2 + 1 - 2 = 1. Only one variable (either temperature or the composition of one phase) can be changed independently while maintaining two phases in equilibrium. If T is fixed, the compositions of the two phases are also fixed.
    *   If three phases coexist (P=3), then F = 2 + 1 - 3 = 0. This can only occur at a specific, fixed temperature and composition (an invariant point like a eutectic).

> **IMSS Olympiad Note: Basic Alloy Terminology**
> Understand the definitions of alloy, component, solid solution (substitutional vs. interstitial), phase, and intermediate phase. Recognize the factors favoring solid solution formation (Hume-Rothery). Know the Gibbs Phase Rule (P+F=C+1 for constant pressure) and its implications for the coexistence of phases in binary systems.

### **8.2 Binary Phase Diagrams: Mapping Alloy Behavior**

A **binary phase diagram** is a graphical map showing the stable phases and their equilibrium relationships as a function of **temperature** and **overall alloy composition** (for two components), usually at a fixed pressure (typically 1 atm).

#### **8.2.1 Axes and Regions**

*   **Temperature**: Usually plotted on the vertical axis.
*   **Composition**: Plotted on the horizontal axis, typically ranging from 0% Component B (100% Component A) on the left to 100% Component B (0% Component A) on the right. Composition can be expressed as weight percent (wt%) or atomic percent (at%).
*   **Phase Regions**: The diagram is divided into regions, each labeled with the phase(s) stable under the conditions of temperature and composition within that region. Regions can represent single phases (e.g., Liquid (L), Solid Solution α, Solid Solution β) or mixtures of two phases (e.g., L + α, α + β).

#### **8.2.2 Interpreting a Point on the Diagram**

For any given point defined by an overall alloy composition (C₀) and temperature (T) on the phase diagram, we can determine (under equilibrium conditions):

1.  **Phases Present**: Locate the point (T, C₀) on the diagram. The label of the region containing this point indicates the phase(s) present.
2.  **Compositions of the Phases**:
    *   **Single-Phase Region**: If the point (T, C₀) lies within a single-phase region (e.g., α), then the composition of that phase is simply the overall composition of the alloy, C<0xE2><0x82><0x90>.
    *   **Two-Phase Region**: If the point (T, C₀) lies within a two-phase region (e.g., α + β), draw a horizontal line (an **isotherm**) through the point that extends across the two-phase region. This line is called the **tie line**. The compositions of the two phases in equilibrium are given by the points where the tie line intersects the boundaries of the adjacent single-phase regions. Read the compositions C<0xE2><0x82><0x90> and C<0xE1><0xB5><0xA6> directly below these intersection points on the composition axis. C<0xE2><0x82><0x90> is the composition of the α phase, and C<0xE1><0xB5><0xA6> is the composition of the β phase, both at temperature T.
3.  **Relative Amounts (Phase Fractions) of the Phases**:
    *   **Single-Phase Region**: The amount of the phase is 100%.
    *   **Two-Phase Region**: Use the **Lever Rule** applied to the tie line constructed in step 2. Let the overall alloy composition be C₀, and the compositions of the two phases be C<0xE2><0x82><0x90> and C<0xE1><0xB5><0xA6> (where the tie line intersects the phase boundaries). The weight fractions (W) of the α and β phases are:
        **W<0xE2><0x82><0x90> = (C<0xE1><0xB5><0xA6> - C₀) / (C<0xE1><0xB5><0xA6> - C<0xE2><0x82><0x90>)**
        **W<0xE1><0xB5><0xA6> = (C₀ - C<0xE2><0x82><0x90>) / (C<0xE1><0xB5><0xA6> - C<0xE2><0x82><0x90>)**
        Note that W<0xE2><0x82><0x90> + W<0xE1><0xB5><0xA6> = 1. The lever rule essentially states that the fraction of a phase is proportional to the length of the tie line segment from the overall composition (C₀) to the *opposite* phase boundary, divided by the total length of the tie line. Imagine the tie line as a lever balanced at C₀; the weight of each phase is needed to balance the lever.

![Schematic Binary Phase Diagram showing a two-phase region (α+β) with a tie line drawn at temperature T. Points Cα, C0, Cβ are marked on the composition axis. Lever rule segments (Cβ-C0) and (C0-Cα) are indicated.](Schematic Binary Phase Diagram showing a two-phase region (α+β) with a tie line drawn at temperature T. Points Cα, C0, Cβ are marked on the composition axis. Lever rule segments (Cβ-C0) and (C0-Cα) are indicated.)

#### **8.2.3 Key Lines on Phase Diagrams**

*   **Liquidus Line**: The line(s) above which the alloy is entirely liquid. Melting begins (on heating) or solidification ends (on cooling) when crossing this line.
*   **Solidus Line**: The line(s) below which the alloy is entirely solid (or a mixture of solid phases). Melting ends (on heating) or solidification begins (on cooling) when crossing this line.
*   **Solvus Line**: A line indicating the limit of solid solubility of one component in another as a function of temperature. Crossing a solvus line upon cooling often leads to the precipitation of a second solid phase from a single-phase solid solution.

> **IMSS Olympiad Note: Reading Phase Diagrams**
> Being able to read a binary phase diagram is a fundamental skill. Practice finding:
> 1.  **Phases present** at a given T and C₀.
> 2.  **Composition of each phase** using the tie line in two-phase regions.
> 3.  **Relative amounts (weight fractions) of each phase** using the lever rule (Wα = opposite arm / total arm).
> Remember the definitions of liquidus, solidus, and solvus lines.

### **8.3 Eutectic Reactions and Microstructures: A Common Transformation**

Many binary phase diagrams exhibit special points and reactions where multiple phases are in equilibrium. One of the most common and important is the **eutectic reaction**.

#### **8.3.1 Invariant Reactions**

Reactions involving three phases in equilibrium in a binary system (at constant pressure) occur at a specific temperature and specific compositions, with zero degrees of freedom (F=0 from Gibbs Phase Rule). These are called **invariant reactions**. The general form is: Phase₁ ↔ Phase₂ + Phase₃ upon cooling/heating.

#### **8.3.2 The Eutectic Reaction**

*   **Definition**: A specific type of invariant reaction where, upon cooling, a single **liquid** phase transforms simultaneously into **two different solid phases**.
    **Liquid (L) ↔ Solid Phase α + Solid Phase β**   (upon cooling / heating)
*   **Eutectic Point**: The specific point on the phase diagram where the liquidus lines from the α+L and β+L regions meet the horizontal eutectic temperature line. It represents the lowest melting point composition for the system.
*   **Eutectic Temperature (T<0xE1><0xB5><0x8A>)**: The constant temperature at which the eutectic reaction occurs.
*   **Eutectic Composition (C<0xE1><0xB5><0x8A>)**: The specific composition of the liquid phase that undergoes the eutectic reaction.

![Schematic Binary Eutectic Phase Diagram (e.g., Pb-Sn). Shows L, α, β, α+L, β+L, α+β regions. Highlights the eutectic point (Ce, Te), liquidus, solidus, and solvus lines.](Schematic Binary Eutectic Phase Diagram (e.g., Pb-Sn). Shows L, α, β, α+L, β+L, α+β regions. Highlights the eutectic point (Ce, Te), liquidus, solidus, and solvus lines.)

#### **8.3.3 Solidification and Microstructure Development in Eutectic Systems**

The microstructure (the arrangement and morphology of the phases) that develops upon cooling an alloy through a eutectic system depends heavily on the overall alloy composition relative to the eutectic composition (C<0xE1><0xB5><0x8A>). We assume equilibrium (slow) cooling:

1.  **Alloy of Eutectic Composition (C₀ = C<0xE1><0xB5><0x8A>)**:
    *   The liquid cools directly to the eutectic temperature (T<0xE1><0xB5><0x8A>).
    *   At T<0xE1><0xB5><0x8A>, the entire liquid transforms simultaneously via the eutectic reaction: L → α + β.
    *   **Microstructure**: Because the α and β phases form simultaneously from the liquid, they grow together in a characteristic morphology. Often, this is a **lamellar structure**, consisting of fine, alternating plates or layers of the α and β phases. This intimate mixture is called the **eutectic microstructure**.

2.  **Hypoeutectic Alloy (C₀ < C<0xE1><0xB5><0x8A>)**: (Composition to the left of the eutectic point)
    *   Cooling starts in the Liquid (L) region.
    *   Upon crossing the liquidus line, solidification begins with the formation of crystals of the **α phase** (the phase rich in Component A). This is called the **proeutectic α** (or primary α).
    *   As cooling continues within the α + L region, more proeutectic α forms, and the remaining liquid becomes richer in Component B, its composition following the liquidus line downwards.
    *   When the temperature reaches the eutectic temperature (T<0xE1><0xB5><0x8A>), the remaining liquid will have reached the eutectic composition (C<0xE1><0xB5><0x8A>).
    *   At T<0xE1><0xB5><0x8A>, this remaining liquid transforms via the eutectic reaction: L<0xE1><0xB5><0x8A> → α + β (forming the lamellar eutectic structure).
    *   **Final Microstructure (below T<0xE1><0xB5><0x8A>)**: Consists of relatively large crystals of **proeutectic α** embedded within the fine **lamellar eutectic structure (α + β)**. The relative amounts of proeutectic α and eutectic structure can be calculated using the lever rule applied just above T<0xE1><0xB5><0x8A> (treating the eutectic structure as a single entity originating from L<0xE1><0xB5><0x8A>).

3.  **Hypereutectic Alloy (C₀ > C<0xE1><0xB5><0x8A>)**: (Composition to the right of the eutectic point)
    *   Solidification proceeds similarly to the hypoeutectic case, but the first solid phase to form upon crossing the liquidus is the **β phase** (rich in Component B). This is the **proeutectic β** (or primary β).
    *   As cooling occurs in the β + L region, more proeutectic β forms, and the remaining liquid becomes richer in Component A, composition following the liquidus towards C<0xE1><0xB5><0x8A>.
    *   At T<0xE1><0xB5><0x8A>, the remaining liquid (of composition C<0xE1><0xB5><0x8A>) transforms via the eutectic reaction: L<0xE1><0xB5><0x8A> → α + β (forming the lamellar eutectic structure).
    *   **Final Microstructure (below T<0xE1><0xB5><0x8A>)**: Consists of relatively large crystals of **proeutectic β** embedded within the fine **lamellar eutectic structure (α + β)**.

![Schematic microstructures for Hypoeutectic (large primary α grains + eutectic), Eutectic (fully lamellar eutectic), and Hypereutectic (large primary β grains + eutectic) alloys.](Schematic microstructures for Hypoeutectic (large primary α grains + eutectic), Eutectic (fully lamellar eutectic), and Hypereutectic (large primary β grains + eutectic) alloys.)

**Solid State Transformations**: Note that further changes can occur upon cooling *below* the eutectic temperature if the solid solubility limits (defined by the solvus lines) decrease with temperature. This can lead to precipitation of β from the α phase, or α from the β phase, within the proeutectic or eutectic constituents.

> **IMSS Olympiad Note: Eutectic Systems**
> The eutectic reaction (L ↔ α + β) is fundamental. Be able to:
> *   Identify the eutectic point, temperature, and composition on a phase diagram.
> *   Describe the sequence of phase transformations during equilibrium cooling for eutectic, hypoeutectic, and hypereutectic alloys.
> *   Sketch or identify the resulting microstructures (lamellar eutectic, proeutectic phases).
> *   Use the lever rule just above and just below the eutectic temperature to calculate the amounts of liquid, solid phases, proeutectic phases, and the total eutectic structure.

### **8.4 Phase Diagrams and Heat Treatment: Controlling Microstructure**

Phase diagrams are not just descriptive; they are predictive tools essential for designing **heat treatments** – controlled heating and cooling cycles used to manipulate the microstructure and thus tailor the properties of alloys.

#### **8.4.1 Guiding Principles from Phase Diagrams**

Phase diagrams reveal critical information for heat treatment:
*   **Transformation Temperatures**: They show the temperatures at which phase changes begin and end (liquidus, solidus, solvus, eutectic, eutectoid, etc.). Heating above or cooling below these temperatures drives phase transformations.
*   **Phase Compositions and Amounts**: They predict the equilibrium phases, their compositions, and relative amounts expected after slow cooling or prolonged holding at temperature.
*   **Solubility Limits**: Solvus lines indicate how solubility changes with temperature. This is exploited in **precipitation hardening**, where an alloy is heated into a single-phase region (solution treatment), quenched to retain a supersaturated solid solution (metastable), and then aged at an intermediate temperature to precipitate fine, strengthening particles.

#### **8.4.2 Influence of Cooling Rate (Introduction)**

Phase diagrams strictly represent **equilibrium** conditions, typically achieved only with very slow heating or cooling. In practice, cooling rates can significantly influence the resulting microstructure:
*   **Non-equilibrium Structures**: Faster cooling may not allow sufficient time for diffusion-controlled transformations (like the full separation of phases in a eutectic or precipitation from solid solution) to reach completion according to the diagram.
*   **Microstructural Refinement**: Faster cooling generally leads to finer microstructures (smaller grains, finer eutectic lamellae, smaller precipitates), which often results in higher strength and hardness.
*   **Metastable Phases**: Very rapid cooling (quenching) can suppress equilibrium transformations altogether, leading to the formation of non-equilibrium **metastable phases** that do not appear on the equilibrium phase diagram (e.g., martensite formation in steel).

While the detailed kinetics of transformations (how fast they occur) are described by Time-Temperature-Transformation (TTT) and Continuous-Cooling-Transformation (CCT) diagrams (beyond the scope of this introductory section), the equilibrium phase diagram provides the essential map of the thermodynamically stable states that the material system tends towards.

> **IMSS Olympiad Note: Phase Diagrams as Processing Guides**
> Understand that phase diagrams show *equilibrium* states. They indicate the temperatures needed to achieve specific phase fields (e.g., heating steel into the austenite (γ) region for hardening) and the phases expected upon slow cooling (e.g., formation of proeutectic and eutectic structures). Recognize that actual microstructures depend on cooling rates, deviating from equilibrium predictions, often forming finer or metastable structures.
