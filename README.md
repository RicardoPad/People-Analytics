

# 🧠 How Social Support Drives Engagement and Organizational Citizenship?
### A People Analytics Study (Moderated Mediation Model)  
### Ricardo Padilla Herrera  

---

## 🎯 Objective  

Does social support influence employee engagement and organizational citizenship behavior (OCB)?

In modern organizations, understanding the drivers of engagement is critical for performance, retention, and workplace culture — they shape productivity, collaboration, and long-term organizational success. This analysis examines whether social support increases engagement, and whether this relationship depends on employees’ emotional state.

The objective is to identify **systematic behavioral drivers** and translate them into actionable HR insights.

---

## 🗃️ Dataset  

People Analytics dataset (survey-based organizational data)

| Field | Description |
|------|------------|
| Social Support (t1) | Perceived support from colleagues and supervisors |
| Engagement (t2) | Employee psychological investment in work |
| OCB (t3) | Organizational Citizenship Behavior |
| Positive Affect (t0) | Baseline emotional state |
| Controls | Age, gender, nationality, work experience |

**Structure:**  
- Temporal design: t0 → t1 → t2 → t3  
- Sample size: ~297 employees  

---

## 🧠 Conceptual Model  

Moderated mediation framework (PROCESS Model 8)

- X → M → Y  
- W moderates X → M  

Where:  
- X = Social Support  
- M = Engagement  
- Y = OCB  
- W = Positive Affect  

---

## 🔬 Methods  

- OLS Regression (PROCESS Model 8)  
- Moderated Mediation Analysis (Hayes)  
- Bootstrapping (10,000 samples)  
- Mean-centering of predictors  
- Control variables included  

---

## 📊 Analytical Approach  

- Composite variables (averages across survey items)  
- Reliability checks (Cronbach’s Alpha)  
- Assumption testing (linearity, multicollinearity)  
- PROCESS macro logic implemented in Python  

---

## 🔑 Key Findings  

- Social support positively impacts engagement  
- Engagement significantly predicts OCB  
- Positive affect strengthens the effect of social support on engagement  
- The indirect effect (Support → Engagement → OCB) is stronger for employees with higher positive affect  

---

## 💡 HR Recommendations  

**1. Strengthen Social Support Systems**  
- Peer mentoring programs  
- Manager training on emotional intelligence  
- Structured feedback culture  

**2. Invest in Emotional Well-being**  
- Psychological safety initiatives  
- Mental health support  
- Positive workplace climate interventions  

**3. Target High-Impact Segments**  
- Employees with low positive affect require tailored interventions  
- Avoid one-size-fits-all HR strategies  

**4. Use Data for Decision-Making**  
- Engagement tracking dashboards  
- Monitor leading indicators (support → engagement → behavior)  

---

## ⚠️ Limitations  

- Self-reported data (potential bias)  
- Cross-sectional design limits causal inference  
- Moderate explanatory power (R² ≈ 0.08)  

---

## 🚀 Business Impact  

This project demonstrates how People Analytics can:  

- Translate employee experience into measurable drivers  
- Identify high-impact HR interventions  
- Support evidence-based management decisions  

---

## 🛠️ Tools & Technologies  

- Python (pandas, statsmodels)  
- pyprocessmacro  
- matplotlib / seaborn  

---

## 📌 Key Takeaway  

Social support alone is not enough — its impact depends on employees’ emotional context.  
The combination of support and positive affect drives high-performance behaviors.

---

<div align="center">
  <img src="People_Analytics_Cover.jpg" width="1000" alt="People Analytics Study">
</div>
