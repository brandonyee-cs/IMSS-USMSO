# **Part IX: Corrosion and Degradation**

## **Material Deterioration in Service Environments**

### **Introduction to Part IX**

Materials selected for engineering applications must often function reliably in environments that can cause them to deteriorate over time. This deterioration can compromise performance, lead to unexpected failures, increase costs due to maintenance and replacement, and pose safety risks. **Corrosion**, the destructive electrochemical attack of a metal, is a primary concern, costing economies billions annually. However, non-metallic materials like polymers and ceramics also undergo **degradation** through different mechanisms when exposed to certain environments (e.g., chemicals, radiation, heat). This part delves into the fundamental principles governing the corrosion of metals, explores the various forms corrosion can take, discusses methods for prevention and control, and briefly touches upon the degradation mechanisms relevant to polymers and ceramics. Understanding material degradation is crucial for ensuring the long-term durability and safety of engineered systems.

### **9.1 Electrochemical Principles in Corrosion: The Battery Analogy**

Most metallic corrosion is an **electrochemical process**. It involves chemical reactions occurring at the surface of a metal exposed to an **electrolyte** (an electrically conductive solution, like moisture containing dissolved salts or acids), where electrons are transferred between different locations on the metal surface or between different metals. Essentially, a corrosion scenario sets up tiny electrochemical cells (batteries) on the metal's surface.

#### **9.1.1 Components of an Electrochemical Cell**

For electrochemical corrosion to occur, four components are necessary:

1.  **Anode**: The site where **oxidation** occurs. Metal atoms lose electrons and dissolve into the electrolyte as positive ions (metal cations). This is where metal loss (corrosion) happens.
    *   Example: M → Mⁿ⁺ + ne⁻ (where M is the metal, n is its valence)
2.  **Cathode**: The site where **reduction** occurs. Electrons generated at the anode flow through the metal (or an external conductor) to the cathode, where they are consumed by a reducible species present in the electrolyte. The metal itself is typically not consumed at the cathode. Common cathodic reactions include:
    *   In acidic solutions (low pH): 2H⁺ + 2e⁻ → H₂ (gas) (Hydrogen evolution)
    *   In neutral or basic solutions containing dissolved oxygen: O₂ + 2H₂O + 4e⁻ → 4OH⁻
    *   In acidic solutions containing dissolved oxygen: O₂ + 4H⁺ + 4e⁻ → 2H₂O
    *   Reduction of other metal ions: M²⁺ + 2e⁻ → M (Metal plating)
3.  **Electrolyte**: An electrically conductive solution or medium that allows the flow of ions between the anode and cathode, completing the circuit. Moisture, soil containing dissolved salts, acids, and bases can all act as electrolytes.
4.  **Electrical Connection**: The anode and cathode must be electrically connected (usually through the bulk metal itself) to allow electron flow from anode to cathode.

If any of these components are missing, electrochemical corrosion cannot occur.

![Schematic of an electrochemical corrosion cell showing Anode (metal M dissolving), Cathode (e.g., O2 reduction), Electrolyte (ion flow), and Electrical Connection (electron flow through metal).](Schematic of an electrochemical corrosion cell showing Anode (metal M dissolving), Cathode (e.g., O2 reduction), Electrolyte (ion flow), and Electrical Connection (electron flow through metal).)

#### **9.1.2 Electrode Potentials and Driving Force**

Whether a metal acts as an anode or cathode, and the tendency for corrosion to occur, is related to its **electrode potential**. Each metal (or half-reaction) has an intrinsic tendency to be oxidized or reduced, quantified by its standard electrode potential (E°) measured relative to a standard hydrogen electrode under standard conditions.

