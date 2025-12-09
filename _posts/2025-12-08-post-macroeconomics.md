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

### **6. Fiscal Policy Shocks in the Classical Model**
 **1. The Shock: Temporary Increase in Government Purchases**
In the classical model, fiscal policy shocks (like a military buildup or public works program) are a potential source of business cycles. We analyze a **temporary increase in real government purchases ($G$)**.

 **2. Labor Market Effects (The Supply Side)**
The classical view emphasizes that fiscal policy affects labor supply through a **Wealth Effect**.
- **The Mechanism:**
    - Higher government spending ($G \uparrow$) must be paid for by taxes (either current or future).
    - This effectively makes individuals poorer (Negative Wealth Effect).
    - Because workers feel poorer, they cannot afford as much leisure.
    - **Result:** They supply _more_ labor to compensate.
- **Diagrammatic Shift (Figure a):**
    - **Labor Supply ($NS$):** Shifts to the right (from $NS^1$ to $NS^2$).
    - **Labor Demand ($ND$):** No change (MPN is unaffected).
    - **Outcome:**
        - Equilibrium Employment ($N$) **increases** ($N_1 \to N_2$).
        - Real Wage ($w$) **decreases** ($w_1 \to w_2$).
    - **Full-Employment Output:** Because employment ($N$) rises, the full-employment level of output ($\bar{Y}$) increases.

<img width="1322" height="766" alt="image" src="https://github.com/user-attachments/assets/38f7643a-9453-44a9-8785-43cdae9caf75" />

**3. General Equilibrium Effects (The IS-LM-FE Model)**
The shock affects both the goods market (IS) and the general equilibrium (FE).
- **Step 1: The Shifts (Figure b)**
    - **FE Line:** Shifts to the right ($FE^1 \to FE^2$) because full-employment output has risen (due to the labor market changes described above).
    - **IS Curve:** Shifts up and to the right ($IS^1 \to IS^2$).
        - _Reason:_ Higher $G$ reduces desired national saving ($S_{nat} = Y - C - G$). To clear the goods market, the real interest rate must rise.
- **Step 2: The Disequilibrium**
    - The new IS curve ($IS^2$) typically intersects the original LM curve ($LM^1$) to the **right** of the new FE line ($FE^2$).
    - This indicates that Aggregate Demand > Aggregate Supply.
- **Step 3: Restoration of Equilibrium**
    - The excess demand drives the **Price Level ($P$) up**.
    - A rise in $P$ reduces the real money supply ($M/P$).
    - **LM Curve:** Shifts up and to the left ($LM^1 \to LM^2$).
- **Final Result (Point F):**
    - **Output ($Y$):** Higher.
    - **Real Interest Rate ($r$):** Higher.
    - **Price Level ($P$):** Higher.
    - **Real Wage ($w$):** Lower.
  
**4. Policy Implications: Should Fiscal Policy Stabilize Cycles?**
Despite the ability of fiscal policy to affect output, **Classical Economists argue AGAINST using it** to smooth business cycles.
- **Argument 1: The "Invisible Hand" & Welfare**
    - Classicals believe the economy is self-correcting and prices adjust rapidly.
        - Although spending increases output, it does so by making workers **poorer** (forcing them to work more for lower wages). Intervention generally reduces welfare rather than improving it.
       - **The Rule:** Government purchases should only occur if the _benefits_ (e.g., national security) exceed the _costs_ to taxpayers, not merely to boost output.
  - **Argument 2: Practical Lags**
        - **Recognition Lag:** Time taken to identify the shock.
        - **Legislative Lag:** Time taken to pass laws.
        - **Implementation Lag:** Time taken to start projects.
        - **Impact Lag:** Time taken for the economy to respond.
        - _Result:_ By the time a policy takes effect, the economy may have already recovered, potentially destabilizing it further.

### Comparison: Beneficial Productivity Shock vs. Expansionary Fiscal Shock

| Feature | Beneficial Productivity Shock (RBC) | Expansionary Fiscal Shock (Classical) |
| :--- | :--- | :--- |
| **Primary Driver** | Technology improvement, good weather, new management techniques. | Increase in Government Purchases ($G$) (e.g., War, Infrastructure). |
| **Key Mechanism** | **Marginal Product of Labor ($MPN$) rises.** Firms want to hire more workers at any wage. | **Negative Wealth Effect.** Higher taxes make workers poorer, so they supply more labor. |
| **Labor Market Shift** | **Labor Demand ($ND$) shifts Right.** | **Labor Supply ($NS$) shifts Right.** |
| **Output ($Y$)** | **Increases** | **Increases** |
| **Employment ($N$)** | **Increases** | **Increases** |
| **Real Wage ($w$)** | **Increases** (Procyclical)<br>*(Demand for labor outstrips supply)* | **Decreases** (Countercyclical)<br>*(Supply of labor outstrips demand)* |
| **Price Level ($P$)** | **Decreases** (Countercyclical)<br>*(Supply of goods increases relative to demand)* | **Increases** (Procyclical)<br>*(Demand for goods increases relative to supply)* |
| **Labor Productivity** | **Increases**<br>*(Better tech means more output per worker)* | **Decreases**<br>*(Diminishing returns: more workers on same capital)* |
| **Interest Rate ($r$)** | **Decreases**<br>*(Usually, as saving rises to smooth consumption)* | **Increases**<br>*(Government competes for funds, lowering national saving)* |

