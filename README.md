

## 🔹 **Courier Segmentation (4 Quadrants)**

Segmented using:
- **Performance** (High/Low)
- **Distance** (High/Low)

Quadrants:
1. High Performance / Low Distance  
2. High Performance / High Distance  
3. Low Performance / Low Distance  ← ⚠️ **highest managerial concern**  
4. Low Performance / High Distance  

**Example Output Insight:**  
Only **3 couriers** had low performance because of long travel distances — indicating system assignment inefficiency.

---

## 🔹 **Segment Distribution Output**

- 27 couriers fall into **Low-Performance, Low-Distance** group →  
  *Underperforming despite easy conditions.*

These individuals should be:
- retrained  
- incentivized  
- or replaced  

---

# ⭐ **Dashboard 2 — Customer Rating & Satisfaction Dashboard**

### 🎯 Purpose  
Help **marketing managers** understand customer behavior, review sentiment, restaurant quality, and satisfaction drivers.

---

## 🔹 **Key KPIs Displayed**

- **Total Restaurants:** 4,940  
- **Total Customer Reviews:** 88,920  
- **Average Rating:** 4.11  
- **Factors Above Threshold:** (Interactive)

---

## 🔹 **Customer Segmentation (Clustering)**

Tableau auto-clustered customers into 3 groups:

| Segment | Profile |
|---------|---------|
| **Cheerleaders** | High rating & high positivity |
| **Neutrals** | High rating, low sentiment |
| **Critics** | Low rating, low sentiment |

Used to design **personalized campaigns** and **retention strategies**.

---

## 🔹 **Most Important Review Factors (Output)**

18 factors were analyzed.  
The dashboard shows % mentions + a movable threshold slider.

### **Top Factor (95% mentions):**  
### ⭐ **Food Taste**

Implication:  
Marketing should prioritize restaurants known for superior taste.

---

## 🔹 **Sentiment Coefficient Heatmap (Output)**

Correlation between each factor and overall rating:

- **Food Taste:** +0.48 (strongest predictor of rating)  
- Service, Parking, Queue, Ambience: weaker correlations  
- Price Level: slightly negative  

This helps rank what matters most to customers.

---

## 🔹 **Interactive Restaurant & Customer Insights**

Users can:
- click a segment to filter dashboards  
- explore patterns (e.g., critics avg rating = 2.57)  
- analyze restaurants with consistently high 5-star zone  
- identify dissatisfaction drivers  

---

# 🧠 **Technical Workflow**

### **Data Preparation in Tableau Prep**
- Sampled 2,000 couriers (to ensure dashboard responsiveness)
- Cleaned and standardized field names
- Removed invalid couriers (100% rejection)
- Joined review sentiment coefficients (Python → Tableau)

### **Data Quality Fixes**
- enforced consistent schema  
- validated join keys  
- removed nulls/outliers  
- ensured interactive filters & parameters updated all charts  

---

# 🔐 **Ethical Considerations**

- Courier and customer data kept **anonymized**  
- Avoided biased performance scoring  
- Ensured metrics reflect real constraints (weather, traffic, distance)  
- Recommended aggregated/role-based dashboards  

---

# 🚀 **Key Insights & Business Impact**

### **1. Delivery delays mostly occur during ARRIVAL stage → route optimization needed**  
### **2. Low-performance/low-distance couriers are the real problem → not distance-related**  
### **3. Food Taste is the #1 driver of customer satisfaction → restaurant onboarding strategy**  
### **4. Critics segment is most likely to churn → targeted recovery campaigns**  
### **5. KPI-driven BI reviews can significantly improve operational performance**

---

# 🛠️ **Tools Used**
 **Tableau Desktop**
 **Tableau Prep Builder**
 **Python (Google Colab) for sentiment coefficients**
 **Excel/CSV**
 **Figma (for visual planning)**

---

# 👨‍💻 **Authors**
- Rama Shrotri  
- Yi Wang  
- Stacey Happy  

MIS 584 – Business Intelligence  
Worcester Polytechnic Institute (WPI)