*   **Standard EMF Series**: Lists metals in order of their standard reduction potentials (E°). Metals with more negative E° are more easily oxidized (more **active**) and tend to act as anodes. Metals with more positive E° are less easily oxidized (more **noble**) and tend to act as cathodes.
*   **Galvanic Series**: A similar ranking based on observed corrosion behavior of metals and alloys in a specific environment (like seawater). More practical for predicting behavior in real-world conditions. Metals higher on the list (more active/anodic end) corrode preferentially when coupled with metals lower on the list (more noble/cathodic end) in that environment.
*   **Potential Difference (Voltage)**: The difference in electrode potential between the anodic and cathodic sites (or between two different metals) provides the driving force (voltage) for the corrosion cell. A larger potential difference generally leads to a greater tendency for corrosion. ΔE_cell = E_cathode - E_anode. A positive ΔE_cell indicates a spontaneous reaction.

#### **9.1.3 Faraday's Law and Corrosion Rate**

The rate of corrosion (amount of metal lost over time) is directly proportional to the current flowing in the corrosion cell, according to **Faraday's Law**:

m = (I * t * A) / (n * F)

Where:
*   m = mass of metal oxidized (lost)
*   I = corrosion current
*   t = time
*   A = atomic weight of the metal
*   n = number of electrons involved in the oxidation reaction (valence)
*   F = Faraday's constant (≈ 96,500 Coulombs per mole of electrons)

Corrosion rate can be expressed as mass loss per unit area per unit time (e.g., mg/dm²/day) or as penetration rate (e.g., mm/year or mils per year, mpy). Higher corrosion current implies a faster corrosion rate.

> **IMSS Olympiad Note: Electrochemical Basis**
> Understand that corrosion is usually electrochemical, requiring an anode (oxidation, metal loss), cathode (reduction), electrolyte (ion path), and electrical connection (electron path). Recognize that potential differences (related to Standard EMF or Galvanic Series) drive corrosion, with more active metals acting as anodes. Higher potential difference often means higher corrosion tendency.

### **9.2 Forms of Corrosion: Diverse Modes of Attack**

Corrosion can manifest in various ways, depending on the metal, environment, and operating conditions. Recognizing the form of corrosion is crucial for diagnosis and prevention.

#### **9.2.1 Uniform (General) Corrosion**

*   **Description**: Corrosion proceeds relatively uniformly over the entire exposed surface. Anodic and cathodic sites are numerous and shift randomly over time.
*   **Appearance**: General thinning or wasting away of the material. Rusting of steel in the atmosphere is a common example.
*   **Predictability**: Relatively predictable based on immersion tests; rates often expressed in mm/year or mpy. Can be managed by material selection, coatings, or specifying a corrosion allowance (extra thickness).

#### **9.2.2 Galvanic Corrosion**

*   **Description**: Occurs when two **dissimilar metals** (having different electrode potentials) are electrically connected and exposed to a common electrolyte.
*   **Mechanism**: The more active metal (more negative potential in the galvanic series for that environment) becomes the **anode** and corrodes at an accelerated rate. The more noble metal becomes the **cathode** and is protected (its own corrosion rate decreases).
*   **Severity Factors**: Increased by:
    *   Larger potential difference between the metals.
    *   Larger cathode area relative to the anode area (concentrates current on the smaller anode, leading to rapid attack).
    *   Higher electrolyte conductivity.
*   **Example**: Steel screws (anode) corroding rapidly when used in contact with brass (cathode) in a marine environment.

#### **9.2.3 Crevice Corrosion**

*   **Description**: Intense localized corrosion occurring within narrow gaps, crevices, or under shielded surfaces (e.g., under gaskets, washers, bolt heads, deposits).
*   **Mechanism**: Typically driven by differences in concentration of dissolved species within the crevice compared to the bulk environment. A common mechanism involves **oxygen depletion** within the crevice. The crevice becomes anodic (metal dissolves: M → M⁺ + e⁻), while the area outside the crevice, with access to oxygen, becomes cathodic (O₂ + 2H₂O + 4e⁻ → 4OH⁻). Migration of negative ions (like Cl⁻) into the crevice to maintain charge neutrality leads to formation of acidic conditions (M⁺ + H₂O → MOH + H⁺), further accelerating corrosion within the crevice.
*   **Susceptibility**: Affects metals that rely on passive oxide films (like stainless steels, aluminum, titanium), especially in chloride-containing environments.

#### **9.2.4 Pitting Corrosion**

