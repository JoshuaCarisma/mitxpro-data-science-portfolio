# Module 02: Probability Distributions & Risk Modeling

## Objective
This module introduces how probability distributions help quantify and manage uncertainty in real-world scenarios — from pandemic capacity planning to inventory decisions. It explores how distributions can shift decision-making from deterministic “yes/no” answers to probabilistic reasoning that reflects real-world variability.

---

## Learning Outcomes
- Employ probability distributions in predictive and prescriptive models
- Compute sufficient inventory in uncertain demand conditions
- Explain the advantage of risk pooling and flexibility to decision makers
- Use simulation and scenario analysis to evaluate capacity planning
- Model outcomes using empirical and standard distributions
- Translate complex probability outputs into real-world business insights

---

## Techniques Covered
- Standard vs. Empirical Probability Distributions
- Simulation with randomized parameters
- SIR (Susceptible-Infectious-Recovered) Epidemic Modeling
- Normal distribution & fill rate analysis
- Cumulative probability analysis
- Scenario comparison & risk visualization

---

## Tools Used
- Python
- NumPy, Pandas
- SciPy Stats
- Matplotlib
- Simulation frameworks
- Conceptual modeling from MIT xPRO

---

## Personal Reflection

> "In a world full of uncertainty, we don’t need guarantees — we need clarity about risk."

This module made me think deeply about **how poorly we often handle uncertainty** — especially in critical environments like healthcare. In my coaching and clinical support roles, I often see people make plans based on “averages,” ignoring the variability that defines real life. This module emphasized something I’ve come to believe intuitively: **the average outcome is not the most likely outcome**, and making decisions based only on point estimates is often dangerously naive.

Using the SIR model to simulate infection waves, I could clearly see how changing just a single input parameter — like infectiousness or recovery rate — can drastically shift the system. This mirrored real-world healthcare settings where slight delays or misestimates can overwhelm a clinic or hospital.

What stuck with me most was the lesson from the retail scenario: **decisions based on probability distributions aren't about predicting the future — they're about preparing for its many possible versions.** That’s how I want to lead in health tech: by building systems that are not just smart, but resilient.

> “We must stop solving for the mean and start planning for the margins.”

---

## Example Case Studies
- **SIR Epidemic Model**  
  Simulated different pandemic scenarios and evaluated hospital capacity under various beta/gamma combinations.  
  Showed that >25% of scenarios led to dangerous, high-speed peaks in infections that outpaced capacity build-up.

- **Retail Inventory Fill Rate**  
  Modeled inventory of 1000 units under uncertain demand (μ = 800, σ = 250) using a normal distribution.  
  Found that 1000 units only covers ~79% of expected scenarios; ~1212 units are needed to reach a 95% service level.

---

## Key Takeaways
- Uncertainty is better modeled with distributions, not averages
- SIR modeling demonstrates how critical small parameter changes can be in dynamic systems
- Risk pooling and scenario analysis enable better planning than fixed estimates
- Real-world decisions (from healthcare to retail) require **probabilistic thinking**, not binary assumptions

---

## Notebook: [`probability_distributions.ipynb`](./probability_distributions.ipynb) *(coming soon)*
