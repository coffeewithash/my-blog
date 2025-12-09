---
title: "Macroeconomics"
date: 2025-12-08
categories:
  - blog
tags:
---
# The Algebraic AD–AS Model

### 1. The Aggregate Demand (AD) Curve
* **Definition:** The AD curve represents the level of output ($Y$) where the IS curve (goods market) and LM curve (asset market) intersect for any given price level ($P$).
* **Derivation:** Found by equating the interest rate ($r$) from the algebraic IS and LM equations and solving for $Y$.
* **The Equation:**
    $$
    Y = \frac{\alpha_{IS} - \alpha_{LM} + (1/\beta_{LM})(M/P)}{\beta_{IS} + \beta_{LM}}
    $$
    *(Note: This represents the intersection where output is a function of real money supply and market intercepts.)*
* **Key Characteristics:**
    * **Slope:** The curve slopes downward. As the price level ($P$) rises, real money supply ($M/P$) falls, reducing aggregate output demanded ($Y$).
    * **Shifts:**
        * **IS Shifts:** Expansionary fiscal policy (e.g., increased government purchases) shifts the IS curve up/right, shifting AD up/right.
        * **LM Shifts:** Expansionary monetary policy (increased nominal money supply, $M$) shifts the LM curve down/right, shifting AD up/right.

### 2. The Aggregate Supply Curves
* **Short-Run Aggregate Supply (SRAS):**
    * Firms supply whatever output is demanded at a fixed price level.
    * **Equation:** Horizontal line where $P = P_{sr}$.
* **Long-Run Aggregate Supply (LRAS):**
    * Output is fixed at the full-employment level, regardless of price.
    * **Equation:** Vertical line where $Y = \bar{Y}$.

### 3. Equilibrium Solutions
* **Short-Run Equilibrium:**
    * Occurs at the intersection of **AD** and **SRAS**.
    * **Calculation:** Substitute the fixed price ($P_{sr}$) into the AD equation to solve for output ($Y$).
* **Long-Run Equilibrium:**
    * Occurs at the intersection of **AD** and **LRAS** (where markets for labor, goods, and assets all clear).
    * **Output:** Fixed at $\bar{Y}$.
    * **Price Level:** The price level ($P$) is endogenous. It is found by setting the AD equation equal to $\bar{Y}$ and solving for $P$. This ensures the price level adjusts to align demand with full-employment output.
 
# Classical Business Cycle Analysis: Market-Clearing Macroeconomics
### **1. Classical Business Cycle Fundamentals**

- **Core Belief:** Models are built on micro-foundations (utility and profit maximization) where markets always clear (prices and wages adjust rapidly).
- **Primary Cause of Cycles:** Real shocks to the economy (disturbances to the "real side" like production functions or labor force size), rather than nominal shocks (money supply).
### **2. Real Business Cycle (RBC) Theory**
**The Central Premise:**
- Business cycles are driven primarily by **Productivity Shocks** (Supply Shocks).
- **Booms:** Caused by beneficial productivity shocks (new tech, good weather).
- **Recessions:** Caused by adverse productivity shocks (regulations, bad weather, resource scarcity).

**Mechanism of an Adverse Shock:**
1. **Shock:** Negative productivity shock reduces the Marginal Product of Labor ($MPN$).
2. **Labor Market:** Labor demand falls $\rightarrow$ Equilibrium employment ($N$) and Real Wages fall.
3. **Output:** Full-employment output ($\bar{Y}$) falls because $N$ is lower and capital is less productive.
4. **IS-LM-FE Effect:** The $FE$ line shifts left. The result is lower output, higher real interest rates, and a higher price level.
### **3. RBC Theory vs. The Facts**
**Evidence Supporting RBC:**
- **Output Fluctuations:** Continuous productivity shocks naturally create recurrent fluctuations.
- **Procyclical Variables:** Correctly predicts that **Employment**, **Real Wages**, and **Average Labor Productivity** move in the same direction as output (procyclical).
    - _Note:_ Without productivity shocks, diminishing returns would make labor productivity _countercyclical_ (falling when employment rises).
**Evidence Challenging RBC:**
- **Inflation:**
    - **The Theory:** Predicts counter-cyclical prices (Recession = Supply scarcity = High Prices).
    - **The Fact:** Inflation is typically procyclical (slows down during recessions).
    - _RBC Defense:_ Kydland & Prescott argue that since WWII, supply shocks (like oil crises) have indeed caused prices to rise during slumps (stagflation).
**The "Small Shocks" Argument:**
- Critics argue large economy-wide shocks are rare.
- RBC proponents counter that the cumulative effect of many small, random productivity shocks can generate large cycle-like fluctuations.
### **4. Measuring Shocks: The Solow Residual**
RBC economists use the **Solow Residual** to measure Total Factor Productivity ($A$).
The Standard Equation:
$$\text{Solow Residual (A)} = \frac{Y}{K^a N^{1-a}}$$

(Where $Y$ is output, $K$ is capital, $N$ is labor, and $a$ is the capital share).
The Measurement Problem (Utilization & Hoarding):
The standard equation assumes capital and labor are always used at constant intensity. In reality, utilization varies:
- **Capital Utilization ($u_K$):** Machines run faster/longer in booms (e.g., higher electricity use).
- **Labor Utilization ($u_N$):**
    - **Labor Hoarding:** In recessions, firms keep workers but utilize them less (maintenance, "make-work") to avoid firing/hiring costs.
    - This makes measured productivity fall in recessions even if technology ($A$) hasn't changed.

Refined Production Function:

$$Y = A (u_K K)^a (u_N N)^{1-a}$$
- **Conclusion:** The standard Solow Residual captures both technology changes **and** utilization changes. Therefore, strictly interpreting it as "technology" overstates the role of tech shocks in business cycles.
### **5. Modern Classical View (DSGE)**
- Acknowledging that productivity isn't the _only_ driver, modern models are called **DSGE (Dynamic Stochastic General Equilibrium)**.
- These models incorporate both productivity shocks and other disturbances (like fiscal policy or war) into the market-clearing framework.
 
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    }
  };
</script>