*   **Description**: Highly localized form of corrosion resulting in small pits or holes penetrating the metal surface.
*   **Mechanism**: Similar to crevice corrosion in that it involves breakdown of a passive film at specific points and formation of localized anodic sites. Often initiated by aggressive anions, particularly **chloride ions (Cl⁻)**. Once a pit starts, the local chemistry inside becomes aggressive (low pH, high Cl⁻ concentration), promoting rapid penetration. Gravity can cause pits to grow downwards.
*   **Danger**: Very insidious, as significant penetration and potential perforation can occur with only minimal overall mass loss, making it hard to detect.
*   **Susceptibility**: Common in passive metals like stainless steels, aluminum alloys, especially in chloride environments.

#### **9.2.5 Intergranular Corrosion (IGC)**

*   **Description**: Preferential corrosion attack occurring along or adjacent to the **grain boundaries** of a metal, while the bulk of the grains remains largely unaffected.
*   **Mechanism**: Often caused by **sensitization**, where heat treatment (e.g., welding of austenitic stainless steels) causes precipitation of chromium carbides (Cr₂₃C₆) along grain boundaries. This depletes chromium from the regions adjacent to the boundaries, reducing their corrosion resistance compared to the grain interiors. These depleted zones become anodic relative to the rest of the grain.
*   **Consequences**: Can lead to loss of strength and ductility, as grains effectively fall apart.

#### **9.2.6 Selective Leaching (Dealloying)**

*   **Description**: Preferential removal of one specific element (usually the more active one) from a solid solution alloy by corrosion processes.
*   **Example**: **Dezincification** of brass (Cu-Zn alloy), where zinc is selectively leached out, leaving behind a porous, weak copper residue. Can occur in plumbing fittings. Graphitic corrosion of gray cast iron (selective removal of iron, leaving graphite network).

#### **9.2.7 Erosion-Corrosion**

*   **Description**: Acceleration of corrosion damage due to the combined action of chemical attack and mechanical wear/abrasion caused by a moving fluid (often containing solid particles or bubbles).
*   **Mechanism**: The flowing fluid removes protective surface films (passive layers or corrosion products), exposing fresh metal to corrosive attack. The mechanical action itself can also cause wear.
*   **Appearance**: Often characterized by grooves, gullies, waves, or holes exhibiting a directional pattern related to the fluid flow. Common in piping, elbows, valves, pump impellers, turbine blades.

#### **9.2.8 Stress Corrosion Cracking (SCC)**

*   **Description**: Brittle fracture of a normally ductile material occurring under the combined action of a **tensile stress** (applied or residual) and a **specific corrosive environment**.
*   **Requirements**: Requires the simultaneous presence of three factors:
    1.  A susceptible material.
    2.  A specific corrosive environment (often mild).
    3.  A tensile stress (can be below the yield strength).
*   **Characteristics**: Cracking can be intergranular or transgranular, often with minimal signs of corrosion product. Failure can be sudden and catastrophic.
*   **Examples**: Cracking of brass in ammonia environments ("season cracking"), cracking of stainless steels in chloride environments, cracking of carbon steels in certain caustic or nitrate solutions.

> **IMSS Olympiad Note: Recognizing Corrosion Forms**
> Be familiar with the defining characteristics of the common forms of corrosion:
> *   **Galvanic**: Dissimilar metals + electrolyte.
> *   **Crevice**: Confined spaces/gaps, oxygen depletion.
> *   **Pitting**: Localized holes/pits, often chloride-initiated.
> *   **Intergranular**: Attack along grain boundaries (sensitization).
> *   **SCC**: Tensile Stress + Specific Environment + Susceptible Material.

### **9.3 Corrosion Prevention Techniques: Mitigation Strategies**

Preventing or controlling corrosion involves interrupting one or more components of the electrochemical cell or altering the material/environment interaction.

#### **9.3.1 Material Selection**