### **Key Takeaways for Analysis**
- **The "Wage" Test:** If you see a boom where real wages are **falling**, it supports the Fiscal/Classical view (workers working harder because they are poorer). If wages are **rising**, it supports the RBC view (workers are more valuable due to tech).
- **The "Price" Test:** RBC theory struggles to explain why prices usually rise during booms (since supply shocks should lower prices). Fiscal shocks explain inflation during booms well.
- **The "Productivity" Test:** RBC fits the data well here—productivity usually rises in booms. Fiscal shocks imply productivity should fall (due to diminishing returns), which contradicts most historical data

### **Unemployment in the Classical Model**

Classical economics, in its simplest form, struggles to explain cyclical unemployment, as the basic supply-and-demand labor model predicts **zero unemployment** (market-clearing wage). To account for real-world unemployment, classical economists introduced modifications based on heterogeneity and search costs.
### **1. Classical Explanation for Non-Zero Unemployment**
- **Labor Market Heterogeneity:** The simple model fails because it assumes all workers and jobs are identical. In reality, workers have varied skills, and jobs have varied requirements.
- **Search and Matching Costs:** Matching workers to suitable jobs is **time-consuming and costly**. This explains why some people are always unemployed:
    - **Frictional Unemployment:** People spending time and effort searching for a new job after losing one or entering the labor force.
    - **Structural Unemployment:** Workers' skills do not match the requirements of growing industries (chronic mismatch).
- **Natural Rate of Unemployment:** The sum of frictional and structural unemployment is always greater than zero.

### **2. Explaining Cyclical Unemployment (The Mismatch Argument)**
Some classical economists argue that macroeconomic disturbances (like productivity shocks) increase the mismatch between workers and firms, causing cyclical unemployment.
- **Mechanism (Adverse Productivity Shock):**
    - A shock (e.g., oil price increase) affects industries and regions differently (jobs destroyed in energy-intensive sectors, created in energy-light sectors).
    - Workers displaced from shrinking sectors search for jobs elsewhere, increasing **frictional unemployment**.
    - If their old skills are obsolete, they become **structurally unemployed**.
    - The increased number of job seekers increases the time needed to find a new job.
    - **Result:** Adverse productivity shocks raise the total of frictional and structural unemployment, effectively raising the **natural rate of unemployment** during recessions.
- **Evidence of Mismatch:**
    - Studies (e.g., Davis and Haltiwanger) show significant **"churning"** in the U.S. labor market, where job creation and destruction rates are high, even in non-recession years.
    - Research shows that during or immediately following recessions, **job destruction exceeds job creation** significantly.
- **Critique:** The mismatch theory doesn't explain everything:
    - Much of the increase in unemployment is due to **temporary layoffs** (workers wait for a callback, not search for a new job).
    - The theory predicts more **job vacancies** during recessions (as firms try to find workers with new skills), but vacancies actually **fall**.
### **3. Classical Policy View on Unemployment**
Classical economists remain opposed to using active fiscal policy to combat unemployment, even with the mismatch modification.
- **Inadequacy of Fiscal Policy:** Raising aggregate demand (e.g., $G \uparrow$) does not directly fix the microeconomic problem of **mismatch** between skills and job requirements.
- **Recommended Approach:** Eliminate barriers to labor market adjustment, such as:
    - High legal minimum wages (which price low-skilled workers out of the market).
    - Burdensome regulations that raise the cost of hiring.
### **4. Jobless Recoveries**
"Jobless recoveries" are a new feature of the U.S. business cycle, where employment continues to fall or remains stagnant for months _after_ a recession officially ends (after the business-cycle trough).
- **Recent Examples:** Recoveries following the 1990–1991, 2001, and 2007–2009 recessions.
- **Potential Explanations:**
    - **Mild Recessions:** (Disputed, as the 2007–2009 recession was severe).
    - **Increased Labor Productivity:** Strong productivity growth enables firms to increase output (**GDP**) without hiring new workers, thus delaying the recovery of the **labor market**. This explains the lack of job creation, but not why this pattern is only recent.











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
