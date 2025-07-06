# Module 08: Optimization – From Linear Programming to Real-World Impact

## Objective  
This module series introduces optimization as a decision-making framework across five real-world applications: supply chains, pricing, advertising, retail, and logistics. It builds from foundational linear programming concepts to large-scale modeling using Python and Gurobi. Through case-based learning, it connects theory to business and humanitarian outcomes, highlighting optimization’s role in shaping strategic decisions.

---

## Learning Outcomes  
- Formulate real-world problems as optimization models using decision variables, objectives, and constraints  
- Build and solve linear programs using the Simplex Method  
- Understand discrete (integer, binary) and continuous optimization differences  
- Use Excel Solver and Python (Gurobi) for building and solving models  
- Evaluate feasibility, boundedness, robustness, and “what-if” sensitivity  
- Apply optimization to pricing, supply chain logistics, advertising slates, and network flow problems  
- Quantify model impact and explain decisions to stakeholders  

---

## Techniques Covered  
- Linear programming (LP)  
- Integer and binary optimization  
- Non-linear and mixed-integer programming (MIP)  
- Network flow modeling (supply, transshipment, demand nodes)  
- Demand modeling for price optimization  
- Display ad slate optimization using expected revenue models  
- Retail price ladder constraints and business rules  
- Gurobi in Python for scalable modeling  
- Sensitivity analysis and scenario modeling  
- Dashboarding and decision presentation  

---

## Tools Used  
- Excel Solver  
- Python  
- Gurobi (Gurobipy)  
- Pandas, NumPy  
- Matplotlib  
- Structured dashboards for insight communication  

---

## Personal Reflection

Optimization has shifted my thinking from "what is the best option?" to "how can we define, constrain, and test what 'best' really means?"

The first parts of this module helped me master the essentials of linear programming — identifying variables, maximizing objectives, and respecting real-world constraints. What stood out most was learning that the **corner points of a feasible region are where optimal solutions live**. This taught me how to frame messy business or health problems in a structured, solvable form.

In later sections, the complexity increased, but so did the relevance. The Filatoi Riuniti outsourcing case helped me understand optimization as both a technical and political tool — a way of structuring decisions while anticipating the resistance they might meet. The lesson: **you must understand and explain your model** — not just trust the math.

The pricing optimization segment especially resonated. I could immediately apply the framework to coaching packages, program promotions, and platform-based health services. Setting pricing isn't just about gut feeling — it's about balancing constraints, promotions, customer psychology, and revenue goals. Watching how simple changes in rules (like "no back-to-back discounts") impact revenue taught me that **optimization isn't just about getting the right answer — it's about asking the right questions.**

In the final module, working with Gurobi and seeing optimization applied to global problems (like the UN World Food Program’s supply chain) gave me a new goal: to use analytics for work that matters. Whether it’s public health, education, or sustainability — optimization helps us **do better with what we already have**.

---

## Example Case Studies  
- **Filatoi Riuniti Yarn Outsourcing**  
  Created a cost-minimization model for outsourcing yarn production under capacity and transportation constraints. Reduced cost by ~3%, equating to ~$500k in annual savings.

- **Retail Pricing Optimization**  
  Built a demand-prediction model based on historical pricing, then embedded it into a mixed-integer nonlinear optimization model. Balanced business rules (promotion frequency, pricing ladder, seasonal effects) to maximize revenue.

- **Display Ad Slate Optimization**  
  Modeled ad selection using expected revenue and integer constraints. Used optimization to outperform “greedy” baseline solutions by 3–10% in platform revenue.

- **UN World Food Program Network Flow**  
  Modeled supply, transshipment, and demand nodes for food logistics in crisis regions. Implemented network flow logic and cost minimization using Python and dashboards.

---

## Key Takeaways  
- Optimization models formalize strategic decisions through math and logic  
- Business rules, real constraints, and psychology matter just as much as the math  
- Linear models are efficient but limited; mixed-integer and nonlinear models unlock real-world value  
- Dashboards and clear communication are essential for adoption  
- Optimization isn't just about solving problems — it's about **changing how we think through them**

---

## Notebook: `optimization_model.ipynb` *(coming soon)*