*   **Principle**: Choose materials that are inherently resistant to corrosion in the specific service environment.
*   **Options**:
    *   **Noble Metals**: Gold, platinum (often too expensive).
    *   **Passive Metals**: Stainless steels (contain Cr to form protective Cr₂O₃ layer), aluminum alloys (form Al₂O₃), titanium alloys (form TiO₂). Passivity can break down under certain conditions (e.g., chlorides).
    *   **Corrosion-Resistant Alloys**: Nickel-based alloys (e.g., Hastelloy, Monel) for aggressive chemical environments.
    *   **Non-Metallic Materials**: Polymers, ceramics (where suitable for mechanical/thermal requirements).
*   **Considerations**: Cost, mechanical properties, temperature limits, fabricability.

#### **9.3.2 Environmental Alteration**

*   **Principle**: Modify the operating environment to make it less corrosive.
*   **Methods**:
    *   **Lowering Temperature**: Generally reduces reaction rates.
    *   **Removing Oxygen**: Deaeration of water can reduce cathodic reaction rates.
    *   **Adjusting pH**: Changing acidity/alkalinity can affect corrosion rates and passive film stability.
    *   **Adding Inhibitors**: Chemicals added in small concentrations to the electrolyte that adsorb on the metal surface or react with corrosive species, slowing down anodic or cathodic reactions.

#### **9.3.3 Design Changes**

*   **Principle**: Design components and structures to minimize opportunities for corrosion initiation and propagation.
*   **Strategies**:
    *   **Avoid Crevices**: Use welded joints instead of bolted/riveted ones where possible; use non-absorbent gaskets; design for complete drainage.
    *   **Minimize Galvanic Coupling**: Avoid direct contact between dissimilar metals. If unavoidable, use compatible metals, insulate them, or make the anode area large relative to the cathode.
    *   **Reduce Stress Concentrations**: Smooth contours and generous radii reduce stress levels, mitigating SCC and fatigue initiation.
    *   **Avoid Stagnant Areas**: Design for smooth fluid flow to prevent deposit buildup and erosion-corrosion.

#### **9.3.4 Coatings**

*   **Principle**: Apply a protective layer to physically isolate the base metal from the corrosive environment (barrier protection) or to provide electrochemical protection.
*   **Types**:
    *   **Metallic Coatings**:
        *   *Noble Coatings* (e.g., Tin, Nickel on steel): Act purely as a barrier. If the coating is scratched, the underlying base metal becomes a small anode relative to the large cathode coating, leading to rapid localized corrosion.
        *   *Sacrificial Coatings* (e.g., Zinc (galvanizing), Aluminum on steel): The coating metal is more active than the base metal. It acts as a sacrificial anode, corroding preferentially even if the coating is scratched, thus protecting the base metal cathodically.
    *   **Organic Coatings (Paints, Polymers)**: Primarily act as a barrier to electrolytes and oxygen. May contain corrosion inhibitors or sacrificial pigments (like zinc dust). Effectiveness depends on adhesion, thickness, and resistance to degradation.
    *   **Inorganic Coatings (Non-metallic)**:
        *   *Ceramic Coatings (Enamels, Glass Linings)*: Provide excellent barrier protection, often at high temperatures or in aggressive chemical environments. Can be brittle.
        *   *Anodizing*: Electrochemical process that grows a controlled, thicker, more protective oxide layer on certain metals (esp. Al, Ti, Mg). Can be porous for subsequent sealing or dyeing.
        *   *Conversion Coatings* (e.g., Phosphating, Chromating): Thin inorganic layers formed by chemical reaction with the metal surface, providing mild corrosion resistance and improving paint adhesion.

#### **9.3.5 Cathodic Protection (CP)**

*   **Principle**: Making the entire surface of the structure to be protected act as the **cathode** of an electrochemical cell, thereby suppressing metal dissolution (anodic reaction). This is achieved by supplying electrons to the structure from an external source.
*   **Methods**:
    1.  **Sacrificial Anode Cathodic Protection (SACP)**:
        *   Electrically connect the structure (e.g., steel pipeline, ship hull) to blocks of a more active metal (the **sacrificial anode**, e.g., Zinc, Aluminum, Magnesium alloys).
        *   The sacrificial anode corrodes preferentially, supplying electrons to the structure, making it cathodic.
        *   Simple, no external power required, but anodes are consumed and need periodic replacement. Driving voltage is limited by the potential difference between the metals.
    2.  **Impressed Current Cathodic Protection (ICCP)**:
        *   Use an external DC power source (e.g., rectifier) to impress a current from an **inert anode** (e.g., graphite, high-silicon cast iron, platinum-coated titanium) buried or immersed in the electrolyte, onto the structure to be protected.
        *   The power supply forces the structure to become cathodic.
        *   Requires external power, more complex installation/maintenance, but can provide higher driving voltage and protect larger structures. Anodes are relatively permanent.

