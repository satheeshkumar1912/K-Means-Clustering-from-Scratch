# K-Means-Clustering-from-Scratch
Implementing and Analyzing K-Means Clustering from Scratch

1) Dataset Preparation
   This dataset simulates customer purchase behavior in a simple business scenario. 
   It’s intentionally designed to teach how data → decisions → predictions work.
   
   "Given a customer’s profile, can we predict whether they will purchase?"

  1. age
        - Customer’s age (21–49)
        - Proxy for life stage
        - Influences income, experience, and spending maturity

    Hidden idea: age itself doesn’t cause purchase — it correlates with other factors.

  2. experience
        - Years of work experience
        - Derived from age (not random)
        - Indicates earning stability
     
    Why it matters:  More experience → more stable income → higher purchasing power.

  4. income
        - Monthly income (₹)
        - Function of experience + noise
        - Core economic driver

    This is the strongest signal in the dataset.

  4. spend_score
        Abstract score (20–95)
        Represents:
        - Lifestyle
        - Willingness to spend
        - Consumption behavior

    Think of it as: “How likely is this person to spend money freely?”

  5. purchased (Target Variable)
        0 → Did not purchase
        1 → Purchased

    This is what your ML model tries to predict.


*The hidden logic*
The dataset follows this causal chain:

          Age
           ↓
      Experience
           ↓
        Income
           ↓
      Spend Score
           ↓
    Purchase Decision

So:
Young + low income → low spend score → no purchase
Older + stable income → high spend score → purchase

    This is designed reality, not randomness.