Cathodic protection is widely used for pipelines, storage tanks, ship hulls, offshore platforms, and reinforced concrete structures.

> **IMSS Olympiad Note: Prevention Principles**
> Understand the *mechanism* behind major corrosion prevention strategies:
> *   **Coatings**: Barrier vs. Sacrificial (galvanizing).
> *   **Cathodic Protection**: Making the structure the cathode via Sacrificial Anodes (more active metal) or Impressed Current (external power source).
> *   **Material Selection**: Using inherently resistant or passive materials.
> *   **Design**: Avoiding features that promote localized corrosion (crevices, galvanic couples).

### **9.4 Degradation of Non-Metallic Materials**

While corrosion focuses on metals, polymers and ceramics also degrade, though typically via different mechanisms.

#### **9.4.1 Polymer Degradation**

Polymers can degrade through physical processes or chemical changes to their long-chain molecules:

*   **Swelling and Dissolution**: Absorption of liquids (solvents) can cause polymers to swell, soften, lose strength, and potentially dissolve if the polymer-solvent interactions are strong enough. Cross-linking reduces swelling and dissolution.
*   **Bond Scission (Chain Breakage)**: The breaking of the primary covalent bonds within the polymer backbone or side groups. This reduces the average molecular weight and typically leads to embrittlement, reduced strength, and discoloration. Common causes include:
    *   **Heat (Thermal Degradation)**: Excessive temperature can break bonds directly or accelerate oxidative reactions.
    *   **Radiation**: High-energy radiation (UV light from sunlight, gamma rays, electron beams) can generate free radicals that initiate chain scission. UV degradation is a major issue for outdoor polymer applications. Stabilizers (UV absorbers, antioxidants) are often added.
    *   **Chemical Attack**: Strong oxidizing agents (like ozone), acids, or bases can attack specific chemical groups in the polymer chain. Hydrolysis (reaction with water) can degrade polymers like polyesters and polyamides.
    *   **Mechanical Stress**: Can contribute to degradation, sometimes synergistically with environmental factors (e.g., ozone cracking of stressed rubber).
*   **Weathering**: The combined detrimental effects of sunlight (UV), moisture, temperature cycles, and atmospheric pollutants (like oxygen, ozone) on polymers used outdoors.

#### **9.4.2 Ceramic Degradation**

Ceramics are generally known for their excellent resistance to high temperatures and chemical attack due to their strong ionic/covalent bonding.
*   **Chemical Dissolution**: While often highly resistant, some ceramics can be slowly dissolved by aggressive chemicals, particularly at high temperatures.
    *   Silica-based glasses can be attacked by strong alkaline solutions or hydrofluoric acid (HF).
    *   Some oxides may react with molten metals or slags.
*   **Mechanical Degradation**: Fracture (due to brittleness), wear, and thermal shock are often more significant modes of failure for ceramics than chemical degradation in many applications.
*   **High-Temperature Oxidation**: Some non-oxide ceramics (like SiC or Si₃N₄) can slowly oxidize at very high temperatures in oxygen-containing atmospheres, potentially forming a protective SiO₂ layer or sometimes leading to degradation.

> **IMSS Olympiad Note: Non-Metallic Degradation**
> Recognize that polymers degrade primarily via **swelling/dissolution** in solvents or **bond scission** (chain breakage) caused by heat, radiation (UV), or chemical attack. Ceramics are generally very resistant to chemical attack (corrosion) but can dissolve in specific aggressive environments and are more often limited by mechanical failure modes like brittle fracture.
